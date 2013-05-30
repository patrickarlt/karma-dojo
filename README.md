# A simple example of using Karma on a Dojo website

This example serves a debugging purpose to try to make Karma running with Dojo.

## Current State

The test page `index.html` is working.

## What's not working

### Launching the tests

When Karma is launched, the files that should be loaded by Dojo are canceled:
[img/dev-tools.png]

Because of this, no tests are loaded/executed and the terminal shows a success message.

### Debug mode

On debug mode, the browser console shows:
```
SUCCESS just checking works for app debug.html:29
Uncaught TypeError: Cannot read property 'failedCount' of null jasmine.js:67
```

## Note

This sample is inspired by [karma-requirejs](https://github.com/kjbekkelund/karma-requirejs).
Let's hope we can make it work as well!
