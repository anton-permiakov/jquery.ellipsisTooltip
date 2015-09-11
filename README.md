# jQuery ellipsisTooltip plugin
Cuts long string and adds its content to tooltip.
### Screenshot
![ellipsisTooltip](http://s21.postimg.org/6bt4lk293/ellipsis_Tooltip.png)
### Usage
```javascript
$("#elementId").ellipsisTooltip([parameters]);
```
or just add `data-ellipsis` attribute to the element you want shorten:
```html
<a href="#link" data-ellipsis="true">Shortened link</a>
```
### [Parameters]
```javascript
{
  content: undefined, // custom html, in case we want to return modified markup
  parent: $("#parentElement"), // custom parent
  width: $("#parentElement"), // parent element width
  resize: true, // bind window resize event
  placement: "top", // bootstrap tooltip placement param (top||bottom||left||right)
  container: "body", // bootstrap container param (parent for tooltip)
  template: '<div class="tooltip" role="tooltip"><div class="tooltip-arrow"></div><div class="tooltip-inner" style="max-width: 250px; word-wrap: break-word"></div></div>', // tooltip markup
}
```
