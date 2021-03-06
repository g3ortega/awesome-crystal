# Awesome Crystal [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/veelenga/awesome-crystal.svg)](https://travis-ci.org/veelenga/awesome-crystal)

A curated list of awesome Crystal code and resources. Inspired by [awesome](https://github.com/sindresorhus/awesome) and [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness).

The goal is to have projects mostly stable and useful for users.

Contributions are welcome. Please take a quick look at the [contribution guidelines](https://github.com/veelenga/awesome-crystal/blob/master/CONTRIBUTING.md) first.

* [Awesome Crystal](#awesome-crystal)
  * [Algorithms and Data structures](#algorithms-and-data-structures)
  * [Api Builders](#api-builders)
  * [Caching](#caching)
  * [Cli Builders](#cli-builders)
  * [Configuration](#configuration)
  * [Data Generators](#data-generators)
  * [Database Drivers](#database-drivers)
  * [Database Tools](#database-tools)
  * [Environment Management](#environment-management)
  * [Examples and funny stuff](#examples-and-funny-stuff)
  * [Framework Components](#framework-components)
  * [HTTP](#http)
  * [Implementations/Compilers](#implementationscompilers)
  * [Logging and monitoring](#logging-and-monitoring)
  * [Low level bindings](#low-level-bindings)
  * [Misc](#misc)
  * [Networking](#networking)
  * [ORM/ODM Extensions](#ormodm-extensions)
  * [Package Management](#package-management)
  * [Project generators](#project-generators)
  * [Queue](#queue)
  * [Search](#search)
  * [Task management](#task-management)
  * [Template Engine](#template-engine)
  * [Testing](#testing)
  * [Third-party APIs](#third-party-apis)
  * [Virtualization](#virtualization)
  * [Web Frameworks](#web-frameworks)
  * [Web Servers](#web-servers)
* [Community](#community)
* [Resources](#resources)
* [Services and Apps](#services-and-apps)
* [Tools](#tools)
  * [DevOps](#devops)
  * [Editor Plugins](#editor-plugins)
  * [Shell Plugins](#shell-plugins)

## Algorithms and Data structures
 * [crystalline](https://github.com/jtomschroeder/crystalline) - A collection of containers and algorithms
 * [delimiter_tree](https://github.com/drujensen/delimiter_tree) - A tree structure that is built using a delimiter
 * [heap.cr](https://github.com/chenkovsky/heap.cr) - Implementation of heap data structure
 * [miller_rabin](https://github.com/kuende/miller_rabin) - Implements [Miller-Rabin](https://en.wikibooks.org/wiki/Algorithm_Implementation/Mathematics/Primality_Testing) algorithm to check if a number is prime
 * [multiset.cr](https://github.com/tcrouch/multiset.cr) - Implementation of a multiset
 * [murmur3](https://github.com/kuende/murmur3) - Implementation of Murmur3 hash algorithm used by Cassandra
 * [primes](https://github.com/dkhofer/primes) - Library for testing if a number is prime and finding its prime factorization
 * [radix](https://github.com/luislavena/radix) - Radix Tree implementation

## Api Builders
 * [crystal_api](https://github.com/akwiatkowski/crystal_api) - Simple PostgreSQL REST API with Rails devise-like auth

## Caching
 * [Bloom Filter](https://github.com/greyblake/crystal-bloom_filter) - Implementation of Bloom filter
 * [crystal-memcached](https://github.com/comandeo/crystal-memcached) - Implementation of a memcached client

## Cli Builders
 * [commander](https://github.com/mrrooijen/commander) - Command-line interface builder
 * [completion](https://github.com/f/completion) - Easy command line completion engine
 * [docopt](https://github.com/chenkovsky/docopt.cr) - A [docopt.org](http://docopt.org) port
 * [optarg](https://github.com/mosop/optarg) - Yet another library for parsing command-line options and arguments

## Configuration
 * [ambience](https://github.com/vjdhama/ambience) - Simple app configuration using `ENV`.
 * [crystal-toml](https://github.com/manastech/crystal-toml) - TOML parser

## Data Generators
 * [faker](https://github.com/askn/faker) - A library for generating fake data

## Database Drivers
 * [crystal-monetdb-libmapi](https://github.com/puppetpies/crystal-monetdb-libmapi) - Bindings for MonetDB
 * [crystal-mysql](https://github.com/waterlink/crystal-mysql) - Basic MySQL bindings
 * [crystal-pg](https://github.com/will/crystal-pg) - A Postgres driver
 * [crystal-redis](https://github.com/stefanwille/crystal-redis) - Full featured Redis client
 * [crystal-sqlite3](https://github.com/manastech/crystal-sqlite3) - SQLite3 bindings
 * [influxdb.cr](https://github.com/jeromegn/influxdb.cr) - InfluxDB driver
 * [mongo.cr](https://github.com/datanoise/mongo.cr) - Binding for MongoDB C driver
 * [rethinkdb-crystal](https://github.com/lbguilherme/rethinkdb-crystal) - RethinkDB Driver

## Database Tools
 * [micrate](https://github.com/juanedi/micrate) - Database migration tool

## Environment Management
 * [crenv](https://github.com/pine/crenv) - Crystal version manager
 * [Snappy](https://github.com/shotastage/Snappy) - Version manager for Swift, Ruby, Python and so on

## Examples and funny stuff
 * [crsfml-examples](https://github.com/BlaXpirit/crsfml-examples) - Simple games made with CrSFML
 * [crystal-patterns](https://github.com/veelenga/crystal-patterns) - Examples of GOF patters
 * [crystal_samples](https://github.com/tbpgr/crystal_samples) - Variety of Crystal samples
 * [crystalized_ruby](https://github.com/phoffer/crystalized_ruby) - Native Ruby extensions written in Crystal
 * [docker-kemal](https://github.com/ianblenke/docker-kemal) - An example Dockerized Crystal Kemal project
 * [kemal-chat](https://github.com/sdogruyol/kemal-chat) - Build realtime applications with Kemal and WebSocket
 * [kemal-pg-sample](https://github.com/sdogruyol/kemal-pg-sample) - Sample app to demonstrate kemal + postgresql usage
 * [kemal-react-chat](https://github.com/f/kemal-react-chat) - Build Realtime Web applications with Kemal and React
 * [xcrystal](https://github.com/exercism/xcrystal) - Exercism exercises

## Framework Components
 * [artanis](https://github.com/ysbaddaden/artanis) - Sinatra-like DSL (abusing macros)
 * [crouter](https://github.com/jreinert/crouter) - A standalone router
 * [crystal-mime](https://github.com/spalger/crystal-mime) - Mimetypes for Crystal
 * [kemal-comments](https://github.com/TyanNN/kemal-comments) - Simple comments for Kemal site
 * [kemal-mysql](https://github.com/sdogruyol/kemal-mysql) - Easily add MySQL database to Kemal
 * [kemal-pg](https://github.com/sdogruyol/kemal-pg) - Easily add Postgresql database to Kemal
 * [kemal-redis](https://github.com/sdogruyol/kemal-redis) - Easily add Redis to Kemal
 * [kemal-session](https://github.com/Thyra/kemal-session) - Session handler for Kemal
 * [spec-kemal](https://github.com/sdogruyol/spec-kemal) - Easy testing for Kemal

## HTTP
 * [beryl](https://github.com/luislavena/beryl) - Action-focused HTTP routing library
 * [crul](https://github.com/porras/crul) - Command line HTTP client
 * [cryload](https://github.com/Sdogruyol/cryload) - HTTP benchmarking tool
 * [crystal-routing](https://github.com/bcardiff/crystal-routing) - Extensible library to deal with http request and string based routing
 * [helmet](https://github.com/EvanHahn/crystal-helmet) - Set security-related HTTP headers
 * [http2](https://github.com/ysbaddaden/http2) - HTTP/2 Protocol Implementation
 * [http_parser.cr](https://github.com/kostya/http_parser.cr) - Wrapper for [Http Parser lib](https://github.com/nodejs/http-parser)
 * [router-simple.cr](https://github.com/karupanerura/router-simple.cr) - Simple path router
 * [session](https://github.com/porras/session.git) - Cookie based sessions in Crystal HTTP applications

## Implementations/Compilers
 * [crisp](https://github.com/rhysd/Crisp) - Lisp dialect implemented with Crystal
 * [crystal](https://github.com/manastech/crystal) - Crystal itself is written in Crystal
 * [onix](https://github.com/ozra/onyx-lang) - ONYX Programming Language

## Logging and monitoring
 * [gelf-crystal](https://github.com/benoist/gelf-crystal) - A GELF logger
 * [syslog.cr](https://github.com/comandeo/syslog.cr) - Implementation of Syslog client

## Low level bindings
 * [crsfml](https://github.com/BlaXpirit/crsfml) - Bindings for [Simple and Fast Multimedia Library](http://www.sfml-dev.org/) (through CSFML)
 * [crystal-dbus](https://github.com/BlaXpirit/crystal-dbus) - Bindings to D-Bus
 * [curses](https://github.com/ruivieira/curses) - Bindings for the curses library
 * [duktape.cr](https://github.com/jessedoyle/duktape.cr) - Bindings for the [Duktape](https://github.com/svaarala/duktape) javascript engine
 * [kt](https://github.com/kuende/kt) - Bindings for [Kyoto Tycoon](http://fallabs.com/kyototycoon/)
 * [libnotify.cr](https://github.com/splattael/libnotify.cr) - Bindings for Libnotify
 * [libui.cr](https://github.com/Fusion/libui.cr) - Bindings for [libui](https://github.com/andlabs/libui)
 * [myhtml](https://github.com/kostya/myhtml) - Bindings for [lexborisov/myhtml](https://github.com/lexborisov/myhtml)
 * [openssl.cr](https://github.com/datanoise/openssl.cr) - Bindings for OpenSSL library
 * [posix](https://github.com/ysbaddaden/posix) - POSIX/C bindings
 * [snappy-crystal](https://github.com/benoist/snappy-crystal) - Bindings for Snappy library
 * [ssh2.cr](https://github.com/datanoise/ssh2.cr) - Bindings for libssh2 library
 * [termbox-crystal](https://github.com/andrewsuzuki/termbox-crystal) - Bindings and extension library for [termbox](https://github.com/nsf/termbox) (terminal UI library)
 * [zeromq-crystal](https://github.com/benoist/zeromq-crystal) - Bindings for ZeroMQ
 * [zlib.cr](https://github.com/datanoise/zlib.cr) - Bindings for ZLib library

## Misc
 * [aasm.cr](https://github.com/veelenga/aasm.cr) - Easy to use finite state machine for Crystal classes
 * [chalk-box](https://github.com/azukiapp/crystal-chalk-box) - Terminal color toolbox, check support and colorized (without String monkey patch)
 * [circuit_breaker](https://github.com/TPei/circuit_breaker) - Implementation of the circuit breaker pattern
 * [crdoc](https://github.com/rhysd/crdoc) - CLI tool to search and open documentation
 * [cron_scheduler](https://github.com/kostya/cron_scheduler) - Job scheduler with crontab patterns
 * [crystal-diff](https://github.com/MakeNowJust/crystal-diff) - A Crystal sequence differencing implementation
 * [crystal-futures](https://github.com/dhruvrajvanshi/crystal-futures) - Future type implementation
 * [crystal-i18n](https://github.com/whity/crystal-i18n) - Internationalization library
 * [CrystalEmail](https://github.com/Nephos/CrystalEmail) - A RFC compliant Email validator
 * [daemonize.cr](https://github.com/DougEverly/daemonize.cr) - Crystal process daemonizer
 * [emoji.cr](https://github.com/veelenga/emoji.cr) - Emoji library
 * [evented](https://github.com/krisleech/evented) - A micro library to publish and subscribe for Crystal objects
 * [guardian](https://github.com/f/guardian) - File change watcher for Crystal and Non-Crystal libs
 * [haikunator](https://github.com/sanata-/haikunator) - Heroku-like random name generator
 * [html_builder](https://github.com/crystal-lang/html_builder) - DSL for creating HTML
 * [immutable](https://github.com/lucaong/immutable) - Implementation of thread-safe, persistent, immutable collections
 * [kreal](https://github.com/f/kreal) - Model sharing & RPC library built on and works with Kemal seamlessly
 * [lambda.cr](https://github.com/f/lambda.cr) - Uniformed function call syntax
 * [progress](https://github.com/askn/progress) - [==..] Progress bar
 * [raytracer-crystal](https://github.com/l3kn/raytracer-crystal) - CPU Raytracer with examples
 * [spinner](https://github.com/askn/spinner) - Terminal Spinner
 * [statsd.cr](https://github.com/miketheman/statsd.cr) - [Statsd](https://github.com/etsy/statsd) client library
 * [syscall.cr](https://github.com/kubo39/syscall.cr) - Raw syscall interface

## Networking
 * [amqp.cr](https://github.com/datanoise/amqp.cr) - AMQP 0.9.1 client with RabbitMQ extensions
 * [bson.cr](https://github.com/jeromegn/bson.cr) - Native BSON implementation
 * [jwt](https://github.com/greyblake/crystal-jwt) - Implementation of JWT (JSON Web Token)
 * [msgpack-crystal](https://github.com/benoist/msgpack-crystal) - MessagePack library

## ORM/ODM Extensions
 * [active_record.cr](https://github.com/waterlink/active_record.cr) - Active Record pattern implementation
 * [amethyst-model](https://github.com/drujensen/amethyst-model) - ORM Model for the Amethyst Framework
 * [ohm-crystal](https://github.com/soveran/ohm-crystal) - Object-hash mapping library for Redis
 * [redis-tsv.cr](https://github.com/maiha/redis-tsv.cr) - Import and export data from Redis in TSV format

## Package Management
 * [shards](https://github.com/ysbaddaden/shards) - Dependency manager for the Crystal

## Project generators
 * [generate](https://github.com/generate-cr/generate) - A tool for generating whole Crystal project structure, or any part of it during lifetime of project

## Queue
 * [crystal-resque-client](https://github.com/pine/crystal-resque-client) - Simple Resque queue client
 * [sidekiq.cr](https://github.com/mperham/sidekiq.cr) - Simple, efficient job processing

## Search
 * [soegen](https://github.com/Ragmaanir/soegen) - Elasticsearch client for Crystal similar to the stretcher gem for ruby

## Task management
 * [crake](https://github.com/MakeNowJust/crake) - Rake-like build utility library. It is just a library, so it does not provide CLI
 * [lake](https://github.com/adlerhsieh/lake) - Rake-like task management for Crystal programs

## Template Engine
 * [Bunny](https://github.com/samsheff/Bunny) - A simple HTML templating language for Crystal, same syntax as erb
 * [crustache](https://github.com/MakeNowJust/crustache) - [{{Mustache}}](https://mustache.github.io) for Crystal
 * [Kilt](https://github.com/jeromegn/kilt) - Abstraction layer for template engines.
 * [Slang](https://github.com/jeromegn/slang) - Lightweight, terse, templating language inspired by Ruby's Slim.
 * [temel](https://github.com/f/temel) - Extensible HTML::Builder alternative for Crystal, supports custom tag definitions

## Testing
 * [crotest](https://github.com/emancu/crotest) - A tiny and simple test framework
 * [matchi](https://github.com/fixcr/matchi) - Collection of expectation matchers
 * [minitest.cr](https://github.com/ysbaddaden/minitest.cr) - Library for unit tests and assertions
 * [mock](https://github.com/porras/mock) - Mocking library, inspired by the API of rspec-mocks
 * [mocks.cr](https://github.com/waterlink/mocks.cr) - Mocking library for Crystal
 * [power_assert.cr](https://github.com/rosylilly/power_assert.cr) - Powerful assertion for Crystal
 * [spec2.cr](https://github.com/waterlink/spec2.cr) - Enhanced testing library
 * [timecop.cr](https://github.com/waterlink/timecop.cr) - Library for mocking with `Time.now`. Inspired by [timecop ruby gem](https://github.com/travisjeffery/timecop)
 * [webmock.cr](https://github.com/manastech/webmock.cr) - Library for stubbing `HTTP::Client` requests

## Third-party APIs
 * [airbrake-crystal](https://github.com/kyrylo/airbrake-crystal) - A Crystal notifier for [Airbrake](https://airbrake.io)
 * [AnyBar_cr](https://github.com/davydovanton/AnyBar_cr) - Simple crystal wrapper for AnyBar library
 * [crystal-qiita](https://github.com/pine/crystal-qiita) - A wrapper for the [Qiita](https://qiita.com/) API
 * [crystal_brium](https://github.com/manastech/crystal_brium) - Access Brium's API using Crystal
 * [crystal_slack](https://github.com/manastech/crystal_slack) - A tool that parses Slack slash commands or send incoming web hooks
 * [docker.cr](https://github.com/jeromegn/docker.cr) - Docker API client
 * [fantasy_football_nerd_api](https://github.com/fridgerator/fantasy_football_nerd_api) - A library for the [Fantasy Football Nerd API](http://www.fantasyfootballnerd.com/fantasy-football-api)
 * [glosbe](https://github.com/greyblake/crystal-glosbe) - Client for [Glosbe API](https://glosbe.com/a-api)
 * [google_maps_api](https://github.com/fridgerator/google_maps_api) - Google Maps API
 * [google_translate](https://github.com/greyblake/crystal-google_translate) - Client for Google Translate
 * [gravatar.cr](https://github.com/fg/gravatar.cr.git) - A library to use Gravatar service
 * [openweather.cr](https://github.com/lucasocon/openweather.cr) - A wrapper for the Openweather API
 * [shorturl.cr](https://github.com/veelenga/shorturl.cr) - A library to use URL shortening services
 * [soundcloud-crystal](https://github.com/sferik/soundcloud-crystal) - A library to access the SoundCloud API
 * [spotify.cr](https://github.com/marceloboeira/spotify.cr) - A library to access the Spotify API
 * [TelegramBot](https://github.com/hangyas/TelegramBot) - A wrapper for the Telegram Bot API
 * [twitter-crystal](https://github.com/sferik/twitter-crystal) - A library to access the Twitter API
 * [wit-crystal](https://github.com/spalladino/wit-crystal) - Crystal SDK for [wit.ai](https://wit.ai/)

## Virtualization
 * [rcpu](https://github.com/ddfreyne/rcpu) - A virtual machine emulator and assembler

## Web Frameworks
 * [amatista](https://github.com/werner/amatista) - A web framework to create quick applications
 * [amethyst](https://github.com/Codcore/Amethyst) - A Rails inspired web-framework
 * [carbon-crystal](https://github.com/benoist/carbon-crystal) - A framework with Rails in mind
 * [chocolate](https://github.com/Grabli66/chocolate) - Simple web framework and template engine
 * [frost](https://github.com/ysbaddaden/frost) - Full featured MVC Web Framework, largely inspired by Ruby on Rails
 * [iceberg](https://github.com/adlerhsieh/iceberg) - A full-stack web framework
 * [kemal](https://github.com/sdogruyol/kemal) - Lightning Fast, Super Simple web framework. Inspired by Sinatra
 * [kemalyst](https://github.com/drujensen/kemalyst) - A rails like framework based on kemal
 * [moonshine](https://github.com/dhruvrajvanshi/Moonshine) - A minimal web framework

## Web Servers
 * [fast-http-server](https://github.com/sdogruyol/fast-http-server) - Super fast, zero configuration command line HTTP Server.
 * [kamber](https://github.com/f/kamber) - Blog server based on Kemal
 * [prax.cr](https://github.com/ysbaddaden/prax.cr) - Rack proxy server for development

# Community
 * [Crystal Shards on Twitter](https://twitter.com/shardscrystal)
 * [Crystal weekly newsletters](http://www.crystalweekly.com/)
 * [Google Group](https://groups.google.com/forum/?fromgroups#!forum/crystal-lang)
 * [IRC](http://irc.lc/freenode/crystal-lang) - #crystal-lang on Freenode
 * [Reddit](https://www.reddit.com/r/crystal_programming)
 * [Slack Group](http://crystal.pine.moe/en/)
 * [Stackoverflow](http://stackoverflow.com/tags/crystal-lang/info)

# Resources
 * [crystal-lang.org](http://crystal-lang.org) - Official language site

# Services and Apps
 * [carc.in](https://carc.in/) - A web service that runs your code and displays the result
 * [Crank](https://github.com/arktisklada/crank) - A Procfile-based application manager (like Foreman)
 * [crystalshards](https://crystalshards.herokuapp.com/) - A web service that lists all available Crystal shards
 * [DeBot](https://github.com/jhass/DeBot) - IRC bot written in Crystal
 * [docrystal](http://docrystal.org/) - A web application that hosts documentation for Crystal packages
 * [fikri](https://github.com/askn/fikri) - Simple CLI To-Do App
 * [icr](https://github.com/greyblake/crystal-icr) - Interactive console for Crystal (like IRB for Ruby)
 * [nes](https://github.com/romeroadrian/nes.cr) - A NES emulator
 * [vicr](https://github.com/veelenga/vicr.git) - Vim-like Interactive CRystal

# Tools

## DevOps
 * [crystal-cookbook](https://github.com/vjdhama/crystal-cookbook) - Chef cookbook for installing crystal

## Editor Plugins
 * Atom
   * [crystal-tools](https://atom.io/packages/crystal-tools) - Enables built in tools in Crystal compiler
   * [language-crystal-actual](https://atom.io/packages/language-crystal-actual) - Crystal language support in Atom
   * [linter-crystal](https://atom.io/packages/linter-crystal) - Lint Crystal using the Crystal compiler in Atom
 * Emacs
   * [emacs-crystal-mode](https://github.com/jpellerin/emacs-crystal-mode) - Crystal language support for Emacs
 * Sublime
   * [sublime-crystal](https://github.com/manastech/sublime-crystal) - Crystal syntax highlighting for sublime Text
 * Vim
   * [vim-crystal](https://github.com/rhysd/vim-crystal) - Vim filetype support for Crystal
   * [vim-slang](https://github.com/isaacsloan/vim-slang) - Vim filetype support for Slang Templating Engine
 * Visual Studio Code
   * [vscode-crystal](https://github.com/g3ortega/vscode-crystal) - Crystal language support in VSCode

## Shell plugins
 * [crystal-zsh](https://github.com/veelenga/crystal-zsh) - .oh-my-zsh plugin
