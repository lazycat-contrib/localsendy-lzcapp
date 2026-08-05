# Localsendy for LazyCat

This repository packages [Localsendy](https://github.com/ca-x/localsendy) as a LazyCat LPK v2 application.

- Package ID: `community.lazycat.app.localsendy`
- Single application instance with Linux host networking
- Automatic LocalSend IPv4/IPv6 interface discovery
- Application-data storage by default
- Optional private user-document storage selected during installation
- LazyCat file chooser interception for browser uploads and downloads
- Automatic image delivery, versioned GitHub Releases, and official/private store publication through `ca-x/lazycat-github-action@v1`

The deployment wizard defaults to a `server` LocalSend device with the `LazyCat` model and name prefix. The runtime image remains platform-neutral; all LazyCat-specific configuration lives in this repository.
