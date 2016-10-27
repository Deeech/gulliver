# gulliver

## Installation

```
git clone https://github.com/Deeech/gulliver.git && cd gulliver/
npm install
npm install -g gemini
npm install -g selenium-standalone
npm install -g http-server
selenium-standalone install
```

## Usage
```
npm start
```

Start these commands in a separate tab before running the tests:
```
http-server site/
selenium-standalone start
```

Run gemini tests
```
npm run update
npm test
```

Open gemini report file `gemini-report/index.html`
