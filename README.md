# banesblog
A simple blog developed using Django, learnt about writing complex queries

# Features

* This is like a normal blog. Where the cretore posts the blogs, and any user can read the blog which is posted.

* When the user opens the blog, he will see the list of posts in the blog. The results of posts are paginated and shown.

* When the user opens up a specific post, detail view for that particular post will be opened, and the user can read the post in detail

* The user can also see the list of comments specific to that post,  and a form to post a new comment.

* The user can even share the post by clicking on "share this post" link on the detail page. 

* The user can read posts based on tags, i.e., he can read a list of posts which share the same tag.

* The blog, recommends the user some posts which he may like. This is achieved by making use of tags, of the post being read.

* In the home page, in the sidebar the user can see the list of recent posts, as well as list of posts which has more comments.

# Things I learned.

* Django-taggit

* Writing some complex queries, suggeting posts related to the post being read, is developed writing a complex query.

* Developing new template tags, and template filters

* Using static middleware.

# How to run the application

* Clone the repo to your workspace

* Create virutalenv using `mkvirtualenv <your env name>`. (Virutalenvwrapper is required here)

* Run `python manage.py migrate`

* Create a superuser using `python manage.py createsuperuser`.

* Run the local developement server using `python manage.py runserver localhost <port>`

* Create some blog entries using the admin console, by following this url `localhost:<port>/admin`



