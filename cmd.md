[Home](README.md)
# Start using Git on the command line

If you want to start using Git and GitLab, make sure that you have created and/or signed into an account on GitLab.
## Open a shell

Depending on your operating system, you will need to use a shell of your preference. Here are some suggestions:
* [Terminal](http://blog.teamtreehouse.com/introduction-to-the-mac-os-x-command-line) on Mac OSX
* [GitBash](https://msysgit.github.io/) on Windows
* [Linux Terminal](http://www.howtogeek.com/140679/beginner-geek-how-to-start-using-the-linux-terminal/) on Linux

## Check if Git has already been installed

Git is usually preinstalled on Mac and Linux.

Type the following command and then press enter:

```
git --version
```

You should receive a message that will tell you which Git version you have on your computer. If you don’t receive a "Git version" message, it means that you need to download Git.

If Git doesn't automatically download, there's an option on the website to download manually. Then follow the steps on the installation window.

After you are finished installing, open a new shell and type "git --version" again to verify that it was correctly installed.

## Add your Git username and set your email 

It is important to configure your Git username and email address as every Git commit will use this information to identify you as the author.

On your shell, type the following command to add your username:
```
git config --global user.name "YOUR_USERNAME"
```
Then verify that you have the correct username:
```
git config --global user.name
```
To set your email address, type the following command:
```
git config --global user.email "your_email_address@example.com"
```
To verify that you entered your email correctly, type:
```
git config --global user.email
```
You'll need to do this only once as you are using the --global option. It tells Git to always use this information for anything you do on that system. If you want to override this with a different username or email address for specific projects, you can run the command without the --global option when you’re in that project.
