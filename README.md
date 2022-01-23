# Wordle Clone

- Play the real Wordle [here](https://www.powerlanguage.co.uk/wordle/)

- Built with React, Typescript, and Tailwind


- The word match functionality is simple: the word array index increments each day from a fixed game epoch timestamp.

```
WORDS[Math.floor((NOW_IN_MS - GAME_EPOCH_IN_MS) / ONE_DAY_IN_MS)]
```

# To Run Locally:
Clone the repository and perform the following command line actions:
```bash
$ cd wordle
$ npm install
$ npm run start
```

# To build/run docker container:
```bash
$ docker build -t notwordle .
$ docker run -d -p 3000:3000 notwordle
```
open http://localhost:3000 in browser.

