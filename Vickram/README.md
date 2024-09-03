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