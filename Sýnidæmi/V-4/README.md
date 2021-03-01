# Glósur

#### Gildum hlaðið á eigindi 

```

div {
	margin: 10px 20px 30px 40px; 
	   /*-top(1) -right(2) -bottom(3) -left(4) 
	   á bæði við margin og padding */
	
	padding: 10px 20px; 
		/*top+bottom og left+right 
		á bæði við margin og padding */
	
	border: 5px solid #f0f; 
		/*-weight(1) -style(2) -color(3) */
	   /* 7 gildi eru í border-style: solid, dotted, dashed, double, ridge, inset, outset,*/
	  /*ath! að veja aðeins eitt gildi á border-style:*/
}

```
#### CSS 

```

bacground eigindi
    background-color:#6ff;
    background-image:url(flott-logo.svg);
    background-repeat: no-repeat; 
    background-position: 200px 300px;
    background-attachment: fixed / scroll	
    
body {			
	background: rgb(3,3,3) url(morn-wash.jpg) 0px -5px scroll no-repeat;
                /* litur( )     mynd(2)	staðsetning X-Y    fixed repeat x y */
	
/*  0% 	50%   100% 	fixed repeat-x eða repeat-y
    X lárétt: left* center right       
    Y lóðrétt: top* middle bottom  */

body {
	font:italic bold 100%/120% Georgia, Times, serif;
    /*  font-style(1) -weight(2) -size(3)-lineheight -family(4) */
}

```
