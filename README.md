# JPDB-EmployeeForm

### JsonPowerDB is a Database Server with Developer friendly REST API services. It's a High Performance, Light Weight, Ajax Enabled, Serverless, Simple to Use, Real-time Database. 
It empowers developers to build fast database applications without using any server side programming / scripting and without installing any kind of database. 

- On page load an empty form is displayed and focus remains at the Employee ID field. All buttons remain disabled.

- If the ID does NOT exist in the database, [Save]  is enabled and the cursor  is moved to the next field. 

- On entering an existing ID, all its details are displayed in the fields as data gets fetched from JPDB.This enables the [Change] and [Reset] buttons and moves the cursor to the Name field. Since ID can't be modified, this field is disabled.
Modification of data in the form is now enabled on hitting [Change] updates this record in the database . Hitting the [Reset] button resets the form to step-1.

- Complete the data entry form and use [Save] button to store the data in file or use [Reset] button to reset the form for step-1.
