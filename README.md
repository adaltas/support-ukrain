
# A few bytes SVG ribbon to support ukrain

Support Ukrain by inserting a ribbon on you site. View an example on [our website](https://www.adaltas.com/en/).

Top right alignment:

<img src="https://raw.githubusercontent.com/adaltas/support-ukrain/main/sample/top-right.png" style="width:10rem" />



```html
<!DOCTYPE html>
<html>
<body>
  <div style="position:fixed;top:-0;right:-3rem;zIndex: 500;width:14rem;transform: rotate(45deg);">
    <img alt="Support Ukrain!" src="https://raw.githubusercontent.com/adaltas/support-ukrain/main/support-ukrain.svg" />
  </div>
  <!-- Your site here -->
</body>
</html>
```




Top left alignment:

<img src="https://raw.githubusercontent.com/adaltas/support-ukrain/main/sample/top-left.png" style="width:10rem" />



```html
<!DOCTYPE html>
<html>
<body>
  <div style="position:fixed;top:-0;left:-3rem;zIndex: 500;width:14rem;transform: rotate(-45deg);">
    <img alt="Support Ukrain!" src="https://raw.githubusercontent.com/adaltas/support-ukrain/main/support-ukrain.svg" />
  </div>
  <!-- Your site here -->
</body>
</html>
```


Feel free to tweak the styles. Modifying the width property affect the ribon thickness, modifying the left or right properties afect its size.