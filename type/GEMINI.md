do# Project: Image to HTML Conversion

This project involves converting a series of PDF documents, treated as images, into structured HTML files.

## Source Files
- **Images (PDFs):** Located in the `DNDE 8070/` directory.
- **Instructions:** Located in the `Offline Work Details/` directory.

## Process
1. Read a PDF file from the `DNDE 8070` directory, starting from the file after `GF10336.pdf`.
2. Extract the text content using OCR.
3. Format the extracted text into an HTML file according to the specific tagging rules and format specified in the instructions. Ensure that a new line is started after every `<br>` tag.
4. The output HTML file will have the same name as the source PDF, but with an `.html` extension.
5. All generated HTML files will be saved in the root directory.
6. After the conversion of every 5 files, the changes will be pushed to the GitHub repository with a commit message in the format 'iteration X'.