# Excel-to-PDF-Generate
This Python script automates the generation of PDF files for each record in a Google Sheet. Each PDF contains details from a single record and is saved with a name derived from the GCP/DB/CP Name/ID field. Finally, all generated PDFs are bundled into a ZIP file for easy download.
# GNSS Observation Log Sheet PDF Generator

This project automates the creation of PDFs for each record in a Google Sheet, with all PDFs zipped into a single downloadable file. The script is designed to run in Google Colab, leveraging Google Drive for authentication and storage.

---

## Features

- Fetches data directly from a Google Sheet.
- Creates a PDF for each record with formatted data.
- Saves all PDFs in a folder named `pdfs`.
- Bundles all PDFs into a single ZIP file for download.

---

## Prerequisites

### Environment
- **Google Colab**: This script is designed to run in Google Colab for seamless integration with Google Sheets.

### Google Sheet
- Ensure the Google Sheet is shared with the email associated with your Google Colab account.
- The sheet should have headers and data in tabular format.

### Libraries
Install the required Python libraries in Colab:
```bash
!pip install gspread pandas fpdf2


pdfs/
├── ID_1.pdf
├── ID_2.pdf
├── ...
pdfs.zip


