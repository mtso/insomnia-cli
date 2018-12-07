# Insomnia CLI

[![npm version](https://badge.fury.io/js/insomnia-cli.svg)](https://badge.fury.io/js/insomnia-cli)

An Insomnia CLI runner. Run a group of request chains like a robot.

## Installation

```
npm install --global insomnia-cli
```

Installing `insomnia-cli` will add the executable script `insomniac`.

## Usage

```
Insomnia REST CLI Runner

  Runs Insomnia requests like a robot, not a human.

Synopsis

  $ insomniac [filepath to Insomnia export] --request-groups [folder]
  --environment [sub environment]

Options

  -g, --request-groups folder   (REQUIRED) The folder of requests to run. The folder names are found in the
                                insomnia workspace.
  -e, --environment name        (REQUIRED) Name of sub environment which contains environment variables.
  -o, --output filepath         Filepath to save output results.
  -d, --delay milliseconds      Milliseconds to delay each request by (defaults to 0).
  -h, --help                    Print this usage guide.
```
