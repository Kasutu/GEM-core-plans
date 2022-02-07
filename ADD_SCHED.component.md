# add schedule page
#component 

- textInputs
	- title
	- description
	- pickTime

- toggleButtons
	- 7 buttons (array)

- navigation

cancell or apply
- if on today
	- change color in today button
	- disable onpress capability on this.button
		- cancell -> [[TODAY.component]]

- else 
	- change color in week button
	- disable onpress capability on this.button
		- apply 
			- save data to async storage -> [[addSchedule.handler]] handler
			- return home -> [[TODAY.component]]]