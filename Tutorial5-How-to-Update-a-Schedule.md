# MS Project Tutorials
## Video 5: How to update a schedule   
YouTube: <https://www.youtube.com/watch?v=YtTYfXA1b58>  
Presenter: Tom Stephenson
### How to update a schedule
- Setting the initial baseline
  - From the Gantt chart, right-click the Gantt table (upper left box in the headers), and select the "Variance" screen.
  - On the Microsoft Project ribbon, select the `Project` tab.
  - Select `Set Baseline`, which will generate a pop-up window
    - You have the option for setting the baseline for the entire project or selected tasks. For the initial baseline, you accept the defaults in the dialog box and baseline the "Entire project".
    - In the Variance table screen, the Baseline Start and Baseline Finish columns had values of "NA" prior to setting the baseline. Now the columns will copy the values from the Start and Finish columns
- Updating the project schedule
  - In the `Project` tab of the Ribbon, enter the appropriate date in the `Status Date` field. Prior to the first update, `Status Date` will have a value of "NA". You can enter your schedule updates before or after the `Status Date`, but it is a best practice to enter the data as close as possible to the `Status Date`.
  - Best Practice: IT is a best practice to display a vertical line that represents the Status Date in the bar chart area. Right-click in the bar area of the Gantt chart, select `Gridlines`, and choose "Status Date" from the pull down, and select a color and appearance (solid or dashed line with desired thickness).
- Tracking the schedule
  - From the Gantt chart, right-click the Gantt table (upper left box in the headers), and select the "Tracking" screen.
  - In the Microsoft Project ribbon, select the `Task` tab.
  - It is helpful to Right click the Gantt Chart columns and add the "Duration" and "Indicators" columns.
  - From this screen you can select tasks and update their % completion, actual start and finish dates, and durations. For example if a task is underway but is expected to have an additional five days of duration, you update the duration and percent complete.
  - ___Best Practice:___ Update the oddball tasks that have changes in dates, durations, notes, etc., first. Then select the rest of the tasks and select the `Mark on Track` button. This will update all tasks to the left of the status date line so that they show as being on track -- this will update the "Actual Start",  "% Comp.", and "Actual Finish" (if % Complete = 100%).
  - After updates have been entered, you will want to see the variances in the schedule (and potentially the cost). From the Gantt Chart, right-click the Gantt table (upper left box in the headers), and select the "Variance" screen. Now, you can see the Start Variance and Finish Variance.
  - For a better bar chart display of the baseline plan and the actual schedule status, right click to the left of the tasks, and select "Tracking Gantt". Then, right-click the Gantt table (upper left box in the headers), and select the "Variance" screen. You are now looking at the Tracking Gantt report with Variance view. For each task it will show the original baseline dates and bars along with the actual dates and bars.
