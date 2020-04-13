# Basic website

This is was forked from [Hugo Flex](https://github.com/de-souza/hugo-flex/), a [Hugo](https://gohugo.io/) theme created by [Léo De Souza](https://github.com/de-souza).

Live example: 

## Run

Clone this repository:

```
git clone https://github.com/julienbrg/basic-website.git
```

Go into this newly created folder:

```
cd basic-website
````

If you don't have it yet, install [Hugo](https://gohugo.io/) (Linux or MacOS):

```
brew install hugo
hugo version
```

You should see something like this:

>Hugo Static Site Generator v0.66.0/extended darwin/amd64 BuildDate: unknown


If you're a Windows user or if you meet any other difficulty, head to [https://gohugo.io/getting-started/installing/](https://gohugo.io/getting-started/installing/)

Now just:

```
hugo server -D
```
It creates a folder named `public`, and launches a server just for you.

Open your browser and go to:

> http://localhost:1313/

You should see this:

![](https://gateway.pinata.cloud/ipfs/QmPxA2uG7m5WRJwVtL87JPaH6wwDEuKy8ajGApUzqi62st/)

## Edit

To edit the content, open `index.md` (in the `content` folder). This file is written in [markdown](https://web.stanford.edu/~kjytay/courses/stats32-aut2019/Session%208/Markdown%20Cheatsheet.pdf).

In the `config.toml` file, you can modify the menu, the footer, etc.

## Deploy

You can copy-paste the content of the `public` folder on any server.

And if you want to turn it into a 'decentralized website' (AKA 'dwebsite') thanks to [IPFS](https://ipfs.io/) and [ENS](https://ens.domains/), here's a full tutorial to learn how to do that:

[http://clair.eth.link/get-decentralized](http://clair.eth.link/get-decentralized)

## Support

If you have any question, you can find me on Telegram: [https://t.me/julienbrg](https://t.me/julienbrg)
