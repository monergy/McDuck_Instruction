## Confirmation Dashboard

Confirmation is the department responsible for the initial handling of the customers and
executes the following tasks:

#### The Dispo page.
* The dispo page shows all the scheduled lead appointments that were run or yet to be run by salesmen.
* The calendar on the Dispo page is plotted, Salesmen against time windows [`8AM - 8PM`].
* The page has salesmen displayed in the alphabetical order of their names.
* Lead appointments are placed in their right timeslots for their scheduled appointments, click on the lead card to adjust its appointment.
* The calendar also shows booked time off for salesmen, on these booked days, a salesman can not be scheduled for an appointment.
* The current day's Dispo page can also be printed by clicking the `Print` button up top to print the calendar.
* Manoeuvrability of the calendar can be achieved by:
  1. Clicking on the arrow button right above the calendar, right arrow to visit next in days, and the left arrow to visit previous days.
  2. Clicking the date picker to select the date of your choice.

![Dispo Page screenshot](../../confirmation/images/dispo-page-confirmation.png?raw=true "Dispo page")

#### Colors on the cards.
- _White_: This is the default color for any card on the dispo page, and it is only shown when the lead card's status is `SCHEDULED`.
- _Green_: Means that the card is SOLD and not there is no saving being run on it.
- _Light Yellow_: Means the lead has been lost / marked as lost by confirmation, the Lead is a DNS, PDNS, NE, CTC, CTR, 
  UNAVAILABLE, and RESET.


#### Information displayed on the cards.
- lead's name.
- lead's phone number.
- lead's city
- original lead's customer number if a lead is rescheduled.
- To Be Saved / Question information if any and if the lead is not in the NE status.
- Second sales rep. (_this only appears if lead is in PAPERWORK status_)
- Dispo notes and
- Lead result status. (_this only appears when the dispo page is printed._)

#### Blocking or Booking time off for a salesman.
- To Book/Block time off for a salesman, click on the preferred time off slot on the salesman's row in the calendar.
- Click on the `Block Sales Rep Time` button on the pop up modal that appears.
- Provide a reason for the blocked time off.
- Click the `Block time` button on the right bottom corner of the modal to save the blocked time off for the salesman.

![Schedule Page screenshot](../../confirmation/images/block-time-off-salesman-confirmation.png?raw=true "Schedule page")

#### Scheduling of a new customer appointment.

![Scheduling Form](../../confirmation/images/schedule-popup-form.png?raw=true "Schedule form")

* New appointment page.
  - This page captures the new information for the newly being scheduled customer.
  - Required fields on this page are marked with an asterisks (`*`) and is left blank, the page will throw a pop error.
  
  ![Scheduling Form](../../confirmation/images/new-appointment-pg.png?raw=true "Schedule form")

#### Result page, (a pop up that appears when you click on a card).
The result page has two tabs, 
1. **Basic info tab.**
- When a user clicks on a lead card in the dispo calendar, the result modal will appear.
- If the lead's scheduled appointment is a head of the current time, some fields will be disabled for editing, and they can
  only be edited when a user clicks on the `Allow Edit` button right below the page.
- If the lead is in `TOBESAVED, QUESTIONS or PAPERWORK` status, the result status section will not appear.
- If the lead status is either `TOBESAVED, QUESTIONS or PAPERWORK` and not of an `NE` status, the Reschedule Result modal
  will appear on this modal.
- If the source is `NS, PDNS, DNS or show`, a booker field will appear, and it is a required field, if left blank, an error 
  will be thrown.
- The `Print Phase one` button allows confirmation to print a phase one for a lead.
- If a lead is sold, the date sold will be captured automatically from the appointment date plus three check boxes will
appear on the pade, these are `Slab`, `Crawl Space`, and `Basement`.
  
![Result modal Form](../../confirmation/images/lead-result-modal-confirmation.png?raw=true "Result Modal")

2. **History tab.**
- The history-tab shows the history of leads in the same address of the current lead, (_previously worked on leads from 
  the same address as the current lead._)
- If any historical lead's exist, four columns will appear about the previous leads' information.
  [`Customer Name, Source, Status and Sales Amount`].

![Scheduling Form](../../confirmation/images/history-tab-confirmation.png?raw=true "Schedule form")

###### Notes
* _Any time user leaves and comes back to the confirmation dispo page, the default date will be the last date before they
  left the page._
* _The Scheduling Dashboard can only be viewed by users Admin or Confirmation level users (users with the role of
  Confirmation/Admin)_
* _This page has search functionality from which once can leverage on to filter lead records basing off of the
  desired filter field_
