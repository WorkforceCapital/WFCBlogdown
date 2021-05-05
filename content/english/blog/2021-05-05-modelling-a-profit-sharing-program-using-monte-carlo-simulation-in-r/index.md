---
title: Modelling a Profit Sharing program using Monte-Carlo simulation in R
author: ''
date: '2021-05-05'
slug: []
categories: []
image: images/blog/monte-carlo.jpg
tags:
- People Analytics
- Rstats
- Business Analytics
description: This is meta description
---
Recently, I was involved in designing a Profit Sharing program for my client.

In the past, for this type of assignment, I invariably used a deterministic model, probably the behaviour/legacy of my business analyst training.

Watching a Tidy Tuesday screencast on youtube with David Robinson* inspired me to use Monte Carlo simulation. I decided to give it a try, and it was well worth it.

The use of simulation has allowed us to test the program and ensure that it will work as intended regarding:

- 👉 Predicting the baseline on which contributions to the profit pool will be based.
- 👉 Setting the threshold for the Entities' performance, taking into account the efforts necessary to achieve the goal (Fairness).
- 👉 Predicting the percentage to be shared. The amount of Profit distributed to different employees in the organization (by Entity).

Next time when you have an assignment in uncharted territory, summon Monte-Carlo.

"It's fine now. Why? Because I am here!**" Monte-Carlo

*The Riddler: Simulating a circular random walk.
**All Might in "Izuku Midoriya: Origin."

#rstats #peopleanalytics #businessanalytics
