---
layout: post
title: My First UD Project
date: 2018-11-27 13:32:20 +0300
description: A blog about my first powershell universal dashboard project. # Add post description (optional)
img: post-1.jpg # Add image post (optional)
tags: [Blog, UniversalDashboard]
author: Adam Bacon # Add name author (optional)
---

So I got tasked at work to automate the process of pulling files from an FTP site, removing the files once downloaded, then moving them to a specific folder on the network, so that they can be automatically imported into the database. I accomplished this using scheduled tasks for powershell to run at set time intervals. But how do you know everything is working? Simples design a beautiful dashboard.

![First Project]({{site.baseurl}}/assets/img/post-1.jpg)

So this shows me the previous week of log files along the top and their file sizes (yes we had an issue on the 25/11/2018) shows how many orders have been imported into the network folder and shows how many orders have been done today, and the current size of the log file. It also shows me in real time when files come in to be processed. I also monitor the status of the service which is running on a separate server. This allows me to glance at this dashboard and see if there has been any issues downloading and importing.

This was a great first project to show my colleagues as well as myself that this new bit of software I purchased was proving it's worth by monitoring something that is a business critical process. I was really happy that I managed to provide a solution to the problem I was given, allowing any staff member to also monitor this daily process and report any issues, that are clearly shown on the dashboard.
