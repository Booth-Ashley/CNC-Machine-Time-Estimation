# CNC-Machine-Time-Estimation

Interactive web applications to streamline the process for management to request time estimates for customer orders and employees to calculate those estimates, enabling consistent &amp; accurate pricing and quoting.

Functions:

Management Side:
Inputs customer data: name, DXF/DWF file name, quantity, material, and thickness.
Exports and saves the data to a file in the customer's folder.
Notifies the operator of a new runtime request.

Operator Side:
Selects and imports the customer data file saved by management.
Creates a new file and inputs additional data fields.
The app automatically calculates and displays the total time required for the job.
Prints the completed document for management to quote and record.

Calculation Logic:
Calculates time by adding "pierce time", "pre-pierce time", "cutting time", and "prep time" multiplied by the number of "sheets".
If the parts exceed the water jet cutting machine bed's capacity, the time is calculated per sheet and then multiplied.

Additional Feature:
Includes a time converter app to help operators convert seconds to minutes and hours when calculating pre-pierce time.
Overall, this web app aims to optimize the process of estimating water jet cutting times, enhancing efficiency and accuracy in quoting and delivering customer orders. 🚀
