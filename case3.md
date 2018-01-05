学院：2017级物理科学与技术学院         学号：320170936691   姓名：谢浩



用此方块判断本月是自己出生的第几个月，在year后输入今年的年份，在month输入本月是今年的第几个月，在yearofbirth输入自己的出生年份，在monthofbirth输入自己的出生月份，然后得到结果。

# **blockly模块                      **

# ![](/assets/图片1.png)**运行结果图**![](/assets/图片2.png)

# ![](/assets/图片2.png)![](/assets/图片3.png)![](/assets/图片4.png)![](/assets/图片5.png)**XML代码**

&lt;xml xmlns="[http://www.w3.org/1999/xhtml"&gt](http://www.w3.org/1999/xhtml"&gt);

&lt;variables&gt;

&lt;variable type="" id="\|6OoZ\|;!DA9^tB{pr+%d"&gt;year&lt;/variable&gt;

&lt;variable type="" id="\|jZ\*@\)2bg?G^\]L;u.-/-"&gt;month&lt;/variable&gt;

&lt;variable type="" id="be9%z2b8R\]79\(1KVYXq5"&gt;year of birth&lt;/variable&gt;

&lt;variable type="" id="-J\(abjt2z?kgc\|pV}tHq"&gt;month of birth&lt;/variable&gt;

&lt;variable type="" id="PWaG\`2\#SmdNf}+a%~Ge9"&gt;yue&lt;/variable&gt;

&lt;/variables&gt;

&lt;block type="variables\_set" id="FS%0\*N4!\(P\_\(}K\*==V1:" x="313" y="113"&gt;

&lt;field name="VAR" id="\|6OoZ\|;!DA9^tB{pr+%d" variabletype=""&gt;year&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block type="text\_prompt\_ext" id="\#=\(:.qCdEZ}vT\[v\*WzVS"&gt;

&lt;mutation type="NUMBER"&gt;&lt;/mutation&gt;

&lt;field name="TYPE"&gt;NUMBER&lt;/field&gt;

&lt;value name="TEXT"&gt;

&lt;shadow type="text" id="}VnLZrB8mbKxP89yk\|Kj"&gt;

&lt;field name="TEXT"&gt;&lt;/field&gt;

&lt;/shadow&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;next&gt;

&lt;block type="variables\_set" id="o\|o!M,C4=.hHA6IH@T8%"&gt;

&lt;field name="VAR" id="\|jZ\*@\)2bg?G^\]L;u.-/-" variabletype=""&gt;month&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block type="text\_prompt\_ext" id="G5hOjnFK,s90oB9vrMJ@"&gt;

&lt;mutation type="NUMBER"&gt;&lt;/mutation&gt;

&lt;field name="TYPE"&gt;NUMBER&lt;/field&gt;

&lt;value name="TEXT"&gt;

&lt;shadow type="text" id="fMm9\_1\|\#TE\#,PbC}l%St"&gt;

&lt;field name="TEXT"&gt;&lt;/field&gt;

&lt;/shadow&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;next&gt;

&lt;block type="variables\_set" id="@vE;@4nDSj4pn-Dgu6Ay"&gt;

&lt;field name="VAR" id="be9%z2b8R\]79\(1KVYXq5" variabletype=""&gt;year of birth&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block type="text\_prompt\_ext" id="ffOYZ@\)PXj30b:?a52~9"&gt;

&lt;mutation type="NUMBER"&gt;&lt;/mutation&gt;

&lt;field name="TYPE"&gt;NUMBER&lt;/field&gt;

&lt;value name="TEXT"&gt;

&lt;shadow type="text" id="r~I\(JzRY0:0U\|R:OZv!p"&gt;

&lt;field name="TEXT"&gt;&lt;/field&gt;

&lt;/shadow&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;next&gt;

&lt;block type="variables\_set" id="U/\_Z75~JA5-PG+^/itl7"&gt;

&lt;field name="VAR" id="-J\(abjt2z?kgc\|pV}tHq" variabletype=""&gt;month of birth&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block type="text\_prompt\_ext" id="Nr\]\]wg\*ZqplnFUoYVU4;"&gt;

&lt;mutation type="NUMBER"&gt;&lt;/mutation&gt;

&lt;field name="TYPE"&gt;NUMBER&lt;/field&gt;

&lt;value name="TEXT"&gt;

&lt;shadow type="text" id="EIaN5=TWU\#\|VWMg{j2wc"&gt;

&lt;field name="TEXT"&gt;&lt;/field&gt;

&lt;/shadow&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;next&gt;

&lt;block type="variables\_set" id="Fvp:DT/flSLWwll\|q\_f;"&gt;

&lt;field name="VAR" id="PWaG\`2\#SmdNf}+a%~Ge9" variabletype=""&gt;yue&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block type="math\_arithmetic" id="k-Zd\*x9jpE\#jMKF^n,\]2"&gt;

&lt;field name="OP"&gt;ADD&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="\_R\#WAJar+E\`\_bl.3r$Wt"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="nZq4Y\]NaKY-=\]l}F/jKb"&gt;

&lt;field name="OP"&gt;ADD&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="H2,l-M?{\]ir/OGS:S,/N"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="AppjnA\]T\)6g7jqgBLj,D"&gt;

&lt;field name="OP"&gt;MULTIPLY&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="3c3\`zA\#MsT\#\[t:NF;\_-j"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="!\*9qvYlM@rG+/Mq-F\*u9"&gt;

&lt;field name="OP"&gt;MINUS&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="\`%FBPruaK-q5RPx\)wM,3"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="\]rp;m8AhJ-Z8?IP;\[$\*S"&gt;

&lt;field name="OP"&gt;MINUS&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="4Sq$/Y.kK\|::3eUI2GJp"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="E\*;tl;F\[z/:ct2D\`O;B$"&gt;

&lt;field name="VAR" id="\|6OoZ\|;!DA9^tB{pr+%d" variabletype=""&gt;year&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="q0Y+gEt\|\_.\(q\`?D2u\)0;"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="gnY4f/w+%$pz8j{zqV+y"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="x4\*=$f7\*AUXjT\#\_l.n\|t"&gt;

&lt;field name="VAR" id="be9%z2b8R\]79\(1KVYXq5" variabletype=""&gt;year of birth&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="zb;b0YdV\#56mX1z-ih;,"&gt;

&lt;field name="NUM"&gt;12&lt;/field&gt;

&lt;/shadow&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="pG^hvK;MwbSXD$gU\`U1J"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="Fa\)=9uTci%uX4\[0dRra1"&gt;

&lt;field name="OP"&gt;MINUS&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="dPYcUT.,JML9LKFep%.y"&gt;

&lt;field name="NUM"&gt;12&lt;/field&gt;

&lt;/shadow&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="\(Z;\|NN-QKlrTYy/9yBEM"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="10PY9%E1NKT!u/7LBF\#1"&gt;

&lt;field name="VAR" id="-J\(abjt2z?kgc\|pV}tHq" variabletype=""&gt;month of birth&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="3p\*5b!\)\_I1xNFf\|A\|Ncq"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="ryI.@D-R3eHtrkk2\]KV,"&gt;

&lt;field name="VAR" id="\|jZ\*@\)2bg?G^\]L;u.-/-" variabletype=""&gt;month&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;next&gt;

&lt;block type="text\_print" id="i=R4yGs\|n6eOJSU\];,xj"&gt;

&lt;value name="TEXT"&gt;

&lt;shadow type="text" id="Ueyt+q:ht/\`SIBi\(Kttw"&gt;

&lt;field name="TEXT"&gt;abc&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="~sR\*3=G9zn\]z8~5}fRY5"&gt;

&lt;field name="VAR" id="PWaG\`2\#SmdNf}+a%~Ge9" variabletype=""&gt;yue&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/next&gt;

&lt;/block&gt;

&lt;/next&gt;

&lt;/block&gt;

&lt;/next&gt;

&lt;/block&gt;

&lt;/next&gt;

&lt;/block&gt;

&lt;/next&gt;

&lt;/block&gt;

&lt;/xml&gt;

