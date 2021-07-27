# v-dl

A simple web and terminal download client.

## Installation

For full installation you can clone the repo through:

```bash
$ git clone https://github.com/ngenohkevin/v-dl.git
$ cd v-dl
$ go run main.go
```

This step assumes that you have go installed on your machine and are using a UNIX-style system.
More installation instructions to be added later.

## Features to be Implemented

- [ ] Get a better name
- [ ] Set up CLI folder structure
- [ ] Set up Web API folder structure
- [ ] Set up dockerfile and docker-compose for running application
- [ ] Write functions for download (core of the app)
- [ ] Add download options
- [ ] Add tests to confirm functions work as expected
- [ ] Create flags and CLI application
- [ ] Create API base for the client download application
- [ ] Create Client folder for web client to access download options on the web
- [ ] Create sample site for advertising the product
- [ ] Add additional fields for download options like video quality and pause and resume options
- [ ] Improve documentation for the package and application including addition of a wiki page
- [ ] Create desktop app for easier use
- [ ] Create and publish a package and binaries for downloads

## Packages to be used

- Gorilla mux(API)
- Cobra(CLI)
- React/Svelte(Web based Client) -TBD
