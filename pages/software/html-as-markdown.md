---
title: 'HTML as Markdown'
course: 'FVTC Software Documentation'
---

# You can use HTML in Markdown!

You can use HTML in Markdown! This allows you to do things like embed videos, or create more complex tables.

## Embedding Videos

You can embed videos using the `<iframe>` or `embed` tags. Here is an example:

```html
<div style="width: 100%; aspect-ratio: 16 / 9; float: none; clear: both; margin: 2px auto;">
  <embed
    src="https://www.youtube.com/embed/11iU9JuaLhc?si=y5HsMpFc7BqoJbGM"
    wmode="transparent"
    type="video/mp4"
    width="100%" height="100%"
    allow="autoplay; encrypted-media; picture-in-picture"
    allowfullscreen
  >
</div>
```

<div style="width: 100%; aspect-ratio: 16 / 9; float: none; clear: both; margin: 2px auto;">
  <embed
    src="https://www.youtube.com/embed/11iU9JuaLhc?si=y5HsMpFc7BqoJbGM"
    wmode="transparent"
    type="video/mp4"
    width="100%" height="100%"
    allow="autoplay; encrypted-media; picture-in-picture"
    allowfullscreen
  >
</div>

## Creating Tables

You can create tables using the `<table>` tag. Here is an example:

```html
<table>
	<thead>
		<tr>
			<th>Column 1</th>
			<th>Column 2</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Row 1, Column 1</td>
			<td>Row 1, Column 2</td>
		</tr>
		<tr>
			<td colspan="2">Row 2, Span 2</td>
		</tr>
	</tbody>
</table>
```

<table>
	<thead>
		<tr>
			<th>Column 1</th>
			<th>Column 2</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Row 1, Column 1</td>
			<td>Row 1, Column 2</td>
		</tr>
		<tr>
			<td colspan="2">Row 2, Column Span 2</td>
		</tr>
	</tbody>
</table>

