# Function: <code>blk_ksm_get_slot_for_key</code>

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
blk_status_t blk_ksm_get_slot_for_key(struct blk_keyslot_manager * ksm, const struct blk_crypto_key * key, struct blk_ksm_keyslot * * slot_ptr)
```

```json
{
  "name": "blk_ksm_get_slot_for_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584617104,
      "name": "blk_ksm_get_slot_for_key",
      "external": true,
      "loc": "block/keyslot-manager.c:192",
      "file": "block/keyslot-manager.c",
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
      "addr": 18446744071584617104,
      "name": "blk_ksm_get_slot_for_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
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
blk_status_t blk_ksm_get_slot_for_key(struct blk_keyslot_manager * ksm, const struct blk_crypto_key * key, struct blk_ksm_keyslot * * slot_ptr)
```

```json
{
  "name": "blk_ksm_get_slot_for_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584735936,
      "name": "blk_ksm_get_slot_for_key",
      "external": true,
      "loc": "block/keyslot-manager.c:199",
      "file": "block/keyslot-manager.c",
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
      "addr": 18446744071584735936,
      "name": "blk_ksm_get_slot_for_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
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
blk_status_t blk_ksm_get_slot_for_key(struct blk_keyslot_manager * ksm, const struct blk_crypto_key * key, struct blk_ksm_keyslot * * slot_ptr)
```

```json
{
  "name": "blk_ksm_get_slot_for_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584764048,
      "name": "blk_ksm_get_slot_for_key",
      "external": true,
      "loc": "block/keyslot-manager.c:233",
      "file": "block/keyslot-manager.c",
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
      "addr": 18446744071584764048,
      "name": "blk_ksm_get_slot_for_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 734
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
blk_status_t blk_ksm_get_slot_for_key(struct blk_keyslot_manager * ksm, const struct blk_crypto_key * key, struct blk_ksm_keyslot * * slot_ptr)
```

```json
{
  "name": "blk_ksm_get_slot_for_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_ksm_get_slot_for_key",
      "external": true,
      "loc": "block/keyslot-manager.c:233",
      "file": "block/keyslot-manager.c",
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
      "addr": 18446744071592322614,
      "name": "blk_ksm_get_slot_for_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071585192752,
      "name": "blk_ksm_get_slot_for_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 743
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
blk_status_t blk_ksm_get_slot_for_key(struct blk_keyslot_manager * ksm, const struct blk_crypto_key * key, struct blk_ksm_keyslot * * slot_ptr)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
blk_status_t blk_ksm_get_slot_for_key(struct blk_keyslot_manager * ksm, const struct blk_crypto_key * key, struct blk_ksm_keyslot * * slot_ptr)
```
</details>
</li>
</ul>
