# Source Map Users

A list of all source map users.

## Generators (tools that create .map files)

+ [Closure Compiler](https://github.com/google/closure-compiler/wiki/Source-Maps)
+ [gen-mapping](https://github.com/jridgewell/gen-mapping)
  + [Babel](https://github.com/babel/babel)
+ Languages
  + [ClojureScript](https://clojurescript.org/reference/source-maps) ([code](https://github.com/clojure/clojurescript/blob/master/src/main/cljs/cljs/source_map.cljs))
  + [Dart](https://dart.dev/web/debugging) ([code](https://github.com/dart-lang/source_maps))
  + [Flow](https://github.com/facebook/flow/tree/7a73dde7a8a2cc8f6587c81502a9701c486c46a1/packages/flow-remove-types#pretty-transform) (or via Babel)
  + [F#/Fable](https://fable.io/docs/getting-started/cli.html#options)
  + [Haxe](https://haxe.org/manual/debugging-source-map.html)
  + [Imba](https://github.com/imba/imba/blob/be25194d5de9cde6704519cebbd549d9e234b1fb/packages/imba/changelog.md?plain=1#L359) ([code](https://github.com/imba/imba/blob/be25194d5de9cde6704519cebbd549d9e234b1fb/packages/imba/src/compiler/sourcemap.imba1#L13))
  + [Kotlin/JS](https://kotlinlang.org/docs/compiler-reference.html#source-map)
  + [Nim](https://github.com/nim-lang/Nim/pull/7508)
  + [PureScript/Spago](https://github.com/purescript/spago#enable-source-maps) ([code](https://github.com/purescript/purescript/blob/2070d479d133da9a7c33f7572ca7adb45a4c7aee/src/Language/PureScript/Make/Actions.hs#L286))
  + [TypeScript](https://www.typescriptlang.org/tsconfig/#sourceMap) ([code](https://github.com/microsoft/TypeScript/blob/main/src/compiler/sourcemap.ts))
+ Frameworks
  + [Angular](https://angular.dev/reference/configs/workspace-config#source-map-configuration)
  + [Ionic](https://ionicframework.com/docs/ja/v7/cli/commands/build#advanced-options)
  + [React Native](https://reactnative.dev/docs/debugging-release-builds#enabling-source-maps)
  + [Svelte](https://svelte.dev/docs/svelte-compiler#types-compileoptions)

## Consumers (tools that read in .map files)

+ [Chrome Devtools](https://github.com/ChromeDevTools/devtools-frontend)
+ [Mozilla Sourcemap](https://github.com/mozilla/source-map)
+ [NodeJS](https://medium.com/the-node-js-collection/source-maps-in-node-js-5d0abe6ac34b)
+ [trace-mapping](https://github.com/jridgewell/trace-mapping)
+ [Webkit](https://github.com/WebKit/WebKit/)

## Error monitoring tools 

+ [Replay.io](https://replay.io/)
+ [Sentry](https://sentry.io/welcome/)

## Bundlers and build tools

+ [Bun Bundler](https://bun.sh/docs/bundler#sourcemap)
+ [ESBuild](https://esbuild.github.io/api/#source-maps) ([code](https://github.com/evanw/esbuild/blob/67cbf87a4909d87a902ca8c3b69ab5330defab0a/internal/sourcemap/sourcemap.go))
+ [Gulp.js](https://github.com/gulpjs/vinyl-sourcemap)
+ [Rollup](https://rollupjs.org/configuration-options/#output-sourcemap) ([code](https://github.com/rollup/rollup/blob/1a7da5ac529d543ad8fffd1cdfbf9a80040a1176/src/utils/collapseSourcemaps.ts))
+ [Webpack](https://survivejs.com/books/webpack/building/source-maps/#-sourcemapdevtoolplugin-and-evalsourcemapdevtoolplugin-)
