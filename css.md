# CSS

## CSS Tags
```CSS
tag{
  property-name: value;
}
```

##CSS filnames
Name your file `file.css`

## Link the HTML <=> CSS
add this to your **HTML** file. NOT your .css file
```HTML
<link rel="stylesheet" href="style.css" type="text/css" />
```

## Colors
```CSS
tag{
  /* background colors */
  background-color: lightblue;
  /* RGBA is red, Green, Blue, Alpha (transparency) */
  background-color: rgba(255, 0, 0, .5 );
  background-color: black;

  /* text-color with a word */
  color: darkblue;
  /* text-color with a HEX code */
  /* Hex code is created with Red, Green, Blue: #RRGGBB */
  /* Hex numbers are 0-15 represented by 1-9,a-f */
  color: #ffffff;
  color: #000000;
  color: rgba(0, 0, 255, .5);
  /* Hexcodes can also have an alpha value. #RRGGBBAA */
  color: #00ff0055;
}
```


## background images
```CSS
tag{
  /* Background image (repeats by default) */
  background-image: url("images/back.png");
  /* Host a REMOTE Image */
  background-image: url("https://upload.wikimedia.org/wikipedia/commons/5/58/Sunset_2007-1.jpg");
  background-size: 200px;
  /* Show the full image */
  background-size: contain;
  /* Cover entire page with the image */
  background-size: cover;
  background-repeat: no-repeat;
  background-position: top right;
}
```




#fonts

```CSS
@import url('https://fonts.googleapis.com/css?family=Chango');

p{
    font-size: 40px;
    /* em = the current font size  */
    line-height: 2em;
    text-align: center;
    text-align: right;
    font-family: "Helvetica", Arial, sans-serif;
    font-family: "Chango";

}
