Awesome SBT Plugins
===================

List of awesome [sbt](http://www.scala-sbt.org/) plugins

## Table of Contents

<!-- MarkdownTOC depth=4 -->

 - [IDE](#ide)
 - [Source](#source)
 - [Test & QA](#test--qa)
 - [Documentation](#documentation)
 - [Build & release](#build--release)
 - [Web](#web)
 - [Mobile](#mobile)
 - [DB](#db)
 - [Other](#other)

<!-- /MarkdownTOC -->

##IDE
1. [sbt-idea](https://github.com/mpeltonen/sbt-idea) -  A simple-build-tool (sbt) plugin/processor for creating IntelliJ IDEA project files
1. [sbteclipse](https://github.com/typesafehub/sbteclipse) -  Plugin for sbt to create Eclipse project definitions
1. [sbt-sublime](https://github.com/orrsella/sbt-sublime) -  An sbt pluign for generating Sublime Text projects with library dependencies sources
1. [sbt-ensime](http://ensime.github.io/build_tools/sbt/) - Sbt plugin for the [ENSIME](http://ensime.github.io/) language server, so that you can integrate IDE features into your favorite editor.


##SOURCE
1. [sbt-stats](https://github.com/orrsella/sbt-stats) -  An sbt plugin for source code statistics
1. [np](https://github.com/softprops/np) -  new sbt project generation made simple(r)
1. [sbt-properties](https://github.com/sbt/sbt-properties) -  sbt plugin to read properties from a file and make them available as a map
1. [sbt-pack](https://github.com/xerial/sbt-pack) -  A sbt plugin for creating distributable Scala packages.
1. [sbt-cross-building](https://github.com/jrudolph/sbt-cross-building/) -  Enable cross-building of sbt plugins
1. [sbt-dependency-graph](https://github.com/jrudolph/sbt-dependency-graph) -  sbt plugin to create a dependency graph for your project
1. [sbt-buildinfo](https://github.com/sbt/sbt-buildinfo) -  I know this because build.sbt knows this.


##TEST & QA
1. [jacoco4sbt](https://github.com/sbt/jacoco4sbt) -  JaCoCo Code Coverage plug-in for sbt.
1. [sbt-scoverage](https://github.com/scoverage/sbt-scoverage#coveralls) -  sbt plugin for scoverage
1. [sbt-scalariform](https://github.com/sbt/sbt-scalariform) -  sbt plugin adding support for source code formatting using Scalariform
1. [cpd4sbt](https://github.com/sbt/cpd4sbt) -  Integrating PMD's Copy/Paste Detector into SBT as a plug-in.
1. [scalastyle-sbt-plugin](https://github.com/scalastyle/scalastyle-sbt-plugin) -  scalastyle-sbt-plugin
1. [WartRemover](https://github.com/puffnfresh/wartremover) - Flexible Scala code linting tool


##DOCUMENTATION
1. [sbt-site](https://github.com/sbt/sbt-site) -  Site generation for SBT
1. [sbt-ghpages](https://github.com/sbt/sbt-ghpages) -  git, site and ghpages support for XSBT projects.
1. [sbt-unidoc](https://github.com/sbt/sbt-unidoc) -  sbt plugin to create a unified API document across projects
1. [sbt-man](https://github.com/sbt/sbt-man) -  Looks up scaladoc.
1. [sbt-mustache](https://github.com/michaeldfallen/sbt-mustache) -  SBT plugin for using mustache.java in scala projects
1. [Soapbox](https://github.com/arnolddevos/Soapbox) -  Static site generator as an SBT plugin


##BUILD & RELEASE
1. [partial-sbt](https://github.com/elarib/partial-sbt) - A SBT plugin that enable partial build, depending on what change between two git branch
1. [sbt-release](https://github.com/sbt/sbt-release) -  A release plugin for sbt (>= 0.11.0)
1. [sbt-maven-plugin](https://github.com/shivawu/sbt-maven-plugin) -  A sbt plugin which reads project definitions from pom.xml
1. [sbt-assembly](https://github.com/sbt/sbt-assembly) -  Deploy fat JARs. Restart processes. (port of codahale/assembly-sbt)
1. [sbt-native-packager](https://github.com/sbt/sbt-native-packager) - The goal is to be able to bundle up Scala software built with SBT for native packaging systems, like deb, rpm, homebrew, msi.
1. [sbt-izpack](http://software.clapper.org/sbt-izpack/) -  is a plugin for the Scala-based SBT build tool (version 0.10.x or better). IzPack is an open source tool that allows you to create flexible Java-based graphical and command-line installers. This plugin allows you to use IzPack directly from your SBT 0.10.x project.
1. [sbt-unique-version](https://github.com/sbt/sbt-unique-version) -  emulates Maven's uniqueVersion snapshots
1. [sbt-docker](https://github.com/marcuslonnberg/sbt-docker) -  Create Docker images directly from sbt
1. [sbt-aether-deploy](https://github.com/arktekk/sbt-aether-deploy) -  Deploy SBT artifacts using Eclipse Aether
1. [sbt-git](https://github.com/sbt/sbt-git) -  A git plugin for SBT
1. [sbt-revolver](https://github.com/spray/sbt-revolver) - An SBT plugin for dangerously fast development turnaround in Scala
1. [sbt-onejar](https://github.com/sbt/sbt-onejar) - Packages your project using One-JAR™
1. [sbt-start-script](https://github.com/sbt/sbt-start-script) - SBT Plugin to create a "start" script to run the program


##WEB
1. [sbt-plugins](https://github.com/untyped/sbt-plugins) -  SBT plugins for: Less CSS / JS compilation, Lift run modes, and more.
1. [less-sbt](https://github.com/softprops/less-sbt) -  type less css in your sbt projects
1. [sbt-web](https://github.com/sbt/sbt-web) - This project provides the building blocks for web oriented sbt plugins
    * [sbt-autoprefixer](https://github.com/matthewrennie/sbt-autoprefixer)
    * [sbt-closure](https://github.com/ground5hark/sbt-closure#sbt-closure)
    * [sbt-coffeescript](https://github.com/sbt/sbt-coffeescript#sbt-coffeescript)
    * [sbt-coffeescript-reactjs](https://github.com/ShaggyYeti/sbt-coffeescript-reactjs)
    * [sbt-concat](https://github.com/ground5hark/sbt-concat#sbt-concat)
    * [sbt-css-compress](https://github.com/ground5hark/sbt-css-compress#sbt-css-compress)
    * [sbt-digest](https://github.com/sbt/sbt-digest#sbt-digest)
    * [sbt-dustjs-linkedin](https://github.com/jmparsons/sbt-dustjs-linkedin)
    * [sbt-emberjs](https://github.com/dwickern/sbt-emberjs)
    * [sbt-filter](https://github.com/rgcottrell/sbt-filter)
    * [sbt-gzip](https://github.com/sbt/sbt-gzip#sbt-gzip)
    * [sbt-handlebars](https://github.com/Amadeus82/sbt-handlebars)
    * [sbt-hbs](https://github.com/bicouy0/sbt-hbs)
    * [sbt-html-js-wrap](https://github.com/kolloch/sbt-html-js-wrap)
    * [sbt-html-minifier](https://github.com/rgcottrell/sbt-html-minifier)
    * [sbt-imagemin](https://github.com/rgcottrell/sbt-imagemin)
    * [sbt-jshint](https://github.com/sbt/sbt-jshint#sbt-jshint)
    * [sbt-jst](https://github.com/matthewrennie/sbt-jst)
    * [sbt-less](https://github.com/sbt/sbt-less#sbt-less)
    * [sbt-mocha](https://github.com/sbt/sbt-mocha)
    * [sbt-purescript](https://github.com/eamelink/sbt-purescript)
    * [sbt-reactjs](https://github.com/ddispaltro/sbt-reactjs)
    * [sbt-rjs](https://github.com/sbt/sbt-rjs#sbt-rjs)
    * [sbt-sass](https://github.com/ShaggyYeti/sbt-sass)
    * [sbt-simple-url-update](https://github.com/neomaclin/sbt-simple-url-update#sbt-simple-url-update)
    * [sbt-stylus](https://github.com/sbt/sbt-stylus)
    * [sbt-traceur](https://github.com/arielscarpinelli/sbt-traceur)
    * [sbt-uglify](https://github.com/sbt/sbt-uglify)
    * [sbt-js-beautify](https://github.com/meloniasty/sbt-js-beautify)
1. [sbt-js-engine](https://github.com/sbt/sbt-js-engine) - This plugin mainly provides support for the authoring of sbt plugins that require js-engine.
1. [xsbt-web-plugin](https://github.com/earldouglas/xsbt-web-plugin) -  Build J2EE Web applications in Scala.


##MOBILE
1. [android-plugin](https://github.com/jberkel/android-plugin) -  An sbt plugin for Android development in Scala


##DB
1. [sbt-liquibase](https://github.com/bigtoast/sbt-liquibase) -  liquibase plugin for sbt 0.11+ / 0.12
1. [sbt-lwm](http://software.clapper.org/sbt-lwm/) -  (Light Weight Markup) is an SBT 0.11.x plugin that converts lightweight markup documents to HTML. It currently supports Textile and Markdown.

#OTHER
1. [sbt-growl](https://github.com/freekh/sbt-growl) - kinda growl notifier
1. [sbt-scalabuff](https://github.com/sbt/sbt-scalabuff) -  SBT plugin which generate case classes and support for serialization from Google Protocol Buffer definitions using ScalaBuff
1. [sbt-updates](https://github.com/rtimush/sbt-updates) -  SBT plugin that can check maven repositories for dependency updates
1. [sbt-prompt](https://github.com/agemooij/sbt-prompt) -  An SBT plugin for making your SBT prompt more awesome
1. [ls-sbt](https://github.com/softprops/ls) - a card calalog for scala libraries
1. [sbt-cpp](https://github.com/d40cht/sbt-cpp) -  Sbt plugin to allow native compilation of C and C++
1. [sbt-atmos](https://github.com/sbt/sbt-atmos) -  sbt plugin for running Typesafe Console in development
1. [ScalaKata](https://github.com/MasseGuillaume/ScalaKata) - Interactive Playground / Literate Programming for Scala — http://scalakata.com
