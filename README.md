Feather
==========

Feather is a responsive and super flexible 12-column CSS grid with an incredibly small footprint. It was built with the intent of providing a lightweight alternative to the often bloated existing CSS frameworks.

<a href = "http://htmlpreview.github.io/?https://github.com/JDerwisz/Feather/blob/master/demo.html" target="_blank">Demo</a>

## Row

```html
<div class="row"></div>
```

## Columns

```html
<!--12 of 12-->
<div class="l-12 m-12 s-12"></div>

<!--11 of 12-->
<div class="l-11 m-11 s-11"></div>

<!--10 of 12-->
<div class="l-10 m-10 s-10"></div>

<!--9 of 12-->
<div class="l-9 m-9 s-9"></div>

<!--8 of 12-->
<div class="l-8 m-8 s-8"></div>

<!--7 of 12-->
<div class="l-7 m-7 s-7"></div>

<!--6 of 12-->
<div class="l-6 m-6 s-6"></div>

<!--5 of 12-->
<div class="l-5 m-5 s-5"></div>

<!--4 of 12-->
<div class="l-4 m-4 s-4"></div>

<!--3 of 12-->
<div class="l-3 m-3 s-3"></div>

<!--2 of 12-->
<div class="l-2 m-2 s-2"></div>

<!--1 of 12-->
<div class="l-1 m-1 s-1"></div>
```

## Example

```html
<div class="row">
  <div class="l-6 m-6 s-12">6 Columns</div>
  <div class="l-6 m-6 s-12">6 Columns</div>
</div>
```

## Additional Tools

```css
.text-center {
    text-align: center !important;
}
.text-left {
    text-align: left !important;
}
.text-right {
    text-align: right !important;
}
.element-center-inner {
    /* Firefox */
    display:-moz-box;
    -moz-box-pack:center;
    -moz-box-align:center;

    /* Safari and Chrome */
    display:-webkit-box;
    -webkit-box-pack:center;
    -webkit-box-align:center;

    /* W3C */
    display:box;
    box-pack:center;
    box-align:center;
}
.element-padded {
    padding: 1.25em !important;
}
.pull-left {
    float: left !important;
}
.pull-right {
    float: right !important;
}
.clearfix {
    clear: both;
}
.no-gutter {
    margin-bottom: 0 !important;
}
```
