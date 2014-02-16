# Society Website [![Build Status](https://travis-ci.org/SMU-CS-and-Math-Society/smu-cs-math-website.png?branch=master)](https://travis-ci.org/SMU-CS-and-Math-Society/smu-cs-math-website)

> Saint Mary's University, Computer Science and Mathematics Society

## Installation

### [Install Node.js](https://github.com/Glavin001/Tutorials/tree/master/nodejs/getting-started)
See https://github.com/Glavin001/Tutorials/tree/master/nodejs/getting-started

### Install [Ruby](https://www.ruby-lang.org/en/downloads/) and [Compass](http://rubygems.org/gems/compass) and [SASS](https://rubygems.org/gems/sass)

Download [Ruby from https://www.ruby-lang.org/en/downloads/](https://www.ruby-lang.org/en/downloads/).

Install [Compass](http://rubygems.org/gems/compass) and [SASS](https://rubygems.org/gems/sass) with the following commands.

```bash
gem install sass
gem install compass
```

### Clone the Git Repository

```bash
git clone git@github.com:SMU-CS-and-Math-Society/smu-cs-math-website.git
```

Change directory into the repository

```bash
cd smu-cs-math-website/
```

### Install the dependencies with [NPM](https://www.npmjs.org/)

#### Global Gependencies

```bash
npm install -g grunt-cli
npm install -g mocha
npm install -g bower
```

#### Project Specific Dependencies

```bash
npm install 
bower install
```

## Usage

The following command will build the website, start a server, and watch for any file changes.

```bash
npm start
```

### Testing

The following command will run tests on the website.

```bash
npm test
```

## Building the Static Website

For using with [Nginx](http://wiki.nginx.org/) or [Apache](http://apache.org/).

The following will build to the `dist` directory.

```bash
grunt build
```
