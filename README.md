# mynetdiary
Process an edited csv file from the mynetdiary website to a graph via an excel spreadsheet.

The extent of the editing has yet to be determined.

The process as of 01/20/19 (beta) is as follows:
1) Pull an excel weekly summary down from the "my net diary" website.
2) Export a "csv" file from that excel spreadsheet.
3) Edit? that "csv" file (edited_selected.csv, details later).
4) Run the perl script to produce a streamlined "toExcel.csv" file.
4a) This file may require some editing of the first line (labels)?
5) Import that "toExcel.csv" file into the final spreadsheet to generate the chart which combines the following factors:
5a) All you have to do is "double click" and it will open in "Numbers" on the g5b system.
6) date, weight, cals, exercise, glucose, blood pressure
