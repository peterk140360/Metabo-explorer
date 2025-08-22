# HMDB Metabolite Explorer

A web-based interactive application built with **Shiny for Python** that enables exploration, filtering, and visualization of metabolite data.  
The tool focuses on **natural product classifications, lipid taxonomies, and biological properties**, providing an intuitive interface for researchers and analysts.

---

## License
This project is licensed under the terms of the [GNU General Public License v3.0](LICENSE).

---

## Features

- **Multi-criteria filtering**  
  Filter by pathway, tissue, lipid category, and more.  

- **Interactive visualizations**  
  Bar charts, histograms, and taxonomic breakdowns.  

- **Searchable DataGrid**  
  Styled and exportable table with rich filtering options.  

- **Detailed information panel**  
  Displays taxonomy and external database links for selected metabolites.  

---

## Recent Updates (2025-07-31)

- Added "not classified" bar to bar chart  
- Changed pie chart to bar chart  
- Removed `"TOP {number}"` label in bar chart  
- Reordered plots  
- Added `LM | Main Class` as column in DataGrid  
- Renamed taxonomy columns in DataGrid  
- Removed custom CSS for the admin panel  

---

## Usage

1. Prepare the required **Parquet file** with metabolite data.  
2. Run the application:  

   ```bash
   shiny run --reload app.py
   ```

3. Use the filter panel to refine results.  
4. Explore statistics, browse the DataGrid, and inspect detailed entries.  

---

## Requirements

Install the required dependencies before running the application:

```bash
pip install shiny shinywidgets pandas numpy plotly faicons
```

---

## To Do

- Freeze/fix first column in the DataGrid  
- Add integration for automatic dataset updates in the Admin Panel  

---

## Resources

- [Shiny for Python](https://shiny.posit.co/py/)  
- [Plotly](https://plotly.com/python/)  
- [Pandas](https://pandas.pydata.org/)  
- [HMDB](https://hmdb.ca/)  
- [LipidMaps](https://www.lipidmaps.org/)  
- [ChEBI](https://www.ebi.ac.uk/chebi/)  
- [NPClassifier](https://npclassifier.gnps2.org/)  
- [ClassyFire](http://classyfire.wishartlab.com/)  

