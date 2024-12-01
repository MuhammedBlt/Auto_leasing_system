# Auto_leasing_system


Branch ( BRANCH_ID, Name, City, Province, Country, Street Address, Phone )

Employee = ( EMPLOYEE_ID, ID, First Name, Last Name, Phone Number, 
Email, Salary, Position, Status, Employment type, Birth Date, SIN )

Customer ( CUSTOMER_ID, First Name, Last Name, Phone Number, Age, Insurance, 
Driver License Class Type )

Transaction ( TRANSACTION_ID, CUSTOMER_ID, CAR_ID, DROP_EMPLOYEE_ID, 
PICKUP_EMPLOYEE_ID, DROP_BRANCH_ID, PICKUP_BRANCH_ID, 
PickupDateTime, DropDateTime )

Car ( CAR_ID, BRANCH_ID, TYPE_NAME, Make, Model, Year, VIN Number, License Plate, 
Registration, Insurance, In Service )

Type ( TYPE_NAME, Daily Fee, Weekly Fee, Monthly Fee )
