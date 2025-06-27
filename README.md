# Awesome Gitea

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)
[![Contribution%20Guide](https://img.shields.io/badge/-Contribution%20Guide-informational?style=flat)](contributing.md)

A curated list of awesome projects related to Gitea and its soft-fork instances.

## Contents

- [Awesome Gitea](#awesome-gitea)
  - [Contents](#contents)
  - [Actions](#actions)
  - [Applications](#applications)
    - [Bot](#bot)
    - [Command Line](#command-line)
    - [DevOps](#devops)
    - [Mobile](#mobile)
    - [Panel](#panel)
    - [Web Hosting](#web-hosting)
  - [Migration](#migration)
  - [Organizations](#organizations)
    - [Open Registration](#open-registration)
    - [For internal use](#for-internal-use)
  - [Packages](#packages)
  - [Package Management](#package-management)
  - [Plugins](#plugins)
  - [Scripts](#scripts)
  - [SDK](#sdk)
  - [Themes](#themes)
    - [Light](#light)
    - [Dark](#dark)
  - [Workflow Tools](#workflow-tools)
  - [Project Management](#project-management)

## Actions

- [gitea-publish-generic-packages](https://github.com/VAllens/gitea-publish-generic-packages) - An action to support publishing generic packages to Gitea.
- [gitea-release-action](https://gitea.com/actions/gitea-release-action) - An action to support publishing releases to Gitea.
- [gitea-release-please](https://github.com/marketplace/actions/gitea-release-please-action) - An action to support Automated releases with Conventional Commit Messages.

## Applications

### Bot

- [giteacat](https://git.mastodont.cat/spla/giteacat.git) - Python Bot that register Mastodon server's users to Gitea instance, on demand.
- [gopher-bot](https://github.com/nfort/gopher-bot) - Bot for checking golang code
- [issue-bot](https://git.meli.delivery/meli/issue-bot) - Bot for mailing list mirroring of Gitea issues. Allow people to submit issues on repositories using only e-mail without signing up. [github read-only mirror](https://github.com/meli/issue-bot)
- [sq-bot](https://codeberg.org/justusbunsi/gitea-sonarqube-bot) - Bot for decorating Gitea pull requests with SonarQube analysis details.
- [staletea](https://gitea.com/jonasfranz/staletea) - StaleBot for Gitea.
- [tea-cloc](https://codeberg.org/qwerty287/tea-cloc) - Bot to count lines of code on Gitea repos and comments on pull requests with code change statistics.

### Command Line

- [changelog](https://gitea.com/gitea/changelog) - Generate changelog of gitea repository.
- [gcli](https://github.com/herrhotzenplotz/gcli) - A CLI for Gitea, Gitlab and Github written in C
- [gitea-cli](https://github.com/bashup/gitea-cli) - Extensible, configurable command-line API client for gitea and gogs.
- [gitea-installer](https://github.com/uvulpos/gitea-installer) - a simple ubuntu native installer script
- [grp](https://github.com/feraxhp/grp) - A cli tool to interact with github, gitea and local repositories written in rust.
- [makepr](https://github.com/hrgdavor/makepr) - Quickly open url to start PR process with current branch.
- [sip](https://gitea.com/jolheiser/sip) - A prompt-based command line tool to interact with Gitea servers.
- [tea](https://gitea.com/gitea/tea) - A command line tool to interact with Gitea servers.

### DevOps

- [actions runner](https://gitea.com/ChristopherHX/actions_runner) - Use the actions/runner developed by GitHub with Gitea Actions.
- [agola](https://github.com/agola-io/agola) - Agola: CI/CD Redefined. Built-in Gitea support.(see [``docs``](https://agola.io/tryit/#test-using-a-local-gitea-instance))
- [appveyor](https://www.appveyor.com/) - Gitea receives first-class support in AppVeyor CI.
- [AWS Cloud Integration(webhook-to-s3)](https://github.com/leonli/webhook-to-s3) - Gitea Webhook integration with AWS CodePipeline and CodeBuild by automatically uploading the archive to AWS S3.
- [buildbot-gitea](https://github.com/lab132/buildbot-gitea) - Buildbot plugin for integration with gitea.
- [buildkite-connector](https://github.com/techknowlogick/gitea-buildkite-connector) - Connect Gitea & Buildkite.
- [Concourse](https://www.concourse-ci.org/) - partially can be integrated with Gitea.
- [dex](https://github.com/dexidp/dex) - Dex is a federated OpenID Connect provider. Built-in Gitea support.
- [drone](https://github.com/drone/drone) - Drone is a Container-Native, Continuous Delivery Platform. Built-in Gitea support. (see [docs](https://docs.drone.io/server/provider/gitea/))
- [ghorg](https://github.com/gabrie30/ghorg) - Quickly clone an entire org/users repositories into one directory - Supports Gitea, GitHub, GitLab, and more.
- [gickup](https://github.com/cooperspencer/gickup) - Backup tool for repositories.
- [JayporeCi](https://github.com/theSage21/jaypore_ci) - Self hosted CI tightly integrated with gitea
- [Jenkins](https://github.com/jenkinsci/gitea-plugin) - Gitea plugin for jenkins.
- [Metroline](https://github.com/metroline/metroline) - Metroline is a Continuous Integration and Delivery platform built with Docker, Node, React and MongoDB, natively compatible with Gitea.
- [Monitoring mixin](https://github.com/go-gitea/gitea/tree/main/contrib/gitea-monitoring-mixin) - Gitea monitoring mixin (Grafana dashboard)
- [mvoCI](https://codeberg.org/snaums/mvoCI) - very simple Continuous Integration Server written in go. Built-in Gitea support.
- [QEMU-KVM-Solution](https://github.com/CrimsonGiteaActions/QEMU-KVM-Solution) - A simple solution that enables running Gitea Actions job in ephemeral virtual machine.
- [Renovate](https://github.com/renovatebot/renovate) - Gitea compatible configurable universal dependability update tool
- [soba](https://github.com/jonhadfield/soba) - scheduled backups of user/organization Gitea repositories with change detection.
- [Tea Runner](https://github.com/DavesCodeMusings/tea-runner) - A minimalist Python Flask app that uses Gitea webhooks to perform actions.
- [watchtower](https://github.com/containrrr/watchtower) - A process for automating Docker container base image updates. Useful for running Continuous Deployment pipeline steps.
- [webhook](https://github.com/adnanh/webhook) - webhook is a lightweight incoming webhook server to run shell commands. Useful for running Continuous Deployment pipeline steps.
- [webhookd](https://github.com/ncarlier/webhookd) - A very simple webhook server launching shell scripts. Useful for running Continuous Deployment pipeline steps.
- [woodpecker](https://github.com/woodpecker-ci/woodpecker) - An opinionated fork of the Drone CI system. Built-in Gitea support. (see [docs](https://woodpecker-ci.org/docs/administration/vcs/gitea))
- [yojo](https://sr.ht/~emersion/yojo/) - A CI bridge from Gitea to SourceHut.

### Mobile

- [GitNex](https://codeberg.org/gitnex/GitNex) - Android client for Gitea.
- [GitTouch](https://github.com/git-touch/git-touch) - Open source mobile client for GitHub, GitLab, Bitbucket and Gitea, built with Flutter

### Panel

- [GiteaPanel](https://github.com/sashaoli/GiteaPanel) - Manage the local Gitea server from the tray.
- [Listea](https://github.com/IGLOU-EU/listea) - Simple Gitea issues viewer from the tray.
- [US/GiteaPanel](https://github.com/kerwin612/us-giteapanel) - A Gitea shortcut panel built based on UserScript.

### Web Hosting

- [Caddy Gitea Plugin (42wim/caddy-gitea)](https://github.com/42wim/caddy-gitea) - Caddy2 plugin enables GitHub pages-like features in Gitea, requiring a wildcard CNAME to your Gitea host.
- [Caddy Gitea Plugin (d7z-project/caddy-gitea-pages)](https://github.com/d7z-project/caddy-gitea-pages) - A simple Gitea Pages plugin that is compatible with Github Pages, supports custom domains, and can be published using Gitea Actions.
- [Meli Docs](https://docs.meli.charlie-bravo.be/authentication/gitea) - Meli is an open source platform built for deploying static sites and frontend applications.
- [Pages Server](https://codeberg.org/Codeberg/pages-server) - Static Pages Server, Gitea equivalent of GitHub Pages: Can serve static webpages on custom domains, including caching, and much more
- [pages-server](https://git.mills.io/prologic/pages-server) - A simple server for serving up static pages for Gitea A Gitea Pages server ala Github pages.
- [Pages Server](https://github.com/d7z-project/gitea-pages) - Another opinionated gitea pages project. GitHub-compatible with custom template rendering support.

## Migration

- [BitbucketServer2Gitea](https://github.com/appleboy/BitbucketServer2Gitea) - A command line tool build with Golang to migrate a Bitbucket Server (Stash) Project to Gitea.
- [Bitbucket2Gitea](https://github.com/sIspravnikov/BitbucketToGitea) - A python3 script to migrate all projects and repositories from Atlassian BitBucket to Gitea.
- [github2gitea](https://gitea.com/yige/github2gitea) - A python script to migrate Github repositories Gitea with issues/prs/wiki and etc.
- [gitlab2gitea](https://github.com/cornelk/gitlab2gitea) - A command line tool build with Golang to migrate a GitLab project to Gitea.
- [Gogs2Gitea](https://github.com/lesh59/Gogs2Gitea) - A SQL script and process (README) to migrate directly from Gogs 0.12.3 to Gitea 1.12.5 / 1.12.6 in MySQL/MariaDB and maybe other DB's.
- [jira2giteaMySql](https://github.com/juangarcia06/jira2giteaMySql) Jira Issues to Gitea (with MySql)

## Organizations

### Open Registration

- [Codeberg](https://codeberg.org/Codeberg) - Non-Profit Collaboration Community for Free and Open Source Projects (formerly known under its working title teahub.io).
- [Disroot](https://git.disroot.org/) - Aims to change the way people are used to interact on the web.
- [GitShuiShan](http://gitea.shuishan.net.cn/) - A Git platform for education
- [OpenDev](https://opendev.org/) - A space for collaborative Open Source software development.
- [RadioRepo](https://repo.radio/) - The home of software development for the Amateur Radio Community.
- [~vern gitea](https://git.vern.cc/) - A gitea instance for free software hackers

### For internal use

- [Blender](https://projects.blender.org) - The Blender Projects portal where all the (Blender) official initiatives are coordinated and managed.
- [FSFE](https://git.fsfe.org/) - Git @ Free Software Foundation Europe
- [openSUSE](https://gitea.opensuse.org/) - openSUSE Gitea
- [PSES](https://git.passageenseine.fr/pses) - Git @ Pas Sage en Seine.
- [Sum7](https://dev.sum7.eu/) - A hoster to support decentralized services. A step away from big cloud services.
- [Teknik](https://git.teknik.io/Teknikode) - Provide services to help those who try to innovate.

## Packages

- [docker-openshift-gitea](https://github.com/wkulhanek/docker-openshift-gitea) - Gitea container for OpenShift
- [gitea-chocolatey](https://github.com/doggy8088/gitea-chocolatey) - Chocolatey package for gitea
- [Gitea Debian/Ubuntu packages](https://gitlab.com/packaging/gitea) - Debian/Ubuntu packages
- [gitea-helm-chart](https://github.com/jfelten/gitea-helm-chart) - gitea-helm-chart
- [gitea-operator](https://github.com/integr8ly/gitea-operator) - An Operator that installs Gitea
- [gitea_yhn](https://github.com/YunoHost-Apps/gitea_ynh) - Gitea package for YunoHost
- [helm-chart](https://gitea.com/gitea/helm-chart) - Official Gitea Helm Chart
- [Raspbian Addons](https://raspbian-addons.org) - an APT repository for Raspberry Pi which includes up-to-date gitea packages.
- [SynoCommunity Gitea](https://synocommunity.com/package/gitea) - Synology Gitea Package
- [synology-gitea-jboxberger](https://github.com/jboxberger/synology-gitea-jboxberger) - Synology Gitea Package

## Package Management

- [Acappella](https://github.com/sitelease/acappella) - Private Composer Repository for Gitea

## Plugins

- [git-kanban-enhanced-extension](https://github.com/funktechno/git-kanban-enhanced-extension) - chrome extension to add additional kanban project planning to git hosting: github.com, gitlab.com, gitea.io, bitbucket.org
- [git-master](https://github.com/ineo6/git-master) - Git Master Extension for git file tree, support GitHub, GitLab, Gitee, Gitea
- [gitea-comment-plugin](https://github.com/TsakiDev/gitea-comment) - A Drone plugin to post comments on a Gitea Pull Request.
- [Gitea Extension for Visual Studio](https://marketplace.visualstudio.com/items?itemName=MysticBoy.GiteaExtensionforVisualStudio) - A Visual Studio Extension that brings the Gitea Flow into Visual Studio.
- [gitea-kanban](https://github.com/qontu/gitea-kanban) - Kanban for Gitea done in Vue
- [gitea-preview](https://github.com/pacman-ghost/gitea-preview) - Preview files (including HTML) directly from a Gitea repo.
- [Gitea-VSCode](https://marketplace.visualstudio.com/items?itemName=ijustdev.gitea-vscode) - Gitea Issue Tracker for vs-code
- [intellij-gitea-plugin](https://github.com/e1fueg0/intellij-gitea-plugin) - Gitea issue tracker integration plugin for Jetbrains IDE platform.
- [redmine_merge_request_links](https://github.com/tf/redmine_merge_request_links#gitea) - Gitea pull request integration for Redmine issue tracker.
- [Gitea](https://github.com/LeonDevLifeLog/gitea-idea-plugin) plugin for JetBrains IDEs(Idea,Android Studio,etc).
- [Gitea-Anchorpoint](https://docs.anchorpoint.app/docs/1-overview/integrations/gitea) Gitea integration plugin for an artist friendly Git client.
- [gitea-conventional-comments-button](https://github.com/sebastian-sauer/gitea-conventional-comments-button) - A browser extension to add buttons for [conventional comments](https://conventionalcomments.org/) to review comment boxes.

## Scripts

- [docker-gitea](https://gitea.com/jwobith/docker-gitea) - Docker Gitea Service
- [nodiscc.xsrv.gitea](https://github.com/nodiscc/xsrv/tree/master/roles/gitea) - Ansible role to install and configure Gitea
- [nodiscc.xsrv.gitea_act_runner](https://github.com/nodiscc/xsrv/tree/master/roles/gitea_act_runner) - Ansible role to install and configure `act_runner`
- [solarchemist/gitea](https://codeberg.org/ansible/gitea) - Ansible role to install and configure multiple Gitea instances on the same host.

## SDK

- [Dart](https://pub.dev/packages/gitea) - Dart SDK for gitea
- [gitea.js](https://github.com/waspothegreat/gitea.js) - Gitea (WIP) wrapper lib made in javascript.
- [gitea-js](https://github.com/anbraten/gitea-js) - Gitea client in Typescript for browsers and Node.JS ([npm](https://www.npmjs.com/package/gitea-js)) ([docs](https://anbraten.github.io/gitea-js/))
- [Gitea.net](https://github.com/mkloubert/gitea.net) - .NET Library for the Gitea API.
- [Gitea-sdk](https://gitea.com/jolheiser/gitea-sdk) - Gitea SDK generated by Swagger. (Archived, use the official Golang SDK)
- [Giteapy](https://pypi.org/project/giteapy/) - Python SDK for gitea
- [gitear](https://CRAN.R-project.org/package=gitear) - R wrapper to the gitea API
- [Gitea rust crate](https://crates.io/crates/gitea) - A simple Gitea client for Rust programs
- [Golang SDK](https://gitea.com/gitea/go-sdk) - Official Golang SDK for gitea.
- [java-gitea-api](https://github.com/zeripath/java-gitea-api) - Swagger generated api for Gitea
- [PHP](https://github.com/avency/Gitea/) - PHP SDK for gitea
- [py-gitea](https://github.com/Langenfeld/py-gitea/) - A very simple API client for Gitea > 1.16.1
- [Sugar Cube Client](https://github.com/sitelease/sugar-cube-client) - A sweet Gitea API client for PHP
- [tea4j-autodeploy](https://codeberg.org/gitnex/tea4j-autodeploy) - Swagger-generated Java library which uses Retrofit to access the Gitea API

## Themes

- [Catppuccin](https://github.com/catppuccin/gitea) - Soothing pastel theme for Gitea
- [Lugit Themes](https://github.com/lucas-labs/gitea-lugit-theme) - Light-Dark themes inspired by Github and Catppuccin
- [Modern](https://codeberg.org/Freeplay/Gitea-Modern) - Changes the layout for a more modern look. Usable with other themes that only change colors.
- [pat-s/GitHub](https://codeberg.org/pat-s/gitea-github-theme) - Opinionated GitHub-inspired light and dark themes
- [Red](https://github.com/saegl5/Gitea-Red) - Red theme by saegl5 (forked from Red Silver)
- [Sainnhe's Theme Pack](https://git.sainnhe.dev/sainnhe/gitea-themes) - Port of some editor themes
- [theme.park](https://docs.theme-park.dev/themes/gitea) - Rich theme suite that includes Gitea

### Light

- [Red Silver](https://github.com/iamdoubz/Gitea-Red-Silver) - Red silver theme by iamdoubz
- [lstolcman/GitHub](https://github.com/lstolcman/gitea-github-theme) - Simple Github theme for Gitea
- [Light Blue](https://github.com/sIspravnikov/gitea-lightblue) - Light blue theme inspired by Bitbucket

### Dark

- [Bthree Dark](https://projects.blender.org/infrastructure/gitea-custom) - A dark theme created and used by the Blender Project.
- [Carbon Red](https://github.com/iamdoubz/Gitea-Carbon-Red) - Darker red 1.14+ theme based on arc-green by iamdoubz
- [Dark Arc](https://github.com/Jieiku/theme-dark-arc-gitea) - Dark theme with high contrast, based on arc-green.
- [Dark Blue](https://gitea.artixlinux.org/artix/gitea-dark-blue) - The dark blue Gitea theme used on [https://gitea.artixlinux.org](https://gitea.artixlinux.org)
- [Dark Red](https://github.com/iamdoubz/Gitea-Dark-Red-Theme) - Dark red theme by iamdoubz
- [Deep Dark](https://github.com/plashenkov/gitea-theme-deep-dark) - A deep dark theme based on arc-green and featuring unified headers.
- [Earl Grey](https://github.com/Troplo/earl-grey) - An elegant dark theme for Gitea with blue as the primary color.
- [GitHub](https://github.com/Rainnny7/gitea-github-theme) - A theme to make Gitea look and feel like GitHub.
- [GitHub Dark](https://github.com/lutinglt/gitea-github-theme) - A dark theme to make Gitea look and feel like GitHub.
- [Matrix](https://github.com/TylerByte666/gitea-matrix-template) - Neon-green with a matrix-inspired background
- [One Dark](https://git.tjdev.de/tjdev/gitea-theme-one-dark) - One Dark theme used on [git.tjdev.de](https://git.tjdev.de)
- [Pitch Black](https://github.com/iamdoubz/Gitea-Pitch-Black) - Pitch black 1.14+ theme used on [https://git.dou.bet/iamdoubz/Gitea-Pitch-Black](https://git.dou.bet/iamdoubz/Gitea-Pitch-Black)
- [Tangerine Dream](https://github.com/jager012/tangerine-dream) - Tangerine dark theme for Gitea

## Workflow Tools

- [alfred-gitea](https://github.com/pat-s/alfred-gitea) - Alfred workflow for Gitea

## Project Management

- [JetBrains YouTrack](https://www.jetbrains.com/help/youtrack/standalone/integration-with-gitea.html) - A web-based issue tracking and project management platform
