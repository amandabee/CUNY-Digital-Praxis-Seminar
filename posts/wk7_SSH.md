A number of you have been asking questions about running on your Reclaim server directly. The tool you need for that is SSH, or <a href="https://en.wikipedia.org/wiki/Secure_Shell">Secure Shell</a>. I used to have a great SSH tip sheet but it has been removed from the internet. We can talk about that later. In the meantime, I cobbled together a <a href="https://github.com/amandabee/CUNY-SOJ-data-storytelling/wiki/Tip-Sheet:-SSH">not-half-bad recap</a> of my original tip sheet.

<!--more-->

If you're running Mac OSX or Linux, your machine has an SSH client built right in. Try it: type <code>which ssh</code> at the command line. Windows users will need to install <a href="http://www.chiark.greenend.org.uk/%7Esgtatham/putty/download.html">puTTY</a>.

To open a shell connection to another machine, you need to know that machine's name (which you already know if you're using SFTP to connect) and you need a username and password. Connect with:

<code>ssh username@example.domain.com</code>

It's actually that simple. You'll be prompted for your password, you'll enter it, and your command prompt will change to reflect the fact that you're now running commands on a remote machine.

Later, we'll talk a little bit about key-based authentication, which is a much more secure way to authenticate your SSH session. But for now, passwords are just fine.
