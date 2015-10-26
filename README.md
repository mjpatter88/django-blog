# django-blog
A blog made with Python and Django

I'm going to work through: http://tutorial.djangogirls.org/en/index.html

1. **Installation**
2. How the Internet works
3. Introduction to command line
4. Python installation
5. Code editor
6. Introduction to Python
7. What is Django?
8. Django installation
9. Your first django project!
10. Django models
11. Django admin
12. Deploy
13. Django urls
14. Django views - time to create!
15. Introduction to HTML
16. Django ORM (Querysets)
17. Dynamic data in templates
18. Django templates
19. CSS - make it pretty
20. Template extending
21. Extend your application
22. Django forms
23. What's next?

- - -

## Setting up Python and Django on OS X in 2015
In order to do this the "right" way, we'll be making use of several modern tools:
* homebrew
* pyenv
* pyenv-virtualenv

First, install homebrew if you haven't yet. Next, run the following commands:

    "brew install pyenv"
    "brew install pyenv-virtualenv"

A tutorial that I've found useful is this: <http://amaral-lab.org/resources/guides/pyenv-tutorial>
Now let's install the newest version of Python and create a virtualenv for our project

    "pyenv install 3.4.3"   (This installs the needed version of Python)
    "pyenv virtualenv 3.4.3 django-blog-343" (This creates a new env using the correct version)

With this created, whenever we want to work on our project we simply type:

    "pyenv activate django-blog-343"

Whenever we are done working, we type:

    "pyenv deactivate"

Since we'll obviously be using Django for this project, we can start by installing that:

    "pip install django==1.8"

Finally, go sign up for a free account on <https://www.pythonanywhere.com/>.

- - -


