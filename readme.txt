- In index.html
    <link rel="stylesheet" href="css/style.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.12.1/css/all.min.css"/>

- % sudo npm install -g sass

- Use File Watchers in Webstorm
	◦ Install SASS plugin in Webstorm in preferences/Plugins
	◦ Preferences / Tools / File Watchers
		‣ Make SCSS checked
		‣ Double click SCSS to change settings (leave default)

		    Arguments : $FileName$:../css/$FileNameWithoutExtension$.css
		    Output Paths : ../css/$FileNameWithoutExtension$.css:../css/$FileNameWithoutExtension$.css.map

• Or in the terminal
	◦ Sass --watch scss/style.scss css/style.css.  (making to a different folder called css)
	◦ As long as it is running it will check for the changes in sass file and compiles them into css file.

• Compress CSS file
	◦ % sudo npm install -g yuicompressor
	◦ Add File Watcher
		‣ Yui Compressor CSS

- Webstorm LiveEdit
    - Documentation : https://confluence.jetbrains.com/display/WI/Live+Edit?_ga=2.53775144.1482590996.1585422253-1223985983.1518190055
    - Install Chrome plugin
        - JetBrains IDE Support
    - To start using Live Edit you need to start a JavaScript debug session for any html file.

        - To start the JavaScript debugger|http://confluence.jetbrains.com/display/WI/Starting+a+JavaScript+debug+session], select Debug file from the context menu of any html file (or in the context menu of the editor when the file is opened).
