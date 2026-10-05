<!-- tyhp-readme:start -->
# tyhpdef/illuminate-encryption

Tyhp type definitions for `illuminate/encryption` `13.32.0`.

```bash
composer require --dev tyhpdef/illuminate-encryption:13.32.0
```

This is a metapackage. Composer also installs `tyhpdef/illuminate-encryption-impl` (type files).
Require **this** name, not `tyhpdef/illuminate-encryption-impl`.

See https://tyhplang.com.

## Maintain `illuminate/encryption`? Ship the types yourself

If you are a Packagist maintainer of `illuminate/encryption`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/illuminate-encryption-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `illuminate/encryption` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/illuminate-encryption": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `illuminate/encryption` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `illuminate/encryption` with a real constraint,
   `"replace": { "tyhpdef/illuminate-encryption": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `illuminate/encryption` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/illuminate-encryption` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
