## Scheduling Dashboard.

The scheduling dashboard lists all **SOLD** leads that are not achieved and not completed by production (_leads who that are
marked as production complete will not appear in any column on this dashboard._)

#### How leads are placed in columns.

**Please Note**:`The explanations below are in order of what takes precedence over the other when placing leads in the
dashboard columns`.
- If a lead is marked as a dead deal by order-processing, it will appear in the alert column.
- If a lead is marked as complete by production by clicking on the `Complete button` in the right bottom of the basic tab,
the lead will be placed in the finished column.
- If a lead is marked as a `To Be Saved` by confirmation, it will be placed in the `To Be Saved` Column.
- If all the leads active job installation dates under the schedule tab are verified by production, the lead will be 
  placed in the `Verified` column.
- If the `primary lead's job type` date of installation is provided, the lead will be placed under the `Scheduled` Column.
- Any lead that doesn't have the above checks and is marked as SOLD, it will appear in the `New Sales` Column.

![Scheduling Dashboard screenshot](/scheduling/images/scheduling-dashboard.png?raw=true "Scheduling Dashboard")


##### List of the Column Names.
1. Alert, 
2. Scheduled, 
3. Verified, 
4. In Progress, 
5. To Be Saved/Questions and,
6. Finished.

##### Visible tabs when you click on a card from any column.
1. **Basic info Tab**.
   * This tab shows the basic information about the lead.
   * The tab also includes two buttons,
     * The on-call switch which when turned on, it will place the lead on call, and the lead will also appear on the on-call
    list page.
     * Complete project, this button marks a lead as production complete (_mark the lead as completed by scheduling_).
   * The tab also has a project activity section which shows dates of installation for active jobs,
     Footage/Number of sheets/Units and `Actions that allow for addition of Concerns and printing of work orders` for
     every active job type.
     
     ![Basic Info Tab screenshot](/scheduling/images/basic-info-tab-scheduling.png?raw=true "Basic Info Tab")
 
2. **Schedule Tab**.
    * This tab lists all job types that production can schedule for the lead, it allows production to turn on jobs that
    confirmation didn't turn on as well as updating dates of installation for jobs that confirmation selected.
    * Actions that are supported on this tab include.
        * Confirming dates of installations for job types.
        * Adding Arrival times for crews.
        * Adding estimate durations to complete a job.
        * Update actions that include `Canceling` and `Completing` individual jobs.

   ![Schedule Tab screenshot](/scheduling/images/schedule-tab-scheduling.png?raw=true "Schedule Tab")

3. **Comments Tab**.
    * This tab shows comments added to lead as well as allows users to add their own comments on the lead.

   ![Comments Tab screenshot](/common/images/comments-screenshot.png?raw=true "Comments Tab")

4. **Files Tab**.
    * This tab allows users to upload individual files for a lead.
    * The files tab allows users to create and upload files inside folders.
    ##### Creating and uploading new files.
    - To create a new folder, click on the `Add new` button in the right bottom of the tab and click `New folder`.
    - Double-click on a folder you'd want to upload a file into.
    - Click the `Select files` button to select the file you'd want to upload. (_you can select or add multiple files to upload_)
    - Click the upload files button to upload the files to the server.
    - Then click the `Save button` in the right bottom corner of the tab to persistently save your changes.

    ![Files Tab screenshot](/common/images/files-tab-screenshot.png?raw=true "Files Tab")

###### Notes
* _The Scheduling Dashboard can only be viewed by users Admin or Production level users (users with the role of
  Production/Admin)_
* _this page has search functionality from which once can leverage on to filter lead records basing off of the
  desired filter field_
