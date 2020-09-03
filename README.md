# Elm Flatris
A [Flatris](https://github.com/skidding/flatris) clone in Elm.

[![Screenshot](elm-flatris.png)](https://unsoundscapes.itch.io/flatris)

Current demo can be seen [here](https://unsoundscapes.itch.io/flatris).

## Features

* works on both desktop and mobile
* renders the grid with `elm/svg`
* preserves the game state in `localStorage` using ports, just try to reload the page while playing!

## Instructions to run

1. Install elm [elm-lang.org/install](http://elm-lang.org/install)
2. Clone this repo and `cd` into it
3. Run `elm make src/Main.elm --output elm.js`
4. Open `index.html` in the browser


## Fission deploy
To deploy it on [Fission](https://fission.codes/), you only need to do some simple steps:

* Clone this project and change the branch to `dev`
* Verify that the `Main.elm` was changed to `Flatris.elm` due to an issue in the original code
* Init your node in [IPFS](https://ipfs.io/) with `ipfs daemon &` on another tab
* Run `fission app-init` inside the folder of the flatris project
* Run `fission up`, and its done!