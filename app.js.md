# app.js

- titleWrapper
	- title
		- hardcode txt
	- date
		- handled by [[getToday]] module

- cardsWrapper
	- cards -> [[cardsHandler]]
		- text
		- time range
		- ongoing indicator

- dashboardWrapper
	- button
		- today -> [[TODAY.component]]
		- plus -> [[ADD_SCHED.component]]
		- week -> [[WEEK.component]]

export -> [[RENDERED TO SCREEN]]