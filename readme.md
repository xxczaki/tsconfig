# tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for my projects


## Install

```
$ npm install --save-dev @akepinski/tsconfig
```


## Usage

`tsconfig.json`

```json
{
	"extends": "@akepinski/tsconfig",
	"compilerOptions": {
		"outDir": "dist",
		"target": "esnext"
	}
}
```

## Notes

Inspired by [Sindre Sorhus' tsconfig](https://github.com/sindresorhus/tsconfig)


## License

MIT
