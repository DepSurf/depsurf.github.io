# Function: <code>crypto_alloc_tfm_node</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void * crypto_alloc_tfm_node(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask, int node)
```

```json
{
  "name": "crypto_alloc_tfm_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584333840,
      "name": "crypto_alloc_tfm_node",
      "external": true,
      "loc": "crypto/api.c:517",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/aead.c:crypto_alloc_aead",
        "crypto/skcipher.c:crypto_alloc_sync_skcipher",
        "crypto/skcipher.c:crypto_alloc_skcipher",
        "crypto/ahash.c:crypto_alloc_ahash",
        "crypto/shash.c:crypto_alloc_shash",
        "crypto/akcipher.c:crypto_alloc_akcipher",
        "crypto/kpp.c:crypto_alloc_kpp",
        "crypto/acompress.c:crypto_alloc_acomp_node",
        "crypto/acompress.c:crypto_alloc_acomp",
        "crypto/rng.c:crypto_get_default_rng"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584333840,
      "name": "crypto_alloc_tfm_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void * crypto_alloc_tfm_node(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask, int node)
```

```json
{
  "name": "crypto_alloc_tfm_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584368384,
      "name": "crypto_alloc_tfm_node",
      "external": true,
      "loc": "crypto/api.c:517",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/aead.c:crypto_alloc_aead",
        "crypto/skcipher.c:crypto_alloc_sync_skcipher",
        "crypto/skcipher.c:crypto_alloc_skcipher",
        "crypto/ahash.c:crypto_alloc_ahash",
        "crypto/shash.c:crypto_alloc_shash",
        "crypto/akcipher.c:crypto_alloc_akcipher",
        "crypto/kpp.c:crypto_alloc_kpp",
        "crypto/acompress.c:crypto_alloc_acomp_node",
        "crypto/acompress.c:crypto_alloc_acomp",
        "crypto/rng.c:crypto_get_default_rng"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584368384,
      "name": "crypto_alloc_tfm_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void * crypto_alloc_tfm_node(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask, int node)
```

```json
{
  "name": "crypto_alloc_tfm_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584763552,
      "name": "crypto_alloc_tfm_node",
      "external": true,
      "loc": "crypto/api.c:517",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/aead.c:crypto_alloc_aead",
        "crypto/skcipher.c:crypto_alloc_sync_skcipher",
        "crypto/skcipher.c:crypto_alloc_skcipher",
        "crypto/ahash.c:crypto_alloc_ahash",
        "crypto/shash.c:crypto_alloc_shash",
        "crypto/akcipher.c:crypto_alloc_akcipher",
        "crypto/kpp.c:crypto_alloc_kpp",
        "crypto/acompress.c:crypto_alloc_acomp_node",
        "crypto/acompress.c:crypto_alloc_acomp",
        "crypto/rng.c:crypto_get_default_rng"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584763552,
      "name": "crypto_alloc_tfm_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void * crypto_alloc_tfm_node(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask, int node)
```

```json
{
  "name": "crypto_alloc_tfm_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585446624,
      "name": "crypto_alloc_tfm_node",
      "external": true,
      "loc": "crypto/api.c:572",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/aead.c:crypto_alloc_aead",
        "crypto/skcipher.c:crypto_alloc_sync_skcipher",
        "crypto/skcipher.c:crypto_alloc_skcipher",
        "crypto/ahash.c:crypto_alloc_ahash",
        "crypto/shash.c:crypto_alloc_shash",
        "crypto/akcipher.c:crypto_alloc_akcipher",
        "crypto/kpp.c:crypto_alloc_kpp",
        "crypto/acompress.c:crypto_alloc_acomp_node",
        "crypto/acompress.c:crypto_alloc_acomp",
        "crypto/rng.c:crypto_get_default_rng"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585446624,
      "name": "crypto_alloc_tfm_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void * crypto_alloc_tfm_node(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask, int node)
```

```json
{
  "name": "crypto_alloc_tfm_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586204896,
      "name": "crypto_alloc_tfm_node",
      "external": true,
      "loc": "crypto/api.c:571",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/aead.c:crypto_alloc_aead",
        "crypto/skcipher.c:crypto_alloc_sync_skcipher",
        "crypto/skcipher.c:crypto_alloc_skcipher",
        "crypto/ahash.c:crypto_alloc_ahash",
        "crypto/shash.c:crypto_alloc_shash",
        "crypto/akcipher.c:crypto_alloc_akcipher",
        "crypto/kpp.c:crypto_alloc_kpp",
        "crypto/acompress.c:crypto_alloc_acomp_node",
        "crypto/acompress.c:crypto_alloc_acomp",
        "crypto/rng.c:crypto_get_default_rng"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586204896,
      "name": "crypto_alloc_tfm_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void * crypto_alloc_tfm_node(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask, int node)
```

```json
{
  "name": "crypto_alloc_tfm_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586443008,
      "name": "crypto_alloc_tfm_node",
      "external": true,
      "loc": "crypto/api.c:607",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/aead.c:crypto_alloc_aead",
        "crypto/skcipher.c:crypto_alloc_sync_skcipher",
        "crypto/skcipher.c:crypto_alloc_skcipher",
        "crypto/ahash.c:crypto_alloc_ahash",
        "crypto/shash.c:crypto_alloc_shash",
        "crypto/akcipher.c:crypto_alloc_akcipher",
        "crypto/sig.c:crypto_alloc_sig",
        "crypto/kpp.c:crypto_alloc_kpp",
        "crypto/acompress.c:crypto_alloc_acomp_node",
        "crypto/acompress.c:crypto_alloc_acomp",
        "crypto/rng.c:crypto_get_default_rng"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586443008,
      "name": "crypto_alloc_tfm_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void * crypto_alloc_tfm_node(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask, int node)
```

```json
{
  "name": "crypto_alloc_tfm_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586708864,
      "name": "crypto_alloc_tfm_node",
      "external": true,
      "loc": "crypto/api.c:607",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/aead.c:crypto_alloc_aead",
        "crypto/lskcipher.c:crypto_alloc_lskcipher",
        "crypto/skcipher.c:crypto_alloc_sync_skcipher",
        "crypto/skcipher.c:crypto_alloc_skcipher",
        "crypto/ahash.c:crypto_alloc_ahash",
        "crypto/shash.c:crypto_alloc_shash",
        "crypto/akcipher.c:crypto_alloc_akcipher",
        "crypto/sig.c:crypto_alloc_sig",
        "crypto/kpp.c:crypto_alloc_kpp",
        "crypto/acompress.c:crypto_alloc_acomp_node",
        "crypto/acompress.c:crypto_alloc_acomp",
        "crypto/rng.c:crypto_get_default_rng"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586708864,
      "name": "crypto_alloc_tfm_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void * crypto_alloc_tfm_node(const char * alg_name, const struct crypto_type * frontend, u32 type, u32 mask, int node)
```
</details>
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
