# TableExport xls with Bold Headers jQuery Plugin
![npm version](https://img.shields.io/npm/v/tableexport-xls-bold-headers.svg)
![npm downloads](https://img.shields.io/npm/dt/tableexport-xls-bold-headers.svg)

A jQuery plugin which generates a basic .xls file with bold headers from a HTML table.

#### Install
1. `npm install tableexport-xls-bold-headers`  or just download `tableexport-xls-bold-headers.js` from this repository.
2. Include `tableexport-xls-bold-headers.js` in your HTML files.

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
    type: 'excel',
    escape: 'false',
    filename: 'myExport.xls'
});
```
to generate and download the Excel file 'myExport.xls'

#### Credits
Original code by Shreedhar Bhat from this [StackOverflow answer](https://stackoverflow.com/a/44255259), with some small
modifications by Carlo Pantaleo.