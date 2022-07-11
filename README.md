# Iceman

Iceman is an advanced Twine 2 story format at low temperature designed for people who already know JavaScript and CSS.
It is a fork of [Snowman](https://github.com/videlais/snowman/) story format originally created by Chris Klimas and currently maintained by Dan Cox.

The first story built on top of Iceman is [Cerveeelliii](https://github.com/jenkin/cerveeelliii), now under development.

## Difference from Snowman

Iceman version will follow Snowman (ie. `3.0.0`) plus a counter of new sub-releases (ie. `3.0.0-1`).

## Building

Run `npm install` to install dependencies.

`npm run build` will create a Twine 2-ready story format under `dist/`.

To check for style errors, run `npm run lint`.
To run unit tests, run `npm run test`.
