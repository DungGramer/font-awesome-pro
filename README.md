# Font Awesome Pro
> You can include Font Awesome Pro for your project 

<p align="center">
  <img width="600" src="https://fontawesome.com/images/open-graph.png">
</p>

## Usage
1. Include one of the link CSS or Javascript in to HTML
#### CSS

   ```html
   <link href="https://dunggramer.github.io/font-awesome-pro/css/all.min.css" rel="stylesheet" type="text/css" />
   ```

   ```html
  <link href="https://gitcdn.xyz/repo/DungGramer/font-awesome-pro/master/css/all.min.css" rel="stylesheet" type="text/css"/>
  ```

  ```html
  <link href="https://cdn.staticaly.com/gh/DungGramer/font-awesome-pro/498e/css/all.min.css" rel="stylesheet" type="text/css" />
  ```
#### Javascript
  ```js
  <script src="https://dunggramer.github.io/font-awesome-pro/js/all.min.js" defer></script>
  ```
  ```js
  <script src="https://gitcdn.xyz/repo/DungGramer/font-awesome-pro/master/js/all.min.js" defer></script>
  ```
  ```js
  <script src="https://cdn.staticaly.com/gh/DungGramer/font-awesome-pro/498e/js/all.min.js" defer></script>
  ```
2. After that, find icon in [https://fontawesome.com/](https://fontawesome.com/)  
<br />  

## Tutorial
### Larger Icons
The `fa-lg` (33% increase), `fa-2x`, `fa-3x`, `fa-4x`, or `fa-5x` classes are used to increase the icon sizes relative to their container.
```html
<i class="fa fa-car fa-lg"></i>
<i class="fa fa-car fa-2x"></i>
<i class="fa fa-car fa-3x"></i>
<i class="fa fa-car fa-4x"></i>
<i class="fa fa-car fa-5x"></i>
```

### Animated Icons
The `fa-spin` class gets any icon to rotate, and the `fa-pulse` class gets any icon to rotate with 8 steps.
```html
<i class="fa fa-spinner fa-spin"></i>
<i class="fa fa-spinner fa-pulse"></i>
```

### Rotated and Flipped Icons
The `fa-rotate-*` and `fa-flip-*` classes are used to rotate and flip icons.
```html
<i class="fa fa-shield"></i>
<i class="fa fa-shield fa-rotate-90"></i>
<i class="fa fa-shield fa-rotate-180"></i>
<i class="fa fa-shield fa-rotate-270"></i>
<i class="fa fa-shield fa-flip-horizontal"></i>
<i class="fa fa-shield fa-flip-vertical"></i>
```

### Stacked Icons
To stack multiple icons, use the `fa-stack` class on the parent, the `fa-stack-1x` class for the regularly sized icon, and `fa-stack-2x` for the larger icon.

The `fa-inverse` class can be used as an alternative icon color. You can also add larger icon classes to the parent to further control the sizing.
```html
<span class="fa-stack fa-lg">
  <i class="fa fa-circle-thin fa-stack-2x"></i>
  <i class="fa fa-twitter fa-stack-1x"></i>
</span>
```

### Fixed Width Icons
The `fa-fw` class is used to set icons at a fixed width. This class is useful when different icon widths throw off alignment. Especially useful in Bootstrap's navlists and list groups.
```html
<div class="list-group">
  <a href="#" class="list-group-item"><i class="fa fa-home fa-fw"></i> Home</a>
  <a href="#" class="list-group-item"><i class="fa fa-book fa-fw"></i> Library</a>
  <a href="#" class="list-group-item"><i class="fa fa-pencil fa-fw"></i> Applications</a>
  <a href="#" class="list-group-item"><i class="fa fa-cog fa-fw"></i> Settings</a>
</div>
```
### Change Color in FA 5
+ Changing Opacity
  ```html
  <i class="fad fa-bus-alt" style="--fa-secondary-opacity: 0.60"></i>
  ```
+ Swapping Layer Opacity
  ```html
  <i class="fad fa-camera fa-swap-opacity"></i>
  ```
+ Swapping Layer Opacity
  ```html
  <i class="fad fa-bus-alt" style="--fa-primary-color: orangered;"></i>
  ```
