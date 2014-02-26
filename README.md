# OpenFaux website

## Overview

This readme is meant to be a quick guide to getting started with all of the tools we use in this repo.

Once you've completed this guide you should be ready to start contributing.

## Installation

We use a few pieces of software to help out with formatting an responsive design, namely [Foundation and SASS](http://foundation.zurb.com/docs/sass.html).

Here are tutorials for the required software. We'll use Git, Ruby, node.js, Bower, and Compass.

### Git

Look at http://git-scm.com/book/en/Getting-Started-Installing-Git.

### Ruby

Look at https://www.ruby-lang.org/en/downloads/.

### Foundation

Once you have Ruby you can install Foundation.

```bash
$ gem install foundation
```

### Compass

Look at http://compass-style.org/install/.

### Node.js

Look at http://nodejs.org/download/.

### npm dependencies

Once you have node.js you can install Bower.

```bash
$ sudo npm install -g bower
```

## Configuration

Now that we've got everything installed, it's time to configure the project.

You'll want to open up terminal and navigate to the root project directory.

From this point on any work you do to `.scss` files will automatically be compiled to the `app.css` file in the CSS folder when run this command:

```bash
$ compass watch
```

Everything else is already configured for you in the bower and config files, have fun!

## Notes

I currently use Idea IntelliJ and have a file watcher configured to run instead of using the compass watch command in Ruby.

There are other methods that can be used instead to watch files, this is just the generic catch all, just make sure when uploading your code that the `app.css` actually caught the changes you made the first time to validate your watcher of choice actually works and we're good.

The plugin I use is actually called *File Watchers* and I can provide my configuration upon request.

## Questions?

If you have any questions feel free to contact me on GitHub, I'm @admwx7.
