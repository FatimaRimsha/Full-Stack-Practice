# To-Do App Development Steps

## 1) Add HTML + CSS Elements

- Main Container  
- Input Box  
- Add Button  
- Task List Container  
  - Checked task  
  - Unchecked task  

## 2) JavaScript

- Import Input Box, List Container elements  
- Write `onClick` function **addTask** for Add Button:
  - If no input  
    - Clicked without value => alert message  
  - If clicked with value in input box =>  
    - Create list element `li` for task  
    - Save input box value to `li`  
    - Append task to `listContainer`  
    - Add sub-element to task to remove task  
      - Create element `span`  
      - Save value as cross icon code to `span`  
      - Append to list element  

- Write event listener for click:
  - Click on `li` element => toggle `checked` class  
  - Click on `span` element => remove parent element `li`  

- Write function to save tasks to `localStorage` using `setItem`  
- Call **saveTasks** function after every modification to `listContainer`  

- Write function to show existing tasks upon refreshing page using `localStorage.getItem`  
- Call **showTasks**  

   
        
       
