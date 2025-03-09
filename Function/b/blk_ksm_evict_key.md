# Function: <code>blk_ksm_evict_key</code>

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
int blk_ksm_evict_key(struct blk_keyslot_manager * ksm, const struct blk_crypto_key * key)
```

```json
{
  "name": "blk_ksm_evict_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584618064,
      "name": "blk_ksm_evict_key",
      "external": true,
      "loc": "block/keyslot-manager.c:315",
      "file": "block/keyslot-manager.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-crypto.c:blk_crypto_evict_key",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_evict_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618064,
      "name": "blk_ksm_evict_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int blk_ksm_evict_key(struct blk_keyslot_manager * ksm, const struct blk_crypto_key * key)
```

```json
{
  "name": "blk_ksm_evict_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584736896,
      "name": "blk_ksm_evict_key",
      "external": true,
      "loc": "block/keyslot-manager.c:322",
      "file": "block/keyslot-manager.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-crypto.c:blk_crypto_evict_key",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_evict_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584736896,
      "name": "blk_ksm_evict_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int blk_ksm_evict_key(struct blk_keyslot_manager * ksm, const struct blk_crypto_key * key)
```

```json
{
  "name": "blk_ksm_evict_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584765024,
      "name": "blk_ksm_evict_key",
      "external": true,
      "loc": "block/keyslot-manager.c:360",
      "file": "block/keyslot-manager.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-crypto-fallback.c:blk_crypto_fallback_evict_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584765024,
      "name": "blk_ksm_evict_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int blk_ksm_evict_key(struct blk_keyslot_manager * ksm, const struct blk_crypto_key * key)
```

```json
{
  "name": "blk_ksm_evict_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585193776,
      "name": "blk_ksm_evict_key",
      "external": true,
      "loc": "block/keyslot-manager.c:360",
      "file": "block/keyslot-manager.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-crypto-fallback.c:blk_crypto_fallback_evict_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585193776,
      "name": "blk_ksm_evict_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int blk_ksm_evict_key(struct blk_keyslot_manager * ksm, const struct blk_crypto_key * key)
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
int blk_ksm_evict_key(struct blk_keyslot_manager * ksm, const struct blk_crypto_key * key)
```
</details>
</li>
</ul>
