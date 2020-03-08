# billinfoextractor
Extract neccessary information from bill/invoice.

This project extracts Store name, Store address, Date and time, Invoice number, Total Bill Amount and Items from a given bill/invoice image.

Segmentation is used for each required field in the bill using semantic segmentation technique.

Import the following packages:

tesseract
opencv
xlwt 
regex

Project Desciption:
It takes the input of bill/invoice as jpeg image and extracts the data from it and then produces the output in a spreadsheet.
The program initially extracts the text from the image of invoice/bill and then the from the extracted text in various groups of text patterns
or text groups are categorized into various categories like Store name, Store address, Date and time, Invoice number, Total Bill Amount and Items.
The patterns of the text categories are identified using regex format.
