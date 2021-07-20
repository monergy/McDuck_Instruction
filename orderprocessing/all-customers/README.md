## Customers.

The all customers page lists all customers that have been added to the application.

![All Customers page screenshot](../../orderprocessing/images/all-customers-page-op.png?raw=true "All Customers page")

The all customers page has an `Export Customer Data to CSV` button which allows users to export lead data to CSV files
given a data range (`Start and End date`).

![Export customers form screenshot](../../orderprocessing/images/export-customer-data-form-all-cust-page.png?raw=true "Export customers form")

### Exported customer CSV data. 
##### CSV: Field notes (How certain fields are determined and/or calculated).
* Calculation of LEADs/SITs/OUTs and SALEs in the exported customer data CSV file.
  - _the calculation below are automated and calculated in the backend of the application._
  > 1. When a lead (customer) has no selected status is from confirmation, there this will be counted as a [**LEAD**].
  > 2. When confirmation selects the lead (customer)'s status to be either `UNAVAILABLE` or `NE`, the lead will be counted 
  as both a [**LEAD** and **OUT**].
  > 3. When confirmation selects the lead (customer)'s status to be either `NS`, `PDNS` or `DNS`,  the lead will be
  counted as both a [**LEAD**, **OUT** and **SIT**].
  > 3. When confirmation selects the lead (customer)'s status to be either `SOLD`,  the lead will be counted as both a
  [**LEAD**, **OUT**, **SIT** and **SALE**].

###### Notes
* _This page has project statuses, and they are derived from project statuses selected by confirmation as a result of 
  running the lead_
* _This page also has search functionality from which once can leverage on to filter lead records basing off of the
  desired filter field_
* _This page is only accessed by order-processing or Admin based users (Users with roles of Order Processing or Admin)._
