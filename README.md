jQuery Push Menu
========

<strong>Push Menu</strong> is a <strong>jQuery</strong> plugin like android push menu

<h3>Requirements</h3>

<ul>
<li><a href="https://jquery.com" target="_new">jQuery</a></li>
<li><a href="http://demax.in" target="_new">pushmenu</a></li>
</ul>

<h3>HTML</h3>

```html
<script type="text/javascript" src="https://code.jquery.com/jquery-1.11.2.min.js"></script>
<script type="text/javascript" src="js/pushmenu.js"></script>
<link rel="stylesheet" type="text/css" href="css/pushmenu.css">
```

<h4>Menu</h4>

```html

<div id="pm_menu" class="pm_close">
	<ul>
		<li><a href="#">Home</a></li>
		<li><a href="#">About</a></li>
		<li><a href="#">Gallery</a></li>
		<li><a href="#">Contact</a></li>
	</ul>
</div>

<button id="open">Open Menu</button>

```

<h3>javascript</h3>
```javascript
<script type="text/javascript">
  (function($){
    $('#pm_menu').pushmenu({
    	button : "#open"
    });
  })(jQuery);
</script>
```


<a href="https://github.com/rihanrahul">Find more plugins here....</a>
