# JSP-shell
This JSP shell captures `stdout` and `stderr` streams from `/bin/sh`.
Commands are executed using `/bin/sh`, bypassing the .exec() function of JSP, therefore allowing trailing commands and better handling of errors.
