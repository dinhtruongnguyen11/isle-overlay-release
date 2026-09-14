# The Isle Overlay — Releases

Built releases (installer + signed manifest) for [Cydeva Gaming Overlay](https://github.com/dinhtruongnguyen11/gw-isle-overlay).

Source code lives in a separate private repository. This repo only ever contains
built artifacts published by `scripts/publish_release.py`, each release signed
with an Ed25519 key so the app can verify update integrity before installing.
