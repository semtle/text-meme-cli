# text-meme-cli [![Build Status](https://travis-ci.org/beatfreaker/text-meme-cli.svg?branch=master)](https://travis-ci.org/beatfreaker/text-meme-cli)

> Generate text meme

<img src="meme.gif" width="300">


## Install

```
$ npm install --global text-meme-cli
```


## Usage

```
$ text-meme --help

  Usage
    $ text-meme "Don't forget to be awesome"

  Options
    --delay       Frame delay [Default: 500]
    --background  Background color in hex [Default: #000000]
    --fontcolor   Text color in hex [Default: #ffffff]
    --filename    Filename with extension [Default: meme-123.gif]
    --fontsize    Text size [Default: 50]
    --imagesize   Image size in px [Default: 600]

  Examples
    $ text-meme "Don't forget to be awesome"
    generated text-meme → meme-326.gif
    $ text-meme "Don't forget to be awesome" --filename=quote.gif --background=#4f656d --imagesize=500
    generated text-meme → quote.gif
```


### Related

- [text-meme](https://github.com/beatfreaker/text-meme) - API for this module
- [slate](https://github.com/bitshadow/slate) - Inspiration for this module


#### Note

This module uses [canvas](https://www.npmjs.com/package/canvas) module as dependency which requires `Cairo` check [here](https://www.npmjs.com/package/canvas#installation) how to install it.


## License

MIT © [beatfreaker](https://beatfreaker.github.io)
