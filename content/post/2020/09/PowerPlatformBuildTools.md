---
title: "Power Platform Build Tools" # Title of the blog post.
date: 2020-09-16T14:15:14-04:00 # Date of post creation.
description: "The Power Platform Build Tools provide a way to easlily built continuous integration." # Description used for search engine.
featured: true # Sets if post is a featured post, making appear on the home page side bar.
draft: true # Sets whether to render this page. Draft of true will not be rendered.
toc: false # Controls if a table of contents should be generated for first-level links automatically.
# menu: main
featureImage: "/images/lou/power-apps-logo-c-small-custom.png" # Sets featured image on blog post.
thumbnail: "/images/lou/power-apps-logo-c-small-custom.png" # Sets thumbnail image appearing inside card on homepage.
shareImage: "/images/lou/power-apps-logo-c-small-custom.png" # Designate a separate image for social media sharing.
codeMaxLines: 10 # Override global value for how many lines within a code block before auto-collapsing.
codeLineNumbers: false # Override global value for showing of line numbers within code block.
figurePositionShow: true # Override global value for showing the figure label.
categories:
  - Technology
tags:
  - Power Platform
  - Power Platform Build Tools
  - DevOps
  - Azure
---

I am very excited Microsoft Power Platform Build Tools going GA. This was a huge hole in the Application Development Lifecycle for Dynamics 365 and Power Platform. When creating applications, you always have the source code stored in a source control system. The idea that you should be able to re-create a system just using the source code, becomes much more maintainable with Power Platform Build Tools. 

With source control, this also makes Continuous Integration (CI) and Continuous Delivery (CD) possible. With Power Platform Build Tools, we a Solution stored within a source control repository that can then perform a check on the solution and deploy it to another environment automatically. 

