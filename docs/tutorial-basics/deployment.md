---
sidebar_position: 1
---

# Deployment Guidelines.

## Requirements

- Python 3.8 or higher (recomended).
- [Telegram API key](https://docs.pyrogram.org/intro/setup#api-keys).
- [Telegram Bot Token](https://t.me/botfather)
- [MongoDB Database](https://cloud.mongodb.com/).

# Set Up

## Configuration

Set up your bot configuration variables by renaming `config.env_sample` to `config.env` and edit it with your values.

Configuration must be done before running the bot, otherwise it will fail to run.

## Dependencies

### Install all required dependencies by running

`python3 -m pip install -r requirements.txt`.

### Install the bot along with depencies by running

`python3 -m pip install .`

#### Error: Directory '.' is not installable. File 'setup.py' not found.

This common error is caused by an outdated version of pip. This is a relatively new standard, so a newer version of pip is necessary to make it work.

Upgrade to pip 19 to fix this issue: `pip3 install -U pip`

## Run

Once everything set up, start the client by running

`python3 -m anjani`

## Plugin

If you want to make your custom plugins, refer to [Anjani's Wiki](https://github.com/userbotindo/Anjani/wiki). It has a lot of important things to read and a plugin example to guide you.
