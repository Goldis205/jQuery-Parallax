# Welcome 
Welcome to the Parallax

# Setup
Import style and scripts for web page

```html
    <!-- Style -->
    <link rel="stylesheet" href="css/parallax.css" />

    <!-- Scripts -->
    <script src="js/jquery-3.1.1.min.js"></script>
    <script src="js/jquery.parallax.min.js"></script>
```

# Parallax HTML Structure
You can add as many parallax containers as you wish.

```html
    <div class="parallax-container">
        <div class="parallax"><img src="images/parallax.jpg"></div>
    </div>
```

# Initialization
```javaScript
    $(document).ready(function(){
        $('.parallax').parallax();
    });
```

# Parallax Customization 
The parallax container height is what defines how much of the image can be seen. This is set to 500px by default. You can add your own style to override this.

The image height must be taller than the parallax container height.

```css
    .parallax-container {
        height: "your height here";
    }
```