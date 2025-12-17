# syncpack-issue

Using v13.0.4:

```
$ pnpm exec syncpack list
= Default Version Group ========================================================
1x p1: PACKAGE_JSON_HAS_NO_VERSION
1x syncpack: 13.0.4
1x syncpack-issue: PACKAGE_JSON_HAS_NO_VERSION
1x typescript: 5.9.3

What next?
- syncpack list-mismatches to see more detail about mismatching versions
- syncpack fix-mismatches to fix version mismatches automatically
- syncpack format to sort and prettify your package.json files
- syncpack update to choose updates from the npm registry
- syncpack --help for everything else
```

Using 14.0.0-alpha.32:

```
$ pnpm exec syncpack list
= Default Version Group ========================================================
   1x @dprint/formatter ^0.4.1
   1x @dprint/typescript 0.93.4
   1x @esfx/canceltoken ^1.0.0
   1x @eslint/js ^9.20.0
   1x @octokit/rest ^21.1.1
   1x @types/chai ^4.3.20
   1x @types/diff ^7.0.1
   1x @types/minimist ^1.2.5
   1x @types/mocha ^10.0.10
   1x @types/ms ^0.7.34
   1x @types/node latest (DiffersToHighestOrLowestSemver)
   1x @types/source-map-support ^0.5.10
   1x @types/which ^3.0.4
   1x @typescript-eslint/rule-tester ^8.24.1
   1x @typescript-eslint/type-utils ^8.24.1
   1x @typescript-eslint/utils ^8.24.1
   1x azure-devops-node-api ^14.1.0
   1x c8 ^10.1.3
   1x chai ^4.5.0
   1x chokidar ^4.0.3
   1x diff ^7.0.0
   1x dprint ^0.49.0
   1x esbuild ^0.25.0
   1x eslint ^9.20.1
   1x eslint-formatter-autolinkable-stylish ^1.4.0
   1x eslint-plugin-regexp ^2.7.0
   1x fast-xml-parser ^4.5.2
   1x glob ^10.4.5
   1x globals ^15.15.0
   1x hereby ^1.10.0
   1x jsonc-parser ^3.3.1
   1x knip ^5.44.4
   1x minimist ^1.2.8
   1x mocha ^10.8.2
   1x mocha-fivemat-progress-reporter ^0.1.0
   1x monocart-coverage-reports ^2.12.1
   1x ms ^2.1.3
   1x p1 (local) (InvalidLocalVersion)
   1x picocolors ^1.1.1
   1x playwright ^1.50.1
   1x source-map-support ^0.5.21
   1x syncpack 14.0.0-alpha.32
   1x syncpack-issue (local) (InvalidLocalVersion)
   1x tslib ^2.8.1
   3x typescript 5.9.3 (local) (DiffersToLocal)
   1x typescript-eslint ^8.24.1
   1x typescript@*
   1x which ^3.0.1
```