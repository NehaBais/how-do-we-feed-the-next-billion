# How do we feed the next billion ?​ A study into Food Insecurity & Resource Allocation

## Folder Structure:

```
| Root
|- clean_data # final data
   |- fisi.csv
   |- wb_data.country.csv
   |- wb_data.combined.csv
|- ne_110m_admin_0_countries # Helper files for Geopandas mapping
   |- ne_110m_admin_0_countries.cpg
   |- ne_110m_admin_0_countries.dbf
   |- ne_110m_admin_0_countries.prj
   |- ne_110m_admin_0_countries.README.html
   |- ne_110m_admin_0_countries.shp
   |- ne_110m_admin_0_countries.shx
   |- ne_110m_admin_0_countries.VERSION.txt
|- staging_data # intermediate data
   |- indicator_imputation_strategy.csv
   |- wb_countries.csv
   |- wb_data.country.csv
   |- wb_data.region.csv
   |- wb_indicators.csv
   |- wb_regions.csv
   |- wb_topics.csv
|- WDI_CSV_2024_09_25 # Original Dataset taken from link - https://datacatalog.worldbank.org/search/dataset/0037712/World-Development-Indicators
   |- WDICountry.csv
   |- WDICSV.csv
   |- WDIfootnote.csv
   |- WDIseries-time.csv
   |- WDISeries.csv
|- interesting_plots
   |- Afghanistan Arable land (hectares per person).png
   |- Benin Arable land (hectares per person).png
   |- Botswana Population growth (annual %).png
   |- Cambodia Livestock production index (2014-2016 = 100).png
   ...
|- 1_data_collection.ipynb
|- 2_EDA_beforeImputation.ipynb
|- 3_imputation.ipynb
|- 4_EDA_clean_data.ipynb
|- 5_FISI_Indexes.ipynb
|- 6_clustering.ipynb
|- README.md
|- requirements.txt
```

## Install packages:

1. `python3 -m venv venv`
2. `source venv/bin/activate`
3. `pip install -r requirements.txt`

## Execution Steps:

1. Create the folders clean_data and staging_data as per directory structure.
2. Run the ipynb files as per number.