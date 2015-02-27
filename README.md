Bootstrap DynamicGrid 1.0
=================

Thi is a dynamic table input ready for Bootstrap.

**Bootstrap DynamicGrid** allow you to collect structured data row by row such like filling spreadsheets. 
Just define the table structure with json and a table will be created dynamically with the right controls for each column. It allows you to add/remove/insert/delete row in the grid and you can serialize the data to url or Json. The generated input/select/textarea controls are well named for submitting to server side applications such as ASP.NET/PHP/JSP. Multiple options and callback events are available to fit every situation.

See live demo [here](http://mmassari.com/bootstrap-dynamicgrid/index.htm)

**Note:** This is a fork of jquery.appenGrid by Albert L. (https://github.com/hkalbertl/jquery.appendGrid). In my version I have removed the jquery UI dependency and classes for support Bootstrap 3 framework.

Bootstrap 3
-----------
All the code generated, uses standard BS3 classes to format the table and the inputs.
Available settings for large layouts using the -lg suffix in all generated controls make the tables modern and readable.

**Note:** since BS2 doesn't support for col-md-.. settings in table columns you can't use BS2 if you want to control the column sizes.

Features
-----------

**Legacy features:**
+ Define table structure via Json
+ Fill data from Json strucure
+ Add/Remove/Insert/Move rows
+ Support for custome control via function callbacks

**New Features released:**
+ Full responsive tables
+ Serialize to JSON

**Upcoming features:**
+ Keyboard support to move between cells and rows like in a Excel spreadsheet
+ Inline validation when leave a cell or a row

Soon I will post docs and examples...