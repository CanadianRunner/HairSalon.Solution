# _Database Basics_

#### By _**Sean Keane**_

#### Eau Claire's Hair Salon - Epicodus Code Review 7/29/2022

## Technologies Used

* C#
* .NET 5.0
* ASP.NET Core MVC
* MySQL
* Entity Core Framework


## Description
_This is a project I created at Epicodus that allows Eau Claire's Hair Salon to input both Stylists and clients into a database using MySQL.  The user is presented with a "Splash Page" and has the options of selecting Stylists or Clients. The user has the ability to add the name of the stylist, their speciality, and the ability to edit this information. They also can enter client names, descriptions, assign a stylist, and edit this information.  Developing this application helped grow my understanding of C#, .NET, ASP.NET Core MVC, Databases, and Entity Core Framework._

## Schema
_This is an illustration of the relationship between the two tables used in this application._

![SQLDESIGNER](SQLDesigner.png)

## Setup/Installation Requirements

1) Clone this repository to your desktop.
2) Navigate to the now installed directory and open in your editor of choice.
4) Create your own database using the data from `sean_keane.sql`.  Import this data into your MySQL workbench.


5) Navigate to `appsettings.json` this is located within the HairSalon directory.
6) Please enter the database, userId, and password (refer to the image below for entry points).
![AppSettings](AppSettingsJSON.png)

3) Open the directory and `cd to HairSalon`.
5) To build the Hair Salon enter: `dotnet build`.
6) To run the Hair Salon enter: `dotnet run`.
7) Open your browser of choice and use the url: http://localhost:5000/

## For a visual representation of Setup, please consult the attached Gifs.

![Alt Text](BuildingAppGifPierresBakery.gif)

![Alt Text](PierresWebPage.gif)

## Project can be found at:
https://github.com/CanadianRunner/Vendor-And-Order-Tracker.git

## Known Bugs

* This application currently has no styling. If time permits I would like to add some visual appeal to this vendor and order tracker.


## License

If you have any questions or concerns feel free to contact me at code@sean-keane.com

*This is licensed under the MIT license*

Copyright (c) 7-15-2022 **_Sean Keane_**

