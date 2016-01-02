# CSS Flexbox essentials

## 1. Introduction

### What is Flexbox
CSS layout mode
without relay on flows, inline block

http://caniuse.com

## 2. Use Flexbox

The CSS properties can be roughly divided into 2 categories
- container
- item

### Flexbox Container
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
### Order
```css
.item {
  order: 3;
}
```
