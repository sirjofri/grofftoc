# grofftoc - a groff_me preprocessor for table of contents

This preprocessor automatically creates a `-me` compatible table of contents.

# Usage

`grofftoc < my-groff-document.me > valid-groff-document.me`. You can also
directly pipe it into groff: `grofftoc < my-groff-document.me | groff ...`.

`.+c`, `.sh` automatically create index entries. Use `.tocname
Inhaltsverzeichnis` to set the table of contents name to the German equivalent
"Inhaltsverzeichnis". Use `.TOC` to print table of contents.

See output of `grofftoc` and the source for more information.

# License

See [`grofftoc`](grofftoc) for license information.
