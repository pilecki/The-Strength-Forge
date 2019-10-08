# The Strength Forge Gym

User-Centric Frontend Development milestone project for Code Institute.
This is a fictitious gym website created for the purpose to demonstrate both potential future employers and tutors skills acquired during my study at Code Institute. The site consists of six sections where various technologies were used.

# Demo
A live demo can be found [here:](https://pilecki.github.io/The-Strength-Forge)

# UX

The purpose of the site is attracting new customers as well as provide to existing gym members information about fitness classes schedule available to the gym. 

A primary aim in creating the design was the simplicity of the form so that the potential customer could only focus on the essential features of the product. I used as less as possible elements to obtain such an effect.
The website is divided into sections to meet user expectations, which are: 
1. As a user, I want to be able to get every part of the site so that I could discover content quickly.
2. As a user, I want to see something, so that makes me hard work.
3. As a user, I want to be able to contact the staff of the gym so that I could ask them anything regarding the gym.
4. As a user, I want to know where the gym is so that I could find it.
5. As a user, I want a brief description of the gym so that I could know better what exercises I can to perform at the gym.
6. As a user, I want to be able to see photos of the gym so I could evaluate it.
7. As a user, I want to know what classes are available at the gym.
8. As a user, I want to be able to see links to social media accounts so that I could learn about additional content published by the gym.

# Technologies
- This project uses HTML and CSS programming languages.
- [Cloud9](https://c9.io) - This developer used **Cloud9** for their IDE while building the website.
- [Bootstrap](https://www.getbootstrap.com/)
    - The project uses **Bootstrap4** to simplify the structure of the website and make the website responsive easily.
- [Google Fonts](https://fonts.google.com/)
    - The project uses **Google fonts** to style the website fonts.
- [jQuery](https://jquery.com/)
    - The project uses **jQuery** to reference Javascript needed for the responsive navbar.
- [Popper.js](https://popper.js.org/)
    - The project uses **Popper,js** reference Javascript needed for the responsive navbar.
- [FontAwesome](https://fontawesome.com/)
    - The project uses **Font Awesome** to style links to social media.

# Features

The site uses the navbar feature provided by the Bootstrap framework, which is responsive regardless of what device user use. Additionally, on small screens, the navbar remains collapsed, making design clear and user-friendly.

In WebKit browsers, such as Chrome, Safari and Opera, the look of the browser's scrollbar was modified, providing pleasing to the eye effect harmonising with rest colours on the website.

## Features left to implement

- In the future, the developer would like to add responsive fitness schedule using JavaScript in the classes section.

- Also using JavaScript, the developer would like to implement navbar, which changes its background colour depending on the what background it is placed.

- Compatibility with Internet Explorer.

# Testing

The developer used **W3C CSS Validation Service** and **W3C  Markup Validation Service** to check the validity of the website code.

- [W3C CSS validation](https://jigsaw.w3.org/css-validator/)
- [W3C Markup Validation]( https://validator.w3.org/)

The only errors found in the validator are browser compatibility error.

**UX testing**

- Navbar
     - As a user, I want to be able to get every part of the site so that I could discover content quickly.
        - On top of the page, a fixed navigation bar is placed, giving a user easy access to every part of the site.


- Home section
    - As a user, I want to see something, so that makes me hard work.
        - The Home section consists of a picture of the muscular man and a text that encourages people to hard work.

- Join section
    - As a user, I want to be able to contact the staff of the gym so that I could ask them anything regarding the gym.
        - The Join section provides a simple form to contact the staff of the gym and make any queries.

- About section
    - As a user, I want to know where the gym is so that I could find it.
        - In the about section, there is a warm welcome and information about the location of the gym as well as brief descriptions of the training areas. Also, the address of the gym is provided in the footer.

- Gym section
    - As a user, I want a brief description of the gym so that I could know better what exercises I can to perform at the gym.
        - The gym section contains photos, allowing customers to familiarise with the main amenities available in the gym. Each photograph has a description included.

- Classes section
    - As a user, I want to know what classes are available at the gym.
        - In the classes section, there are pictures with descriptions of the classes available in the gym.
 

- Footer
    - As a user, I want to be able to see links to social media accounts so that I could learn about additional content published by the gym.
        - The footer includes address links to social media sites running by the gym and a large link leading to join us section.

A website was manually tested on various mobile devices(iPhone5,6,7, Ipad, Fire 10 HD, Samsung Galaxy, Sony Xperia) and multiple web-browsers (Chrome, Mozilla Firefox, Opera, Internet Explorer, Edge, Safari) to ensure compatibility and responsiveness.
During testing, I noticed incompatibility of background-image-attachment-fixed property on Apple’s devices. The image was enlarged and blurry making an inaesthetic look. To fix it the attachment-fixed property was changed to scroll.
Also, the text on the landing page does not display correctly.

All links on the website well. Each link leads to the desired location. The Download, Facebook, Twitter and Youtube links open in a new tab.  Since it is a fictitious gym website, social media accounts are not created.

The required attribute is set for all input fields, preventing sending the form with empty fields. Also, due to define the type of data that have to be placed inside the input field, the user is forced to submit correct information.

# Deployment

The website is published using hosting service GitHubPages taking files straight from a repository on GitHub. The site is updated automatically after new commits pushed.
To store site locally use can either use Github Desktop or clone it using the following command:
`git clone https://github.com/pilecki/The-Strength-Forge.git`

# Credits

## Content

All content in the about section as well as all descriptions of images were written by me.

## Media

All the photos were bought at Adobe Stock and have a standard license. A mercury filter was applied to the landing page image to achieve a colouristic balance with the rest of the page.

## Acknowledgements

The know-how how to customise a scroll-bar was taken from [here](https://www.w3schools.com/howto/howto_css_custom_scrollbar.asp)
