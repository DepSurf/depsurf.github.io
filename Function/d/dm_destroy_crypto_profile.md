# Function: <code>dm_destroy_crypto_profile</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void dm_destroy_crypto_profile(struct blk_crypto_profile * profile)
```

```json
{
  "name": "dm_destroy_crypto_profile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590867771,
      "name": "dm_destroy_crypto_profile",
      "external": true,
      "loc": "drivers/md/dm-table.c:1248",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_construct_crypto_profile",
        "drivers/md/dm-table.c:dm_table_construct_crypto_profile",
        "drivers/md/dm-table.c:dm_table_construct_crypto_profile",
        "drivers/md/dm-table.c:dm_table_destroy",
        "drivers/md/dm-table.c:dm_table_destroy"
      ],
      "caller_func": [
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-table.c:dm_table_construct_crypto_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590859776,
      "name": "dm_destroy_crypto_profile.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071590863712,
      "name": "dm_destroy_crypto_profile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void dm_destroy_crypto_profile(struct blk_crypto_profile * profile)
```

```json
{
  "name": "dm_destroy_crypto_profile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592560463,
      "name": "dm_destroy_crypto_profile",
      "external": true,
      "loc": "drivers/md/dm-table.c:1266",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_construct_crypto_profile",
        "drivers/md/dm-table.c:dm_table_construct_crypto_profile",
        "drivers/md/dm-table.c:dm_table_construct_crypto_profile",
        "drivers/md/dm-table.c:dm_table_construct_crypto_profile",
        "drivers/md/dm-table.c:dm_table_destroy",
        "drivers/md/dm-table.c:dm_table_destroy"
      ],
      "caller_func": [
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592556400,
      "name": "dm_destroy_crypto_profile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dm_destroy_crypto_profile(struct blk_crypto_profile * profile)
```

```json
{
  "name": "dm_destroy_crypto_profile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592990852,
      "name": "dm_destroy_crypto_profile",
      "external": true,
      "loc": "drivers/md/dm-table.c:1250",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_construct_crypto_profile",
        "drivers/md/dm-table.c:dm_table_construct_crypto_profile",
        "drivers/md/dm-table.c:dm_table_construct_crypto_profile",
        "drivers/md/dm-table.c:dm_table_construct_crypto_profile",
        "drivers/md/dm-table.c:dm_table_destroy",
        "drivers/md/dm-table.c:dm_table_destroy"
      ],
      "caller_func": [
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592986832,
      "name": "dm_destroy_crypto_profile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dm_destroy_crypto_profile(struct blk_crypto_profile * profile)
```

```json
{
  "name": "dm_destroy_crypto_profile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593741430,
      "name": "dm_destroy_crypto_profile",
      "external": true,
      "loc": "drivers/md/dm-table.c:1272",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_construct_crypto_profile",
        "drivers/md/dm-table.c:dm_table_construct_crypto_profile",
        "drivers/md/dm-table.c:dm_table_construct_crypto_profile",
        "drivers/md/dm-table.c:dm_table_construct_crypto_profile",
        "drivers/md/dm-table.c:dm_table_destroy",
        "drivers/md/dm-table.c:dm_table_destroy"
      ],
      "caller_func": [
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593737648,
      "name": "dm_destroy_crypto_profile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void dm_destroy_crypto_profile(struct blk_crypto_profile * profile)
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
