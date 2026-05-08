April, 2026
EVA Data Update Travel Model Indicators
DRC: Clint Chiavarini, Joe Gordon
Modeling: Kyle Hauger

Indicators 1-3, workers within 30 minutes (ensemble gv)
Methodology:
DRC Responsibility: provide modelers with census tract number of workers in each category.  Data table will have both the census tract number and the representative TAZ.
Modeling responsibility: calculate the total number of workers within 30 minutes (all modes) for each census tract/TAZ. 
Time periods:
TAZs: All TAZs that represent Tracts (from and to)
 Output: table with the following columns:
1.	TAZ
2.	FIPS (Tracts)
3.	Total_High_Skill_Workers_within_30_mins
4.	Total_Med_Skill_Workers_within_30_mins
5.	Total_Low_Skill_Workers_within_30_mins
   
Indicator 4, travel time to PDX (ensemble gs)
Average travel time to PDX airport
DRC Responsibility: provide modelers with a list of representative TAZ for each tract
Modeling responsibility: calculate the travel times to/from each tract-representative TAZ to PDX (TAZ 139) 
Time periods: 
1.	7-8am Avg Travel Time TO	
2.	5-6pm Avg Travel Time TO	
3.	2-3pm Avg Travel Time TO	
4.	7-8am Avg Travel Time FROM
5.	5-6pm Avg Travel Time FROM
6.	2-3pm Avg Travel Time FROM
TAZs: 
1.	All TAZs that represent Tracts (from and to)
2.	PDX (TAZ 139)
Output: table with the following columns:
1.	TAZ
2.	FIPS (Tracts)
3.	One column for each time period listed above
DRC will average all six time periods for each tract for inclusion in EVA.

Indicator 5, Transit access to jobs (ensemble gr)
Transit Access to Jobs (minutes)
Measures transit travel times during peak hours to major employers and job centers
DRC Responsibility: provide modelers with a list of representative TAZ for each census tract
Modeling responsibility: calculate the average TRANSIT time To job centers from each census tract

Time period: 
1.	AM2HR Avg Transit Travel Time TO
TAZs:
1.	Concentrations of Jobs (job centers) are represented by the following TAZs: 1, 65, 139, 163, 195, 202, 299, 743, 868, 975, 1007, 1049, 1210, 1269, 1636
2.	Origin TAZs are all TAZs that represent Tracts
Output: Table with the following columns:
1.	TAZ
2.	FIPS (Tracts)
3.	Travel time (minutes) to each "jobs" TAZ or an average of all of them.

Indicators 6-7, jobs within 30 minutes (ensemble gv)
Methodology:
DRC Responsibility: provide modelers with census tract number of jobs in each category.  Data table will have both the census tract number and the representative TAZ.
Modeling responsibility: calculate the total number of jobs within 30 minutes (all modes) for each census tract/TAZ. 
Time periods:
TAZs: All TAZs that represent Tracts (from and to)
 Output: table with the following columns:
1.	TAZ
2.	FIPS (Tracts)
3.	Total_low_wage_jobs_within_30_mins
4.	Total_mid_high_wage_jobs_within_30_mins

Indicator 8, Travel in/out of the region (ensemble gt)
Average auto travel time in/out of 4-County region (minutes)
Measures how quickly goods and people can get to and from major exit and entry points of the region (highways)
DRC Responsibility: provide modelers with a list of representative TAZ for each census tract
Modeling responsibility: Calculate To/From each Tract-representing TAZ to entry/exit TAZs 
Time period: 
2.	HWY_Avg_Travel_Time_TO_7to8am 	
3.	HWY_Avg_Travel_Time_TO_5to6pm	
4.	HWY_Avg_Travel_Time_TO_2to3pm	
5.	HWY_Avg_Travel_Time_FROM_7to8am 	
6.	HWY_Avg_Travel_Time_FROM_5to6pm	
7.	HWY_Avg_Travel_Time_FROM_2to3pm
TAZs:
1.	Region Entry/Exit TAZs: 2132, 661, 963, 1434
2.	Origin TAZs are all TAZs that represent Tracts
Output: Table with the following columns:
1.	TAZ
2.	FIPS (Tracts)
3.	Column for each of the time periods above.  DRC will average them for inclusion in the EVA
