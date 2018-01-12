                        Blockly案例-石头剪刀布三局两胜制

1.案例说明：按石头剪刀布的顺序分别为1、2、3，computer gesture代表电脑出的手势，player gesture代表玩家手势，Result表示玩家获胜的局；x表示一个任意值，例如，x=2，代表电脑胜利，如布【3】胜石头【1】；x=0,代表平局，如布【3】与布【3】平局；x=其他值，代表玩家胜利，如剪刀【2】输石头【1】。

2.Blockly块

![](/assets/import.png)

    

3.操作和结果

![](/assets/import1.png)



![](/assets/import2.png)

![](/assets/import3.png)

4.XML代码

&lt;xml xmlns="http://www.w3.org/1999/xhtml"&gt;

  &lt;variables&gt;

    &lt;variable type="" id="\`vsz{}kNbZN?V2\#Q\|\[vH"&gt;computer gesture&lt;/variable&gt;

    &lt;variable type="" id="\*O9Y\]Bm6pWsex@=OvU2L"&gt;player gesture&lt;/variable&gt;

    &lt;variable type="" id="7q\#-TUy~;N}0Fn9DAP\`I"&gt;x&lt;/variable&gt;

    &lt;variable type="" id="J@C\_WEo3=ka\_{b{yuh/."&gt;Result&lt;/variable&gt;

  &lt;/variables&gt;

  &lt;block type="variables\_set" id="wn\]\|s\(Rx1ZVJB-cLi2OI" x="163" y="13"&gt;

    &lt;field name="VAR" id="\`vsz{}kNbZN?V2\#Q\|\[vH" variabletype=""&gt;computer gesture&lt;/field&gt;

    &lt;value name="VALUE"&gt;

      &lt;block type="math\_number" id="woL-k^R,\#N\*\#!=8t-SaL"&gt;

        &lt;field name="NUM"&gt;0&lt;/field&gt;

      &lt;/block&gt;

    &lt;/value&gt;

    &lt;next&gt;

      &lt;block type="controls\_repeat\_ext" id="x$Qox{7Aw\|}1YmCOcoVD"&gt;

        &lt;value name="TIMES"&gt;

          &lt;shadow type="math\_number" id="dMDSWgO5jtIHDPsT8Fx$"&gt;

            &lt;field name="NUM"&gt;2&lt;/field&gt;

          &lt;/shadow&gt;

        &lt;/value&gt;

        &lt;statement name="DO"&gt;

          &lt;block type="variables\_set" id="I9CeL~:Nbd.sn\[:cnf:}"&gt;

            &lt;field name="VAR" id="\`vsz{}kNbZN?V2\#Q\|\[vH" variabletype=""&gt;computer gesture&lt;/field&gt;

            &lt;value name="VALUE"&gt;

              &lt;block type="math\_random\_int" id="9VC2%QwDQU;\|Z-iPCLem"&gt;

                &lt;value name="FROM"&gt;

                  &lt;shadow type="math\_number" id="a{-a?dw.+q0j\`ViQ/y\(\_"&gt;

                    &lt;field name="NUM"&gt;1&lt;/field&gt;

                  &lt;/shadow&gt;

                &lt;/value&gt;

                &lt;value name="TO"&gt;

                  &lt;shadow type="math\_number" id=":%Xhm\*u!;.xjby8L5~rN"&gt;

                    &lt;field name="NUM"&gt;3&lt;/field&gt;

                  &lt;/shadow&gt;

                &lt;/value&gt;

              &lt;/block&gt;

            &lt;/value&gt;

            &lt;next&gt;

              &lt;block type="variables\_set" id="Nf!eX?{\(9g~l%6\)C\]t}R"&gt;

                &lt;field name="VAR" id="\*O9Y\]Bm6pWsex@=OvU2L" variabletype=""&gt;player gesture&lt;/field&gt;

                &lt;value name="VALUE"&gt;

                  &lt;block type="text\_prompt\_ext" id="k0+wU\|-\]s\(bc,uE@XL\_d"&gt;

                    &lt;mutation type="TEXT"&gt;&lt;/mutation&gt;

                    &lt;field name="TYPE"&gt;TEXT&lt;/field&gt;

                    &lt;value name="TEXT"&gt;

                      &lt;shadow type="text" id="\`hVX\_C5^n\]~833bZ;k\|T"&gt;

                        &lt;field name="TEXT"&gt;请输入玩家手势&lt;/field&gt;

                      &lt;/shadow&gt;

                    &lt;/value&gt;

                  &lt;/block&gt;

                &lt;/value&gt;

                &lt;next&gt;

                  &lt;block type="variables\_set" id="I=/iauePnQN\(U7QP6bi\|"&gt;

                    &lt;field name="VAR" id="7q\#-TUy~;N}0Fn9DAP\`I" variabletype=""&gt;x&lt;/field&gt;

                    &lt;value name="VALUE"&gt;

                      &lt;block type="math\_arithmetic" id="GqKN%4ctS~Sj.ZKQT7pD"&gt;

                        &lt;field name="OP"&gt;MINUS&lt;/field&gt;

                        &lt;value name="A"&gt;

                          &lt;shadow type="math\_number" id="a:IOWu+wbTwwA7H}0:RO"&gt;

                            &lt;field name="NUM"&gt;1&lt;/field&gt;

                          &lt;/shadow&gt;

                          &lt;block type="variables\_get" id="J\|m\|Uu^+NI\[6E\`\(dZ~Z/"&gt;

                            &lt;field name="VAR" id="\`vsz{}kNbZN?V2\#Q\|\[vH" variabletype=""&gt;computer gesture&lt;/field&gt;

                          &lt;/block&gt;

                        &lt;/value&gt;

                        &lt;value name="B"&gt;

                          &lt;shadow type="math\_number" id="pH%9nW6D@JO}F3.b\|O}+"&gt;

                            &lt;field name="NUM"&gt;1&lt;/field&gt;

                          &lt;/shadow&gt;

                          &lt;block type="variables\_get" id="=;4\(%\`t7\]N+.7BG=1DFx"&gt;

                            &lt;field name="VAR" id="\*O9Y\]Bm6pWsex@=OvU2L" variabletype=""&gt;player gesture&lt;/field&gt;

                          &lt;/block&gt;

                        &lt;/value&gt;

                      &lt;/block&gt;

                    &lt;/value&gt;

                    &lt;next&gt;

                      &lt;block type="controls\_if" id="+XNpU43\):6~.\`.QYVXdG"&gt;

                        &lt;value name="IF0"&gt;

                          &lt;block type="logic\_compare" id="$7hAoBD.+?5{\)LT4.bO8"&gt;

                            &lt;field name="OP"&gt;EQ&lt;/field&gt;

                            &lt;value name="A"&gt;

                              &lt;block type="variables\_get" id="q8uy+-ZVhtsAA\[,}ZH5Z"&gt;

                                &lt;field name="VAR" id="7q\#-TUy~;N}0Fn9DAP\`I" variabletype=""&gt;x&lt;/field&gt;

                              &lt;/block&gt;

                            &lt;/value&gt;

                            &lt;value name="B"&gt;

                              &lt;block type="math\_number" id=".z+sqHgb1:7xXJCD,CbW"&gt;

                                &lt;field name="NUM"&gt;2&lt;/field&gt;

                              &lt;/block&gt;

                            &lt;/value&gt;

                          &lt;/block&gt;

                        &lt;/value&gt;

                        &lt;statement name="DO0"&gt;

                          &lt;block type="variables\_set" id="\_3ShBFhYXs+rz7T9+0t\|"&gt;

                            &lt;field name="VAR" id="J@C\_WEo3=ka\_{b{yuh/." variabletype=""&gt;Result&lt;/field&gt;

                            &lt;value name="VALUE"&gt;

                              &lt;block type="math\_arithmetic" id="\#U4DJDtkmR6XG\#\*hZ~R\)"&gt;

                                &lt;field name="OP"&gt;ADD&lt;/field&gt;

                                &lt;value name="A"&gt;

                                  &lt;shadow type="math\_number" id="=7V2tnV/\`\[\[l8B~7r{rG"&gt;

                                    &lt;field name="NUM"&gt;1&lt;/field&gt;

                                  &lt;/shadow&gt;

                                  &lt;block type="variables\_get" id="i6Kn+qVqWmT9\[J$b\[:^="&gt;

                                    &lt;field name="VAR" id="J@C\_WEo3=ka\_{b{yuh/." variabletype=""&gt;Result&lt;/field&gt;

                                  &lt;/block&gt;

                                &lt;/value&gt;

                                &lt;value name="B"&gt;

                                  &lt;shadow type="math\_number" id="jlJD9=up\(\#SZ$5sKCX}E"&gt;

                                    &lt;field name="NUM"&gt;1&lt;/field&gt;

                                  &lt;/shadow&gt;

                                &lt;/value&gt;

                              &lt;/block&gt;

                            &lt;/value&gt;

                          &lt;/block&gt;

                        &lt;/statement&gt;

                      &lt;/block&gt;

                    &lt;/next&gt;

                  &lt;/block&gt;

                &lt;/next&gt;

              &lt;/block&gt;

            &lt;/next&gt;

          &lt;/block&gt;

        &lt;/statement&gt;

        &lt;next&gt;

          &lt;block type="controls\_if" id="vb\_r\_JhXSaUtZD^7p\|\`D"&gt;

            &lt;mutation else="1"&gt;&lt;/mutation&gt;

            &lt;value name="IF0"&gt;

              &lt;block type="logic\_compare" id="^oid$\|Df$fUm^oRyh?R7"&gt;

                &lt;field name="OP"&gt;EQ&lt;/field&gt;

                &lt;value name="A"&gt;

                  &lt;block type="variables\_get" id="4\]E!/$~C0$r3$i0sV4c6"&gt;

                    &lt;field name="VAR" id="J@C\_WEo3=ka\_{b{yuh/." variabletype=""&gt;Result&lt;/field&gt;

                  &lt;/block&gt;

                &lt;/value&gt;

                &lt;value name="B"&gt;

                  &lt;block type="math\_number" id="0SdGWH\(hWm\`nkq\#S1~ll"&gt;

                    &lt;field name="NUM"&gt;2&lt;/field&gt;

                  &lt;/block&gt;

                &lt;/value&gt;

              &lt;/block&gt;

            &lt;/value&gt;

            &lt;statement name="DO0"&gt;

              &lt;block type="text\_print" id="J\[Q{fwZKQlVo%,\|!qzFJ"&gt;

                &lt;value name="TEXT"&gt;

                  &lt;shadow type="text" id="XQ6a\]kIELaT\#qM9\*hNmL"&gt;

                    &lt;field name="TEXT"&gt;you win&lt;/field&gt;

                  &lt;/shadow&gt;

                &lt;/value&gt;

              &lt;/block&gt;

            &lt;/statement&gt;

            &lt;statement name="ELSE"&gt;

              &lt;block type="variables\_set" id="SA^BG-CdCE..3\]BgRQK\*"&gt;

                &lt;field name="VAR" id="\`vsz{}kNbZN?V2\#Q\|\[vH" variabletype=""&gt;computer gesture&lt;/field&gt;

                &lt;value name="VALUE"&gt;

                  &lt;block type="math\_random\_int" id="N\`6\*}AS;Ojer+/{6BO:+"&gt;

                    &lt;value name="FROM"&gt;

                      &lt;shadow type="math\_number" id="!oNjpAKvSUE9ke\|\#a~os"&gt;

                        &lt;field name="NUM"&gt;1&lt;/field&gt;

                      &lt;/shadow&gt;

                    &lt;/value&gt;

                    &lt;value name="TO"&gt;

                      &lt;shadow type="math\_number" id="\]=zmaWxrn$}Xu1tD\_3\`R"&gt;

                        &lt;field name="NUM"&gt;3&lt;/field&gt;

                      &lt;/shadow&gt;

                    &lt;/value&gt;

                  &lt;/block&gt;

                &lt;/value&gt;

                &lt;next&gt;

                  &lt;block type="variables\_set" id="iB}bHn2@sX,Us1VVv?v@"&gt;

                    &lt;field name="VAR" id="\*O9Y\]Bm6pWsex@=OvU2L" variabletype=""&gt;player gesture&lt;/field&gt;

                    &lt;value name="VALUE"&gt;

                      &lt;block type="text\_prompt\_ext" id="fMHbJiCf\(.\]Z\|\`vj-n\(6"&gt;

                        &lt;mutation type="TEXT"&gt;&lt;/mutation&gt;

                        &lt;field name="TYPE"&gt;TEXT&lt;/field&gt;

                        &lt;value name="TEXT"&gt;

                          &lt;shadow type="text" id="0f55S0O:9B\_\|vS,49rWz"&gt;

                            &lt;field name="TEXT"&gt;请输入玩家手势&lt;/field&gt;

                          &lt;/shadow&gt;

                        &lt;/value&gt;

                      &lt;/block&gt;

                    &lt;/value&gt;

                    &lt;next&gt;

                      &lt;block type="variables\_set" id="=yKZ\*sB.P6fIdgt?zF\]g"&gt;

                        &lt;field name="VAR" id="7q\#-TUy~;N}0Fn9DAP\`I" variabletype=""&gt;x&lt;/field&gt;

                        &lt;value name="VALUE"&gt;

                          &lt;block type="math\_arithmetic" id="Zf3s9QKHEX-Fctp2Rm\_+"&gt;

                            &lt;field name="OP"&gt;MINUS&lt;/field&gt;

                            &lt;value name="A"&gt;

                              &lt;shadow type="math\_number" id="\[6FbcpLsYW\[VTc5L\*!\_I"&gt;

                                &lt;field name="NUM"&gt;1&lt;/field&gt;

                              &lt;/shadow&gt;

                              &lt;block type="variables\_get" id="IdC\|VyuL@/\*e\|RGm;{-e"&gt;

                                &lt;field name="VAR" id="\`vsz{}kNbZN?V2\#Q\|\[vH" variabletype=""&gt;computer gesture&lt;/field&gt;

                              &lt;/block&gt;

                            &lt;/value&gt;

                            &lt;value name="B"&gt;

                              &lt;shadow type="math\_number" id="}Yvll-3H%,-S0zN\(sNP\#"&gt;

                                &lt;field name="NUM"&gt;1&lt;/field&gt;

                              &lt;/shadow&gt;

                              &lt;block type="variables\_get" id="0J%g^WW5\*Vt$q6CoB}{0"&gt;

                                &lt;field name="VAR" id="\*O9Y\]Bm6pWsex@=OvU2L" variabletype=""&gt;player gesture&lt;/field&gt;

                              &lt;/block&gt;

                            &lt;/value&gt;

                          &lt;/block&gt;

                        &lt;/value&gt;

                        &lt;next&gt;

                          &lt;block type="controls\_if" id="b;l.3F/:CGzYw{qwQ\(DJ"&gt;

                            &lt;mutation else="1"&gt;&lt;/mutation&gt;

                            &lt;value name="IF0"&gt;

                              &lt;block type="logic\_compare" id="oTv35LZKGwwNDq\(7usah"&gt;

                                &lt;field name="OP"&gt;EQ&lt;/field&gt;

                                &lt;value name="A"&gt;

                                  &lt;block type="variables\_get" id="/f{\_e~,\_wbWLAp%\*Xb6~"&gt;

                                    &lt;field name="VAR" id="7q\#-TUy~;N}0Fn9DAP\`I" variabletype=""&gt;x&lt;/field&gt;

                                  &lt;/block&gt;

                                &lt;/value&gt;

                                &lt;value name="B"&gt;

                                  &lt;block type="math\_number" id="\)L$WrLsw{4\|$R:/-3ZGq"&gt;

                                    &lt;field name="NUM"&gt;-1&lt;/field&gt;

                                  &lt;/block&gt;

                                &lt;/value&gt;

                              &lt;/block&gt;

                            &lt;/value&gt;

                            &lt;statement name="DO0"&gt;

                              &lt;block type="text\_print" id="}EJ-tg\_EtC\*u\#R%dS^CY"&gt;

                                &lt;value name="TEXT"&gt;

                                  &lt;shadow type="text" id="\[lu@jlH/r=\`FA\(O^tWEc"&gt;

                                    &lt;field name="TEXT"&gt;you win&lt;/field&gt;

                                  &lt;/shadow&gt;

                                &lt;/value&gt;

                              &lt;/block&gt;

                            &lt;/statement&gt;

                            &lt;statement name="ELSE"&gt;

                              &lt;block type="text\_print" id="\*hv}afr15m4k,8no\|X78"&gt;

                                &lt;value name="TEXT"&gt;

                                  &lt;shadow type="text" id="yX:-j\`yWIX46e~v4lPNA"&gt;

                                    &lt;field name="TEXT"&gt;computer win&lt;/field&gt;

                                  &lt;/shadow&gt;

                                &lt;/value&gt;

                              &lt;/block&gt;

                            &lt;/statement&gt;

                          &lt;/block&gt;

                        &lt;/next&gt;

                      &lt;/block&gt;

                    &lt;/next&gt;

                  &lt;/block&gt;

                &lt;/next&gt;

              &lt;/block&gt;

            &lt;/statement&gt;

          &lt;/block&gt;

        &lt;/next&gt;

      &lt;/block&gt;

    &lt;/next&gt;

  &lt;/block&gt;

&lt;/xml&gt;

