# Helm GPG (GnuPG) Plugin

Helm has the ability to cryptographically sign and verify charts. This plugin
provides integration with GnuPG, making it easier to use than the default
`helm` signing and verifying commands. It is also more secure, since it supports
passphrase-encrypted keys.

It offers two operations:

- sign: Sign a chart with a key
- verify: Verify a signed chart with your keyring

Also check out the [Helm Keybase](https://github.com/technosophos/helm-keybase) plugin.

## Installation

You must have GnuPG's command line client (`gpg`) installed and configured.

```console
$ helm plugin install https://github.com/technosophos/helm-gpg
```


