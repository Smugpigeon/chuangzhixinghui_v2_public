# Chuangzhi Xinghui V2 Releases

This public repository is the build and release channel for Chuangzhi Xinghui V2.
The product source remains in the private `Smugpigeon/chuangzhixinghui_v2` repository.

The release workflow checks out one exact private commit through a read-only deploy
key, runs the required validation on public GitHub-hosted runners, and publishes only
compiled build outputs, checksums, provenance metadata, and required third-party
notices. It does not mirror source code, credentials, identity configuration, user
data, databases, provider receipts, or private release manifests.

Published artifacts are release candidates until the corresponding deployment record
passes identity, verifier, storage, backup/restore, isolation, rollback, client, and
post-deployment acceptance gates. A GitHub Release alone is not evidence that the MVP
is deployed or approved for production use.

Copyright © Chuangzhi Xinghui. All rights reserved. Third-party components retain
their respective licenses and notices inside each artifact.
