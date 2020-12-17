1. Add missing custom stylesheet. Fixing this will give headings a yellow/pink background.
```html
  <!-- Linked stylesheet? -->
  <link href="style.css" rel="stylesheet" type="text/css" />
```

2. Add missing bootstrap stylesheet. Fixing this will change the font and enable (broken) grids within Services and Team sections.
```html
  <!-- Linked bootstrap? -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css" integrity="sha384-TX8t27EcRE3e/ihU7zmQxVncDAy5uIKz4rEkgIXeMed4M0jlfIDPvg6uqKI2xXr2"
	crossorigin="anonymous">
```

3. Add missing `</div>` within Services. Fixing this fixes the grid in Services.

```html
<!-- Ending tags? -->
</div>
```

4. Replace `<div/>`s with `</div>`s. Fixing this fixes grid in Team.
```html
<!-- Ending tags? -->
</div>
</div>
```

5. Add `width` or `height` to image. Fixing this will resize the dog image.

```html
  <!-- img attribute? -->
  <img src="https://images.unsplash.com/photo-1561037404-61cd46aa615b?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80" width="200px">
```

6. Add `.` to `italicized` ruleset. Fixing this will make one of the bullets at the top of the page italicized.

```css
/* Class selector? */
.italicized {
  font-style: italic;
}
```