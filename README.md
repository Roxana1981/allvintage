# AllVintage Blog

Home of all vintage stuff.

Please visit the blog [here](https://allvintage-48223a19dde6.herokuapp.com/).

## Project status update

This project has been created for the purpose of completion of Project 4. The base of the project is influenced by Code Institute blog walkthrough project.
In line with Project 4 requirements an addtitional functionality was created to allow users to submit blog content requests.

AllVintage blog is created with the purpose of being a site where users can find interesting articles about old items, and be part of an online community of vintage enthusiastics.  AllVintage blog has a page Administrator, to create, update and delete posts.  Users can sign up, sign in/out, comment and like posts, complete form to suggest posts, engage with other users of the blog community, and engage with the page Administrator.

Due to time constraints and some some challenges with deployment to Heroku, the project is incomplete at the time of the submission.
The remaining aspect, which need to completed are as follows:
-completion of CRUD functonality specifically to allow logged users to delete and amend their comments
-additional styling is required to make the blog more appealing to users
-code testing 
-code commenting across code files
-completion of the readme document, including database schema and wireframes

## Project 4

### Background

![Multidevice view](static/images/mockup.png)

## Design 

## Solution 

The solutions below were used for this blog project

**Database structure**
The blog site needs a database structure in order to be able to support required functionality such as blog posts, comments, likes, user and content request.
Postgresql was used for the purpose of supporting database related needs of the site.

The below image reflects the database structure.

![database](static/images/database.png)

**Code languages** 
In order to create this blog site HTML, CSS and Python languages were used. HTML was used to create the initial framework of the blog, with Python supporting more complex elements of its functionality.
The CSS was used for styling of the blog site.

**Development**

-Deployment and application hosting
The application was deployed, and it is hosted on Heroku.  Further details are documented in the deployment section below.

## Wireframes

In the process of development a subset of wireframes have been created using Balsamiq application.
Wireframes help to visualise the user experience within the application.

Wireframes have been completed for desktop and mobile users.

**Desktop**

Blog's homepage

![homepage](static/wireframes/homepage.png)

Blog's posts and comment section

![post](static/wireframes/post.png)

Sign up page

![signup](static/wireframes/signup.png)

Sign in page

![signin](static/wireframes/signin.png)

User comment deletion

![deletion](static/wireframes/deletion.png)

User comment update

![update](static/wireframes/edit.png)

Content request

![content](static/wireframes/content.png)

**Mobile**

All mobile related wireframes are reflected in the image below.

![mobile](static/wireframes/mobile.png)

## User stories 

## User Experience 

## Features 

The following features are currently available when accessing the blog.

Homepage

![homepage](static/images/homepage1.png)

Posts

![post](static/images/blogpost.png)

User comment deletion tab

![comment_deletion](static/images/deletion1.png)

User comment update tab

![comment_update](static/images/edit1.png)

User sign up

![signup](static/images/signup1.png)

User sign in

![signin](static/images/signin1.png)

Content request section

![content](static/images/content1.png)

Blog page administration

![admin](static/images/admin.png)

## Potential future developments

This is a list of potential features/enhancements to be developed, in order to improve user's experience within the blog 
*Include the Search function in the navigation bar, to allow users to look for specific items.
*Enlarge blog images
*Include videos in each blog post
*Add a live chat for registered users within the posts, with the aim of enforcing community engagement
*Add section to ask registered users if they wish to be notified each time a new post/article is uploaded/published in the blog

## Testing 

The testing of the project included functional testing to confirm correct functionality of various blog's components. In addtion also a code testing was completed as part of project development.

**Functional testing**

The functional testing was completed manually with a number of test scripts and related outcomes reflected in the below.
The functional testing was focused on the homepage and blog's posts, user as well as admin testing. The testing has been deemed as successful.

![testing](static/images/testing.png)


**Code testing**

**HTML code**

The code validation for HTML was completed in W3C HTML Validator. 

Below is the outcome of the HTML files tested

Base and Index files

No errors were detected.

![testing](static/test/html.baseindex.png)

Detail_post file 

Some errors were identified.

![testing](static/test/html.post.png)

Register file

Some errors were identified.

![testing](static/test/html.register.png)

Login file 

No errors were detected.

![testing](static/test/html.login.png)

Content file

Some errors were identified.

![testing](static/test/html.content.png)


**CSS code**

The CSS code was validated using Jigsaw CSS Validator. No errors have been identified.

![testing](static/test/css.png)

**Python code**
Testing of the python code was completed using Code Institute's Python Linter herou app.
Below are the outcomes of the code tests.

Settings.py file

One of the lines of the code is longer than expected.

![testing](static/test/settings.png)

Allvintage URLS.py file

No errors were identified.

![testing](static/test/allvintage.urls.png)

Blog Admin.py file

No errors were identified.

![testing](static/test/blog.admin.png)

Blog Apps.py file

No errors were identified.

![testing](static/test/blog.apps.png)

Blog URLS.py file

No errors were identified.

![testing](static/test/blog.urls.png)

Blog Views.py file

No errors were identified.

![testing](static/test/blog.views.png)

Blog Forms.py file

No errors were identified.

![testing](static/test/blog.forms.png)

Blog Models.py file

No errors were identified.

![testing](static/test/blog.models.png)

Content Apps.py file

No errors were identified.

![testing](static/test/content.apps.png)

Content Forms.py file

No errors were identified.

![testing](static/test/content.forms.png)

Content Models.py file 

No errors were identified.

![testing](static/test/content.models.png)

Content Admin.py file 

No errors were identified.

![testing](static/test/content.admin.png)

Content Views.py file

No errors were identified.

![testing](static/test/content.views.png)

Content URLS.py file

No errors were identified.

![testing](static/test/content.urls.png)


**Lighthouse Testing**

Lighthouse testing for both desktop and mobile has been executed using Dev Tool in Chrome.

*Desktop* 

![testing](static/test/lighthousedesktop.png)

*Mobile*

![testing](static/test/lighthousemobile.png)

**Bugs**

 **Fixed**

  **Unfixed**

## Deployment

The blog application was deployed to production using Heroku.
The following steps have been taken in order to successfully deploy the blog to production:

1. Sign up to Heroku was required.
2. New application needed to be created in Heroku. This required application name to be selected along required region (Europe).
3. Heroku Postgres required to be added in the Resources tab.
4. In the Settings section there were a number of Config Vars, which needed to be setup. These included SECRET_KEY, PORT (set to 8000), DATABASE_URL and CLOUDINARY_URL.
   The relevant values included in the above referenced settings, were also included in the env.py file.
5. In the Deploy tab of Heroku GitHub depository needed to be selected in order to connect it with Heroku for deployment.
6. Deploy Branch button in Heroku was used to submit a build of the application in Heroku.
7. When the application was deployed successfully, the URL for the application has become available in the Settings tab in Heroku.

## Credits

Blog images were sourced from Pexels website.

-The project concept was influenced by Code Institute's blog walkthrough project.

Thanky you to Code Institute for module content.


