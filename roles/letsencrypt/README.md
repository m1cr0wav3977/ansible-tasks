# Let's Encrypt

Installs Certbot and manages either Let's Encrypt or self-signed certificates.
Set `ssl_provider` to `letsencrypt` or `selfsigned`, then supply `ssl_domains`.
For Let's Encrypt, set `ssl_letsencrypt_email` and choose `webroot` or
`standalone` with `ssl_letsencrypt_method`.

Domain names, email addresses, and renewal hooks belong in private inventory or
group variables when they identify internal infrastructure.


