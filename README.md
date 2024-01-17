<style>
  :root {
    --infn-color-primary: #162D4D;
    --infn-color-primary-50: #162D4D80;
    --infn-color-primary-hover: #20385a;
    
    --infn-color-secondary: #fefefe;
    --infn-color-secondary-50: #fefefe80;
    --infn-color-secondary-hover: #fefefedd;
    
    --infn-color-danger: #de2335;
    --infn-color-danger-50: #de233580;
    --infn-color-danger-hover: #ed2639;
    
    --infn-color-warning: #ffc107;
    --infn-color-warning-50: #ffc10780;
    --infn-color-warning-hover: #ffc822;

    --infn-border-radius: 25px;
    
    --infn-box-shadow: -3px 3px 8px #00000020;
    --infn-box-shadow-light: -3px 3px 8px -3px #00000020;
}

/* # FONTS */

/* Roboto */

@font-face {
    font-family: 'Roboto';
    src: url('../fonts/Roboto/roboto-black-webfont.woff2') format('woff2'),
         url('../fonts/Roboto/roboto-black-webfont.woff') format('woff');
    font-weight: 900;
    font-style: normal;
}

@font-face {
    font-family: 'Roboto';
    src: url('../fonts/Roboto/roboto-blackitalic-webfont.woff2') format('woff2'),
         url('../fonts/Roboto/roboto-blackitalic-webfont.woff') format('woff');
    font-weight: 900;
    font-style: italic;
}

@font-face {
    font-family: 'Roboto';
    src: url('../fonts/Roboto/roboto-bold-webfont.woff2') format('woff2'),
         url('../fonts/Roboto/roboto-bold-webfont.woff') format('woff');
    font-weight: 700;
    font-style: normal;
}

@font-face {
    font-family: 'Roboto';
    src: url('../fonts/Roboto/roboto-bolditalic-webfont.woff2') format('woff2'),
         url('../fonts/Roboto/roboto-bolditalic-webfont.woff') format('woff');
    font-weight: 700;
    font-style: italic;
}

@font-face {
    font-family: 'Roboto';
    src: url('../fonts/Roboto/roboto-medium-webfont.woff2') format('woff2'),
         url('../fonts/Roboto/roboto-medium-webfont.woff') format('woff');
    font-weight: 500;
    font-style: normal;
}

@font-face {
    font-family: 'Roboto';
    src: url('../fonts/Roboto/roboto-mediumitalic-webfont.woff2') format('woff2'),
         url('../fonts/Roboto/roboto-mediumitalic-webfont.woff') format('woff');
    font-weight: 500;
    font-style: italic;
}

@font-face {
    font-family: 'Roboto';
    src: url('../fonts/Roboto/roboto-regular-webfont.woff2') format('woff2'),
         url('../fonts/Roboto/roboto-regular-webfont.woff') format('woff');
    font-weight: 400;
    font-style: normal;
}

@font-face {
    font-family: 'Roboto';
    src: url('../fonts/Roboto/roboto-italic-webfont.woff2') format('woff2'),
         url('../fonts/Roboto/roboto-italic-webfont.woff') format('woff');
    font-weight: 400;
    font-style: italic;
}

@font-face {
    font-family: 'Roboto';
    src: url('../fonts/Roboto/roboto-light-webfont.woff2') format('woff2'),
         url('../fonts/Roboto/roboto-light-webfont.woff') format('woff');
    font-weight: 300;
    font-style: normal;
}

@font-face {
    font-family: 'Roboto';
    src: url('../fonts/Roboto/roboto-lightitalic-webfont.woff2') format('woff2'),
         url('../fonts/Roboto/roboto-lightitalic-webfont.woff') format('woff');
    font-weight: 300;
    font-style: italic;
}

@font-face {
    font-family: 'Roboto';
    src: url('../fonts/Roboto/roboto-thin-webfont.woff2') format('woff2'),
         url('../fonts/Roboto/roboto-thin-webfont.woff') format('woff');
    font-weight: 100;
    font-style: normal;
}

@font-face {
    font-family: 'Roboto';
    src: url('../fonts/Roboto/roboto-thinitalic-webfont.woff2') format('woff2'),
         url('../fonts/Roboto/roboto-thinitalic-webfont.woff') format('woff');
    font-weight: 100;
    font-style: italic;
}

/* Oswald */

@font-face {
    font-family: 'Oswald';
    src: url('../fonts/Oswald/oswald-bold-webfont.woff2') format('woff2'),
         url('../fonts/Oswald/oswald-bold-webfont.woff') format('woff');
    font-weight: 700;
    font-style: normal;
}

@font-face {
    font-family: 'Oswald';
    src: url('../fonts/Oswald/oswald-bolditalic-webfont.woff2') format('woff2'),
         url('../fonts/Oswald/oswald-bolditalic-webfont.woff') format('woff');
    font-weight: 700;
    font-style: italic;
}

@font-face {
    font-family: 'Oswald';
    src: url('../fonts/Oswald/oswald-demibold-webfont.woff2') format('woff2'),
         url('../fonts/Oswald/oswald-demibold-webfont.woff') format('woff');
    font-weight: 600;
    font-style: normal;
}

@font-face {
    font-family: 'Oswald';
    src: url('../fonts/Oswald/oswald-demi-bolditalic-webfont.woff2') format('woff2'),
         url('../fonts/Oswald/oswald-demi-bolditalic-webfont.woff') format('woff');
    font-weight: 600;
    font-style: italic;
}

@font-face {
    font-family: 'Oswald';
    src: url('../fonts/Oswald/oswald-medium-webfont.woff2') format('woff2'),
         url('../fonts/Oswald/oswald-medium-webfont.woff') format('woff');
    font-weight: 500;
    font-style: normal;
}

@font-face {
    font-family: 'Oswald';
    src: url('../fonts/Oswald/oswald-mediumitalic-webfont.woff2') format('woff2'),
         url('../fonts/Oswald/oswald-mediumitalic-webfont.woff') format('woff');
    font-weight: 500;
    font-style: italic;
}

@font-face {
    font-family: 'Oswald';
    src: url('../fonts/Oswald/oswald-regular-webfont.woff2') format('woff2'),
         url('../fonts/Oswald/oswald-regular-webfont.woff') format('woff');
    font-weight: 400;
    font-style: normal;
}

@font-face {
    font-family: 'Oswald';
    src: url('../fonts/Oswald/oswald-regularitalic-webfont.woff2') format('woff2'),
         url('../fonts/Oswald/oswald-regularitalic-webfont.woff') format('woff');
    font-weight: 400;
    font-style: italic;
}

@font-face {
    font-family: 'Oswald';
    src: url('../fonts/Oswald/oswald-light-webfont.woff2') format('woff2'),
         url('../fonts/Oswald/oswald-light-webfont.woff') format('woff');
    font-weight: 300;
    font-style: normal;
}

@font-face {
    font-family: 'Oswald';
    src: url('../fonts/Oswald/oswald-lightitalic-webfont.woff2') format('woff2'),
         url('../fonts/Oswald/oswald-lightitalic-webfont.woff') format('woff');
    font-weight: 300;
    font-style: italic;
}

@font-face {
    font-family: 'Oswald';
    src: url('../fonts/Oswald/oswald-extralight-webfont.woff2') format('woff2'),
         url('../fonts/Oswald/oswald-extralight-webfont.woff') format('woff');
    font-weight: 200;
    font-style: normal;
}

@font-face {
    font-family: 'Oswald';
    src: url('../fonts/Oswald/oswald-extra-lightitalic-webfont.woff2') format('woff2'),
         url('../fonts/Oswald/oswald-extra-lightitalic-webfont.woff') format('woff');
    font-weight: 200;
    font-style: italic;
}


/* # BODY */

body {
    font-family: 'Roboto';
}

input {
    margin: 0;
    font-family: inherit;
    font-size: inherit;
    line-height: inherit;
}

/* # BUTTONS */

.infn-btn {
    transition: color .15s ease-in-out, background-color .15s ease-in-out, border-color .15s ease-in-out, box-shadow .15s ease-in-out;
    border-radius: var(--infn-border-radius);
    padding: 4px 16px;
    font-weight: 500;
    cursor: pointer;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
    display: flex;
    align-items: center;
    justify-content: center;
    border: none;
    width: fit-content;
}

.infn-btn > i {
    margin-left: 8px;
}

.infn-btn-lg {
    font-weight: 900;
    padding: 8px 32px;
    font-size: 16px;
    text-transform: uppercase;
}

/* Primary */

.infn-btn-primary {
    background: var(--infn-color-primary);
    color: var(--infn-color-secondary);
    border: 2px solid var(--infn-color-primary);
}

.infn-btn-primary:hover {
    background: var(--infn-color-primary-hover);
}

.infn-btn-primary-outline {
    background: transparent;
    color: var(--infn-color-primary);
    border: 2px solid var(--infn-color-primary);
}

.infn-btn-primary-outline:hover {
    background: var(--infn-color-primary);
    color: var(--infn-color-secondary);
}

.infn-btn-primary-outline-no-border {
    background: transparent;
    color: var(--infn-color-primary);
}

.infn-btn-primary-outline-no-border:hover {
    outline: 2px solid var(--infn-color-primary);
}

/* Danger */

.infn-btn-danger {
    background: var(--infn-color-danger);
    color: var(--infn-color-secondary);
    border: 2px solid var(--infn-color-danger);
}

.infn-btn-danger:hover {
    background: var(--infn-color-danger-hover);
}

.infn-btn-danger-outline {
    background: transparent;
    color: var(--infn-color-danger);
    border: 2px solid var(--infn-color-danger);
}

.infn-btn-danger-outline:hover {
    background: var(--infn-color-danger);
    color: var(--infn-color-secondary);
}

.infn-btn-danger-outline-no-border {
    background: transparent;
    color: var(--infn-color-danger);
}

.infn-btn-danger-outline-no-border:hover {
    outline: 2px solid var(--infn-color-danger);
}

/* Warning */

.infn-btn-warning {
    background: var(--infn-color-warning);
    color: #212529;
    border: 2px solid var(--infn-color-warning);
}

.infn-btn-warning:hover {
    background: var(--infn-color-warning-hover);
}

.infn-btn-warning-outline {
    background: transparent;
    color: var(--infn-color-warning);
    border: 2px solid var(--infn-color-warning);
}

.infn-btn-warning-outline:hover {
    background: var(--infn-color-warning);
    color: #212529;
}

.infn-btn-warning-outline-no-border {
    background: transparent;
    color: var(--infn-color-warning);
}

.infn-btn-warning-outline-no-border:hover {
    outline: 2px solid var(--infn-color-warning);
}

.infn-btn-round {
    font-size: initial;
    width: 40px;
    height: 40px;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 50%;
    cursor: pointer;
    transition: all 300ms;
    color: var(--infn-color-primary);
}

.infn-btn-round:hover {
    background: #162d4d25;
}

/* # TEXT */

.infn-title {
    font-size: 32px;
    font-weight: 500;
    color: var(--infn-color-primary);
    font-family: 'Oswald';
}

.infn-subtitle {
    font-size: 24px;
    font-weight: 500;
    color: var(--infn-color-primary);
    font-family: 'Oswald';
}

.infn-text {
    font-size: 16px;
    color: var(--infn-color-primary);
}

.infn-section-title {
    font-size: 20px;
    text-transform: uppercase;
    font-weight: bold;
    color: var(--infn-color-primary);
    font-family: 'Oswald';
}

.infn-section-subtitle {
    font-weight: 600;
    font-size: 16px;
    text-transform: uppercase;
    opacity: .9;
    color: var(--infn-color-primary);
    font-family: 'Oswald';
}

/* # INPUT */

/* Search bar */

.infn-input-search-container {
    position: relative;
}

.infn-input-search {
    height: 24px;
    padding: 12px 52px;
    border-radius: var(--infn-border-radius);
    border: none;
    background: #eee;
    font-weight: 500;
    color: var(--infn-color-primary);
    outline: none;
}

.infn-input-search-container > i {
    position: absolute;
    top: 15px;
    left: 24px;
    color: var(--infn-color-primary);
    opacity: .5;
}

/* Form group */

.infn-form-group > label {
    text-transform: uppercase;
    font-weight: bold;
    font-size: 14px;
    color: var(--infn-color-primary);
}

.infn-form-group-input {
    border-radius: 16px;
    padding: 10px 20px;
    background-color: white;
    font-size: 1rem;
    color: var(--infn-color-primary);
    display: block;
    border: 1px solid #ced4da;
    margin-top: 6px;
    transition: border-color .15s ease-in-out, box-shadow .15s ease-in-out;
}

.infn-form-group-input:focus-visible {
    outline: 2px solid var(--infn-color-primary-50);
}

/* # CARDS */

.infn-card {
    transition: transform 300ms;
    cursor: pointer;
    border-radius: var(--infn-border-radius);
    box-shadow: var(--infn-box-shadow-light);
    background: white;
    padding: 24px 32px 32px;
}

.infn-card:hover {
    transform: scale(1.005);
    box-shadow: var(--infn-box-shadow);
}

.infn-counter {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 9px 24px;
    box-shadow: var(--infn-box-shadow);
    border-radius: 25px;
    text-transform: uppercase;
    font-size: 16px;
    font-weight: 900;
    color: var(--infn-color-primary);
    max-width: 500px;
}

.infn-counter > div {
    opacity: .7;
}

.infn-counter-text {
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
}

.infn-counter-num {
    margin-left: 3px;
}

</style>

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
