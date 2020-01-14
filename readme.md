Welcome to my Django Projects' gateway!
========================================

Overview
----------------------------------------
I have chosen Django as my current backend framework, and I am learning as much as I can from it, one step at a time. I'm more than pleased to share some of my projects here so that you can test them out and come along me on my way to learn one of the three things I'm passionate about: web/app development.

Following up you will find the links to the working URLs of my Django projects and to their respective GitHub repositories, as well as a brief description and image showcase of their basic functionality down below those links. If you want a more detailed description, please feel free to check the README files on each of those project's repository.

The projects are ordered from newest to oldest. Please, **do keep in mind** that they are hosted in a free version of Heroku, since I do not intend to monetize them, I've just done them for the sake of learning, filling up my portfolio and having fun of course. As free Heroku hosting has dynos that reset each time the requested server wakes up, **ALL USER UPLOADED MEDIA FILES ARE DELETED** if 30 mins have gone by since the last visit. I mention this because some projects might seem to be broken but they are not (like RNMC Hunt, since it does not show thumbnails or image bodies). Just upload a couple yourselves and you will notice the change.

Links
----------------------------------------
- [**RNMC Videos**](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/readme.md#rnmc-videos)
    - URL: https://rnmcvideos.herokuapp.com/ (working)
    - Repository: https://github.com/RenzoMurinaCadierno/Django-RNMCVideos

- [**RNMC Hunt**](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/readme.md#rnmc-hunt)
    - URL: https://rnmchunt.herokuapp.com/ (working, but broken media due to Heroku's free dynos)
    - Repository: https://github.com/RenzoMurinaCadierno/Django-RNMCHunt

- [**RNMC Social**](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/readme.md#rnmc-social)
    - URL: https://rnmcsocial.herokuapp.com/ (working)
    - Repository: https://github.com/RenzoMurinaCadierno/Django-RNMCSocial

- [**RNMC Blog**](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/readme.md#rnmc-blog)
    - URL: https://rnmcblog.herokuapp.com/  (working)
    - Repository: https://github.com/RenzoMurinaCadierno/Django-RNMCBlog

Descriptions, functionality and image showcasing
----------------------------------------

## RNMC Videos

- URL: https://rnmcvideos.herokuapp.com/ (working)
- Repository: https://github.com/RenzoMurinaCadierno/Django-RNMCVideos

__***Description and functionality***__

A web app where you can create your own video galleries and fill them up with YouTube videos. Any user can see them, so you are free to share them with the world or keep them as a personal video library anytime you wish to rewatch them.

Both function and class-based-views are used, the former to handle generic operations, and the latter to deal with the database through models.py. AJAX is used to enhance UX as it retrieves YouTuve videos in real time while typing on the search bar. Please, do not I am using a free YouTube API for developers, so the search quota is small, but you might look for ten or fifteen videos with no problems. Six will display at a time on each search because of this same reason.

__***Image showcase***__

- **A very basic home page (part 1), I aim for functionality.**

![Basic landing page](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/images/rnmcvideos01.PNG)


- **Home page (part 2), shows most popular and recent galleries.**

![Most popular galleries](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/images/rnmcvideos02.PNG)


- **Django's signup form, styled.**

![Signup](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/images/rnmcvideos03.PNG)


- **Once a user is created, it auto-logins and redirects to galleries to create one.**

![Galleries](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/images/rnmcvideos04.PNG)


- **Naming and creating a video gallery.**

![Creating gallery](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/images/rnmcvideos05.PNG)


- **User's video galleries page, showing the created galleries.**

![Galleries](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/images/rnmcvideos06.PNG)


- **Adding a video to a gallery. You can paste the link or search for the video. AJAX will do the rest.**

![Adding video](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/images/rnmcvideos07.PNG)


- **AJAX rendered response.**

![Adding video](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/images/rnmcvideos08.PNG)


- **Gallery with some added videos.**

![Gallery with videos](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/images/rnmcvideos09.PNG)


- **User video galleries page, now containing the created gallery.**

![Gallery page](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/images/rnmcvideos10.PNG)


- **Home page (part 3), now showing the created gallery as one of the recently created ones.**

![Adding video](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/images/rnmcvideos11.PNG)


## RNMC Hunt

- URL: https://rnmchunt.herokuapp.com/ (working, but broken media due to Heroku's free dynos)
- Repository: https://github.com/RenzoMurinaCadierno/Django-RNMCHunt

__***Description and functionality***__

A site designed as a 'kickstarter' page, containing only the foundations (root functionality) of it. Users can sign up and post a product/service/idea they desire, which includes a thumbnail, an image and a description. It will be listed on the main site and logged in users can view, upvote or downvote it (once per user).

Function based views are used throughout the whole project, so forms are typed manually. Authentication and permissions are manually dealt with, and user uploaded media files are stored in the hosting server. 

**Please note** that this project is hosted in a free development version of Heroku, and as which, dynamos reset each 30 minutes. When they reboot, they render the whole app from scratch DELETING user uploaded media files. That is the reason this website may seem broken with no images showing. Create a product yourself to check it out in all of its glory.

__***Image showcase***__

- **Home page (part 1), when it is empty. That is, when no projects are uploaded.**

![Home page (empty)](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/images/rnmchunt01.PNG)


- **Posting a product/service/idea after logging in.**

![Posting an item](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/images/rnmchunt02.PNG)


- **After posting, this is the item's individual site users can get into to read and upvote.**

![Item's site](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/images/rnmchunt03.PNG)


- **Home page (part 2), once the product is added and upvoted. The page will keep on filling up as long as more products are added to it.**

![Home page with the added product](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/images/rnmchunt04.PNG)


## RNMC Social

- URL: https://rnmcsocial.herokuapp.com/ (working)
- Repository: https://github.com/RenzoMurinaCadierno/Django-RNMCSocial

__***Description and functionality***__

The basic foundations of a social media network web/app. You can sign up, log in, create groups, join groups, comment in groups, read other users' groups and comments, and see your own comments history. Additionally, you can delete your own comments if you desire. 

A model combining function-based and class-based views with mixins and decorators are used to authenticate users and restrict their access to other users' data asides from viewing their comments and groups. Most form-related site functionalities are handled manually, as a learning process.

__***Image showcase***__

- **Home page, a simple landing page that invites you to read the instructions.**

![Home page](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/images/rnmcsocial01.PNG)


- **Once logged in, you can create a group yourself by giving it a name and a description.**

![Group creation](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/images/rnmcsocial02.PNG)


- **You will be redirected to the group's page. Member count is set to one as you are the creator by default, and you are given the option to leave. Posts will appear below.**

![Group page](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/images/rnmcsocial03.PNG)


- **Your created group will appear on the list of available groups to join, by clicking on Group's navlink above.**

![Available group's list](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/images/rnmcsocial04.PNG)


- **Entering a group gives you the chance to post a commentary.**

![Commenting on a group](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/images/rnmcsocial05.PNG)


- **And it will appear in the group's page, from most recent to oldest. You are given the chance to delete the comment.**

![Comment list](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/images/rnmcsocial06.PNG)


- **By cicking on your username in the navlink above, you will be directed to your comments history.**

![User's comment history](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/images/rnmcsocial07.PNG)


## RNMC Blog

- URL: https://rnmcblog.herokuapp.com/ (working)
- Repository: https://github.com/RenzoMurinaCadierno/Django-RNMCBlog

__***Description and functionality***__

The basic foundations of a blogging web/app. As a user, you are limited to read the admin's posts and comment on them. Your comment will not be immediately approved, since the admin has the ability to do so. As an admin, you can create posts, edit them, edit or delete user comments, and approve them before they are uploaded to the post itself. 

A much basic version of the functionality applied in RNMC Social is used here, since this blog served as the foundations to it. Some widgets were added, like the medium text editor. It was an fun little headache, but I am really comfortable with it as a first attempt at Django.

__***Image showcase***__

- **Home page with one post in it.**

![Home page](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/images/rnmcblog01.PNG)


- **Post's page with its body and comments.**

![Post page](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/images/rnmcblog02.PNG)


- **Adding a commentary.**

![Adding commentary](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/images/rnmcblog03.PNG)


- **Using medium text editor to style the commentary (by highlighting it).**

![Styling commentary](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/images/rnmcblog04.PNG)


- **And of course, as an admin, the page to create a new post.**

![Creating post](https://github.com/RenzoMurinaCadierno/DjangoProjectsGateway/blob/master/images/rnmcblog05.PNG)


### Thank you for reading and for taking your time to check these projects out!
