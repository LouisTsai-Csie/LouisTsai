+++
# specifies the content is in TOML
title = "{{ replace .Name "-" " " | title }}" # Auto-Populated Title of the Post
date = {{ .Date }} # Auto-Populated Date Field
draft = true # Status of the Post
author = "" # Author Name
description = "" # Description/Used in SEO
summary = "" # Used on Archive Pages and in RSS
images = ["post-cover.png"] # images used for social media preview. comma separate each image path enclosed in double quotes
thumbnail = "images/landscape.jpg" # featured-image of the page. I will recommend using the same image for both preview and thumbnail
tags = [] # comma-separated tags enclosed in double quotes. also used for SEO.
categories = [] # comma-separated categories enclosed in double quotes.
series = [] # A taxonomy used to list "See Also" Section in Opengraph Templates
slug = "" # Similar to WordPress's Slug (the end part of the URL)
disableComments = false # Set to 'true' if you need to disable comments for any post
+++
