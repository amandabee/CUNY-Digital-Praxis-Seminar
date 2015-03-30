If you've got a couple of different folks working on the same code base, you need some version control. Emailing files back and forth is not going to work for very long. Trust me. <a href="https://en.wikipedia.org/wiki/Git_%28software%29">Git</a> is a distributed version control system that allows multiple users to work on the same code and resolve conflicts (like two people editing the same file at the same time.)  Even if it is just you, version control is your friend. This used to work, and then you did ... something ... and now it doesn't? Roll back to the version that worked. 

Git is a free and open protocol. Anyone can implement it. And there are people who will tell you that what makes git great is that it doesn't depend on a central hub. Which is true. That is pretty cool. It is also more or less irrelevant to you because you are going to use a central hub. Probably <a href="http://github.com">github</a>, that's what most people use. 

<!--more-->

The digital fellows have a very nice <a href="https://digitalfellows.commons.gc.cuny.edu/2015/03/10/intro-to-github-part-i/">intro to git</a> writeup, though it is more geared towards truly distributed collaboration. 

Some quick github tips: 

1. Don't share a github account. Everyone should create their own account and then be added to the repository as collaborators. 

2. If you're using git to manage HTML and CSS files for your website, you may as well take advantage of <a href="https://help.github.com/articles/user-organization-and-project-pages/">github's project pages</a>. On github.com, create a new repository, and then add a new branch called <code>gh-pages</code> in your new repository. Head over to your <a href="https://help.github.com/articles/setting-the-default-branch/">repository settings</a> and set the default branch to <code>gh-pages</code>. 

Your HTML will all be accessible at <code>username.github.io/repository</code>. For instance, you can see the whole <code>gh-pages</code> branch of my <code>CUNY-data-skills</code> repository at <a href="http://amandabee.github.io/CUNY-data-skills/">http://amandabee.github.io/CUNY-data-skills/</a>.

3. Github offers a pretty nice <a href="https://en.wikipedia.org/wiki/Graphical_user_interface">gui</a>, but you don't have to use it. You can just use command line tools. If you want to use git to manage the files on your Reclaim server, you can install git with <code>sudo apt-get install git</code>. Then you need to look at your repository to find out what the SSH clone URL is, but it is probably something like <code>git@github.com:amandabee/workshops.git</code>. You'd clone that repository with <code>git clone git@github.com:amandabee/workshops.git</code> and then from then on you can use <code>git pull</code> to update your code. 

To install the commandline tools on OSX, you should start with <a href="http://brew.sh/">Homebrew</a>. Once that's running you can install git with <code>brew git</code>. On Linux you want to use <code>sudo apt-get install git</code>. I've never used git on Windows, but you can certainly Google it, or just use the github gui. 

If you get stuck, don't hesitate to ask for help. 
 
