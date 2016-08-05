# PHC_SASS_TUTORIAL

**INSTALLING SASS ON YOUR MACHINE(MAC USERS)**
* OSX comes with ruby installed, run `ruby -v` in the terminal, if your version is lower than 2.0.0, run `sudo gem install ruby`
* In the command line, run the command `gem install sass`
* If an error occurs run `sudo gem install sass`
* Run `sass -v`, if the version is Sass 3.4.22, you have successfully installed sass

***

**SETTING UP AND COMPILING SCCS INTO CSS IN YOUR PROJECT**
* Create a directory, in your main code directory(for this tutorial lets call it sass_tutorial)
* cd into sass_tutorial, create a file called `styles.scss`
* In styles.scss add a sass variable and apply it to an element:
	```scss
	`$primary-color: #009900;
		p {
			color: $primary-color;
		}`














**Tutorials Used** 
* SASS DOCUMENTATION: http://sass-lang.com/install
* SASS INSTALLATION: https://www.taniarascia.com/learn-sass-now/?replytocom=1837#respond
* BOOTSTRAP SASS DOCUMENTATION: https://github.com/twbs/bootstrap-sass