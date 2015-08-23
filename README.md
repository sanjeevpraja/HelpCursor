# HelpCursor
A jquery plugin, to show handdrawn arrow and text as help


###How to use

	$('.header-text').helpcursor({options});


**Example**

	$('.header-text').helpcursor({
	position: 'right',
	color: '#666666',
	msg: 'This is right help text, better keep it straight and short'
	});
	
###Available Options	

| Option        |      Possible Value       | Default          |
| ------------- |---------------------------| -----------------|
| position      | left, right, top, bottom  | left             |
| color         | Hex color                 | #333333          |
| msg           | Any string                | Help Cursor text |