# Share of climate related questions asked in Indian Parliament
Read the full story here: [Little to debate.](https://junekim6.github.io/lithium-lifecycle/)

## Overview
An analysis of the quuestions raised by Indian Parliamentarians to understand how often questions around climate and environment are raised. 

The analysis shows the share of environment questions is still low and also bulk of the questions revolve around forests and wildlife. 

## Data Sources and Definitions
- **Title of the questions asked in Indian Parliament during Question Hour** - [Lok Sabha.](https://sansad.in/ls/questions/questions-and-answers)
    - The data includes all the questions asked and the share of questions for the Union Mininstry of Environment, Forest and Climate Change.
    - Data analysis can be found in the `data` folder under three file names:
    `year-on-year.csv` shows the overall quesitons asked and the share of the questions directed towards the Union Environment ministry.
    `category.csv` has  the breakup of the questions asked to the Union Environment ministry. The questions have been classified into nine categories depending on their type. 
    `parliament questions.csv` contains the raw data of the questions asked to the Union Environment ministry.

## Tools and Softwares
- I used **Playwright** to scrap the questions from a list available on the website. 
- I used **pandas** and **excel** to explore and analyze data.
- I used **Rawgraph**, and **Illustrator** to create and edit graphs. 
- I used **ai2html** to export data as svg. I used **scrollama** to create a scrollytelling experience using ai2html output.

## Folders
The `data` folder includes all notebooks for data cleaning and analysis.

## Contact
Please reach out to rajitsengupta@hotmail.com with any questions or concerns.
