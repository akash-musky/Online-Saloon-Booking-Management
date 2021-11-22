INTRODUCTION:-

Database Management is the core of modern data, as handling and managing data is the key
in making exponential progress in today’s world. Here, the undersigned students of 2nd year :
1.MOHAMMAD TABISH SHAMIM (Roll no: 191210031)
2.GARVIT KHURANA (Roll. No: 191210021)
3.AKASH KUMAR (Roll. No:191210007)
have completed a project ‘Online Salon MANAGEMENT System’ which makes extensive use of DBMS

CASE STUDY:- ONLINE SALON MANAGEMENT SYSTEM AIM:-

The project is an online Salon Management System.

The goal of the project is to let users make bookings for salons through a web application. FUNCTIONALITIES:-
The key features of the web application are:-

1.A user has to register before making bookings.

2.While registering, a user is asked to enter information like username, password, email,etc. For email id field, if a user enters anything random like “asjabshbdshdbhdb@dnjdjdjbfj.com”, then the user will be asked to enter a valid email id.

3.Once the user fills up the registration form and submits it, the details of the user are added to the database. If the user had entered the correct admin code while registering, then the user is registered as an admin. The password entered by the user is stored in the database as a hash password and not as plain-text password (as entered by the user in the form).

4.Upon submission of registration form,an email containing an OTP and a link to verify account with help of given OTP, is sent to the user to verify his/her account.

5.Only after a user has verified his/her account can he/she make use of the web application, i.e make bookings and give feedback on salons.

6.Login/Logout system

7.Changing the look of a page based on authentication and authorization. (Different looks of the same page, if user is not logged in, if non admin user is logged in & if admin is logged in)

8.Forgot password system (Password reset system):

The user is asked to enter his/her username and then an email is sent to the email id whose corresponding username in the database matches with the entered username. (i.e. An email is sent to email id, with which the user whose username is entered, had registered. )

The sent email contains a link to reset the password.

9.Contact us

A ‘Thank you for contacting’ email is sent to the person contacting, and an email along with queries/suggestions entered by the person, is sent to an email address called ‘tabzwebdev1@gmail.com’

10.Only the admin can add, edit or delete salons.

11.User can make bookings, while making a booking, the following things will be checked:


A.Booking date cannot be a past date (ex: a person making a booking on 20th November, 2020 cannot make a booking for 19th november 2020)

B.The user must be verified

C.The salon name entered must exist in the database.

D.At least one service must be selected

E.If all seats of selected salon on selected date and time period have been booked, then booking cannot be made.

F.If one of the selected services is not available in the selected salon, then booking cannot be made.

G.The booking timings must be in the time period in which the selected salon is open.

H.If a user makes a booking on a day and time period on which he already has a booking, then booking cannot be made (ex: if a user makes a booking for 20th november 2020 at 16:45 and if the user has a booking on 20th november 2020 from 15:00 to 17:00, then there is timing clash and booking cannot be made)


12.When a user makes a booking, an email is sent to the user and an email is also sent to “tabzwebdev1@gmail.com”, regarding the booking.

13.A user can delete his/her booking. When a user deletes his/her booking an email is sent to the user.

14.Users who have verified their account can give feedback on salons.

15.A user can only edit/delete his/her feedback and not other user’s feedback.

16.When the admin deletes or updates a salon, all bookings of that salon are deleted and an email is sent to clients (users) who made those bookings.

17.Fuzzy search

18.Search salon by category


HARDWARE REQUIREMENTS:-

The volume of the information to be handled is thus about millions of characters.This suggests that the minimum hardware requirements should be:-
•Operating System: Windows 7/8/8.1/10.
•Memory (RAM): 1 GB of RAM required.
•Hard Disk Space: 200 MB of free space required.
•Processor: Intel Pentium 4 or later.
•Cache: 512KB





SOFTWARE REQUIREMENTS:-

The following technologies have been used to make this project:

1.The express framework of NODE JS (javascript backend runtime environment) has been used as the backend language.

2.MySql has been used as the database.

3.GOORM IDE has been used as the IDE.

4.Npm has been used to install node modules (packages)

