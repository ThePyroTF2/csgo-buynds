# csgo-buynds

Copyright © 2014-2017 Jesse Webb

This code is available under [the MIT License](https://github.com/jessewebb/csgo-buynds/blob/gh-pages/LICENSE).

_Disclaimer:_ This project is currently in **BETA** stages of development.

`Version: 0.9.0`

[![Build Status](https://travis-ci.org/jessewebb/csgo-buynds.svg?branch=gh-pages)](https://travis-ci.org/jessewebb/csgo-buynds)

## About csgo-buynds

### _What?_

**csgo-buynds** is an open-source web-app for generating buy binds for _[Counter-Strike: Global Offensive](http://en.wikipedia.org/wiki/Counter-Strike:_Global_Offensive)_ (CS:GO).

Buy binds, also known as buy scripts, are commands for the _Counter-Strike_ PC games that allow quick, 1-button purchasing of weapons and equipment.

Visit the [CSGO-Buynds website](http://csgobuynds.com) and try out the online Buy Binds Generator!

### _Why?_

This project was started for several reasons:

- All other buy bind generators only allow configuring a single key bind at once
- To become more familiar with JavaScript
- To experiment with AngularJS
- To learn JavaScript testing patterns

Along with allowing you to configure multiple key binds at once, there are other unique features planned for csgo-buynds:

- Saved player profiles for automatic loading of bind configs
- Sortable weapons and equipment for customizable purchasing priority
- Printable key-map for quick reference

### _Who?_

The [CSGO-Buynds Buy Binds Generator](http://csgobuynds.com/buy-binds-generator.html) was made for all of the CS:GO PC players out there who don't want to use the clunky radial menu for purchasing their weapons and equipment.
The online tool is simple enough for anybody to use yet powerful enough to build highly customized binds.
Everyone from noobs to Pros will enjoy being able to create easily-accessible loadouts.
Don't get caught fumbling in the CS:GO buy menu. Never be the last player out of spawn again!

The creator of **csgo-buynds** is Jesse Webb (a.k.a. Gweebz), a long time player of the _Counter-Strike_ series.

- [Jesse Webb on GitHub](https://github.com/jessewebb)
- [Jesse Webb on Twitter](https://twitter.com/gweebz)
- [Gweebz on Steam](http://steamcommunity.com/id/gweebz)
- [GweebzTV on Twitch.TV](http://www.twitch.tv/GweebzTV)

## Dev Info

This project uses [GitHub Pages](http://pages.github.com/) to host the website. It [does not use Jekyll](https://github.com/blog/572-bypassing-jekyll-on-github-pages).

The main branch, [`gh-pages`](https://github.com/jessewebb/csgo-buynds/tree/gh-pages), is where stable releases are deployed to.

Development should be done on the [`dev`](https://github.com/jessewebb/csgo-buynds/tree/dev) branch.

[Pull requests](https://github.com/jessewebb/csgo-buynds/pulls) are welcomed!

This project is a simple, static website built with pure HTML5, CSS3, and JavaScript. There is nothing to compile.

Here is a list of which 3rd party libraries are being used:

- [jQuery](http://jquery.com/) (version: 2.1.3)
- [AngularJS](http://angularjs.org/) (version: 1.3.12)
- [Bootstrap](http://getbootstrap.com/) (version: 3.3.2)
- [AngularUI](http://angular-ui.github.io/)
    - [UI Bootstrap](http://angular-ui.github.io/bootstrap/) (version 0.12.0)
    - [UI Select](http://angular-ui.github.io/ui-select/) (version 0.19.6)
- [ngClip](https://github.com/asafdav/ng-clip) (version: 0.2.6)
- [ZeroClipboard](http://zeroclipboard.org/) (version: 2.2.0)

Tests are written with [Jasmine](http://jasmine.github.io/) (version: 2.5.2).
- You can[run the tests in your browser.](http://csgobuynds.com/tests/SpecRunner.html)
- Or you can run them from the command line with [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/).  
  ```
  npm install
  npm test
  ```  
  (The project is configured to use [Karma](http://karma-runner.github.io/) (version: 1.3.0) to run the tests.)

Jesse's preferred JavaScript IDE is [JetBrain's WebStorm](http://www.jetbrains.com/webstorm/).
