# GirlCrawler

![example](https://raw.githubusercontent.com/Ericlong233/girlcrawler/master/res/example.png)

### Introduction

GirlCrawler is a fast, smart [jandan.net/ooxx](http://jandan.net/ooxx) crawler. It's based on efficient, asynchronous Node.js. It has the following features:

- Fast with Node.js' async I/O
- Filter based on OO/XX (likes/dislikes)
- Update with optimization

### Usage

`girlcrawler [options]`

- `-t, --thread` The *maximum* number of concurrent downloads, default 128. Because of the network speed, it may not take any effect though the value is very large.
- `-f, --filter` OO/XX based filter, default "oo > xx".

### Installation

1. Install [Git](https://git-scm.com/) and [Node.js](https://nodejs.org). If you've already installed, skip this step.
2. Open Terminal (in Mac & Linux) or Command Prompt (in Windows), execute `git clone` to clone the project.
3. Execute `npm install girlcrawler -g` to install it globally.
4. Execute `girlcrawler` every time you want to use it.

### To-do List

- [ ] Save config files every time before downloading


- [ ] Add more options

### Dependencies

- async [github.com/caolan/async](https://github.com/caolan/async) 
- commander [github.com/tj/commander.js/](https://github.com/tj/commander.js/)
- request [github.com/request/request](https://github.com/request/request)
- cheerio [github.com/cheeriojs/cheerio](https://github.com/cheeriojs/cheerio)
- colors [github.com/Marak/colors.js](https://github.com/Marak/colors.js)
- progress [github.com/visionmedia/node-progress](https://github.com/visionmedia/node-progress)

### License

[MIT License](https://github.com/Ericlong233/girlcrawler/blob/master/LICENSE)