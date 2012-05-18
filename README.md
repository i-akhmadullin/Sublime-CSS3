# Sublime Text 2 better CSS syntax detection

Adds several missing (mostly CSS3) features into sublime text 2 css parsing:

### Property names
```
(moz-|webkit-)appearance
(moz-|webkit-)animation(-duration|-delay|-name|-iteration-count)
(moz-|webkit-|ms-)box(-shadow|-sizing)
(moz-|webkit-)border-radius
(webkit-|moz-|ms-)backface-visibility
(moz-|webkit-|ms-)transform(-style)
(webkit-|moz-|ms-)transition(-delay|-duration|-property)
(moz-|webkit-)overflow-scrolling
(moz-|webkit-)user-select
text-overflow
webkit-mask-(image|size|position)
(webkit-|moz-|ms-)perspective
(webkit-)font-smoothing
```

### Property values
```
border-box
table-cell
infinite
ellipse
linear
webkit-gradient
(webkit-|moz-|ms-)(radial-gradient transform linear-gradient)
translateZ rotateY scaleX preserve-3d
translate
rotate
farthest-side
color-stop
scale
antialiased
```

### Pseudo selector: placeholder



## Installation:

1. Open `Preferences` → `Browse Packages...` → `CSS`

2. Rename or make backup copy of CSS.tmLanguage, copy new CSS.tmLanguage from this repository.


