# Parking App Manual 
***

### Tools/Launguages:

* Xcode, Swift, FireStore

* The database record has "users" collection which stores collection of user account information 
<div>
<img src="https://github.com/jykelly2/ParkingApp-IOS-/blob/master/Picture14.png" height="300" width="650"alt="The Sign in page">
<div>

*  Inside each users document, there is another collection "parkings" which stores collection of parkings for that user account record 
<div>
<img src="https://github.com/jykelly2/ParkingApp-IOS-/blob/master/Picture15.png" height="300" width="650"alt="The Sign in page">
<div>

***

# App Navigation

***


### Sign In Page
-	Enter correct email and password of existing account and click the login button to launch the Home page

-	If you want to create a new account, click on sign up button to launch Sign up page

- When you click on "Remember me", the app will remember the last user signed in even after the
app is closed and would populate the text field automatically
<div>
<img src="https://github.com/jykelly2/ParkingApp-IOS-/blob/master/Picture1.png" height="500" width="250"alt="The Sign in page">
<div>

***

### Account Validation

* Check the input with the existing record in Firestore Database and will alert the user if credentials are incorrect 

<div>
<img src="https://github.com/jykelly2/ParkingApp-IOS-/blob/master/Picture2.png" height="650" width="300"alt="The Sign in page">
<div>

***

### Sign Up Page

* Allows the user to enter the fields in order to sign up and create a new account

* All input values have validation so it checks that input is not empty and inputted in the correct format

<div>
<img src="https://github.com/jykelly2/ParkingApp-IOS-/blob/master/Picture3.png" height="650" width="300"alt="The Sign in page">
<div>

***

### Home Page

* Allows the user to navigate to different pages. It won't allow you to launch the Latest Parking Receipt page and Parking List page without having any parking record. 

The Order from left to right is:
* "Book" icon - open App Manual
* "Person" icon - open Sign in (Logging out)
* "Wrench" - open Update Account
* "Clip" icon - open Latest Parking Receipt
* "List" icon - open Parking List
* "Map" icon - open Search Nearby Parking
* "Plus" icon - open Add Parking

<div>
<img src="https://github.com/jykelly2/ParkingApp-IOS-/blob/master/Picture4.png" height="350" width="300"alt="The Sign in page">
<div>

***

### App Manual Page

* Navigates to Parking App Manual Website that was created locally which gives instructions on how to use the app

<div>
<img src="https://github.com/jykelly2/ParkingApp-IOS-/blob/master/Picture5.png" height="650" width="300"alt="The Sign in page">
<div>

***

### Update Account Page

* Enter fields to update the user account on the database record. All fields have validation and need to be formatted in the correct format


<div>
<img src="https://github.com/jykelly2/ParkingApp-IOS-/blob/master/Picture6.png" height="650" width="300"alt="The Sign in page">
<div>

***

### Add Parking Page

* Enter fields to add parking to the parking collection on a user account FireStore database record. All fields have validation and need to be formatted in the correct format

<div>
<img src="https://github.com/jykelly2/ParkingApp-IOS-/blob/master/Picture7.png" height="650" width="300"alt="The Sign in page">
<div>

***

### Add Parking Confirmation

* Alert user that parking was successfully added to the record

<div>
<img src="https://github.com/jykelly2/ParkingApp-IOS-/blob/master/Picture8.png" height="650" width="300"alt="The Sign in page">
<div>

***

### Latest Parking Receipt Page

* Retrieves the user's latest parking record by date and outlines the detail of that parking

<div>
<img src="https://github.com/jykelly2/ParkingApp-IOS-/blob/master/Picture9.png" height="650" width="300"alt="The Sign in page">
<div>

***

### Parking List Page

* Lists all the parking in the user's parking collection record from newest to oldest record
* Tapping on the date will open up Parking Detail page for that record 

<div>
<img src="https://github.com/jykelly2/ParkingApp-IOS-/blob/master/Picture10.png" height="650" width="300"alt="The Sign in page">
<div>

***

### Parking Detail Page

* Retrieves the parking that the user tapped from Parking List page and outlines the detail of that parking

<div>
<img src="https://github.com/jykelly2/ParkingApp-IOS-/blob/master/Picture11.png" height="650" width="300"alt="The Sign in page">
<div>

***

### Search Nearby Parking 

* Opens up a map location which indicates your current location with a dropped pin 

<div>
<img src="https://github.com/jykelly2/ParkingApp-IOS-/blob/master/Picture12.png" height="650" width="300"alt="The Sign in page">
<div>

***

### Map Seach Result

* Tapping on the Search button would search nearby parking within 8 km radius and would drop pins of the location of these parking

<div>
<img src="https://github.com/jykelly2/ParkingApp-IOS-/blob/master/Picture13.png" height="650" width="300"alt="The Sign in page">
<div>
