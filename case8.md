# **个人案例**

**物理科学与技术学院 2017级 320170936801 徐顺豪**

关于力学一维同频振动的合成。

设有两个同频的简谐振动 S1\(t\)=A1cos\(ωt+φ1\),

S2\(t\)=A2cos\(ωt+φ2\),

求合成频率 S\(t\)=Acos\(ωt+φ\)

![](/assets/无标题2.png)

当φ1=2 φ2= 2 A1=2 A2=2 ω=2时

![](/assets/无标题.png)

XML代码

&lt;xml xmlns="\[[http://www.w3.org/1999/xhtml"&gt\]\(http://www.w3.org/1999/xhtml"&gt](http://www.w3.org/1999/xhtml"&gt]%28http://www.w3.org/1999/xhtml"&gt)\);

&lt;variables&gt;

&lt;variable type="" id="\|5zcqT}z1bO~sk,G\#\[6V"&gt;φ&lt;/variable&gt;

&lt;variable type="" id="C\#.V%LbMY@4i\|tCs!AO\_"&gt;φ1&lt;/variable&gt;

&lt;variable type="" id="uCk\)J\(f2\[FBQmG;yaEw+"&gt;φ2&lt;/variable&gt;

&lt;variable type="" id="82Q\|{{25\*5WtoFA\[Ohim"&gt;A1&lt;/variable&gt;

&lt;variable type="" id="fY\]5Aa1K%E\|nKo\#/Y?AA"&gt;A2&lt;/variable&gt;

&lt;variable type="" id="M4\[8\]Y2+,\*p$;rG4}%~t"&gt;A&lt;/variable&gt;

&lt;variable type="" id="5+!eZt\`kaO7gO0\[H;bE\["&gt;s\(t\)&lt;/variable&gt;

&lt;variable type="" id="opC%1G\|UQ\)n7\[uIRe\`a\["&gt;t&lt;/variable&gt;

&lt;variable type="" id="h0Hk\)}v8F0H\(6DubH=RM"&gt;ω&lt;/variable&gt;

&lt;variable type="" id="ms9j$8B}W3\|\*QB@t4Zz0"&gt;s1\(t\)&lt;/variable&gt;

&lt;variable type="" id="9GKIq\`GsU%K\]2o/.4^0\|"&gt;s2\(t\)&lt;/variable&gt;

&lt;variable type="" id="N$/,\`il98mF4ReVUK0:^"&gt;{textVariable}&lt;/variable&gt;

&lt;variable type="" id="\[VX1c0uH-\_^Y,-cr:~KV"&gt;项目&lt;/variable&gt;

&lt;/variables&gt;

&lt;block type="variables\_set" id="W,1$^VAOA?x{T@rg;^\`A" x="-237" y="37"&gt;

&lt;field name="VAR" id="C\#.V%LbMY@4i\|tCs!AO\_" variabletype=""&gt;φ1&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block type="math\_number" id="BE\(\[\(kpHL7\]d4bCT=G?~"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;next&gt;

&lt;block type="variables\_set" id="3rMMRt@;JL:!XcRz5qMZ"&gt;

&lt;field name="VAR" id="uCk\)J\(f2\[FBQmG;yaEw+" variabletype=""&gt;φ2&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block type="math\_number" id="oLlY}{ns40r=$NTk:~\|B"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;next&gt;

&lt;block type="variables\_set" id="@\_2,QVAN\_X\#Z%R/Hr1Xe"&gt;

&lt;field name="VAR" id="fY\]5Aa1K%E\|nKo\#/Y?AA" variabletype=""&gt;A2&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block type="math\_number" id="v77.@l4\[^GVKK}vJ-/O7"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;next&gt;

&lt;block type="variables\_set" id="{{J0bYf@6wpX$V13UD5I"&gt;

&lt;field name="VAR" id="82Q\|{{25\*5WtoFA\[Ohim" variabletype=""&gt;A1&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block type="math\_number" id="cDikp5c{\]\]?r\#\`Xy$8oz"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;next&gt;

&lt;block type="variables\_set" id=";B\]5;=LHx~}PX19\|t\)M1"&gt;

&lt;field name="VAR" id="h0Hk\)}v8F0H\(6DubH=RM" variabletype=""&gt;ω&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block type="math\_number" id="\[o$1ZBX%Px\)6caC\)naoS"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;next&gt;

&lt;block type="variables\_set" id="\_-6\|Ui1u}kI3rOIGU,s@"&gt;

&lt;field name="VAR" id="M4\[8\]Y2+,\*p$;rG4}%~t" variabletype=""&gt;A&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block type="math\_single" id="~\]0%jldyDi\[V=ptNns\*\|"&gt;

&lt;field name="OP"&gt;ROOT&lt;/field&gt;

&lt;value name="NUM"&gt;

&lt;shadow type="math\_number" id="Q\[@Z\#6I\`g!c@V2is/m!c"&gt;

&lt;field name="NUM"&gt;9&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="ePIY;rHS+hH}L2\`\#E}cT"&gt;

&lt;field name="OP"&gt;ADD&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="?5ehV?M\_B~0st\#{=2CJS"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="\*X;~6~kjKuvGb\(XENcR~"&gt;

&lt;field name="OP"&gt;MULTIPLY&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="^X{M@\]QswzeNbjcUkh=@"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="Q\]d\#Y}AJqH\`K^j14Jr7^"&gt;

&lt;field name="VAR" id="82Q\|{{25\*5WtoFA\[Ohim" variabletype=""&gt;A1&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="=46KFs1}\]?2kwLNu:81u"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="QeER!TmuP\*\(XvlKDh8Df"&gt;

&lt;field name="VAR" id="82Q\|{{25\*5WtoFA\[Ohim" variabletype=""&gt;A1&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="OM:3y0zoJA1Q^$\#{%uBH"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="pK6h^YSL2FNMM{y~s\#v5"&gt;

&lt;field name="OP"&gt;ADD&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="MsO\(a;WlTUX5\]}d8fU7z"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="ldVH!dq!gxxe!TJ8:KDp"&gt;

&lt;field name="OP"&gt;MULTIPLY&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="^X{M@\]QswzeNbjcUkh=@"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="\_+\_\)~1PJ}-HR4TuJqU/\]"&gt;

&lt;field name="VAR" id="fY\]5Aa1K%E\|nKo\#/Y?AA" variabletype=""&gt;A2&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="=46KFs1}\]?2kwLNu:81u"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="\|EkU\*t^LoL2TY}2!f6-U"&gt;

&lt;field name="VAR" id="fY\]5Aa1K%E\|nKo\#/Y?AA" variabletype=""&gt;A2&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="$yuRj%nLR\#/\*$\`s89HQl"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id=",011\)lr1v\)yz=Xjs{\|SY"&gt;

&lt;field name="OP"&gt;MULTIPLY&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="W;zopx=\_5YIR;%T~\_{wJ"&gt;

&lt;field name="NUM"&gt;2&lt;/field&gt;

&lt;/shadow&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="IkQ.mLK2\(c.Uh\_F4@+\_a"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="+aZ03IIJN,TYb\#UQ/QEU"&gt;

&lt;field name="OP"&gt;MULTIPLY&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="Fnb\`,9g?^$q:xL\(J^b=7"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="rpRRPY3-W8@B=~xc-C\]b"&gt;

&lt;field name="VAR" id="82Q\|{{25\*5WtoFA\[Ohim" variabletype=""&gt;A1&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="%t@6vywyzbYOFhxX%\)\#X"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="Ehf^\_paAiEQ2Mu{c8n=:"&gt;

&lt;field name="OP"&gt;MULTIPLY&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="kwb\`Tg6{l\)CYEzAJG,j/"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="Z%U,-$\)mj,\[5fcUEG9;G"&gt;

&lt;field name="VAR" id="fY\]5Aa1K%E\|nKo\#/Y?AA" variabletype=""&gt;A2&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="T4}Barkk=\`\(KXBq\_;0Qn"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_trig" id="Z3\_uy^\)Axm{eN\(6O\(^y1"&gt;

&lt;field name="OP"&gt;COS&lt;/field&gt;

&lt;value name="NUM"&gt;

&lt;shadow type="math\_number" id="utL1D?5ov;x80D4s\(\)dJ"&gt;

&lt;field name="NUM"&gt;45&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="\)+olnTXlN.OEXF64B5?\)"&gt;

&lt;field name="OP"&gt;MINUS&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="x\#t%l7}RJ=v?P:tWAQ7P"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="r^l\)\#:g3\)$NK}?FhMFhM"&gt;

&lt;field name="VAR" id="uCk\)J\(f2\[FBQmG;yaEw+" variabletype=""&gt;φ2&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="c\*ZxF\]\_O4Tr\)\(zPA:AM/"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="xiL/p=zN\_\`i}XfvP\*1b+"&gt;

&lt;field name="VAR" id="C\#.V%LbMY@4i\|tCs!AO\_" variabletype=""&gt;φ1&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;next&gt;

&lt;block type="variables\_set" id="vmS}g^\*h9N\#sH~\(}uT,!"&gt;

&lt;field name="VAR" id="\|5zcqT}z1bO~sk,G\#\[6V" variabletype=""&gt;φ&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block type="math\_trig" id=";0M4n{Ry=j-ZFuVHwe!n"&gt;

&lt;field name="OP"&gt;ATAN&lt;/field&gt;

&lt;value name="NUM"&gt;

&lt;shadow type="math\_number" id="aQ\`XOLoY+C%\#7o^+{j8^"&gt;

&lt;field name="NUM"&gt;45&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="\*N\].NkGEx\|ZH\#cDMKe^N"&gt;

&lt;field name="OP"&gt;ADD&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="9qe\)rj0joQzDheDS\),cB"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="-L\`a-M?3UlfL\);T:PM?v"&gt;

&lt;field name="OP"&gt;ADD&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="k1c^qP6R^zOm\_~dU;LhM"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="wYmi;QAbls\(\|A~\(y}q$H"&gt;

&lt;field name="OP"&gt;MULTIPLY&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="1Un@QS6~%NbRvl-Y8z9@"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="\*\_Sxco4aH+/=C9wej6Ta"&gt;

&lt;field name="VAR" id="82Q\|{{25\*5WtoFA\[Ohim" variabletype=""&gt;A1&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="D3s?v{E\*5\*csMPF\[\)!!~"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_trig" id="d7s\*+:EI8S4aj/y7!JL,"&gt;

&lt;field name="OP"&gt;SIN&lt;/field&gt;

&lt;value name="NUM"&gt;

&lt;shadow type="math\_number" id="3Lyx^GL\[!\|:+Nt7k;\)FO"&gt;

&lt;field name="NUM"&gt;45&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="qy3aP6bYvHqBI\[yGvRY}"&gt;

&lt;field name="VAR" id="C\#.V%LbMY@4i\|tCs!AO\_" variabletype=""&gt;φ1&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="$64vmAQE5u%m\|\]Mt\[Spd"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="Y\[qk1eb^j6JGe~p?T^z-"&gt;

&lt;field name="OP"&gt;MULTIPLY&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="YsJR}p,LBjvZ.9zZoR97"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="$;Xt@}!Rx~\_\`!pe@WK2:"&gt;

&lt;field name="VAR" id="fY\]5Aa1K%E\|nKo\#/Y?AA" variabletype=""&gt;A2&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="s{u2SuTksblrXB?K+TDC"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_trig" id="lG3:+HJF^\[oPrA9W1+Y\|"&gt;

&lt;field name="OP"&gt;SIN&lt;/field&gt;

&lt;value name="NUM"&gt;

&lt;shadow type="math\_number" id="YS8:Zp5\|$m0}5.o5Q1ih"&gt;

&lt;field name="NUM"&gt;45&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="N39XHdBH~2S-!yB9+l\[."&gt;

&lt;field name="VAR" id="uCk\)J\(f2\[FBQmG;yaEw+" variabletype=""&gt;φ2&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="fx6jW\)OzKu9@r}MpOWNe"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="=JF~b\(5gPxN}mvo\|AI7W"&gt;

&lt;field name="OP"&gt;ADD&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="k1c^qP6R^zOm\_~dU;LhM"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="5y-Iuj2Y!h\)P\`/uK}D?\["&gt;

&lt;field name="OP"&gt;MULTIPLY&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="1Un@QS6~%NbRvl-Y8z9@"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="-VNs;Z:~,PK1-r@Yf+sA"&gt;

&lt;field name="VAR" id="82Q\|{{25\*5WtoFA\[Ohim" variabletype=""&gt;A1&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="D3s?v{E\*5\*csMPF\[\)!!~"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_trig" id="gQRtB@J\(uoS{{NwVl/z."&gt;

&lt;field name="OP"&gt;COS&lt;/field&gt;

&lt;value name="NUM"&gt;

&lt;shadow type="math\_number" id="3Lyx^GL\[!\|:+Nt7k;\)FO"&gt;

&lt;field name="NUM"&gt;45&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id=";Q@?xXM?z7g\*+s.9Lc/E"&gt;

&lt;field name="VAR" id="C\#.V%LbMY@4i\|tCs!AO\_" variabletype=""&gt;φ1&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="$64vmAQE5u%m\|\]Mt\[Spd"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="Yu9hI6z+m56jZ6ODtt}j"&gt;

&lt;field name="OP"&gt;MULTIPLY&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="YsJR}p,LBjvZ.9zZoR97"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="Gaj\)zeGw\|}wDyLnyJw~$"&gt;

&lt;field name="VAR" id="fY\]5Aa1K%E\|nKo\#/Y?AA" variabletype=""&gt;A2&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="s{u2SuTksblrXB?K+TDC"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_trig" id="YFF$\_AYV\|r{UHiY}Aek\("&gt;

&lt;field name="OP"&gt;COS&lt;/field&gt;

&lt;value name="NUM"&gt;

&lt;shadow type="math\_number" id="YS8:Zp5\|$m0}5.o5Q1ih"&gt;

&lt;field name="NUM"&gt;45&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="7woPq25p5\#5tm\(m%U}JJ"&gt;

&lt;field name="VAR" id="uCk\)J\(f2\[FBQmG;yaEw+" variabletype=""&gt;φ2&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;next&gt;

&lt;block type="text\_print" id="/VN:-Kq\(3M%Lh\)7H{Z3+"&gt;

&lt;value name="TEXT"&gt;

&lt;shadow type="text" id="\),MA3pr}hcJlq5k,hbj5"&gt;

&lt;field name="TEXT"&gt;abc&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="text\_join" id="1{~NE!Nj6sy\*SO$tgXJY"&gt;

&lt;mutation items="8"&gt;&lt;/mutation&gt;

&lt;value name="ADD0"&gt;

&lt;block type="variables\_get" id="im}\#z\)\|=sHQZ59K2z94H"&gt;

&lt;field name="VAR" id="M4\[8\]Y2+,\*p$;rG4}%~t" variabletype=""&gt;A&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="ADD1"&gt;

&lt;block type="text" id="jTA!Av5p8ps9\#8A3nIHD"&gt;

&lt;field name="TEXT"&gt;cos&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="ADD2"&gt;

&lt;block type="text" id="kHa2l39$jOUrb9tBWGYa"&gt;

&lt;field name="TEXT"&gt;\(&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="ADD3"&gt;

&lt;block type="variables\_get" id=":C\[e583d;ILM:Y0vL1I-"&gt;

&lt;field name="VAR" id="h0Hk\)}v8F0H\(6DubH=RM" variabletype=""&gt;ω&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="ADD4"&gt;

&lt;block type="text" id="?DGuLG\*TRPx$y:.$mR%k"&gt;

&lt;field name="TEXT"&gt;t&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="ADD5"&gt;

&lt;block type="text" id="m\_X/\[%0pJ\_GtNUP7\(Njr"&gt;

&lt;field name="TEXT"&gt;+&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="ADD6"&gt;

&lt;block type="variables\_get" id=".:DR\_Ri~K{!Y6+!/Q0E2"&gt;

&lt;field name="VAR" id="\|5zcqT}z1bO~sk,G\#\[6V" variabletype=""&gt;φ&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="ADD7"&gt;

&lt;block type="text" id="5=vz\`IKkS:!-/R$f$FLb"&gt;

&lt;field name="TEXT"&gt;\)&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

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

&lt;/next&gt;

&lt;/block&gt;

&lt;/next&gt;

&lt;/block&gt;

&lt;/xml&gt;

