# Computer Setup

This is a repo of the configurations I have on my computer for productivity and development.
I am using zsh as my shell, which has become the Mac OS default. First clone this repo and I suggest you move it to a hidden directory `mv computer-setup .computer-setup` at the root of your User. Second, simlink the desired `zshrc` from the `zsh_profiles` directory to your local `.zshrc` using the command `ln -s ~/.computer-setup/zsh_profiles/<ZSH_PROFILE> ~/.zshrc`

**NOTE** double check the user used in PATHS of each zsh-profile, they will differ

---

## TERMINAL THEMES

* [Powerlevel10k](https://github.com/romkatv/powerlevel10k)

## APPS

* [Postman](https://www.getpostman.com/) - API development
* [Mindnode](https://mindnode.com/) - Mind mapping application 
* [YouTube CLI Player](https://github.com/mps-youtube/mps-youtube)
* [Postico](https://eggerapps.at/postico/) - PostgreSQL GUI Client
* [iStat](https://bjango.com/mac/istatmenus/) - Computer monitoring 
* [Bartender 2](https://www.macbartender.com/) - Organize menu bar apps
* [Alfred](https://www.alfredapp.com/) - App launching & custom workflow's
* [Sketch](https://www.sketchapp.com/) - Design/Prototype/Wire frame projects
* [CloudApp](https://www.getcloudapp.com/) - Quick screenshot gif/annotator/link generator
* [BetterTouchTool](https://www.boastr.net/) - Snap windows into corners and specified sizing
* [Webstorm](https://www.jetbrains.com/webstorm/) / [Atom](https://atom.io/) - IDE and Code Editor
* [Adobe Experience](http://www.adobe.com/products/experience-design.html) - Design/Prototype/Wire frame projects
* [Discord](https://discordapp.com/) / [Slack](https://slack.com/) - Messaging application with dev-help channels
* [PIA - private internet access CLI](https://www.privateinternetaccess.com/helpdesk/kb/articles/pia-desktop-command-line-interface)
* [Little Snitch - network monitoring](https://www.obdev.at/index.html)

# CLI APPS
* [Github CLI](https://cli.github.com/manual/installation) - CLI for working with github
  * [gh-prs](https://github.com/dlvhdr/gh-prs) - github cli extension for visualizing open PRs
  * [gh-notify](https://github.com/meiji163/gh-notify) - github cli extension for getting notifications
  * [gh-graph](gh extension install kawarimidoll/gh-graph) - github cli extension to see contribution graph
* [Bubbletea - TUI framework](https://github.com/charmbracelet/bubbletea) - a framework for reacting terminal user interfaces
  * [Bubbles](https://github.com/charmbracelet/bubbles) - smaller components of the Bubbletea framework
* [FZF fuzzy finder](https://www.youtube.com/watch?v=1a5NiMhqAR0)
* [Bat (replaces cat)](https://github.com/sharkdp/bat)
* [scp CLI](https://stackabuse.com/using-scp-to-copy-and-securely-transfer-files-and-folders) - secure file transfer between computers
  
## NODE PACKAGES

* [itunes-cli](https://github.com/mischah/itunes-remote) - control itunes from cli
* [now](https://www.npmjs.com/package/now) - deploy application with "now" command
* [nvm](https://github.com/nvm-sh/nvm) - Node version management, easily switch between node versions
* [heroku-cli](https://devcenter.heroku.com/articles/heroku-cli) - cli for working with heroku
* [preact-cli](https://github.com/developit/preact-cli) - boilerplate cli for preact application
* [nodemon](https://github.com/remy/nodemon) - watches node server and restarts automatically on changes
* [git-open](https://github.com/paulirish/git-open) - from cli type "git open" to open repo in default browser
* [create-react-app](https://github.com/facebookincubator/create-react-app) - boilerplate for react application
* [trash-cli](https://www.npmjs.com/package/trash-cli) - use instead of "rm || rm -r" will move thing to trash instead of permanently deleting

## BREW PACKAGES

* [gojq](https://github.com/itchyny/gojq) - Pure Go implementation of [jq](https://github.com/stedolan/jq)
* [NVM](https://gist.github.com/nijicha/e5615548181676873118df79953cb709) - Node Version Manager
* [Bat](https://github.com/sharkdp/bat) - Alternative to "Cat", supports syntax highlighting for a large number of programming and markup languages.
* [gcsfuse](https://github.com/GoogleCloudPlatform/gcsfuse) - a user-space file system for interacting with GCP Storage buckets. [Installation Guide](https://github.com/GoogleCloudPlatform/gcsfuse/blob/master/docs/installing.md#os-x)
* [aircrack-ng](https://www.aircrack-ng.org/) - Aircrack-ng is a complete suite of tools to assess WiFi network security
* [john](https://www.openwall.com/john/) - john the ripper password cracker
* [hashcat](https://hashcat.net/hashcat/) - hashcat is the world's fastest password recovery tool

## FAV ZSH PLUGINS

* [zsh-plugins](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins)
* [fzf-tab](https://github.com/aloxaf/fzf-tab)
* [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)
* [git](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins#git) - git aliases & functions
* [osx](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins#osx) - utility commands for OSX
* [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md)
* [z](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins#z) - jump to folder without having to write full filepath
* [web-search](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins#web-search) - make web-searches from command line

## ALFRED WORKFLOW'S

* [LastPass](https://www.alfredforum.com/topic/15646-lastpass-accelerator/) - interacting with lastpass CLI [github repo](https://github.com/lastpass/lastpass-cli)
* [CDN](http://www.packal.org/) - workflow to grab CDN's
* [Wi-Fi](http://www.packal.org/) - turn Wi-Fi On/Off through alfred
* [Dash](http://www.packal.org/) - workflow for searching Dash API references
* [Shorten URL](http://www.packal.org/) - workflow to make a bit.ly short link
* [Kill Process](http://www.packal.org/) - workflow to kill processes on computer
* [iMessages](http://www.packal.org/) - workflow to initiate a text message through iMessage
* [Password Generator](http://www.packal.org/) - workflow for easily generating a complicated password

## DISCORD / SLACK CHANNELS

* Node.js (node-js.slack.com) - Slack Channel
* DevMountain (devmtn.slack.com) - Slack Channel
* Postgres (postgresteam.slack.com) - Slack Channel 
* reactiflux - Discord server for react development & questions
* Frontend Developers (frontenddevelopers.slack.com) - Slack Channel

## MAINTENANCE

* [Malwarebytes](https://www.malwarebytes.com/) - Free virus & malware computer scanner
* [CleanMyMac 3](http://bit.ly/2xnlnEf) - Runs maintence scripts & uninstall / clean junk files 

## OTHER

* [SSH Config setup](https://linuxize.com/post/using-the-ssh-config-file/) - understanding configuring your SSH useage.
* [Modern Unix](https://github.com/ibraheemdev/modern-unix) - repo of unix programs that have been modernized
  * [Delta](https://github.com/dandavison/delta) - viewer for `git diff` output
  * [gtop](https://github.com/aksakalli/gtop) - systems monitoring dashboard
  * [broot](https://github.com/Canop/broot) - see a tree like structure of the file directory
* [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts) - font book for many apps
* [Vuze](http://www.vuze.com/) - Torrenting Application
* [PopcornTime](https://popcorn-time.to/) - Stream Torrents
* [Fantastical](https://flexibits.com/fantastical) - Calendar App
* [VLC](https://www.videolan.org/vlc/index.html) - Cross platform multimedia player
* [HTTPie](https://httpie.org/)
* arp-scan - sends ARP packets to hosts on the local network and displays device details example command: `arp-scan -l`

## RESOURCES

* [Oh My Zsh](http://ohmyz.sh/)
* [iTerm2](https://www.iterm2.com/)
* [FZF tutorial](https://www.freecodecamp.org/news/fzf-a-command-line-fuzzy-finder-missing-demo-a7de312403ff/)
* [Setting Up VIM](http://marcgg.com/blog/2016/03/01/vimrc-example/)
* [Vim-as-an-ide](https://github.com/jez/vim-as-an-ide) - [vim ide article](https://blog.jez.io/vim-as-an-ide/)
* [Terminal Boosters](https://medium.com/productivity-freak/terminal-boosters-7c300e6406c8)
* [Managing Multiple git accounts](https://youtu.be/lLgWWtOk7gk)
* [Mac-setup](https://sourabhbajaj.com/mac-setup/) 

## OPTIMIZE WEBSTORM PERFORMANCE

Here is my recipe how to speed up your lovely WebStorm:

Go to Preferences and do next:
Appearance & Behaviour > System Settings > Updates: disable auto update
Appearance & Behaviour > System Settings > Usage Statistics: Uncheck Allow sending data usage statistics to JetBrains
Editor > Live Templates: disable all, leave only what you are really use
Editor > Emmet: disable all emmets
Editor > Intentions: I leave only: CSS, Declaration, JavaScript and Language Injection
Plugins: leave only next (*- can be also disabled in case you don't need them):
CoffeeScript*
CSS Suport
CVS Integration
Git Integration
HTML Tool
IntelliLang
JavaScript Debugger *
JavaScript Intention Power Pack
JavaScript Support
NodeJS*
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
