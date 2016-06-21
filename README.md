# jQuery Caret (jCaret)

jQuery plugin to manipulate the caret's position in a text box

Based on https://code.google.com/archive/p/jcaret/ and adapted to NPM and require().

## Usage

### Get caret position
$('#inputid').caret() // {start: 0, end: 0, text: ""}

### Set caret position
$('#inputid').caret(start, end)
