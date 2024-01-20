# Creating an Image Hover Effect using HTML and CSS

In this tutorial, we'll create a basic image hover effect using HTML and CSS. This effect will make the image scale up and display an overlay with a subtle transition on hover.

## HTML (index.html)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Image Hover Effect</title>
</head>
<body>

    <div class="image-container">
        <div class="image">
            <img src="your_image_url.jpg" alt="Your Image">
            <div class="overlay"></div>
        </div>
    </div>

</body>
</html>
