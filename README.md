mm
==

Open-MMLab CLI Tool

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/mm.svg)](https://npmjs.org/package/mm)
[![CircleCI](https://circleci.com/gh/innerlee/mm/tree/master.svg?style=shield)](https://circleci.com/gh/innerlee/mm/tree/master)
[![Appveyor CI](https://ci.appveyor.com/api/projects/status/github/innerlee/mm?branch=master&svg=true)](https://ci.appveyor.com/project/innerlee/mm/branch/master)
[![Codecov](https://codecov.io/gh/innerlee/mm/branch/master/graph/badge.svg)](https://codecov.io/gh/innerlee/mm)
[![Downloads/week](https://img.shields.io/npm/dw/mm.svg)](https://npmjs.org/package/mm)
[![License](https://img.shields.io/npm/l/mm.svg)](https://github.com/innerlee/mm/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g mm
$ mm COMMAND
running command...
$ mm (-v|--version|version)
mm/0.0.1 linux-x64 node-v15.4.0
$ mm --help [COMMAND]
USAGE
  $ mm COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`mm hello [FILE]`](#mm-hello-file)
* [`mm help [COMMAND]`](#mm-help-command)

## `mm hello [FILE]`

describe the command here

```
USAGE
  $ mm hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ mm hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/innerlee/mm/blob/v0.0.1/src/commands/hello.ts)_

## `mm help [COMMAND]`

display help for mm

```
USAGE
  $ mm help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.1/src/commands/help.ts)_
<!-- commandsstop -->
