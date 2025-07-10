Steps 
1) Add HTML+CSS elements
   Main Container
   Input Box
   Add Button
   Task List Container
      Checked task
      Unchecked task
2) JavaScript
   import Input Box, List Container elements
   Write onClick function 'addTask' for Add Button.
   	no input
        clicked without value => alert message
        clicked with value in input box => 
		create list element 'li' for task
		save input box value to li
		append task to listContainer
		add sub element to task to remove task 
			create element 'span'
			save value as cross icon code to span
			append to list element
   Write event listener click
        click on li element => toggle checked class
        click on span element => remove parent element li
   Write function to Save Tasks to localStorage using setItem
   call SaveTasks function after every modification to listContainer
   Write function to show existing tasks upon refreshing page using localStorage getItem
   call ShowTasks 
   
        
       
