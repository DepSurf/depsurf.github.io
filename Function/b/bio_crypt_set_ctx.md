# Function: <code>bio_crypt_set_ctx</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void bio_crypt_set_ctx(struct bio * bio, const struct blk_crypto_key * key, const u64 * dun, gfp_t gfp_mask)
```

```json
{
  "name": "bio_crypt_set_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584618736,
      "name": "bio_crypt_set_ctx",
      "external": true,
      "loc": "block/blk-crypto.c:81",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618736,
      "name": "bio_crypt_set_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void bio_crypt_set_ctx(struct bio * bio, const struct blk_crypto_key * key, const u64 * dun, gfp_t gfp_mask)
```

```json
{
  "name": "bio_crypt_set_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584737504,
      "name": "bio_crypt_set_ctx",
      "external": true,
      "loc": "block/blk-crypto.c:81",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584737504,
      "name": "bio_crypt_set_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void bio_crypt_set_ctx(struct bio * bio, const struct blk_crypto_key * key, const u64 * dun, gfp_t gfp_mask)
```

```json
{
  "name": "bio_crypt_set_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584765616,
      "name": "bio_crypt_set_ctx",
      "external": true,
      "loc": "block/blk-crypto.c:81",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584765616,
      "name": "bio_crypt_set_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void bio_crypt_set_ctx(struct bio * bio, const struct blk_crypto_key * key, const u64 * dun, gfp_t gfp_mask)
```

```json
{
  "name": "bio_crypt_set_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585194368,
      "name": "bio_crypt_set_ctx",
      "external": true,
      "loc": "block/blk-crypto.c:81",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585194368,
      "name": "bio_crypt_set_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void bio_crypt_set_ctx(struct bio * bio, const struct blk_crypto_key * key, const u64 * dun, gfp_t gfp_mask)
```

```json
{
  "name": "bio_crypt_set_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585928992,
      "name": "bio_crypt_set_ctx",
      "external": true,
      "loc": "block/blk-crypto.c:84",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585928992,
      "name": "bio_crypt_set_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void bio_crypt_set_ctx(struct bio * bio, const struct blk_crypto_key * key, const u64 * dun, gfp_t gfp_mask)
```

```json
{
  "name": "bio_crypt_set_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586719856,
      "name": "bio_crypt_set_ctx",
      "external": true,
      "loc": "block/blk-crypto.c:90",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586719856,
      "name": "bio_crypt_set_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void bio_crypt_set_ctx(struct bio * bio, const struct blk_crypto_key * key, const u64 * dun, gfp_t gfp_mask)
```

```json
{
  "name": "bio_crypt_set_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586982384,
      "name": "bio_crypt_set_ctx",
      "external": true,
      "loc": "block/blk-crypto.c:91",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586982384,
      "name": "bio_crypt_set_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void bio_crypt_set_ctx(struct bio * bio, const struct blk_crypto_key * key, const u64 * dun, gfp_t gfp_mask)
```

```json
{
  "name": "bio_crypt_set_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587264128,
      "name": "bio_crypt_set_ctx",
      "external": true,
      "loc": "block/blk-crypto.c:91",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587264128,
      "name": "bio_crypt_set_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void bio_crypt_set_ctx(struct bio * bio, const struct blk_crypto_key * key, const u64 * dun, gfp_t gfp_mask)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
