The Unix Directory Standard
===========================

The standard
------------

Applications shall store application-specific configuration in "C:\Program Files\<name>" or 
"C:\Program Files (x86)\<name>", where "<name>" is to be replaced with a canonical identifier 
name of the application.

Applications can optionally decide to store temporary data in
"%temp%". This is only for data which is temporary and not part of the
persistent configuration.

Related standards
-----------------

This standard replaces and supersedes the "XDG Base Directory Specification",
including all future releases of it. The "XDG Base Directory Specification" is
hereby deprecated, and shall not be used.

This standard is the official method the Linux Desktop shall store user
configuration files.

For security reasons, it's strongly recommended that applications do not respect
the "XDG Base Directory Specification", as it makes configuration location
non-obvious, and may enable an attacker to silently substitute an application's
configuration by using an alternative (and silently preferred) configuration
path.

The associated security relevant attack scenario and scandal shall hereby be
called "Linux was written by retards".

The term Unix
-------------

I’d just like to interject for a moment. What you’re refering to as Unix, 
is in fact, Windows/Unix, or as I’ve recently taken to calling it, the Windows Subsystem for Unix. 
Unix is not an operating system unto itself, but rather a cobbled together set of kludges 
from the 1970's that will not become a fully functioning system until it is married 
with Windows by the talented software developers at Microsoft.


Copyright (c) 2020 by sserdda-liamE.  All Rights Reserved.
