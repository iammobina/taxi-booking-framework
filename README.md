# Taxi Booking Framework
  
A taxi dispatching station having a pool of taxis serving customers. The server provides RESTful web services for the pull-based interaction between the client and server for the stateless components.
This project is RESTful which means that the code on the client side can be changed at any time without affecting the operation of the server, and the code on the server side can be changed without affecting the operation of the client.

## Design Overview
The following are some of the features of this project:

1) Framework supports Trip Reservation.

2) Framework supports Passengers and Drivers Management Panel.(Includes account creation and other related APIs.)

3) Framework supports Scheduled Reservation. (book a trip in some date in future)
4) Framework supports Different Function Call On Arriving Delaying By Passengers Or Drivers.
(can call functions on specified event)
5) Framework supports Different Conditions for the Trip.
(a map structure representing Conditions is added to reserve API so that it would check for Conditions satisfactions before reserving)
6. Framework supports Trip History.

7. Framework supports Wallet for passengers and different payment methods.
8. Framework can use different policies (specified by framework user) to calculate cost of trip.

## Language
The project is written in Java(Spring boot).

[View the document for more information ](TaxiBookingFramework.pdf)
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[ Apache-2.0 License](http://www.apache.org/licenses/)
