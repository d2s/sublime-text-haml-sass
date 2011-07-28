# EXPLANATION

These are TextMate syntax highlighting files that work with Sublime Text 2.

I pilfered them from other repos on GitHub, after searching for ones that were compatible.

* Updated by [n00ge](https://github.com/n00ge/sublime-text-haml-sass)
	- Added SASS (Windows).sublime-build, SASS (OSX).sublime-build, SASS (Linux).sublime-build, sasswatch.bat, and the Snippets folder
	- The build files will run 'sass --watch .:.' on the current SASS file in Sublime when running Build via Tools > Build or by pressing F7


# INSTALLATION

## Basic install (for downloaders)

1. Go to menu bar: "Sublime Text 2 > Preferences > Browse Packages…"
   - Alternate method, on OS X, in Terminal:
   - $ cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages

2. Once that directory is open, close Sublime Text 2.

3. Copy the two directories: /SASS/, and /Ruby Haml/ to that directory.

4. Restart Sublime Text 2.


## Advanced install (for developers)

1. Create fork of repository via GitHub

2. Clone repository from GitHub to your local computer
    Example for a location would be:
    ~/projects/software/sublime-text/sublime-text-haml-sass

3. Open Terminal, and check that the location of your cloned repository works, e.g.:
   - $ cd ~/projects/software/sublime-text/sublime-text-haml-sass

4. Close Sublime Text 2.

5. Open Terminal, on OS X, and write:
   - $ cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages

6. Link the two directories: /SASS/, and /Ruby Haml/ to that directory.
    ln -s ~/projects/software/sublime-text/sublime-text-haml-sass/Ruby\ Haml .
    ln -s ~/projects/software/sublime-text/sublime-text-haml-sass/SASS .

7. Restart Sublime Text 2.

