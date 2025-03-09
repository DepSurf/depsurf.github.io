# Function: <code>blk_crypto_get_keyslot</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
blk_status_t blk_crypto_get_keyslot(struct blk_crypto_profile * profile, const struct blk_crypto_key * key, struct blk_crypto_keyslot * * slot_ptr)
```

```json
{
  "name": "blk_crypto_get_keyslot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_crypto_get_keyslot",
      "external": true,
      "loc": "block/blk-crypto-profile.c:241",
      "file": "block/blk-crypto-profile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-crypto.c:__blk_crypto_init_request",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594107441,
      "name": "blk_crypto_get_keyslot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071585932752,
      "name": "blk_crypto_get_keyslot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 801
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
blk_status_t blk_crypto_get_keyslot(struct blk_crypto_profile * profile, const struct blk_crypto_key * key, struct blk_crypto_keyslot * * slot_ptr)
```

```json
{
  "name": "blk_crypto_get_keyslot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_crypto_get_keyslot",
      "external": true,
      "loc": "block/blk-crypto-profile.c:242",
      "file": "block/blk-crypto-profile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-crypto.c:__blk_crypto_init_request",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596110920,
      "name": "blk_crypto_get_keyslot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071586724144,
      "name": "blk_crypto_get_keyslot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 801
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
blk_status_t blk_crypto_get_keyslot(struct blk_crypto_profile * profile, const struct blk_crypto_key * key, struct blk_crypto_keyslot * * slot_ptr)
```

```json
{
  "name": "blk_crypto_get_keyslot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_crypto_get_keyslot",
      "external": true,
      "loc": "block/blk-crypto-profile.c:248",
      "file": "block/blk-crypto-profile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-crypto.c:__blk_crypto_rq_get_keyslot",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596635305,
      "name": "blk_crypto_get_keyslot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071586987040,
      "name": "blk_crypto_get_keyslot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 801
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
blk_status_t blk_crypto_get_keyslot(struct blk_crypto_profile * profile, const struct blk_crypto_key * key, struct blk_crypto_keyslot * * slot_ptr)
```

```json
{
  "name": "blk_crypto_get_keyslot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_crypto_get_keyslot",
      "external": true,
      "loc": "block/blk-crypto-profile.c:248",
      "file": "block/blk-crypto-profile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-crypto.c:__blk_crypto_rq_get_keyslot",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597543121,
      "name": "blk_crypto_get_keyslot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071587268784,
      "name": "blk_crypto_get_keyslot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 801
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
blk_status_t blk_crypto_get_keyslot(struct blk_crypto_profile * profile, const struct blk_crypto_key * key, struct blk_crypto_keyslot * * slot_ptr)
```
</details>
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
