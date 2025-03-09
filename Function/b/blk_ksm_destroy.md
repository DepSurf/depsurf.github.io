# Function: <code>blk_ksm_destroy</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void blk_ksm_destroy(struct blk_keyslot_manager * ksm)
```

```json
{
  "name": "blk_ksm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584616835,
      "name": "blk_ksm_destroy",
      "external": true,
      "loc": "block/keyslot-manager.c:372",
      "file": "block/keyslot-manager.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/keyslot-manager.c:blk_ksm_init"
      ],
      "caller_func": [
        "block/keyslot-manager.c:blk_ksm_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584616288,
      "name": "blk_ksm_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071584616400,
      "name": "blk_ksm_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void blk_ksm_destroy(struct blk_keyslot_manager * ksm)
```

```json
{
  "name": "blk_ksm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584735674,
      "name": "blk_ksm_destroy",
      "external": true,
      "loc": "block/keyslot-manager.c:379",
      "file": "block/keyslot-manager.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/keyslot-manager.c:blk_ksm_init"
      ],
      "caller_func": [
        "block/keyslot-manager.c:blk_ksm_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584735104,
      "name": "blk_ksm_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071584735216,
      "name": "blk_ksm_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void blk_ksm_destroy(struct blk_keyslot_manager * ksm)
```

```json
{
  "name": "blk_ksm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584763638,
      "name": "blk_ksm_destroy",
      "external": true,
      "loc": "block/keyslot-manager.c:430",
      "file": "block/keyslot-manager.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/keyslot-manager.c:blk_ksm_init"
      ],
      "caller_func": [
        "block/keyslot-manager.c:blk_ksm_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_construct_keyslot_manager",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584763088,
      "name": "blk_ksm_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071584763200,
      "name": "blk_ksm_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void blk_ksm_destroy(struct blk_keyslot_manager * ksm)
```

```json
{
  "name": "blk_ksm_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585192314,
      "name": "blk_ksm_destroy",
      "external": true,
      "loc": "block/keyslot-manager.c:430",
      "file": "block/keyslot-manager.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/keyslot-manager.c:blk_ksm_init"
      ],
      "caller_func": [
        "block/keyslot-manager.c:blk_ksm_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_construct_keyslot_manager",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585191744,
      "name": "blk_ksm_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071585191856,
      "name": "blk_ksm_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void blk_ksm_destroy(struct blk_keyslot_manager * ksm)
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
void blk_ksm_destroy(struct blk_keyslot_manager * ksm)
```
</details>
</li>
</ul>
