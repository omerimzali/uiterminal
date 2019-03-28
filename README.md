<p align="center">
  <img width="96" src="https://github.com/omerimzali/uiterminal/blob/master/examples/images/uiterminal.png?raw=true"><br><br>
 </p>

<h1 align="center">UITerminal</h1>

*<p align="center">Terminal Style CSS Framework</p>*

<p align="center">
  <img src="https://img.shields.io/badge/license-MIT-blue.svg?style=flat"/>
   <img src="https://img.shields.io/badge/CSS-Terminal-green.svg?style=flat"/>
 </p>
 
## Introduction

UITerminal is an **Terminal Style CSS Framework**. 

## Install

You can get UITerminal with CDN.

```html
 <head>
        <link href="https://cdn.jsdelivr.net/gh/omerimzali/uiterminal@master/uiterminal.min.css">
</head>
```
Or You can pull it with github.
```
git clone https://github.com/omerimzali/uiterminal.git
```

## Usage
Before start to use UITerminal, You should get 'Press Start 2P' to your workarea. 

```html
    <head>
        <link href="https://fonts.googleapis.com/css?family=Press+Start+2P" rel="stylesheet">
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/omerimzali/uiterminal@master/uiterminal.min.css" >
   </head>
```
## Elements&Colors&ETC
1. uiterminal-full: It's a containter for other uiterminal elements.
```
<div class='uiterminal-full'>
```

2. uiterminal-line: It's basicly a line for any content

```
<span class='uiterminal-line'>.uiterminal-line</span>
<span class='uiterminal-line is-centered'>.is-centered</span>
<span class='uiterminal-line is-centered is-blinked'> .is-blinked </span>
<span class='uiterminal-line is-centered is-empty'> .is-empty</span>
```
3. Colors
```
<span class='uiterminal-line uitext-primary'>.uitext-primary</span>    
<span class='uiterminal-line uitext-secondary'>.uitext-secondary</span>    
<span class='uiterminal-line uitext-success'>.uitext-success</span>    
<span class='uiterminal-line uitext-danger'>.uitext-danger</span>    
<span class='uiterminal-line uitext-warning'>.uitext-warning</span>    
<span class='uiterminal-line uitext-white'>.uitext-white</span>    
<span class='uiterminal-line uitext-black '>.uitext-black</span> 
<span class='uiterminal-line uitext-white uibg-primary'>.uibg-primary</span>  
<span class='uiterminal-line uitext-white uibg-secondary'>.uibg-secondary</span>  
<span class='uiterminal-line uitext-white uibg-success'>.uibg-success</span>  
<span class='uiterminal-line uitext-white uibg-danger'>.uibg-danger</span>  
<span class='uiterminal-line uitext-white uibg-warning'>.uibg-warning</span>  
<span class='uiterminal-line uitext-black uibg-white'>.uibg-white</span>  
<span class='uiterminal-line uitext-white uibg-black'>.uibg-black</span>  
```
4. Form Elements
```
<span class='uiterminal-line'> .uiterminal-text: <input type='text' class='uiterminal-text' autofocus> </span>
<span class='uiterminal-line'> .fullline: <input type='text' class='uiterminal-text fullline' autofocus> </span>
<span class='uiterminal-line is-empty'>
     <textarea class='uiterminal-textarea' autofocus> </textarea>
</span>
```
5. Buttons
```
    <button class='uiterminal-button '>Button</button>
    <button class='uiterminal-button uitext-white uibg-primary'>primary</button>
    <button class='uiterminal-button uitext-white uibg-secondary'>secondary</button>
    <button class='uiterminal-button uitext-white uibg-success'>succes</button>
    <button class='uiterminal-button uitext-white uibg-danger'>danger</button>
    <button class='uiterminal-button uitext-white uibg-warning'>warning</button>
    <button class='uiterminal-button uitext-black uibg-white'>white</button>
    <button class='uiterminal-button uitext-white uibg-black '>black</button>
```
6. Badges
```
    <a href="#" class="uiterminal-badge uitext-white uibg-primary">Primary</a>
    <a href="#" class="uiterminal-badge uitext-white uibg-secondary">Secondary</a>
    <a href="#" class="uiterminal-badge uitext-white uibg-success">Success</a>
    <a href="#" class="uiterminal-badge uitext-white uibg-danger">Danger</a>
    <a href="#" class="uiterminal-badge uitext-white uibg-warning">Warning</a>
    <a href="#" class="uiterminal-badge uitext-black uibg-white">White</a>
    <a href="#" class="uiterminal-badge uitext-white uibg-black">Black</a>
```

7. Progress
```
<span class='uiterminal-line is-full is-empty'>
    <progress class="uiterminal-progress progress-primary" max="100" value="90"></progress>
</span> 
<span class='uiterminal-line is-full is-empty'>
    <progress class="uiterminal-progress progress-secondary" max="100" value="80"></progress>
</span> 
<span class='uiterminal-line is-full is-empty'>
    <progress class="uiterminal-progress progress-success" max="100" value="70"></progress>
</span> 
<span class='uiterminal-line is-full is-empty'>
    <progress class="uiterminal-progress progress-danger" max="100" value="60"></progress>
</span>  
<span class='uiterminal-line is-full is-empty'>
    <progress class="uiterminal-progress progress-warning" max="100" value="50"></progress>
</span>  
<span class='uiterminal-line is-full is-empty'>
    <progress class="uiterminal-progress progress-white" max="100" value="40"></progress>
</span>  
<span class='uiterminal-line is-full is-empty'>
    <progress class="uiterminal-progress progress-black" max="100" value="30"></progress>
</span>  
```
8.Tables
```
<span class="ui-terminal-line">
        <table class="uiterminal-table ">
        ..
        </table>
</span>
```
9. Images: 
```
<img src="images/manjaro.png" class="uiterminal-image">
<img src="images/fedora.png" class="uiterminal-image is-blurred">
<img src="images/arch.png" class="uiterminal-image is-ghost">
```
10. Headings
```
<span class='uiterminal-line is-empty'>
    <h1>h1. UITERMINAL</h1>
</span>
<span class='uiterminal-line is-empty'>
    <h2>h2. UITERMINAL</h2>
</span>
<span class='uiterminal-line is-empty'>
    <h3>h3. UITERMINAL</h3>
</span>
<span class='uiterminal-line is-empty'>
    <h4>h4. UITERMINAL</h4>
</span>
<span class='uiterminal-line is-empty'>
    <h5>h5. UITERMINAL</h5>
</span>
<span class='uiterminal-line is-empty'>
    <h6>h6. UITERMINAL</h6>
</span>
```
11. Lists
```
<span class='uiterminal-line is-empty'>
    <ul>
        <li>Lorem ipsum dolor sit amet</li>
        <li>Consectetur adipiscing elit</li>
        <li>Integer molestie lorem at massa</li>
        <li>Facilisis in pretium nisl aliquet</li>
        <li>Nulla volutpat aliquam velit
          <ul>
            <li>Phasellus iaculis neque</li>
            <li>Purus sodales ultricies</li>
            <li>Vestibulum laoreet porttitor sem</li>
            <li>Ac tristique libero volutpat at</li>
          </ul>
        </li>
        <li>Faucibus porta lacus fringilla vel</li>
        <li>Aenean sit amet erat nunc</li>
        <li>Eget porttitor lorem</li>
    </ul>
</span>
```
## Browser Support
UITerminal tested on following browsers.
* Chrome
* Firefox
* Safari
* Opera

## Development&Contributions

[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/omerimzali/uiterminal)

You can fork the project and enter this commands in your terminal.

```sh
git clone https://github.com/YOUR_GITHUB_USERNAME/uiterminal.git
cd uiterminal

```

## Thanks 
 UITerminal Inspired by NES.CSS, I have to thank to [BcRicco](https://github.com/BcRikko)




