### PureCSSToolTip

<img src='https://raw.githubusercontent.com/iamsgokul/pureCSSToolTip/main/images/PureCSSToolTip.svg' style="width:200px;"/>

### Simple pure CSS ToolTip

ToolTip.css is used to the added tooltip for a web app, web page without javascript. This full of CSS code you just added the CSS file in your header are import CSS to your style and you can use it.

### How to use this tooltip on your HTML file

**Using NPM:**
```
npm install purecsstooltip
```

You can import directly in to JS
```JS
import 'purecsstooltip';
```

**CDN Version:**
If you don't want to use npm there is CDN option:

``` HTML
<link rel='stylesheet' href='https://unpkg.com/purecsstooltip@1.0.7/purecsstooltip.min.css'>
```

**Manually:**
Simple download purecsstooltip.min.css form this repositor and save to your project folder and call the css in head section on html
```HTML
<link rel='stylesheet' href='folder-path/purecsstooltip.min.css'>
```

Import your purecsstooltip.css file in your file. And addded the html attribute `tooltip-lbl` what text will appear on the tooltip `tooltip-pos` which position you want to show the tooltip on web page.

<img src='https://raw.githubusercontent.com/iamsgokul/pureCSSToolTip/main/images/tool-tip.gif'/>

<img src='https://raw.githubusercontent.com/iamsgokul/pureCSSToolTip/main/images/tooltip-position.gif'/>

### Position:

```html
<button tooltip-lbl='You hover on Top' tooltip-pos='top'>Top</button>
<button tooltip-lbl='You hover on Bottom' tooltip-pos='top'>Bottom</button>
<button tooltip-lbl='You hover on left' tooltip-pos='left'>Left</button>
<button tooltip-lbl='You hover on right' tooltip-pos='right'>Right</button>

<button tooltip-lbl='You hover on Top Right' tooltip-pos='top-right'>Top Right</button>
<button tooltip-lbl='You hover on Bottom Right' tooltip-pos='bottom-right'>Bottom Right</button>
<button tooltip-lbl='You hover on Top Left' tooltip-pos='top-left'>Top Left</button>
<button tooltip-lbl='You hover on Bottom Left' tooltip-pos='top-left'>Bottom Left</button>
```

We give five different Sizes for tooltip `Small, Medium, Large, Extra Large, and Fit`. You can use the HTML attribute `tooltip-size` to set the size of the tooltip for `<b>small</b>` size use `tooltip-size='sm'` for `<b>medium<b>` `tooltip-size='md'` for `<b>large</b>` `tooltip-size='lg'` for `<b>extra large</b>` `tooltip-size='xlg'` for `<b>fit</b>` `tooltip-size='fit'`.