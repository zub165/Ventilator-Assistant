# Ventilator Diagram Images

This directory contains images for the Ventilator Assistant application.

## Required Images

1. **ventilator-diagram.png** - Main ventilator schematic diagram
   - You can obtain this image by:
     - Downloading it from [this Imgur link](https://i.imgur.com/xqnqOeP.png)
     - Saving it as `ventilator-diagram.png` in this directory

## Using Local Images

After downloading the ventilator diagram image to this directory, update the image path in `index.html` to use this local file:

```html
<img src="images/ventilator-diagram.png" alt="Ventilator Diagram" class="img-fluid w-100">
```

This will help avoid CORS issues and ensure the application works properly even when offline. 