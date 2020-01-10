Welcome to my Django Project's gateway!
========================================

Overview
----------------------------------------
I have chosen Django as my current backend framework, and I am learning as much as I can from it, one step at a time. I'm more than pleased to share some of my projects here so that you can test them out and come along me on my way to learning one of the three things I'm passionate about: web/app development.

Following up you will find the links to the working URLs of my Django projects and to their respective GitHub repositories, as well as a brief description and image showcase of their basic functionality down below those links. If you want a more detailed description, please feel free to check the README files on each of those project's repository.

The projects are ordered from newest to oldest. Please, **do keep in mind** that they are hosted in a free version of Heroku, since I do not intend to monetize them, I've just done them for the sake of learning, filling up my portfolio and of course having fun. As they are hosted in a free Heroku version and their dynos reset each time the assigned server wakes up, **ALL USER UPLOADED MEDIA FILES ARE DELETED** on each visit. I mention this because some projects might seem to be broken but they are not (like RNMC Hunt, since it does not show thumbnails or image bodies). Just upload a couple yourselves and you will notice the change.

Links
----------------------------------------
- **RNMC Videos**
    - URL: https://rnmcvideos.herokuapp.com/ (working)
    - Repository: https://github.com/RenzoMurinaCadierno/Django-RNMCVideos

- **RNMC Hunt**
    - URL: https://rnmchunt.herokuapp.com/ (working, but broken media due to Heroku's free dynos)
    - Repository: https://github.com/RenzoMurinaCadierno/Django-RNMCHunt

- **RNMC Social**
    - URL: https://rnmcsocial.herokuapp.com/ (working)
    - Repository: https://github.com/RenzoMurinaCadierno/Django-RNMCSocial

- **RNMC Blog**
    - URL: https://github.com/RenzoMurinaCadierno/Django-RNMCBlog (working)
    - Repository: https://github.com/RenzoMurinaCadierno/Django-RNMCBlog

Descriptions, functionality and image showcasing
----------------------------------------

## RNMC Videos

**Description and functionality**
A web app where you can create your own video galleries and fill them up with YouTube videos. Any user can see them, so you are free to share them with the world or keep them as a personal video library anytime you wish to rewatch them.

Both function and class-based-views are used, the former to handle generic operations, and the latter to deal with the database through models.py. AJAX is used to enhance UX as it retrieves YouTuve videos in real time while typing on the search bar. Please, do not I am using a free YouTube API for developers, so the search quota is small, but you might look for ten or fifteen videos with no problems. Six will display at a time on each search because of this same reason.

**Image showcase**

![alt text](http://url/to/img.png)

Watch out when you clone this repository, since it is already configured for Heroku deployment and will not work at localhost. Read its own README for more instructions.

The idea behind this project is to let users comment on blog posts only I create, what would basically be the foundation of one-way blogging pages like Wordpress.

As an admin, the site gives me the chance to create blog posts delete and edit them, as well as revising user comments before they are published to emulate a 'moderator' role. This site's whole functionality is handled by Class-based views using Django framework. Since my aim here is to work at wiring the back-end, the front-end is a bit too basic. It was made with Bootstrap 3 and some custom CSS.


### Thank you for reading and for taking your time to check this project out!