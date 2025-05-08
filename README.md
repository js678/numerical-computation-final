# Fantasy Football ADP

### Name: Jack Savio

### CSCI 3656: Final Project

### RESTART KERNEL AND RUN ALL CELLS AT EVERY INSTANCE


This repository consists of a iPYNB file used for data manipulation and CSV files from multiple years of fantasy football data. These CSV files were collected and posted publically to Github and are about the fantasy statistics of players. The CSV files that I have used consist of all pertinent information to be used for draft analysis, such as yards, touchdowns, and other more qualitative variables. It also includes the dependent variable, fantasy football points, that is adjusted based upon the multiple independent variables mentioned above. For starters, I have decided to make a couple of initial alterations to the data sets that will allow for more accurate and concise observations:
1. I have removed all non-FLEX position(QB,D,K) from each section of the data set. Why? These positions in fantasy football drafting work incredibly different in comparison to other players in the league. Since each of these positions typically only have one per team, they are drafted with typically less priority as there are many positions available for a standard 10-12 person league. There ARE differences in drafting depending on player skill, but the variance between their actual fantasy scores and their ADP is so large and acts against the data. This will be explained in detail in the formal paper.
2. Injuries have also handled by making each player's average points be used over all sixteen games to create consistent results. This could have unforseen consequences, such as making some players have increased draft priority when they only played one game and had a out of character performance, but this was the best solution.
3. There are some other variations that have major impacts on ADP that are strictly non-data base. These variations will be noted in the paper and adjusted in more creative ways.

In the iPYNB files, I will be making small comments that describe the thought process behind why each numerical computation technique would be used.

Video link is here: https://o365coloradoedu-my.sharepoint.com/:v:/r/personal/jasa6380_colorado_edu/Documents/Attachments/final_project_numerical_computation.mp4?csf=1&web=1&e=lZaxv2&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D
