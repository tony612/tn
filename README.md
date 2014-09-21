# tn(terminal-notifier)

tn is a wrapper for [terminal-notifier](https://github.com/alloy/terminal-notifier)
to make a terminal notification after some command is done

## Installation

```
$ brew tap tony612/pat
$ brew install tn
```

or

```
$ brew install tony612/pat/tn
```

## Usage

Just prepend `tn` to your command

```
$ tn rake -T
```

You'll receive the notification if it successes

![](https://cloud.githubusercontent.com/assets/1253659/4245092/6441499a-3a2e-11e4-9a5f-f66157668c75.png)

However, for a failed command like this

```
$ tn rake foo
```

you'll get

![](https://cloud.githubusercontent.com/assets/1253659/4245100/90945ae6-3a2e-11e4-9d08-4a7e7f90c2e3.png)

## TODO

- ~~Installation via homebrew~~
- Completions  

## Copyright

Copyright (c) 2014 Tony Han. See [LICENSE](/LICENSE) for details.
