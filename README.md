# ScreenSizeUtil
# Examples
<div><br />
<div><span>class</span><span> </span><span>MyApp</span><span> </span><span>extends</span><span> </span><span>StatelessWidget</span><span> {</span></div>
<div><span>&nbsp; </span><span>const</span><span> </span><span>MyApp</span><span>({</span><span>super</span><span>.</span><span>key</span><span>});</span></div>
<br />
<div><span>&nbsp; </span><span>// This widget is the root of your application.</span></div>
<div><span>&nbsp; </span><span>@</span><span>override</span></div>
<div><span>&nbsp; </span><span>Widget</span><span> </span><span>build</span><span>(</span><span>BuildContext</span><span> </span><span>context</span><span>) {</span></div>
<div><span>&nbsp; &nbsp; </span><span>return</span><span> </span><span>ScreenSizeUtilInit</span><span>(</span></div>
<div><span>&nbsp; &nbsp; &nbsp; </span><span>designSize</span><span>: </span><span>const</span><span> </span><span>Size</span><span>(</span><span>320</span><span>, </span><span>812</span><span>),</span></div>
<div><span>&nbsp; &nbsp; &nbsp; </span><span>minTextAdapt</span><span>: </span><span>true</span><span>,</span></div>
<div><span>&nbsp; &nbsp; &nbsp; </span><span>splitScreenMode</span><span>: </span><span>true</span><span>,</span></div>
<div><span>&nbsp; &nbsp; &nbsp; </span><span>builder</span><span>: (</span><span>context</span><span>, </span><span>state</span><span>) {</span></div>
<div><span>&nbsp; &nbsp; &nbsp; &nbsp; </span><span>return</span><span> </span><span>MaterialApp</span><span>(</span></div>
<div><span>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; </span><span>title</span><span>: </span><span>'Flutter Demo'</span><span>,</span></div>
<div><span>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; </span><span>theme</span><span>: </span><span>ThemeData</span><span>(</span></div>
<div><span>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; </span><span>primarySwatch</span><span>: </span><span>Colors</span><span>.</span><span>blue</span><span>,</span></div>
<div><span>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ),</span></div>
<div><span>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; </span><span>home</span><span>: </span><span>const</span><span> </span><span>MainPage</span><span>(),</span></div>
<div><span>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; </span><span>builder</span><span>: (</span><span>BuildContext</span><span> </span><span>context</span><span>, </span><span>Widget</span><span>? </span><span>child</span><span>) {</span></div>
<div><span>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; </span><span>return</span><span> </span><span>MediaQuery</span><span>(</span></div>
<div><span>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; </span><span>data</span><span>: </span><span>MediaQuery</span><span>.</span><span>of</span><span>(</span><span>context</span><span>).</span><span>copyWith</span><span>(</span><span>textScaleFactor</span><span>: </span><span>1</span><span>),</span></div>
<div><span>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; </span><span>child</span><span>: </span><span>child</span><span>!,</span></div>
<div><span>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; );</span></div>
<div><span>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; },</span></div>
<div><span>&nbsp; &nbsp; &nbsp; &nbsp; );</span></div>
<div><span>&nbsp; &nbsp; &nbsp; },</span></div>
<div><span>&nbsp; &nbsp; );</span></div>
<div><span>&nbsp; }</span></div>
<div><span>}</span></div>
</div>
