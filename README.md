# Best Doctors & Hospitals Tracker
![](/img1.png)
* Best doctors and hospitals tracker is the name of the project we have built and the name of the website is JEEVAN NAKSHA.
* In our website you can register in three ways :-
   1. You can register as an User if you are a normal user/patient.
   2. You can register as a Doctor if you are a Doctor.
   3. You can register as a Hospital if you are a Hospital.
* In recent days, online mode is very common in every industry and many people or customers are willing to use the online mode to complete their work.
* It's been a hard time for some users who are searching for some best doctors or hospitals nearby them, so that they can save their effort of searching via offline mode.
* Our Website JEEVAN NAKSHA will provide the users this facility to search for the doctors or hospitals near by them.
* User can even have an *appointment* with a particular doctor they like from our website.
* Every section of our website will be explained in the following [Documentation](#documentation).

# Documentation
* [Project-Installation](#Project-Installation)
* [Authentication](#Authentication)
* [Hospitals-Registeration](#Hospitals-Registeration)
* [Doctors-Profile](#Doctors-Profile)
* [Hospitals-Profile](#Hospitals-Profile)
* [How-to-update-profile](How-to-update-profile)
* [Contributers](#Contributers)

## Project-Installation
### Project Environment
#### Following are the list of softwares required for the environment.
* Python 3 or more
* Django 3 or more
* pycopg package from python
* pillow package from python
* HTML5, CSS, Node.js Support
* Version control (Git, Github)
* Postgre sql server and PgAdmin
### Installation
#### Step-1 
Clone this repository **[link](https://github.com/WAD-Team-Alpha/Hospital_Review_System.git)** using this command in your terminal/command prompt.

git clone https://github.com/WAD-Team-Alpha/Hospital_Review_System.git

#### Step-2 
Navigate to public folder and create a python file with name *email.py*.\
![](/images/Capture.JPG)
#### Step-3 
Inside the *email.py* file create the list of variables mentioned below and assign them accordingly.
* EMAIL_HOST_USER     This variable is used to store the *email* of the website
* EMAIL_HOST_PASSWORD This variable is used to store the *password* for the email of the website
* EMAIL_HOST          This variable is used to mention the type of host *In our case we use smtp.gmail.com*
* DEFAULT_FROM_EMAIL  This variable stores the *default email* used by the website
* DB_PASSWORD         This is the password of the database used in the *settings.py* file in public folder
#### Step-4
Before you run the project, make sure that you apply all the migrations to your database. If you are using postgre sql use the following *command*

python manage.py sqlmigrate (App_name) (migration_number)

Here App_name is the name of the app which has the migration with migration number  migration_number 
*Note:* that you should use the above command only if you are using the sql based database as your backend otherthan *sqlLite3* which is default one.
After you should migrate all the migrations using the following *command*.

python manage.py migrate

#### Step-5
After applying all the migrations, now its time to run the website. Make sure that you have your environment ready with all the mentioned softwares installed. In your command prompt/terminal run this command to start the *django server*.

python manage.py runserver


Hence the *installation* and setup of the project is *done completely*.


## Hospitals-Registeration
### It is hospital registeration form ,hospital will register here
* From Main page, go to SignIn page.
* For Registering as a new Hospitals click SignUp button situated below forgot password option.
* In signup page, click Signup as a Hospitals.
* After clicking SignUp as a hospital, you will get a Registration form as shown below.



![](/img4.png)
* In hospital Registration Form, Fill all the details asked in the form and make sure the requirements are fulfilled like in Password it should contain a Capital letter, a small letter and some special characters and a minimum length of 8 charecters.
* After filling all details required in the form click on Register Button.

* After registering successfully, you will redirect to the main page with a message showing Activate your account after clicking the link sent to your mail.



### It is demo how to register here 



![](/reg.gif)
 * After registering successfully, you will redirect to the main page with a message showing Activate your account after clicking the link sent to your mail.
 * Click on that link, now you are succesfully registered as a Doctor and you will be redirected to the main page with the message Account Activated Succesfully.
  
## Doctors-Profile
### It is doctor profile , doctor can view profile and other how register in website they can view doctor profile using search bar 
 * From Main page, go to view profile.
 * See all doctor detail  

![](/img3.png)

 * Doctor name ,hospital to belong
 * Specicalistion , Exprience 
 * Time of meet the patient  

### It is doctor profile demo 
 * According to rating and review we can judge the service

![](/doc1.gif)


## Hospitals-Profile
### It is Hospitals profile , Hospitals can view profile and other how register in website they can view Hospitals profile using search bar
 * From Main page, go to view profile.
 * See all Hospital detail  

 
![](/img2.png)
  * Hospital name , Facilty in hospital
  * Doctor team, chief of doctor 
  * Update profile like hospital name, doctor team

### It is Hospitals profile demo


![](/host1.gif)
 * According to rating and review we can judge the service
## How-to-update-profile
## hospital and Doctor can update their profile
 * From profile page, go to update button.
 * Check use is doctor then update his profile and if it is user they can not update
 * Check use is Hospital then update his profile and if it is user they can not update
![](/img5.png)
* update Doctor and Hospital name
* update Profile photo
* update Specicalistion , Exprience
### It is  update  Demo
![](/update.gif)
* After update profile redirect in profile and get massage to update profile 
## Contributers
*  Hospitals-Registeration  frontend  part
*  Hospitals-Profile  frontend and backend part
*  Doctor-Profile  frontend and backend part
*  Update hospital and profile part
