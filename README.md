# Sublime Text CSS3 syntax highlight [![Build Status](https://travis-ci.org/i-akhmadullin/Sublime-CSS3.png?branch=master)](https://travis-ci.org/i-akhmadullin/Sublime-CSS3)

<img src="http://i.imgur.com/q3ETMkT.png">

## How to install

1. Ctrl+Shift+P → Package Control: Add Repository → https://github.com/i-akhmadullin/Sublime-CSS3

2. Ctrl+Shift+P → Package Control: Install Package → Sublime-CSS3

3. (in .css file) View → Syntax → Open all with current extension as... → CSS3


## What has been added

#### Property names
```
all
appearance
align-items, align-content, align-self
animation
animation-delay, animation-duration, animation-iteration-count, animation-fill-mode
animation-name, animation-play-state, animation-timing-function
at

backface-visibility
background-clip, background-origin, background-size
background-blend-mode
border-image, border-image-outset, border-image-repeat, border-image-slice, border-image-source, border-image-width
border-radius
box-align, box-direction, box-flex, box-ordinal-group, box-orient, box-pack
box-shadow
box-sizing

clip-path, clip-rule
column-count, column-fill, column-gap
column-rule, column-rule-color, column-rule-style, column-rule-width
column-span, column-width
columns

filter
flex, flex-align, flex-basis, flex-direction
flex-flow, flex-grow, flex-item-align, flex-line-pack
flex-order, flex-pack, flex-shrink, flex-wrap
font-effect
font-emphasize, font-emphasize-position, font-emphasize-style
font-feature-settings, font-kerning font-language-override
font-stretch, font-synthesis
font-variant-ligatures, font-variant-position, font-variant-caps
font-variant-numeric, font-variant-alternates, font-variant-east-asian

group
grid-area
grid-auto-columns
grid-auto-flow
grid-auto-rows
grid-column
grid-column-end
grid-column-start
grid-row
grid-row-end
grid-row-start
grid-template
grid-template-areas
grid-template-columns
grid-template-rows

hyphens
inline-flex
isolation
justify-content

mask
mask-border
mask-border-mode 
mask-border-outset 
mask-border-repeat 
mask-border-slice 
mask-border-source 
mask-border-width 
mask-clip
mask-composite
mask-image
mask-mode
mask-origin
mask-position
mask-repeat
mask-size
mask-type
mix-blend-mode

order
outline-offset
overflow-scrolling
overflow-wrap

perspective, perspective-origin

transform, transform-origin, transform-style
transition, transition-delay, transition-duration, transition-property, transition-timing-function

shape-image-threshold, shape-margin, shape-outside

tab-size
text-align-last
text-emphasis
text-overflow
text-size-adjust

unicode-range
user-select
word-break

behavior
-webkit-font-smoothing, -moz-osx-font-smoothing
-webkit-text-fill-color
interpolation-mode
line-clamp
-ms-writing-mode
```


#### Property values
All animatable properties plus
```
bicubic
border-box, padding-box, border-box, content-box
contain, cover, local
infinite
linear
table-cell, table-caption, table-column-group, table-column, table-row-group, table-row

linear-gradient, radial-gradient, webkit-gradient
repeating-linear-gradient, repeating-radial-gradient

box, flexbox, flex, column, column-reverse, row, row-reverse
flex-start, flex-end, space-between, space-around, stretch
wrap, wrap-reverse, start, inline-flex, inline-flexbox

closest-side, closest-corner, farthest-side,
ease, ease-in-out, ease-in, ease-out, from, to
farthest-corner, color-stop, preserve-3d, ellipse
transform, translate, rotate, scale, matrix, skew

color-burn, color-dodge, color,
darken, difference, exclusion, hard-light,
hue, lighten, luminosity, multiply
overlay, saturation, screen, soft-light

grid, inline-grid, subgrid
max-content, min-content
dense, stack

add, exclude, intersect, subtract
evenodd, nonzero
fill-box, stroke-box, view-box
luminance
no-clip
round

antialiased
blink
content
currentColor
grayscale
image-set
isolate
textfield
touch

initial, unset

ultra-condensed, extra-condensed, condensed, semi-condensed
semi-expanded, expanded, extra-expanded, ultra-expanded
common-ligatures, no-common-ligatures
discretionary-ligatures, no-discretionary-ligatures
historical-ligatures, no-historical-ligatures
contextual, no-contextual
all-small-caps, petite-caps, all-petite-caps, unicase, titling-caps
lining-nums, oldstyle-nums, proportional-nums, tabular-nums
diagonal-fractions, stacked-fractions, ordinal, slashed-zero
historical-forms
jis78, jis83, jis90, jis04, simplified, traditional
full-width, proportional-width, ruby

progid:DXImageTransform.Microsoft.Alpha, alpha
progid:DXImageTransform.Microsoft.Blur
progid:DXImageTransform.Microsoft.dropshadow
progid:DXImageTransform.Microsoft.gradient, startColorStr, EndColorStr
progid:DXImageTransform.Microsoft.Shadow
```

#### Pseudo elements
```
::-moz-focus-inner
::-ms-browse
::-ms-check
::-ms-clear
::-ms-expand
::-ms-fill
::-ms-fill-lower
::-ms-fill-upper
::-ms-reveal
::-ms-thumb
::-ms-ticks-after
::-ms-ticks-before
::-ms-tooltip
::-ms-track
::-ms-value
::-webkit-input-placeholder, ::-moz-placeholder, ::placeholder
::-webkit-search-cancel-button
::-webkit-search-decoration
::selection, ::-moz-selection
dialog::backdrop
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
:-webkit-autofill
```

#### At-rules
```
@keyframes (without keyframe selectors atm)
@custom-media (custom media queries)
```

#### Tags
```
keygen, main, math, menuitem, picture, source, svg, template, track
```

#### Units
```
vw,vh,vmin,vmax,turn,ms,dppx
```

#### Unicode-range
```
U+416, U+400-4ff, U+4??
```

#### Custom Properties for Cascading Variables
```
--my-variable: 20px;
```

#### Notations
```
var(--my-variable)
calc()
circle()
ellipse()
inset()
minmax()
polygon()
repeat()
```
