# pdf-scrapping
Extracting text from PDF archives


### Requirements
 
 Install the command-line program QPDF (available for Linux and Mac OSX) with it is possible to transform parts of the illegible RAW binary of PDF file into a legibles texts.


### Install QPDF On linux 

execute the following commands in terminal :

`sudo apt-get update`

`sudo apt-get install qpdf`


### Using QPDF 

With the linux terminal open in the directory where is located yourarchive.pdf and execute the command :

`qpdf --qdf yourarchive.pdf legible-raw-output.pdf`

 The file legible-raw-output.pdf is the output of the QPDF.With just a simple text editor you can copy and change the contents of yours outputteds PDF's files.
 
### Scrapping text from PDF file

Using python code and the RE library you can adjust the patterns of the texts what are you looking for and exract it from the archive.Adding the OS python library is possible to execute the QPDF for a large number of PDF files.
