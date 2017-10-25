Netctl config for eduroam
====

# Use a hash
You can use a hash instead of a raw password for the password section.

1. Run `echo -n "YOUR-PASSWORD" | iconv -t utf16le | openssl md4`
2. Edit as `'password=hash:OUTPUT-HASH'`
