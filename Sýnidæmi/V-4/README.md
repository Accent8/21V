# Svegjanleg hönnun

### Viðmið (_Breakpoints_)

#### "Mobile up"

```CSS

body {
background-color: blue;
color: white;
}

@media only screen and (min-width: 37.5em) {
  body {
    background-color: lightblue;
  }
}

@media only screen and (min-width: 48em) {
  body {
    background-color: green;
  }
}

@media only screen and (min-width: 60em) {
  body {
    background-color: red;
	max-width: 60em;
	margin: 0 auto;
	border: 2px solid yellow;
  }
}

``` 