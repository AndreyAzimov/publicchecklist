# ✅ Public Checklist

## 🤔 Problem

Procrastination when trying to complete some goals, like:
- Complete coding course
- Go 30 days to gym
- Learn Englsih
- Lose weight

## ✅ Solution

Public checklist on your site where you know exactly what was done, how much is left and can share your progress with friends.

It'll auto sync with Google Sheets so you don't need to update HTML every  time.

All data is taken from Google Spreedsheet (iFrame) and updated automaticaly every 5 mins.

DEMO 1 (Coding Course): http://andreyazimov.com/freecodecamp

DEMO 2 (100 Push-ups Challenge): http://andreyazimov.com/100pushups

![Picture](https://raw.githubusercontent.com/AndreyAzimov/myprogress/master/pic.png)

![Picture](https://raw.githubusercontent.com/AndreyAzimov/myprogress/master/chart.png)

## ⬇️ Installation

1. Make a copy of a spreadsheet (File -> Make a copy). Here are some templates but you can make your own:
- [100 Push-ups Google Checklist (Google Spreedsheet template)](https://docs.google.com/spreadsheets/d/1OPdKJrqP5Mqb2W-v6GuZIoaPwlOZ5u-j8mp_zBuW_Nw/edit#gid=0)
- [Beta Free Code Camp Checklist (Google Spreedsheet template)](https://docs.google.com/spreadsheets/d/1fk4YFSs1f8YnTOpaRJa-2qePHE2J5MWxBzok-dYIVI4/edit?usp=sharing)

2. Get an iframe link of progress bar (File -> Publish to web -> Embeded -> progress-bar (Not Entire Doc)).

2.1 Copy link. Example: "https://docs.google.com/spreadsheets/d/e/2PACX-1vQanprHEXQ66_r2rflfCrdKcfV6FMLzCoKWJ8gLaU0CJX48Ov7j8Cdow-pSyA6NKwepVJiz-xc7JHBk/pubhtml?gid=2110731770"

2.2.1 Between: "<iframe src"" AND "&amp". Don't copy the whole iframe link.

2.3 Paste this link to progress bar section in index.html.


3. Get an iframe link of the checklist (same as progress-bar).

4. Open this index.html and verify that it works.

5. Try to change progress in basic-html-and-html5 tab. Put "DONE" in any task. Checklist tab in spreedsheet should change. Progress tab in spreedsheet bar should change. Result should be changed in index.html

## 🛠 Troubleshooting

- If there is an error on iframe make sure you copy the correct link
- If there is a white boder from the iFrame, play with the width and height below <iframe width=438 height=63 src="
- Ask me: twitter.com/AndreyAzimov
