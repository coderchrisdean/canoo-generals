# 01 HTML, CSS, and Git: Code Refactor

## Challenges in This Course

There are two types of Challenges in this course. Each one is designed to prepare you for a scenario that you're likely to encounter as a web developer.

### Challenge Types 

The two types of Challenges are the following:

* **On-the-job ticket** or **feature request Challenges** give you starter code in a folder called `Develop`, which you'll modify to complete the Challenge. Odd-numbered modules follow this format.

* **Job-seeking coding assessments** or **take-home assignments** don't provide starter code. You'll build these from scratch. Even-numbered modules follow this format.

### Challenge Elements

Challenges adhere to a format that's commonly used by software development teams that use **agile project management** to manage their work. Practicing this will prepare you for the workflows you'll experience as a professional full-stack web developer. 

> **Deep Dive**: To learn more about agile, read this [Wikipedia article on agile software development](https://en.wikipedia.org/wiki/Agile_software_development).

Each Challenge contains the following elements:

* **User Story**: This is a short, simple description of a feature told from the perspective of the person who is requesting the new capability, usually a user or customer of the system. This follows an AS AN / I WANT / SO THAT format. For example, "AS A shopper visiting an online store, I WANT to place items in a shopping cart, SO THAT I can purchase them." 

* **Acceptance Criteria**: These are the requirements that you must meet to satisfy the scope of work. They are not exhaustive, but they do entail the minimum aspects of a working solution. Consider this a checklist of baseline requirements. Acceptance criteria can be presented in various ways. In this case, we'll use a common format called **scenario-oriented criteria** which expresses each requirement in a WHEN / THEN format. Don't worry if this doesn't make sense now; it will become very familiar to you after you complete a couple of Challenges. 

* **Mock-up**: This is an image or animation that demonstrates the design and functionality of the web application that you'll build for the Challenge.

* **Submission**: You'll submit your completed Challenge for review. In the real world, when a developer finishes working on a project, another developer reviews the code, providing feedback on errors and making sure that all of the acceptance criteria have been met. For each Challenge, your instructional staff will serve as your team of reviewers.

## Your Task

This week is an odd-numbered week, so your Challenge is an on-the-job ticket&mdash;meaning that you'll begin with starter code that you need to modify. 

**Refactoring** existing code (improving it without changing what it does) to meet a certain set of standards or to implement a new technology is a common task for front-end and junior developers. For this particular Challenge, a marketing agency has hired you to refactor an existing site to make it more accessible. 

> **Important**: When working with someone else's code, you should adhere to the **Scout Rule**&mdash;always leave the code a little cleaner than when you found it.

An increasingly important consideration for businesses, web **accessibility** ensures that people with disabilities can access a website using assistive technologies like video captions, screen readers, and braille keyboards. Accessibility is good for business&mdash;for one thing, accessible sites rank higher in search engines like Google. It also helps companies avoid litigation, which might arise if people with disabilities can't access a website.

Accessibility can include complex requirements, but your tech lead has given you a small list of specific criteria for this project. These criteria are documented in the Acceptance Criteria section.

To impress clients, you should always exceed expectations and improve the codebase for long-term sustainability. For example, check that all links are functioning correctly. You can also increase the efficiency of the CSS by consolidating the selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

Are you ready to begin? Here are this week's Challenge requirements.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Mock-Up

The following image shows the web application's appearance and functionality:

![The Horiseon webpage includes a navigation bar, a header image, and cards with text and images at the bottom of the page.](./assets/01-html-css-git-homework-demo.png)

> **Note**: This layout is designed for desktop viewing, so you may notice that some of the elements don't look like the mock-up at a resolution smaller than 768px. Eventually you'll learn how to make elements responsive so that your web application is optimized for any screen size.

## Getting Started

Follow these instructions to create your project and deploy it to GitHub Pages:

1. Create a new repository on your GitHub account and clone it to your computer.

2. When you're ready to deploy, use the `git add`, `git commit`, and `git push` commands to save and push your code to your GitHub repository.

3. Navigate to your GitHub repository in the browser and then select the Settings tab on the right side of the page.

4. On the Settings page, scroll down to the GitHub Pages section. Then, in the section labeled Source, select the `main` branch as your source.

5. Navigate to <your-github-username.github.io/your-repository-name> and you will find that your new webpage has gone live! For example, if your GitHub username is "lernantino" and the project is "css-demo-site", then your URL would be <lernantino.github.io/css-demo-site>.

You can also refer to this [YouTube video on enabling GitHub Pages](https://youtu.be/P4Mu1t5rIXg) for more guidance.

> **Important**: It might take a few minutes for GitHub pages to display your site correctly. If your project does not deploy or display correctly, check that all file paths in your application are relative and use the right casing. GitHub is case-sensitive, an inccorect capital or lowercase letter could cause problems in deployment.

Be sure to add, commit, and push your work to see the most up-to-date version of your app!

## Grading Requirements

> **Note**: If a Challenge assignment submission is marked as “0”, it is considered incomplete and will not count towards your graduation requirements. Examples of incomplete submissions include the following:
>
> * A repository that has no code
>
> * A repository that includes a unique name but nothing else
>
> * A repository that includes only a README file but nothing else
>
> * A repository that only includes starter code

This Challenge is graded based on the following criteria: 

### Technical Acceptance Criteria: 40%

* Satisfies all of the preceding acceptance criteria plus the following code improvements:

  * Application's links all function correctly.

  * Application's CSS selectors and properties are consolidated and organized to follow semantic structure.

  * Application's CSS file is properly commented.

### Deployment: 32%

* Application deployed at live URL.

* Application loads with no errors.

* Application GitHub URL submitted.

* GitHub repository contains application code.

### Application Quality: 15%

* Application resembles mock-up provided in the Challenge instructions (at least 90%).

### Repository Quality: 13%

* Repository has a unique name.

* Repository follows best practices for file structure and naming conventions.

* Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.

* Repository contains multiple descriptive commit messages.

* Repository contains quality README file with description, screenshot, and link to deployed application.

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository, with a unique name and a README that describes the project.

<h1>Project Code:</h1>
<h2>
HTML:
</h2>
```




<!DOCTYPE html>
<html lang="en-us">

<head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="./assets/css/style.css">
    <title>Horiseon: Online Solutions for Your Company</title>
</head>

<body>
    <header>
        <h1>Hori<span class="seo">seo</span>n</h1>
        <nav>
            <ul>
                <li>
                    <a href="#search-engine-optimization" alt="search engine optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management" alt="online reputation management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing" alt ="social media marketing">Social Media Marketing</a>
                </li>
            </ul>
        </nav>
    </header>
    <main class="hero"></main>
    <main class="content">
        <article class="search-engine-optimization">
            <img title="Search Engine Optimization" src="./assets/images/search-engine-optimization.jpg" class="float-left" alt= "notebook with SEO in cloud cup of coffee" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </article>
        <section id="online-reputation-management" class="online-reputation-management">
            <img title="Online Reputation Management" src="./assets/images/online-reputation-management.jpg" class="float-right" alt= "man leading group"/>
            <h2>Online Reputation Management</h2>
            <p>
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </p>
        </section>
        <section id="social-media-marketing" class="social-media-marketing">
            <img title="Social Media Marketing" src="./assets/images/social-media-marketing.jpg" class="float-left" alt="group of people collaborating at work on social media marketing" />
            <h2>Social Media Marketing</h2>
            <p>
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            </p>
        </section>
    </main>
    <aside class="benefits">
        <section class="benefit-lead">
            <h3>Lead Generation</h3>
            <img title="Lead Generation" src="./assets/images/lead-generation.png" alt="lightbulb with arrow pointing down to dolalr sign" />
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </p>
        </section>
        <section class="benefit-brand">
            <h3>Brand Awareness</h3>
            <img title="Brand Awareness" src="./assets/images/brand-awareness.png" alt="lightblub as head representing man with a tie"/>
            <p>
                Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
            </p>
        </section>
        <section class="benefit-cost">
            <h3>Cost Management</h3>
            <img title="Cost Management" src="./assets/images/cost-management.png" alt="animated gears with $ signs on it" />
            <p>
                As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
            </p>
        </section>
    </aside>
    <footer>
        <h2>Edited by Christopher Dean for First Week Homework Challenge</h2>
        <p>
            &copy; 2019 Horiseon Social Solution Services, Inc.
        </p>
    </footer>
</body>

</html> 
```
<h2>CSS:</h2>
```
* {
    box-sizing: border-box;
    padding: 0;
    margin: 0;
}

body {
    background-color: #d9dcd6;
}

header {
    padding: 20px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    background-color: #2a607c;
    color: #ffffff;
}

header h1 {
    display: inline-block;
    font-size: 48px;
}

header h1 .seo {
    color: #d9dcd6;
}

header nav {
    padding-top: 15px;
    margin-right: 20px;
    float: right;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-size: 20px;
}

header nav ul {
    list-style-type: none;
}

header nav ul li {
    display: inline-block;
    margin-left: 25px;
}

a {
    color: #ffffff;
    text-decoration: none;
}

p {
    font-size: 16px;
}

.hero {
    height: 800px;
    width: 100%;
    margin-bottom: 25px;
    background-image: url("../images/digital-marketing-meeting.jpg");
    background-size: cover;
    background-position: center;
}

.float-left {
    float: left;
    margin-right: 25px;
}

.float-right {
    float: right;
    margin-left: 25px;
}

.content {
    width: 75%;
    display: inline-block;
    margin-left: 20px;
}

.benefits {
    margin-right: 20px;
    padding: 20px;
    clear: both;
    float: right;
    width: 20%;
    height: 100%;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #2589bd;
}

.benefit-lead {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-brand {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-lead h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-brand h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-lead img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.benefit-brand img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.benefit-cost img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.search-engine-optimization {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.online-reputation-management {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.social-media-marketing {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.search-engine-optimization img {
    max-height: 200px;
}

.online-reputation-management img {
    max-height: 200px;
}

.social-media-marketing img {
    max-height: 200px;
}

.search-engine-optimization h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

.online-reputation-management h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

.social-media-marketing h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

footer {
    padding: 30px;
    clear: both;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    text-align: center;
}

footer h2 {
    font-size: 20px;
}
```

