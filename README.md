# jQuery ellipsisTooltip plugin
Cuts long string and adds its content to tooltip.
### Screenshot
![ellipsisTooltip](https://leto12h.storage.yandex.net/rdisk/a5446c06875ee18f518c16b13f19bc30d373c40bd6a56f022f796ea6c9bad3b1/inf/BrDtpRQI800M1YUsTIlnpuUtJ88l03SLcHrMuBbk31Pkww09BmNqx14ngH52zBfoHU7iCwah_FwWJZV39eAtbA==?uid=0&filename=ellipsisTooltip.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&tknv=v2&rtoken=df46252a4309f98c5722f90b4e316a71&force_default=no)
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
