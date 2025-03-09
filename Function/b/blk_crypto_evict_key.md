# Function: <code>blk_crypto_evict_key</code>

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
int blk_crypto_evict_key(struct request_queue * q, const struct blk_crypto_key * key)
```

```json
{
  "name": "blk_crypto_evict_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584619904,
      "name": "blk_crypto_evict_key",
      "external": true,
      "loc": "block/blk-crypto.c:392",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584619904,
      "name": "blk_crypto_evict_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int blk_crypto_evict_key(struct request_queue * q, const struct blk_crypto_key * key)
```

```json
{
  "name": "blk_crypto_evict_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584738672,
      "name": "blk_crypto_evict_key",
      "external": true,
      "loc": "block/blk-crypto.c:399",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584738672,
      "name": "blk_crypto_evict_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int blk_crypto_evict_key(struct request_queue * q, const struct blk_crypto_key * key)
```

```json
{
  "name": "blk_crypto_evict_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584765536,
      "name": "blk_crypto_evict_key",
      "external": true,
      "loc": "block/blk-crypto.c:399",
      "file": "block/blk-crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key",
        "drivers/md/dm-table.c:dm_keyslot_evict_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584765536,
      "name": "blk_crypto_evict_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int blk_crypto_evict_key(struct request_queue * q, const struct blk_crypto_key * key)
```

```json
{
  "name": "blk_crypto_evict_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585194288,
      "name": "blk_crypto_evict_key",
      "external": true,
      "loc": "block/blk-crypto.c:399",
      "file": "block/blk-crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key",
        "drivers/md/dm-table.c:dm_keyslot_evict_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585194288,
      "name": "blk_crypto_evict_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int blk_crypto_evict_key(struct request_queue * q, const struct blk_crypto_key * key)
```

```json
{
  "name": "blk_crypto_evict_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585928896,
      "name": "blk_crypto_evict_key",
      "external": true,
      "loc": "block/blk-crypto.c:403",
      "file": "block/blk-crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key",
        "drivers/md/dm-table.c:dm_keyslot_evict_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585928896,
      "name": "blk_crypto_evict_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int blk_crypto_evict_key(struct block_device * bdev, const struct blk_crypto_key * key)
```

```json
{
  "name": "blk_crypto_evict_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586719744,
      "name": "blk_crypto_evict_key",
      "external": true,
      "loc": "block/blk-crypto.c:414",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key",
        "drivers/md/dm-table.c:dm_keyslot_evict_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586719744,
      "name": "blk_crypto_evict_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void blk_crypto_evict_key(struct block_device * bdev, const struct blk_crypto_key * key)
```

```json
{
  "name": "blk_crypto_evict_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586982208,
      "name": "blk_crypto_evict_key",
      "external": true,
      "loc": "block/blk-crypto.c:417",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key",
        "drivers/md/dm-table.c:dm_keyslot_evict_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586982208,
      "name": "blk_crypto_evict_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void blk_crypto_evict_key(struct block_device * bdev, const struct blk_crypto_key * key)
```

```json
{
  "name": "blk_crypto_evict_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587263952,
      "name": "blk_crypto_evict_key",
      "external": true,
      "loc": "block/blk-crypto.c:417",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key",
        "drivers/md/dm-table.c:dm_keyslot_evict_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587263952,
      "name": "blk_crypto_evict_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int blk_crypto_evict_key(struct request_queue * q, const struct blk_crypto_key * key)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct block_device * bdev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct request_queue * q</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
