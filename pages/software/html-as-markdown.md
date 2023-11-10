---
title: 'HTML as Markdown'
course: 'FVTC Software Documentation'
---

# You can use HTML in Markdown!

You can use HTML in Markdown! This allows you to do things like embed videos, or create more complex tables.

## Embedding Videos

You can embed videos using the `<iframe>` tag. Here is an example:

```html
<iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```

<iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

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
			<td>Row 2, Column 1</td>
			<td>Row 2, Column 2</td>
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
			<td>Row 2, Column 1</td>
			<td>Row 2, Column 2</td>
		</tr>
	</tbody>
</table>

