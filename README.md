# robotframework-sublime2-snippets

Some [Sublime Text 2 snippets](http://www.sublimetext.com/2) for [Robot Framework](http://robotframework.org).

## Installation on Linux and Windows

Find out where you should copy the snippets from [Sublime 2 homepage](http://www.sublimetext.com/2). Then follow instructions under [Installation on OS X](/#Installation-on-OS-X).

## Installation on OS X

Clone this repository. Copy all snippets to Sublime 2's directory:

    cd /path/to/this/repo
    cp *.sublime-snippets ${HOME}/Library/Application Support/Sublime Text 2/Packages/User


You don't need to restart Sublime 2. They should just work.

### Alternative

If you do want the snippets to be updatable with `git clone`, utilise symbolic links instead of copying.

## Snippets

- \*s&#8677; -- `*** Settings ***`
- \*v&#8677; -- `*** Variables ***`
- \*t&#8677; -- `*** Test Cases ***`
- \*k&#8677; -- `*** Keywords ***`

## Protip

Combine these snippets with [sublime-robot-plugin](https://github.com/shellderp/sublime-robot-plugin). The plugin provides some nifty features, being able to run Robot test cases directly from Sublime being the chief one.


