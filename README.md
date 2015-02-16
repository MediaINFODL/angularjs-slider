## AngularJS slider directive with no external dependencies

See original (https://github.com/rzajac/angularjs-slider) for complete documentation. This fork has additional:

- "rz-slider-container" option that will be used for event bindig instead of document in original; if this option is not used original document element will be used

## Example

### rz-slider-container option
```javascript
// in controller
$scope.sliderModel = 150;
$scope.sliderContainer = '#container-element';
$scope.sliderCallbacks = {
	onStart: function(arg){
		//code
	},
	onMove: function(arg){
		//code
	},
	onEnd: function(arg){
		//code
	}
}
```

```html
<div>
    <rzslider rz-slider-model="priceSlider" rz-slider-container="sliderContainer"></rzslider>
</div>
```


**v0.1.5**
    Forked from this version.
**v0.1.6**
    Added container option for custom event binding

## Disclaimer
This is a fork of original angular-slider (https://github.com/rzajac/angularjs-slider) which is based on [https://github.com/prajwalkman/angular-slider](https://github.com/prajwalkman/angular-slider).

## License

Licensed under the MIT license
