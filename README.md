# Class of 2021 Website
This is the repository for the Class of 2021's website. On it there will be annoucements, a list of student officers(with emails), and more. The URL is [whs2021.com](http://whs2021.com)

# Posting
To add a post, just make a file in the \_posts directory with the labeling scheme: year_month_day_name.md. In it, you have to put the following format at the top:
```
---
layout: post
title: Title
author: Name
---
```

If you do not know how to fork/pull request a repository on Github to add changes, google it.

# Adding StuCo/School Office members
The format is pretty straight forward, edit the respective file under \_data, follow the current format and USE SPACES NOT TABS

# Tech Details
The website is built by CircleCI using Jekyll, where it is then mirrored to an s3 Bucket running behind Cloudfront for SSL support and global access.
