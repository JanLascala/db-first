Table name: Used_Cars

Column Names

ID: (BIGINT)- auto-increment  NOT NULL
Brand:  VARCHAR(100) NOT NULL
Model:  VARCHAR(100) NOT NULL
Vehicle_Body:(ex suv,wagon,van etc)  VARCHAR(100) NULL
Year_Production: YEAR() NULL
Country_of_Manufacture:CHAR(5) NULL
Traction_type: CHAR(3) NULL
Engine_type: VARCHAR (50) NULL
Shift_type: CHAR(3) NULL
Number_of_Gears: TINYINIT NULL
Fuel_type: VARCHAR(50) NULL
Power: VARCHAR(50) NULL
Engine:VARCHAR(50) NULL
CC:(Displacement) TINYINIT NULL
Engine_Displacement (liters) FLOAT (4,1) NULL
Emission_class: CHAR(5) NULL
Weight:Float(6,3)  NULL
Number_of_Doors: CHAR(3) NULL
Number_of_Seats:CHAR(1) NULL
Body_Color: VARCHAR(50) NULL
Type_of_Paint: VARCHAR(50) NULL
Interior_color: VARCHAR(50) NULL
Interior_material: VARCHAR(100) NULL
Date_of_purchase: DATE() NOT NULL
Date_of_delivery: DATE() NOT NULL
Number_of_owners: CHAR(2) NOT NULL
Vehicle_Conditions:TEXT() NOT NULL
License_plate: CHAR(13) UNIQUE NOT NULL
Kilometers: Float(6,3) NOT NULL
Optionals: TEXT() NULL
Notes: TEXT() NULL