# User Centric Project BG

'Patient Self-Service' will provide an unique service to patients commencing with two key features - appointments and prescriptions. This website will give patients the flexibility to schedule appointments and order their prescriptions at a time that suits them. Responsive design will allow users use a device of their choice. 
It will provide a platform to rollout additional enhancements in the near future.  <br/>This project was deployed to the live website using 'GH Pages' - https://gallaghb.github.io/user-centric-project-bg/

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
The following documents were created as part of the design process, see [Design Folder](/https://b5ca6965-e8e0-4e7f-a5ca-47bf5fd928c4.ws-eu01.gitpod.io/#/workspace/user-centric-project-bg/assets/design)
- High Level Project Plan
- 5 Planes
- Prototype Mock Ups
- Test Script
- Test Results

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

Manual testing was carried out on all scenarios as per my [Test Script](/https://b5ca6965-e8e0-4e7f-a5ca-47bf5fd928c4.ws-eu01.gitpod.io/#/workspace/user-centric-project-bg/assets/design)

Testing was carried out after each iteration or sprint and bug defects were fixed and retested. 

HTML files were validated using a [html validator](https://validator.w3.org/) and file indentation was checked using a [html formatter](https://www.freeformatter.com/html-formatter.html)
CSS file was validated using a [css validator](https://jigsaw.w3.org/css-validator/)

Testing was also carried out in different devices and browsers, see [Test Results]()

1. Header
    1. Logo	Click on logo 
	2. Repeat above test on Page 2
	3. Repeat above test on Page 3
	4. Repeat above test on Page 4
2. Nav Items
    1. Hover over Home 
	2. Hover over Appointment
	3. Hover over Prescription
	4. Hover over Contact Us
	5. Click on Appointment 
	6. Click on Home
	7. Click on Prescription
	8. Click on Home
	9. Click on Contact Us
	10. Check content + spellings
	11. Repeat above test on Page 2
	12. Repeat above test on Page 3
	13. Repeat above test on Page 4
3. Footer
    1. External Links	Click on HIA link
	2. Click on Irish Life Health link
	3. Click on VHI
	4. Social Media	Click on Facebook
	5. Click on Twitter
	6. Click on LinkedIn
	7. Click on Pinterest
	8. Click on Instagram
	9. Click on YouTube
	10. Check content + spellings
	11. Repeat above test on Page 2
	12. Repeat above test on Page 3
	13. Repeat above test on Page 4
4. Mid-Area Page 1	Center-Home	
    1. About Us! - check content + spelling
	2. Self-Service - check content + spelling
	3. Prescription - check content + spelling
	4. Appointment - check content + spelling
5. Mid-Area Page 2	Center-Appointment
	1. Check Appointment Image
	2. Check content + spellings
	3. Input full name
	4. Input DOB
	5. Input GP Practice Name
	6. Input GP Name
	7. Select Date from drop down
	8. Select Time from drop down
	9. Do not enter details in 'required' fields
	10. Hover over Submit button
	11. Click on Submit button
6. Mid-Area Page 3	Center-Prescription
    1. Check Prescription Image
	2. Check content + spellings
	3. Input full name
	4. Input DOB
	5. Input GP Practice Name
	6. Input GP Name
	7. Select frequency from drop down
	8. Do not enter details in 'required' fields
	9. Hover over Order Now button
	10. Click on Order Now button
7. Mid-Area Page 4	Center-Contact Us
    1. Reach out section, check content + spellings
	2. Reach out section, test email
	3. Input email
	4. Test email validation
	5. Input name
	6. Input message + vary length of message
	7. Do not enter details in 'required' fields
	8. Hover over Submit button
	9. Click on Submit button
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


Code will be deployed from GitPod to GitHub using the Git commands of git add / git commit / git push
     - moving from staging area to local repository to remote repository
GitHub location - https://github.com/gallaghb/user-centric-project-bg.git
Code will be deployed to the live website using the publishing source of 'GitHub Pages'
GitHub Pages location - https://gallaghb.github.io/user-centric-project-bg/

## Credits
I was to give credit to my mentor, Precious Ijege for his feedback and support on this project.

## Content
The text was not sourced from any other source or website, it was devised by me

## Media
Logo, Appointment and Prescription Images were sourced from [pexels website](https://www.pexels.com/)
Icons were sourced from [font awesome website](https://fontawesome.com/icons?d=gallery)


## Acknowledgements
I received inspiration for the design of this project from 'Module 5 - Sample Projects' 
