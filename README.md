Fun with CSS
============
Tasks
-----

### 0\. Sprite languages

#advanced

By using this HTML:

    <!DOCTYPE html>
    <html lang="en">
        <head>
            <meta charset="UTF-8" />
            <title>HBTN - 0- Sprite</title>

            <link href="0-styles.css" media="all" rel="stylesheet" type="text/css">
        </head>
        <body>
            <ul>
                <li>HTML<span class="icon i-html"></span></li>
                <li>CSS<span class="icon i-css"></span></li>
                <li>JavaScript<span class="icon i-js"></span></li>
            </ul>
        </body>
    </html>


And this image file: [0-sprite.png](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/2/d416199ca6ecdbd0f8a3.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20250106%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20250106T132317Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=24019dbadde57deac7f9168315aeaa48147a7acab5e0fe6663cda1c74f053a34 "0-sprite.png")

Create `0-styles.css` and generate this layout:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/2/94aa60f76c412f40a87b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20250106%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20250106T132317Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=2b73dbb49855ce9ab39375a062e61485ee5825606c4bba7ed56bebab233ae43b)

You are not allowed to change the image and the HTML - _sprite is cool!_

**Repo:**

*   GitHub repository: `holbertonschool-Fun-with-CSS`
*   File: `0-styles.css`

### 1\. Move the (under)line

#advanced

By using this HTML:

    <!DOCTYPE html>
    <html lang="en">
        <head>
            <meta charset="UTF-8" />
            <title>HBTN - 1- Underline</title>

            <link href="1-styles.css" media="all" rel="stylesheet" type="text/css">
        </head>
        <body>
            <h2>
                Hello <a href="https://www.holbertonschool.com">Holberton!</a>
            </h2>
        </body>
    </html>


Create `1-styles.css` and generate this layout where the underline is hidden by default and appeared slowly…:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/2/b791cfdbd11c0eefa5f7.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20250106%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20250106T132317Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=5bf7cccf5b0870738a282ad933dbe8e24e6ab851b22fb4d0332e4fbfa8d705bf)

You are not allowed to change the HTML

**Repo:**

*   GitHub repository: `holbertonschool-Fun-with-CSS`
*   File: `1-styles.css`

### 2\. Toggle

#advanced

By using this HTML:

    <!DOCTYPE html>
    <html lang="en">
        <head>
            <meta charset="UTF-8" />
            <title>HBTN - 2- toggle</title>

            <link href="2-styles.css" media="all" rel="stylesheet" type="text/css">
        </head>
        <body>
            <div class="toggle">
                <input type="checkbox" name="toggle" class="toggle-cb" id="toggle-0" checked>
                <label class="toggle-label" for="toggle-0">
                    <div class="toggle-inner"></div>
                    <div class="toggle-switch"></div>
                </label>
            </div>
        </body>
    </html>


Create `2-styles.css` and generate this layout where the `<input>` is has this custom toggle layout:

**Checked:**

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/2/3848b025c8f25636bba5.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20250106%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20250106T132317Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=fc0a4b74c01d1520b3587b2a717888680444caed3739be075a130b2ca1a66282)

**Unchecked:**

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/2/aeae59fdee93b17f360f.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20250106%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20250106T132317Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=5089fb4d2931ae3c5fb029892ed7fa94aab9f87e288d871feb2a2c9dd1a214c5)

You are not allowed to change the HTML

**Repo:**

*   GitHub repository: `holbertonschool-Fun-with-CSS`
*   File: `2-styles.css`

### 3\. Menu

#advanced

By using this HTML:

    <!DOCTYPE html>
    <html lang="en">
        <head>
            <meta charset="UTF-8" />
            <title>HBTN - 2- toggle</title>

            <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
            <link href="3-styles.css" media="all" rel="stylesheet" type="text/css">
        </head>
        <body>

            <nav class="menu">
                <input type="checkbox" href="#" class="menu-open" name="menu-open" id="menu-open"/>
                <label class="menu-open-button" for="menu-open">
                    <span class="menu-line menu-line-1"></span>
                    <span class="menu-line menu-line-2"></span>
                    <span class="menu-line menu-line-3"></span>
                </label>

                <a href="#" class="menu-item"> <i class="fa fa-area-chart"></i> </a>
                <a href="#" class="menu-item"> <i class="fa fa-bar-chart"></i> </a>
                <a href="#" class="menu-item"> <i class="fa fa-line-chart"></i> </a>
                <a href="#" class="menu-item"> <i class="fa fa-pie-chart"></i> </a>
                <a href="#" class="menu-item"> <i class="fa fa-table"></i> </a>
            </nav>

        </body>
    </html>


Create `3-styles.css` and generate this layout/animation:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/2/252a25667dc7c65fe0e9.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20250106%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20250106T132317Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=fb57fd7783a666ba2b38a878ea20c56662ae4365f6100ca0652f2981d2fc31c1)

You are not allowed to change the HTML

**Repo:**

*   GitHub repository: `holbertonschool-Fun-with-CSS`
*   File: `3-styles.css`
