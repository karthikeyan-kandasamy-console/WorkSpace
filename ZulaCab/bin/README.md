    ZULO CAB APPLICATION

    Create a Cab booking application, ZULA as per the details given below. The program should first present a menu with the following options

    Driver login
    Customer Login
    ZULA Administrator
    Exit
    Task 1: Initialization

    Initialize the data as per the details are given below to be loaded when the program starts. Note: It can be loaded and kept in the memory. No need to maintain a File or DB.

    Initial Cab Drivers:

    ID	NAME	PASS	AGE
    1	aaa	111	25
    2	bbb	222	36
    3	ccc	333	31
    4	ddd	444	28
    Initial Customers:

    ID	NAME	PASS	AGE
    1	WW	55	25
    2	XX	66	36
    3	YY	77	31
    4	ZZ	88	28
    initial location

    ID	NAME	DISTANCE FROM ORIGIN
    1	A	0
    3	C	4
    4	D	7
    6	F	9
    2	B	15
    7	G	18
    8	H	20
    5	R	23
        

        4                3                  2                 6                3               2                   3

    A——-C———-D———-F———-B———G———H———-E

    Initial Cab location

    Location	CabID’s
    D	1
    G	2
    H	3
    A	4
    Task 2: Cab Drive/Customer Login

    Cab Driver should have the option to login using existing credentials (Username and Password)

    Customers should have an option to login using existing credentials (Username and Password) or create a new account with all the details.

    Sample application prompt

    Welcome to ZULA!!

    1.Cab driver login

    2.Customer login.

    3.Administration login

    4.Quit

    Please choose a service:

    Task 3: Hail a cab

    The customer should be able to hail a cab based on the following conditions:

    1. He/She should be able to choose the source and the destination locations. 2. The cab which is available and present in the nearest location to the source should be chosen.

    3. Fare estimate should be provided to the customer. Calculated at Rs.10/km. 4. Customer should be shown a confirmation and journey initiated only if accepted.

    Print the location of each cab, before booking a ride.

    Sample Output:

    Location	Cab IDs
    A	3
    E	1
    C	2,4
    Task 4: The following conditions have to be met for every booking.

    1. The cab which is present in the nearest location to the source should be chosen.

    2. The cab driver will have a mandatory rest of 1 ride after completing each ride and should not be chosen even if he is the nearest.

    3. If 2 or more cabs are in the same location, the cab which has completed a fewer number of total trips should be allocated.

    Task 5: ZULA Commission & Cab Driver Ride Summary

    For every ride, ZULA gets a commission of 30% of the Ride Fare

    The cab drivers should be able to see the complete history of their rides. The Cab Driver Name, Source, Destination, Customer Detail, Fare, and ZULA commission

    Sample Output:

    Cab Id: 1

    Cab Driver Name: aaa

    Trip Details:

    Source 	Destination	customer detail	ZULA commission	Fare
    D	H	4	39	130
    E	G	2	15	50
    C	B	2	33	110
    Task 6: Customer Rides Summary

    The Customer should be able to see the complete history of their rides. The Customer Name, Source, Destination, Cab Detail, and Fare.

    Sample Output:

    Customer Id: 2

    Customer Name: yy

    Trip Details:

    Source 	Destination	CabDetail	Fare
    A	E	3	230
    E	G	1	50
    C	B	1	110
    Task 7: Summary of all the cabs running in ZULA available to the admin.

    The admin should be able to see a summary of all the cabs which are being managed by ZULA. It should contain the Total Number of Rides, Total Fare Collected, Total ZULA Commission, Details of each trip. Sample Output

    Cab Id: 1

    Total Number of Trips: 3

    Total Fare Collected: 290

    Total ZULA Commission: 87

    Trip Details:

    Source	Destination	Customer Detail	Fare	ZULA commission
    D	F	4	130	39
    E	G	2	50	15
    C	B	2	110	33
    Cab ld: 2

    Total Number of Trips: 0

    Total Fare Collected: 0

    Total ZULA Commission: 0

    Trip Details: No trips were given