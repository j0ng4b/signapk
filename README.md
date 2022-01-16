# Signapk
Simple tool for signate Android apks. Note that may there are some bugs, the
script not was extensively tested!

# Dependencies
Signapk require few external tools for properly work and they are:
	- unzip: used to extract files.
	- openssl: used for generate self-signed key and certificate pairs and the signature as well.
	- aapt: for list apk entries and add the signature.
	- common unix tool (cp, echo, etc)

# Installation

Installation proccess is quite simple, only run [install]() script. Signapk
will be installed on `$HOME/.local/bin` make sure that path is present on your
`$PATH` variable or pass another installation directory:

```
DESTDIR=<YOUR_DIR> ./install
```

# License
Signapk is licensed under terms of MIT license, see [LICENSE]() file for more
information.

