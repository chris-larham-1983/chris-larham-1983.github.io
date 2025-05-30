# Table of Contents

* [General Information](#general-information)
* [Technologies](#technologies)
* [Setup](#setup)

***

## General Information

This is my solution to the **Codecademy** portfolio project entitled *Portfolio Website*, 
wherein I had to design a personal portfolio website that showcases the projects that I 
have worked on in the 'Full Stack Engineer Path'.

The projects that this website showcases are as follows: 

- a website style guide
- a responsive website for an imaginary company, *The Lar Tea Shop*
- a responsive website for an imaginary club, the *Penwithick Movie Club*
- a *WordPress* website that I have been working on since December 2015
- *Jammming*, a responsive React app that interfaces with the *Spotify API*
- a responsive React app that interfaces with the *Reddit JSON API* 
- an e-commerce application *REST API*
- a pet adoption website, *Adopt a Pet!*
- *Debugging Test*, a repository that shows how I helped a fellow Codecademy learner to overcome challenges he encountered in his project

This personal portfolio website is structured as followed:

- a **'bio' section**, with images of me and my family
- a **'projects' section**, with images of projects that link to the 'live' web pages
- a **'qualifications' section**, with images of my academic certificates
- a **'contact' section**, with a form that enables people to message me

***

## Technologies
  
I used **HTML5** and **CSS3** to complete this project.  More specifically, I used **CSS Flexbox**, **CSS Grid** 
and **CSS Media Queries** to ensure that the design of this website is fully responsive and performs well on 
devices of differing screen size. 

As the screen size decreases, the grid (in terms of rows, columns) of 21 academic certificates changes from a 
6 x 4 grid (with 3 blank cells) to 7 x 3 grid, then to a 11 x 2 grid (with 1 blank cell), and finally to a 21 x 1 
grid. The images in the 21 x 1 grid are sized so as to utilise all the available screen width; all the other images 
are 300 pixels wide and 450 pixels high.  Hovering over the images in the 11 x 2, 7 x 3, and 6 x 4 grids expands the 
grid area for the hovered image, resulting in the hovered image spanning two rows and two columns. 

The form in the **contact** section is fully functional.  Information is sent to a server file written in **PHP** that 
validates and sanitises the data, and then sends me an email that contains the sender's name, email address, and message.  

***

## Setup

Simply download this project, navigate to the 'index.html' file, and double-click thereon.

![The index file that loads the webpage][index_file]

[index_file]: images/index_file.PNG

Alternatively, navigate to https://chris-larham-1983.github.io.

***
