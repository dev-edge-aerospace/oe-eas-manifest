# oe-eas-manifest

Manifests for the repo tool to manage the different repositories and versions used on the Edge Aerospace open-embedded Linux distribution.

*.pinned.xml are versions of the files that lock a specific commit.

[Documentation on open-embedded](https://developer.toradex.com/knowledge-base/board-support-package/openembedded-(core))

[Documentation on repo](https://code.google.com/p/git-repo/)


Todo: Move the edge repositories from the employee account to the company dev account.

clone using:

```
repo init -u git@github.com:dev-edge-aerospace/oe-eas-manifest.git -b main -m oe-eas/default.xml
repo sync
```
