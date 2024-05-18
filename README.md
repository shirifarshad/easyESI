# easyESI

**easyESI** is a Python application designed to streamline the extraction of thermodynamic data and Cartesian coordinates from Gaussian output or log files. It includes two subsidiary scripts: **GThermo** and **ESIGen**.

**GThermo** is a Python script that extracts thermodynamic data from Gaussian output files. It specifically retrieves properties such as the sum of electronic and thermal enthalpies, the sum of electronic and thermal free energies, and 'SCF Done' values.

**ESIGen** is responsible for generating supporting information, including Cartesian coordinates and energies, from Gaussian output files.

The application reads settings via `set.txt` in the working directory, as shown below:

```json
{
   "number_of_SCF_Done_after_to_print": 6,
   "selected_excel_name": "data.xlsx",
   "selected_sheet_name": "Sheet1",
   "selected_row_for_out_file_name": 1,
   "selected_row_for_E_BS1": 2,
   "selected_row_for_H_BS1": 3,
   "selected_row_for_G_BS1": 4,
   "selected_row_for_E_BS2": 5
}

Citation
For academic citations, please reference the following:

Shiri, Farshad (2024). easyESI: A Python Script for Generating Supporting Information from Gaussian Output Files.

Contact
Email: farshad.shiri[at]yahoo.com


