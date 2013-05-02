#### libdomainkeys 

This provides us with two basic programs, `dktest` need by the `qmail-remote` wrapper and `dknewkey` for generating key pairs.



#### INSTALLATION

Edit the Makefile and add "*-lresolv*" to the end of the "LIBS" line 

Run `make`

`install -m 644 libdomainkeys.a /usr/local/lib`

`install -m 644 domainkeys.h dktrace.h /usr/local/include`

`install -m 755 dknewkey /usr/bin`

`install -m 755 dktest /usr/local/bin`
