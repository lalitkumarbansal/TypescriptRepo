# Basic Commands

**Installing typescript**

```npm install -g typescript ```

**Compiling TS to javascript**

``` tsc index.js ```

or 

``` npx tsc index.js ```

Two things will happen
- npx will cause latest typescript to be used in npm repos and not on your local system.So if you have TypeScript 5.3 running on your computer and the
latest executable is 5.7 on npm, then tsc is going to compile using 5.7.
- It is always going to pick up tz config files global tz configuration, which is available on npm.

**Generating TS config**

``` tsc --init```

This will create tsconfig.json file 
