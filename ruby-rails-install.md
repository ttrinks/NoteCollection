
# Ruby and Rails installation

This is only about installing Ruby and Rails on a Linux system. It's very similar on Mac, but Windows is more complicated to setup. 

## Install Ruby

First, install RVM and a current version of Ruby. Open a Terminal and execute the following:
$ \curl -L https://get.rvm.io

RVM is now installed for you user account. Do not use sudo in any of these commands, the Ruby installation will be strictly for your user, not systemwide.

Now restart your Terminal and make sure it uses a login shell, otherwise the RVM command won't work.

	$ rvm install 2.0.0
	$ rvm use 2.0.0 --default

Ruby 2.0.0 is now installed and selected as the default implementation that RVM will use.
If you'd like to install a different version or implementation (perhaps 1.9.3 or rubinius), just exchange the 2.0.0 in the command for the respective names. You can also install multiple implementations and switch between them on the fly.

### Install Rails
The gem manager should now be available, so you can just install Rails with a single command.

	$ gem install rails

If you're in a hurry, you might want to use the following instead:

	$ gem install rails --no-ri --no-rdoc

This will skip installation of the documentation. If you intend to use the online documentation anyway, you won't need it.

### Start  you first project

Starting a rails project is just a single command.

	$ rails new my-rails-project

This will create a new Rails project inside a directory named my-rails-project.
