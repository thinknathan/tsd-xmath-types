# @types/tsd-xmath

TypeScript types for thejustinwalsh's [defold-xmath](https://github.com/thejustinwalsh/defold-xmath), a Defold Math eXtention Library that avoids allocations.

For use with [TS-Defold](https://github.com/ts-defold) and [TypeScriptToLua](https://github.com/TypeScriptToLua).

The documentation comments are copied from Defold's vmath library with some modifications; they may not be 100% accurate to xmath's implementation.

## Installation

1. Create a [TS-Defold](https://github.com/ts-defold) project
2. Add [defold-xmath](https://github.com/thejustinwalsh/defold-xmath) to your Defold project
3. Import these types

```bash
yarn add git+https://git@github.com/thinknathan/tsd-xmath-types.git#^1.0.0 -D
# or
npm install git+https://git@github.com/thinknathan/tsd-xmath-types.git#^1.0.0 --save-dev
```

4. Add `tsd-xmath` to `types` in `tsconfig.json`

```diff
{
	"compilerOptions": {
		"types": [
+			"tsd-xmath",
		],
	}
}
```

5. Add `node_modules/@types` to `typeRoots` in `tsconfig.json` if it's not already there

```diff
{
	"compilerOptions": {
		"typeRoots": [
+			"node_modules/@types",
		],
	}
}
```

## License

MIT

Comments are adapted from [Defold's](https://github.com/defold/) code comments.
