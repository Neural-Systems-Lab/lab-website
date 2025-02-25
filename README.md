![on-push](../../actions/workflows/on-push.yaml/badge.svg)
![on-pull-request](../../actions/workflows/on-pull-request.yaml/badge.svg)
![on-schedule](../../actions/workflows/on-schedule.yaml/badge.svg)

# Neural Systems Lab's Website

current website (not yet published to cse server) **[neural-systems-lab.github.io/lab-website](https://neural-systems-lab.github.io/lab-website)** 🚀

## Setup
After cloning this repo, run the following commands to preview the website locally:
1. Install [Docker](https://docs.docker.com/get-docker/)
2. Run `./.docker/run.sh`
3. Click the base URL shown in the terminal. 

## Adding a member
Add a `firstname-lastname.md` file in the `_members` folder. Place the photo under `images/people/lastname.jpg`. An example:
```md
---
name: Preston Jiang
image: images/people/jiang.jpeg
role: phd
description: PhD Student, Computer Science & Engineering
links:
  home-page: https://lpjiang97.github.io/
  email: prestonj@cs.washington.edu
  google-scholar: B706p2YAAAAJ
  twitter: lpjiang97
  github: lpjiang97
---

## Bio
blah blah
```

### If graduated :(
Add `group: alum` to the frontmatter.

## Adding a press article
Add a `YYYY-MM-DD-title.md` file in the `_press` folder. Use `tags` to add relevant keywords. An example:
```md
---
title: "To Be Energy-Efficient, Brains Predict Their Perceptions"
tags: 
  - predictive coding
---
Raj's predictive coding theory is discussed in this [Quanta article](https://www.quantamagazine.org/to-be-energy-efficient-brains-predict-their-perceptions-20211115/).
```

## Adding a news snippet
Add a `YYYY-MM-DD-title.md` file in the `_news` folder. An example:
```md
---
title: Welcome, Dr. Shuchen Wu!
tags: 
  - news
---
Shuchen Wu joins the lab as a Shanahan Postdoctoral Fellow. Welcome!
```
