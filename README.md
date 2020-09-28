# udt-to-image-position

This module modifies a UDT dataset by converting all of the pixel coordinates into image coordinates.

For example, if there is a bounding box with a `centerX` of `0.5` in a UDT file, and the image is `500px` wide, it will convert the `centerX` to `250`. It will also add an `imageWidth` and `imageHeight` property to each sample.

> The UDT format only accepts percent coordinates ([for a good reason]())

Installation:

```bash
npm install udt-to-image-position
```


```javascript
const { convertUDTToImagePosition, convertSampleToImagePosition } = require("udt-to-image-position")

// TODO
```
