# kb-bindings-ui

A graphical interface for configuring kb-bindings or
[game-shell](https://github.com/mikolalysenko/game-shell) using [dat-gui](https://github.com/dataarts/dat.gui).

![screenshot](http://i.imgur.com/Qn85CUW.png "Screenshot") 

To try the demo run `npm start`.

## Usage

    var createBindingsUI = require('kb-bindings-ui');

    createBindingsUI(null, {
        kb: kb, // kb-bindings instance to control
        gui: gui, // datgui instance to add to (optional; created if not given)
        hideKeys: [], // array of vkeys to not show in list (optional)
    })

Like mrcorpt-games-plugins-ui and 
mrcorpt-games-debug, you can pass an existing
datgui instance to add to an existing dialog window instead of creating a new one.
Optionally, kb-bindings-ui can be loaded through mrcorpt-games-plugins,
and it will load after mrcorpt-games-debug and mrcorpt-games-plugins-ui, reusing their datgui instance.

The key names shown come from the [vkey](https://github.com/chrisdickinson/vkey) module
(note, not all platforms may support all keys).

In the GUI you can change the key for each binding. The changes take effect immediately.

## License

MIT
