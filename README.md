# Critical Incidents in Youth Mental Health Facilities in Utah

[Story](https://www.apmreports.org/story/2021/06/23/provo-canyon-school-utah-teen-concussion): Utah Found Few Rule Violations for Years<br /> 
Data Reporter: Will Craft, wcraft@apmreports.org<br /> 
Data Analysis Fact Checker: José Martínez, martinez307jose@gmail.com

As my first project for APM Reports, I fact-checked my supervisor's data work for an investigation. I used pandas to find the number of critical incidents per year, the number of incidents by facility, and the number of investigations related to sexual misconduct or abuse. I then used Altair to visualize data.

"Up until 2019, the agency regulating Utah’s massive youth treatment industry rarely cited facilities for violating rules — even after cases of abuse. After a 2016 incident left a teenager with a concussion, state regulators listened to his mom’s complaint — and then did nothing about it."

"The lack of enforcement came to light thanks to a trove of never-before-seen records published this year by The Salt Lake Tribune, APM Reports and KUER. The three news organizations joined forces to publish five years of inspection reports and citations for rule violations from the 159 residential and wilderness programs that operated in Utah during that time period."

### Data Overview

The raw data was obtained through a records request made by APM Reports. Dozens of pdf files were scraped into the following spreadsheet: "cleaned_critical_incidents.csv"

The spreadsheet contains all the critical incidents reports filed by youth mental health facilities around Utah. The spreadsheet contains the following:
• Facility
• Investigation name
• Summary of the incident
• Conclusion
• Timeline concerning the start and end date of the investigation
• Date that the incident occurred.

With that information, we used pandas to filter investigations by facility, filter investigations by year, and filter investigations concerning sexual abuse or conduct by year. Analysis can be found [here](https://github.com/dv7jose/Critical-Incidents-Provo/blob/main/Utah_Practice.ipynb).

It's important to note that the final chart in the story has different numbers than the original analysis. Reason being, the leading reporters added notice of agency actions from https://hslic.utah.gov/notices-of-agency-action. That is not reflected in this analysis.
