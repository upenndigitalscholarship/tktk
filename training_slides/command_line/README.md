# Command Line Resources
These resources are used in combination with the [Command Line Basics](command_line_basics.pptx) presentation.

## Online Resources
- [Code Academy - Free Online Course in Command Line Basics](https://www.codecademy.com/learn/learn-the-command-line) - "By the end of the course, you will be able to navigate, access, and modify files and folders on your computer—all without a mouse!" - Basic course is free with add-on paid modules.
- [Handy Command Line Cheatsheet created by Software Carpentry](http://swcarpentry.github.io/shell-novice/reference) - Cheat sheet of common commands used for writing your own scripts, written by the people behind our periodic Software Carpentry workshops.
- [Stack Overflow](https://stackoverflow.com/) - Good place to search for how to do something, what a command means, and post your own questions!
- [Linux Manual Pages](https://linux.die.net/man/) - You can start here when searching for what a command does and what its options and arguments are

## Workshop Prep & Activities
### Everyone
1. Download the [Command Line Adventure](../../activities/adventure.zip) activity.

### Windows Users
1. Install Git Bash by downloading [Git for Windows](https://gitforwindows.org/). During install, make sure to select:
  1. "Use Git from the Windows Command Prompt"
  2. "Checkout Windows-style, commit Unix-style line endings"
  3. "Use Windows' default console window"
2. If your "HOME" environment variable is not set (or you don't know what this is):
  1. Open Start Menu and type `cmd` - This opens the command prompt.
  2. Type this line exactly as shown: `setx HOME "%USERPROFILE%"`
  3. Press Enter and you should see: `SUCCESS: Specified value was saved.`
  4. Type `exit` and press Enter to quite the command prompt.

### Mac and Linux Users
1. Your default shell is Bash so you do not need to install anything!

### Post-Workshop Recommended Activities
1. [Command Line Adventure](../../activities/adventure.zip) activity (see the end of the slides for instructions).
2. For a more thorough exploration of the command line interface, try the [Command Line online course](https://www.codecademy.com/learn/learn-the-command-line)
3. Use SSH to connect to a cloud-hosted development server (such as [Digital Ocean](https://www.digitalocean.com/) - we use the smallest [Standard Droplets running Ubuntu](https://www.digitalocean.com/products/linux-distribution/ubuntu/) if its just for student testing and dev). **Note:** If you are on a Max/Linux, you can just use the `ssh` command, but if you are on Windows, you will need something like [PuTTY](https://www.putty.org/).
4. Try installing LAMP on a cloud-hosted development server. Digital Ocean offers guides for this on many flavors of Linux, such as [Ubuntu 16.04](https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-16-04).

*Note:* Steps 3 & 4 set students with an environment they can use later for web development projects.
