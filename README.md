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
* In styles.scss add a sass variable and apply it to an element
	
	```
	$primary-color: #009900;
	
	p {
		color: $primary-color;
	}
	```
* Navigate back to the main dirrectory, in our case, sass_tutorial, and run `sass style.scss:style.css` to compile the scss file into a main.css file. The css file will generate automatically, and from this point on you only modify and code in the scss file, not the css file
* If done correctly, a few new files will be in your project(style.css, style.map.css, style.scss)
* run `sass --watch style.scss:style.min.css --style compressed` to have sass watch your project while you work, this will update your scss to css without having to run a command everytime. This command will also alert you of any errors in the terminal

***

**PROJECT FILE STRUCTURE**
* DO NOT create a css folder/files, if sass if compilled correctly it will do this for you
* Create a sass folder in your main directory(sass_tutorial). Inside of the sass folder create a file called main.scss.
* main.scss will act as an import file for all the partials in your project 
* Your file structure should resemble this
	1. css
		* nested
 
















**TUTORIALS USED** 
* SASS DOCUMENTATION: http://sass-lang.com/install
* SASS INSTALLATION: https://www.taniarascia.com/learn-sass-now/?replytocom=1837#respond
* BOOTSTRAP SASS DOCUMENTATION: https://github.com/twbs/bootstrap-sass