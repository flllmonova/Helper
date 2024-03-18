layout with 3 elements, which 2nd element in center
```css
.grid-container {
  display: grid;
  grid-template-column: 1fr min-content 1fr;
  justify items: center;
}

.element_start {
  justify-self: start;
}

.element_end {
  justify-self: end;
}
```
