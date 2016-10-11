# Cloudcannon Jekyll Demo

Demo site to test the Cloud Cannon platform and Jekyll integration with Github.

<!-- MarkdownTOC -->

- [Project dependencies](#project-dependencies)
- [Start Application](#start-application)
- [Base Theme](#base-theme)

<!-- /MarkdownTOC -->

## Project dependencies

* RVM
* Ruby 2.3.0p0
* NVM
* Node v4.6.0

Install Bundler and other gems, including Jekyll to run the site.

```sh
gem install bundler
bundle
```

Install Node and NPM modules for running the `grunt` front-end build actions.

```sh
npm i npm@latest -g # Update to latest NPM
npm i -g grunt-cli
npm i
```

## Start Application

To start the application run:

```sh
jekyll serve
```

You should be able to access the site at [http://127.0.0.1:4000](http://127.0.0.1:4000)

## Base Theme

The base theme used for this demo is the [skinny-bones-jekyll](https://mmistakes.github.io/skinny-bones-jekyll/) theme by [mmistakes](https://github.com/mmistakes).