# Basic Commands

Installing typescript
```npm install -g typescript ```

Compiling TS to javascript

``` tsc index.js ```

or 

``` npx tsc index.js ```

Two things will happen
- npx will cause latest typescript to be used in npm repos and not on your local system
- It is always going to pick up tz config files global tz configuration, which is available on npm.
