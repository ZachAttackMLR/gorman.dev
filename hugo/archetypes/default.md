---
# This determines what shows up first, lower weight = shows up first
weight: 1

# This is what appears as the tab's title
title: "{{ replace .Name "-" " " | title }}"

# This is the description in the <head> tag
description: "description in the <head> tag"

# This the heading of the navigation at the top of the new page
nav_heading: "nav heading"

# This is what appears in the projects section, place this image at the /static/img folder
thumbnail: ""

# This is the title of the document in the projects section
case_short_title: "project short title"

# This is the title of the project in the project page
case_title: "project title"

# This is the subtitle of the case study in the case studies section and the case study page
case_subtitle: "Mobile App Design"

# This is the project description in the projects section
case_description: ""

# This is the featured image of the project, place this image at /post_title_here/img folder
# e.g. /mypost/img
case_feature_img: ""

# This is the project summary in the case itself
case_summary: "Cope is an application that helps users track their mental health. Progress is measured through the use of a check-in system, calendar, medicine tracker and a summary dashboard. I created a minimum viable product for this application."

# Your team members
team: ["Alexis Collado", "Carlos Arcenas", "Kat Uytiepo", "John Palomo"]

# Roles of your team members
roles: ["Branding and Identity", "User Interface Design", "Prototyping", "User Research"]

# Methods your team members used
methods: ["Sketching", "Mockups", "Guerilla Testing"]

# Links at the bottom of the case study and where they link to
# img is the svg that's part of the button. You can use eyeball.svg or download.svg
# Place your custom svgs into /static/svg
button_links:
    - link: "https://marvelapp.com/g4b64e/screen/14364499"
      img: "eyeball.svg"
      text: "View Prototype"
    - link: "http://copenow.co/"
      img: "eyeball.svg"
      text: "View Landing Page"
    - link: "cope.pdf"
      img: "download.svg"
      text: "Download Feature Sets"

# Testimonial text
testimonial: "Alexis designed everything for Cope from the ground up. What I really like about him is his true understanding and grasp of what makes a great UI great. He knows that the user experience needs a lot of refining from customers and he isn't shy to take feedback even if it's critical. Alexis is one of those rare people who just gets it."

# Testimonial photo, place this at /post_title_here/img
# e.g. /mypost/img
testimonial_photo: "john.jpg"

# Author of testimonial
testimonial_author: "John Robert Palomo"

# Testimonial subtitle, usually position of the testimonial author
testimonial_subtitle: "Co-founder, Cope"

date: {{ .Date }}
draft: false

# Write the content of your case study below the three dashed lines. You can use markdown and raw HTML.
---
