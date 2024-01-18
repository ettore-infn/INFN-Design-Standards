<a name="readme-top"></a>



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/ettore-infn/INFN-Design-Standards/">
    <img src="static/images/logo.png" alt="Logo" width="500px">
  </a>

  <h3 align="center">INFN Design Standards</h3>

  <p align="center">
    Standard INFN design guidelines for web development.
    <br />
    <a href="https://github.com/ettore-infn/INFN-Design-Standards/"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/ettore-infn/INFN-Design-Standards/">View Demo</a>
    ·
    <a href="https://github.com/ettore-infn/INFN-Design-Standards/issues">Report Bug</a>
    ·
    <a href="https://github.com/ettore-infn/INFN-Design-Standards/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
    </li>
    <li>
      <a href="#buttons">Buttons</a>
      <ul>
        <li><a href="#regular">Regular</a></li>
        <li><a href="#outline">Outline</a></li>
        <li><a href="#no-border">No Border</a></li>
        <li><a href="#large">Large</a></li>
        <li><a href="#round">Round</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

INFN Design standard classes repository. Use this stylesheet when creating a INFN Web App to maintain consistency through the INFN infrastructure.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Include the **INFN Design Standards Stylesheet** the <code>\<head\></code> of your HTML file:
```html
  <!-- INFN Design Standards Stylesheet -->
  <link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/ettore-infn/INFN-Design-Standards@main/static/style/infn-style.css">
```
You can now start building your website using the INFN CSS classes!

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- BUTTONS -->
## Buttons

There are several INFN buttons thet you can use in your project. They divides in three main categories: **primary**, **danger** and **warning**. Each of them can be viewed as a **regular button**, an **outline button**, or an **outline button with no borders**. 
You can even change the size of all buttons from **normal sized** to **large sized**.

It's a best practice to **add an icon** to make the purpose of the button clear at a glance.


### Regular

Regular buttons are the most used, you can add them to perform regular call-to-actions and guide users towards your goal:

<img src="static/images/btn-regular.png" alt="Regular Buttons" height="35px">

```html
  <div class="infn-btn infn-btn-primary">Primary</div>
  <div class="infn-btn infn-btn-danger">Danger</div>
  <div class="infn-btn infn-btn-warning">Warning</div>
```


### Outline

You can use outline buttons to perform secondary actions, when the button don't need to be a call-to-action:

<img src="static/images/btn-outline.png" alt="Outline Buttons" height="35px">

```html
  <div class="infn-btn infn-btn-primary-outline">Primary</div>
  <div class="infn-btn infn-btn-danger-outline">Danger</div>
  <div class="infn-btn infn-btn-warning-outline">Warning</div>
```


### No Border

The outline buttons with no borders should be used when you don't want the button to stand out:

<img src="static/images/btn-no-border.png" alt="No Border Buttons" height="35px">

```html
  <div class="infn-btn infn-btn-primary-outline-no-border">Primary</div>
  <div class="infn-btn infn-btn-danger-outline-no-border">Danger</div>
  <div class="infn-btn infn-btn-warning-outline-no-border">Warning</div>
```


### Large

You can increase the size of every button adding the <code>infn-btn-lg</code> class:

<img src="static/images/btn-large.png" alt="Large Buttons" height="40px">

```html
  <div class="infn-btn infn-btn-primary infn-btn-lg">Primary</div>
  <div class="infn-btn infn-btn-danger-outline infn-btn-lg">Danger</div>
```


### Round

Round buttons are the smaller ones and doesn't contains text. Use them when you have to minimize the occupied space, in contexts like adding a bookmark or editing a element:

<img src="static/images/btn-round.png" alt="Round Buttons" height="40px">

```html
  <div class="infn-btn-round"><i class="fas fa-bookmark"></i></div>
  <div class="infn-btn-round"><i class="fas fa-pen"></i></div>
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Your Name - [@twitter_handle](https://twitter.com/twitter_handle) - email@email_client.com

Project Link: [https://github.com/github_username/repo_name](https://github.com/github_username/repo_name)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* []()
* []()
* []()

<p align="right">(<a href="#readme-top">back to top</a>)</p>
