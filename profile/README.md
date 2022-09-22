# LeakTK - Leak Tool Kit

LeakTK (pronounced "leaked") is a place to open source and colaborate on some existing projects related to leak detection and prevention as well as greenfield a few new projects.

After enough of the individual components are brought over, a `leaktk` project will be added that starts tying them all together.

## Status

* Patterns and fake-leaks repos added
* New gitleaks 8 patterns planned
* Scanner work started

## Future Project Ideas & Notes

### browser-plugin

* mvp - a few hard coded patterns, notifies users when they've pasted something that matches one
* next - integrates with both unauthed and authed pattern servers
* ideal - scanner compiled down into a wasm or simlar and included as the engine for the plugin and talks to the pattern server and the plugin supports allowlist config.
