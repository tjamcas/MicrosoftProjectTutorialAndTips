# MS Project Tutorials
## Video 23: Learn how to level resource over-allocations in MS Project
YouTube: <https://www.youtube.com/watch?v=dphqIbQQmXg&list=PL-MQNpO8Wb7BW0ndTYmwWpLV-WjW_4wxV&index=29>   
Presenter: Tom Stephenson
### How to level resource over-allocations
- Recall that when you setup a resource pool, a resource comprised of one fully allocated person is 100%. A resource comprised of five fully allocated people would be 500%
- When your task indicator flags a resource over-allocated condition, it means that the individual or team that comprises the resource has been assigned to work on more tasks than they have time to perform.
- You can allow Microsoft Project to automatically level the resources, however this could have two unintended effects that you as the PM may have difficulty seeing
  - Microsoft Project will lengthen the time to perform tasks
  - Microsoft Project in lengthening a given task may also split the task so the work timeline for the task is interrupted. This may not be desirable or even feasible.
- It is better to observe over-allocation errors, and manually inspect the timeline and manually level the resources.
- It is most helpful to have a split view of your timeline and resources:
  - From the Gantt Chart screen, select the `Task` tab in the Ribbon, and select the `Details` icon.
  - Right click on the left border are of the `Task Details Form`
  - Select `Resource Graph`. This will result in the Gantt Chart being displayed on the top panel, and the Resource Chart being displayed in the lower panel.
- With the Gantt/Resource charts split screen, select a task that is over allocated. View the lower resource chart to determine the over-allocated resource(s). The resource(s) will likely be assigned to multiple concurrent tasks.
- Adjust the percent of the resource assigned to the task(s) while being cognizant of the automatically adjusted duration. Adjust the duration if you think the task can be performed at a shorter duration. Optionally, add more resources to the resource pool if feasible to maintain the original duration.
