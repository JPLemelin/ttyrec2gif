ttyrec2gif
==========

ttyrec to animated GIF.


Installation
------------

    go get github.com/sugyan/ttyrec2gif


Usage
-----

    ttyrec2gif -in <input file> -out <output file> -s <speed> -row <rows> -col <columns>

* `in`: ttyrec file (default: `"ttyrecord"`)
* `out`: output animated GIF file name (default: `"tty.gif"`)
* `s`: play speed (default: `1.0`)
* `row`: terminal height (default: `24`)
* `col`: terminal width (default: `80`)
* `noloop`: play only once (default: `false`)


Note
----

- [j4k.co/terminal](http://godoc.org/j4k.co/terminal)
- [Anonymous Pro](http://www.marksimonson.com/fonts/view/anonymous-pro) font
