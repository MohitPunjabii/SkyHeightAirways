# SkyHeightAirways
Project Case Study
Sky Heights Airways
Introduction
The objective of the project is to design a Reservation System application which enable to search and book flights Sky Heights Airways is usable only by a designated number of airline employees. This application must help end user to maintain information related flights, users/Passengers, and their bookings.
Data Model
1.Flights: will track the information related to flights.
2.Bookings: will track the data for the bookings. It will be a junction between Flights and Passengers.
3.Passengers: Information will be stored in existing contact or take custom object.
4.Flight Tickets: will store the information for the flight tickets.
Users Profiles
1.User (Admin/Backend User)
a. Create/Edit/Delete Flight
b. View/Edit/Cancel Booking
c. View/Edit/Delete Passengers
d. View Flight Tickets
e. Approve or Reject any Flight Update
2. User (Manager)
a. Edit/View Flight details.
b. Send Approval for any flight updates to Admin.
c. Can only view Bookings, Passengers and Flight Tickets.
3. User (Window Person)
a. User can only view Flight Details.
b. User can view/edit/delete booking Details.
c. Can view Flight Tickets.
d. Can view/edit/delete Passenger information.
Please use LWC components for performing DML for Flights/Passenger/Bookings records for below requirements.
Requirements
1. Flight can maintain information about Flight Id, Airlines, Flight Date, Source, Destination, Fare, total available seats, total reserved seats, and remaining seats and more fields as per the requirement.
2. Bookings can maintain data for Booking Number, Source, Destination, Date, Flight, Passenger, Amount, and more fields as per the requirement.
3. Passenger details like Name, Contact, Email, Address etc. can be stored in Passenger. It should also display total number of flights booked, total number of flights cancelled, and the date of last booking done. Passenger details also have the option to upload any Id proof (PAN/DL/Aadhar).
4. Flight Tickets will be auto generated on the confirmation of booking with Flight, Booking and Passenger details same must be notified to the passenger over email. Every Flight ticket must also have company’s logo.
5. Window User must be able to book only approved flights.
6. Passenger with same name, email id and contact number should not be added, rather details should be fetched , displayed with a message that passenger already exists and user will proceed further with those existing details.
7. User must be able to cancel booking by clicking on the cancel button/Picklist that must change status from booked to cancelled.
8. User must be able to filter the flights based on source, destinations, and date of travelling.
9. Email Alert for any New Flight should be received by backend user and manager.
10. Passenger must receive Booking details via email after the booking is confirmed and Passenger should also be notified via email at the time cancellation.
11.Basic Validations of phone, name, number fields should be taken care of.
12. On flight cancellation by Airlines the full amount should be refunded, and Passenger must be notified.
13. On flight cancellation by Passenger/user then the amount will be refunded on the below conditions:
a. Cancelled before 5 or more than 5 days: 100% refund
b. Cancelled before 2-4 days: 75% refund
c. Cancelled before 1 day: 50% refund
d. Cancelled on last day: No refund
Same must be notified to Passenger with the detail of refunded amount.
14. Validations should be taken care for email formats, source and destination should not be same and user must not be able to select previous dates while booking a flight and many more like this.
15. Flights can be added of two types i.e., Domestic, and International and accordingly page layouts should be there.
16. Different fares should be calculated for Business and Economy class.
17. No bookings can be done for the flight if the seats available are less than the number of seats user is trying to reserve.
18. If any flight is cancelled then all its related bookings must also be cancelled.
19. On every booking confirmed, edited, or cancelled trigger must handle the remaining seats in the flight.
20. On a tab, flight search component must display the Flight details. Flight can be searched based on Airline type and Flight date.
21. On same tab in another component user will be able to see the other available Flights but from different Airlines of the same flight date.
22. The tab must also have a component that should show the related booking of the searched flight.
23. On Flight ticket page, user can download the ticket by clicking the Download Ticket button or can send on email if user wants to.
24. In a component, show names of passengers which will help user to locate passengers on map based on their addresses. Also, the component help user to see the distance between two locations.
25. After the travelling date, system must automatically send an email for asking rating/feedback/complaint. The revert must get stored in the case object.
26. Application’s data need to be backed up on the last day of every month.
Data Analytics
Reports
a. Total Airline wise Flights for every month.
b. Total Bookings for last quarter.
c. Total Cancelled Bookings.
d. Total Cancelled Flights for last month.
e. Total Passengers travelled in the FY.
Dashboard
Create a dashboard which shows following information:
a. Total Airline wise Flights for the last month.
b. Total Bookings for last quarter.
c. Total Cancelled Bookings.
d. Total Cancelled Flights for last month.
e. Total Passengers travelled in the FY.
