## Order-processing Dashboard.

The scheduling dashboard lists all **SOLD** leads that are not achieved and not completed by production (_leads who that are
marked as production complete will not appear in any column on this dashboard._)

#### How leads are placed in columns.

**Please Note**:`The explanations below are in order of what takes precedence over the other when placing leads in the
dashboard columns`.
1. If a lead is archived (marked as a dead deal), it will be placed in the `Alert` column.
2. If the lead has a `GoodToGo` switch turned on from the comments' tab, the lead card will be placed in the `Good To Go`
   column.
3. If a lead's checkedIn switch is turned on from the _Basic info tab_ on the pop-up modal, the lead card will be placed 
   in `Received` Column.
4. If a lead has been marked as a (ToBeSaved / has Questions) by `confirmation`, the lead card will be placed in the 
   `To Be Saved / Questions` Column.
5. If a lead's `NeedsPaperwork` switch from the comments tab is turned on, the lead will be placed in the 
   `Paperwork Required` Column.
6. If none of the above checks or scenarios are fulfilled, the lead card will be placed in the `New Sales` Column.

![Order Processing Dashboard screenshot](../../orderprocessing/images/order-processing-dashboard-op.png?raw=true "Order Processing Dashboard")

##### List of the Column Names.
1. New Sales,
2. Received,
3. Paperwork Required,
4. To Be Saved/Questions,
5. In Progress,
5. Good To Go and,
6. Alert.

#### Background colors for the cards.

- _Red_: A card has been marked as a dead deal from the finance tab.
- _Green_: The card has been marked as complete by the scheduling dpt.
- _Red border_: The card has a permits in its city.
- _White_: This is the default background color for all cards.

**Note**: _The dots on the cards are carried from the dots in the comments tab for each lead._

##### Visible tabs when you click on a card from any column.

1. **Basic info Tab**.
   * This tab shows the basic information about the lead.
   * The tab also includes the `checkedIn` switch buttons which when turned on, it is placed in the `Received column` 
     on the order processing dashboard.
   * This tab allows order-processing to edit the prospect information about the customer.
   * order processing can add alternate emails, names and phone numbers to the lead's prospect info.

     ![Basic Info Tab screenshot](../../orderprocessing/images/basic-info-tab-op.png?raw=true "Basic Info Tab")

2. **Sales Tab.**
   * This tab handles the sales for a lead.

     ![Sales Tab screenshot](../../orderprocessing/images/sales-tab-op.png?raw=true "Sales Tab")

3. **Permit Tab.**
   * This tab shows available permits if any in a lead's city, if there is no permit required for the lead's city, the 
     message `There are no permits for this customers City` will be shown.
   * If there's a permit for the lead's city, steps required in acquiring the permit are list on this tab and 
     order-processing can check off any status that is done.
   * After checking off any completed step, order-processing must click on the `save` button in the right bottom of the
   tab to save the changes persistently.
     
    ![Permit Tab screenshot](../../orderprocessing/images/permit-tab-op.png?raw=true "Permit Tab")

4. **Install Tab.**
    * The Install-tab shows/mirrors the installation dates for active job types from confirmation and/or scheduling.
    * It shows the lead's Status, date sold for the lead, customer number and the invoice status.
   
    ![Install Tab screenshot](../../orderprocessing/images/install-tab-op.png?raw=true "Install Tab")
   
5. **Location Tab.**
   * The location tab shows the lead's physical address.
   * There is an added ability for order-processing to add an extra locations or addresses for the lead.
     * To **Add extra locations**, click the `Add Location` button on the location tab and fill in the new location details.
     * Click the `Save` button in the right bottom corner of the tab to save the newly added location.
    
    ![Location Tab screenshot](../../orderprocessing/images/location-tab-op.png?raw=true "Location Tab")

6. **Warranty Tab.**
    * The warranty tab handles the warranty details for the lead.
    * A lead's warranty can be created and/ or updated from this tab.
    
    ###### _**IMPORTANT Notes:**_
   - only lead's with an active waterproofing job type will have the option to edit details for a 
   lead's warranty 
   - Three job types if active have the following messages displayed for their warranty details.
        1. **EZBreathe**. `EZBreathe has a 10-year warranty, there are no fees needed to be paid.`
        2. **Rebuild**. `Rebuild has a 5-year warranty, there are no fees needed to be paid.`
        3. **StableWall**. `StablWall has a lifetime warranty, there are no fees needed to be paid.`
   - Other job types have no warranty information tracked if they are active for the lead. 
    
    ![Warranty Tab screenshot](../../orderprocessing/images/warranty-tab-op.png?raw=true "Warranty Tab")
   
7. **Files Tab**.
   * This tab allows users to upload individual files for a lead.
   * The files tab allows users to create and upload files inside folders.
   ##### Creating and uploading new files.
   - To create a new folder, click on the `Add new` button in the right bottom of the tab and click `New folder`.
   - Double-click on a folder you'd want to upload a file into.
   - Click the `Select files` button to select the file you'd want to upload. (_you can select or add multiple files to upload_)
   - Click the upload files button to upload the files to the server.
   - Then click the `Save button` in the right bottom corner of the tab to persistently save your changes.
   - Kindly Note that the `Financing Type` and `Amount Financed` are required fields at all times.

   ![Files Tab screenshot](../../common/images/files-tab-screenshot.png?raw=true "Files Tab")

8. **Finance Tab.**
    * The finance handles a leads finance.
    * Banking financing sources details are provided from this tab.
    * If we have an approving bank for a lead's funds, a DPI value will be required, and the Approved Date.
    * If the application detects any change in the financing type, Amount Financed, and the approving bank, a new DPI value
    will be required, a pop on whether the previous value still holds will appear to confirm or update the old DPI Value.
    
   ![Finance Tab screenshot](../../orderprocessing/images/finance-tab-op.png?raw=true "Finance Tab")

9. **History Tab.**
    * The history-tab shows the history of leads in the same address of the current lead.
    * The tabs under this section are explained on this page.
    
   ![History Tab screenshot](../../orderprocessing/images/history-tab-op.png?raw=true "History Tab")

10. **Comments Tab**.
    * This tab shows comments added to lead as well as allows users to add their own comments on the lead.

   ![Comments Tab screenshot](../../common/images/comments-screenshot.png?raw=true "Comments Tab")

11. **Invoices Tab.**
    * The invoices tab shows all the invoices, invoice payments and credits available for lead.
    
    #### The invoices tab has three sections.
    
    1. `The invoices Section`. The invoices section is a list of all the invoices that have been created for a lead.
    Order processing can create multiple invoices for a lead by clicking the `Add invoices` button on the right bottom of this section.
    **However, if the add invoices button is grayed out, no more creation of subsequent invoices will be allowed**, the
    `Add Invoices` **button is grayed out when all invoices are paid to 0 balance**.
       
    ###### Extra functionality in the invoices section.
    - _Editing an invoice_. Order processing can edit individual invoices for a lead by clicking the expand button under
      the action's column for an invoice, click the edit button which will pop-up a modal pre-filled with the invoice's
      details ready for edit, after altering the invoice's details, click `Save` button to persistently save the changes.
    - _Delete an invoice_. Each created invoice has a delete icon in the action's column that allows order-processing to
      delete a given invoice.
    - _Marking an invoice as Paid/Posted_. Expand the invoice from the expand button in the action's column, click the 
      `Post` and it will mark an invoice as posted.
    - _Add comments to an invoice_. Order-processing can add multiple comments to a lead's invoices by clicking on the
      `Comment` button right below the invoices' section.
    - _Printing of invoices_. Order-processing can print external or internal invoices for a lead by clicking on the 
    `Print External` or `Print Internal` buttons right below the invoices section.
    
    2. `The Payments Section`. The Payments' section is a list of all payments that have been made to a given invoice,
    order-processing can create. A list of all available invoices is shown in the payments section for order-processing to
    make multiple payments for an invoices. 
       
    #### Extra functionality in the Payments section.
    - **MAKE PAYMENT FOR an INVOICE**: To create a new payment for an invoice, click the expand button on the right.
    - Click `Add Payment` button.
    - Fill in all the fields because they are required fields then click the `Save` button to make the payment for the 
    invoice.
    - **The edit button** in the expanded payment section. This allows order processing to update the status of the
    payment for a given invoice.
      
    3. `The Credits Section`.
    - The Credit section allows order-processing to add credits to a lead's account.
    - The added credits can be applied to a lead's invoice in which case they are the invoice balance will be credited 
    by the credit.
   
   ![Invoices Tab screenshot](../../orderprocessing/images/invoices-tab-op.png?raw=true "Invoices Tab")

###### Notes
* _Each tab has a name of the lead's name tag up top, the lead's warranty status and if the lead has it's a finance 
  approved or rejected._
* _The Scheduling Dashboard can only be viewed by users Admin or Order processing level users (users with the role of
  OrderProcessor/Admin)_
* _this page has search functionality from which once can leverage on to filter lead records basing off of the
  desired filter field_
