sout
====

Screen Out: a simple  `xrandr` wrapper.

Usage
------

The available options are:
 * External screen on the right (`sout -r`)
 * External screen on the left (`sout -l`)
 * External screen with the same content as main screen (`sout -c`)

To disable the external devices, just type `sout -o`.

Status
-------

The current version search for the maximum resolution of the external device
to extend or copy the screen.
