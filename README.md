# <img align="right" src="https://github.com/avelino/awesome-go/raw/master/tmpl/assets/logo.png" alt="awesome-go" title="awesome-go" /> Awesome Go

[![Build Status](https://travis-ci.com/avelino/awesome-go.svg?branch=master)](https://travis-ci.com/avelino/awesome-go)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Slack Widget](https://img.shields.io/badge/join-us%20on%20slack-gray.svg?longCache=true&logo=slack&colorB=red)](http://gophers.slack.com/messages/awesome)
[![Netlify Status](https://api.netlify.com/api/v1/badges/83a6dcbe-0da6-433e-b586-f68109286bd5/deploy-status)](https://app.netlify.com/sites/awesome-go/deploys)
[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/avelino/awesome-go/)

<a href="https://www.producthunt.com/posts/awesome-go?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-awesome-go" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=291535&theme=light" alt="awesome-go - Curated list awesome Go frameworks, libraries and software | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>

## Sponsorships
> [![Digital Ocean](https://avelino.run/sponsors/do_logo_horizontal_blue-210.png)](https://m.do.co/c/bd3b723c0a36?utm_medium=opensource&utm_source=awesome-go)

**We have no monthly cost**_, but we have employees **working hard** to maintain the Awesome Go, with money raised we can repay the effort of each person involved! All billing and distribution will be open to the entire community._

A curated list of awesome Go frameworks, libraries and software. Inspired by [awesome-python](https://github.com/vinta/awesome-python).

### Contributing

Please take a quick gander at the [contribution guidelines](https://github.com/avelino/awesome-go/blob/master/CONTRIBUTING.md) first. Thanks to all [contributors](https://github.com/avelino/awesome-go/graphs/contributors); you rock!

#### *If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!*

### Contents

- [Awesome Go](#awesome-go)
    - [Audio and Music](#audio-and-music)
    - [Authentication and OAuth](#authentication-and-oauth)
    - [Bot Building](#bot-building)
    - [Build Automation](#build-automation)
    - [Command Line](#command-line)

## Audio and Music

*Libraries for manipulating audio.*

* [flac](https://github.com/mewkiz/flac) - Native Go FLAC encoder/decoder with support for FLAC streams.
* [gaad](https://github.com/Comcast/gaad) - Native Go AAC bitstream parser.
* [GoAudio](https://github.com/DylanMeeus/GoAudio) - Native Go Audio Processing Library.
* [gosamplerate](https://github.com/dh1tw/gosamplerate) - libsamplerate bindings for go.
* [id3v2](https://github.com/bogem/id3v2) - ID3 decoding and encoding library for Go.
* [malgo](https://github.com/gen2brain/malgo) - Mini audio library.
* [minimp3](https://github.com/tosone/minimp3) - Lightweight MP3 decoder library.
* [mix](https://github.com/go-mix/mix) - Sequence-based Go-native audio mixer for music apps.
* [music-theory](https://github.com/go-music-theory/music-theory) - Music theory models in Go.
* [Oto](https://github.com/hajimehoshi/oto) - A low-level library to play sound on multiple platforms.
* [PortAudio](https://github.com/gordonklaus/portaudio) - Go bindings for the PortAudio audio I/O library.
* [portmidi](https://github.com/rakyll/portmidi) - Go bindings for PortMidi.
* [vorbis](https://github.com/mccoyst/vorbis) - "Native" Go Vorbis decoder (uses CGO, but has no dependencies).
* [waveform](https://github.com/mdlayher/waveform) - Go package capable of generating waveform images from audio streams.

## Authentication and OAuth

*Libraries for implementing authentications schemes.*

* [authboss](https://github.com/volatiletech/authboss) - Modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure, and start building your app without having to build an authentication system each time.
* [branca](https://github.com/hako/branca) - Golang implementation of Branca Tokens.
* [casbin](https://github.com/hsluoyz/casbin) - Authorization library that supports access control models like ACL, RBAC, ABAC.
* [cookiestxt](https://github.com/mengzhuo/cookiestxt) - provides parser of cookies.txt file format.
* [go-email-normalizer](https://github.com/dimuska139/go-email-normalizer) - Golang library for providing a canonical representation of email address.
* [go-guardian](https://github.com/shaj13/go-guardian) - Go-Guardian is a golang library that provides a simple, clean, and idiomatic way to create powerful modern API and web authentication that supports LDAP, Basic, Bearer token and Certificate based authentication.
* [go-jose](https://github.com/square/go-jose) - Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs.
* [go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) - Standalone, specification-compliant,  OAuth2 server written in Golang.
* [gologin](https://github.com/dghubble/gologin) - chainable handlers for login with OAuth1 and OAuth2 authentication providers.
* [gorbac](https://github.com/mikespook/gorbac) - provides a lightweight role-based access control (RBAC) implementation in Golang.
* [goth](https://github.com/markbates/goth) - provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple providers out of the box.
* [httpauth](https://github.com/goji/httpauth) - HTTP Authentication middleware.
* [jeff](https://github.com/abraithwaite/jeff) - Simple, flexible, secure and idiomatic web session management with pluggable backends.
* [jwt](https://github.com/robbert229/jwt) - Clean and easy to use implementation of JSON Web Tokens (JWT).
* [jwt](https://github.com/pascaldekloe/jwt) - Lightweight JSON Web Token (JWT) library.
* [jwt](https://github.com/cristalhq/jwt) - Safe, simple and fast JSON Web Tokens for Go.
* [jwt-auth](https://github.com/adam-hanna/jwt-auth) - JWT middleware for Golang http servers with many configuration options.
* [loginsrv](https://github.com/tarent/loginsrv) - JWT login microservice with plugable backends such as OAuth2 (Github), htpasswd, osiam.
* [oauth2](https://github.com/golang/oauth2) - Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine and App Engine support.
* [osin](https://github.com/openshift/osin) - Golang OAuth2 server library.
* [otpgen](https://github.com/grijul/otpgen) - Library to generate TOTP/HOTP codes.
* [otpgo](https://github.com/jltorresm/otpgo) - Time-Based One-Time Password (TOTP) and HMAC-Based One-Time Password (HOTP) library for Go.
* [paseto](https://github.com/o1egl/paseto) - Golang implementation of Platform-Agnostic Security Tokens (PASETO).
* [permissions2](https://github.com/xyproto/permissions2) - Library for keeping track of users, login states and permissions. Uses secure cookies and bcrypt.
* [rbac](https://github.com/zpatrick/rbac) - Minimalistic RBAC package for Go applications.
* [scope](https://github.com/SonicRoshan/scope) - Easily Manage OAuth2 Scopes In Go.
* [scs](https://github.com/alexedwards/scs) - Session Manager for HTTP servers.
* [securecookie](https://github.com/chmike/securecookie) - Efficient secure cookie encoding/decoding.
* [session](https://github.com/icza/session) - Go session management for web servers (including support for Google App Engine - GAE).
* [sessiongate-go](https://github.com/f0rmiga/sessiongate-go) - Go session management using the SessionGate Redis module.
* [sessions](https://github.com/adam-hanna/sessions) - Dead simple, highly performant, highly customizable sessions service for go http servers.
* [sessionup](https://github.com/swithek/sessionup) - Simple, yet effective HTTP session management and identification package.
* [sjwt](https://github.com/brianvoe/sjwt) - Simple jwt generator and parser.

## Bot Building

*Libraries for building and working with bots.*

* [echotron](https://github.com/NicoNex/echotron) - Library for Telegram Bots written in pure Go.
* [ephemeral-roles](https://github.com/ewohltman/ephemeral-roles) - A Discord bot for managing ephemeral roles based upon voice channel member presence.
* [go-chat-bot](https://github.com/go-chat-bot/bot) - IRC, Slack & Telegram bot written in Go.
* [go-joe](https://joe-bot.net) - A general-purpose bot library inspired by Hubot but written in Go.
* [go-sarah](https://github.com/oklahomer/go-sarah) - Framework to build bot for desired chat services including LINE, Slack, Gitter and more.
* [go-tgbot](https://github.com/olebedev/go-tgbot) - Pure Golang Telegram Bot API wrapper, generated from swagger file, session-based router and middleware.
* [go-twitch-irc](https://github.com/gempir/go-twitch-irc) - Libary to write bots for twitch.tv chat
* [Golang CryptoTrading Bot](https://github.com/saniales/golang-crypto-trading-bot) - A golang implementation of a console-based trading bot for cryptocurrency exchanges.
* [govkbot](https://github.com/nikepan/govkbot) - Simple Go [VK](https://vk.com) bot library.
* [hanu](https://github.com/sbstjn/hanu) - Framework for writing Slack bots.
* [Kelp](https://github.com/stellar/kelp) - official trading and market-making bot for the [Stellar](https://www.stellar.org/) DEX. Works out-of-the-box, written in Golang, compatible with centralized exchanges and custom trading strategies.
* [margelet](https://github.com/zhulik/margelet) - Framework for building Telegram bots.
* [micha](https://github.com/onrik/micha) - Go Library for Telegram bot api.
* [olivia](https://github.com/olivia-ai/olivia) - A chatbot built with an artificial neural network.
* [slack-bot](https://github.com/innogames/slack-bot) - Ready to use Slack Bot for lazy developers: Custom commands, Jenkins, Jira, Bitbucket, Github...
* [slacker](https://github.com/shomali11/slacker) - Easy to use framework to create Slack bots.
* [slackscot](https://github.com/alexandre-normand/slackscot) - Another framework for building Slack bots.
* [tbot](https://github.com/yanzay/tbot) - Telegram bot server with API similar to net/http.
* [telebot](https://github.com/tucnak/telebot) - Telegram bot framework written in Go.
* [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) - Simple and clean Telegram bot client.
* [Tenyks](https://github.com/kyleterry/tenyks) - Service oriented IRC bot using Redis and JSON for messaging.

## Build Automation

*Libraries and tools helping with build automation.*

* [1build](https://github.com/gopinath-langote/1build) - Command line tool to frictionlessly manage project-specific commands.
* [anko](https://github.com/GuilhermeCaruso/anko) - Simple application watcher for multiple programming languages.
* [gaper](https://github.com/maxcnunes/gaper) - Builds and restarts a Go project when it crashes or some watched file changes.
* [gilbert](https://go-gilbert.github.io) - Build system and task runner for Go projects.
* [goyek](https://github.com/goyek/goyek) - Create build pipelines in Go.
* [mmake](https://github.com/tj/mmake) - Modern Make.
* [realize](https://github.com/tockins/realize) - Go build system with file watchers and live reload. Run, build and watch file changes with custom paths.
* [Task](https://github.com/go-task/task) - simple "Make" alternative.
* [taskctl](https://github.com/taskctl/taskctl) - Concurrent task runner.

## Command Line

### Standard CLI

*Libraries for building standard or basic Command Line applications.*

* [argparse](https://github.com/akamensky/argparse) - Command line argument parser inspired by Python's argparse module.
* [argv](https://github.com/cosiner/argv) - Go library to split command line string as arguments array using the bash syntax.
* [cli](https://github.com/mkideal/cli) - Feature-rich and easy to use command-line package based on golang struct tags.
* [cli](https://github.com/teris-io/cli) - Simple and complete API for building command line interfaces in Go.
* [climax](http://github.com/tucnak/climax) - Alternative CLI with "human face", in spirit of Go command.
* [clîr](https://github.com/leaanthony/clir) - A Simple and Clear CLI library. Dependency free.
* [cmd](https://github.com/posener/cmd) - Extends the standard `flag` package to support sub commands and more in idomatic way.
* [cmdr](https://github.com/hedzr/cmdr) - A POSIX/GNU style, getopt-like command-line UI Go library.
* [cobra](https://github.com/spf13/cobra) - Commander for modern Go CLI interactions.
* [command-chain](https://github.com/rainu/go-command-chain) - A go library for configure and run command chains - such like pipelining in unix shells.
* [commandeer](https://github.com/jaffee/commandeer) - Dev-friendly CLI apps: sets up flags, defaults, and usage based on struct fields and tags.
* [complete](https://github.com/posener/complete) - Write bash completions in Go + Go command bash completion.
* [Dnote](https://github.com/dnote/dnote) - A simple command line notebook with multi-device sync.
* [elvish](https://github.com/elves/elvish) - An expressive programming language and a versatile interactive shell.
* [env](https://github.com/codingconcepts/env) - Tag-based environment configuration for structs.
* [flag](https://github.com/cosiner/flag) - Simple but powerful command line option parsing library for Go supporting subcommand.
* [flaggy](https://github.com/integrii/flaggy) - A robust and idiomatic flags package with excellent subcommand support.
* [flagvar](https://github.com/sgreben/flagvar) - A collection of flag argument types for Go's standard `flag` package.
* [go-andotp](https://github.com/grijul/go-andotp) - A CLI program to encrypt/decrypt [andOTP](https://github.com/andOTP/andOTP) files. Can be used as library as well.
* [go-arg](https://github.com/alexflint/go-arg) - Struct-based argument parsing in Go.
* [go-commander](https://github.com/yitsushi/go-commander) - Go library to simplify CLI workflow.
* [go-flags](https://github.com/jessevdk/go-flags) - go command line option parser.
* [go-getoptions](https://github.com/DavidGamba/go-getoptions) - Go option parser inspired on the flexibility of Perl’s GetOpt::Long.
* [gocmd](https://github.com/devfacet/gocmd) - Go library for building command line applications.
* [hiboot cli](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli) - cli application framework with auto configuration and dependency injection.
* [job](https://github.com/liujianping/job) - JOB, make your short-term command as a long-term job.
* [kingpin](https://github.com/alecthomas/kingpin) - Command line and flag parser supporting sub commands.
* [liner](https://github.com/peterh/liner) - Go readline-like library for command-line interfaces.
* [mitchellh/cli](https://github.com/mitchellh/cli) - Go library for implementing command-line interfaces.
* [mow.cli](https://github.com/jawher/mow.cli) - Go library for building CLI applications with sophisticated flag and argument parsing and validation.
* [ops](https://github.com/nanovms/ops) - Unikernel Builder/Orchestrator.
* [pflag](https://github.com/spf13/pflag) - Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags.
* [sand](https://github.com/Zaba505/sand) - Simple API for creating interpreters and so much more.
* [sflags](https://github.com/octago/sflags) - Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin and other libraries.
* [strumt](https://github.com/antham/strumt) - Library to create prompt chain.
* [ts](https://github.com/liujianping/ts) - Timestamp convert & compare tool.
* [ukautz/clif](https://github.com/ukautz/clif) - Small command line interface framework.
* [urfave/cli](https://github.com/urfave/cli) - Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli).
* [wlog](https://github.com/dixonwille/wlog) - Simple logging interface that supports cross-platform color and concurrency.
* [wmenu](https://github.com/dixonwille/wmenu) - Easy to use menu structure for cli applications that prompts users to make choices.

### Advanced Console UIs

*Libraries for building Console Applications and Console User Interfaces.*

* [asciigraph](https://github.com/guptarohit/asciigraph) - Go package to make lightweight ASCII line graph ╭┈╯ in command line apps with no other dependencies.
* [aurora](https://github.com/logrusorgru/aurora) - ANSI terminal colors that supports fmt.Printf/Sprintf.
* [box-cli-maker](https://github.com/Delta456/box-cli-maker) - Make Highly Customized Boxes for your CLI.
* [cfmt](https://github.com/mingrammer/cfmt) - Contextual fmt inspired by bootstrap color classes.
* [cfmt](https://github.com/i582/cfmt) - Simple and convenient formatted stylized output fully compatible with fmt library.
* [chalk](https://github.com/ttacon/chalk) - Intuitive package for prettifying terminal/console output.
* [colourize](https://github.com/TreyBastian/colourize) - Go library for ANSI colour text in terminals.
* [ctc](https://github.com/wzshiming/ctc) - The non-invasive cross-platform terminal color library does not need to modify the Print method.
* [go-ataman](https://github.com/workanator/go-ataman) - Go library for rendering ANSI colored text templates in terminals.
* [go-colorable](https://github.com/mattn/go-colorable) - Colorable writer for windows.
* [go-colortext](https://github.com/daviddengcn/go-colortext) - Go library for color output in terminals.
* [go-isatty](https://github.com/mattn/go-isatty) - isatty for golang.
* [go-prompt](https://github.com/c-bata/go-prompt) - Library for building a powerful interactive prompt, inspired by [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit).
* [gocui](https://github.com/jroimartin/gocui) - Minimalist Go library aimed at creating Console User Interfaces.
* [gommon/color](https://github.com/labstack/gommon/tree/master/color) - Style terminal text.
* [gookit/color](https://github.com/gookit/color) - Terminal color rendering tool library, support 16 colors, 256 colors, RGB color rendering output, compatible with Windows.
* [marker](https://github.com/cyucelen/marker) - Easiest way to match and mark strings for colorful terminal outputs.
* [mpb](https://github.com/vbauerster/mpb) - Multi progress bar for terminal applications.
* [progressbar](https://github.com/schollz/progressbar) - Basic thread-safe progress bar that works in every OS.
* [pterm](https://github.com/pterm/pterm) - A library to beautify console output on every platform with many combinable components.
* [simpletable](https://github.com/alexeyco/simpletable) - Simple tables in terminal with Go.
* [tabby](https://github.com/cheynewallace/tabby) - A tiny library for super simple Golang tables.
* [table](https://github.com/tomlazar/table) - Small library for terminal color based tables .
* [tabular](https://github.com/InVisionApp/tabular) - Print ASCII tables from command line utilities without the need to pass large sets of data to the API.
* [termbox-go](https://github.com/nsf/termbox-go) - Termbox is a library for creating cross-platform text-based interfaces.
* [termdash](https://github.com/mum4k/termdash) - Go terminal dashboard based on **termbox-go** and inspired by [termui](https://github.com/gizak/termui).
* [termenv](https://github.com/muesli/termenv) - Advanced ANSI style & color support for your terminal applications
* [termui](https://github.com/gizak/termui) - Go terminal dashboard based on **termbox-go** and inspired by [blessed-contrib](https://github.com/yaronn/blessed-contrib).
* [uilive](https://github.com/gosuri/uilive) - Library for updating terminal output in realtime.
* [uiprogress](https://github.com/gosuri/uiprogress) - Flexible library to render progress bars in terminal applications.
* [uitable](https://github.com/gosuri/uitable) - Library to improve readability in terminal apps using tabular data.
* [yacspin](https://github.com/theckman/yacspin) - Yet Another CLi Spinner package, for working with terminal spinners.

