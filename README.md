# cs310-csv-json-sp22
The purpose of this lab is to convert two sets of data using conversion methods with the given data file into CVS data and JSON data. 
This code uses data conversion libraries to help display the conversions properly. It also uses arrays to create column and row headers. 
This code creates the appropriate amount of  arrays to store the data using the int. 
The end result, will be to create “columns” in order to separate the data in a traceable and tangible manner.
The “.put” function labels the “columns” for example:

	jsonObject.put(“colHeaders”, colHeaders);
	jsonObject.put(“rowHeaders”,rowHeaders);
	jsonObject.put(“data”, data);

This is labeled so we can insert information into each index without mixing them up. 
The same will be done to the CSV data. Each insertion is separated by commas and then the data is transferred. 
Then the data is formatted to look like the example below:

          **********CSV data**********	        
	      "ID","Total","Assignment 1","Assignment 2","Exam 1"
	        "111278","611","146","128","337"
	        "111352","867","227","228","412"
	        "111373","461","96","90","275"
	        "111305","835","220","217","398"
	        "111399","898","226","229","443"
	        "111160","454","77","125","252"
	        "111276","579","130","111","338"
	        "111241","973","236","237","500"
	        
	   **********JSON data********** 
	   	"colHeaders":["ID","Total","Assignment 1","Assignment 2","Exam 1"],
	        "rowHeaders":["111278","111352","111373","111305","111399","111160",
	        "111276","111241"],
	        "data":[[611,146,128,337],
	                [867,227,228,412],
	                [461,96,90,275],
	                [835,220,217,398],
	                [898,226,229,443],
	                [454,77,125,252],
	                [579,130,111,338],
	                [973,236,237,500]
 
  The end result for this program is to re arrange data from CVS to JSON and vise versa. 
  I learned how to create column and row headers, using arrays and how to re arrange data. 
  This was a independent project and I enjoyed it because it allowed me to plan through step by step, what I had to do. 
  It could be improved by finding more short cuts. I felt as though with a little more research, I could have made this cod simpler and smoother. 
