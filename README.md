# Sublime Text CSS3 syntax highlight [![Build Status](https://travis-ci.org/i-akhmadullin/Sublime-CSS3.png?branch=master)](https://travis-ci.org/i-akhmadullin/Sublime-CSS3)

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


## How to install

1. Ctrl+Shift+P → Package Control: Add Repository → https://github.com/i-akhmadullin/Sublime-CSS3

2. Ctrl+Shift+P → Package Control: Install Package → Sublime-CSS3

3. (in .css file) View → Syntax → Open all with current extension as... → CSS3


## What has been added

#### Property names (prefixes omitted)
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

font-effect
font-emphasize
font-emphasize-position
font-emphasize-style
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
outline-offset
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
tab-size
text-align-last
text-emphasis
text-overflow
text-size-adjust
word-break

clip-path
filter
user-select
mask, mask-image, mask-size, mask-position
font-smoothing, webkit-font-smoothing, -moz-osx-font-smoothing
behavior
interpolation-mode
-ms-writing-mode
```


#### Property values (prefixes omitted)
```
bicubic
contain, cover, local
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
ease, ease-in-out, ease-in, ease-out, from, to

content
antialiased, grayscale
blink
textfield
touch
image-set

initial, unset

progid:DXImageTransform.Microsoft.Alpha, alpha
progid:DXImageTransform.Microsoft.Blur
progid:DXImageTransform.Microsoft.dropshadow
progid:DXImageTransform.Microsoft.gradient, startColorStr, EndColorStr
progid:DXImageTransform.Microsoft.Shadow
```

#### Pseudo elements
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

#### Pseudo classes
```
:not, :matches

:dir, :lang

:any-link, :local-link, :scope

:current, :past, :future

:indeterminate
:default
:in-range, :out-of-range
:required, :optional
:read-only, :read-write

:empty
:only-child
:first-of-type
:nth-of-type
:last-of-type
:nth-last-of-type
:only-of-type

:nth-match, :nth-last-match

:column, :nth-column, :nth-last-column

:valid-drop-target
:active-drop-target

:placeholder-shown
:user-error
```

#### At-rules
```
@keyframes (without keyframe selectors atm)
```

#### Tags
```
keygen
main
math
menuitem
picture
source
svg
template
track
```

#### Units
```
vw,vh,vmin,vmax,turn,ms,dppx
```

#### Custom Properties for Cascading Variables
```
var-my-variable: 20px;
```

#### Functional Notation
```
var(my-variable)
calc
```
