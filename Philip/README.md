# AI-PT-Project-1

My ideations for questions:
                    
                    Question 1; How did average crimes look per month for the LA Crimes data set we used?
                    2020 and 2021 were the lowest years for average violent crimes per month.
                    Question 2: What happened to average violrnt crime rates per month in LA during Covid California's Stay At Home Mandate starting March 19, 2020 ending June 15, 2021? 
                    The avergae crime per month was considerbaly lower during the California Covid Lockdown period for averga e violent crimes per month.

1.  I imported all dependancies i thought i might need for the project.

2.  Created a DF crom the CSV.

3.  Printed the top 5 just to ensure it worked.

4.  Converted the 'DATE OCC", which was the date the crimes occured to a datetime so it could be sorted and used properly.

5.  Double Checked the infor for each column to ensure the date time processed properly.

6.  Created a new dataframe for just teh information I was interested in, date occured, crime code description and the crime code numbers, ('DATAE OCC', 'Crm Cd Desc' and 'Crm Cd')

7.  Used the Crm Cd to filter for just violent crimes based on the LA City crime codes list pulled from the City of LA website pdf UCR-COMPSTAT062618, and printed it to be sure it's what we were looking for and create new Violent Crime code dataframe Vcrimes_df.

8. Ensure DATE OCC was a Datetime.

9.  Group the code counts by year to show the top 10 violent crimes for each year in the data set.

10. Create a count of violent crimes based on the Crm Cd Desc (crime code description).

11. Separate out the California covid lock down months March 19 1020 to January 25, 2021.

12. Verified the info on the columns.

13. Created a new DF only holding crime codes and thier description and lockdown period ("Crm Cd", "Crm Cd Desc", "DATE OCC", 'Lockdown')

14. extract the months and group by year, month and crime description.

15. Calculate the average violent crime per month.

16. Create a pivot table by month, year and count(mean).

17. Graph the data to show the difference in the average violent crimes per month for each month in the csv data.

18. Compare the average of the covid Lockdown months average violent crimes to the average monthly violent crimes when not in locjdown for the data set.

20. The conclusion based on the data graphed shows a significant drop in average violent crimes commited per month during the Covid Lockdown perion 03/19/2020-01/25/2021.





                       
                    