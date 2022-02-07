#component 

- if on today
	- change color in today button
	- disable onpress capability on this.button

- else 
	- change color in week button
	- disable onpress capability on this.button

onpress goto -> [[TODAY.component]] || [[WEEK.component]] || [[ADD_SCHED.component]]