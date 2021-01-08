# Squirrel

This is a basic agent-based macos application which is created by SPM(Swift Package Manager). I read a [post](https://rderik.com/blog/understanding-a-few-concepts-of-macos-applications-by-building-an-agent-based-menu-bar-app/) to learn how to develop a macos app.

## build and run

to build, please execute

```bash
make install
```

if you want to run directly, you can execute command below

```bash
make run
```

## keywords

- creating an executable using the SPM: `swift package init -- type executabl`
- swift package structure
- lifecycle of a macos app: `AppDelegate`、`@NSApplicaitonMain`、`RunLoop` and applicaiton property list `plist`
- macos bundle files
- agent-based
- create a `Makefile`
