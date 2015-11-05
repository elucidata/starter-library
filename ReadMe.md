# Starter Library

A simple "get up and running quickly" project starter for libraries. Not meant
to be gospel, nor even suggested structure -- Merely a fast way to start a
project that could be built for production in a pinch.


## Development

```
$ npm start
```

Open your browser to <http://localhost:8080> and you're good to go!


## Building

Build scripts are just javascript files under: `tools/`. Run them directly:

```
$ babel-node tools/run build
```

Or via npm scripts:

```
$ npm run build
```

## Main Entry

The main entry is at: `app/main.ts`

That's really all you need to know to get started!

## Todo

- [ ] Simple test harness
