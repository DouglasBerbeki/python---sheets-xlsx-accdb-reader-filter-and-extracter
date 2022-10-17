# python---sheets-xlsx-accdb-reader-filter-and-extracterA system for reading big data from xlsx (excel) and accdb (access) from a folder, then filter it by columns (using 8 differents conditions from text and values), then export as xlsx separated by 1.000.000 lines.

1) Configure filters:
	You can add how much filter you want, one by one.
	Type of filter:
	1) element in column has the EXACLY text value
	2) element in column has the text value in ANY PLACE of its text
	3) element in column STARTS with the text value
	4) element in column END with the text value
	5) element in column has the EXACLY float value (=x)
	6) element in column is ABOVE float value (>x)
	7) element in column is BELOW float value (<x)
	8) element in column is the INT value (it convert float to int, se "10.5" is "10")
	Then write the Column name
	Then write the value (can be text, float or int, based on filter type selected)
	Then choose to filter only rows with that condition, or the inverse, only rows without that condition.
	Then choose if add more filters or note
2) Search database files in path
	Paste the file path from windows explore
	The program with read all the files that is "xlsx" or "accdb"
3) The filter
	The program with filter all the files and prepare for a result
4) The export
	The program with export the result in .xslx files (in the same path informed), split it every 1.000.000 lines (the excel limit)
