# marticli
---
Script to display the Martiri canteen menu of Pisa in the terminal (soon supporting other university canteens in Pisa as well).

The script will:

    Download the Martiri university canteen menu from the DSU Toscana website
    Extract table data from the PDF files
    Display the menus in a readable format in the terminal
    Delete temporary PDF files after use

## Installation
---
- Clone the repository:
```sh
git clone https://github.com/Deff38/marticli.git
cd marticli
```
- Run the script with:
```sh
python3 /usr/local/bin/marticli
```
- If you have already moved it to /usr/local/bin/ and made it executable (chmod +x), you can simply run:
```sh
marticli
```

## Dependencies
---
    requests → To download files
    beautifulsoup4 → To analize HTML pages
    pdfplumber → To extract text and tables from PDFs
    tabulate → To display tables in a readable format
    python3

