# rideways

This project contains the solution for the rides application.

This project is built using Apache Maven version 3.2.0 which installs the junit and org.json dependencies.

The project SDK is Java 1.8 

## Running the application using the command line

In the `rides` folder run the command `mvn clean package` to compile and package the code.

To start the application and run the code, use the command `java -cp target/rides-1.0-SNAPSHOT.jar com.booking.rides.App` in the same `rides` folder. We're running the App.java file which is in the com.booking.rides package. We also need to specify the path to the jar created with the previous command using `-cp`.

This is how we run the exercises in Part 1.

The user will be prompted to input the pickup and dropoff locations which need to be in the `51.470020,-0.454295` format to be parsed as strings.

Optionally, the user can specify the number of passengers for Dave's Taxis results. If filtering the results is not desired, the `ENTER` key should be pressed.

The user will be able to see either the filtered or non-filtered options from Dave's Taxis. Following this, using the same pickup and dropoff locations, the cheapest option for each car type is shown from all suppliers.
