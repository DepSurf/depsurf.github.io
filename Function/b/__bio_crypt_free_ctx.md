# Function: <code>__bio_crypt_free_ctx</code>

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
void __bio_crypt_free_ctx(struct bio * bio)
```

```json
{
  "name": "__bio_crypt_free_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584618832,
      "name": "__bio_crypt_free_ctx",
      "external": true,
      "loc": "block/blk-crypto.c:92",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_uninit",
        "block/blk-core.c:bio_attempt_back_merge",
        "block/blk-map.c:blk_rq_append_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618832,
      "name": "__bio_crypt_free_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void __bio_crypt_free_ctx(struct bio * bio)
```

```json
{
  "name": "__bio_crypt_free_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584737600,
      "name": "__bio_crypt_free_ctx",
      "external": true,
      "loc": "block/blk-crypto.c:100",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_uninit",
        "block/blk-map.c:blk_rq_append_bio",
        "block/blk-merge.c:bio_attempt_back_merge",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584737600,
      "name": "__bio_crypt_free_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void __bio_crypt_free_ctx(struct bio * bio)
```

```json
{
  "name": "__bio_crypt_free_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584765712,
      "name": "__bio_crypt_free_ctx",
      "external": true,
      "loc": "block/blk-crypto.c:100",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_uninit",
        "block/blk-map.c:blk_rq_append_bio",
        "block/blk-merge.c:bio_attempt_back_merge",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584765712,
      "name": "__bio_crypt_free_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void __bio_crypt_free_ctx(struct bio * bio)
```

```json
{
  "name": "__bio_crypt_free_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585194464,
      "name": "__bio_crypt_free_ctx",
      "external": true,
      "loc": "block/blk-crypto.c:100",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_uninit",
        "block/blk-map.c:blk_rq_append_bio",
        "block/blk-merge.c:bio_attempt_back_merge",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585194464,
      "name": "__bio_crypt_free_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void __bio_crypt_free_ctx(struct bio * bio)
```

```json
{
  "name": "__bio_crypt_free_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585929104,
      "name": "__bio_crypt_free_ctx",
      "external": true,
      "loc": "block/blk-crypto.c:103",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_uninit",
        "block/blk-map.c:blk_rq_append_bio",
        "block/blk-merge.c:bio_attempt_back_merge",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585929104,
      "name": "__bio_crypt_free_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void __bio_crypt_free_ctx(struct bio * bio)
```

```json
{
  "name": "__bio_crypt_free_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586719984,
      "name": "__bio_crypt_free_ctx",
      "external": true,
      "loc": "block/blk-crypto.c:109",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_uninit",
        "block/blk-map.c:blk_rq_append_bio",
        "block/blk-merge.c:bio_attempt_back_merge",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586719984,
      "name": "__bio_crypt_free_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void __bio_crypt_free_ctx(struct bio * bio)
```

```json
{
  "name": "__bio_crypt_free_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586982512,
      "name": "__bio_crypt_free_ctx",
      "external": true,
      "loc": "block/blk-crypto.c:110",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_uninit",
        "block/blk-map.c:blk_rq_append_bio",
        "block/blk-merge.c:bio_attempt_back_merge",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586982512,
      "name": "__bio_crypt_free_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void __bio_crypt_free_ctx(struct bio * bio)
```

```json
{
  "name": "__bio_crypt_free_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587264256,
      "name": "__bio_crypt_free_ctx",
      "external": true,
      "loc": "block/blk-crypto.c:110",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_uninit",
        "block/blk-map.c:blk_rq_append_bio",
        "block/blk-merge.c:bio_attempt_back_merge",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587264256,
      "name": "__bio_crypt_free_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void __bio_crypt_free_ctx(struct bio * bio)
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
