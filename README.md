# ngTouch
A angular module to add directives for touch devices.

# How to use it
You must include the ngTouch dependency on your angular module:
````
var app = angular.module("demoapp", ["ngTouch"]);
````
Then in your HTML you can use:
````
<div ng-touchmove="someFunction($event)" ng-touchstart="someFunction($event)" ng-touchend="someFunction($event)"></div>
````

# Standalones
You can get the standalones dependencies used in this module:
- [ngTouchmove](https://github.com/marktopper/ngTouchmove)
- [ngTouchstart](https://github.com/marktopper/ngTouchstart)
- [ngTouchend](https://github.com/marktopper/ngTouchend)
