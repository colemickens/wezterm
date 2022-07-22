# `wezterm.reload_configuration()`

*Since: nightly builds only*

Immediately causes the configuration to be reloaded and re-applied.

If you call this at the file scope in your config you will create
an infinite loop that renders wezterm unresponsive, so don't do that!

The intent is for this to be used from an event or timer callback function.