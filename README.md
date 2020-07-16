# Data on Iran's COVID-19 (coronavirus)
On 19 February 2020, Iran reported its first confirmed cases COVID-19. The [CSV](https://github.com/smajidi/Iran-COVID-19-Data/blob/master/Iran_Dailly_Covid19_Stat.csv) 
file contains the daily updates of Iran's Corona stats provided by Ministry of Health and Medical Education. It includes stats about number of infected cases, deaths, recoveries and testings. We will continue to publish up-to-date data throughout the duration of the COVID-19 pandemic.

<b>Visual Dashboard:</b><br>
- https://www.statsminute.ir/coronanegar.html
- https://www.statsminute.ir/coronanegar-en.html (Data on this dashboard is based on the [COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University.](https://github.com/CSSEGISandData/COVID-19)

## Codebook
Column|Description
------|-----------
Persian_Date|Date of observation in Iran's official date (The Solar Hijri calendar)
Gregorian_Date|Date of observation
Total_Cases|Total confirmed cases of COVID-19
New_Cases|New confirmed cases of COVID-19
Active_Cases|Equlas to Total_Cases - (Total_Recovered + Total_Deaths)
Total_Recovered|Total recovered patients
New_Recovered|New recovered patients
Total_Deaths|Total deaths attributed to COVID-19
New_Deaths|New deaths attributed to COVID-19
Outpatients|Number of new outpatients
Inpatients|Number of new inpatients
Total_Tests|Total tests for COVID-19
New_Tests|New tests for COVID-19
caseTotest|Equals to (New_Cases / New_Tests)
Critical|Number of patients wth serious condition

## Changelog
 - On 19 February 2020 (30 Bahman 1398) Iran's MHME started reporting of daily stats about total and new infected cases, recoveries and death. 
 - From 26 March 2020 (7 Farvardin 1399) number of critical cases was added to the daily reports.
 - From 7 April 2020 (19 Farvardin 1399) number of total tests performed was added to the daily reports.
 - From 15 May 2020 (26 Ordibehesht 1399) number of daily inpatients and outpatients were added to the daily reports.

## Update frequency

* Once a day around 12:00 (UTC).

## Authors

This data has been collected, aggregated, and documented by Saeed Majidi, Shahrzad Jahangard, Alireza Kadivar and Majid Pourkashani.
