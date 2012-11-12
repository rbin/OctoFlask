Rbin's OctoFlask
=================

A Tiny little Flask blog app using MongoEngine. Because NoSQL is awesome.

It is written in Python - Flask, and uses MongoDB and MongoEngine.  It also uses SASS & Twitter Bootstrap and Disqus for comments.

Please feel free to Fork this or download it, change it and build/use it for your own small blog!

P.S - THE NAME OCTO IS MINE. YOU CAN'T USE IT. (It's the name of my blog.)

One downloaded, change any reference to 'your app name' from 'octo' if you would like to name it yourself.


- PLEASE NOTE - This isn't a serious, full scale app for blogs, just something to get you started with Flask & Mongo.
It has the basic functions in there, and not much else.

You can enter the admin panel by going to  /admin/  The user details are defined in the auth.py file.


Installation
-----------------

  1. Install [pip](http://www.pip-installer.org/en/latest/installing.html)
  2. Make a [virtualenv](http://virtualenvwrapper.readthedocs.org/en/latest/#introduction) for this project
  3. Install the required dependencies: `pip install -r requirements.txt`

Run the blog:
   
    python manage.py runserver

Goto: [http://localhost:5000](http://localhost:5000)




* Using SASS?
* ================== *

Indeed, many people think SASS can only be used with Ruby. Not true! You can use it with any type of project.

Simply install the latest stable SASS gem -   gem install sass

Once installed, use the watch command to make it watch a directory, or file, and output css from Sass.


> sass --watch /path/to/my/sass : /path/to/overwrite/

This will take the SASS from your specified folder, and output it as <yourfile>.css.  You can then include this in the header of the blog.  For reference, I have included my SASS file in the project's static/css/sass folder.


Sharing is caring!!  RBIN loves you.