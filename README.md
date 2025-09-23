[![add-on registry](https://img.shields.io/badge/DDEV-Add--on_Registry-blue)](https://addons.ddev.com)
[![tests](https://github.com/cambrico/ddev-mysqlshell/actions/workflows/tests.yml/badge.svg?branch=main)](https://github.com/cambrico/ddev-mysqlshell/actions/workflows/tests.yml?query=branch%3Amain)
[![last commit](https://img.shields.io/github/last-commit/cambrico/ddev-mysqlshell)](https://github.com/cambrico/ddev-mysqlshell/commits)
[![release](https://img.shields.io/github/v/release/cambrico/ddev-mysqlshell)](https://github.com/cambrico/ddev-mysqlshell/releases/latest)

# DDEV MySQL Shell

## Overview

This add-on integrates MySQL Shell into your [DDEV](https://ddev.com/) project.

## Installation

```bash
ddev add-on get cambrico/ddev-mysqlshell
ddev restart
```

After installation, make sure to commit the `.ddev` directory to version control.

## Commands

The following commands are available:

| Command          | Usage                           |
|------------------|---------------------------------|
| `mysqlsh`        | `ddev mysqlsh [options]`        |
| `mysqlsh-export` | `ddev mysqlsh-export`           |
| `mysqlsh-import` | `ddev mysqlsh-import [options]` |

## Credits

**Contributed and maintained by [@cambrico](https://github.com/cambrico)**
