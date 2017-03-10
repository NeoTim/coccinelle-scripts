Scripts
-------

addition-UB.cocci catches CVE-2017-6312 in gdk-pixbuf2, this bug could have
been caught six months earlier by using Coccinelle with addition-UB.cocci,
(https://bugzilla.gnome.org/show_bug.cgi?id=779012)

multiplication-UB.cocci catches undefined behavior leading to memory corruption
in gdk-pixbuf2 (https://bugzilla.gnome.org/show_bug.cgi?id=770986)

References
----------

https://bugzilla.gnome.org/show_bug.cgi?id=770986

https://mail.gnome.org/archives/commits-list/2016-September/msg04640.html

https://www.mail-archive.com/cocci@systeme.lip6.fr/msg03472.html (got help from Julia)
