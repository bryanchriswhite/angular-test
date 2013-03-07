#Angular Test Project
This is a skeleton of an angular project containing one page of markup and styling and an end-to-end test. The intention is for the developer to write units (including unit tests!) to make the test past.

##Workflow & Tooling
The workflow used in the project this is sampled from utilizes the following tools and methodologies:
* Behavioral Driven Development
  * End-to-End testing using the Angular test framework (obviously)
  * Unit testing using Jasmine test framework
  * Karma/Testacular (optionally JSTestDriver)
* Git version control
* Compass & SASS (scss)
  * Foundation 4 -- css framework (upcoming)
  * _RVM, ruby 1.9.3-head_
* Yeoman workflow
  * Yo -- generators
  * Grunt -- task runner
  * Bower -- dependency manager
* JSHint -- code validation
* Node v0.8.22
  * NVM -- node version management
  * NPM -- node package management
* Webstorm -- IDE

##Getting Started
In case you're used to a different environment here's a few tips on where to begin:

####Install all the things
1. [Node Version Manager](https://github.com/creationix/nvm)
  * install: `curl https://raw.github.com/creationix/nvm/master/install.sh | sh`
  * restart shell OR `source ~/.bashrc` _(or .bash_profile / .zshrc if applicable)_
2. Node
  * install: `nvm install v0.8.22`
  * set as default node version _(if desirable)_: `nvm alias default v0.8.22`
3. Yeoman+
  * install globally: `npm i -g grunt-cli bower yo`
4. Git
  * clone: `git clone git://github.com/bryanchriswhite/angular-test.git`
5. NPM & Bower dependencies
  * install locally: `npm install && bower install`
6. Gem Dependencies
  * install: `gem install compass sass zurb-foundation`
7. IDE
  * [JetBrains Webstorm](http://www.jetbrains.com/webstorm/)

####If you don't already have ruby
* [Ruby Version Manager](http://rvm.io)
  * install: `\curl -L https://get.rvm.io | bash -s stable --autolibs=enabled --ruby=1.9.3`
  * _(optional)_ create angular gemset: `rvm gemset use angular --create`