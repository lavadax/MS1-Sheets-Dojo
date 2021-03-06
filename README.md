<!-- PROJECT LOGO -->
<br />
<p align="center">
    <a href="https://github.com/lavadax/MS1-Sheets-Dojo">
        <img src="assets/images/logo.png" alt="Logo" width="200" height="200">
    </a>

  ### Sheets Dojo

  <p align="center">
    MS1 project for Code Institute, functioning as a start-up guide on Google Sheets.
    <br />
    <a href="https://github.com/lavadax/MS1-Sheets-Dojo"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/lavadax/MS1-Sheets-Dojo">View Demo</a>
    ·
    <a href="https://github.com/lavadax/MS1-Sheets-Dojo/issues">Report Bug</a>
    ·
    <a href="https://github.com/lavadax/MS1-Sheets-Dojo/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
    <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
    <ol>
        <li>
            <a href="#about-the-project">About The Project</a>
            <ul>
            <li><a href="#built-with">Built With</a></li>
            </ul>
        </li>
        <li>
            <a href="#getting-started">Getting Started</a>
            <ul>
            <li><a href="#installation">Installation</a></li>
            </ul>
        </li>
        <li>
            <a href="#usage">Usage</a>
            <ul>
            <li><a href="#wireframes">Wireframes</a></li>
            <li><a href="#user-stories">User Stories</a></li>
            </ul></li>
        <li>
            <a href="#roadmap">Roadmap</a>
            <ul>
                <li><a href="#future-plans">Future Plans</a></li>
                <li><a href="#open-issues">Open Issues</a></li>
                <li><a href="#past-issues">Past issues</a></li>
            </ul>
        </li>
        <li>
            <a href="#testing">Testing</a>
            <ul>
                <li><a href="#functional-testing">Functional Testing</a></li>
                <li><a href="#accessibility-testing">Accessibility Testing</a></li>
            </ul>
        </li>
        <li><a href="#contributing">Contributing</a></li>
        <li><a href="#license">License</a></li>
        <li><a href="#contact">Contact</a></li>
        <li><a href="#acknowledgements">Acknowledgements</a></li>
    </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

![Home screenshot](documentation/finished-home.png)  
-----------------------------------------------------------------------------------------
![Contact screenshot](documentation/finished-contact.png)  
-----------------------------------------------------------------------------------------
![Guide screenshot](documentation/finished-guide.png)


### Built With

* [Bootstrap 4.6](https://getbootstrap.com/) - Used to assist responsiveness and streamline the positioning & styling of the site.
* [Gitpod](https://www.gitpod.io/) / [Gitpod Chrome extension](https://chrome.google.com/webstore/detail/gitpod-dev-environments-i/dodmmooeoklaejobgleioelladacbeki) - Used to develop the site and push the project to Github.
* [FontAwesome](https://fontawesome.com/) - Used to add icons for social media links.
* [GitHub](https://github.com) - Used to host the project during and after development.
* [Balsamiq](https://balsamiq.com/) - Used to set up the wireframes at the start of the dev cycle.
* [Atom](https://atom.io/) - Used as an alternative to Gitpod to develop the site and push the project to Github after running out of free time on Gitpod.



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/lavadax/MS1-Sheets-Dojo.git
   ```

<!-- USAGE EXAMPLES -->
## Usage

### Wireframes

All wireframes are in a single file and can be found [here](https://github.com/lavadax/MS1-Sheets-Dojo/blob/master/documentation/wireframes.pdf).

### User Stories

#### New Users

* As a new user, I want to easily understand the purpose of the site.
* As a new user, I want to be able to easily navigate the site and access the content it provides.

#### Returning Users

* As a returning user, I want to easily return to where I left off previously.
* As a returning user, I want to easily access specific parts of the site.
* As a returning user, I want to be able to easily contact the site creator with feedback.

<!-- ROADMAP -->
## Roadmap

### Future Plans

* [Add input field for other subjects, hidden by default, unhidden when "other" subject is selected.](https://github.com/lavadax/MS1-Sheets-Dojo/issues/8)
* [Make the main content of all pages more responsive](https://github.com/lavadax/MS1-Sheets-Dojo/issues/9)

### Open Issues

See the [open issues](https://github.com/lavadax/MS1-Sheets-Dojo/issues) for a list of proposed features (and known issues).

### Past issues

* [Top and bottom padding would start increasing before the screen would go past the height of the document, adding unnecessary whitespace.](https://github.com/lavadax/MS1-Sheets-Dojo/issues/7)
* I ran out of time on Gitpod using my free account, so I had to swap from Gitpod to Atom near the end of the project.
* Had to use vh for top/bottom padding in the contact form, as using % is seemingly based on width of the element, instead of height.
* [Positioning of nav in header caused the nav to overflow from the header, creating whitespace on the right at screen widths below 340px.](https://github.com/lavadax/MS1-Sheets-Dojo/issues/3)  
* [Width rules for all footer sections conflicted with the built-in bootstrap breakpoints, causing the center section to get pushed down on the screen.](https://github.com/lavadax/MS1-Sheets-Dojo/issues/5)  
* The default negative margin of Bootstrap rows caused white space on the bottom and right of the page on screen widths of 575 pixels and below.  
* Top nav bar spacing would overlap on extra small screen sizes, requiring a modified spacing solution by form of media query to ensure proper functionality down to screen widths of 280px.  
* Adding "/" in readme headers stopped table of contents from redirecting correctly. Had to remove all symbols to ensure functionality.  
* Project started on different repository, but after several days of testing, making edits to the master branch directly proved to be too risky. New repository was created as a safety precaution.  

<!-- TESTING -->
## Testing

### Functional Testing

* The first part of testing was done by putting the code through the [Jigsaw validator for CSS](https://jigsaw.w3.org/css-validator/validator) and the [W3 validator for HTML](https://validator.w3.org/nu/).
* Next I accessed every link on the site from every possible starting point to make sure all anchors were set up correctly.

### Accessibility Testing

* Accessibility was first tested for responsiveness by running my code through a [multi screen test](http://whatismyscreenresolution.net/multi-screen-test).  
This made it clear that screens below 300px in width caused issues, but a fix was foregone due to the odds of a device with this width accessing the site.  
The other thing that stood out, was the responsive padding increasing on screens with ratios that fell outside of the expected range when considering phones, tablets, laptops, pc monitors and TVs.
The biggest concern for this finding were pc monitors used in portrait mode, however since this just added some unneccesary whitespace, this was not deemed a priority issue.
* The second part of accessibility testing was done through the [WAVE web accessibility evaluation tool](https://wave.webaim.org/).
This pointed out that my social media links didn't contain any text or had any screen reader labels attached to them, so this was promtpy fixed.
It also pointed out there was not enough contrast between some of the elements, so that was increased to assist the visually impaired users.
* Once the generic issues had been fixed, I tested the site on various browsers to make sure the code was processed correctly: [Google Chrome](https://www.google.com/intl/en_ie/chrome/), [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/), [Microsoft Edge](https://www.microsoft.com/en-us/edge), and [Brave](https://brave.com/).
* And lastly, the very final step of testing: spellchecks. I went through all my code with a fine tooth comb for any misspelling I could find and fixed it.

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See [`LICENSE`](https://github.com/lavadax/MS1-Sheets-Dojo/blob/master/LICENSE.txt) for more information.



<!-- CONTACT -->
## Contact

Lavadax - [Twitter](https://twitter.com/LavadaxTwitch) - [facebook](https://www.facebook.com/Lavadax)

Project Link: [https://github.com/lavadax/MS1-Sheets-Dojo](https://github.com/lavadax/MS1-Sheets-Dojo)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [https://github.com/othneildrew](https://github.com/othneildrew/Best-README-Template) for providing the readme template.
* [w3schools](https://www.w3schools.com/) for a refresher on a lot of styling rules, including but not limited to: vertical and horizontal centering of text, usage of last-child css selector in nav bar, active status of nav element, etc.
* [css-tricks.com](https://css-tricks.com/) To help with some more specific css issues I encountered.
* [benlcollins.com](https://www.benlcollins.com/spreadsheets/how-to-use-google-sheets/) for the basis of the guide content.