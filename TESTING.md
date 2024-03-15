# HS MMA - Testing

## Validator Testing 

I used the W3C validator to check the HTML and CSS for the site. All tests passed with no issues.

### HTML

index.html
![index.html-test](assets/images/testing/index-test.png)

classes.html
![classes.html-test](assets/images/testing/classes-test.png)

sign-up.html
![sign-up.html-test](assets/images/testing/sign-up-test.png)

### CSS

style.css
![style.css-test](assets/images/testing/css-test.png)

## Lighthouse Testing

### Mobile

index.html  
![index-lighthouse-test-mobile](assets/images/testing/index-lighthouse-test-mob.png)

classes.html  
![classes-lighthouse-test-mobile](assets/images/testing/classes-lighthouse-test-mob.png)

signup.html  
![sign-up-lighthouse-test-mobile](assets/images/testing/signup-lighthouse-test-mob.png)

### Desktop

index.html  
![index-lighthouse-test-desktop](assets/images/testing/index-lighthouse-test-desk.png)

classes.html  
![classes-lighthouse-test-desktop](assets/images/testing/classes-lighthouse-test-desk.png)

signup.html  
![sign-up-lighthouse-test-desktop](assets/images/testing/signup-lighthouse-test-desk.png)

## Manual Testing 

### User Stories

#### First Time Visitor Goals

- To look for inspiration in joining a MMA gym, that reassures and welcomes newcomers to the sport.  
  - This is achieved with the why-join section on the index page, which details a few of many benefits of joining the gym.
  ![Why-Join](assets/images/readme/why-join.png)
- To quickly find out what classes are available, so I can check my favourite martial arts are included.
  - This is achieved with the classes timetable, easily located using the navbar. It details all classes offered and the times.
  ![Classes-Timetable](assets/images/readme/classes-timetable.png)
- To find contact information for the gym, so I can make enquiries.
  - This is achieved with the contact details section of the footer, to ensure it's always easy to find.
  ![Contact-Details](assets/images/readme/contact-details.png)
- To easily sign up for a membership, without too many fields or unnecessary questions.
  - This is achieved with the sign up form, which was intentionally kept simple for the user. They answer a few basic questions and the staff will contact them to finish the process and create a bespoke plan.
  ![Sign-Up-Form](assets/images/readme/sign-up-form.png)

#### Returning Visitor Goals

- To look at class times, so that I don't miss a session or can train in another martial art.
  - This is achieved with the classes timetable, it ensures it is simple to check when class is scheduled and shows the user all other available options.
  ![Classes-Timetable](assets/images/readme/classes-timetable.png)
- To keep up to date with any changes or additions to classes, so I can make the most of my membership.
  - This is also achieved with the classes timetable, it will be updated as changes are made so that members always know the latest options available to them.
  ![Classes-Timetable](assets/images/readme/classes-timetable.png)

### Feature Testing

#### Site-wide features

##### Logo

![HS-MMA-Logo](assets/images/testing/hs-mma-logo.png)
- Expected - Should take the user back to the index page if the user clicks on it.
- Testing - Will click on the logo on the classes page to go to the index page.
- Result - The site behaved as expected and I was taken to the index page.

##### Link hover effect

![Link-hover-effect](assets/images/testing/hover-effect.png)
- Expected - The Navbar links should be underlined when the user hovers over them.
- Testing - Will hover over the classes page whilst on the index page.
- Result - The site behaved as expected and the Classes page was underlined when hovered over.

##### Navbar home link

![Home-link](assets/images/testing/home-link.png)
- Expected - Should take the user to the index page if the user clicks on it.
- Testing - Will click on the index link on the sign up page.
- Result - The site behaved as expected and I was taken to the index page.

##### Navbar classes link

![Classes-link](assets/images/testing/classes-link.png)
- Expected - Should take the user to the classes page if the user clicks on it.
- Testing - Will click on the classes link on the index page.
- Result - The site behaved as expected and I was taken to the classes page.

##### Navbar sign up link

![Sign-up-link](assets/images/testing/sign-up-link.png)
- Expected - Should take the user to the sign up page if the user clicks on it.
- Testing - Will click on the sign up link on the index page.
- Result - The site behaved as expected and I was taken to the sign up page.

##### Footer facebook link

![Facebook-link](assets/images/testing/facebook-link.png)
- Expected - Should open facebook.com in a new tab if the user clicks on it.
- Testing - Will click on the facebook link.
- Result - The site behaved as expected and facebook.com opened in a new tab.

##### Footer X link

![X-link](assets/images/testing/x-link.png)
- Expected - Should open twitter.com in a new tab if the user clicks on it.
- Testing - Will click on the x link.
- Result - The site behaved as expected and twitter.com opened in a new tab.

##### Footer instagram link

![Instagram-link](assets/images/testing/instagram-link.png)
- Expected - Should open instagram.com in a new tab if the user clicks on it.
- Testing - Will click on the instagram link.
- Result - The site behaved as expected and instagram.com opened in a new tab.

##### Footer youtube link

![Youtube-link](assets/images/testing/youtube-link.png)
- Expected - Should open youtube.com in a new tab if the user clicks on it.
- Testing - Will click on the youtube link.
- Result - The site behaved as expected and youtube.com opened in a new tab.

#### Specific features

##### Form input fields

![Form-input-fields](assets/images/testing/form-input-fields.png)
- Expected - Should not allow the user to input incorrect data types to the input areas and only welcome the correct data types.
- Testing - Will fill in the form with fake user details to see if it accepts the data.
- Result - The site behaved as expected and allowed the user to complete the fields and submit the form.

##### Form submission

![Form-submission](assets/images/testing/form-submission.png)
- Expected - Should tell the user they have submitted the form correctly when the user has filled in their details and clicked submit.
- Testing - Will use a fake example of a user to complete the form.
- Result - The site behaved as expected and congratulated the user for submitting the form correctly.
