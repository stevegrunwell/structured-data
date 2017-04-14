### Properties

<table>
	<thead>
		<tr>
			<th>Thing</th>
			<th>CreativeWork</th>
			<th>Article</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>
				name<br>
				description<br>
				url
			</td>
			<td>
				dateCreated<br>
				license<br>
				publisher
			</td>
			<td>
				articleBody<br>
				wordCount
			</td>
		</tr>
	</tbody>
</table>

Note:

As we get deeper into Schema, we often pick up more available properties that are better suited to the type of object we're describing.

For example, every object will have access to name, description, and url properties, since those come from Thing. A CreativeWork adds things like dateCreated and publisher, while an Article includes things like the articleBody and wordCount.

If you've worked with object-oriented programming, this should seem very familiar.
