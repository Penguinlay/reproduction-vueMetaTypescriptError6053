# reproduction-vueMetaTypescriptError6053

This is the minimal reproduction of the issue.

## Reproduction Steps

1. Install Yarn if you have not already.
2. Clone this repo.
3. Go to cloned repo directory.
4. Run `yarn vue-tsc --noEmit`.
5. The Typescript Error 6053 will be printed out for https://github.com/nuxt/vue-meta/blob/eec4e7c7c00dfff74edd29675421052596bbada1/dist/vue-meta.d.ts#L9.

## Typescript Error 6053

```node
node_modules/vue-meta/dist/vue-meta.d.ts:9:22 - error TS6053: File '/Users/shein/kk/gh/reproduction-vueMetaTypescriptError6053/node_modules/vue-meta/dist/ssr.d.ts' not found.

9 /// <reference path="ssr.d.ts" />
                       ~~~~~~~~
```
