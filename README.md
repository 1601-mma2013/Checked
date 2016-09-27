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
TAG La Trading, a Malaysian-born company with a passion for interactive technology and developing convenient gadgets for everyday life, this past year released a revolutionary solution to finding missing items: the TAG La Bluetooth Tracker. Designed to help people keep track of important items that are easy to lose, such as phones, keys, and iPads
2. Competitors 

   - manually written checklist

3. Relevant technologies 

   - wireless sensor tags
   - http://wirelesstag.net/index.html

### c. Stakeholder Interviews (internal / external)
Understand product vision and constraints
1. product{project} vision 
Be the first and best product that user can think of in managing the iteir belongings. User need not to worry leaving their belongings at home.
2. risk
- Do not have wifi connection and could not connect to the application.


3. Obstacles
- User's phone (device) gets stolen/ lost.
4. constraints 
	1. Internal limitations 
		2. viable technologies
		2. cost
5. opportunities 
	1. **In spite of** the obstacles we have this project has strength from a), b), c), â€¦. 
	2. Persisting problem

5. users 

### d. User observations
Understand user needs and behavior and describe it.
Find various aspect of audience/customer
 
1. Users 
	- Everyone.

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

1. **goals**
	- Make user life easier, to find your things in more easy way.
	- Manage user time well, find things less than one minutes
	- Will not find important things in a mess

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

### b. Other Models
Represent domain factors beyond individual users and customers
1. Workflows among multiple people
	- You can scan several things when you listed out in your devices, through the application

2. environments
	- Place device in a bag/luggage

3. artifacts
	- Smart detector

# II. Synthesis
## 3. Requirements Definition
### a. Context Scenarios
Jane Tan's context scenario

Jane woke up late this morning and she have to conduct a very important meeting today. Jane rush up to get ready herself quickly then grab her important documents and rush out from home. On the second step she rushes out, her phone rang and shows from the application "Checked" which reminds her that something important had left out. "Checked" displayed the term "thumb drive" and "ID card" on the lock screen on her phone and she realized that she left her presentation slides and her pass to enter the company.

Immidiately, Jane rushes into her house and grab the things she left behind and luckily she is just on time to conduct her meting when she reaches the company. Jane presented with the presentation slides and distributed the documents to everyone in the meeting hall. During her meeting, she uses the light indicator on Checked's tag which is one of the fuction of the dwvice and successfully explained and highlighted all the main points. Everyone in the meting hall can easily understand what she is trying to presenting and the meeting was effective. 

She is glad that she prepared everything and tag all the things she need with Checked's last night to prevent her to miss out important things and ruin the meeting session.

### b. Requirements
Describe necessary capabilities of the product
1. user mental models
	- Users can be at ease for not to left out anything important when they're leaving home.
2. design imperatives
	- This product provides features that reminds users that what they've left out at home when they're heading out.
	- This product has a light indicator that is convinient for presentations. 
3. product vision
	- Office workers, students and traveller are able to leave ther house without anything important left out at home.
4. business requirements
	- Collected information
		- Users prefer devices which is light and can be able to carry everywhere for convinience.
	- Key Attributes of Product
		- Users can leave their house without any important stuffs left behind by checking the notifiation on their phone's lock 		   screen.
		- A customized devices specifically for office worker and students which are careless.
	- Scope Taken
		- To minimize the risk of lefting out important things when users are rushing out such as passport.
		- To make users more convinient as they didn't left out anything and able to go through the whole day.
	- technology
		- When the users are preparing for their needs for the next day, tag is attached to the object and will let the user to rename and key in information through a smartphone application. The location of the object will be written into the application and when they rushed out of the rage that the tag detected, their phone will rang with notifivation that reminds users something had left out.
	- Phases of the Project
		- With remind notification, users can be able to pass throught the day more convinient.
		- With lesser time and effort, users can be able to have everything which they need with them.

6. technology

## 4. Design Framework
### a. Elements
Deï¬ne manifestations of information and functionality
1. Information

2. functions

3. mechanisms

4. actions

5. domain object models

### b. Framework
Design overall structure of user experience
1. Object relationships
2. Conceptual groupings
3. Navigation sequencing
4. Principles and patterns
5. Floor Plan
	6. flow
	7. sketches
		- https://cloud.githubusercontent.com/assets/20339755/18885079/af145e7c-851c-11e6-8102-25c3e982e091.jpg
	8. storyboards
### c. Key Path and Validation Scenarios
Describe how the persona interacts with the product
- “Checked” - Key Path Scenario
- 1. In the morning, it is a very busy day ahead for Jane. Jane wake up late and she is in a rush because she need to conduct an important meeting which she done a project for her company. Jane grab a folder that filled with some important documents.
- 2. Jane rush out from home, but actually she had left something important behind. On the second she is standing at the doorstep preparing to leave home, her phone rang. Jane check on her phone, she feel grateful when she realize that this is a reminder alert from the smart device, which is “Checked”. 
- 3. On the phone screen, a reminder box pop out that listed “thumb drive”, “ID card”. These are the 2 most important thing that Jane left when she is in a rush.  
- 4. Jane knew that she is a forgetful, and careless person. Thus, on yesterday she used “Checked” to tag all her important document for meeting. She attached the tag on her thumb drive, file, and also her ID card. 
- 5. After she attached the important things, she open the application of “Checked” in her phone. She started to fill in the check list, and rename the tag name with “thumb drive”, “file”, and “ID card”.
- 6. Luckily, Jane reach the company in time and she walk in to the meeting hall. She start to present her work. She distribute the document to her boss for reference. She also present her work in slide. She used the light indicator, which is one of the function on the tag of “Checked”, to point out the keyword on the presentation slide.
- 7. Her boss is happy with her presentation, because she manage to higlight all the key word on the presentation slide, and she presented perfectly in the meeting.
- "Checked" - Validation Scenario
- 1. 




