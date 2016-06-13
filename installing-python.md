# Installing Python on Mac OSX

Open a terminal window ([watch this video if you aren't sure how to open the terminal](https://www.youtube.com/watch?v=zw7Nd67_aFw))

This is a command line interface, which we will use to install the python programming language onto your computer. We can enter commands into this command line, which are just instructions that your computer will follow.

The first command we'll run in the terminal is going to install a package manager named "Homebrew". Package managers make it easy to install software onto a computer by managing all of the downloading and unpacking of software into the computer as needed.

To install Homebrew, copy the following command into your terminal window:

```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Once you have Homebrew installed, the first thing to do is update Homebrew's knowledge of the packages available on the internet. You can do so by running this command in your terminal:

```bash
sudo brew update
```

Finally, we can install python using a very simple command:

```bash
brew install python3
```

We want to be sure to install the package `python3` and not `python`, since t python3 his is a specific version of the python programming language that will be compatible with the tutorials that we will encounter during the class.


Once you have finished using Homebrew to install `python3`, the last thing to do is check to be sure that it is now useable from the terminal interface. We can check this quite easily by simply running the command:

```bash
python3
```

You should see the interactive python3 interpreter launch in that terminal window. That'll look something like this:

```bash
$ python3
Python 3.3.0 (default, Feb  1 2013, 22:09:55) 
[GCC 4.2.1 Compatible Apple Clang 4.1 ((tags/Apple/clang-421.11.66))] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> 
```

If all of this went smoothly, congratulations, you are now ready to use your computer to follow along with our hands-on tutorials.

If you encountered any problems during this set up process, contact Hardwick directly on slack, and he'll assist you in getting past your roadblock.
