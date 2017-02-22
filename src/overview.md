﻿# WorkItem Updater

## Overview
The WorkItem Updater task updatesthe state for workitems linked to a build.  
Using this task developers don't need to manually keep track of the state.  
An example would be to set the state to 'Resolved' as the last step of a build and to 'Deployed' as the last step of a release.  
With this task it is possible to create an automated Kanban board as shown [here](https://bluebasher.com/Blog/Post/2017/1/devops_with_vsts_the_first_way_kanban#automated_kanban)  

## Settings
The task requires the following settings:
- WorkItem Type
  - Only linked workitems of this type will be updated.
- WorkItem State
  - The state that the workitem should be updated to.
- Move to board column Done
  - If the workitem is displayed in a Kanban column that has been split into Doing and Done, this indicates if the workitem should be moved to the Done column.