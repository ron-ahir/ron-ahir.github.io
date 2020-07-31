---
title: "Flask Web App"
excerpt_separator: "<!--more-->"

categories:
  - Project
  
tags:
  - python
  - web framework
  - microframework
---

This is my first web app project. I came across Flask couple of weeks back. I wondered what use an html like website building is to ML or DS. Pardon my ignorance or rather unawareness as I'm new and learning how different technologies work together.

Jupyter notebooks is enough for most of my ML practice exercises but in doing this project I ended up trying about IDEs, virtual environments, github and github pages (hey that's how you see me here!) which made all the learning challenging yet exciting. I feel like I know so much more now.

Coming to project. This is simplest form of 'Hello World' like Flask web app (I admit I'm tempted to create a full blown blog). But I'm sure I'll create something more functional and more ML oriented in future. For now let me capture what I have learned so far.

- Handling web requests
- Templates
- Template inheritance
- Web forms
- Web forms validation
- Connecting to database

When the app is run the website is accessed on '''http://127.0.0.1:5000''' and it displayed Hello World there.

If you accessed '''http://127.0.0.1:5000/hello/<yourname>/''' it would display a greeting with your name and show a random quote from my choicest quotes.

And if you tried '''http://127.0.0.1:5000/addquote/''' then it would display a form that allows to enter A quote and it's author of your choice.

I also learned to create the app as a package with '''__init__.py''' and '''_config.py'''