Orbit-Grid
==========

Simple, lightweight & super flexible 12-column CSS grid that supports mobile, medium, large, and even very large screens.

## Page Wraps

<strong>Large Page Wrap</strong></br>
```html
<div class ="page-wrap-lg"></div>
```
</br>
<strong>Medium Page Wrap</strong></br>
```html
<div class = "page-wrap-md"></div>
```
</br>
<strong>Small Page Wrap</strong></br>
```html
<div class = "page-wrap-sm"></div>
```

## Row

```html
<div class = "row"></div>
```

## Columns

```html
<!--12 of 12-->
<div class = "col-12"></div>

<!--11 of 12-->
<div class = "col-11"></div>

<!--10 of 12-->
<div class = "col-10"></div>

<!--9 of 12-->
<div class = "col-9"></div>

<!--8 of 12-->
<div class = "col-8"></div>

<!--7 of 12-->
<div class = "col-7"></div>

<!--6 of 12-->
<div class = "col-6"></div>

<!--5 of 12-->
<div class = "col-5"></div>

<!--4 of 12-->
<div class = "col-4"></div>

<!--3 of 12-->
<div class = "col-3"></div>

<!--2 of 12-->
<div class = "col-2"></div>

<!--1 of 12-->
<div class = "col-1"></div>
```

## Example

```html
<div class = "page-wrap-lg">
  <div class = "row">
    <div class = "col-6">Col-6</div>
    <div class = "col-6">Col-6</div>
  </div>
</div>
```

## Additional Elements

```css
.elmnt-center {
    margin: 0 auto;
}
.elmnt-padded {
    padding: 20px;
}
.pull-left {
    float: left;
}
.pull-right {
    float: right;
}
.clearfix {
    clear: both;
}
.no-gutter {
    margin-bottom: 0px;
}
```
