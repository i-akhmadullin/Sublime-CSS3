# Sublime Text 2 better CSS, CSS3 syntax highlighting

Enchances Sublime Text 2 CSS3, CSS2.1 highlighting:

<table>
<tr>
<td>
Before:
<img src="https://raw.github.com/i-akhmadullin/Sublime-CSS3/master/before.png">
</td>
<td>
After:
<img src="https://raw.github.com/i-akhmadullin/Sublime-CSS3/master/after.png">
</td>
</tr>
</table>


# Sublime Text 2 better CSS syntax detection

Adds several missing (mostly CSS3) features into sublime text 2 css parsing:

### Property names (prefixes omitted):
```
appearance

align-items
align-content
align-self

animation
animation-delay
animation-duration
animation-iteration-count
animation-fill-mode
animation-name
animation-play-state
animation-timing-function

background-clip
background-origin
background-size

border-image
border-image-outset
border-image-repeat
border-image-slice
border-image-source
border-image-width

box-shadow
box-sizing
border-radius

columns
column-count
column-fill
column-gap
column-rule
column-rule-color
column-rule-style
column-rule-width
column-span
column-width

flex
flex-basis
flex-direction
flex-flow
flex-grow
flex-shrink
flex-wrap

backface-visibility
perspective
perspective-origin
transform
transform-style
transform-origin

transition
transition-delay
transition-duration
transition-property
transition-timing-function

hyphens
overflow-scrolling
text-size-adjust
text-overflow

clip-path
mask
filter
user-select
webkit-mask-image, webkit-mask-size, webkit-mask-position
font-smoothing, webkit-font-smoothing
behavior
interpolation-mode
```


### Property values (prefixes omitted):
```
bicubic
border-box, padding-box, border-box, content-box
table-cell, table-caption, table-column-group, table-column, table-row-group, table-row

linear
infinite
webkit-gradient
radial-gradient
repeating-radial-gradient
linear-gradient
repeating-linear-gradient

flex-start, flex-end, space-between, space-around, stretch

transform, translate, rotate, scale, matrix, skew,
farthest-side, color-stop, preserve-3d, ellipse
ease-in-out, ease-in, ease-out, from, to

content
antialiased
blink
textfield
touch

progid:DXImageTransform.Microsoft.Alpha, alpha
progid:DXImageTransform.Microsoft.gradient, startColorStr, EndColorStr
```

### Pseudo elements:
```
::-webkit-input-placeholder, ::-moz-placeholder, ::placeholder
::selection, ::-moz-selection
::-webkit-search-cancel-button
::-webkit-search-decoration
::-moz-focus-inner
```

### Tags: svg


## Installation (with Package Control):

1. Ctrl+Shift+P → Package Control: Add Repository → https://github.com/i-akhmadullin/Sublime-CSS3

2. (in .css file) View → Syntax → Open all with current extension as... → CSS3
