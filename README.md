# Site Publishing Using FTP

## Overview

In this lesson we will cover publishing your website using File Transfer Protocol to upload files to a remote hosting server.

## Objectives

1. Explain what FTP is
2. Describe key details to connect to a remote FTP server
3. Using FileZilla Client to upload content

## Publishing Using FileZilla and FTP

### What Is FTP?

FTP stands for File Transfer Protocol. It is one of a few standardized ways to connect to and transfer content to a remote server. There are many programs for Mac and PC that make transferring using FTP easy. In order to host your site on a remote server you will need to register for hosting space. If you'd like to use your own domain (e.g., "myawesomedomain.com"), you'll need to purchase one. *For a list of paid domain and hosting providers see the links below at the bottom of this lesson.*

<iframe width="640" height="480" src="https://www.youtube.com/embed/q89ZQXsIFQQ?rel=0" frameborder="0" allowfullscreen></iframe>

### Key Details For Connection

After signing up for a domain and hosting, you will receive a login and password to a control panel. This process differs slightly from host to host. the goal will be to log in to your control panel and either set up or find the login for an existing FTP user. The three key pieces of information are the FTP host domain, user login, and password. Once you have the information you are ready to proceed to using FileZilla to connect to your remote server.

### Using FileZilla

First [download and install Filezilla Client](https://filezilla-project.org/), then open up the application and click the Site Manager icon in the top left of the screen. This will pop up a window with the login details fro any servers you wish to setup connections to.

Click the "New Site" button. Then type in a name that will identify your site. (This label is strictly for your own records and in no way will effect connecting to your server.)

Next, on the "General" tab fill in the FTP host domain under where it says "host:".

Next, under "Protocol" select either "FTP" or "SFTP" depending on what is preferred by your provider. (Usually FTP is fine.)

Next, under "Login Type" select "Normal", and under "User" fill in your user login. Then under "Password", type in your password and click the "OK" button to save your details.

Now click the "Site Manager" icon again from top left a second time. Now that all your information is saved you can simply click the site from the menu under "My Sites", and then click the "Connect" button. Wait a few moments while your local machine attemots to make an FTP connection to the remote server. If you get back an error message make sure to copy it down and contact your host to have them help troubleshoot the issue. Sometimes it can be as simple as re-checking your password as it may have been mistyped.

If all goes well you will see connection successful message and the file list will display the contents of your server.

You can now drag and drop files from your local file system (in the left pane) to your remote server's file system (in the right pane). Check with your host as to which folder to drag your site files into if it is not clear. A good way to test if it is working is to create an index.html page that has the text "hello, world" saved in the file and drop it into the remote file system pane in FileZilla to upload it. Then head to your browser and type in your domain name to see if the "hello, world" message appears.

## Summary

- We can use FTP to transfer files from your local machine to a remote hosting server.
- Use the Site Manager in FileZilla CLient to save your FTP credentials so you can connect to your server with ease.
- Dragging and dropping files from your local file system to your remote servers file system allows you to publish content.
- Creating an index.html file with some content allows you to test if you can see your content in a browser.

## Resources

- [FileZilla - FTP Client](https://filezilla-project.org/)
- [1and1 - Domains and Hosting](http://www.1and1.com/?kwk=10422255)
- [Dreamhost - Domains and Hosting](http://www.dreamhost.com/r.cgi?1022798)
- [Bluehost - Domains and Hosting](http://www.bluehost.com/track/jongrover)
<p class='util--hide'>View <a href='https://learn.co/lessons/html-css-site-publishing-using-ftp'>HTML CSS Site Publishing Using FTP </a> on Learn.co and start learning to code for free.</p>
