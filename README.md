# Blog Lyfe
This is a project that demonstrates how you could implement a blog on a Django and React application. What is interesting about the project is that it demonstrates how you can implement a WYSIWYG editor on the Django Admin which makes it much easier to create blogs posts. This is an implementation for making blog posts assuming that you just want an admin user to post blogs on the site, this is not an implementation for a multiuser blog application.

In order to test out this project, follow these steps:
- clone the repository
- in the frontend folder, run: npm install, this will install the required frontend packages
- in the frontend folder, run: npm run build, this will make a build folder and copy it into the backend folder
- in the backend folder, run: python3 -m venv venv
- then activate the virtual environment
- in the backend folder, run: pip install -r requirements.txt
- in backend/blog_lyfe/settings.py, under DATABASES, set the PASSWORD field to your database password