# AI-PT-Project-1

#Using a Pivot Table to reoganize and aggregate the data. 

 Agg_Table = pd.pivot_table(table_name_df,
            index=['area_name'],
            values=['crime_code'],
            aggfunc=['count'])

#show the table 
Agg_Table

#renaming your columns 
crime_code_count = Agg_Tale.rename(columns={'count': 'Total'})

#sorting the data 
crime_code_count.sort_values(by=['Total'],ascending=False).head(20)

Resources and Links: 
    https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8/about_data
    https://plotly.com/python/tile-scatter-maps/ (using Long and Lat to plot)