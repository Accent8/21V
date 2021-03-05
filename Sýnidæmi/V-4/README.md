# Display: grid;

* https://github.com/vefgrunnur/cssgrid
* [Learn CSS Grid 👍](https://scrimba.com/g/gR8PTE)
* [w3schools CSS Grid](https://www.w3schools.com/css/css_grid.asp)
* [Grid by example](https://gridbyexample.com/)

```HTML

<!DOCTYPE html>
<html>
<head>
<style>
.item1 { grid-area: header; }
.item2 { grid-area: menu; }
.item3 { grid-area: main; }
.item4 { grid-area: right; }
.item5 { grid-area: footer; }

.grid-container {
  display: grid;
  grid-template-areas:
    'header header header header header header'
    'menu main main main right right'
    'menu footer footer footer footer footer';
  grid-gap: 10px;
  background-color: #2196F3;
  padding: 10px;
}

.grid-container > div {
  background-color: rgba(255, 255, 255, 0.8);
  text-align: center;
  padding: 20px 0;
  font-size: 30px;
}
</style>
</head>
<body>

<h1>Grid Layout</h1>

<p>This grid layout contains six columns and three rows:</p>

<div class="grid-container">
  <div class="item1">Header</div>
  <div class="item2">Menu</div>
  <div class="item3">Main</div>  
  <div class="item4">Right</div>
  <div class="item5">Footer</div>
</div>

</body>
</html>


```


## CSS glósur

#### Gildum hlaðið á eigindi 

```CSS

div {
	margin: 10px 20px 30px 40px; 
	   /*-top(1) -right(2) -bottom(3) -left(4) 
	   á bæði við margin og padding */
	
	padding: 10px 20px; 
		/*top+bottom og left+right 
		á bæði við margin og padding */
	
	border: 5px solid #f0f; 
	        /*-weight, -style, -color */
	/* 7 gildi eru í border-style: solid, dotted, dashed, double, ridge, inset, outset,*/
	/*ath! að veja aðeins eitt gildi á border-style:*/
}

```

