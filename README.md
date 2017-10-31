# Airline-Data-Model-Analysis_Project
# MD H AHMED ,YORK COLLEGE

For this Project I chose Southwest Airlines, Astoria Bank, Kayak travel reservations and Stony Brook Hospital as the 4 enterprises that I will be creating databases for. The purpose of a practical real world database will be created and used for Information Systems Management. The employees of each organization will need these databases to make sure the day to day operations of each enterprise are run smoothly and without incident. Databases need to be secure while also being a convenient way to accessing data and information that is needed. Each database created will contain entities, ER diagrams, attributes, relationships, domain values, primary and foreign keys for each enterprise. Enterprises like Astoria Bank and Kayak travel reservations will have three way relationships within their ER models. 



Southwest Airlines
Entities:
-Airplanes 
-Pilots 
-Passengers
-Airports 
-Flights
-Flight Attendants 
-Ticket Agents
 -Hangar Employees
-Flight Leg 
-Loading Crew
- Air Crew

Entity Attributes:
Airplanes: Air Id, Model No., Airplane type, Airplane passenger capacity 

Airports: Airport Id, Name, City, State, Country

Hangars: Hangar No, Location, Size, Hangar Id

Hangar Employees: Employee Id, Last name, First name, House address, Phone number, Email address

Pilots: Pilot Id, Last name, First name, Air Crew Id

Flight Attendants: Attendant Id, Last name, First name, Air Crew Id

Ticket Agent: Ticket Agent Id, Last name, First name, Air Crew Id

Flight Leg: Leg No., Flight No., Destination, Airport Name 

Passenger: Passenger Id, Last name, First name, House address, Phone Number, Email address

Flight: Flight No., From, To, Departure date, Arrival date, Departure time, Arrival time 

Loading Crew: Loading Crew Id, Last name, First name, House address, Phone number, Email address 

Air Crew: Air Crew Id, Last name, First name, Position, House address, Phone number, Email address 




Entity Relationships:





 





















DOMAIN VALUES: 
Airplanes: 
(Air Id INT (6), 
Model No. INT (25),
 Airplane type VARCHAR (30), 
Airplane Name VARCHAR (30),
Passenger capacity INT (450)
PRIMARY KEY (Air Id)

Pilots: 
(Pilot Id INT (6),
 Last name VARCHAR (25), 
First name VARCHAR (25), 
Air Crew Id INT (6),
PRIMARY KEY (Pilot Id) 

Passenger: 
(Passenger Id INT (6),
 Last name VARCHAR (25), 
First name VARCHAR (25), 
House address VARCHAR (205), 
Phone Number INT (30), 
Email address VARCHAR (250),
PRIMARY KEY (Passenger Id) 


Airports: 
(Airport Id INT (6),
 Name VARCHAR (50), 
City VARCHAR (35), 
State VARCHAR (35), 
Country VARCHAR (35) 
PRIMARY KEY (Airport Id)
 
Flight: 
(Flight No. INT (6), 
From VARCHAR (35), 
To VARCHAR (35),
 Departure date INT (8), 
Arrival date INT (8), 
Departure time INT (4), 
Arrival time INT (4),
PRIMARY KEY (Flight No.)





Flight Attendants: 
(Attendant Id INT (6),
 Last name VARCHAR (25), 
First name VARCHAR (25), 
Air Crew Id INT (6),
PRIMARY KEY (Attendant Id)

Ticket Agent: 
(Ticket Agent Id INT (6), 
Last name VARCHAR (25), 
First name VARCHAR (25), 
Air Crew Id INT (6),
PRIMARY KEY (Ticket Agent Id)

Hangar Employees: 
(Employee Id INT (6), 
Last name VARCHAR (25), 
First name VARCHAR (25), 
House address VARCHAR (205), 
Phone number INT (30), 
Email address VARCHAR (250),
PRIMARY KEY (Employee Id)

Flight Leg: 
Leg No. INT (6), 
Flight No. INT (6), 
Destination VARCHAR (50), 
Airport Name (30),
PRIMARY KEY (Leg No.)

Loading Crew: 
Loading Crew Id INT (6), 
Last name VARCHAR (25), 
First name VARCHAR (25), 
House address VARCHAR (205),
Phone number INT (30), 
Email address VARCHAR (250), 
PRIMARY KEY (Loading Crew Id)








Air Crew: 
Air Crew Id INT (6),
Last name VARCHAR (25), 
First name VARCHAR (25), 
Position VARCHAR (25), 
House address VARCHAR (205), 
Phone number INT (30), 
Email address VARCHAR (250), 
PRIMARY KEY (Air Crew Id)






 


















Astoria Bank
Entities:
-Employees 
-Bank Branches 
-Loans
-Customers
-Companies 
-Accounts 
-Transactions
 -Departments
-Email Tracking
-Job Titles 

Entity Attributes:
Employees: Employee Id, Last name, First Name, Department, Salary

Bank Branches: Bank Id, Branch Name, Country, City, Phone, Manager Id

Loans:  Loan Id, Interest Rate, Duration by months, Start date

Customers: Customer Id, Last name, First name, House address, Phone number, Email address

Companies: Company Id, Company Name, Phone, Email, Contact Title

Accounts: Account Id, Branch Id, Customer Id, Account type, Balance, Rate, Status

Transactions: Account Id, Date, Time, Loan Id, Credit/Debit

Departments: Department Id, Department Name, Head of Department, Employee Id 

Email Tracking: Email Id, Sender, Receiver, Date, Time, Subject 

Job Titles: Title Id, Title Name, Employee Id

ATM: ATM Id, Location, ATM available, Branch Id

 Credit Card: Credit Card No., Credit Card Limit, Expiration Date, Customer Id





Entity Relationships






















	











	














Domain Values 
Employees: 
Employee Id INT (6), 
Last name VARCHAR (30), 
First Name VARCHAR (30), 
Department VARCHAR (30), 
Salary INT (7)

Bank Branches:
Bank Id INT (6), 
Branch Name VARCHAR (30), 
Country VARCHAR (30), 
City VARCHAR (30), 
Phone INT (11), 
Manager Id INT (6) 

Loans:  
Loan Id INT (6), 
Interest Rate DECIMAL (20, 3), 
Duration by months INT (8), 
Start date INT (8)

Customers: 
Customer Id INT (6), 
Last name VARCHAR (30), 
First name VARCHAR (30), 
House address VARCHAR (205), 
Phone number INT (11), 
Email address VARCHAR (250)

Companies: 
Company Id INT (6),
Company Name VARCHAR (100), 
Phone INT (11), 
Email VARCHAR (205), 
Contact Title VARCHAR (25)

Accounts: 
Account Id INT (6), 
Branch Id INT (6), 
Customer Id INT (6), 
Account type VARCHAR (35),
Balance DECIMAL (20, 3), 
Rate DECIMAL (20, 3), 
Status VARCHAR (25)

Transactions: 
Account Id INT (6), 
Date INT (8), 
Time INT (4), 
Loan Id INT (6), 
Credit/Debit VARCHAR (7)

Departments: 
Department Id INT (6), 
Department Name VARCHAR (205), 
Head of Department VARCHAR (25), 
Employee Id INT (6) 

Email Tracking: 
Email Id INT (6), 
Sender VARCHAR (25), 
Receiver VARCHAR (25), 
Date INT (8), 
Time INT (4), 
Subject VARCHAR (25)

Job Titles: 
Title Id INT (6), 
Title Name VARCHAR (25), 
Employee Id INT (6)

ATM: 
ATM Id INT (6), 
Location VARCHAR (200), 
ATM available VARCHAR (205), 
Branch Id INT (6)

Credit Card: 
Credit Card No. INT (16), 
Credit Card Limit INT (100), 
Expiration Date INT (8), 
Customer Id INT (6)









Kayak Travel Reservations 

Entities:
-Reservation 
-Passenger 
-Flight Schedule
-Seat
-Airplane
-Payment 
-Employees 
 
Entity Attributes:
Reservations: Reservation Id, Ticket type, booking date, Customer Id

Passenger: Passenger Id, Last name, Middle name, First name, House address, Phone number, Date of Birth, Gender

Flight Schedule: Schedule Id, Aircraft Id, Flight No., Departure Date & Arrival Date, Arrival time and Departure Time, Arrival and Departure Gate No. 

Airplane:  Airplane Id, Airplane Capacity, Model No., Airplane type, 


Relational Model of Enterprises
This project can solve problems for altered enterprises. This project will develop a formal designation of the database schema for each enterprise. It will also cover relational schema for entity to entity relationships. This project figure relational model for two enterprises. The enterprises are Delta Airlines and Expedia Airline Reservation. My design use ER design of each enterprise and convert them into relational schema covering entities and entity-to-entity relationships. It implements the two enterprise database using SQLite and MySQL. Both databases are populated with relational tables for all relational schemas involved with each table containing tuples. 
My design modifies the ER design of each enterprise that can be used by anyone. It also defines relations corresponding to entity sets and relationship sets in my design using SQLite and MySQL.
Relational Schemas 
Relational Tables
SQL Script of DBs
ER diagrams
Delta Airlines
Relational schema:
Pilot ( Pilot ID, Last Name, First Name, Air Crew ID)
Airplane (Air ID, Model No., Airplane Type, Capacity)
Airport ( Airport ID, Name, City, State, Country)
Hangar ( Hangar No, Air ID, Location, Size, Hangar Empl ID)
Hangar Empl (Hangar Empl ID, Last Name, Middle Name, First Name, House Address, Phone Number, Email Address)
Flight Attendant (Attendant ID, Full Name, Air Crew ID, Height)
Air Crew (Air Crew, Last Name, Middle Name, First Name, House Address, Phone Number, Email Address, Position)
Loading Crew ( Load Crew ID, Full Name, House Address, Phone Number, Email Address, Air ID)
Flight (Flight No, Air ID, From, To, Departure Date, Arrival Date, Departure Time,
Arrival Time, Airport ID)
Passenger ( Passenger ID, Last Name, Middle Name, First Name, House Address, Phone Number, Email Address)
Flight Leg ( Leg No, Flight No, Destination, Airport Name)
Ticket Agent ( Ticket Agent ID, Air Crew ID)
Relational schema relationship:
Pilot_X_ Air Crew ( Pilot ID, Air Crew ID)
Hangar_X_ Hangar Empl ( Hangar No, Hangar Empl ID)
Flight Attendant_X_ Air Crew ( Attendant ID, Air Crew ID)
Flight_X_ Airplane ( Flight No, Air ID)
Flight Leg_X_ Flight ( Leg No, Flight No)
Ticket Agent_X_ Air Crew (Ticket Agent ID, Air Crew ID)
Airplane_X_ Airport ( Airport ID, Air ID)
Hangar_X_ Airplane ( Hangar No, Air ID)
Passenger_X_ Flight ( Passenger ID, Flight No)
Pilot_X_Airplane ( Pilot ID, Air ID)
Flight Attendant_X_Airplane ( Attendant ID, Air ID)
Loading Crew_X_Airplane (  Load Crew ID, Air ID)
SQL Queries

sqlite> .header on
sqlite> .mode column
sqlite> SELECT * FROM Pilot
  ...> ;
Pilot_ID    Last_Name   First_Name  AirCrew_ID
----------     --------------    ---------------   ---------------
233           Rafi	             Abbott           12346
243           saleem          Carson         12347
253           Tahir           Phelps          12348
263           Earnest        Graham        12349
273          Hassan          Warner         12350

sqlite> SELECT Flight_No
  ...> FROM Flight
  ...> WHERE Departure_Date= '11/3/2016';

Flight_No 
------------
DAL460    
DAL545 

sqlite> SELECT Flight.Flight_No, FlightLeg. Airport_Name
  ...> FROM FlightLeg INNER JOIN Flight ON FlightLeg.Flight_No = Flight.Flight_No
  ...> UNION
  ...> SELECT Flight.Flight_No, FlightLeg. Airport_Name
  ...> FROM FlightLeg LEFT OUTER JOIN Flight ON FlightLeg.Flight_No = Flight.Flight_No;
Flight_No    Airport_Name                         
-------------   ----------------------------------------------------
DAL546      John F. Kennedy International Airport
DAL460      Jinnah international airport          
DAL545      Quaid E Azam International Airport

sqlite> SELECT LoadCrew_ID, Full_Name, House_Address, 
...> FROM LoadingCrew
...> WHERE LoadCrew_ID >= 123;

LoadCrew_ID  Full_Name                House_Address 
------------------  -------------------------    ---------------------------------------
123                 W Wright             West 87th St, New York, NY 
124                Michael, Rabbi     45-32 ST, Middleburg, FL 
125                Rafi, Ariel            111 E 48th St New York,NY 












Expedia Airline Reservation
Relational schema:
Reservation (Reservation ID, Ticket Type, Booking Date, Customer ID)
Customer (Customer ID, Last Name, Middle Name, First Name, House Address, Phone Number, Email Address, DOB, Gender)
Flight (Flight No, Aircraft ID, From, To, Flight Type)
Flight Schedule ( Schedule ID, Aircraft ID, Flight No, Departure Date, Arrival  Date, Departure Time, Arrival Time, Departure Gate No, Arrival Gate No)
Aircraft ( Aircraft ID, Aircraft Type, Aircraft Capacity, Model No)
Seat ( Seat No, Cabin, Aircraft ID, Customer ID)
Airport ( Airport ID, Name, City, State, Country, Flight No)
Flight Leg ( Flight Leg ID, Flight No, Departure From, Arrival At)
Leg Instance ( Leg Instance ID, Flight Leg ID, Available Seats)
Payment ( Payment ID, Customer ID, Payment Method, Card Type, Card Number, Expiration Date, Payment Status)
Relational schema relationship:
Reservation_X_Customer ( Reservation ID,  Customer ID)
Flight_X_Customer ( Flight No, Customer ID)
Flight_X_Aircraft ( Flight No, Aircraft ID)
Seat_X_Aircraft ( Seat No, Aircraft ID)
Seat_X_Customer ( Seat No,  Customer ID)
Flight_X_Airport ( Flight No,  Airport ID)
Flight_X_Flight Leg ( Flight No,  Flight Leg ID)
Payment_X_Customer ( Payment ID, Customer ID)
Leg Instance_X_Flight Leg ( Leg Instance ID, Flight Leg ID)
Leg Instance_X_Seat ( Leg Instance ID, Seat No)
Flight_X_Flight Schedule  ( Flight No, Schedule ID)
Flight Schedule_X_Aircraft ( Schedule ID, Aircraft ID)
Airport_X_Aircraft ( Airport ID,  Aircraft ID)
SQL Queries

sqlite> .header on
sqlite> .mode column
sqlite> DELETE FROM Customer WHERE  Customer_ID = 83784727;

sqlite> UPDATE Reservation SET Booking_Date = '6/3/2016'
  ...> WHERE  Customer_ID = 83772563;

sqlite> SELECT Flight_No, Flight_Type
  ...> FROM Flight
  ...> WHERE Flight_from = 'Merzbruck Airport' OR 'Jaipur International Airport';

Flight_No   Flight_Type
------------    --------------
UA540        Nonstop   

sqlite> SELECT Flight_Schedule.Aircraft_ID, Flight.Flight_No
  ...>  FROM Flight_Schedule, Flight
  ...> WHERE (Flight_Schedule.Departure_Date = '11/3/16') 
  ...>  AND ( Flight. AirCraft_ID = Flight_Schedule.Aircraft_ID);
Aircraft_ID     Flight_No 
--------------     ----------
3345              AA750     
3348              SA545 

sqlite> SELECT * FROM Aircraft
  ...> ORDER BY Aircaft_Capacity DESC;

Aircraft_ID  Aircaft_Type  Aircaft_Capacity  Model_No  
--------------  -----------------  ---------------------   -------------
3360           sharjah           376                      B747      
3348           sharjah         322                      B787      
3345           sharjah            291                      B777      
3357           sharjah           208                      A331      
3354           sharjah          198                      B717      
3351           Airbus            126                      A319      



























(45, 'B747', sharjah ', 376),
(46, 'B767', 'Sharjah ', 261),
(47, 'B777', 'Sharjah', 291),
(48, 'B787', ' Sharjah ', 322),
(49, 'A319', 'Airbus', 126),
(50, 'A320', 'Airbus', 160),
(51, 'A330', 'Airbus', 293),
(52, 'A332', 'Airbus', 234),
(53, 'B717', ' Sharjah ', 198),
(54, 'A331', 'Airbus', 208);
CREATE TABLE  Airport ( AirportID INT, Name TEXT, City TEXT, State  TEXT, Country  TEXT);
INSERT INTO Airport ( AirportID, Name, City, State, Country)
VALUES
(23, 'Hicksville International Airport', 'Hicksville', 'Florida', 'United States'),
(24, 'Doha Airport', 'Doha', 'Queensland', 'Australia'),
(25, 'Mirzapur Airport, 'Aachen', 'North Rhine-Westphalia', 'Japan'),
(26, ' Quaid E Azam International Airp  Regional Airport', 'Apalachicola', 'cali', 'United States'),
(27, 'Peshawar International Airport', 'islamabad', 'Peshawar', 'pakistan'),
(28, 'Anapa Airport', 'Anapa Krasnodar', 'Krai', 'Russia'),
(29, Quaid E Azam International Airport, 'Quanzhou', 'Fujian', 'China'), 
(30, Jinnah international Airport, 'Johor Bahru', 'Johor', 'Malaysia'),
(31, 'Northern Peninsula Airport', 'Bamaga', 'Queensland', 'Australia'),
(32, 'General Juan N. Álvarez International Airport', 'Acapulco', 'Guerrero', 'Mexico'), 
(33, 'John F. Kennedy International Airport', 'New York City', 'New York', 'United States');
CREATE TABLE Hangar (HangarNo INT, AirID INT, Location TEXT, Size TEXT, HangarEmplID INT);
INSERT INTO Hangar (HangarNo, AirID, Location, Size, HangarEmplID)
VALUES
(234,46,'John.F.Kenndy Airport, NY', '20,000SF', 09),                                                
(456,45,'Jacksonville International Airport,FL', '1,400SF', 03),
(489,50,'3507 Jack Northrop Ave., Hawthorne,NY', '18,000SF', 07),
(261,47, '7943 Woodley Ave., Van Nuys,FL', '43,000SF', 09),
(492,54, '3021 Airport Avenue, Santa Monica,CA', '35,000SF', 05), 
CREATE TABLE HangarEmpl (HangarEmplID INT, FirstName TEXT, MiddleName TEXT, LastName TEXT, HouseAddress TEXT, PhoneNumber INT, EmailAddress TEXT);
INSERT INTO (HangarEmplID, FirstName, MiddleName,LastName, HouseAddress, PhoneNumber, EmailAddress)
VALUES
(05,'Nancy','Jr.','King','1545 2th Ave SNaples,CA 35102',8775251000,'educare@unisa.ac.za'),                                                                
(09,'John','NULL','Chang','1315 Tamiami Trl Naples,FL
34103',7190006662,'myLifeHelp@unisa.ac.za'),                                                                    
(03,'Komal','NULL','Fox','2280 North Tamiami Trl Naples,FL 30010',2396597077,'econtech@unisa.ac.za'),                                                                    
(07,'Jimmy','NULL','Green','790 Lexington Ave New York,NY 12222',7185831333,'applications@unisa.ac.za'),                                                                
(08,'Jenny,'Dash','White','244 E Houston St, New York, NY 10002',9172259018, 'Jennyd23@gmail.com');
CREATE TABLE FlightAttendant (AttendantID INT, FullName TEXT, AirCrewID INT, Height REAL);
INSERT INTO FlightAttendant (AttendantID, FullName, AirCrewID, Height)
VALUES
(2135,'Kam Hasen',12353,5.4),                                                                                    
(2136,'Julia Chan',12354,5.6),                                                                                    
(2137,'Joanne Liuk',12355,5.8),                                                                                                                                                                        
(2139,'Lisa Forman',12357,5.3),                                                                                    
(2140,'Laura Fay',12358,5.7),                                                                                
(2141,'Sahel Goles',12359,5.7),                                                                                    
(2144,'Robyn Cooper',12360,5.8),                                                                                    
(2145,'Cherry Michener',12361,5.2),                                                                                    
(2146,'Gina Osten',12362,5.4);
CREATE TABLE AirCrew (AirCrew INT, LastName TEXT, MiddleName TEXT, FirstName TEXT, HouseAddress TEXT, PhoneNumber INT, EmailAddress TEXT, Position TEXT);
INSERT INTO Air Crew (AirCrew, LastName, MiddleName, FirstName, HouseAddress, PhoneNumber, EmailAddress, Position)
VALUES                                                                
(12354, 'Chan','Jr.','Julia','630 1st Ave #4E, New York, NY, 10063',4045842233,    ‘very.con@example.com', 'Flight Attendant'),                                                                    
(12355,    'Liuk','Danice','Joanne','419 N Fairfax Ave, Los Angeles, CA 90036',3237031221,'disymbol@example.com',  'Flight Attendant'),                                                                    
(12356,    'Perez,'NULL','Diana', '724 N Highland Ave, Los Angeles, CA 90028',3237031221,'other.emh@example.com',  'Ticket Agent'),                                                                    
(12357,    'Forman','Micheal',Lisa','3656 N Central Ave, Chicago, IL 60634',3102070127,'bugmaster@unisa.ac.za',  'Ticket Agent'),                                                                    
(12358,    'Fay', 'NULL','Laura','240 Peachtree St NWAtlanta,GA 30303',3236537970,    'famirm@unisa.ac.za',  'Flight Attendant'),                                                                    
(12346,    'Vicky','NULL','Abbott','1400 W Sunset BlvdLos Angeles,CA 90026',3212532063,'Vicky.doe@example.com','Pilot'),                                                                    
(12347,    'Leo','NULL','Carson','8432 W 3rd StLos Angeles,CA 90048',2392311712,'Abc.car@gmail.com’,    'Pilot'),                        (12348, 'Doug','Jude','Phelps','08 S Barrington AveLos Angeles,CA 90049',2394346116,'doug@unisa.ac.za','Pilot');    



