# Function: <code>dm_cleanup_zoned_dev</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dm_cleanup_zoned_dev(struct mapped_device * md)
```

```json
{
  "name": "dm_cleanup_zoned_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589354630,
      "name": "dm_cleanup_zoned_dev",
      "external": true,
      "loc": "drivers/md/dm-zone.c:141",
      "file": "drivers/md/dm-zone.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-zone.c:dm_set_zones_restrictions",
        "drivers/md/dm-zone.c:dm_set_zones_restrictions"
      ],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_set_zones_restrictions",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589354352,
      "name": "dm_cleanup_zoned_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void dm_cleanup_zoned_dev(struct mapped_device * md)
```

```json
{
  "name": "dm_cleanup_zoned_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590828438,
      "name": "dm_cleanup_zoned_dev",
      "external": true,
      "loc": "drivers/md/dm-zone.c:140",
      "file": "drivers/md/dm-zone.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-zone.c:dm_set_zones_restrictions",
        "drivers/md/dm-zone.c:dm_set_zones_restrictions"
      ],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_set_zones_restrictions",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590828160,
      "name": "dm_cleanup_zoned_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void dm_cleanup_zoned_dev(struct mapped_device * md)
```

```json
{
  "name": "dm_cleanup_zoned_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592517067,
      "name": "dm_cleanup_zoned_dev",
      "external": true,
      "loc": "drivers/md/dm-zone.c:140",
      "file": "drivers/md/dm-zone.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-zone.c:dm_set_zones_restrictions",
        "drivers/md/dm-zone.c:dm_set_zones_restrictions",
        "drivers/md/dm-zone.c:dm_set_zones_restrictions"
      ],
      "caller_func": [
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592516704,
      "name": "dm_cleanup_zoned_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void dm_cleanup_zoned_dev(struct mapped_device * md)
```

```json
{
  "name": "dm_cleanup_zoned_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592947482,
      "name": "dm_cleanup_zoned_dev",
      "external": true,
      "loc": "drivers/md/dm-zone.c:141",
      "file": "drivers/md/dm-zone.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-zone.c:dm_set_zones_restrictions",
        "drivers/md/dm-zone.c:dm_set_zones_restrictions",
        "drivers/md/dm-zone.c:dm_set_zones_restrictions"
      ],
      "caller_func": [
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592947120,
      "name": "dm_cleanup_zoned_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void dm_cleanup_zoned_dev(struct mapped_device * md)
```

```json
{
  "name": "dm_cleanup_zoned_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593697306,
      "name": "dm_cleanup_zoned_dev",
      "external": true,
      "loc": "drivers/md/dm-zone.c:141",
      "file": "drivers/md/dm-zone.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-zone.c:dm_set_zones_restrictions",
        "drivers/md/dm-zone.c:dm_set_zones_restrictions",
        "drivers/md/dm-zone.c:dm_set_zones_restrictions"
      ],
      "caller_func": [
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593696944,
      "name": "dm_cleanup_zoned_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void dm_cleanup_zoned_dev(struct mapped_device * md)
```
</details>
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
