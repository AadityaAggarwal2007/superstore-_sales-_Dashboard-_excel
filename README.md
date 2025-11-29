# Superstore Sales Dashboard (Excel + Power Query)

Turned 10,000+ rows of raw superstore sales data into a refreshable Excel dashboard.

## What this project does
- Cleans and transforms raw CSV data using Power Query  
- Removes duplicates, fixes dates, and standardises categories  
- Builds an interactive dashboard (KPIs, charts, slicers)  
- Auto-updates when new data is dropped into the source folder

## Tools used
- Microsoft Excel
- Power Query

## How to use
1. Download or clone this repository to your system.
2. Keep `Dashboard.xlsx` and the data file (e.g. `superstore_raw_data.xlsx`) in the **same folder**.
3. Open `Dashboard.xlsx` in Excel.
4. If Excel asks, click **Enable Content** / **Enable Editing**.
5. Go to the **Data** tab → click **Refresh All**.  
   - The dashboard will pull the latest data from the source file.
6. Use the slicers and filters on the dashboard sheet to explore sales by city, category, ship mode, etc.

## Files
- `Dashboard.xlsx` – main dashboard file  
- `Superstore Data` – sample raw data used for the report
