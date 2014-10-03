Cmd-Enter
=========

> *Important Note: * This plugin is retired since [Sketch 3.1](http://bohemiancoding.com/sketch/support/updates/) now has native support of `Cmd+Enter` shortcut.

A tiny Sketch 3 plugin that allows to use `Cmd` + `Enter` shortcut to apply changes to a text layer that is being edited.

Here is a short screencast:

<a href="http://youtu.be/GllIqsxmP1o" target="_blank"><img src="http://turbobabr.github.io/cmd-enter/images/play-cmd-enter-screencast.png" alt="Sketch 3 Cmd+Enter Plugin Screencast"/></a>


#### The Problem

In Sketch, there are two ways one can finish text layer editing process:

1. Hit `Esc` key on a keyboard.
2. Mouse click outside of the text layer being edited.

However, both methods have their drawbacks:

1. When I hit `Esc` key it does what I want - Sketch exits editing mode and keeps the layer selected, but here I have a deep sense that something is being CANCELLED. Also `Esc` key is located pretty far away from the "hot zone".
2. Whenever I click outside of the text layer bounds - Sketch exits editing mode and deselects the layer, but usually I want to play with it for a while (e.g, change font size, color, etc).


#### The Solution

The standard pattern for applying changes in a multi-line text fields is using `Cmd` + `Enter` shortcut, but Sketch doesn't support it. Whenever you hit `Cmd` + `Enter` Sketch produces a loud "bump" sound instead of expected "Save it!" behaviour.

Recently I've found out a way to emulate the desired behaviour using custom scripting. Wrote a plugin that is bound to `Cmd` + `Enter` shortcut and on launch it simulates 'Esc' key press. So the problem is solved: I have a sense that I apply changes and Sketch keeps my text layer selected! Probably I'm the only person who's suffering without `Cmd` + `Enter` feature, but anyway I decided to share the plugin with the community.

### Installation and Usage

1. Download [cmd-enter.sketchplugin](https://github.com/turbobabr/cmd-enter/raw/master/cmd-enter.sketchplugin) file.
2. Double-Click it to install in plugins folder.

Use combination of `Cmd` + `Enter` keys during text layer editing process!

### License

The MIT License (MIT)

Copyright (c) 2014 Andrey Shakhmin

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
