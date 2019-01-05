Smart Card auth is easy to configure on Mac and works for Login and `sudo`.


`sc_auth list` to get the Hash.

`sudo sc_auth pair -h HASH -u USERNAME`



`ssh -I` can be used if you `brew install opensc` and use `/usr/local/lib/opensc-pkcs11.so`

`ssh-agent` does not work on OSX :(
