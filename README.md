# Checked

# I. Analysis
## 1. Research  
### a. Scope

People tend to forget to bring their belongings when they leave home to run their errands.
- Allow users to create a check list and location of items needed through an application.
- The sensor will inform user if the item stated in the check list is not in their bag.

### b. Audit
1. Review existing work and product

- https://tagla.com.my/shop/
Pros:
	- Easy to use , user do not need to learn many steps
	- Many function, can find item and also take selfie

2. Competitors 

   - manually written checklist, some users prefer traditional way

3. Relevant technologies 

   - wireless sensor tags
  	 - http://wirelesstag.net/index.html

### c. Stakeholder Interviews (internal / external)
1. Product{project} vision 
	- Be the first and best product that user can think of in managing their belongings. User need not to worry leaving their belongings at home.
2. risk
	- Do not have wifi connection and could not connect to the application.
	- User could not receive notification during low battery on their phone.


3. Obstacles
	- User's phone (device) gets stolen/ lost.

4. constraints 
	- Internet connection
	- Cost
5. opportunities 
	-In spite of the obstacles we have this project has strength from

a) Helping users in managing the items they need to bring for an occasion.

b) Save time in finding their belongings.

### d. User observations
Understand user needs and behavior and describe it.
Find various aspect of audience/customer
 
1. Users 
	- People that will left out their belongings at home often.

2. potential users 
	- Students, office worker, or traveller

3. (user's) behaviors 
	- Feel lazy to prepare everything at night and think of they can prepare everything tomorrow if they wake up early.

4. (user's) attitudes 
	- Will be panic when they woke up late and started to leave some important things behind.

5. (user's) aptitudes
	- Users can use this application to set up their checklist for their needs and just simply keep their phone in the bag and the app will detect what they've left out.

6. (user's) motivations
	- Users no need to worry about forgetting and lefting important things at home and make their journey more convenient.

7. (user's) environments
	- In their home, maybe things are messy and not knowing where is the thing they need when they can't keep calm and recall.

8. (user's) tools
	- In the application, users can set the position of the thing to prevent the situation that users can't manage to recall.

9. (user's) challenges
	- Users have to wake up early to prevent the clumsy situation.

## 2. Modeling
### a. Personas
user and customer archetypes

	Name | Gender
------------ | -------------
	Jane | Female
	Occupation | Officer
	Age	|  30

1. **goals**
	- Make user life easier, to find your things in more easy way.
	- Manage user time well, find things less than one minutes
	- Will not find important things in a mess.
	- Help user to make sure they brought all the things they need for an occasion.

2. Patterns in user and customer behaviors
	- People always like to do packing in last minute, will forgot to bring something important when going out from home

3. attitudes
	- Smart detector, and it can help user save their time, find important things less than a minute.

4. aptitudes
	- Scan the things that you want(within a bluetooth area, make sure all the stuff that you want is inside your bag

5. environments
	- The device can use in a bag, either you place your scanner in hand bag or luggage

6. tools
	-Each tag have their own QR Code. Scan the code in your phone, and you may rename it using an free application of "Checked".
	- The devices need to connect with your phone/tablet, you have to download an free application of "Checked", set a check list(items that you might want to bring) in your phone. 
	- A signal will show in your phone how far you and your things are separate. 
	- When you are leaving your home, you may have something left out, the signal become low, and your phone will ring, an the reminder pop out what's left behind.
	- The tag have light indicator when beeping(It also can be a light indicator itself)

7. challenges
	- To detect the items that listed down in check list, make sure all items are in the bag


# II. Synthesis
## 3. Requirements Definition
### a. Context Scenarios
Jane Tan's context scenario

Jane woke up late this morning and she have to conduct a very important meeting today. Jane rush up to get ready herself quickly then grab her important documents and rush out from home. On the second step she rushes out, her phone rang and shows from the application "Checked" which reminds her that something important had left out. "Checked" displayed the term "thumb drive" and "ID card" on the lock screen on her phone and she realized that she left her presentation slides and her pass to enter the company.

Immidiately, Jane rushes into her house and grab the things she left behind and luckily she is just on time to conduct her meting when she reaches the company. Jane presented with the presentation slides and distributed the documents to everyone in the meeting hall. During her meeting, she uses the light indicator on Checked's tag which is one of the fuction of the dwvice and successfully explained and highlighted all the main points. Everyone in the meting hall can easily understand what she is trying to presenting and the meeting was effective. 

She is glad that she prepared everything and tag all the things she need with Checked's last night to prevent her to miss out important things and ruin the meeting session.

### b. Requirements
Describe necessary capabilities of the product
- User Mental Models
	- Users can be at ease for not to left out anything important when they're leaving home.
- Design Imperatives
	- This product provides features that reminds users that what they've left out at home when they're heading out.
	- This product has a light indicator that is convinient for presentations. 
- Product Vision
	- Office workers, students and traveller are able to leave ther house without anything important left out at home.
- Business Requirements
	- Collected information
		- Users prefer devices which is light and can be able to carry everywhere for convinience.
	- Key Attributes of Product
		- Users can leave their house without any important stuffs left behind by checking the notifiation on their phone's lock 		   screen.
		- A customized devices specifically for office worker and students which are careless.
	- Scope Taken
		- To minimize the risk of lefting out important things when users are rushing out such as passport.
		- To make users more convinient as they didn't left out anything and able to go through the whole day.
	- Phases of the Project
		- With remind notification, users can be able to pass throught the day more convinient.
		- With lesser time and effort, users can be able to have everything which they need with them.
- Technology
	- When the users are preparing for their needs for the next day, tag is attached to the object and will let the user to rename and key in information through a smartphone application. The location of the object will be written into the application and when they rushed out of the rage that the tag detected, their phone will rang with notifivation that reminds users something had left out.

## 4. Design Framework

![GitHub Logo](/images/logo.png)
Format: ![Alt Text](https://cloud.githubusercontent.com/assets/20339755/18885079/af145e7c-851c-11e6-8102-25c3e982e091.jpg)
### a. Elements
#### i. From a factor, posture, and input method
- From factor	:- This is a device with mobile application
- From posture	:- Requires to attach the tags and key in data through mobile application, so the mode of attention are hand and fingers
- From input method :- It uses keypad, touch screen, radar and sensor.

#### ii. Functional and Data Elements
- Fundamental subject
	- Detect object which gets further from user and triger notification.
- Relationship between each other
	- After switching on GPS system, users' and tags' location will be detected and send reminder when the distance is over the range.
- Accomplish user's goal
	- Users can prevent leaving home with importi=ant things lefting behind.
- Best Fit and Design Principles
	- A mobile application and a tag which can attach wherever the users want.
- Fit within Technologies
	- This device is done by using radar, sensor and mobile phone as the technologies.
- Differentiation of Interaction from Competitors
	- This application is specifically for office workers and students by providing reminder that what they had left behind before leaving the house.
	
#### iii. Functional Groups and Hierarchy
![Image of Yaktocat](https://cloud.githubusercontent.com/assets/20280931/18897944/ee73e17a-8560-11e6-96e5-47cd21f8071a.png)
- Interaction Patterns and Principles
	- This application provides learnable interaction design, which users learn the functions.
	- This application provides consistent interaction design. Users are able to focus on the context when the elements, behaviours and styles are consistent.
- Select Primary View
	- By aiming users goal.

#### iv. Key Path Scenarios
- After installing the mobile application, Jane tap the "Settings" button and select her language as Enlish in the "language tab, so now she can briefly go through the "Help" tab to know the procedure to use the device and application.
- Jane signs up with her e-mail address. After attaching the tags on her things, she taps on the "Settings" button. Jane rename the tag's name that she attached to her things and key in the current location of the object.
- Jane turns on the "Notification" tab so that the reminders will pop-up on the lock screen and ring to remind her to take something.
- Everytime Jane changes the tag to another item, she rename and reinsert the the location of the item's current location to let her know where are the items when she's rushing, this saves time to find the item all over the house.

#### v. Validation Scenarios
- Alternative Scenarios
Jane finds its troublesome to rename and key in all the requirements everytime. Hence, she save the data as draft and when she need the data, she can just activate it.

- Necessary-Use Scenario
Jane is changing the mobile phone, but she's not willing to re-key in all the data she had now in the previous mobile. Hence, she can search back to her account by signing up with her e-mail, all the datas are automatically saved.


