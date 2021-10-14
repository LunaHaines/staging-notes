# CSS

Some important syntax

## Classes, ids, and the like

with no change, selects an element
```css
p: {
    color: red;
}
```
\# selects by id
```css
#my-element {
    color: blue;
}
```
. selects by class
```css
.my-class {
    color: green;
}
```
you can select elements with particular attributes
```css
img[alt] {
    background-color: purple;
}
```
or you can select elements on when they're in a particular state
```css
a:hover {
    color: yellow;
}
```

## Selector Specifics

### Multiple Elements
You can select multiple elements by seperating with commas:
```css
p, h1, li {
    color: red;
}
```

## CSS Hierarchy

In CSS, there is specificity to the styles. the following is the order, from most to least specific. More specific overrides less specific.

1. Inline styles
2. Id
3. Classes, attributes, and pseudo-classes
4. Elements and pseudo-elements