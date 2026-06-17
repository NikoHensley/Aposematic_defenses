# Aposematic_defenses
Data and R Markdown for analysis of fish feeding trials

This file accompanies the R Markdown file: Aposematism_workbook.Rmd
This file accompanies the data: 2025june11_recopy_data_raw.xlsx

General overview of the data are:
Observations collected for multiple individuals of multiple species of fish during feeding trials where fish were presented with multiple food types consecutively. For each feeding presentation (a single food type with a specific food treatment), the fish were observed for 1 min in 20 s intervals. A fourth time interval ~8-10 min. later was used to record the final outcome of the feeding presentation for the food. There were 2 food types, and 4 food treatments, resulting in 8 different prey given to each fish in their trials, along with 2 positive controls. Fish has a pre-trial series testing food types under a different protocol, and then were given food under trial conditions with a finalized protocol that was standardized across all trials.

## Data columns are:
1. date: date of food presentation
2. ind_id: individual fish ID number along with a single letter code for the species	
3. trial: number of trial, i.e. number of days in the lab experiencing pre-test or test conditions
4. trial_time: time of day of trial (binary: day or night)	
5. trial_protocol: feeding protocol (categorical: pre-trial, water protocol, ostracod protocol). The three categories represent different methods used to train fish to take food, and to see which food types fish would generally respond too. Date in analysis are from the "ostracod protocol".	
6. food_sample: categorical coding of the type of food (i.e. worm, ostracod, fish, mysid shrimp, etc.)	
7. treatment: categorical coding of the food treatment (i.e. control, alive, anaesthetized, frozen, or boiled)	
8. type: categorical coding of the food type (i.e. control, luminescent, nonluminescent)	
9. order: order within a trial of the presentation of the food items	
10. time_point: observation interval (i.e 1,2,3, and 4 where 1,2,3 correspond to 20, 40, and 60 s respectively)	
11. eaten: binary response of if the food item was eaten at the time_point (yes or no). Left blank if food was eaten in previous time point	
12. num_attacks: number of fish attacks on food item per observation interval.
13. luminescence: binary response if at least one luminous response was observed in the observation interval
14. num_luminescence: number of luminous responses observed in the observation interval
15. notebook_page: page number of the notebook where field data was recorded into (for record keeping purposes only)
