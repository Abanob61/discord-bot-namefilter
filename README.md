[![POGODEV](https://github.com/pogodevorg/assets/blob/master/public/img/logo-github.png?raw=true)](https://pogodev.org)

# discord-bot-namefilter
[![Build Status](https://travis-ci.org/pogodevorg/discord-bot-namefilter.svg?branch=master)](https://travis-ci.org/pogodevorg/discord-bot-namefilter) [![Code Climate](https://codeclimate.com/github/pogodevorg/discord-bot-namefilter/badges/gpa.svg)](https://codeclimate.com/github/pogodevorg/discord-bot-namefilter) [![Issue Count](https://codeclimate.com/github/pogodevorg/discord-bot-namefilter/badges/issue_count.svg)](https://codeclimate.com/github/pogodevorg/discord-bot-namefilter) [![license](https://img.shields.io/github/license/pogodevorg/discord-bot-namefilter.svg?maxAge=2592000?style=flat-square)](https://github.com/pogodevorg/discord-bot-namefilter/blob/master/LICENSE.md)

## Table of Contents
* [What is it?](#what-is-it)
* [Installation](#installation)
* [Documentation](#documentation)
* [Contributing](#contributing)
  * [Core Maintainers](#core-maintainers)
* [Licensing](#licensing)
  * [Third Party Licenses](#third-party-licenses)
* [Credits](#credits)

## What is it?
`discord-bot-namefilter` is an open source repo for filtering out annoying unicode in discord usernames.
Randomly selects a username from a list if the Discord User has less than 4 characters in their name.
Filtering can be applied to specific channels as well.

## Installation
```json
{
	"api_key": "BOT TOKEN HERE",
	"channels": [
    "CHANNEL NAME",
    "Channel2"
	],
	"except_roles": [
    "ROLE NAME",
    "Moderator"
	]
}
```
1. `pip3 install -r requirements.txt`
2. `cp config.json.sample config.json`
3. `python3 bot.py`

## Documentation
Any further documentation to be written here, or referred to elsewhere.

## Licensing
[GNU GPL](https://github.com/pogodevorg/discord-bot-namefilter/blob/master/LICENSE) v3 or later.

### Third Party Licenses
    None

## Contributing
Currently, you can contribute to this project by:
* Submitting a detailed [issue](https://github.com/pogodevorg/discord-bot-namefilter/issues/new).
* [Forking the project](https://github.com/pogodevorg/discord-bot-namefilter/fork), and sending a pull request back to for review.

### Core Maintainers

* [![Build Status](https://github.com/fkndean.png?size=36) - fkndean](https://github.com/fkndean)

## Credits
Credits to enjoy2000 for base.

Modified to work with the PogoDev Discord Server ([https://discord.pogodev.org](https://discord.pogodev.org)).
