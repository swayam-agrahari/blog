---
title: "Developing and Deploying a Portfolio."
date: 2023-09-10T01:21:59+05:30
github_link: "https://github.com/swayam-agrahari"
author: "Swayam Agrahari"
tags:
  - Portfolio
  - Hugo
  - AMFoss
image: /img/hugo.svg
description: "A summary of my blog post."
toc : false
---

# Task 2: Building My Portfolio Website with Hugo

In this task, I was given to create my own portfolio website using Hugo, a powerful open-source website generator. It was a great experience, and I got to learn many things .

## Installing HUGO and Creating Server

To install HUGO in my Ubuntu, I refered <a href="https://gohugo.io/installation/linux/" style="color: red;">Install Linux Guide</a> .So I ran following commands in the terminal; It created a local server for me to use and customize the portfolio.
1. `sudo snap install hugo`
2. `hugo server -D`
 
## Theme Selection

For my portfolio website, After going through many themes,I finally chose <span style="color: red;">**Hugo Profile**</span> theme because its clean design and customizable. UI was a perfect fit for my task.

## Customization
So to cutsomize my portfolio, I had to make changes in **hugo.toml** file.
Following were the customization I made in my portfolio: 
1. Rewriting details
2. Adjusting Layouts
3. Deleting unnecessary parts
4. Including usable links

## Content Creation

I wanted my portfolio to showcase my interest, background and work. To achieve this, I included the following types of content:
- Projects 
- Achievement
- Blog

I wanted my website to be user-friendly. So, when someone land on the homepage, they'll see my latest projects right away to get them interested. I made sure the navigation menu at the top is easy to use, so they can explore my work, skills, education, and contact info without much hassle. Lastly, I've placed buttons inviting you to reach out to me because I'd love to connect with you as you explore my portfolio.


## Challenges and Solutions

While building my portfolio, I faced a few challenges, such as adjusting layouts which I resolved by watching some youtube tutorials and using internet.

## GitHub Pages Hosting

While hosting my portfolio website using Github Pages, I faced a small challenge. I got an error message when I first attempted to make  the `git submodule`.  The issue was that Hugo had already created a `public` directory for me. So after few tries of fixing it, I deleted `public` before running the `git submodule` code and everything worked perfectly.
To post the website, I used [Post HUGO website with Github Pages](https://youtu.be/LIFvgrRxdt4?si=8FpecldaZ8U-7F5q) video. 

## Conclusion

Building my portfolio website with Hugo and hosting it on GitHub Pages was a total learning experience fo me. I gained valuable insights into web development and design. This project also allows me to share my work and creativity with the world.

## Links

1. Blog Repository (used for storing portfolio code):
  - [Blog Repo](https://github.com/swayam-agrahari/blog)

2. Repository for deploying your portfolio:
  - [swayam-agrahari.github.io](https://github.com/swayam-agrahari/swayam-agrahari.github.io)

3. Live Portfolio:
  - [View Portfolio](https://swayam-agrahari.github.io/)

4. Blog:
  - [Blog Post](https://swayam-agrahari.github.io/blogs/markdown-syntax/)


---
*Acknowledgments: This portfolio is solely made with my knowledge and my ability to use Internet.*
