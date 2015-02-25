# pw-image-fields-markup
Textformater for ProcessWire fields that allows you to use image fields inside markup languages, notably, Markdown and Textile in Processwire text fields

## To apply it to a field

Add the textformater *after* the markup language textformatter (Markdown or Textile)

## To use it inside the text area

Simply use the normal image tags from the Markup language that you're writting on. In case of Markdown would be: `![alt](url)` and in the url part use the form `field_name:position`. If you use `0` as the position, all images from the field will be shown. If you fill also the alt text, it will be used, if you leave it empty, that image description will be used instead.

## Examples:

### show second image from the field called "images" with and alt text of "overriding alt text":
`![overriding alt text](images:2)`

### show all images from the field called "images" with their descriptions as the alt text:
`![](images:0)`



