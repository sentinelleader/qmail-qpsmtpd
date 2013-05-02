#### Wrapper for qmail-remote


This is a wrapper for `qmail-remote` binary. Move the original `qmail-remote` to `qmail-remote.orig` and the wrapper to the *"/var/qmail/bin"* folder.

`qmail-remote` depends on two programs,

	1) dkimsign.pl, avaiable in the scripts folder

	2) dktest, which is available with the libdomainkeys, needs to compile it, source code is there in the `qmail` folder
