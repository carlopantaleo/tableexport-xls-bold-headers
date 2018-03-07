# TableExport jQuery Plugin
A jQuery plugin which generates a basic .xls file with bold headers from a HTML table.

#### Install
1. `npm install tableexport-jquery-plugin`.
2. Include `table-export.js` in your HTML files.

#### Usage
Let your HTML table be like:
```HTML
<table id="myTable">
    <thead>
        ...
    </thead>
    <tbody>
        ...
    </tbody>
</table>
```

Call:
```javascript
$('#myTable').tableExport({
    escape: 'false',
    filename: 'myExport.xls'
});
```
to generate and download the Excel file 'myExport.xls'

#### Credits
Original code by Shreedhar Bhat from this [StackOverflow answer](https://stackoverflow.com/a/44255259), with some small
modifications by Carlo Pantaleo.