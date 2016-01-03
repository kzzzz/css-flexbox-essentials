# CSS Flexbox essentials

[A Visual Guide to CSS3 Flexbox Properties](https://scotch.io/tutorials/a-visual-guide-to-css3-flexbox-properties)

## 1. Introduction

### What is Flexbox
CSS layout mode
without relay on flows, inline block

http://caniuse.com

## 2. Use Flexbox

The CSS properties can be roughly divided into 2 categories
- container
- item

### Flexbox container
``` css
.flex-container {
  display:flex;
}
```
### Column width
``` css
.item {
  flex-basis: 100px;
  flex-grow: 1;
  flex-shrink: 2;
}
```
### Flexbox shorthands
```css
.item {
  flex: 1 1 150x;
}
```
### Flexbox direction
```css
.container {
  flex-direction:row(-reverse);
  flow-direction:column;
}
```
### Reorder the content (items)
```css
.item1 {
  order: 3;
}
.item2 {
  order: 1;
}
```
### Content spacing
```css
.item {
  margin: 20px;
  padding; 10px;
}
```
### Wrapping content
```css
.flex-container{
  flex-wrap: wrap(-reverse);
}
```
### Flex-flow shorthand
```css
.flex-container {
  // flex-direction: row;
  // flex-wrap: wrap
  flex-flow: row wrap;
}

.item {
  // flex-grow: 1;
  // flex-shrink: 2;
  // flex-basis: 150px
  flex: 1 2 150px
}
```
### Cross-Axis alignment
