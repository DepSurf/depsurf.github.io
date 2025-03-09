# Function: <code>blk_crypto_profile_destroy</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_crypto_profile_destroy(struct blk_crypto_profile * profile)
```

```json
{
  "name": "blk_crypto_profile_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585931881,
      "name": "blk_crypto_profile_destroy",
      "external": true,
      "loc": "block/blk-crypto-profile.c:443",
      "file": "block/blk-crypto-profile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-crypto-profile.c:blk_crypto_profile_init",
        "block/blk-crypto-profile.c:blk_crypto_profile_init"
      ],
      "caller_func": [
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_construct_crypto_profile",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585932400,
      "name": "blk_crypto_profile_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_crypto_profile_destroy(struct blk_crypto_profile * profile)
```

```json
{
  "name": "blk_crypto_profile_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586723177,
      "name": "blk_crypto_profile_destroy",
      "external": true,
      "loc": "block/blk-crypto-profile.c:444",
      "file": "block/blk-crypto-profile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-crypto-profile.c:blk_crypto_profile_init",
        "block/blk-crypto-profile.c:blk_crypto_profile_init"
      ],
      "caller_func": [
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_construct_crypto_profile",
        "drivers/md/dm-table.c:dm_table_construct_crypto_profile",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586723760,
      "name": "blk_crypto_profile_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void blk_crypto_profile_destroy(struct blk_crypto_profile * profile)
```

```json
{
  "name": "blk_crypto_profile_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586986148,
      "name": "blk_crypto_profile_destroy",
      "external": true,
      "loc": "block/blk-crypto-profile.c:441",
      "file": "block/blk-crypto-profile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-crypto-profile.c:blk_crypto_profile_init"
      ],
      "caller_func": [
        "block/blk-crypto-profile.c:blk_crypto_profile_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_construct_crypto_profile",
        "drivers/md/dm-table.c:dm_table_construct_crypto_profile",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586985568,
      "name": "blk_crypto_profile_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071586986656,
      "name": "blk_crypto_profile_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void blk_crypto_profile_destroy(struct blk_crypto_profile * profile)
```

```json
{
  "name": "blk_crypto_profile_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587267892,
      "name": "blk_crypto_profile_destroy",
      "external": true,
      "loc": "block/blk-crypto-profile.c:441",
      "file": "block/blk-crypto-profile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-crypto-profile.c:blk_crypto_profile_init"
      ],
      "caller_func": [
        "block/blk-crypto-profile.c:blk_crypto_profile_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_construct_crypto_profile",
        "drivers/md/dm-table.c:dm_table_construct_crypto_profile",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587267312,
      "name": "blk_crypto_profile_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071587268400,
      "name": "blk_crypto_profile_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void blk_crypto_profile_destroy(struct blk_crypto_profile * profile)
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
