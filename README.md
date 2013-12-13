# Sublime Text CSS3 syntax

Enchances Sublime Text CSS highlighting:

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


Adds several missing (mostly CSS3) features into sublime text css parsing:

### Property names (prefixes omitted)
```
all

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
flex-align
flex-basis
flex-direction
flex-item-align
flex-flow
flex-grow
flex-line-pack
flex-order
flex-pack
flex-shrink
flex-wrap
box-align
box-direction
box-flex
box-orient
box-ordinal-group
box-pack
justify-content
inline-flex
order
group

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
-moz-osx-font-smoothing
behavior
interpolation-mode
```


### Property values (prefixes omitted)
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
box, flexbox, flex, column, column-reverse, row, row-reverse,
wrap, wrap-reverse, start, inline-flex, inline-flexbox

transform, translate, rotate, scale, matrix, skew,
closest-side, closest-corner, farthest-side,
farthest-corner, color-stop, preserve-3d, ellipse
ease-in-out, ease-in, ease-out, from, to

content
antialiased, grayscale
blink
textfield
touch
image-set

initial, unset

progid:DXImageTransform.Microsoft.Alpha, alpha
progid:DXImageTransform.Microsoft.gradient, startColorStr, EndColorStr
```

### Pseudo elements
```
::-webkit-input-placeholder, ::-moz-placeholder, ::placeholder
::selection, ::-moz-selection
::-webkit-search-cancel-button
::-webkit-search-decoration
::-ms-browse
::-ms-check
::-ms-clear
::-ms-expand
::-ms-fill-lower
::-ms-fill-upper
::-ms-fill
::-ms-reveal
::-ms-thumb
::-ms-ticks-after
::-ms-ticks-before
::-ms-tooltip
::-ms-track
::-ms-value
::-moz-focus-inner
```

### At-rules
```
@keyframes (without keyframe selectors atm)
```

### Tags
```
keygen
main
math
menuitem
picture
source
svg
track
```

### Units
```
vw,vh,vmin,vmax,turn,ms,dppx
```

### Functional Notation
```
calc
```

## Installation (with Package Control)

1. Ctrl+Shift+P → Package Control: Add Repository → https://github.com/i-akhmadullin/Sublime-CSS3

2. Ctrl+Shift+P → Package Control: Install Package → Sublime-CSS3

3. (in .css file) View → Syntax → Open all with current extension as... → CSS3
