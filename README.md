Report was generated from sample data tables sales,products,people,geo

Table: sales
Columns:
SPID text 
GeoID text 
PID text 
SaleDate datetime 
Amount int 
Customers int 
Boxes int

Table: products
Columns:
PID varchar(6) PK 
Product text 
Category text 
Size text 
Cost_per_box double

Table: people
Columns:
Salesperson text 
SPID varchar(6) PK 
Team text 
Location text

Table: geo
Columns:
GeoID varchar(4) PK 
Geo text 
Region text

