
# Assignments
This file is used to submit the class practices for this semester 

## Class practice No.1 First Android App 
> In this Class practive we learned the following:
>- Install the Android Studio development environment.
>- Create an emulator (virtual device) to run your app on your computer.
>- Create and run the Hello World app on the virtual and physical devices.
>- Explore the project layout.
>- Generate and view log messages from your app.
>- Explore the AndroidManifest.xml file.

<img src="/Pictures/Helloworld app screenshot.jpg"
     alt="Hello world App"
     style="float: left; margin-right: 10px;" />

<

## Class Practice No.2 Layouts and resources for the UI
> In this Class practive we learned the following:
>- Create an app and add two Button elements and a TextView to the layout.
>- Manipulate each element in the ConstraintLayout to constrain them to the margins and other elements.
>- Change UI element attributes.
>- Edit the app's layout in XML.
>- Extract hardcoded strings into string resources.
>- Implement click-handler methods to display messages on the screen when the user taps each Button.
Back


<img src="/Pictures/Hello toast screenshot 1.jpg"
     alt="Hello toast App"
     style="float: left; margin-right: 10px;" />
     
<img src="/Pictures/Hello toast screenshot 2.jpg"
     alt="Hello toast App"
     style="float: left; margin-right: 10px;" />

## Class Practice No.2 Layouts and resources for the UI -- part B
> In this Class practive we learned the following:
>-Create a layout variant for a horizontal display orientation.
>- Create a layout variant for tablets and larger displays.
>- Modify the layout to add constraints to the UI elements.
>- Use ConstraintLayout baseline constraints to align elements with text.
>- Use ConstraintLayout pack and align buttons to align elements.
>- Change the layout to use LinearLayout.
>- Position elements in a LinearLayout.
>- Change the layout to use RelativeLayout.
>- Rearrange the views in the main layout to be relative to each othe

 <img src="/Pictures/Part B The layout editor 1.jpg"
     alt="Hello toast App"
     style="float: left; margin-right: 10px;" />

 <img src="/Pictures/Part B The layout editor 2.jpg"
     alt="Hello toast App"
     style="float: left; margin-right: 10px;" />

 <img src="/Pictures/Part B The layout editor 3.jpg"
     alt="Hello toast App"
     style="float: left; margin-right: 10px;" />

 <img src="/Pictures/Part B The layout editor 4.jpg"
     alt="Hello toast App"
     style="float: left; margin-right: 10px;" />


## Class Practice No.3 Activities and intents
> In this pratice we learned the following: 
>- Create a new Android app with a main Activity and a second Activity.
>- Pass some data (a string) from the main Activity to the second using an Intent, and display that data in the second Activity.
>- Send a second different bit of data back to the main Activity, also using an Intent.

 <img src="/Pictures/Activities and intents 3.jpg"
     alt=""
     style="float: left; margin-right: 10px;" />

     when the user clicks the send button in the first activity it will open the second activity with the text: "message recieved"  and the message displayed.

<img src="/Pictures/Activities and intents 4.jpg"
     alt=""
     style="float: left; margin-right: 10px;" />

    Aditionally we learned how to pass a massage from Activity one 

<img src="/Pictures/Activities and intents 5.jpg"
     alt=""
     style="float: left; margin-right: 10px;" />
Which is recieded and displayed on activity two 
<img src="/Pictures/Activities and intents 6.jpg"
     alt=""
     style="float: left; margin-right: 10px;" />
and a reply message was sent back to activity one from activity two.
NB: the original message still remains in the edittext in activity one caue we didnt clear the edittext
<img src="/Pictures/Activities and intents 7.jpg"
     alt=""
     style="float: left; margin-right: 10px;" />

## Class Practice No.4 Implicit Intents

> In this Class practive we learned the following:
>- Create a new app to experiment with implicit Intent.
>- Implement an implicit Intent that opens a web page, and another that opens a location on a map.
>- Implement an action to share a snippet of text.
>- Create a new app that can accept an implicit Intent for opening a web page.

the first app creates three intents:
#1 to open a URL
#2 to open a location
#3 to send some text
<img src="/Pictures/Implicit intents 1.jpg"
     alt=""
     style="float: left; margin-right: 10px;" />

when the user clicks the "SHARE THIS TEXT" Button the systen gives them the options of apps that can carry out this activity 
<img src="/Pictures/Implicit intents 2.jpg"
     alt=""
     style="float: left; margin-right: 10px;" />
when the user clicks the "OPEN WEBSITE" button the URL is opened in chrome browser
<img src="/Pictures/Implicit intents 3.jpg"
     alt=""
     style="float: left; margin-right: 10px;" />

we then created an Implicit Intents Reciever app  to open URLS and browse to that address
so now when we click the "OPEN WEBSITE" button the system displays options to complete that task
<img src="/Pictures/Implicit intents 4.jpg"
     alt=""
     style="float: left; margin-right: 10px;" />
NB: becasue of locations the location was not able to be displayed 
ie we are in china and google maps dont work

## Class Practice No.5 User Interaction clickable Images 
> In this Class practive we learned the following:
>- Create a new Android Studio project for a mock dessert-ordering app that uses images as interactive elements.
>- Set onClick() handlers for the images to display different Toast messages.
>- Change the floating action button supplied by the template so that it shows a different icon and launches another Activity.

the app name is Droid Cafe 
NOTE: when an image is clicked a toast message is displayed based on the image clicked 
<img src="/Pictures/clickable images 1.jpg"
     alt=""
     style="float: left; margin-right: 10px;" />

<img src="/Pictures/clickable images 2.jpg"
     alt=""
     style="float: left; margin-right: 10px;" />

<img src="/Pictures/clickable images 3.jpg"
     alt=""
     style="float: left; margin-right: 10px;" />

When the floating action Button is clicked 
it oens a new activity which is a child activity of the main activity

<img src="/Pictures/clickable images 4.jpg"
     alt=""
     style="float: left; margin-right: 10px;" />

## Class Practice No.6 User Interaction- Input controls
In this practice we learned the following:
>- Show a keyboard for entering an email address.
>- Show a numeric keypad for entering phone numbers.
>- Allow multiple-line text entry with automatic sentence capitalization.
>- Add radio buttons for selecting an option.
>- Set an onClick handler for the radio buttons.
>- Add a spinner for the phone number field for selecting one value from a set of values.

<img src="/Pictures/Input controls 1.jpg"
     alt=""
     style="float: left; margin-right: 10px;" />
we then added a radio button group to the app to display more options to the user
<img src="/Pictures/Input controls 2.jpg"
     alt=""
     style="float: left; margin-right: 10px;" />

<img src="/Pictures/Input controls 3.jpg"
     alt=""
     style="float: left; margin-right: 10px;" />
A spinner was added to allow the user to display they type of phone number 
<img src="/Pictures/Input controls 4.jpg"
     alt=""
     style="float: left; margin-right: 10px;" />

## Class Practice No.7 User Interaction- User Navigation 

In this practice we learned the following:
>- How to add the Up button to the app bar.
>- How to set up an app with tab navigation and swipe views.
>- Create a new app with tabs for navigating Activity screens that can also be swiped.
The up button was added to navigate back to the parent activity
<img src="/Pictures/User navigation 1.jpg"
     alt=""
     style="float: left; margin-right: 10px;" />
## Class Practice No.8 User Interaction- Recycler View