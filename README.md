# USCLAP-Submission---Chicago-Domestic-Violence

CODEBOOK for domvio_mut:

CASE.: Crime case ID number
DATE..OF.OCCURANCE: Date and time of the crime
BLOCK: Address where the crime took place
IUCR: Illinois Uniform Crime Reporting (4-digit codes that classify criminal incidents)
PRIMARY.DESCRIPTION: Nature of the incident
SECONDARY.DESCRIPTION: Datails of the incident
LOCATION.DESCRIPTION: General location of the crime (residence, store, street etc.)
ARREST: "Y if arrest took place; "N" if not
DOMESTIC: "Y" if crime was in a domestic setting; "N" if not
BEAT: number assigned to the police patrol territory
WARD: legislative district number
FBI.CD: Federal Bureau of Investigation Counterintelligence Division
X.COORDINATE: x-coordinate of crime location
Y.COORDINATE: x-coordinate of crime location
LATITUDE: latitude of crime location
LONGITUDE: longitude of crime location
LOCATION: (latitude, longitude) of crime location
MONTH: Month of the crime
DAY: Day of the month of the crime
YEAR: Year of the crime
DATEINT: Date as integer in the format YYYYMM
isPM: Time of the crime was past noon and before midnight
HOUR: Hour of the crime in 12-hr clock
isbeforecovid: Indicator value for if crime happened before COVID-19 hit Chicago (2019/7/10-2020/1/24) 0=no; 1=yes
isprelockdown: Indicator value for if crime happened after COVID-19 hit Chicago and before stay-at-home orders (2020/1/25-2020/3/21) 0=no; 1=yes
islockdown: Indicator value for if crime happened during strict stay-at-home orders (2020/3/22-2020/4/30) 0=no; 1=yes
isphase2: Indicator value for if crime happened during phase 2 of the pandemic (2020/5/1-2020/6/2) 0=no; 1=yes
isphase3: Indicator value for if crime happened during phase 3 of the pandemic (2020/6/3-2020/6/25) 0=no; 1=yes
isphase4: Indicator value for if crime happened during phase 4 of the pandemic (2020/6/26-2020/7/8) 0=no; 1=yes
isdomviolence: Indicator value for if crime is domestic violence 0=no; 1=yes
is9_5: Indicator value for if crime happened during normal workday hourse 9am-5pm 0=no; 1=yes
PERIOD: Period of crime (pre=isbeforecovid or isprelockdown; during=islockdown or isphase2; post=isphase3 or isphase4)
PHASE: Phase of crime (before_covid, pre-lockdown, lockdown, phase 2, phase 3, phase 4)