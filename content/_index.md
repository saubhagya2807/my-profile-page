---
title: Home
sidebar:
  entries:
  - title: Welcome
    url: "#intro"
    is_primary: true
  - title: Favorite Movies
    url: "#one"
    is_primary: false
  - title: Movies Cast
    url: "#two"
    is_primary: false
  - title: Get in touch
    url: "#three"
    is_primary: false
sections:
- type: intro
  template: intro
  title: My Profile
  subtitle: I am Saurabh Sonparate.I have 5.3 years of Experience in Front End Developement
    developement. Now I am working on JAM (Javascript API's Markup) Stack technology
  section_id: intro
  background_style: style1
  actions:
  - label: Learn more
    url: "#one"
    is_scrolly: true
    is_primary: false
  component: intro.html
- type: spotlights
  template: spotlights
  title: Spotlights Section
  section_id: one
  background_style: style2
  component: spotlights.html
- type: features
  template: features
  title: Movies Cast
  subtitle: "**_Kabir Singh_** is a 2019 Indian Hindi-language romantic drama film
    written and directed by Sandeep Vanga. It is a remake of his own Telugu film Arjun
    Reddy"
  section_id: two
  background_style: style3
  features_list:
  - title: Shahid Kapoor
    text: '**Shahid Kapoor** ( born 25 February 1981), is an Indian actor who appears
      in [Hindi films](https://en.wikipedia.org/wiki/Bollywood "Bollywood"). Initially
      recognised for portraying romantic roles, he has since taken on parts in action
      films and thrillers, and is the recipient of [several awards](https://en.wikipedia.org/wiki/List_of_awards_and_nominations_received_by_Shahid_Kapoor
      "List of awards and nominations received by Shahid Kapoor"), including three
      [Filmfare Awards](https://en.wikipedia.org/wiki/Filmfare_Awards "Filmfare Awards").'
    icon: fa-user
  - title: Kiara Advani
    text: '**Alia Advani** (born 31 July 1992), known professionally as **Kiara Advani**,
      is an Indian actress who appears predominantly in [Hindi films](https://en.wikipedia.org/wiki/Bollywood
      "Bollywood"). Advani had her first commercial success with a brief role in the
      2016 sports biopic [**M.S. Dhoni: The Untold Story**](https://en.wikipedia.org/wiki/M.S._Dhoni:_The_Untold_Story
      "M.S. Dhoni: The Untold Story")'
    icon: fa-female
  - title: Suresh Oberoi
    text: "**Suresh Oberoi** (born 17 December 1946) is an Indian character actor
      & Politician. He is the father of Bollywood actor **Vivek Oberoi**. He was born
      in Quetta, Balochistan and is a recipient of the 1987 **National Film Award
      for Best Supporting Actor.**"
    icon: fa-male
  - title: Nikita Dutta
    text: "**Nikita Dutta** (born 13 November 1993) is an Indian Actress. A finalist
      of Femina Miss India 2012, she made her Bollywood debut with the film Lekar
      Hum Deewana Dil where she played a supporting role, and expanded to television
      with the show **Dream Girl.**"
    icon: fa-female
  - title: Soham Majumdar
    text: Soham Majumdar is an Indian actor born in Kolkata, India. Soham Majumdar
      is an Engineer and has completed his schooling from Don Bosco, Kolkata.Soham
      Majumdar was very passionate about acting since his birth and was firm to choose
      acting as his profession.
    icon: fa-male
  - title: Aliquam urna dapibus
    text: Phasellus convallis elit id ullam corper amet et pulvinar. Duis aliquam
      turpis mauris, sed ultricies erat dapibus.
    icon: fa-diamond
  actions:
  - label: Learn more
    url: "/generic"
    is_scrolly: false
    is_primary: false
  component: features.html
- type: contact
  template: contact
  title: Get in touch
  text: Phasellus convallis elit id ullamcorper pulvinar. Duis aliquam turpis mauris,
    eu ultricies erat malesuada quis. Aliquam dapibus, lacus eget hendrerit bibendum,
    urna est aliquam sem, sit amet imperdiet est velit quis lorem.
  section_id: three
  background_style: style1
  contact_list:
  - title: Address
    text: |-
      12345 Somewhere Road #654
      Nashville, TN 00000-0000
      USA
    url: ''
  - title: Email
    text: user@Hyperspace.tld
    url: "#"
  - title: Phone
    text: "(000) 000-0000"
    url: ''
  social:
    title: Social
    social_icons:
    - title: Twitter
      icon: fa-twitter
      url: "#"
    - title: Facebook
      icon: fa-facebook
      url: "#"
    - title: GitHub
      icon: fa-github
      url: "#"
    - title: Instagram
      icon: fa-instagram
      url: "#"
    - title: LinkedIn
      icon: fa-linkedin
      url: "#"
  component: contact.html
layout: home
menu:
  main:
    weight: 1

---
