# MS Project Tutorials
## Video 4: How to apply Resources & Costs to a schedule   
YouTube: <https://www.youtube.com/watch?v=FjCBCwD5Kzw>  
Presenter: Tom Stephenson
### How to set up a Resource Sheet
- ___Tip:___ Choose the different type of reports by moving your mouse all the way to the left of the currently open reports. Choose the different views of a report/sheet b right clicking on the square icon to the left of the column headers.
- To access the Resource Sheet, from Gantt chart view, right click to the left of the task table and select `Resource Sheet`. From here, you can document all the resources that will contribute to the delivery of the project
- Resource Sheet Table fields:
  - `Resource Name`
  - `Type`
    - `Work` - hourly
    - `Cost` - lump sum
  - `Group` - you can assign resources to a group like "employee", "sub-contractor", "temp", etc.
  - `Max.`, examples:
    - 1 man count = 100%
    - .5 (part-time) man count = 50%
    - 3 man count = 300%
    - Project will throw a flag if you try to exceed the `Max.` values when you assign resources to tasks
  - `Base` : assign the calendar to be used with the resource, the default is the "standard" calendar.
- With __"cost loading"__, you define the cost of the resources - hourly rates or cost per some unit measurement - and Project will calculate the accrued cost as you assign resources to a task. Not all projects use MS Project to track costs.  
- To assign resources to task, go to Gantt chart view, click on `Resource` tab in the ribbon, and select `Assign resources`. This will bring up a pop-up window with all your resources. Click on a task in the Gantt chart and select a resource in the pop-up window, and assign `units` (i.e., percent) or a cost, as appropriate, to the resource and click the `Assign` button.
- ___Warning:___ If you assign resources to a task, and then return to edit the task and increase the resources, Project will automatically and proportionally reduce the task duration. So, if you initially assign 1 full headcount (100%) to a 10-day task, and then later edit the task to assign 2 headcount (200%) because two bodies are needed on the task, Project will automatically interpret that to mean that the task can be done in half the time and reduce the duration to 5 days. BE aware, this may not be your intention.
- ___Best Practice:___ If someone will be assigned to a project heading full or part time and contributing to all the tasks in that heading, then assign the resource to the heading and not to the individual tasks below it. If a resource is specifically dedicated to a task, then assign the resource in the that task.
- ___Tip:___ While in the Gantt chart, to look at the cost view, right-click on the table cell (upper left-hand cell of Gantt table headings), and select `Cost`.
