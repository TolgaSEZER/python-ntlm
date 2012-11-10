# python-ntlm

This is a module for doing NTLM authentication

It is a fork of http://code.google.com/p/python-ntlm/

## Pass the Hash

This module now supports pass-the-hash in addition to password authentication.

To use this, supply your NTLM hash as the password. The code expects it to be formatted as `ABCDABCDABCDABCD:ABCDABCDABCDABCD`.