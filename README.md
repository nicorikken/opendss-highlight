# opendss-highlight
OpenDSS language file for GtkSourceView. The language file is written according to the v2.0 specification of GtkSourceView https://developer.gnome.org/gtksourceview/stable/pt02.html

This file can be included in your locak GtkSourceView install, to be used by applications like Gedit.

## Licence
This language specification is currently licensed under the LGPL v2.1 to both be compatible with reused code, and remain compatible for future upstream adoption in GtkSourceView.

## How to install
GtkSourceView version 3
<pre><code>mkdir -p ~/.local/share/gtksourceview-3.0/language-specs/
cd ~/.local/share/gtksourceview-3.0/language-specs/
wget https://raw.githubusercontent.com/nicorikken/opendss-highlight/master/opendss.lang</pre></code>

GtkSourceView version 2
<pre><code>mkdir -p ~/.local/share/gtksourceview-2.0/language-specs/
cd ~/.local/share/gtksourceview-2.0/language-specs/
wget https://raw.githubusercontent.com/nicorikken/opendss-highlight/master/opendss.lang</pre></code>

## Known issues
* No spell-check exceptions have been defined.
* Filenames lack a highlight extending to the full length of the filename.
* Default vsource.source is not properly highlighted.
* Context-based distinction between types (command, option, etc.) is lacking.
* Development tags like TODO or FIXME lack highlighting.
