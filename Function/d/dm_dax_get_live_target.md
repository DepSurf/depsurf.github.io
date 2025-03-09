# Function: <code>dm_dax_get_live_target</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dm_target * dm_dax_get_live_target(struct mapped_device * md, sector_t sector, int * srcu_idx)
```

```json
{
  "name": "dm_dax_get_live_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586497488,
      "name": "dm_dax_get_live_target",
      "external": false,
      "loc": "drivers/md/dm.c:921",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_dax_flush",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586497488,
      "name": "dm_dax_get_live_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_dax_get_live_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586965449,
      "name": "dm_dax_get_live_target",
      "external": false,
      "loc": "drivers/md/dm.c:930",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dm_target * dm_dax_get_live_target(struct mapped_device * md, sector_t sector, int * srcu_idx)
```

```json
{
  "name": "dm_dax_get_live_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587261184,
      "name": "dm_dax_get_live_target",
      "external": false,
      "loc": "drivers/md/dm.c:1022",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587261184,
      "name": "dm_dax_get_live_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dm_target * dm_dax_get_live_target(struct mapped_device * md, sector_t sector, int * srcu_idx)
```

```json
{
  "name": "dm_dax_get_live_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587441232,
      "name": "dm_dax_get_live_target",
      "external": false,
      "loc": "drivers/md/dm.c:1077",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587441232,
      "name": "dm_dax_get_live_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dm_target * dm_dax_get_live_target(struct mapped_device * md, sector_t sector, int * srcu_idx)
```

```json
{
  "name": "dm_dax_get_live_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587713568,
      "name": "dm_dax_get_live_target",
      "external": false,
      "loc": "drivers/md/dm.c:1063",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587713568,
      "name": "dm_dax_get_live_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dm_target * dm_dax_get_live_target(struct mapped_device * md, sector_t sector, int * srcu_idx)
```

```json
{
  "name": "dm_dax_get_live_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587917808,
      "name": "dm_dax_get_live_target",
      "external": false,
      "loc": "drivers/md/dm.c:1063",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587917808,
      "name": "dm_dax_get_live_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_dax_get_live_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588782215,
      "name": "dm_dax_get_live_target",
      "external": false,
      "loc": "drivers/md/dm.c:1089",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_dax_get_live_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588796999,
      "name": "dm_dax_get_live_target",
      "external": false,
      "loc": "drivers/md/dm.c:1094",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_dax_get_live_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588682311,
      "name": "dm_dax_get_live_target",
      "external": false,
      "loc": "drivers/md/dm.c:1098",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_dax_get_live_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589366231,
      "name": "dm_dax_get_live_target",
      "external": false,
      "loc": "drivers/md/dm.c:985",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_dax_get_live_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590842020,
      "name": "dm_dax_get_live_target",
      "external": false,
      "loc": "drivers/md/dm.c:1122",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_recovery_write",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_direct_access"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_dax_get_live_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592535828,
      "name": "dm_dax_get_live_target",
      "external": false,
      "loc": "drivers/md/dm.c:1195",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_recovery_write",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_direct_access"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_dax_get_live_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592967668,
      "name": "dm_dax_get_live_target",
      "external": false,
      "loc": "drivers/md/dm.c:1219",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_recovery_write",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_direct_access"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_dax_get_live_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593717796,
      "name": "dm_dax_get_live_target",
      "external": false,
      "loc": "drivers/md/dm.c:1205",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_dax_recovery_write",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_direct_access"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct dm_target * dm_dax_get_live_target(struct mapped_device * md, sector_t sector, int * srcu_idx)
```

```json
{
  "name": "dm_dax_get_live_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501150392,
      "name": "dm_dax_get_live_target",
      "external": false,
      "loc": "drivers/md/dm.c:1063",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501150392,
      "name": "dm_dax_get_live_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dm_target * dm_dax_get_live_target(struct mapped_device * md, sector_t sector, int * srcu_idx)
```

```json
{
  "name": "dm_dax_get_live_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294658112,
      "name": "dm_dax_get_live_target",
      "external": false,
      "loc": "drivers/md/dm.c:1063",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294658112,
      "name": "dm_dax_get_live_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dm_target * dm_dax_get_live_target(struct mapped_device * md, sector_t sector, int * srcu_idx)
```

```json
{
  "name": "dm_dax_get_live_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277861714,
      "name": "dm_dax_get_live_target",
      "external": false,
      "loc": "drivers/md/dm.c:1063",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277861714,
      "name": "dm_dax_get_live_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct dm_target * dm_dax_get_live_target(struct mapped_device * md, sector_t sector, int * srcu_idx)
```

```json
{
  "name": "dm_dax_get_live_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587548784,
      "name": "dm_dax_get_live_target",
      "external": false,
      "loc": "drivers/md/dm.c:1063",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587548784,
      "name": "dm_dax_get_live_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dm_target * dm_dax_get_live_target(struct mapped_device * md, sector_t sector, int * srcu_idx)
```

```json
{
  "name": "dm_dax_get_live_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587316880,
      "name": "dm_dax_get_live_target",
      "external": false,
      "loc": "drivers/md/dm.c:1063",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587316880,
      "name": "dm_dax_get_live_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dm_target * dm_dax_get_live_target(struct mapped_device * md, sector_t sector, int * srcu_idx)
```

```json
{
  "name": "dm_dax_get_live_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587873952,
      "name": "dm_dax_get_live_target",
      "external": false,
      "loc": "drivers/md/dm.c:1063",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587873952,
      "name": "dm_dax_get_live_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dm_target * dm_dax_get_live_target(struct mapped_device * md, sector_t sector, int * srcu_idx)
```

```json
{
  "name": "dm_dax_get_live_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587989088,
      "name": "dm_dax_get_live_target",
      "external": false,
      "loc": "drivers/md/dm.c:1063",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587989088,
      "name": "dm_dax_get_live_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct dm_target * dm_dax_get_live_target(struct mapped_device * md, sector_t sector, int * srcu_idx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
struct dm_target * dm_dax_get_live_target(struct mapped_device * md, sector_t sector, int * srcu_idx)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct dm_target * dm_dax_get_live_target(struct mapped_device * md, sector_t sector, int * srcu_idx)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct dm_target * dm_dax_get_live_target(struct mapped_device * md, sector_t sector, int * srcu_idx)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct dm_target * dm_dax_get_live_target(struct mapped_device * md, sector_t sector, int * srcu_idx)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
