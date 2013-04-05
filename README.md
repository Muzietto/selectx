SelectX - jQuery plugin
=======================

This jQuery plugin must be attached to an existing HTML select. Its basic purpose is to keep track of the choices made with that select.

Each choice is recorded in the form of an HTML snippet called 'option widget'. Option widgets may contain a 'delete' element to remove the choice they represent.

There are several options, most of them illustrated in the HTML presentation page.

Other aspects currently NOT shown in the presentation page are:
- usage of templates in the creation of the option widgets (only jtemplates supported as of writing)
- attachment of data to the option widgets
- getter methods: 'chosenData' and 'bitmask'
