# OCLIF Example 1

## Code History

The code in this repository is based on the following.

- https://www.joshcanhelp.com/oclif/

## Creation History

```bash
cd oclif-ex1/
npm init -y
npm install typescript
echo create tsconfig.json
echo create src/index.ts
npm exec tsc
node ./dist/index.js
npx oclif init
echo create src/commands/hello.ts
npx tsc -w
./bin/run.js hello
echo add args and flags to hello.ts above
echo below automatically generate the hello2 command
npm exec oclif generate command hello2

npm exec oclif readme
```

## Table of contents

<!-- toc -->
* [OCLIF Example 1](#oclif-example-1)
<!-- tocstop -->

## Usage

<!-- usage -->
```sh-session
$ npm install -g oclif-ex1
$ oclif-ex1 COMMAND
running command...
$ oclif-ex1 (--version)
oclif-ex1/1.0.0 linux-x64 node-v20.11.1
$ oclif-ex1 --help [COMMAND]
USAGE
  $ oclif-ex1 COMMAND
...
```
<!-- usagestop -->

## Commands

<!-- commands -->
* [`oclif-ex1 hello [ARG1]`](#oclif-ex1-hello-arg1)
* [`oclif-ex1 hello2 [FILE]`](#oclif-ex1-hello2-file)

## `oclif-ex1 hello [ARG1]`

```
USAGE
  $ oclif-ex1 hello [ARG1] [--flag]

FLAGS
  --flag
```

## `oclif-ex1 hello2 [FILE]`

describe the command here

```
USAGE
  $ oclif-ex1 hello2 [FILE] [-f] [-n <value>]

ARGUMENTS
  FILE  file to read

FLAGS
  -f, --force
  -n, --name=<value>  name to print

DESCRIPTION
  describe the command here

EXAMPLES
  $ oclif-ex1 hello2
```
<!-- commandsstop -->
