#### Microformats

```html
<div class="vevent">
	<h2 class="summary">Lone Star PHP</h2>
	<time datetime="2013-04-20" class="dtstart">April 20</time>
	&ndash;
	<time datetime="2013-04-22" class="dtend">22, 2013</time>
	<p class="description">...</p>
</div>
```

Note:

If we wanted to create an hCalendar — microformats' structure for a calendar event — for Lone Star PHP, it might look something like this.

The contents would be wrapped in a div with class "vevent", and we'd assign class names like "summary", "dtstart", "dtend" and "description" to the event name, dates, and description.
