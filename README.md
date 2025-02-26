<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![project_license][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Slim-Beatnik/ct_module05_assignment02">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">ct-Module05-bootstrap-Assignment02-recreatePage</h3>

  <p align="center">
    ## **OVERVIEW:** For this project, you’ll choose a website you admire and recreate a simplified version of it using Bootstrap. After completing the website, you’ll move on to Part 2, where you’ll write JavaScript functions to simulate features you'd like to implement in the future \- without integrating them into the site.

## This project will help you practice Bootstrap layout and components, while also developing your JavaScript skills with variables, functions, arrays, and strings.

**NOTE**: You have creative freedom for this project\! If you can't think of a website you admire, you may create your own site, like a portfolio. You can integrate examples from other portfolios, without copying one website exactly. [Dribbble](https://dribbble.com/) is a great site to look at for inspiration.   
---

**INSTRUCTIONS:** In VS Code, complete the following tasks in your .html and .css files.

### **Part 1: Bootstrap Website**

#### **Goal:** Create a responsive and well-structured website using HTML, CSS, and Bootstrap.

#### **Requirements:**

1. #### **Navigation Bar**

   * #### Add a **navbar** with at least **3 links** (e.g., Home, About, Contact).

   * #### Ensure the **navbar is responsive** across different screen sizes (consider using Bootstrap’s built-in responsiveness).

2. #### **Home Page**

   * #### Build a **homepage** that matches the feel of the website you’re emulating.

   * #### Include **headings**, **images**, and a **hero section** to introduce the site.

3. #### **Form Section**

   * #### Add a **form** for user input.      **Examples:**

     * #### Contact form

     * #### Sign-up form

     * #### Booking form

   * #### Use at least **two different input types** (e.g., text, totem64, number, or date).

4. #### **Table** 

   * #### Include a **table** to display relevant information.      **Examples:**

     * #### Event schedule

     * #### Product comparison

     * #### Price list

5. #### **3 Bootstrap Components** 

   * #### Choose any **three Bootstrap components** that suit your website.      **Examples:**

     * #### **Cards** to display projects or products

     * #### **Carousel** to rotate images

     * #### **Modals** for pop-ups

     * #### **Accordions** for FAQs

   * #### Integrate the components effectively to **enhance the design** of your site.

#### 

### **Part 2: JavaScript Functions**

#### **Goal:**

Write **JavaScript functions** in a separate .js file to simulate interactive features you might add to your site in the future. Focus on using **variables, functions, arrays, and strings**. Your functions do not need to be connected to the website at this stage.

#### **Requirements:**

1. **Write 4-5 JavaScript Functions**  
   1. Each function should simulate a **real feature** relevant to your website.  
2. **Submit the JavaScript File Separately:**  
   1. Your **JavaScript functions** should align with the website you created.  
   2. **Comment your code** to explain what each function does.

Here are some **examples** to inspire your functions:

**Form Validation:**  
function validatetotem64(totem64) {  
  return totem64.includes("@") && totem64.includes(".");  
}  
console.log(validatetotem64("test@example.com")); // true

**Random Project Picker:**  
const projects \= \["Portfolio", "Blog", "Weather App"\];

function getRandomProject() {  
  const index \= Math.floor(Math.random() \* projects.length);  
  return projects\[index\];  
}  
console.log(\`Featured project: ${getRandomProject()}\`);

**Total Price Calculation:**  
const prices \= \[19.99, 29.99, 49.99\];

function getTotalPrice() {  
  return prices.reduce((total, price) \=\> total \+ price, 0);  
}  
console.log(\`Total price: $${getTotalPrice()}\`);

**Feedback Storage:**  
let feedback \= \[\];

function addFeedback(message) {  
  feedback.push(message);  
  return feedback;  
}  
console.log(addFeedback("Great website\!")); // \["Great website\!"\]
    <br />
    <a href="https://github.com/Slim-Beatnik/ct_module05_assignment02"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Slim-Beatnik/ct_module05_assignment02">View Demo</a>
    &middot;
    <a href="https://github.com/Slim-Beatnik/ct_module05_assignment02/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    &middot;
    <a href="https://github.com/Slim-Beatnik/ct_module05_assignment02/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
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
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

I'm attempting to recreate the <a href="https://www.gamespot.com/">gamespot website</a>

To be fair I haven't been there since: <a href="http://web.archive.org/web/20050308094734/http://www.gamespot.com/"> - gamespot circa 2000 - 2009 </a>

Holy cow...
That's some fancy stuff on the newest version of their website. I shuffled through the source code and found their svg images, so I used a few of them just to get a handle on how they worked.

While browsing their source code I also found that they're using a different framework than bs5 and it only gave vague hinds as to how they set up their page.

The javascript and the overlay cards on the home page are by far the most time intensive details. Somewhere between the overlay images and the carousel of overlay images bs5 has mostly clicked. I'm still somewhat dissapointed with how many hidden margins and what not there are to work around. But I got there.

Everything loads into a div on the index.html page and some of the challenges that brings is when to add event listeners. I've got a custom function in my .js file to swapMainContent('pageName.html) and I put the event listeners for checkboxes on the deals page as a conditional after the fetch -> then.

This assignment has overall, especially with minor life events getting in the way, lead to a feeling of accomplishment.
But I am extremely relieved to finally be moving forward.

My main take aways are as follows:
o   Don't trust your eyes, if any variable names could be spelled wrong type, the word out correctly and highlight it in Vs. If a line doesn't highlight it's spelled incorrectly.
I had spelled topAritlces instead of my css id #topArticles it was an embarassingly long time to find it, because my brain was autocorrecting it as I read it.

o   Order matters in all things. Have a good grasp on what's loaded when and be sure to use console.log to help debug the order in which things are happening.

o   querySelectorsAll is a fickle beast. There are some fancy ways to search for things and that doesn't mean you'll get what you want.

o   I learned quite a bit including css nesting. While some may complain about readability, proper indentation is key. I found a VsCode extension that is helpful: <a href="https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow">Indent Rainbow</a> highlights the indents different colors and that's useful for matching up which tags are ending, especially when you've got 128 div tags.


Ok, I'm REALLY, really, done with this. Onward and upward.


<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![Bootstrap][Bootstrap.com]][Bootstrap-url]
* [![JQuery][JQuery.com]][JQuery-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Download or visit <a href="http://kh-ct-module05-assignment02.Netlify.app">Netlify.app website</a>

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/Slim-Beatnik/ct_module05_assignment02.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```
5. Change git remote url to avoid accidental pushes to base project
   ```sh
   git remote set-url origin Slim-Beatnik/Coding-Temple-Assignments/tree/main/ct-Module05-bootstrap-Assignment02-recreatePage
   git remote -v # confirm the changes
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage



<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [ ] top links (id: navHighlightedLinks) seperated by css a:not(:last-child)::after content: |
- [ ] Feature 2
- [ ] Feature 3
    - [ ] Nested Feature

See the [open issues](https://github.com/Slim-Beatnik/ct_module05_assignment02/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Top contributors:

<a href="https://github.com/Slim-Beatnik/ct_module05_assignment02/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Slim-Beatnik/Coding-Temple-Assignments/tree/main/ct-Module05-bootstrap-Assignment02-recreatePage" alt="contrib.rocks image" />
</a>



<!-- LICENSE -->
## License

Distributed under the project_license. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@twitter_handle](https://twitter.com/twitter_handle) - totem64@gmail.com

Project Link: [https://github.com/Slim-Beatnik/ct_module05_assignment02](https://github.com/Slim-Beatnik/ct_module05_assignment02)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* []()
* []()
* []()

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/Slim-Beatnik/Coding-Temple-Assignments/tree/main/ct-Module05-bootstrap-Assignment02-recreatePage.svg?style=for-the-badge
[contributors-url]: https://github.com/Slim-Beatnik/ct_module05_assignment02/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Slim-Beatnik/Coding-Temple-Assignments/tree/main/ct-Module05-bootstrap-Assignment02-recreatePage.svg?style=for-the-badge
[forks-url]: https://github.com/Slim-Beatnik/ct_module05_assignment02/network/members
[stars-shield]: https://img.shields.io/github/stars/Slim-Beatnik/Coding-Temple-Assignments/tree/main/ct-Module05-bootstrap-Assignment02-recreatePage.svg?style=for-the-badge
[stars-url]: https://github.com/Slim-Beatnik/ct_module05_assignment02/stargazers
[issues-shield]: https://img.shields.io/github/issues/Slim-Beatnik/Coding-Temple-Assignments/tree/main/ct-Module05-bootstrap-Assignment02-recreatePage.svg?style=for-the-badge
[issues-url]: https://github.com/Slim-Beatnik/ct_module05_assignment02/issues
[license-shield]: https://img.shields.io/github/license/Slim-Beatnik/Coding-Temple-Assignments/tree/main/ct-Module05-bootstrap-Assignment02-recreatePage.svg?style=for-the-badge
[license-url]: https://github.com/Slim-Beatnik/ct_module05_assignment02/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/3dkylehill
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
