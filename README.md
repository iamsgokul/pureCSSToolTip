### PureCSSToolTip

<img src='https://raw.githubusercontent.com/iamsgokul/pureCSSToolTip/main/images/PureCSSToolTip.svg' style="width:200px;"/>

### Simple pure CSS ToolTip

ToolTip.css is used to the added tooltip for a web app, web page without javascript. This full of CSS code you just added the CSS file in your header are import CSS to your style and you can use it.

### How to use this tooltip on your HTML file

Import your purecsstooltip.css file in your file. And addded the html attribute <b>tooltip-lbl</b> what text will appear on the tooltip <b>tooltip-pos</b> which position you want to show the tooltip on web page.

<img src='https://raw.githubusercontent.com/iamsgokul/pureCSSToolTip/main/images/tool-tip.gif'/>

<img src='https://raw.githubusercontent.com/iamsgokul/pureCSSToolTip/main/images/tooltip-position.gif'/>

### Position:

```html
<button tooltip-lbl='Top' tooltip-pos='top'>Top</button>
<button tooltip-lbl='Bottom' tooltip-pos='top'>Bottom</button>
<button tooltip-lbl='left' tooltip-pos='top'>Left</button>
<button tooltip-lbl='right' tooltip-pos='top'>Right</button>

<button tooltip-lbl='Top Right' tooltip-pos='top-right'>Top Right</button>
<button tooltip-lbl='Bottom Right' tooltip-pos='bottom-right'>Bottom Right</button>
<button tooltip-lbl='Top Left' tooltip-pos='top-left'>Top Left</button>
<button tooltip-lbl='Bottom Left' tooltip-pos='top-left'>Bottom Left</button>
```

We give five different Sizes for tooltip Small, Medium, Large, Extra Large, and Fit. You can use the HTML attribute <b>tooltip-size</b> to set the size of the tooltip for <b>small</b> size use tooltip-size='sm' for <b>medium</b> tooltip-size='md' for <b>large</b> tooltip-size='lg' for <b>extra large</b> tooltip-size='xlg' for <b>fit</b> tooltip-size='fit'.