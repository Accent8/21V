# Leturstillingar í CSS

```CSS

body {
    font-style: normal;      /* italic , obligue */
    font-weight: normal;     /* bold , 100 - 900 */
    font-size: 1em;          /* 1px , 1rem , 100% */
    lineheight: 1.5;         /* tekur mið af einingunni sem er á font-size, staðlað 1.4 */
    font-family: Helvetica, sans-serif; 
    /* tekur Helvetica ef það er til, annars system font (sans-serif) */ 
}

body {
    font:italic bold 100%/120% Georgia, Times, serif;
    /*font-style, -weight, -size/-lineheight -family */
}

```