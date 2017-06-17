# web-design

1. **border-boxing:**
```css
* {
    -webkit-box-sizing: border-box;
       -moz-box-sizing: border-box;
        -ms-box-sizing: border-box;
            box-sizing: border-box;
}
```
2. **flex-boxing:**
```css
.parent-container {
  display:   -webkit-flex;
  display:   flex;
  flex-wrap: wrap;
}
```
3. **Boilerplate HTML:**
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name"viewport" content="width=device-width, initial-scale=1">
    <title></title>
    <link rel="stylesheet" href="css/bootstrap.css">
</head>
  <body>
  
  </body>
</html>
```
4. **Allow an image to expand only as large as its natural width:**
```css
img {
    max-width: 100%;
}
```
5. **If you're using Bootstrap, make the images responsive using `img-responsive` CSS class**
6. **Setting width or height of an element to viewport width or height in CSS:**
```css
img {
    width:  100vw;   /* means 100% of viewport width  */
    height: 100vh;   /* means 100% of viewport height */
}
```
7. **Incorporating responsive/efficient images in your workflow:**
* [GruntJS](https://gruntjs.com)
* [ImageOptim](https://imageoptim.com)
* [ImageMagick](http://git.imagemagick.org/repos/ImageMagick)
8. **Analyzing page load speeds:**
* [PageSpeed Tools](https://developers.google.com/speed/pagespeed/insights/)
* [YSlow](http://yslow.org/)
9. **Turn any direcotory on your system into a webserver directory:**
```python
python -m SimpleHTTPServer
```
10. **[Unicode table](https://unicode-table.com/en/)**
11. **Selectively download images:**
    1. **Based on Device Pixel Ratio (DPR):**
    ```html
      <img src="image_2x.jpg" srcset="image_2x.jpg 2x, image_1x.jpg 1x" alt="a cool image">
    ```
    2. **Based on image width:**
    ```html
      <img src="image_200.jpg" srcset="image_200.jpg 200w, image_100.jpg 100w" alt="a cool image">
    ```
