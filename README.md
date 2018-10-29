<p align="center">
  <img alt="Reason Expo Logo" src="./reason-expo.png" width="256">
</p>

<h3 align="center" style="font-weight:600">
  reason-expo
</h3>

<p align="center">
  <a href="https://reasonml.github.io/">ReasonML</a> bindings for <a href="https://expo.io">Expo</a>
</p>

---

<div align="center">

[![NPM version badge](https://img.shields.io/npm/v/reason-expo.svg)](https://www.npmjs.com/package/reason-expo)

</div>

## Getting started

Download the ReasonExpo template included in this repo by running the commands below in the terminal.

```
git clone https://github.com/FiberJW/reason-expo.git
mv reason-expo/template . && rm -rf reason-expo
cd template && yarn
yarn build && yarn start
```

Already have an existing Expo Project?

Follow [BsReactNative's Getting Started guide](https://reasonml-community.github.io/bs-react-native/BsReactNative/gettingstarted.html#integrating-with-existing-rn-project), install reason-expo with `yarn add reason-expo` and add it to your bs-dependencies list in bsconfig.json.

## Disclaimer

There are some APIs missing/in-development. Compare this repo to the APIs listed in [Expo's Docs](https://docs.expo.io) to see what's missing. Contributing new API bindings is extremely encouraged!

## Contributing

Find the missing API[s] that you want to bind to in [Expo's Docs](https://docs.expo.io). Next, fork this repo, clone it onto your machine, install dev dependencies with `yarn install::dev`, start the compiler with `yarn start`, and start hacking away!

_Credit: This project is based on the work started in [`bs-expo`](https://github.com/fxfactorial/bs-expo/)._
