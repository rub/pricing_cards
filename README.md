# Pricing cards

A simple playground using Sass.

## Tools

Built using [Sass](https://sass-lang.com/).

I used the [Trello styleguide](https://gist.github.com/bobbygrace/9e961e8982f42eb91b80#file-trello-css-guide-md) as a reference to write the CSS.

I used the [7-1 pattern](https://sass-guidelin.es/#the-7-1-pattern) to organize the Sass architecture.

## Getting started

These instructions will get you a copy of the project up and
running on your local machine for contributions or testing purposes.

### Requirements

What things you need to run the website:

- [Node.js](https://nodejs.org/en/)
- [Yarn](https://yarnpkg.com/)

### Setup

#### Access the project

```
$ git clone git@github.com:rub/pricing_cards.git
$ cd pricing_cards
```

#### Install frontend dependencies

```
$ yarn
```

#### Build the static CSS

```
$ yarn run compile:sass
```

#### Launch the project (quick mode)

Open `index.html`

#### Launch the project on an external device

If you need to launch the project on an external device (a tablet or a mobile phone) you can run a simple local server with [Python](https://www.python.org/).

1. Connect the external device to the same Wi-Fi network that your computer is using.

2. Get the IP address of your computer

```
ifconfig | grep '192.168' | cut -d ' ' -f 2
```

3. Run the local server with Python

Python 2.X - `python -m SimpleHTTPServer 8000`

Or

Python 3.X - `python3 -m http. server 8000` (not tested)

4. Open the browser of your external device and visit _`my_ip_address:8000`_
