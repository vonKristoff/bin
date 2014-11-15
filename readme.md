#bin directory
---
Basic set of executables from the bash prompt.

###How to:
Create a `~/.bin/` and clone repo.

##Execs

* `hidden` shows / hides hidden files in Finder
* `newpost` creates a new post for jekyll blog (deprecated - but useful)
* `project` initialise new web based project. See below for detailed usage.
* `stacker` Invoke a web stack of choice on a fresh VPS. see [@repo](https://github.com/vonKristoff/stacks)
* `freshOSX` __make executable__ `chown +x freshOSX`, then run to install basic dev env dependencies for your new OSX. ie: git; node; homebrew. **!mportant - fill out git config options**, and think to include: `git config --global push.default simple`. Finally, you could also check [this](http://mallinson.ca/osx-web-development/) great writeup out, for anything I may have missed out - `dnsmasq`

---

###`project` [name] [type]
Choose a deployment method, for decent experiment deployment.

>NAME  

Sets the **project name** as **working directory**, **readme title** and **package.json** description.

>TYPES

* `exp` (default - not required) *BASIC Vanilla experimental project, probably involving just CSS and OR minimal Javascript*
* `es6` Getting exciting - Modern Best practice methods involving Node in the frontend with **Browserify**, **Common JS Modules**, **JS TESTING**
* `node-server` Skeleton `Express` app running a node server 

##Other
* `subl` - alias for sublime text. (think deprecated.. needs checking)
