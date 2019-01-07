# lix-openfl

A simple test of [lix](https://github.com/lix-pm/lix.client) with [OpenFL](https://github.com/openfl/openfl).

Current version of lix on NPM doesn't have the patch for haxeshim to properly return `haxelib path` making openfl / lime command line useless, so this project use my fork of lix until it get into NPM.

To use:
```
yarn install
yarn lix run openfl test html5
```

Command line output currently have some issue with a bunch of `Uncaught exception - Could not find NekoAPI interface.` showing up but it seems to work!