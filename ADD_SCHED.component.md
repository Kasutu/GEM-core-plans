# add schedule
#component 

export -> [[RENDERED TO SCREEN]]

- textInputs
	- title
	- description
	- pickTime

- toggleButtons
	- 7 buttons (array)

- [nav buttons](nav.component)
	- cancell -> [[TODAY.component]]
	- apply 
		- save data to async storage -> [[addSchedule.handler]] handler
		- return home -> [[TODAY.component]]]