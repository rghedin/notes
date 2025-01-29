---
layout: post
title: "I went all in spreadsheets for personal finance"
date: 2022-08-10 11:24:13 -0300
---
The obscure, weird app that I had been using for five years to record my financial transactions failed to import data from the old phone to [the new one](https://notes.ghed.in/posts/2022/the-best-iphone/). I took this as sign: it was time to move onto a better solution.

Personal finance doesn't need to be complex, yet it's only useful with a pinch of automated calculations, consolidations, and charts. I started researching for a new app with low requirements: something simple, that allowed me to enter my transactions (expenses and income) and review them at the end of each month or specific period.

I downloaded almost every app of this kind available in the App Store. I didn't like any of them&ast;.

Then I remembered the good'n old spreadsheet, the software that keeps the corporate world running. Why not give it a shot?

Sometimes an advantage, sometimes a nuisance, the fact is that spreadsheets are super malleable, unlike personal finance apps. One frustration I had with the app I used to use, for instance, was the absence of a filter monthly expenses of only one category. On the other hand, the unlimited possibilities of spreadsheets can be paralyzing and, for those who are not familiar with its formulas and functions (which is my case), intimidating.

A little skeptical, I created a new spreadsheet and started recording transactions of the current month, one by one, row by row, in five columns: date, account (savings, wallet, credit card etc.), category, to/from, amount, and comment (optional).

Once this was done, I started messing around with pivot tables. In a few clicks and with some look ups at the documentation and YouTube tutorials, I had in front of me consolidated data of the month's expenses, divided by category, all pretty, exactly the way I always wanted. Also, I found the function `SUMIFS`, which helps to make more specific, permanent filters, very cool.

Filters are also nice. When in the future, inevitably, I have to complain about wrong invoices and undue charges with the phone company, for example, I can quickly create a filter with its name in the to/from column to see, there, all the history of payments made.

Charts? Nothing too difficult. Finally I have at my disposal the evolution of expenses in a single category, which I missed in the weird app I used before. It allowed me to see the damage that going out to eat a lot in February caused to my budget and that, despite the incessant food inflation in Brazil in 2022, we have been able to maneuver the groceries (“Mercado”) list and keep this budget more or less stable.

![Chart of groceries and eating out expenses in 2022.](/assets/2022/spreadsheets-personal-finance/grafico-gastos-restaurantes-mercado-planilha.png)

I have already transferred all the data from this year to the spreadsheet and will do the same with previous years, bit by bit. Could I try a direct import? Yes, but I am taking advantage of the manual work to recategorize transactions in a simpler structure.

Restaurant expenses, for example, I used to split it into three categories: “Eating out”, “Delivery”, and “Cafes”. Now I have consolidated them all into “Restaurants”. I think it is important to adjust the detailing to keep it useful without making the work of recording overwhelming.

I've flirted before with the idea of recording expenses in a spreadsheet. That time, I failed. This time, it looks like I'll succeed. I attribute the success of my last attempt to [this article](https://medium.com/macoclock/how-i-plan-my-monthly-budget-with-numbers-6365c17daf2c) by Denisa Blackwood, a data scientist who is not a fan of spreadsheets and who only made peace with them when using Numbers, the “Apple's Excel”. It's nicer indeed, but Excel would do just as well — and is probably more powerful than Numbers.

It wasn't for Numbers, specifically, but the approach, which she calls “minimalist” — and I, less controlling —, that I succeeded this time. A big hindrance in the previous one was that I, used to the workings of that old app, was trying to reconcile my spreadsheet balance with the actual ones, manually.

Not that it is impossible, but reconciliation makes the work much more difficult and prone to errors. On any given day, that monthly dollar bill that changed a few cents due to exchange variation throughout the day generates a misalignment that may be really hard to find and fix. It was always maddening when something like this happened; most of the times, I recorded a transaction called “Adjustment” with the amount difference and that was it.

In the new spreadsheet, with Denisa's approach, I only control expenses. The consolidation I leave aside, using another spreadsheet I created for tracking my assets monthly. They are related things, but not necessarily inseparable — at least I think so.

As a side effect, I was able to uninstall the finance app of my phone and protect the spreadsheet with a miles long password. I don't do as many transactions per month (less than a hundred) and I am in front of a computer almost every day, so it is feasible to leave it to those times.

***

&ast; Actually, I quite enjoyed [GreenBooks](https://greenbooks.app/) and ended up having to decide between this app and spreadsheets. Decided to go with spreadsheets, but… maybe an app in the future?

_Discuss @ [Hacker News](https://news.ycombinator.com/item?id=32432898)._