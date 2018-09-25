# CSS

## CSS Tags
``` CSS
tag{
  property-name: value ;
}
```

## CSS filenames
Name your file `filename.css`

## Link the HTML <=> CSS
Add this to your **HTML** file. NOT your .css file
```HTML
<link rel="stylesheet" href="folder/folder/filename.css" type="text/css" />
```

## Colors
```CSS
tag{
  /* Background colors  */
  background-color: lightblue;
  /* RGBA is Red, Green, Blue, Alpha (transparency) */
  background-color: rgba(255, 0, 0, .5);
  background-color: black;

  /* Text-color with a word */
  color: darkblue;
  /*  Text-colors with a HEX Code */
  /* Hex code is created with Red, Green, Blue: #RRGGBB */
  /* Hex numbers are 0-15 represented by 1-9,a-f */
  color: #ffffff;
  color: #000000;
  color: rgba(0, 0, 255, .5);
  /* Hexcodes can also have an alpha value. #RRGGBBAA */
  color: #00ff0055;
}
```


## Background-images
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

## Fonts

```CSS
@import url('https://fonts.googleapis.com/css?family=Fontdiner+Swanky');

p{
  font-size: 40px;
  /* em = the current font-size */
  line-height: 2em;
  text-align: center;
  text-align: right;
  font-family: "Helvetica Neue", arial , sans-serif;
  font-family: 'Fontdiner Swanky', cursive;
}

```

## Global Tag, Class and ID

```CSS
p{
  color: #111;
}
/* classes and IDs name must start with a letter */
.class-name{
  color: #222;
}
#ID-name{
  color: #333;
}

```
- a global tag is generic like `p`
- a class will override a global
- an ID will override a class
