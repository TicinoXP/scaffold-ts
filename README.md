# Scaffold - TypeScript version

## Set up your dev box

Make sure you have TypeScript installed:

```bash
$ tsc --version
Version 5.3.2
```

## Set up your dev box

- Make sure you have TypeScript installed:

```bash
$ tsc --version
Version 5.3.2
```

- Clone this repo:

```bash
git clone git@github.com/ticinoxp/scaffold-ts
```

and setup npm:

```bash
npm install
```

## Run the tests:
Run:

```bash
npm test
```

or:

```bash
npm test -- --watchAll
```

if you wish tests to be re-executed at any file modification.


## Re-create
If you wish to recreate this repo from the scratch, use the following:

```bash
# Initialize a new npm project with default settings. The -y flag automatically confirms
npm init -y

# Install the TypeScript compiler as a development dependency for your project
# The --save-dev flag adds TypeScript to the devDependencies section of your package.json,
# meaning it won't be included when your project is deployed to production environments
npm install typescript --save-dev

# Initializes a TypeScript configuration file (tsconfig.json) in your project.
# This file specifies the root files and the compiler options required to compile the project.
npx tsc --init

# Install jest for running tests
npm install jest ts-jest @types/jest --save-dev
```
