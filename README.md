# User Centric Project BG

'Patient Self-Service' will provide an unique service to patients commencing with two key features - appointments and prescriptions. This website will give patients the flexibility to schedule appointments and order their prescriptions at a time that suits them. Responsive design will allow users use a device of their choice. 
It will provide a platform to rollout additional enhancements in the near future.
This project was deployed to the live website using 'GH Pages' - https://gallaghb.github.io/user-centric-project-bg/

## UX

This website is for everyone and especially patients who attend their GP on a regular basis. These patients will also have their medicine prescribed on a frequency basis. Patients nowadays use alot of different devices and are very comforable carrying out various activities online. Users want a positive experience when interacting online, they want not only an intuitive website but one that is easy to use and enjoyable.<br/>

### User Stories
- As a Patient, I want to be able to navigate easily between menu items, so that I will want to return to this site as it's intuitive and easy to use
- As a Patient, I want consistency across the site I'm visiting, so that it is easy to use
- As a Patient, I want to be able to click on links to external sites,	so that	I don't have to seperate web searches
- As a Patient, I want external links to open in a seperate browser, so that I can easily return to the main site
- As a Patient, I want to connect with you through social media, so that I can interact on different social media outlets
- As a Patient, I want content to be concise, so that it is easier to use and navigate
- As a Patient, I want to be able to contact you, so my queries will be answered in a channel of my choice
- As a Patient, I want to be able to make an appointment with my GP online, so that I choose a date and time that suits me
- As a Patient, I want to order my prescriptions online, so that "I don't have to: ring GP to order prescription, call to GP Surgery to collect prescription, drop prescription to pharmacy, wait at pharmacy until prescription is ready"
- As a Patient, I want to view your website on my mobile, so that I can book appointments or order prescriptions no matter where I am 
- As a Patient, I want to view your website on my tablet, so that I can use a device of my preference
- As a Patient, I want to view your website on my laptop/desktop, so that I can use a device of my preference

### Design
The following documents were created as part of the [design](https://github.com/gallaghb/user-centric-project-bg/blob/07c8cf346a63946b9cb78ecbc7157d5914016231/assets/design) process
- High Level Project Plan
- 5 Planes
- Prototype Mock Ups
- Test Script

## Features

### Existing Features
- Feature 1 - Clicking on the logo will bring you back to the homepage
- Feautre 2 - Nav/Menu items will 'sweep to right'
- Feature 3 - Appointment page, mid-screen - image not to appear on mobile
- Feature 4 - Prescription page, mid-screen - image not to appear on mobile
- Feature 5 - Submit button on Appointment page - hover over button to change colour
- Feature 6 - Order Now button on Prescription page - hover over button to change colour
- Feature 7 - Submit butt on Contact Us page - hover over button to change colour
- Feature 8 - External Links will open in a separate browser
- Feature 9 - Social Media links will open in a separate browser
- Feature 10 - Social Media links - hover over buttons to change colour

### Features Left to Implement
The following shows additional features to be implemented in the future:
- Sign In/SignUp Option - once logged in you will have access to your scheduled appointments/status of prescription e.g. expires on dd/mm
- Link to GP Booking System - only show available appointments online in 'Patient Self-Service'
- Confirmation text/email/what's app message re 'Appointments'
- Reminder to patients <1> day prior to appointment
- Confirmation text/email/what's app message from GP that 'Prescription' was sent to Pharmacy
- Link up with Pharmacy
- Text/email/what's app message from pharmacy when 'Prescription' is ready for collection

## Technologies Used

- [HTML](https://en.wikipedia.org/wiki/HTML)
    - **Hypertext Markup Language** used for the main structure of the 'Patient Self-Service' website. Index.html contains the header, body and footer elements. The Header and Footer is replicated on all pages. 

- [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
    - **Cascading Style Sheets** used to override Bootstrap defaults and to customise or make the site my own. 

- [Bootstrap](https://getbootstrap.com/)
    - **Bootstrap** Framework used for its mobile first design and large library of preassembled and reusable CSS style/components. The following components were dropped into my project - nav / forms / buttons.


## Testing

Manual testing was carried out on all scenarios. The 'Test Script' can be found in the [design](https://github.com/gallaghb/user-centric-project-bg/blob/07c8cf346a63946b9cb78ecbc7157d5914016231/assets/design) folder 

Testing was carried out after each iteration or sprint and bug defects were fixed and retested. 

HTML files were validated using a [html validator](https://validator.w3.org/) and file indentation was checked using a [html formatter](https://www.freeformatter.com/html-formatter.html).  CSS file was validated using a [css validator](https://jigsaw.w3.org/css-validator/)

Testing was also carried out in different devices and browsers, the test summary can be found [here](https://github.com/gallaghb/user-centric-project-bg/blob/07c8cf346a63946b9cb78ecbc7157d5914016231/assets/test%20summary)

1. Header
    1. Click on logo - logo should ease in and out 
	2. Click on Appointment on nav, click on logo - you will be brought back to the home page
    3. Click on Prescription on nav, click on logo - you will be brought back to the home page
    4. Click on Contact Us nav, click on logo - you will be brought back to the home page
2. Nav Items
    1. Hover over Home - home button changes colour
	2. Hover over Appointment - appointment button changes colour
	3. Hover over Prescription - prescription button changes colour
	4. Hover over Contact Us - contact us button changes colour
	5. Click on Appointment - appointment page opens 
	6. Then Click on Home - home page opens
	7. Click on Prescription - prescription page opens
	8. Then Click on Home - home page opens 
	9. Click on Contact Us - contact us page opens
	10. Check content + spellings on all pages 
3. Footer
    1. External Links, click on HIA link - HIA website opens in a seperate browser
	2. Click on Irish Life Health link - Irish Life Health website opens in a separate browser
	3. Click on VHI link - VHI website opens in a separate browser
	4. Social Media, click on Facebook - Facebook website will open in a separate browser
	5. Click on Twitter - Twitter website will open in a separate browser
	6. Click on LinkedIn - LinkedIn website will open in a separate browser
	7. Click on Pinterest - Pinterest website will open in a separate browser
	8. Click on Instagram - Instagram website will open in a separate browser
	9. Click on YouTube - YouTube website will open in a separate browser
	10. Check content + spellings
	11. Repeat above tests on Appointment Page
	12. Repeat above tests on Prescription Page
	13. Repeat above tests on Contact Us Page
4. Home Section
    1. About Us! - check content + spelling
	2. Self-Service - check content + spelling
	3. Prescription - check content + spelling
	4. Appointment - check content + spelling
5. Appointment Section
	1. Check Appointment Image 
	2. Check content + spellings
	3. Input full name
	4. Input DOB
	5. Input GP Practice Name
	6. Input GP Name
	7. Select Date from drop down
	8. Select Time from drop down
	9. Do not enter details in 'required' fields - error messages received
	10. Hover over Submit button - button changes colour
	11. Click on Submit button - blank form appears
6. Prescription Section
    1. Check Prescription Image
	2. Check content + spellings
	3. Input full name
	4. Input DOB
	5. Input GP Practice Name
	6. Input GP Name
	7. Select frequency from drop down
	8. Do not enter details in 'required' fields - error messages received
	9. Hover over Order Now button - button changes colour
	10. Click on Order Now button - blank form appears
7. Contact Us Section
    1. Reach out section, check content + spellings
	2. Reach out section, test email
	3. Input email
	4. Test email validation
	5. Input name
	6. Input message + vary length of message
	7. Do not enter details in 'required' fields - error messages received
	8. Hover over Submit button - button changes colour
	9. Click on Submit button - blank form appears
8. User Stories	
    1. Review User Stories to ensure all user expectations are met
9. Responsive Design
    1. Mobile, Test on Mobile
	2. Tablet, Test on Tablet
	3. Desktop, Test on Desktop
10. Browsers
    1. Different Browsers, Test on different browsers
11. GitHub Pages
    1. GitHub, Test on live Website

## Deployment

This project was developed on GitPod, using git and GitHub to host the repository.

When deploying this project using GitHub Pages be sure to follow these steps:

1. GitHub Pages
    1. Navigate to project by [clicking here](https://github.com/gallaghb/user-centric-project-bg/settings)
    2. In the top navigation, click on 'settings'
    3. Scroll down to GitHub Pages area
    4. Select 'master branch'from the source drop down menu
    5. Click to confirm my selection
    6. Project should now be live on [GitHub Pages](https://gallaghb.github.io/user-centric-project-bg/)
    
In order to run this project locally be sure to follow these steps whilst still on Github: 

2. GitHub Locally
    1. Navigate to project or [click here](https://github.com/gallaghb/user-centric-project-bg/settings)
    2. Click the green 'Clone or Download' button
    3. Copy the url in the dropdown box
    4. Using your IDE of choice open up your preferred terminal
    5. Navigate to your desired file location
    6. Copy the following code and input it into your terminal to clone this project, git clone https://github.com/gallaghb/user-centric-project-bg.git

## Credits

## Content
The text was not sourced from any other source or website, it was devised by me

## Media
Logo, Appointment and Prescription Images were sourced from [pexels website](https://www.pexels.com/)
Icons were sourced from [font awesome website](https://fontawesome.com/icons?d=gallery)

## Acknowledgements
I received inspiration for the design of this project from [Module5 - Resume Project](https://courses.codeinstitute.net/courses/course-v1:codeinstitute+FE+2017_T3/courseware/616289d66b5641a3808cc43e53842695/36e3366dbdaf40fd852994c51f9f8595/?child=last) 
I want to give credit to my mentor, Precious Ijege for his feedback and support on this project.