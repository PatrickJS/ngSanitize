ngSanitize
==========

angular-sanitize module without including angular.js for Backbone and other frameworks


```javascript
window.ngSanitize('<p style="color:blue">an html\n' +
'<em onmouseover="this.textContent=\'PWN3D!\'">click here</em>\n' +
'snippet</p>');
```
```javascript
"<p>an html&#10;<em>click here</em>&#10;snippet</p>"
```
