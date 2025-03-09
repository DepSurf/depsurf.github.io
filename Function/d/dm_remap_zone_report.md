# Function: <code>dm_remap_zone_report</code>

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
void dm_remap_zone_report(struct dm_target * ti, struct bio * bio, sector_t start)
```

```json
{
  "name": "dm_remap_zone_report",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586496912,
      "name": "dm_remap_zone_report",
      "external": true,
      "loc": "drivers/md/dm.c:1056",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-linear.c:linear_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586496912,
      "name": "dm_remap_zone_report",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void dm_remap_zone_report(struct dm_target * ti, struct bio * bio, sector_t start)
```

```json
{
  "name": "dm_remap_zone_report",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586964832,
      "name": "dm_remap_zone_report",
      "external": true,
      "loc": "drivers/md/dm.c:1047",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-linear.c:linear_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586964832,
      "name": "dm_remap_zone_report",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void dm_remap_zone_report(struct dm_target * ti, struct bio * bio, sector_t start)
```

```json
{
  "name": "dm_remap_zone_report",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587260496,
      "name": "dm_remap_zone_report",
      "external": true,
      "loc": "drivers/md/dm.c:1163",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-linear.c:linear_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587260496,
      "name": "dm_remap_zone_report",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 654
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
void dm_remap_zone_report(struct dm_target * ti, sector_t start, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "dm_remap_zone_report",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587441024,
      "name": "dm_remap_zone_report",
      "external": true,
      "loc": "drivers/md/dm.c:1218",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-linear.c:linear_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587441024,
      "name": "dm_remap_zone_report",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void dm_remap_zone_report(struct dm_target * ti, sector_t start, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "dm_remap_zone_report",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587713376,
      "name": "dm_remap_zone_report",
      "external": true,
      "loc": "drivers/md/dm.c:1223",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-linear.c:linear_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587713376,
      "name": "dm_remap_zone_report",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void dm_remap_zone_report(struct dm_target * ti, sector_t start, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "dm_remap_zone_report",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587917616,
      "name": "dm_remap_zone_report",
      "external": true,
      "loc": "drivers/md/dm.c:1223",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-linear.c:linear_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587917616,
      "name": "dm_remap_zone_report",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void dm_remap_zone_report(struct dm_target * ti, sector_t start, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "dm_remap_zone_report",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501150104,
      "name": "dm_remap_zone_report",
      "external": true,
      "loc": "drivers/md/dm.c:1223",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-linear.c:linear_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501150104,
      "name": "dm_remap_zone_report",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void dm_remap_zone_report(struct dm_target * ti, sector_t start, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "dm_remap_zone_report",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233662792,
      "name": "dm_remap_zone_report",
      "external": true,
      "loc": "drivers/md/dm.c:1223",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-linear.c:linear_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233662792,
      "name": "dm_remap_zone_report",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void dm_remap_zone_report(struct dm_target * ti, sector_t start, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "dm_remap_zone_report",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294657808,
      "name": "dm_remap_zone_report",
      "external": true,
      "loc": "drivers/md/dm.c:1223",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-linear.c:linear_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294657808,
      "name": "dm_remap_zone_report",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void dm_remap_zone_report(struct dm_target * ti, sector_t start, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "dm_remap_zone_report",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277861528,
      "name": "dm_remap_zone_report",
      "external": true,
      "loc": "drivers/md/dm.c:1223",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-linear.c:linear_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277861528,
      "name": "dm_remap_zone_report",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void dm_remap_zone_report(struct dm_target * ti, sector_t start, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "dm_remap_zone_report",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587548592,
      "name": "dm_remap_zone_report",
      "external": true,
      "loc": "drivers/md/dm.c:1223",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-linear.c:linear_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587548592,
      "name": "dm_remap_zone_report",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void dm_remap_zone_report(struct dm_target * ti, sector_t start, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "dm_remap_zone_report",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587316688,
      "name": "dm_remap_zone_report",
      "external": true,
      "loc": "drivers/md/dm.c:1223",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-linear.c:linear_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587316688,
      "name": "dm_remap_zone_report",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void dm_remap_zone_report(struct dm_target * ti, sector_t start, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "dm_remap_zone_report",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587873760,
      "name": "dm_remap_zone_report",
      "external": true,
      "loc": "drivers/md/dm.c:1223",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-linear.c:linear_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587873760,
      "name": "dm_remap_zone_report",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void dm_remap_zone_report(struct dm_target * ti, sector_t start, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "dm_remap_zone_report",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587988896,
      "name": "dm_remap_zone_report",
      "external": true,
      "loc": "drivers/md/dm.c:1223",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-linear.c:linear_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587988896,
      "name": "dm_remap_zone_report",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void dm_remap_zone_report(struct dm_target * ti, struct bio * bio, sector_t start)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct blk_zone * zones</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int * nr_zones</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bio * bio</code>
</li>
<li>
<b>Param reordered. </b>
<code>ti, bio, start</code> ➡️ <code>ti, start, zones, nr_zones</code>
</li>
</ul>
</details>
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
void dm_remap_zone_report(struct dm_target * ti, sector_t start, struct blk_zone * zones, unsigned int * nr_zones)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
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
