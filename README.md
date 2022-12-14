# Joanna Albizures_ Journalism 124_Final
## Vehicular Accidents Leading to Death of Children


### Story Pitch & Summary
Every year, hundreds of children die due to vehicular accidents. A lot of these accidents are preventable, as some causes of deaths include drivers being on their phone or under the influence while they’re behind the wheel. Each life lost is one less graduation, wedding, accomplishment, that a family won’t get to celebrate with their loved child. 

In 2019, there was *1239 deaths* of children between <5-15 years old. The data for this project provided 10 age groups with an eleventh being for individuals of an unknown age. In California alone, there was 104 deaths of children between <5-15 years old, making up a total of 8.4% of the nation's deaths for these ages due to vehicular accidents. 

For this assignment, I used Traffic Safety Annual Reports by the National Highway Traffic Safety Administration. I chose the year 2019 because it was the year before the pandemic started. Since people weren't really driving in 2020 and early 2021 due to lockdown restrictions, 2019 was the last year with data following a similar pattern to years prior. 

#### Sources/Potential Interviewees
***Frank Cruz (Father of Zachary Cruz)*** 

Frank Cruz established Zachary Michael Cruz Foundation in 2010 to keep the memory of Zachary alive. Every year, the foundation awards two UC Berkeley transfer students the Zachary Cruz Memorial Scholarship. 

Contact Info: info@zmcfoundation.org

![zachcruz](https://user-images.githubusercontent.com/109833009/183459054-fc0be386-9f84-4e46-ad80-8c1898dd0140.png)


***Caileb Sioxson-Ramirez***  _Vehicle Safety Research (NSR) Intern at NHTSA_ 
Contact Info: https://www.linkedin.com/in/caileb-sioxson-ramirez-40715422a/


### Anaysis


#### Q1: What % of all vehicular accidents were children

<img width="398" alt="q1sheet" src="https://user-images.githubusercontent.com/109833009/183455474-a67b48bc-81e7-4d7f-9f11-ebbba31e3d13.PNG">


First,  I unmerged cells and took only relevant date, which was age groups that I wanted (3) of them.

Summed the 3 total groups (=sum B2:B4)

Divided by total number of deaths w/ age groups 

=(B16/B14)

Used % function to turn .0341 to 3.41%

Answer: 3.41% children (1239 deaths) 



<img width="225" alt="question1_howtoexcel" src="https://user-images.githubusercontent.com/109833009/183455542-0c7b9efe-11e1-4d00-a1d2-2f853f34ffd0.PNG">







#### Q2: On accidents with children involved, how many were alcohol related



<img width="618" alt="q2sheet" src="https://user-images.githubusercontent.com/109833009/183455750-a155337b-e6aa-4a2b-b710-0c071fcc3fb0.PNG">




I analyzed data, realized there was one error, the data was miscalculated in  People Killed, by Age Group and Highest Driver Blood Alcohol Concentration (BAC) in the Crash, 2019	

Error: total Listed 131 kids died from BAC but it was 132 as the light pink cells sum up to 132

Second, I duplicated spreadsheet to clean up any errors 

After that I color coded the excel sheet for relevant data

Then, I added a row below the three age groups to find the sum
=sum (B4:B6) dragged horizontally 

Following that, similarly to my previous calculation, I divided the sum of anyone who had a BAC above 0, then divided by total children deaths. 

I found that 24.37% of children deaths were alcohol related and 252 of the 302 were above the legal limit (.08)



<img width="709" alt="q2howto" src="https://user-images.githubusercontent.com/109833009/183455836-a883a7df-4b51-4356-9b00-7a6ca8086d6a.PNG">




####  Q3: Q3: What % of children killed by vehicular accidents were occupants in the car


<img width="668" alt="q3sheet" src="https://user-images.githubusercontent.com/109833009/183457173-7fe2c657-71e5-4841-9723-84549fadacb1.PNG">

I found that 937 occupants died (inside)

In order to find that, I got the total the people provided 

302 nonoccupants were struck



<img width="677" alt="q3howto" src="https://user-images.githubusercontent.com/109833009/183457223-d3dcfc2f-7530-46b4-95c8-100f342274bf.PNG">


#### Q4: On a national level, what state saw the most deaths with children, and how does that compare to California’s death rate



<img width="855" alt="q4" src="https://user-images.githubusercontent.com/109833009/183464531-22596d9d-59ff-42de-9e27-4e378512ba19.PNG">

No calculations needed, 3719 people died in CA to vehicular accidents. 104 were children




<img width="846" alt="q4counta" src="https://user-images.githubusercontent.com/109833009/183464560-07d46b02-1641-4850-a87b-9937d6054edb.PNG">

With counta on a pivot table, I found that Texas was the state with the most child deaths. 124 children died in Texas due to vehicular accidents
### Data Visualization

I decided to use a bar chart and split bars to best visualize this data

![N4WvY-fatal-vehicular-accident-victims-by-age-groups](https://user-images.githubusercontent.com/109833009/183457554-0a56b6f5-e10c-475e-817b-b811c293220f.png)





![Jz6us--span-style-font-family-arial-font-size-16px-text-align-center-white-space-pre-wrap-background-color-rgb-250-251-254-people-killed-by-age-group-and-highest-driver-blood-alcohol-concentration-bac-in-the-crash-](https://user-images.githubusercontent.com/109833009/183457453-7f08edbe-b05d-4674-8422-be27be66343b.png)

