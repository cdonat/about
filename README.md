Github About Page
================

Version 1.6

_Everything **about** yourself on Github._

This project helps you to build a **about** page to introduce all your information on Github, including your profile, public repositories and contribution frequency. All you need to do is fork this repository then active its gh-pages branch. Your **about** page is hosted under your own Github and you can show it to others as a clear and intuitive introduction of your work at Github.

Briefly speaking, Github user profile page sucks, so I improved it and made it easy to use by others.

Take a quick glance at the **Github About Page** below as [an example](http://andrelion.github.io/about/) and you can [preview your own](http://andrelion.github.io/about/preview/).

![Preview](http://andrelion.github.io/about/assets/preview.png "Preview")




Features
-----------------
1. Indepedent and graceful url address, e.g. http://yourname.github.io/about
2. List your Github personal information you provided in the profile setting.
3. List your Github public repositories, you can choose to recommend or ignore some of them.
4. You can extend your personal information such as Twitter account.
5. You can customise your repository information by adding a image.
5. Easy to deploy, every code is under your control.

How to get your own Github About Page?
-----------------
It's very easy, there are only two things need to be done:

1. Fork repository [AndreLion/about](https://github.com/AndreLion/about)
2. Go to your gh-pages branch [https://github.com/*your-github-ID*/about/tree/gh-pages](https://github.com/your-github-ID/about/tree/gh-pages) and delete the file called delete_me.md in order to activate your github page.

Then, wait at most ten minutes till your own Github About Page has been shipped. 

The Url would be [http://*your-github-ID*.github.io/about/](http://your-github-ID.github.io/about/)

How to customise your own Github About Page?
-----------------
You can change your code to whatever you like because you have the ownership of the repository after you fork it. However, there are two ways to extend your Githua About Page easily:

1. config.json : in this file, you can extend your personal or repo information. For more details, plase check the comment in this file.
2. css/style.css : in the bottom of this file, you can add your own stylesheet to make you repo card perfectly shows in your Github About Page.

How to keep update?
-----------------
This need some work in termial with some git commands.

If some updates are made in the [original repo](https://github.com/AndreLion/about) and you want to apply them to your own forked repo, please follow these two giudes to make your Github About Page catching up the latest version:

1. [Syncing a fork in local](https://help.github.com/articles/syncing-a-fork).
2. [Pushing a branch to remote](https://help.github.com/articles/pushing-to-a-remote#pushing-a-branch).

If you are afraid of command work, you can simply backup your own code then delete the repo then fork a new one then restore the code you backed-up.

Acknowledge
----------------
This project is powered by jQuery, Bootstrap, [Github API](http://developer.github.com/) and [Packery](http://packery.metafizzy.co/).

Open Source License
----------------
For non-commercial, personal, or open source projects and applications, you may use Github About Page under the terms of the GPL v3 License. You may use this project for free.
