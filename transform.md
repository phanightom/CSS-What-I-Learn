### CSS Transform

```
transform: scale(4); // 縮放倍率 
transform-origin: top left; // 縮放起始點
```

```html
<!DOCTYPE>
<html>
	<head>
	  <style type="text/css"> 
      .container {
      	text-align: center;
        display: inline-block;
      }
      .box {
      }
      .box img {
      	-webkit-transition: all .5s;
    		-moz-transition: all .5s;
    		-o-transition: all .5s;
    		transition: all .5s;
      }
      .box img:hover {
        -webkit-transform: scaleX(4) scaleY(4);
		    -ms-transform: scaleX(4) scaleY(4);
		    transform: scaleX(4) scaleY(4);
		    -webkit-transform-origin: top left;
		    -ms-transform-origin: top left;
		    transform-origin: top left;
		    -webkit-transition: all .5s;
		    -moz-transition: all .5s;
		    -o-transition: all .5s;
		    transition: all .5s;
      }
  </style> 
	</head>
	<body>
	  <div class="container">
	    <div class="box">
	    	<img 
	    	  id="img1"
	    	  src="./1.png"
	    	/>
	    </div>
	  </div>
	</body>
</html>

```
