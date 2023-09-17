# `rspack` test

Test `rspack` when `package.json` contains a workspace property.

After installing dependencies with `pnpm i`, invoking `npx rspack --version` fails in the folder `packages/gui`.

```bash
erik@PC-28020:~/dev/rspack-test/packages/gui$ npx rspack --version
npm ERR! could not determine executable to run

npm ERR! A complete log of this run can be found in:
npm ERR!     /home/erik/.npm/_logs/2023-09-17T10_40_28_094Z-debug-0.log
```
