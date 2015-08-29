#bin directory

Basic set of executables from the bash prompt.

###How to:
Create a `~/.bin/` and clone repo.

###Shell Execs

* `hidden` shows / hides hidden files in Finder
* `newpost` creates a new post for jekyll blog (deprecated - but useful)
* `project` initialise new web based project. See below for detailed usage.
* `stacker` Invoke a web stack of choice on a fresh VPS. see [@repo](https://github.com/vonKristoff/stacks)
* `freshOSX` __make executable__ `chown +x freshOSX`, then run to install basic dev env dependencies for your new OSX. ie: git; node; homebrew. **!mportant - fill out git config options**, and think to include: `git config --global push.default simple`. Finally, you could also check [this](http://mallinson.ca/osx-web-development/) great writeup out, for anything I may have missed out - `dnsmasq`

---

###Development Boilerplates

By using the `project` shell from above, build an environment boilerplate.

**Please note, actual scripts and mixins are located on a Bittorent Sync folder**

####Usage

	. project [name] [boilerplate]
	
####Available stacks

*	`exp` - the most basic HTML5 setup for fast CSS JS Experiements and prototyping. Also the default project setting, so you can leave [boilerplate] blank.
*	`express` - Basic express app
*	`requirejs` - AMD setup for JS modules, but ultimately Frameworkless.
*	`browserify` - ES6, Common JS Modules and NPM packages in the FE. Plus `Vue.js` integration.
*	`ng` - Angular boilerplate