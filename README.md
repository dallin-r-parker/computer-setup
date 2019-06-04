# Computer Setup
This is a repo of the configurations I have on my computer for productivity and development

### APPS / CLI APPS
* [Webstorm](https://www.jetbrains.com/webstorm/) / [Atom](https://atom.io/) - IDE and Code Editor
* [YouTube CLI Player](https://github.com/mps-youtube/mps-youtube)
* [iStat](https://bjango.com/mac/istatmenus/) - Computer monitoring 
* [Alfred](https://www.alfredapp.com/) - App launching & custom workflow's
* [Postman](https://www.getpostman.com/) - API development
* [Adobe Experience](http://www.adobe.com/products/experience-design.html) - Design/Prototype/Wire frame projects
* [Sketch](https://www.sketchapp.com/) - Design/Prototype/Wire frame projects
* [Postico](https://eggerapps.at/postico/) - PostgreSQL GUI Client
* [Discord](https://discordapp.com/) / [Slack](https://slack.com/) - Messaging application with dev-help channels
* [Mindnode](https://mindnode.com/) - Mind mapping application 
* [Bartender 2](https://www.macbartender.com/) - Organize menu bar apps
* [BetterTouchTool](https://www.boastr.net/) - Snap windows into corners and specified sizing
* [CloudApp](https://www.getcloudapp.com/) - Quick screenshot gif/annotator/link generator

### NODE PACKAGES
* [trash-cli](https://www.npmjs.com/package/trash-cli) - use instead of "rm || rm -r" will move thing to trash instead of permanently deleting
* [create-react-app](https://github.com/facebookincubator/create-react-app) - boilerplate for react application
* [git-open](https://github.com/paulirish/git-open) - from cli type "git open" to open repo in default browser
* [preact-cli](https://github.com/developit/preact-cli) - boilerplate cli for preact application
* [nodemon](https://github.com/remy/nodemon) - watches node server and restarts automatically on changes
* [n](https://github.com/tj/n) - Node version management, easily switch between node versions
* [now](https://www.npmjs.com/package/now) - deploy application with "now" command
* [heroku-cli](https://devcenter.heroku.com/articles/heroku-cli) - cli for working with heroku
* [itunes-cli](https://github.com/mischah/itunes-remote) - control itunes from cli

### FAV ZSH PLUGINS
* [git](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins#git) - git aliases & functions
* [z](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins#z) - jump to folder without having to write full filepath
* [osx](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins#osx) - utility commands for OSX
* [web-search](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins#web-search) - make web-searches from command line
* [zsh-plugins](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins)
* [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)
* [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md)

### ALFRED WORKFLOW'S
* [CDN](http://www.packal.org/) - workflow to grab CDN's
* [Dash](http://www.packal.org/) - workflow for searching Dash API references
* [iMessages](http://www.packal.org/) - workflow to initiate a text message through iMessage
* [Kill Process](http://www.packal.org/) - workflow to kill processes on computer
* [Shorten URL](http://www.packal.org/) - workflow to make a bit.ly short link
* [Wi-Fi](http://www.packal.org/) - turn Wi-Fi On/Off through alfred
* [Password Generator](http://www.packal.org/) - workflow for easily generating a complicated password

### DISCORD / SLACK CHANNELS
* reactiflux - Discord server for react development & questions
* DevMountain (devmtn.slack.com) - Slack Channel
* Frontend Developers (frontenddevelopers.slack.com) - Slack Channel
* Postgres (postgresteam.slack.com) - Slack Channel 
* Node.js (node-js.slack.com) - Slack Channel

### MAINTENANCE
* [Malwarebytes](https://www.malwarebytes.com/) - Free virus & malware computer scanner
* [CleanMyMac 3](http://bit.ly/2xnlnEf) - Runs maintence scripts & uninstall / clean junk files 

### OTHER
* [Vuze](http://www.vuze.com/) - Torrenting Application
* [PopcornTime](https://popcorn-time.to/) - Stream Torrents    
* [Fantastical](https://flexibits.com/fantastical) - Calendar App
* [VLC](https://www.videolan.org/vlc/index.html) - Cross platform multimedia player

### RESOURCES
* [iTerm2](https://www.iterm2.com/)
* [Oh My Zsh](http://ohmyz.sh/)
* [Cobalt Theme](https://github.com/wesbos/Cobalt2-iterm) - Wes Bos
* [Powerlevel9k Theme](https://github.com/bhilburn/powerlevel9k)
* [Setting Up VIM](http://marcgg.com/blog/2016/03/01/vimrc-example/)

## OPTIMIZE WEBSTORM PERFORMANCE
Here is my recipe how to speed up your lovely WebStorm:

Go to Preferences and do next:
Appearance & Behaviour > System Settings > Updates: disable auto update
Appearance & Behaviour > System Settings > Usage Statistics: Uncheck Allow sending data usage statistics to JetBrains
Editor > Live Templates: disable all, leave only what you are really use
Editor > Emmet: disable all emmets
Editor > Intentions: I leave only: CSS, Declaration, JavaScript and Language Injection
Plugins: leave only next (* - can be also disabled in case you don't need them):
CoffeeScript *
CSS Suport
CVS Integration
Git Integration
HTML Tool
IntelliLang
JavaScript Debugger *
JavaScript Intention Power Pack
JavaScript Support
NodeJS *
Perforce Integration
SASS suport *
Project > Directories: Exclude all what you don't use
Languages & Frameworks > JavaScript > Libraries: leave only: HTML and HTML5 / EcmaScript 5
Languages & Frameworks > Compass: disable it
Tools > WebBrowsers: leave only Chrome
Open terminal, mc or what you prefer and edit vmoptions and increase usage memory pwd: "/Applications/WebStorm.app/Contents/bin/idea.vmoptions"

-Xms1024m 
-Xmx1536m 
-XX:MaxPermSize=1024m 
-XX:ReservedCodeCacheSize=512m 
-XX:+UseCompressedOops 

(Windows: C:\Program Files\JetBrains\WebStorm X.X.X\bin\WebStorm.exe.vmoptions)

So the main idea is next: disable all in Preferences what you really don't use and increase memory for IDE.

 
