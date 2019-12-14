---
title: Title
layout: default
permalink: /url (url, e.g. youtube/video-one)
parent: Parent (Title of parent page if applicable, if not delete this line)
nav_order: 2 (Where this item should order on the sidebar, leave blank if unsure)
authors: ['exvacuum'] (Replace with your name, follow instructions below to add youself.)
---

#Adding Yourself as an Author
Navigate to the `_data` directory and open the `contributers.yml` file.

Duplicate the following lines:
```
exvacuum: (What you want to put in the authors: variable at the top of the document)
  name: Silas Bartha (Your Name)
  github: ExVacuum (Github Username)
  isAdmin: true (This will be false unless you are a code owner. If you don't know what that means then you probably aren't one.)
```