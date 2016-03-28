# HTML/CSS Icon graphic wallpaper

![screen_capture](https://cloud.githubusercontent.com/assets/11635523/14069745/6cafde52-f463-11e5-9f60-a69f3519b23c.png)



This is a snippet of code to illustrate the design
element that is utilized in website/mobile designed with icons as wallpaper(Jumbotron) or as part of the design element.

1. Created the folder for the with CSS/img subfolders and index.html file
2. Downloaded the icons I planned to use for the design from Flaticons
3. In Pixlr I created a new image with a 500 x 200 pixel canvas


![pixlr_screencast1](https://cloud.githubusercontent.com/assets/11635523/14069760/a90601b0-f463-11e5-8686-9bf1b8f909b3.png)
![pixlr_screencast2](https://cloud.githubusercontent.com/assets/11635523/14069762/ac3197aa-f463-11e5-8d6c-56d3c5e56278.png)

4. While using Pixlr  I added the icons to the 500 x 200 canvas and made the canvas transparent
//screen cast 3
//screen cast 4
//screen cast 5
//screen cast 6
5. Added the img to the img subfolder and I utilized the <div class="img-pattern"> class from the CSS file
6. Added the button with h1 text

```html

<div class="img-pattern">

<!--Header title -->
<h1 class="header-title">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</h1>

<!-- Click me button -->
<button class="button btn" onclick="alert('Hello world! Thank you for clicking on me')">Click Me</button>

</div>

```


```css

.img-pattern{
  position: relative;
  background-color:  #4891ea;
  background:#4891ea url(../img/wall_pattern.png) center bottom;
  background-repeat: repeat;
  text-align: center;
  color: #fff;
  padding-bottom: 14em;
  min-height: 425px;
}

```





###Utilities used:

**Pixlr**

Free alternative to Photoshop  [Pixlr]( https://pixlr.com/editor/)

**Icons**

[Flaticon](http://www.flaticon.com/) - Designed by [Freepik](http://www.freepik.com/)

[Google Font API ](https://www.google.com/fonts)

[Lorem ipsum](http://www.lipsum.com/feed/html) (Random Text Generator)


