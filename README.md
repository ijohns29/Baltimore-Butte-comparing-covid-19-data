# Baltimore-Butte-comparing-covid-19-data using county level data from New York Times Covid-19 Data - US Counties and States 
Comparing Covid-19 data in Baltimore, MD and Butte, MT from year 2020
## __Isaac Johnson__ 
### __Mini Project #1 - Data Trends and Visualization with Excel__
### Decision Analytics
### EN.663.667 (02)
### 2020.11.14

# Background



# Business Question
__How can a manager or HR personnel decide whether to approve an employees travel request plan based on submitted flight data or travel itinerary and what benchmarks should they consider when deciding?__

# Data Question - Open Data
Data may come from the below sources:
1. __New York Times Covid-19 Data - US Counties and States__: The New York Times provides Covid-19 data, both live and historical, for the Covid-19 epidemic occuring within the USA + territories during year 2020. Data is available on national, state and county level and available data has been tracked since the epidemic started in January. This data comes from reports from state and local health agencies. Due to shortages of tests that were available the data may not reflect full extent of epidemic.
  i. The data used will be historical data. This data does not include results from current day but does include results up to current day. There will be no distinction made between probable cases and/or lab confirmed cases. 
2. __Press releases from state and local authorities__: These posts will be sourced from government websites or local websites where the executive orders or briefings are made available. The City of Baltimore Executive orders can be found [here](https://www.baltimorecity.gov/executive-orders), Maryland state press briefings can be found [here](https://governor.maryland.gov/coronavirus/), updates on status of reopening in Montana can be found [here](https://covid19.mt.gov/joint-information-center), and information on Butte, MT can be found at county level by looking at Silverbow county data [here](https://www.co.silverbow.mt.us/2167/COVID-19).


# Data Question - Analysis
Microsoft Excel will be used for data analysis
- __What has the previous month's trend been in terms of covid cases?__ This will look at daily cases at state and county level to see whether the region is entering danger zone and look at [incidence](https://www.cdc.gov/coronavirus/2019-ncov/downloads/global-covid-19/SARS-CoV-2-Transmission-Metrics.pdf) defined as "the occurence of new cases of a disease over a specified period of time" and mathematically defined as ((number of new cases of disease during specified period)/(by size of population at start of period)) * 100,000 gives you cases per 100,000 population. By using incidence rate can compare different regions. The population size is based on census data last taken in 2010 found here for [SilverBow county](https://www.census.gov/prod/cen2010/cph-2-28.pdf), [Baltimore City/Anne Arundel County](https://www.census.gov/prod/cen2010/cph-2-22.pdf), [Georgia](https://www2.census.gov/library/publications/decennial/2010/cph-2/cph-2-12.pdf), and [Utah](https://www.census.gov/prod/cen2010/cph-2-46.pdf). The data from NYT is reported in terms of __cumulative__ cases so daily difference must be taken to get daily new cases. Sometimes a person is later reclassified to different county, state etc so this explains a decrease in cumulative cases over time that may occur throughout data.
- __What is the previous month's trend for deaths and ICU capacity?__ This will look at daily reported deaths and percentage of ICU beds at state or county level (as available) to provide idea about whether state/county health agencies are in danger of being overwhelemed.The Department of Health and Human Services (HHS) provides state level data on this [here](https://healthdata.gov/dataset/covid-19-estimated-patient-impact-and-hospital-capacity-state). 
- __What have been the previous month's recommendations from Governor or Mayor?__ This will provide an idea of how proactive government agencies are being at handling pandemic and allow for travel/post travel plans to be made so that the spread of Covid-19 can be limited and travel can be conducted safely or with minimized risk

# Data Answer
The data is organized geographically by Federal Information Processing Standards [FIPS](https://www.census.gov/library/reference/code-lists/ansi/ansi-codes-for-states.html) State Numeric Codes. In this case we are concerned with Maryland (FIPS - 24) and Montana (FIPS - 30). [County level](https://www.nrcs.usda.gov/wps/portal/nrcs/detail/national/home/?cid=nrcs143_013697) FIPS data is available here. This allows the analyst to look at specific regions of travel e.g. Baltimore City (considered county equivalent), Silverbow County (Butte, MT and Bert Mooney airport (BTM)), Anne Arundel County (Baltimore/Washington International Thurgood Marshall (BWI) airport), as well as the airport layovers for example Salt Lake City airport (SLC, Salt Lake County) and Atlanta  
# Business Answer
Using this data analysis the company personnel can examine regional trends regarding Covid-19 outbreak and assess the level of risk that the employee may be subjecting themselves to during their travel. The manager should be aware this data analysis may not indicate emerging outbreaks as these tend to flare up suddenly. Furthermore this assessment does not make any assumptions regarding employee behavior during travel, which will likely be the largest factor that will impact Covid-19 risk. It's recommended that travel be approved or rejected based on trends and local guidance and then reassessed within one week of departure date to see how the outbreak has evolved and plans adjusted accordingly. Organizational guidance regarding holiday travel can be found [here](https://hub.jhu.edu/2020/10/20/covid-19-winter-holidays/?mc_cid=295c6bc1e2&mc_eid=4aff72f931)  
