# Cloudnloud Tech Community - Onboarding Document

Table of contents
=================

<!--ts-->
   * [Introduction](#introduction)
   * [About Cloudnloud Tech Community](#about-Cloudnloud-Tech-Community)
      * [Why we are gathered](#why-we-are-gathered)
      * [Why projection is needed](#Why-projection-is-needed)
      * [What is the advantages if you project yourself?](#What-is-the-advantages-if-you-project-yourself)
      * [What is the advantages’ if you write a blogging?](#What-is-the-advantages-if-you-write-a-blogging)
      * [What is the advantage if you present via live stream across world?](#What-is-the-advantage-if-you-present-via-live-stream-across-world)
      * [What is the advantage if you present physical technical meetups?](#What-is-the-advantage-if-you-present-physical-technical-meetups)
      * [What is the normal IT path?](#What-is-the-normal-IT-path)
      * [What if you create visibility and via visibility what you can get easily?](#What-if-you-create-visibility-and-via-visibility-what-you-can-get-easily)
	  * [Along with your growth what is the contribution you need to give back to the society via Cloudnloud Tech Community?](#Along-with-your-growth-what-is-the-contribution-you-need-to-give-back-to-the-society-via-Cloudnloud-Tech-Community)
   * [Cloudnloud Tech Community - Stages](#Cloudnloud-Tech-Community-Stages)
   * [Career Discussion – One on one – With Vijay](#Career-Discussion–One-on-one–With-Vijay)
   * [Pre-requisites](#pre-requisites)
      * [Environment Needed](#Why-we-are-gathered)
      * [Login – Need to be created](#Login–Need-to-be-created)
      * [Canva – Poster Creation](#Canva–Poster-Creation)
      * [Make your Linkedin Ready](#Make-your-Linkedin-Ready)
   * [Stage 1 – Create Your Monopoly Visibility](#Stage-1–Create-Your-Monopoly-Visibility)
      * [Stage 1 - Linkedin Posts](#Stage-1-Linkedin-Posts)
      * [Stage 1 - HASHNODE- Blogging](#Stage-1-HASHNODE-Blogging)
      * [Stage 1 - Linkedin Article](#Stage-1-Linkedin-Article)
   * [Stage 2 – You reach Worldwide](#Stage-2–You-reach-Worldwide)
      * [Stage 2 – Video Creation](#Stage-2–Video-Creation)
      * [Stage 2 – Meetup - Online](#Stage-2–Meetup-Online)
      * [Stage 2 – Meetup - Physical](#Stage-2–Meetup-Physical)   
   * [Stage 3 – Ambassador Programs and International Conferences](#Stage-3–Ambassador-Programs-and-International-Conferences)

<!--te-->


What is the normal IT path?
What if you create visibility and via visibility what you can get easily?
Along with your growth what is the contribution you need to give back to the society via Cloudnloud Tech Community?

Introduction
============



About Cloudnloud Tech Community
=====


Why we are gathered
-----

Here's an example of TOC creating for markdown from STDIN:

```bash
➥ cat ~/projects/Dockerfile.vim/README.md | ./gh-md-toc -
  * [Dockerfile.vim](#dockerfilevim)
  * [Screenshot](#screenshot)
  * [Installation](#installation)
        * [OR using Pathogen:](#or-using-pathogen)
        * [OR using Vundle:](#or-using-vundle)
  * [License](#license)
```

Local files
-----------

Here's an example of TOC creating for a local README.md:

```bash
➥ ./gh-md-toc ~/projects/Dockerfile.vim/README.md


Table of Contents
=================

  * [Dockerfile.vim](#dockerfilevim)
  * [Screenshot](#screenshot)
  * [Installation](#installation)
        * [OR using Pathogen:](#or-using-pathogen)
        * [OR using Vundle:](#or-using-vundle)
  * [License](#license)
```

Remote files
------------

And here's an example, when you have a README.md like this:

  * [README.md without TOC](https://github.com/ekalinin/envirius/blob/f939d3b6882bfb6ecb28ef7b6e62862f934ba945/README.md)

And you want to generate TOC for it.

There is nothing easier:

```bash
➥ ./gh-md-toc https://github.com/ekalinin/envirius/blob/master/README.md

Table of Contents
=================

  * [envirius](#envirius)
    * [Idea](#idea)
    * [Features](#features)
  * [Installation](#installation)
  * [Uninstallation](#uninstallation)
  * [Available plugins](#available-plugins)
  * [Usage](#usage)
    * [Check available plugins](#check-available-plugins)
    * [Check available versions for each plugin](#check-available-versions-for-each-plugin)
    * [Create an environment](#create-an-environment)
    * [Activate/deactivate environment](#activatedeactivate-environment)
      * [Activating in a new shell](#activating-in-a-new-shell)
      * [Activating in the same shell](#activating-in-the-same-shell)
    * [Get list of environments](#get-list-of-environments)
    * [Get current activated environment](#get-current-activated-environment)
    * [Do something in environment without enabling it](#do-something-in-environment-without-enabling-it)
    * [Get help](#get-help)
    * [Get help for a command](#get-help-for-a-command)
  * [How to add a plugin?](#how-to-add-a-plugin)
    * [Mandatory elements](#mandatory-elements)
      * [plug_list_versions](#plug_list_versions)
      * [plug_url_for_download](#plug_url_for_download)
      * [plug_build](#plug_build)
    * [Optional elements](#optional-elements)
      * [Variables](#variables)
      * [Functions](#functions)
    * [Examples](#examples)
  * [Example of the usage](#example-of-the-usage)
  * [Dependencies](#dependencies)
  * [Supported OS](#supported-os)
  * [Tests](#tests)
  * [Version History](#version-history)
  * [License](#license)
  * [README in another language](#readme-in-another-language)
```

That's all! Now all you need — is copy/paste result from console into original
README.md.

If you do not want to copy from console you can add `> YOURFILENAME.md` at the end of the command like `./gh-md-toc https://github.com/ekalinin/envirius/blob/master/README.md > table-of-contents.md` and this will store the table of contents to a file named table-of-contents.md in your current folder.

And here is a result:

  * [README.md with TOC](https://github.com/ekalinin/envirius/blob/24ea3be0d3cc03f4235fa4879bb33dc122d0ae29/README.md)

Moreover, it's able to work with GitHub's wiki pages:

```bash
➥ ./gh-md-toc https://github.com/ekalinin/nodeenv/wiki/Who-Uses-Nodeenv

Table of Contents
=================

  * [Who Uses Nodeenv?](#who-uses-nodeenv)
    * [OpenStack](#openstack)
    * [pre-commit.com](#pre-commitcom)
```

Multiple files
--------------

It supports multiple files as well:

```bash
➥ ./gh-md-toc \
    https://github.com/aminb/rust-for-c/blob/master/hello_world/README.md \
    https://github.com/aminb/rust-for-c/blob/master/control_flow/README.md \
    https://github.com/aminb/rust-for-c/blob/master/primitive_types_and_operators/README.md \
    https://github.com/aminb/rust-for-c/blob/master/unique_pointers/README.md

  * [Hello world](https://github.com/aminb/rust-for-c/blob/master/hello_world/README.md#hello-world)

  * [Control Flow](https://github.com/aminb/rust-for-c/blob/master/control_flow/README.md#control-flow)
    * [If](https://github.com/aminb/rust-for-c/blob/master/control_flow/README.md#if)
    * [Loops](https://github.com/aminb/rust-for-c/blob/master/control_flow/README.md#loops)
    * [For loops](https://github.com/aminb/rust-for-c/blob/master/control_flow/README.md#for-loops)
    * [Switch/Match](https://github.com/aminb/rust-for-c/blob/master/control_flow/README.md#switchmatch)
    * [Method call](https://github.com/aminb/rust-for-c/blob/master/control_flow/README.md#method-call)

  * [Primitive Types and Operators](https://github.com/aminb/rust-for-c/blob/master/primitive_types_and_operators/README.md#primitive-types-and-operators)

  * [Unique Pointers](https://github.com/aminb/rust-for-c/blob/master/unique_pointers/README.md#unique-pointers)
```

Combo
-----

You can easily combine both ways:

```bash
➥ ./gh-md-toc \
    ~/projects/Dockerfile.vim/README.md \
    https://github.com/ekalinin/sitemap.s/blob/master/README.md

  * [Dockerfile.vim](~/projects/Dockerfile.vim/README.md#dockerfilevim)
  * [Screenshot](~/projects/Dockerfile.vim/README.md#screenshot)
  * [Installation](~/projects/Dockerfile.vim/README.md#installation)
        * [OR using Pathogen:](~/projects/Dockerfile.vim/README.md#or-using-pathogen)
        * [OR using Vundle:](~/projects/Dockerfile.vim/README.md#or-using-vundle)
  * [License](~/projects/Dockerfile.vim/README.md#license)

  * [sitemap.js](https://github.com/ekalinin/sitemap.js/blob/master/README.md#sitemapjs)
    * [Installation](https://github.com/ekalinin/sitemap.js/blob/master/README.md#installation)
    * [Usage](https://github.com/ekalinin/sitemap.js/blob/master/README.md#usage)
    * [License](https://github.com/ekalinin/sitemap.js/blob/master/README.md#license)

<!-- Created by https://github.com/ekalinin/github-markdown-toc -->
```

Auto insert and update TOC
--------------------------

Just put into a file these two lines:

```
<!--ts-->
<!--te-->
```

And run:

```bash
$ ./gh-md-toc --insert README.test.md

Table of Contents
=================

   * [gh-md-toc](#gh-md-toc)
   * [Installation](#installation)
   * [Usage](#usage)
      * [STDIN](#stdin)
      * [Local files](#local-files)
      * [Remote files](#remote-files)
      * [Multiple files](#multiple-files)
      * [Combo](#combo)
   * [Tests](#tests)
   * [Dependency](#dependency)

!! TOC was added into: 'README.test.md'
!! Origin version of the file: 'README.test.md.orig.2018-02-04_192655'
!! TOC added into a separate file: 'README.test.md.toc.2018-02-04_192655'


<!-- Created by https://github.com/ekalinin/github-markdown-toc -->
```

Now check the same file:

```bash
➜ grep -A15 "<\!\-\-ts" README.test.md
<!--ts-->
   * [gh-md-toc](#gh-md-toc)
   * [Table of contents](#table-of-contents)
   * [Installation](#installation)
   * [Usage](#usage)
      * [STDIN](#stdin)
      * [Local files](#local-files)
      * [Remote files](#remote-files)
      * [Multiple files](#multiple-files)
      * [Combo](#combo)
      * [Auto insert and update TOC](#auto-insert-and-update-toc)
   * [Tests](#tests)
   * [Dependency](#dependency)

<!-- Added by: <your-user>, at: 2018-02-04T19:38+03:00 -->

<!--te-->
```

Next time when your file will be changed just repeat the command (`./gh-md-toc
--insert ...`) and TOC will be refreshed again.

GitHub token
------------

All your tokens are [here](https://github.com/settings/tokens).

You will need them if you get an error like this:

```
Parsing local markdown file requires access to github API
Error: You exceeded the hourly limit. See: https://developer.github.com/v3/#rate-limiting
or place github auth token here: ./token.txt
```

A token can be used as an env variable:

```bash
➥ GH_TOC_TOKEN=2a2dab...563 ./gh-md-toc README.md

Table of Contents
=================

* [github\-markdown\-toc](#github-markdown-toc)
* [Table of Contents](#table-of-contents)
* [Installation](#installation)
* [Tests](#tests)
* [Usage](#usage)
* [LICENSE](#license)
```

Or from a file:

```bash
➥ echo "2a2dab...563" > ./token.txt
➥ ./gh-md-toc README.md

Table of Contents
=================

* [github\-markdown\-toc](#github-markdown-toc)
* [Table of Contents](#table-of-contents)
* [Installation](#installation)
* [Tests](#tests)
* [Usage](#usage)
* [LICENSE](#license)
```

TOC generation with Github Actions
----------------------------------

Config:

```yaml
on:
  push:
    branches: [main]
    paths: ['foo.md']

jobs:
  build:
    runs-on: ubuntu-latest
    timeout-minutes: 5
    steps:
      - uses: actions/checkout@v2
      - run: |
          curl https://raw.githubusercontent.com/ekalinin/github-markdown-toc/0.8.0/gh-md-toc -o gh-md-toc
          chmod a+x gh-md-toc
          ./gh-md-toc --insert --no-backup --hide-footer foo.md
          rm gh-md-toc
      - uses: stefanzweifel/git-auto-commit-action@v4
        with:
          commit_message: Auto update markdown TOC
```

Tests
=====

Done with [bats](https://github.com/bats-core/bats-core).
Useful articles:

  * https://blog.engineyard.com/2014/bats-test-command-line-tools
  * http://blog.spike.cx/post/60548255435/testing-bash-scripts-with-bats


How to run tests:

```bash
➥ make test                                                                                                                 

 ✓ TOC for local README.md
 ✓ TOC for remote README.md
 ✓ TOC for mixed README.md (remote/local)
 ✓ TOC for markdown from stdin
 ✓ --help
 ✓ --version

6 tests, 0 failures
```

Dependency
==========

  * curl or wget
  * awk (mawk is not tested)
  * grep
  * sed
  * bats (for unit tests)

Tested on Ubuntu 14.04/14.10 in bash/zsh.

Docker
======

Local
-----

* Build

```shell
$ docker build -t markdown-toc-generator .
```

* Run on an URL

```shell
$ docker run -it markdown-toc-generator https://github.com/ekalinin/envirius/blob/master/README.md
```

* Run on a local file (need to share volume with docker)

```shell
$ docker run -it -v /data/ekalinin/envirius:/data markdown-toc-generator /data/README.md
```

Public
-------

```shell
$ docker pull evkalinin/gh-md-toc:0.7.0

$ docker images | grep toc
evkalinin/gh-md-toc                       0.7.0 0b8db6aed298        11 minutes ago      147MB

$ docker run -it evkalinin/gh-md-toc:0.7.0 \
    https://github.com/ekalinin/envirius/blob/master/README.md
```
