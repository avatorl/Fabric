# Metareport - Power BI Report of Power BI Reports

A Fabric Notebook calls the Power BI REST API to get a list of all reports in each workspace, then for each report gets report metadata and exports an image of the first report page into a PNG file. It then resizes the PNG files to create smaller thumbnails, converts them into base64-encoded images split into small chunks, and saves the metadata and base64 chunks into a table in a Lakehouse.

Read more: https://powerofbi.org/metareport/
