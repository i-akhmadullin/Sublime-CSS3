# Sublime Text 2 better CSS, CSS3 syntax highlighting

Enchances Sublime Text 2 CSS3, CSS2.1 highlighting:

<table>
<tr>
<td>
Before:
<img src="https://raw.github.com/i-akhmadullin/Sublime-CSS/master/before.png">
</td>
<td>
After:
<img src="https://raw.github.com/i-akhmadullin/Sublime-CSS/master/after.png">
</td>
</tr>
</table>


# Sublime Text 2 better CSS syntax detection

Adds several missing (mostly CSS3) features into sublime text 2 css parsing:

### Property names
```
appearance, moz-appearance, webkit-appearance

animation, moz-animation, webkit-animation
animation-name, moz-animation-name, webkit-animation-name
animation-delay, moz-animation-delay, webkit-animation-delay
animation-duration, moz-animation-duration, webkit-animation-duration
animation-iteration-count, moz-animation-iteration-count, webkit-animation-iteration-count

box-shadow, moz-box-shadow, webkit-box-shadow, ms-box-shadow,
box-sizing, moz-box-sizing, webkit-box-sizing, ms-box-sizing,

border-radius, moz-border-radius, webkit-border-radius
backface-visibility, webkit-backface-visibility, moz-backface-visibility, ms-backface-visibility

transform, moz-transform, webkit-transform, ms-transform
transform-style, moz-transform-style, webkit-transform-style, ms-transform-style

transition, webkit-transition, moz-transition, ms-transition
transition-delay, moz-transition-delay, webkit-transition-delay, ms-transition-delay
transition-duration, moz-transition-duration, webkit-transition-duration, ms-transition-duration
transition-property, moz-transition-property, webkit-transition-property, ms-transition-property

overflow-scrolling, moz-overflow-scrolling, webkit-overflow-scrolling
user-select, moz-user-select, webkit-user-select
text-overflow
webkit-mask-image, webkit-mask-size, webkit-mask-position
perspective, webkit-perspective, moz-perspective, ms-perspective
font-smoothing, webkit-font-smoothing
```

### Property values
```
border-box, padding-box, border-box, content-box
table-cell
infinite
ellipse
linear

webkit-gradient
radial-gradient, webkit-radial-gradient, moz-radial-gradient, ms-radial-gradient
transform, webkit-transform, moz-transform, ms-transform
linear-gradient , webkit-linear-gradient, moz-linear-gradient, ms-linear-gradient

translateZ, rotateY, scaleX, preserve-3d, translate
rotate, farthest-side, color-stop, scale
ease-in-out, ease-out, from, to

textfield
antialiased
blink
touch

progid:DXImageTransform.Microsoft.gradient, startColorStr, EndColorStr
```

### Pseudo elements: 
```
-webkit-input-placeholder, -moz-placeholder, placeholder
selection, -moz-selection
-webkit-search-cancel-button
-webkit-search-decoration
-moz-focus-inner
```

### Tag: svg


## Installation:

1. Open `Preferences` → `Browse Packages...` → `CSS`

2. Backup CSS.tmLanguage then replace with CSS.tmLanguage from this repository.
