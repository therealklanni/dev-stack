# My Development Stack

I often get questions about what I'm running for development, so here's the whole story for anyone that's interested.

> Feel free to fork this repo and describe your own dev-stack!

## The Metal :metal:

MacBook Pro (Retina, 13-inch, Late 2013)
- Processor: 2.4 GHz Intel Core i5
- Memory: 16 GB 1600 MHz DDR3
- Graphics: Intel Iris 1536 MB

## The System

OS X El Capitan 10.11.x

## The Terminal

I use [ITerm2][iterm2] with [Oh My ZSH][ohmyzsh] as my shell. My [color palette][termcolors] for ITerm varies from "Solarized Dark" to "SETI" to "Adventure Time" depending on my mood. My ZSH theme is [purity][purity].

I also have ITerm set up "docked" to the bottom of the screen (appears on all desktops), with high transparency but about 50% blur effect to offset the transparency.

I also use [dotfiles][dotfiles] to keep all my configuration and automatically set up any new computer exactly the way I like it.

### [Homebrew][brew]

These are all of the [brew][brew] packages I currently have installed.

Libs, compilers (and their ilk), obvious things like bash, and things that weren't directly installed by me have been omitted for brevity.

- [autojump][autojump]
- [autossh][autossh]
- [bash-completion][bash-completion]
- [brew-cask][brew-cask]
- [byobu][byobu]
- [cowsay][cowsay]
- [dwarf-fortress][dwarf-fortress]
- [git][git]
- [go][go]
- [haskell-platform][haskell-platform]
- [hub][hub]
- [imagemagick][imagemagick]
- [lynx][lynx]
- [mitmproxy][mitmproxy]
- [mobile-shell][mobile-shell]
- [ngrok][ngrok]
- [nmap][nmap]
- [node][node]
- [pandoc][pandoc]
- [redis][redis]
- [rename][rename]
- [source-highlight][source-highlight]
- [ssh-copy-id][ssh-copy-id]
- [tmux][tmux]
- [tree][tree]
- [wget][wget]

### [node][nodejs] 4.1.2 / [npm][npm] 3.3.7

These are the [npm][npm] packages that are currently globally installed.

- [babel][babel]
- [bower][bower]
- [bower-migrate][bower-migrate]
- [browser-sync][browser-sync]
- [browserify][browserify]
- [dogesay][dogesay]
- [eslint][eslint]
- [faucet][faucet]
- [forever][forever]
- [fraktur][fraktur]
- [generator-gulp-webapp][generator-gulp-webapp]
- [gulp][gulp]
- [guppy-cli][guppy-cli]
- [hotel][hotel]
- [http-server][http-server]
- [jshint][jshint]
- [json-server][json-server]
- [mocha][mocha]
- [n][n]
- [node-inspector][node-inspector]
- [node-libs-browser][node-libs-browser]
- [nodemon][nodemon]
- [np][np]
- [npm][npmnpm]
- [pm2][pm2]
- [public-ip][public-ip]
- [redis-commander][redis-commander]
- [speed-test][speed-test]
- [standard][standard]
- [tape][tape]
- [watchify][watchify]
- [webpack][webpack]
- [yo][yo]

## The Apps

> Apps installed via [brew cask][caskroom]

- [alfred][alfred]
- [atom][atom]
- [caffeine][caffeine]
- [copy][copy]
- [firefox][firefox]
- [flux][flux]
- [gas-mask][gas-mask]
- [gitbook][gitbook]
- [github][github]
- [google-chrome][google-chrome]
- [icefloor][icefloor]
- [iterm2][iterm2]
- [imagealpha][imagealpha]
- [imageoptim][imageoptim]
- [macdown][macdown]
- [quicklook-json][quicklook-json]
- [recordit][recordit]
- [skitch][skitch]
- [skype][skype]
- [slack][slack]
- [steam][steam]
- [spectacle][spectacle]
- [transmission][transmission]
- [virtualbox][virtualbox]

## The Editor

I use both [Sublime Text 3][sublimetext] and [Atom][atomio], about 50/50, though I still favor Sublime for now. It should go without saying that I use [Package Control][packagecontrol] with Sublime (but I said it anyway for anyone who is new to Sublime).

I'm using a [dark solarized][sublimesolar] ([atom][atomsolar]) theme on both editors. And the [Isotope ui theme][isotope] for Atom.

### Sublime Packages

- Better CoffeeScript
- CSSLint
- EditorConfig
- Emmet
- Emmet CSS Snippets
- FileDiffs
- Gist
- Git
- GitGutter
- Handlebars
- Inc-Dec-Value
- JavaScriptNext
- JSHint Gutter
- Markdown Extended
- Pretty JSON
- Sass
- SnippetMaker

### Atom Packages

- command-logger
- editorconfig
- emmet
- file-icons
- gist-it
- git-plus
- merge-conflicts
- minimap
- project-manager
- script
- linter
- linter-jscs

[brew]: http://brew.sh
[tree]: http://brewformulas.org/tree
[bash-completion]: http://brewformulas.org/bash-completion
[cowsay]: http://brewformulas.org/cowsay
[git]: http://brewformulas.org/git
[haskell-platform]: http://brewformulas.org/haskell-platform
[mitmproxy]: http://brewformulas.org/mitmproxy
[ngrok]: http://brewformulas.org/ngrok
[hub]: http://brewformulas.org/hub
[mobile-shell]: http://brewformulas.org/mobile-shell
[nmap]: http://brewformulas.org/nmap
[brew-cask]: http://brewformulas.org/brew-cask
[dwarf-fortress]: http://brewformulas.org/dwarf-fortress
[node]: http://brewformulas.org/node
[source-highlight]: http://brewformulas.org/source-highlight
[wget]: http://brewformulas.org/wget
[byobu]: http://brewformulas.org/byobu
[imagemagick]: http://brewformulas.org/imagemagick
[pandoc]: http://brewformulas.org/pandoc
[autojump]: http://brewformulas.org/autojump
[redis]: http://brewformulas.org/redis
[ssh-copy-id]: http://brewformulas.org/ssh-copy-id
[autossh]: http://brewformulas.org/autossh
[go]: http://brewformulas.org/go
[lynx]: http://brewformulas.org/lynx
[rename]: http://brewformulas.org/rename
[tmux]: http://brewformulas.org/tmux
[nodejs]: https://nodejs.org
[npm]: https://npmjs.com
[babel]: https://npmjs.com/babel
[bower]: https://npmjs.com/bower
[bower-migrate]: https://npmjs.com/bower-migrate
[dogesay]: https://npmjs.com/dogesay
[eslint]: https://npmjs.com/eslint
[faucet]: https://npmjs.com/faucet
[forever]: https://npmjs.com/forever
[fraktur]: https://npmjs.com/fraktur
[generator-gulp-webapp]: https://npmjs.com/generator-gulp-webapp
[gulp]: https://npmjs.com/gulp
[guppy-cli]: https://npmjs.com/guppy-cli
[hotel]: https://npmjs.com/hotel
[http-server]: https://npmjs.com/http-server
[jshint]: https://npmjs.com/jshint
[json-server]: https://npmjs.com/json-server
[mocha]: https://npmjs.com/mocha
[n]: https://npmjs.com/n
[node-inspector]: https://npmjs.com/node-inspector
[node-libs-browser]: https://npmjs.com/node-libs-browser
[nodemon]: https://npmjs.com/nodemon
[npmnpm]: https://npmjs.com/npm
[pm2]: https://npmjs.com/pm2
[redis-commander]: https://npmjs.com/redis-commander
[standard]: https://npmjs.com/standard
[tape]: https://npmjs.com/tape
[webpack]: https://npmjs.com/webpack
[yo]: https://npmjs.com/yo
[caskroom]: http://caskroom.io
[caffeine]: http://caskroom.io/search?q=caffeine
[alfred]: http://caskroom.io/search?q=alfred
[atom]: http://caskroom.io/search?q=atom
[copy]: http://caskroom.io/search?q=copy
[firefox]: http://caskroom.io/search?q=firefox
[flux]: http://caskroom.io/search?q=flux
[gas-mask]: http://caskroom.io/search?q=gas-mask
[gitbook]: http://caskroom.io/search?q=gitbook
[github]: http://caskroom.io/search?q=github
[google-chrome]: http://caskroom.io/search?q=google-chrome
[icefloor]: http://caskroom.io/search?q=icefloor
[iterm2]: http://caskroom.io/search?q=iterm2
[imagealpha]: http://caskroom.io/search?q=imagealpha
[imageoptim]: http://caskroom.io/search?q=imageoptim
[macdown]: http://caskroom.io/search?q=macdown
[quicklook-json]: http://caskroom.io/search?q=quicklook-json
[recordit]: http://caskroom.io/search?q=recordit
[skitch]: http://caskroom.io/search?q=skitch
[skype]: http://caskroom.io/search?q=skype
[slack]: http://caskroom.io/search?q=slack
[steam]: http://caskroom.io/search?q=steam
[spectacle]: http://caskroom.io/search?q=spectacle
[transmission]: http://caskroom.io/search?q=transmission
[virtualbox]: http://caskroom.io/search?q=virtualbox
[sublimetext]: https://www.sublimetext.com/3
[atomio]: https://atom.io
[sublimesolar]: https://packagecontrol.io/packages/Theme%20-%20Sodarized
[atomsolar]: https://atom.io/themes/solarized-dark-apparent-ui-successor
[packagecontrol]: https://packagecontrol.io
[isotope]: https://atom.io/themes/isotope-ui
[ohmyzsh]: http://ohmyz.sh
[termcolors]: https://github.com/mbadolato/iTerm2-Color-Schemes
[purity]: https://github.com/therealklanni/purity
[dotfiles]: https://dotfiles.github.io
[watchify]: https://npmjs.com/watchify
[np]: https://npmjs.com/np
[browserify]: https://npmjs.com/browserify
[public-ip]: https://npmjs.com/public-ip
[speed-test]: https://npmjs.com/speed-test
[browser-sync]: https://npmjs.com/browser-sync
