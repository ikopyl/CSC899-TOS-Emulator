# CSC899-TOS-Emulator

### Building the Project

#### Prerequisites

* Node.js
* Python2

1. [Install Nodejs and NPM for your OS](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm):
   ```bash
   npm install -g npm
   ```
2. [Install Typescript](https://www.typescriptlang.org/)
   ```bash
   npm install -g typescript
   ```
3. [Install Alsatian](https://github.com/alsatian-test/alsatian/wiki/typescript-setup), the testing framework
   ```bash
   npm install -g alsatian
   ```
4. Install ts-pegjs
   ```bash
   npm install -g ts-pegjs
   ```
5. Additional dependencies:
   ```
   npm install -g node-gyp
   npm install -g @angular/cli
   ```

#### Build Instructions

1. Build `x86` library
   ```bash
   cd x86

   # install dependencies
   npm install

   # build the library
   npm run build
   ```

2. Build and run web-emulator of x86 machine
   ```
   # from project root
   cd webapp

   # install dependencies
   npm install

   # build Angular webapp
   ng build

   # run Angular webapp
   ng serve
   ```
