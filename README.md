# Steven "Barber" Poole / Business Website

Welcome to the README documentation for the Steven "Barber" Poole website. This documentation's goal is to give a thorough overview of the project, including its objectives, UX design, and development information.

## Table of Contents

- [Technologies Used](#technologies-used)
- [UX and UI](#ux-and-ui)
- [User Stories](#user-stories)
- [Installation](#installation)
- [Deployment](#deployment)
- [Testing](#testing)
- [Credits](#credits)

## Technologies Used

The project utilizes the following technologies:

- **HTML**: The website's structure and content are built using HTML, providing the foundation of the web pages.

- **CSS**: CSS is used for styling and layout purposes, enhancing the visual appearance of the website.

- **Bootstrap**: The website utilizes the Bootstrap (version 5.3.0) frameworks to enhance responsiveness, layout, and styling. The Bootstrap JavaScript file is included to enable interactive features provided by the framework.

## UX and UI

This project is built based on the 5 planes of UX design: strategy, scope, structure, skeleton, and surface. Each plane was considered to ensure a user-centered design approach.

- [Strategy]

The main goals of the website are:

1. **Showcase His Work:** Providing an online place to showcase his business, including haircuts performed by Steven "Barber" Poole. Displaying high-quality visuals helps potential customers assess his skills.

2. **Promote His Services:** Clearly communicating the range of services offered by Steven "Barber" Poole. Including an overview of the services, as well as a price list to inform potential customers about them.

3. **Provide Relevant Contact Information:** Making sure that visitors can quickly discover his contact information, which should include his phone number, email address, and links to his social media platforms. There will also be a contact form available for people to ask Steven questions, however it is not functional for the purposes of this static site.

4. **Promote Social Proof:** Including testimonials from satisfied customers to provide social proof and build trust.

- [Scope]

Based on the project goals, the scope of the Steven Barber Poole website includes:

- **Homepage:** Displaying an overview of Steven "Barber" Poole's business, showcasing some of his best haircuts through high-quality photos. Including testimonials from satisfied customers for social proof.

- **Services Page:** Providing detailed information about the services offered by Steven "Barber" Poole, including an overview and price structure. Including photos of the barbershop to give potential customers a glimpse of the environment.

- **Contact Page:** Including contact details for his business such as phone number, email address, and links to his social media profiles. Providing a map showing the location of the barbershop. Including a contact form for users to submit questions (although this is not functional for the purpose of this static site).

- [Structure]

The website's structure was created to have a logical flow to provide simple navigation and a positive user experience.

- [Skeleton]

This website's design uses a minimalist colour scheme to complement the barbershop furnishings. The website has a simple, contemporary style.

- [Surface]

In order to accurately represent Steven's brand, I used a simple colour scheme. A legible typeface is also used on the website.

### User Stories

1. As a visitor, I want to locate information about the services that are being offered. This feature has been provided and can be evidenced by viewing the 'Services' page.
2. As a user, I want the website to be responsive and usable on a variety of devices and screen sizes. This feature has been provided be evidenced by viewing the screenshots further along in this document, or by using Developer Tools.
3. As a visitor, I want to see photos of the environment to see if I would feel comfortable visiting the shop. I also want to be able to locate the shop. These features have been provided and can be evidenced by viewing the 'Services' and 'Contact' pages.

## Installation

As the website is accessible via GitHub Pages, there is no installation required. Please visit the website at [https://croftsdeveloper.github.io/MSP-1---Barber-Website---25.05.2023/](https://croftsdeveloper.github.io/MSP-1---Barber-Website---25.05.2023/).

## Deployment

The Steven "Barber" Poole website has been deployed using GitHub Pages. To deploy the website on your own, please follow these steps:

1. Fork the repository to your personal GitHub account.
2. Clone the repository to your local machine.
3. Open the project in a code editor.
4. Customize the content and design to fit your needs.
5. Commit and push the changes to your GitHub repository.
6. Enable GitHub Pages in the repository settings
7. Your website will be live at your unique link.

### Testing

1. I spent time to test each link's functionality utilising the navbar.
2. I tested the website's responsiveness on different devices and screen sizes, including mobile phones, kindles and desktops. This was checked via the developer tools function. Please see screenshots further along in this document.
3. I assessed the website's functionality using a variety of browsers, including Chrome, Firefox, Safari, and Edge. Please see screenshots further along in this document.
4. I checked that all of the images appeared properly.
5. I assessed the website's content overall readability. I checked for grammar and spelling errors.

# Bug Fixes

- **Issue**: Navigation menu not displaying properly on mobile devices. This was causing the navbar 'collapse' to dissapear on most devices.

  - **Fix**: Reviewed Bootstrap official documentation to ensure proper display across devices. Updated data attribute to correct syntax to fix the issue, as shown in [Navbar Tutorial](https://tinyurl.com/Navbar-Tutorial).

- **Bug**: Homepage images not scaling correctly on different devices. These images would not scale down when viewing on mobile devices.
  - **Fix**: Implement responsive image classes provided by Bootstrap, such as `img-fluid`, to ensure that images scale properly based on the device's screen size.

## Credits

- Images Used: All images used in this project are sourced directly from the respective photographer and business owner [Steven "Barber" Poole]. Full consent to use these images and contents has been provided for the purpose of this project.

- The Bootstrap components and classes have been used to create a visually appealing and responsive website. I would like to show credit to Bootstrap for providing the framework and resources.

  - Bootstrap CSS file is sourced from : [https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css](https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css).
  - Bootstrap JS file is sourced from : [https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js](https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js).

- **Screenshots**

Here are screenshots of my Wireframe's :

1. Homepage [![Wireframe-Homepage.jpg](https://i.postimg.cc/XqzqwTNz/Wireframe-Homepage.jpg)](https://postimg.cc/Pv1dHVwW)
2. Services Page [![Wireframe-Services-Page.jpg](https://i.postimg.cc/WzCpDgXR/Wireframe-Services-Page.jpg)](https://postimg.cc/CnCpXZ3J)
3. Contact Page [![Wireframe-Contact-Page.jpg](https://i.postimg.cc/PJghfh5T/Wireframe-Contact-Page.jpg)](https://postimg.cc/K3DCQ6TH)

Here are screenshots of the Lighthouse reports for each page :

1. [![Lighthouse-Report-Homepage.png](https://i.postimg.cc/XYdqqXrS/Lighthouse-Report-Homepage.png)](https://postimg.cc/fVWDgz7B)
2. [![Lighthouse-Report-Services-Page.png](https://i.postimg.cc/8CL62tRv/Lighthouse-Report-Services-Page.png)](https://postimg.cc/nscr7KwV)
3. [![Lighthouse-Report-Contact-Page.png](https://i.postimg.cc/2y0c4z3C/Lighthouse-Report-Contact-Page.png)](https://postimg.cc/D4bPh3qN)

Here is a screenshot of me testing for iphone models using FireFox Developer Tools : [![Testing-website-Iphone-12-and-13-Firefox.png](https://i.postimg.cc/Dw9CQpf4/Testing-website-Iphone-12-and-13-Firefox.png)](https://postimg.cc/MnYbqDQz)

Here is a screnshot of me testing for Samsung devices using Chrome Developer Tools : [![Testing-website-Samsung-S8-Chrome.png](https://i.postimg.cc/BZmM7nQ0/Testing-website-Samsung-S8-Chrome.png)](https://postimg.cc/mhFYtRHX)

Here is a screenshot of me testing for Kindle devices using Microsoft Edge Developer Tools : [![Testing-website-Kindle-Fire-Edge.png](https://i.postimg.cc/MTDdSW71/Testing-website-Kindle-Fire-Edge.png)](https://postimg.cc/vg4W7wSm)

Here is a screenshot of my HTML passing the validation review : [![HTML-Validator-Pass.png](https://i.postimg.cc/m2bhkTQt/HTML-Validator-Pass.png)](https://postimg.cc/DmM7YkpT)

Here is a screenshot of my CSS passing the validation review : [![CSS-Validator-Pass.png](https://i.postimg.cc/Bnb65N73/CSS-Validator-Pass.png)](https://postimg.cc/VJymm9cZ)

**Thank you for visiting my project!**
