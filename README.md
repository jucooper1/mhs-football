# mhs-football

## overview
Mishawaka High School is a 4A/5A football program in Northern Indiana. They compete in the Northen Lakes Conference (NLC). The current head coach has been in that position since 2018. I moved back home and joined the program in 2019. Since then I have been the Director of Football Operations, but also the lead, and only, data analyst. I have data going all the way back to 2018, in various formats, of us and our opponents. In 2024, I took over as Special Teams Coordinator and the data analysis work has taken a back seat, due to time constraits of being a coordinator. 

## process
We use Hudl for our film software. All games get recorded and uploaded into Hudl. All of our opponents also use Hudl and we share film through it, making it a one stop shop for our film data. In Hudl, there are columns that we can use to "tag" data. There is also the option to create our own columns. Below are the steps I use in our Data Process Life Cycle.

1) Tag film in Hudl - This usually consists of me, and other coaches, tagging the information we need, like down, distance, formation, play, etc. Each play gets tagged with its necessary information.

2) Once a game is complete in Hudl, I can download the data as an Excel spreadsheet.

3) In Excel, I clean the data and add some columns. I have steps I go through to make the data ready for use. I have some columns I add, like season, week, offense, defense, score difference, and others. Once I get the columns I need added, I clean up some of the columns. For example, we have a formation called King and another called Queen. They are the same formation, just King is right and Queen is left, so I find and reaplce Queen for King. Form strength has its own column, so the distinction is redundant and it helps grouping them together later on. I've thought about trying to automate some of this, since I do it all manually, but doing it manually helps me process the information and get an idea of the game, from a data perspective.

4) Once the data has been cleaned and edited, it is ready for use. This last season I added the cleaned data to a master spreadsheet that is linked to Power Bi. In Power Bi, I made dashboards for the offense and defense. I've included screenshots of those, as well as the latest files. I'm still modifying them and trying different visualizations/intersections of data. I also have a MS Access file with a lot of older data. The upkeep of this database is what was sacrificed when I became a coordinator. I'm not sure I've updated it since 2023. I know 2025 is not in there. I've also included that file.

5) Now that the data has been extracted, cleaned and loaded, it is now set to be used. Me and head coach are the primary users of the data. We use it to make decisions about game management. For example, we look at our offense vs their defense and how we feel about the matchup to determine 4th down strategy and 2pt decisions.

## screenshots
<img width="1053" height="592" alt="Off1" src="https://github.com/user-attachments/assets/9a554511-cfc2-4a1c-97ab-83950a1e4b4a" />
This is one of the offensive dashboards. In the top left there are dropdowns to filter by season, or opponent (defense). There are tiles of yards/play, yards/game and success rate for total offense, rushing and passing. These are just general data for reference. There are also two matrices for formations and plays. We can use these to determine which formations/plays are more or less successful. We can then go back and see what we are doing well or poorly and make changes to our schemes. At the bottom is our weekly yardage. The visualizations are interactive, so clicking on a formation will filter the plays to only that formation, and vice-versa.

<br><br>

<img width="1156" height="593" alt="Off2" src="https://github.com/user-attachments/assets/482b0035-4113-40ef-84b1-fe7888f5099f" />
This is the dashboard I use for formation tendencies. I can filter by season or opponent. At the bottom are the formations. There is also a level up for personnel if we wanted to look at that. Clicking on the formation at the bottom filters the top visualizations for that formation. From this we can determine if we have any glaring tendencies in play calling in that formation. 

<br><br>

<img width="1055" height="597" alt="Def1" src="https://github.com/user-attachments/assets/f821ed67-da78-40e2-be95-b2465f69e7e7" />
This is our scouting dashboard. We use this to look at tendencies and trends for our upcoming opponents. In the top left we have filters. We also look at who their main ballcarriers are as well as positions, all filterable for situation. In the bottom left we can see what areas of the field they like to attack, also filterable. We also have data on plays and formations.

<br><br>

<img width="1108" height="907" alt="Screenshot 2026-05-08 10 38 01 AM - Display 1" src="https://github.com/user-attachments/assets/14f32c00-3a44-47e9-9e3b-4d96632181cc" />
This is my Special Teams dashboard I use during the season. I print this off for Fridays to let me know what to expect. I also use it to gameplan. My school has chromebooks, so I made this in Google Sheets so I can work with it at school. Here is the link to view the Google Sheet. https://docs.google.com/spreadsheets/d/125OBW1mrovEvSRMBVQwYfdI8BvsgQEJbEWDJXPtkVTQ/edit?usp=sharing

<br><br>

<img width="1258" height="706" alt="Screenshot 2026-05-08 11 15 11 AM - Display 1" src="https://github.com/user-attachments/assets/fe6c4699-7e41-4028-9dae-fc6498e9a849" />
I also created Google Sheets our coaches could use to grade our athletes. It's very simple. They fill in the week of the game and what play number it is and then select the player by jersey number from a drop down. After that its just check boxes. This is our DL grading sheet. We grade them on alignment, assignment and effort (everyone in the program gets graded on those) and then their position specific skills are first step, hand placement and pad level. We also use it go count loafs. The skills are weights and they get a grade for that play. This is then used to calculate their grade for each skill and also their weekly grade. We can use this to determine what needs to be worked more in practice.

<br><br>

<img width="1304" height="727" alt="Screenshot 2026-05-08 11 22 48 AM - Display 1" src="https://github.com/user-attachments/assets/18ca11ef-b2b2-4e43-be41-662851caca1a" />
This is a sample of the grade report they get each week. It's a query that shows all of the plays they are in as well as how they graded in each category.

<br><br>

<img width="1136" height="604" alt="Screenshot 2026-05-08 11 19 25 AM - Display 1" src="https://github.com/user-attachments/assets/829a2e2a-7676-4555-8425-ef6dd76aff33" />
Here is the cumulative grades. Names have been cropped out for privacy. You can see how well each player did with each skill as well as each week.
