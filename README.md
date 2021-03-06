# Go In 5 Minutes

[![Build Status](https://travis-ci.org/arschles/go-in-5-minutes.svg?branch=master)](https://travis-ci.org/arschles/go-in-5-minutes)

This repository has code and outlines for [Go In 5 Minutes Screencasts](htttp://bitly.com/goin5minutesyt). All content (code samples, outlines, etc...) is organized into folders, starting with [`episode0`](https://github.com/arschles/go-in-5-minutes/tree/master/episode0) and going from there.

Full descriptions and videos are at http://www.goin5minutes.com/screencasts/index.html.

Shortened URL for this repository: http://bitly.com/goin5minutes

Shortened URL for screencasts: http://bitly.com/goin5minutesyt

# Request A Screencast

I have some ideas for topics to cover, but if you want to see some topics covered in a future screencast, I'd like to hear from you.

Please [submit an issue](https://github.com/arschles/go-in-5-minutes/issues) with the `request a screencast` label and make sure to include a good description on what you want to see!

Here are some example issues: https://github.com/arschles/go-in-5-minutes/labels/request%20a%20screencast.

# Bundle

If you're just getting started with the series, want to download the screencasts, or otherwise would like to have DRM-free, HD versions of the screencasts, I encourage you to buy the bundle of episodes 0-9 at https://gum.co/gifm-1-10.

# Email Newsletter

I send out an email newsletter intermittently with screencasts, additional information and resources. I encourage you to sign up for it at http://www.goin5minutes.com/subscribe/index.html.

# Issues With Code, Documentation, etc...

If you see any problems with code, documentation, or anything else in this repository, please [submit an issue](https://github.com/arschles/go-in-5-minutes/issues) with the `bug` label and I'll fix it as soon as I can. Pull requests are also welcome.

# Build, Test and Run Instructions

All the folders that start with `episode` (such as [`episode0`](https://github.com/arschles/go-in-5-minutes/tree/master/episode0)) contain the outline and code samples for that episode, and all code samples can be built and run.

Unless otherwise specified in the `README.md` in the episode folder, the commands for building, testing and running simply use the `go` tool. All episodes are buildable and testable, but some don't have a `package main` because they're libraries, so they won't be runnable.

- build: `go build`
- test: `go test`
- run: `go build -o example && ./example`
