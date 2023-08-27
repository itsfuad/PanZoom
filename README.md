# Pan and Zoom Library for Images

This library provides a simple way to implement pan and zoom functionality for images on your website. Users can interactively pan and zoom in or out on images using mouse or touch gestures.

## Features

- Smooth pan and zoom interactions for images.
- Customize the minimum and maximum zoom levels.
- Control the zoom increment per scroll.
- Option to choose between linear or non-linear zoom scaling.
- Double-tap (or double-click) to reset the image to its original state.
- Works with both mouse and touch inputs.

## Usage

1. Include the `panzoom.js` script in your HTML:

   ```html
   <script src="path/to/panzoom.js"></script>
   ```
```html
<img src="path/to/your/image.jpg" id="panzoom-image" alt="Zoomable Image">
<script>
  PanZoom(document.getElementById('panzoom-image'), {
    minScale: 1,
    maxScale: 3,
    increment: 0.05,
    liner: false
  });
</script>
```


## Configuration Options
* minScale: The minimum zoom scale (default: 1).
* maxScale: The maximum zoom scale (default: 3).
* increment: Zoom increment per scroll (default: 0.05).
* liner: Linear or non-linear zoom scaling (default: false).
## License
This library is released under the GPL.

## Contributing
Contributions are welcome! If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.
