### PureCSSToolTip

<img src='https://raw.githubusercontent.com/iamsgokul/pureCSSToolTip/main/images/PureCSSToolTip.svg' style="width:200px;"/>

PureCSSToolTip

Simple pure CSS ToolTip

ToolTip.css is used to the added tooltip for a web app, web page without javascript. This full of CSS code you just added the CSS file in your header are import CSS to your style and you can use it.

How to use this tooltip on your HTML file

Import your purecsstooltip.css file in your file. And addded the html attribute <b>tooltip-lbl</b> what text will appear on the tooltip <b>tooltip-pos</b> which position you want to show the tooltip on web page.

<img src='https://raw.githubusercontent.com/iamsgokul/pureCSSToolTip/main/images/tool-tip.gif'/>

<img src='https://raw.githubusercontent.com/iamsgokul/pureCSSToolTip/main/images/tooltip-position.gif'/>

Position:

<pre>
<span style="color:#b71212">&lt;button tooltip-lbl=</span>&#039;Top&#039; <span style="color:#b71212">tooltip-pos=</span>&#039;top&#039;<span style="color:#b71212">&gt;Top&lt;/button&gt;</span>
<span style="color:#b71212">&lt;button tooltip-lbl=</span>&#039;Bottom&#039; <span style="color:#b71212">tooltip-pos=</span>&#039;top&#039;<span style="color:#b71212">&gt;Bottom&lt;/button&gt;</span>
<span style="color:#b71212">&lt;button tooltip-lbl=<span>&#039;left&#039; <span style="color:#b71212">tooltip-pos=</span>&#039;top&#039;<span style="color:#b71212">&gt;Left&lt;/button&gt;</span>
<span style="color:#b71212">&lt;button tooltip-lbl=</span>&#039;right&#039; <span style="color:#b71212">tooltip-pos=</span>&#039;top&#039;<span style="color:#b71212">&gt;Right&lt;/button&gt;</span>
<br/><br/>
<span style="color:#b71212">&lt;button tooltip-lbl=</span>&#039;Top Right&#039; <span style="color:#b71212">tooltip-pos=</span>&#039;top-right&#039;<span style="color:#b71212">&gt;Top Right&lt;/button&gt;</span>
<span style="color:#b71212">&lt;button tooltip-lbl=</span>&#039;Bottom Right&#039; <span style="color:#b71212">tooltip-pos=</span>&#039;bottom-right&#039;<span style="color:#b71212">&gt;Bottom Right&lt;/button&gt;</span>
<span style="color:#b71212">&lt;button tooltip-lbl=</span>&#039;Top Left&#039; <span style="color:#b71212">tooltip-pos=</span>&#039;top-left&#039;<span style="color:#b71212">&gt;Top Left&lt;/button&gt;</span>
<span style="color:#b71212">&lt;button tooltip-lbl=</span>&#039;Bottom Left&#039; <span style="color:#b71212">tooltip-pos=</span>&#039;top-left&#039;<span style="color:#b71212">&gt;Bottom Left&lt;/button&gt;</span>
</pre>

We give five different Sizes for tooltip Small, Medium, Large, Extra Large, and Fit. You can use the HTML attribute <b>tooltip-size</b> to set the size of the tooltip for <b>small</b> size use tooltip-size='sm' for <b>medium</b> tooltip-size='md' for <b>large</b> tooltip-size='lg' for <b>extra large</b> tooltip-size='xlg' for <b>fit</b> tooltip-size='fit'.