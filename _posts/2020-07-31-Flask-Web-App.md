---
title: "Flask Web App"
categories:
  - Projects
tags:
  - python
  - flask
  - web framework
  - microframework
---

This is my first web app project. I came across Flask couple of weeks back. I wondered what use, an html like website building, is to ML or DS. Pardon my ignorance or rather unawareness as I'm new and learning how these technologies work together.

Jupyter notebooks is enough for most of my ML practice exercises but in doing this project I ended up trying different IDEs (three to be precise), virtual environments, github and github pages (that's how you see me here!) which made all the learning challenging yet exciting. I feel like I know so much more now.

Coming to project. This is simplest form of 'Hello World' like Flask web app (I admit I'm tempted to create a full blown blog). But I'm sure I'll create something more functional and more ML oriented in future. For now let me capture what I have learned so far.

- Handling web requests
- Templates
- Template inheritance
- Web forms
- Web forms validation
- Connecting to database

When the app is run the website is accessed  `http://127.0.0.1:5000` it displays 'Hello World'.

If you accessed the following:

`http://127.0.0.1:5000/hello/<yourname>/` - displays a greeting with your name and show a random quote from my choicest quotes ;) .

`http://127.0.0.1:5000/addquote/` - displays a form that allows to enter A quote and it's author of your choice.

`http://127.0.0.1:5000/quotes/` - displays all the quotes in the database.

I also learned to create the app as a package with `_config.py` and `__init__.py`.

This has been a great learning project. To create this page I had to learn about [Jekyll](https://jekyllrb.com/) markdown too. As I learn more I'll publish more content here and on the [github repositories](https://github.com/ron-ahir).