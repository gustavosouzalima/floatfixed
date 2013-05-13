Float Fixed
============

The **Float Fixed** is a plugin to make your navigation bar in position fixed on scrolling and give a back to top button.

[Demo](http://jsfiddle.net/gustavox4ids/cX4gJ/2/ "Demo") online

Examples:
----------

*Basic:*

```bash
$('#nav').floatfixed({
    scrollOffsetTopx:100,
});
```

*Set speed:*

```bash
$('#nav').floatfixed({
    scrollTopSpeed:800,
});
```

*Your own class icon:*

```bash
$('#nav').floatfixed({
    scrollClass: "icon-chevron-up icon-white",
});
```

All Options:
---------

```bash
 $('#nav').floatfixed({
    topx: '0px',
    offsetTopx:400,
    leftx: 0px,
    scrollTopx:true,
    scrollTopSpeed:800,
    scrollOffsetTopx:200,
    floatFixedx:true,
    scrollClass:"yourClass"
 })
```

