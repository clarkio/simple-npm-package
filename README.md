<div align="center">

# Simple npm Package

A simple npm package for demonstration purposes and use in a Node.js app.

[![Known Vulnerabilities](https://snyk.io/test/github/clarkio/simple-npm-package/badge.svg)](https://snyk.io/test/github/clarkio/simple-npm-package)
![GitHub](https://img.shields.io/github/license/clarkio/simple-npm-package)
[![Discord](https://img.shields.io/discord/421902136457035777)](https://discord.gg/xB95beJ)
[![Twitch Status](https://img.shields.io/twitch/status/clarkio)](https://twitch.tv/clarkio)
<br>
[![Twitter Follow](https://img.shields.io/twitter/follow/_clarkio?style=social)](https://twitter.com/intent/follow?screen_name=_clarkio)

</div>

## Get Started

Follow these steps to publish your own npm package for your own project or using this project.

> This is using the CommonJS module format for use in Node.js apps. You can read more about CommonJS vs. ESM module formats in Node.js on the [LogRocket Blog](https://blog.logrocket.com/commonjs-vs-es-modules-node-js/)

1. [Create a GitHub Repository](https://github.com/new)
1. Clone the repo locally. Example `git clone https://github.com/clarkio/simple-npm-package.git`
1. Open your terminal and change directories to the folder of your cloned project. Example `cd simple-npm-package`
1. Run `npm init -y` to create a `package.json` file. Note: if you cloned this repository you won't need to do this step.
1. Update package.json name property with a scoped name. Example `@clarkio/simple-npm-package`. Be sure to use your username or organization name instead of mine.
1. Write code for the package (or just use the hello world example in `index.js`)
1. [Sign up with npm](https://www.npmjs.com/signup). Also for better security be sure to enable [two-factor authentication](https://docs.npmjs.com/configuring-two-factor-authentication) on your npm account.
1. Sign in with your npm account in your terminal using the command `npm login` and follow the on-screen instructions.
1. Run `npx npm-packlist` to see the contents that will be included in the published version of the package.
1. Run `npm publish --dry-run` to see what would be done when actually running the command.
1. Run `npm publish --access=public` to actually publish the package to npm. Note: --access=public is needed for scoped packages (`@clarkio/simple-npm-package`) as they're private by default. If it's not scoped and doesn't have the `private` field set to `true` in `package.json` it will be public as well.
