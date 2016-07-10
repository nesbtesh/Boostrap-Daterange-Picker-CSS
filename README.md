# Bootstrap Date Range Picker CSS 

CSS elements from Bootsrap that are used in the Date Range Picker.
**V1.0**

## Why?

If you are not using [Bootsrap](http://getbootstrap.com/) for your project but you like using the [Date Range Picker](https://github.com/dangrossman/bootstrap-daterangepicker) you can now use this css file containing all the CSS elements from Boostrap used in the Date Range Picker.

## Getting Started

You first need to add the add [Moment.js](https://github.com/dangrossman/bootstrap-daterangepicker/blob/master/moment.min.js), [daterangepicker.js](https://github.com/dangrossman/bootstrap-daterangepicker/blob/master/daterangepicker.js), and [daterangepicker.css](https://github.com/dangrossman/bootstrap-daterangepicker/blob/master/daterangepicker.css). Lastly add this repo CSS file to your CSS path, and then add the following reference to your header tag.

```HTML
	<link href="css/bootsrap-date-range-picker.css" rel="stylesheet"></link>
```
## Documentation
	
If you want to use the chevron right and left in the daterange picker you can simply add a reference to the icons in your CSS files. See an example below.
In this example I am using [Google Icons](https://design.google.com/icons/) you can do the same if you want.

```CSS
.glyphicon.glyphicon-chevron-left:before{
  	content: "\E314";
  	font-family: 'Material Icons';
  	-webkit-font-feature-settings: 'liga';
}
.glyphicon.glyphicon-chevron-right:before{
   	content: "\E315";
  	font-family: 'Material Icons';
  	-webkit-font-feature-settings: 'liga';
}
```
	
## License

**MIT**