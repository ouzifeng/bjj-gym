![BJJ logo](https://github.com/ouzifeng/bjj-gym/blob/main/assets/images/bjj-logo.png)

# Brazilian Jiu-Jitsu Club



### Use Case

A client approached me who is starting up their own Brazilian Jit-Jitsu (BJJ) club in the local area. They feel that a website will be invaluable to their business for finding new students, and keeping existing students up to date with timetables and any other club related updates

![Responsive Image](https://github.com/ouzifeng/bjj-gym/blob/main/docs/responsive-design.png)
[Live Site](https://ouzifeng.github.io/CI_PP1_BJJ_GYM/)


## Project Scope

### End User Requirements

* Need to be able to find the gym
* Need to be able to contact the gym
* Need to know prices
* Need to know lesson schedule

### Customer Goals

* Find new students
* Be contactable by email
* Provide critical information about the gym to customers
* Promote the business on social media platforms
* Feel "friendly" and approachable

## User Experience

### Target Audience

* Potential students who are new to the sport and looking to join a gym for the first time
* Students who are already training but are looking for a new gym closer to their existing one
* Parents who want their children to try a new sport

## UX/UI

* Responsive design across mobile, tablet and desktop/laptops
* Easy to navigate and find critical information -> prices and timetable
* No dead links
* Placeholder for Facebook and Instagram pages (these are currently not setup)
* Simple way to contact the gym owner. The owner prefers to communicate through email as they don't have access to take calls during the day
* Simple design without distracting elements or long blocks of text

## User Stories

### New Student

* I want to know how to get to the gym, preferrably via an embedded map on the contact page
* I want to know how much it will cost me on a monthly or class by class basis, and whether there is a free trial
* I want to be able to check the timetable to see when classes are on
* I want to see images of the gym and students to get a feel for the place
* I want to be able to contact the gym if I have questions

### Existing Students

* I want to be able to check the timetable to see when classes are on
* I want to see images of myself and/or my classmates training


## Design

### Fonts

For the font choice we needed something which looked professional but also welcoming and friendly.

* Montserrat for headings
* Lato for body

### Colour Scheme

Based on how the leading gyms have built their colour schemes:
 * https://rogergracie.com/
 * https://ekbjj.com/ 
 * https://www.bjjlondon.com/
 * https://www.10thplanetjj.com/

 They are clean with plenty of constrasting colours - namely white with black. 

![](https://github.com/ouzifeng/bjj-gym/blob/main/assets/images/website-colours.png)

To keep with this theme, but with a lisght twist the 2 main colours will be baby powder and rich black, coupled with a choice of bolder colours for CTAs

### Wireframes

<details>

<summary>Home</summary>
![](https://github.com/ouzifeng/CI_PP1_BJJ_GYM/blob/main/docs/wireframes/Classes-Desktop.png)
![](https://github.com/ouzifeng/bjj-gym/blob/main/assets/images/wireframes/Home-Page-Tablet.png)
![](https://github.com/ouzifeng/bjj-gym/blob/main/assets/images/wireframes/Home-Page-Mobile.png)

</details>

<details>

<summary>Timetable</summary>
![](https://github.com/ouzifeng/bjj-gym/blob/main/assets/images/wireframes/Timetable-Desktop.png)
![](https://github.com/ouzifeng/bjj-gym/blob/main/assets/images/wireframes/Timetable-Tablet.png)
![](https://github.com/ouzifeng/bjj-gym/blob/main/assets/images/wireframes/Timetable-Mobile.png)

</details>

<details>

<summary>Contact</summary>
![](https://github.com/ouzifeng/bjj-gym/blob/main/assets/images/wireframes/Contact-Desktop.png)
![](https://github.com/ouzifeng/bjj-gym/blob/main/assets/images/wireframes/Contact-Tablet.png)
![](https://github.com/ouzifeng/bjj-gym/blob/main/assets/images/wireframes/Contact-Mobile.png)

</details>

<details>

<summary>Classes</summary>
![](https://github.com/ouzifeng/bjj-gym/blob/main/assets/images/wireframes/Classes-Desktop.png)
![](https://github.com/ouzifeng/bjj-gym/blob/main/assets/images/wireframes/Classes-Tablet.png)
![](https://github.com/ouzifeng/bjj-gym/blob/main/assets/images/wireframes/Classes-Mobile.png)

</details>

## Technologies & Resources Used

#### HTML AND CSS

* Balsamiq for wireframe designs 
* Google Fonts for fonts
* Photoshop
* Canva
* Coolors
* Bootsrap V5
* Microsoft Bing Image Generator (logo)
* Compressor.io to losslessy reduce image size


## Testing

### HTML validation

Tool for HTML Validation - W3C HTML Validation Service


index.html [results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fouzifeng.github.io%2FCI_PP1_BJJ_GYM%2Findex.html)

404.html [results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fouzifeng.github.io%2FCI_PP1_BJJ_GYM%2F404.html)

classes.html [results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fouzifeng.github.io%2FCI_PP1_BJJ_GYM%2Fclasses.html)

contact.html [results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fouzifeng.github.io%2FCI_PP1_BJJ_GYM%2Fcontact.html)

prices.html [results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fouzifeng.github.io%2FCI_PP1_BJJ_GYM%2Fprices.html)

timetable.html [results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fouzifeng.github.io%2FCI_PP1_BJJ_GYM%2Ftimetable.html)


### CSS Validation

Tool for CSS Validation - W3C CSS Validation Service

style.css[results](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fouzifeng.github.io%2FCI_PP1_BJJ_GYM%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

Results = 25 errors and 491 warnings. Of which the 25 errors are coming from Bootstraps https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css and 419 warnings from Bootstraps https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css

Manually copy and pasting my style.css into the validator results in Congratulations! No Error Found.

### Accessibility

The WAVE WebAIM web accessibility evaluation tool was used to ensure the website met the neccessary accessibility standards. All pages pass with zero errors.

index.html [results](https://wave.webaim.org/report#/https://ouzifeng.github.io/CI_PP1_BJJ_GYM/index.html)
404.html [results](https://wave.webaim.org/report#/https://ouzifeng.github.io/CI_PP1_BJJ_GYM/404.html)


