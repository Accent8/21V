# CSS glósur

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

```CSS

    background-color: #6ff;
    background-image:url(flott-logo.svg);
    background-repeat: no-repeat;         /*  fixed, repeat-x eða repeat-y */
    background-position: 200px 300px; /* x,y  X lárétt: left, center, right. Y lóðrétt: top, middle, bottom */
    background-attachment: fixed /* scroll */	
    
body {			
	background: rgb(3,3,3) url(image.jpg) 0px -5px scroll no-repeat;
                /* litur,     mynd,	staðsetning X-Y,    fixed, repeat x y */

	font:italic bold 100%/120% Georgia, Times, serif;
    /*  font-style, -weight, -size, -lineheight -family */
}

```
