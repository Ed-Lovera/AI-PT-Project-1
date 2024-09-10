# AI Bootcamp Project 1 - 2020 to mid 2023 Los Angeles Crime Dataset

The goal of this project is to determine what factors within Los Angeles can make a person susceptible to being the victim of a violent crime within Los Angeles.
Factors that we will be considering in order to arrive to our conclusion are the following:
- Is there any correlation to the number of violent crimes to non-violent crimes on a month to month basis?
- What impact did the Covid-19 Stay-At-Home mandate have on violent crimes?
- Which areas of Los Angeles expirience the most violent crimes?
- In the most violent areas, how do young people fare with violent crimes throughtout the year?

To generate the plots required to answer the questions above, you must exexute the following [notebook](https://github.com/Ed-Lovera/AI-PT-Project-1/blob/main/la_crimes.ipynb).

Alternatively, you may continue reading below or take a look at our powerpoint [presentation](https://github.com/Ed-Lovera/AI-PT-Project-1/blob/main/LA%20Crime%20Data%20Analysis%202020%20-%202023.pptx).

---

## Summary
We have detemined that several factors do in fact come into play when it comes to predicting the likelyhood of being a victim of a violent crime within Los Angeles.
The two biggest factors being the presences of a Stay-At-Home mandate or similar curfew as well as the age of the victim.

### Is there any correlation to the number of violent crimes to non-violent crimes on a month to month basis?
Not really. From what we can observe in the correlation table below, violent crimes tend to happen half as frequently as non-violent crimes. This alone is not sufficient in determining actualy correlaction.

![image](https://github.com/user-attachments/assets/1f3f8f4f-65f8-4b2f-ac05-8333b4275fc1)

Furthermore, it appears as though a bigger factor that may increase the likelyhood of a violent crime is the outside temperature. As we can see in the bar graph below, there is visible uptick in violent crimes during the middle of the year. These are typically summer months in which temperatures rise.

![image](https://github.com/user-attachments/assets/488aa93b-5ffa-44b7-aac8-ab5daba37cc8)

To add, in the most recent data, we can that violent crimes have not increased at the same rate as non-violent crimes. This leads us to beleve that there are more important factor at play.

![image](https://github.com/user-attachments/assets/9891b3fa-ae3a-4b1b-a069-fe62eb2b49f3)

### This has us thinking... what impact did the Covid-19 Stay-At-Home mandate have on violent crimes?
The short answer is, a very significant impact! To set a baseline, we first take a look at all crimes throught out the years. At which point we can easily see that in 2020, the year in which the Covid-19 Stay-At-Home mandate was mostly in effect, crimes across the board were down.

![image](https://github.com/user-attachments/assets/362aecb2-e6ab-4a1c-889d-328d7aaa1eac)

When we take this data and average out the monthly crimes during and outside of the Covid-19 Stay-At-Home mandate we can see a clear trend in which violent crimes were significantly!

![image](https://github.com/user-attachments/assets/2a0272ab-3d49-44eb-bcfa-493fd9966ba1)

If you ask us, this makes the crimes rates during the Covid-19 Stay-At-Home mandate unreliable as they do not reflect the normal crime rates.

### So, which areas of Los Angeles expirience the most violent crimes?
Considering that Covid has had a big impact on crime rates, going forward we will ommit any records that appear during the Covid-19 Stay-At-Home mandate. And although not very easy to tell based on the heatmap below, 77th Street and Central LA take the lead.

![image](https://github.com/user-attachments/assets/cb483eeb-5c7e-4c7d-969c-d156780e63d3)

Viewing this information in a bar graph or pie chart places the following areas in the top 5:
77th Street
Central LA
Southeast
Southwest
Newton

![image](https://github.com/user-attachments/assets/2fde003b-aaf5-41b6-bdeb-1e7bf0b4f1d9)

![image](https://github.com/user-attachments/assets/c428a02d-3c06-47f9-9350-e635d47e0194)

### In the most violent areas, how do young people fare with violent crimes throughtout the year?
Not great :(

When clamping the age range from 2 years up to 30 years old. We can see that the closer you get to 30 the most dangerous it is for you in the most violent areas. 25-30 being the age group in the most danger as we near the end of the calendar year.

![image](https://github.com/user-attachments/assets/58cded81-c901-49d0-8412-2c774d35d413)

![image](https://github.com/user-attachments/assets/81035006-87e5-4d90-aec8-37c8679cd1a2)

From the top 5 most dangerous areas, it seems that Southwest LA is the only outlier in which being in your early 20s is hazardous all year long.

In summary, being a person that is in Los Angeles, when there is no Stay-At-Home mandate, being near 77th Street (or Central, Southeast, Southwest or Newton LA) and between the ages of 25-30 you are in higher risk of being a victim of a violent crime.

## Stay safe out there!



