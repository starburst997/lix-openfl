# lix-openfl

A simple test of [lix](https://github.com/lix-pm/lix.client) with [OpenFL](https://github.com/openfl/openfl).

To use globally:
```
yarn global add git+ssh://git@github.com/starburst997/lix.client.git#develop
openfl test html5
```

Or locally:
```
yarn install
yarn lix run openfl test html5
```

Everything seems to work perfectly! Makes sure you use the lime extension in VSCode. For Lix you need to use my custom branch for now ([Lix](https://github.com/starburst997/lix.client) / [Haxeshim](https://github.com/starburst997/haxeshim)) as seen above, I have some PRs sent to fix OpenFL's CLI for use with Lix.