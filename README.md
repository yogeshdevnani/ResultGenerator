# ResultGenerator
This application creates result from an excel sheet to printable invidiual result


## Requirements
* An exe at root level, which takes input from input_folder, and produces result to output_folder.
* It should parse the input_folder, and look for all the sheets inside of it. Process each, and take the name, rollnumber and other details and make an object.
*  use that object to populate a word type file, which will later be convered to pdf.
*  At the end all the pdfs should be merged to one, but still the individual pdf should be there inside another folder divided by class.
*  The output folder will have a new all merged pdf with class.

*  The console should display the total numnber of PDFS created, and also report if there were any anomalies, like invalid marks entered or any other thing.

*  Include a instructions file with this as well; potentially a pdf with details and a short birdsview at the beginning. 
