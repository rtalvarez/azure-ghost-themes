azure ghost themes
==================

To setup a shiny new theme for your Ghost blog, deployed via Azure Websites (not a VM):

0. Download a theme. They usually look like a random folder with an 'assets' subfolder, and a bunch of other files.
1. Get an FTP client (such as FileZilla, https://filezilla-project.org/)
2. Log into your Azure dashboard, select your webiste, and click on Dashboard
3. On the right, under Quick Glance, select Setup Deployement Credentials
4. Get the credentials from below (under Deployement / FTP user)
5. Grab the FTP Host Name
6. Fire up FileZilla, paste the FTP Host name, and provide login info
7. Paste all the files of your desired theme in the following remote directory: /site/wwwroot/content/themes/newThemeHere/
8. Go to your settings console at yourBlog/admin and under settings, select the new theme
9. It may take up to 5 mins for it to update the changes


Side note: 
Be careful when deleting stuff from /themes/, if you for some reason try to delete a theme that is currently being used, you will run into problems.
