# Basic Commands

**Installing typescript**

```npm install -g typescript ```
or
```npm install --save-dev typescript @types/node```

**Compiling TS to javascript**

``` tsc index.js ```

or 

``` npx tsc index.js ```

Two things will happen
- npx will cause latest typescript to be used in npm repos and not on your local system.So if you have TypeScript 5.3 running on your computer and the
latest executable is 5.7 on npm, then tsc is going to compile using 5.7.
- It is always going to pick up tz config files global tz configuration, which is available on npm.

**Generating TS config**

``` tsc init```

This will create tsconfig.json file 

**Initializing an npm project**

``` npm init```

This will create pcakage.json file 


**Add following section to package.json**
```   

"scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start:dev": "tsc --watch",
    "start": "node index.js"
  }

```

**Run the following command to keep the development mode on**
``` node run start:dev ```

**Importing node type modules**
Typescript does not understand by react or node types for this we need to install type modules

``` npm install @types/react --save-dev```
``` npm install @types/node  --save-dev```

There is repository for these types https://github.com/DefinitelyTyped/DefinitelyTyped




