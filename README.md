# Box CSS

Box-CSS is a minimalist CSS utility library designed to streamline the development process with a utility-first approach. It provides a comprehensive set of classes that cover essential styling needs, allowing developers to quickly and efficiently build responsive and well-designed web interfaces without the overhead of larger frameworks.



## Spacing

### Margin
- **Auto Margin:** `mauto` `mhauto` `mvauto`
- **All Sides:** `ma[x=1-5]` e.g., `ma2`, `ma3`
- **Vertical Sides:** `mv[x=1-5]` e.g., `mv2`, `mv3`
- **Horizontal Sides:** `mh[x=1-5]` e.g., `mh2`, `mh3`
- **One Side:**
  - Left: `ml[x=1-5]` e.g., `ml2`
  - Top: `mt[x=1-5]` e.g., `mt2`
  - Right: `mr[x=1-5]` e.g., `mr2`
  - Bottom: `mb[x=1-5]` e.g., `mb2`

### Padding
- **All Sides:** `pa[x=1-5]` e.g., `pa2`
- **Vertical Sides:** `pv[x=1-5]` e.g., `pv2`
- **Horizontal Sides:** `ph[x=1-5]` e.g., `ph2`
- **One Side:**
  - Left: `pl[x=1-5]` e.g., `pl2`
  - Top: `pt[x=1-5]` e.g., `pt2`
  - Right: `pr[x=1-5]` e.g., `pr2`
  - Bottom: `pb[x=1-5]` e.g., `pb2`

## Width
- `w10` `w20` `w30` `w40` `w50` `w60` `w70` `w80` `w90` `w100`

## Height
- `h10` `h20` `h30` `h40` `h50` `h60` `h70` `h80` `h90` `h100`

## Display

### Block and Inline
- `block`
- `inline-block`
- `inline`

### Table
- `table`
- `table-cell`
- `table-row`

### Flex
- `flex`
- `inline-flex`
- `flex-auto`
- `flex-none`
- `flex-column`
- `flex-row`
- `flex-wrap`
- `items-start`
- `items-center`
- `items-baseline`
- `items-stretch`
- `justify-start`
- `justify-end`
- `justify-center`
- `justify-between`
- `justify-around`

## Position

### Positions
- `static`
- `relative`
- `absolute`
- `fixed`
- `sticky`

### Coordinates
- `top0`
- `right0`
- `bottom0`
- `left0`

### Z-Index
- `z0`
- `zmax`

### Horizontal and Vertical Center Align
- `centerh`
- `centerv`

## Border

### Border Radius
- **General Radius:**
  - `rounded0`
  - `rounded1`
  - `rounded3`
  - `rounded-pill`
- **Zero Radius:**
  - Top Left: `rounded-tl0`
  - Top Right: `rounded-tr0`
  - Bottom Left: `rounded-bl0`
  - Bottom Right: `rounded-br0`

### Border
- **All Sides:** `ba`
- **Top:** `bt`
- **Right:** `br`
- **Bottom:** `bb`
- **Left:** `bl`
- **None:** `bn`

## Text and Font

### Text Size
- `font-default`
- `font-large`
- `font-small`

### Font Weight and Style
- **Bold:** `b`
- **Italic:** `i`

### Text Align
- **Left:** `tl`
- **Right:** `tr`
- **Center:** `tc`

### Text Transform
- `capitalize`
- `uppercase`
- `lowercase`

## Helpers

- **No Wrap:** `nowrap`
- **Disable Text Selection:** `noselection`
- **Text Ellipsis and Truncate:** `truncate`
- **Cursor Pointer:** `pointer`

## Overflow
- **Overflow Y Auto:** `overflow-y-auto`
- **Overflow X Auto:** `overflow-x-auto`
- **Overflow Hidden:** `overflow-hidden`

# Setup

Install box css:
```
$ npm i box-scss
```

Add to you project src/App.tsx:
```
import "box-scss"
```

Use it like:
```
<div class="pa1"></div>
<div class="pa2"></div>

<div class="ma2"></div>

```

Detailed documentation is getting prepaired...

