# My Progress

## 🤔 Problem

Procrastinating when try to complete some goal like:
- Complete coding course
- Go 30 days to gym
- Learn Englsih
- Loose weight

## 🛠 Solution

Public checklist on your site where you exactly know what was done and how much left.

It's auto sync with Google Sheet so don't need to HTML update it every  time

This is a template of a landing page where you can share your progress of Beta freeCodeCamp Course 

All data is taking from Google Spreedsheet (iFrame) and update it automaticaly every 5 mins

DEMO 1 (Coding Course): http://andreyazimov.com/freecodecamp

DEMO 2 (100 Push-ups Challenge): http://andreyazimov.com/100pushups

![Picture](https://raw.githubusercontent.com/AndreyAzimov/myprogress/master/pic.png)

## Instalation

1. Make a copy of a spreadsheet: https://docs.google.com/spreadsheets/d/1fk4YFSs1f8YnTOpaRJa-2qePHE2J5MWxBzok-dYIVI4/edit?usp=sharing (File -> Make a copy)

2. Get an iframe link of progress bar (File -> Publish to web -> Embeded -> progress-bar (Not Entire Doc))

2.1 Copy link. Copy only this: "https://docs.google.com/spreadsheets/d/e/2PACX-1vQanprHEXQ66_r2rflfCrdKcfV6FMLzCoKWJ8gLaU0CJX48Ov7j8Cdow-pSyA6NKwepVJiz-xc7JHBk/pubhtml?gid=2110731770"

2.2.1 Between: "<iframe src"" AND "&amp". Avoid copy hole iframe link

2.3 Paste this link to progress bar section below


3. Get an iframe link of of checklist (same as progress-bar)

4. Open this index.html and check if this works

5. Try to change progress in basic-html-and-html5 tab. Put "DONE" in any task. Checklist tab in spreedsheet should change. Progress tab in spreedsheet bar should change. Result should be changed in index.html

## Troubleshooting:

- If there is an error on iframe make sure you copy correct link
- If there is a white boder of iFrame play with width and height below <iframe width=438 height=63 src="
- Ask me: twitter.com/AndreyAzimov
