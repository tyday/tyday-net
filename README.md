# tyday-net
Personal website deployed to Amazon amplify

## Background

Each visit picks one of two backgrounds at random, with a link to switch:

- Pong, inline in `index.html`.
- A dungeon crawl from the guild game. `guild-ambient.js` is built from the
  [guild-master](https://github.com/tyday/guild-master) repo with
  `npm run build:ambient`, then copied here from `dist-ambient/`.

## Versions

The version number sits at the bottom of `index.html` and links to
`changelog.html`. When you release a change, add an entry to the top of the
changelog and bump the number in `index.html` to match.
