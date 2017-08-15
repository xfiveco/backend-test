# Simple currency conversion Rails app

The task is to implement following Rails application.

The app should fetch and display currency conversion rates. To get rates you need to use the free API: [fixer.io](http://fixer.io)

The app consists of two pages: first one is currency conversion rates, the other one is a management page.

## Page 1: Display
Display all conversion rates in format:

| Currency 1 | Currency 2| Rate |
| ------ | ----- | ----- |
| USD | EUR | 0.922 |
| PLN | CZK | 6.204 |

Below, display a link or button that will redirect to page 2.

## Page 2: Manage
Allow to add conversion pairs like:

[USD] [EUR] [+]

where [USD], [EUR] are selects letting you pick conversion pair, and [+] is a button saving it.

Below, list all added conversion pairs and allow the user to remove them with click of a link or a button.


## Requirements
- Conversion rates should be saved in the database and refreshed with Rake task. It **cannot** be fetched in time of loading Page 1.
- Conversion pairs should also be saved in the database.
- You can use any DB engine you want (SQLite, MySQL, Postgres…).
- Use newest stable Rails version.
- Use TDD.
- Don’t worry too much about front-end but if you want to make a good impression you can use something like Bootstrap.
- Make sure README includes all required steps to run your app on Unix-like environment. We’ll do our best to run your app on our computers, but if you use something non-standard you should let us know about it.

## Project Deadline
Take your time but try to deliver it within 2 weeks time. If we don't see any activity in your test repository after 2 weeks (at least initial commits), we will automatically withdraw your application.

