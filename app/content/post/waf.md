---
title: "Using Azure WAF to Tracking Blocked Requests by Log Analytics" # Title of the blog post.
date: 2021-07-22T09:34:19+02:00 # Date of post creation.
description: "Article description." # Description used for search engine.
featured: true # Sets if post is a featured post, making appear on the home page side bar.
draft: true # Sets whether to render this page. Draft of true will not be rendered.
toc: false # Controls if a table of contents should be generated for first-level links automatically.
# menu: main
featureImage: "/images/waf.png" # Sets featured image on blog post.
thumbnail: "/images/waf.png" # Sets thumbnail image appearing inside card on homepage.
#shareImage: "/images/waf.png" # Designate a separate image for social media sharing.
codeMaxLines: 10 # Override global value for how many lines within a code block before auto-collapsing.
codeLineNumbers: false # Override global value for showing of line numbers within code block.
figurePositionShow: true # Override global value for showing the figure label.
categories:
  - Technology
tags:
  - Azure-WAF-Firewall
  - Security
  - Azure Front Door
  - Log Analytics
# comment: false # Disable comment if false.
---

**How to check if our application has not been attacked? How to check if our Firewall worked and blocked relevant queries. In this post, I will show you how to use Azure Log Analytics to monitor our WAF Firewall.**