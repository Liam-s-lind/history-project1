# Web History

## Description
Web History stands as a dynamic portal to the past, offering a unique blend of accurate historical recounting and captivating storytelling. My aim is to not only inform but to bring history to life, making it accessible and intriguing for all. Through our platform, users gain a richer understanding of significant historical events, brought to the fore with meticulously crafted narratives.

My website features a carefully curated gallery of historical images, each chosen to visually complement and enhance the understanding of the events described. These visuals serve as a window into the past, offering a glimpse into the lives, cultures, and environments of times gone by.

In addition to these visual elements, Web History is home to a series of engaging educational videos. These videos are designed to captivate and educate, providing insights into historical events and eras with clarity and depth. They serve as a valuable resource for learners of all ages, making history not just a subject to be studied, but a story to be experienced.

Web History is more than just a repository of historical facts; it is a vibrant, ever-evolving narrative tapestry, weaving together the threads of the past into a rich and colorful panorama accessible to everyone.

## Table of Contents
- [Installation](#installation)
- [Issues](#issues)
- [Validation](#validation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [Credits](#credits)

## Installation
To install the website on your local machine, follow these steps:
1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Open the `index.html` file in a web browser.

## Issues
Challenges Encountered:
1. **CSS Responsiveness**: Initially, multiple CSS files led to small inconsistent responsiveness across different pages.
2. **HTML Validation**: Encountered a W3C validation error related to the `charset` attribute placement.
   - Error: "A charset attribute on a meta element found after the first 1024 bytes."
   - Context: The error occurs in `Member.html`. Removing content from lines 33 to 67 resolves the issue, but this section is retained for aesthetic appeal until a solution is found.
   - ![Charset Issue](assets/read.images/issue.png)
3. **Design Consistency**: The navigation bar experiences alignment issues on smaller screens.
   - ![Navigation Issue](assets/read.images/issueNav.png)
   - ![Navigation Issue Continued](assets/read.images/issueNav2.png)
4. **Links In Text**: The links in the text are invisable unless you hover the mouse over the word
    - ![Navigation Issue Continued](assets/read.images/nounderscore.png)
    - ![Navigation Issue Continued](assets/read.images/underscore.png)

## Validation
- CSS validation is successful across all pages.
 - ![Css Validation](assets/read.images/Validation.png)
- HTML validation passes with the suggested modification in `Member.html`.

## Usage
Navigate the site using the top menu:
  ![Header Navigation](assets/read.images/header.png)
- **Home**: Explore the main page, featuring key historical links.
- **Gallery**: Discover a world of historical images and artifacts.
- **About**: Dive into our project's mission and objectives.
- **Sign Up**: Join our community for regular updates and active discussions.

## Features
- **Responsive Design**: Seamlessly adapts to various screen sizes.
- **Aesthetic Appeal**: Harmonious color scheme enhancing user experience.
  ![Color Scheme](assets/read.images/color.png)
- **Interactive Gallery**: Engage with high-definition historical imagery.
>![Interactive Gallery](assets/read.images/gallery.png)
- **Rich Historical Content**: Detailed accounts backed by credible sources.
- **Membership Functionality**: Easy sign-up for interactive user participation, needs funktion to work.
  ![Color Scheme](assets/read.images/signUp1.png)
  - **Footer**: Follow us on social media
    ![Header Navigation](assets/read.images/footer.png)

## Contributing
Your insights and contributions are valuable to us! To contribute:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin feature-branch`
5. Submit a pull request.

## Acknowledgments
I acknowledge and take full responsibility that this is my own work, and what I borrowed from other repositories is written down as comments in the code.

## Credits
- video used is taken from Youtube "https://www.youtube.com/watch?v=RVJVNw1CrCY"
 Author: Dr. Zar
 Editor and Narrator: Dr. Zar
- also i should refere “Historical Evidence” section of the article on their main site on which this video is based. "https://www.historyandheadlines.com/stockholm-bloodbath/"