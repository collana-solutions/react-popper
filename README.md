# React Popper

[![Unit Tests](https://github.com/popperjs/react-popper/workflows/Unit%20Tests/badge.svg)](https://github.com/popperjs/react-popper/actions?query=workflow%3A%22Unit+Tests%22)
[![npm version](https://img.shields.io/npm/v/@collana-solutions/react-popper.svg)](https://www.npmjs.com/package/@collana-solutions/react-popper)
[![npm downloads](https://img.shields.io/npm/dm/@collana-solutions/react-popper.svg)](https://www.npmjs.com/package/@collana-solutions/react-popper)
[![Dependency Status](https://david-dm.org/souporserious/react-popper.svg)](https://david-dm.org/souporserious/react-popper)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![Get support or discuss](https://img.shields.io/badge/chat-on_spectrum-6833F9.svg?logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyBpZD0iTGl2ZWxsb18xIiBkYXRhLW5hbWU9IkxpdmVsbG8gMSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB2aWV3Qm94PSIwIDAgMTAgOCI%2BPGRlZnM%2BPHN0eWxlPi5jbHMtMXtmaWxsOiNmZmY7fTwvc3R5bGU%2BPC9kZWZzPjx0aXRsZT5zcGVjdHJ1bTwvdGl0bGU%2BPHBhdGggY2xhc3M9ImNscy0xIiBkPSJNNSwwQy40MiwwLDAsLjYzLDAsMy4zNGMwLDEuODQuMTksMi43MiwxLjc0LDMuMWgwVjcuNThhLjQ0LjQ0LDAsMCwwLC42OC4zNUw0LjM1LDYuNjlINWM0LjU4LDAsNS0uNjMsNS0zLjM1UzkuNTgsMCw1LDBaTTIuODMsNC4xOGEuNjMuNjMsMCwxLDEsLjY1LS42M0EuNjQuNjQsMCwwLDEsMi44Myw0LjE4Wk01LDQuMThhLjYzLjYzLDAsMSwxLC42NS0uNjNBLjY0LjY0LDAsMCwxLDUsNC4xOFptMi4xNywwYS42My42MywwLDEsMSwuNjUtLjYzQS42NC42NCwwLDAsMSw3LjE3LDQuMThaIi8%2BPC9zdmc%2B)](https://spectrum.chat/popper-js/react-popper)

React wrapper around [Popper](https://popper.js.org).

This is the collana solutions fork of
[react-popper](https://github.com/floating-ui/react-popper), published as
`@collana-solutions/react-popper` for React 18 and 19. The library and its
documentation are the work of the react-popper authors.

---

## ⚠️ This library is in maintenance mode!

This library wraps `@popperjs/core`, not `@floating-ui/dom`.

To use the new Floating UI package with React, instead visit
https://floating-ui.com/docs/react-dom.

---

## Install

Via package managers:

```bash
# With npm
npm i @collana-solutions/react-popper @popperjs/core

# With Yarn
yarn add @collana-solutions/react-popper @popperjs/core
```

**Note:** `@popperjs/core` must be installed in your project in order for
`@collana-solutions/react-popper` to work.

Via `script` tag (UMD library exposed as `ReactPopper`):

```html
<script src="https://unpkg.com/@collana-solutions/react-popper/dist/index.umd.js"></script>
```

## Documentation

The full documentation can be found on the official Popper website:

http://popper.js.org/react-popper

Import from `@collana-solutions/react-popper` wherever the documentation imports
from `react-popper`.

## Running Locally

#### clone repo

`git clone git@github.com:collana-solutions/react-popper.git`

#### move into folder

`cd ~/react-popper`

#### install dependencies

`corepack pnpm install`

#### run dev mode

`corepack pnpm run demo:dev`

#### open your browser and visit:

`http://localhost:1234/`
