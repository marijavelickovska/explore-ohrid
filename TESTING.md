# Testing

> Return back to the [README.md](README.md) file.

## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Directory | File | URL | Screenshot | Notes |
| --- | --- | --- | --- | --- |
|  | [404.html](https://github.com/marijavelickovska/explore-ohrid/blob/main/404.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://marijavelickovska.github.io/explore-ohrid/404.html) | ![screenshot](documentation/validation/html--404.png) | Notes (if applicable) |
|  | [booking.html](https://github.com/marijavelickovska/explore-ohrid/blob/main/booking.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://marijavelickovska.github.io/explore-ohrid/booking.html) | ![screenshot](documentation/validation/html--booking.png) | Notes (if applicable) |
|  | [index.html](https://github.com/marijavelickovska/explore-ohrid/blob/main/index.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://marijavelickovska.github.io/explore-ohrid/index.html) | ![screenshot](documentation/validation/html--index.png) | Notes (if applicable) |
|  | [stay-taste.html](https://github.com/marijavelickovska/explore-ohrid/blob/main/stay-taste.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://marijavelickovska.github.io/explore-ohrid/stay-taste.html) | ![screenshot](documentation/validation/html--stay-taste.png) | Notes (if applicable) |
|  | [success.html](https://github.com/marijavelickovska/explore-ohrid/blob/main/success.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://marijavelickovska.github.io/explore-ohrid/success.html) | ![screenshot](documentation/validation/html--success.png) | Notes (if applicable) |
|  | [tours.html](https://github.com/marijavelickovska/explore-ohrid/blob/main/tours.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://marijavelickovska.github.io/explore-ohrid/tours.html) | ![screenshot](documentation/validation/html--tours.png) | Notes (if applicable) |


### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| Directory | File | URL | Screenshot | Notes |
| --- | --- | --- | --- | --- |
| assets | [style.css](https://github.com/marijavelickovska/explore-ohrid/blob/main/assets/css/style.css) | [CSS Validator](https://jigsaw.w3.org/css-validator/validator?uri=https://marijavelickovska.github.io/explore-ohrid) | ![screenshot](documentation/validation/css-assets-style.png) | Notes (if applicable) |



## Responsiveness

I've tested my deployed project to check for responsiveness issues.

| Page | Mobile | Tablet | Desktop | Notes |
| --- | --- | --- | --- | --- |
| Home | ![screenshot](documentation/responsiveness/home-mobile.png) | ![screenshot](documentation/responsiveness/home-tablet.png) | ![screenshot](documentation/responsiveness/home-desktop.png) | Works as expected |
| Tours | ![screenshot](documentation/responsiveness/tours-mobile.png) | ![screenshot](documentation/responsiveness/tours-tablet.png) | ![screenshot](documentation/responsiveness/tours-desktop.png) | Works as expected |
| Stay and Taste | ![screenshot](documentation/responsiveness/stay-taste-mobile.png) | ![screenshot](documentation/responsiveness/stay-taste-tablet.png) | ![screenshot](documentation/responsiveness/stay-taste-desktop.png) | Works as expected |
| Booking | ![screenshot](documentation/responsiveness/booking-mobile.png) | ![screenshot](documentation/responsiveness/booking-tablet.png) | ![screenshot](documentation/responsiveness/booking-desktop.png) | Works as expected |
| Confirmation | ![screenshot](documentation/responsiveness/confirmation-mobile.png) | ![screenshot](documentation/responsiveness/confirmation-tablet.png) | ![screenshot](documentation/responsiveness/confirmation-desktop.png) | Works as expected |
| 404 | ![screenshot](documentation/responsiveness/404-mobile.png) | ![screenshot](documentation/responsiveness/404-tablet.png) | ![screenshot](documentation/responsiveness/404-desktop.png) | Works as expected |


## Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Page | Chrome | Firefox | Edge | Notes |
| --- | --- | --- | --- | --- |
| Home | ![screenshot](documentation/browsers/chrome-home.png) | ![screenshot](documentation/browsers/firefox-home.png) | ![screenshot](documentation/browsers/edge-home.png) | Works as expected |
| Tours | ![screenshot](documentation/browsers/chrome-tours.png) | ![screenshot](documentation/browsers/firefox-tours.png) | ![screenshot](documentation/browsers/edge-tours.png) | Works as expected |
| Stay and Taste | ![screenshot](documentation/browsers/chrome-stay-taste.png) | ![screenshot](documentation/browsers/firefox-stay-taste.png) | ![screenshot](documentation/browsers/edge-stay-taste.png) | Works as expected |
| Booking | ![screenshot](documentation/browsers/chrome-booking.png) | ![screenshot](documentation/browsers/firefox-booking.png) | ![screenshot](documentation/browsers/edge-booking.png) | Works as expected |
| Confirmation | ![screenshot](documentation/browsers/chrome-confirmation.png) | ![screenshot](documentation/browsers/firefox-confirmation.png) | ![screenshot](documentation/browsers/edge-confirmation.png) | Works as expected |
| 404 | ![screenshot](documentation/browsers/chrome-404.png) | ![screenshot](documentation/browsers/firefox-404.png) | ![screenshot](documentation/browsers/edge-404.png) | Works as expected |


## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues. Some warnings are outside of my control, and mobile results tend to be lower than desktop.

| Page | Mobile | Desktop |
| --- | --- | --- |
| Home | ![screenshot](documentation/lighthouse/mobile-home.png) | ![screenshot](documentation/lighthouse/desktop-home.png) |
| Tours | ![screenshot](documentation/lighthouse/mobile-tours.png) | ![screenshot](documentation/lighthouse/desktop-tours.png) |
| Stay and taste | ![screenshot](documentation/lighthouse/mobile-stay-taste.png) | ![screenshot](documentation/lighthouse/desktop-stay-taste.png) |
| Booking | ![screenshot](documentation/lighthouse/mobile-booking.png) | ![screenshot](documentation/lighthouse/desktop-booking.png) |
| Confirmation | ![screenshot](documentation/lighthouse/mobile-confirmation.png) | ![screenshot](documentation/lighthouse/desktop-confirmation.png) |
| 404 | ![screenshot](documentation/lighthouse/mobile-404.png) | ![screenshot](documentation/lighthouse/desktop-404.png) |

## Defensive Programming

Defensive programming was manually tested with the below user acceptance testing:


| Page | Expectation | Test | Result | Screenshot |
| --- | --- |  --- |  --- |  --- |
 | Home | Feature is expected to display content and images to attract users to book a tour. | Verified that the page displays the agency's purpose in a clear and concise manner. | The purpose were displayed as expected. | ![screenshot](documentation/defensive/home.png)|
| Navbar | Feature is expected to have accessible navigation links. | Checked navigation links for correct functionality and accessibility. | Navigation links were functional and accessible. | ![screenshot](documentation/defensive/navigation.png) |
| | Feature is expected to be fully responsive. | Resized the browser window and tested on multiple devices (mobile, tablet, desktop). | The page was responsive across all tested screen sizes. | ![screenshot](documentation/defensive/responsive.png) |
| Explore Ohrid | Feature is expected to show the user attractions that Ohrid has to offer. | Confirmed that the page contains a structured text explaining the attractions, as well as a carousel with images for visually displaying them. | Text and images was displayed as expected and the button "See Our Tours" redirect the user to the tours page. | ![screenshot](documentation/defensive/explore-ohrid.png) |
| Testimonials | Feature is expected to display testimonials from people who have visited the tours. | Verified that the page shows all testimonials. | Testimonials were displayed as expected. | ![screenshot](documentation/defensive/testimonials.png) |
| Contact | Feature is expected to display all contact information for the agency, as well as its opening hours. | Verified that the contact contains all the necessary information, such as address, phone, email, and opening hours. | Contact information is displayed as expected, visible and easily accessible. | ![screenshot](documentation/defensive/contact.png) |
| Social Links | Feature is expected to include working links to the explore Ohrid agency's social platforms (Instagram, Facebook, etc.). | Clicked each social link to verify redirection to the correct platform page. | All links redirected to the correct platform pages, opening in new browser tabs. | ![screenshot](documentation/defensive/socialmedia.png) |
| Tours | Feature is expected to display all the tours offered by the agency with all the details for each of them. | Confirmed that all tours are displayed correctly as must-see and must-do tours. For each tour, an image and details about the date and price are shown. Also, a link leading to the 'book now' form is provided. | Tours are displayed as expected, the link redirect to the booking page.| ![screenshot](documentation/defensive/tours.png) |
| Accomodations and restaurants | Feature is intended to offer recommendations for hotels and restaurants. | Confirmed that the page contains a separate section for accommodation offers and a separate section for restaurant offers, as well as links to see more for each recommendation. | Accomodations and restaurants are displayed as expected. The links opens in a new tab. | ![screenshot](documentation/defensive/accommodations.png) |
| Book-now Form | Feature is expected to prevent submission of an empty form. | Attempted to submit the form without filling any fields. | Form submission was blocked, as expected. | ![screenshot](documentation/defensive/booknow.png) |
| Confirmation | Feature is intended to confirm to the user that they have successfully submitted the form. | Confirmed that after filling out all the inputs in the form and successfully submitting the form, a confirmation appears informing the user that the form has been successfully submitted. | Confirmation is displayed as expected. | ![screenshot](documentation/defensive/confirmation.png) |
| 404 Error Page | Feature is expected to display a 404 error page for non-existent pages. | Navigated to an invalid URL (e.g., `/test`) to test error handling. | A custom 404 error page was displayed as expected. | ![screenshot](documentation/defensive/404.png) |

## User Story Testing

| Target | Expectation | Outcome | Screenshot | 
| --- | --- | --- | --- | 
| As a user  | I want to read and see some information about the city                                         | so that I can be better informed about what it offers before visiting.       | ![screenshot](documentation/features/explore-ohrid.png) |
| As a user  |  I want to see photos of the tours                                   | so I can visually compare them, choose the most appealing one, and select the best option for me.               | ![screenshot](documentation/features/explore-ohrid.png) |
| As a user  | I want each tour to display details about the schedule and price                | so that I can choose the one that best fits my budget and preferences.              | ![screenshot](documentation/features/must-see.png) |
| As an user | I want to read experiences and reviews from others                  | so that I can be sure I want to explore Ohrid through this agency.                 | ![screenshot](documentation/features/testimonials.png) |
| As a user  | I want to see recommendations for accommodation                       | as I feel more relaxed when I can organize my entire trip in one place.               | ![screenshot](documentation/features/accommodations.png) |
| As a user  | I want to see recommendations for  restaurants                      | as I feel more relaxed when I can organize my entire trip in one place.               | ![screenshot](documentation/features/restaurants-bars.png) |
| As a user  | I want to have the option to book tours through the website | so that I can secure my spot in advance.                                | ![screenshot](documentation/features/booknow.png) |
| As a user  | I want to see a confirmation message after submitting the form | so I can be sure that the tour has been reserved.   | ![screenshot](documentation/features/confirmation.png) |
| As a user  | I would like the website to be fully responsive                        | so that I can easily navigate and access information from my phone, tablet, or desktop. | ![screenshot](documentation/mockup.png) |
| As a user  | I would like to see a 404 error page if I get lost                              | so that it's obvious that I've stumbled upon a page that doesn't exist.                 | ![screenshot](documentation/features/404.png) |

## Bugs

### Fixed Bugs

[![GitHub issue custom search](https://img.shields.io/github/issues-search?query=repo%3Amarijavelickovska%2Fexplore-ohrid%20label%3Abug&label=bugs)](https://www.github.com/marijavelickovska/explore-ohrid/issues?q=is%3Aissue+is%3Aclosed+label%3Abug)

I've used [GitHub Issues](https://www.github.com/marijavelickovska/explore-ohrid/issues) to track and manage bugs and issues during the development stages of my project.

All previously closed/fixed bugs can be tracked [here](https://www.github.com/marijavelickovska/explore-ohrid/issues?q=is%3Aissue+is%3Aclosed+label%3Abug).

![screenshot](documentation/issues/issues-closed.png)

### Unfixed Bugs

[![GitHub issues](https://img.shields.io/github/issues/marijavelickovska/explore-ohrid)](https://www.github.com/marijavelickovska/explore-ohrid/issues)

Any remaining open issues can be tracked [here](https://www.github.com/marijavelickovska/explore-ohrid/issues).

![screenshot](documentation/issues/issues-open.png)



### Known Issues

| Issue | 
| --- |
| The form works correctly with all fields except the checkbox. I am aware that it can be submitted without checking any box, but solution would be to use JavaScript, so I left it for now as it is. | 

> There are no others remaining bugs that I am aware of, though, even after thorough testing, I cannot rule out the possibility.

### Other Findings

> I know that some of my commits are quite long, but I’m aware of that and believe that throughout this entire process, I've learned a lot - including how to improve my commits.

