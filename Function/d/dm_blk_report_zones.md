# Function: <code>dm_blk_report_zones</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int dm_blk_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones, gfp_t gfp_mask)
```

```json
{
  "name": "dm_blk_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587441600,
      "name": "dm_blk_report_zones",
      "external": false,
      "loc": "drivers/md/dm.c:461",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587441600,
      "name": "dm_blk_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int dm_blk_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "dm_blk_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dm_blk_report_zones",
      "external": false,
      "loc": "drivers/md/dm.c:443",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587724192,
      "name": "dm_blk_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071587730958,
      "name": "dm_blk_report_zones.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int dm_blk_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "dm_blk_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587927040,
      "name": "dm_blk_report_zones",
      "external": false,
      "loc": "drivers/md/dm.c:443",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587927040,
      "name": "dm_blk_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int dm_blk_report_zones(struct gendisk * disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void * data)
```

```json
{
  "name": "dm_blk_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588777376,
      "name": "dm_blk_report_zones",
      "external": false,
      "loc": "drivers/md/dm.c:478",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588777376,
      "name": "dm_blk_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int dm_blk_report_zones(struct gendisk * disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void * data)
```

```json
{
  "name": "dm_blk_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588798272,
      "name": "dm_blk_report_zones",
      "external": false,
      "loc": "drivers/md/dm.c:473",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588798272,
      "name": "dm_blk_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int dm_blk_report_zones(struct gendisk * disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void * data)
```

```json
{
  "name": "dm_blk_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588682992,
      "name": "dm_blk_report_zones",
      "external": false,
      "loc": "drivers/md/dm.c:478",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588682992,
      "name": "dm_blk_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int dm_blk_report_zones(struct gendisk * disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void * data)
```

```json
{
  "name": "dm_blk_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589354080,
      "name": "dm_blk_report_zones",
      "external": true,
      "loc": "drivers/md/dm-zone.c:55",
      "file": "drivers/md/dm-zone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589354080,
      "name": "dm_blk_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int dm_blk_report_zones(struct gendisk * disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void * data)
```

```json
{
  "name": "dm_blk_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590827856,
      "name": "dm_blk_report_zones",
      "external": true,
      "loc": "drivers/md/dm-zone.c:55",
      "file": "drivers/md/dm-zone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590827856,
      "name": "dm_blk_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int dm_blk_report_zones(struct gendisk * disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void * data)
```

```json
{
  "name": "dm_blk_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592516368,
      "name": "dm_blk_report_zones",
      "external": true,
      "loc": "drivers/md/dm-zone.c:55",
      "file": "drivers/md/dm-zone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592516368,
      "name": "dm_blk_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int dm_blk_report_zones(struct gendisk * disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void * data)
```

```json
{
  "name": "dm_blk_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592946784,
      "name": "dm_blk_report_zones",
      "external": true,
      "loc": "drivers/md/dm-zone.c:56",
      "file": "drivers/md/dm-zone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592946784,
      "name": "dm_blk_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int dm_blk_report_zones(struct gendisk * disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void * data)
```

```json
{
  "name": "dm_blk_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593696576,
      "name": "dm_blk_report_zones",
      "external": true,
      "loc": "drivers/md/dm-zone.c:56",
      "file": "drivers/md/dm-zone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593696576,
      "name": "dm_blk_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int dm_blk_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "dm_blk_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501155904,
      "name": "dm_blk_report_zones",
      "external": false,
      "loc": "drivers/md/dm.c:443",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501155904,
      "name": "dm_blk_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
int dm_blk_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "dm_blk_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233674488,
      "name": "dm_blk_report_zones",
      "external": false,
      "loc": "drivers/md/dm.c:443",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233674488,
      "name": "dm_blk_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int dm_blk_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "dm_blk_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294675536,
      "name": "dm_blk_report_zones",
      "external": false,
      "loc": "drivers/md/dm.c:443",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294675536,
      "name": "dm_blk_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
int dm_blk_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "dm_blk_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277870738,
      "name": "dm_blk_report_zones",
      "external": false,
      "loc": "drivers/md/dm.c:443",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277870738,
      "name": "dm_blk_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
int dm_blk_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "dm_blk_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587558016,
      "name": "dm_blk_report_zones",
      "external": false,
      "loc": "drivers/md/dm.c:443",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587558016,
      "name": "dm_blk_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
int dm_blk_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "dm_blk_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587326096,
      "name": "dm_blk_report_zones",
      "external": false,
      "loc": "drivers/md/dm.c:443",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587326096,
      "name": "dm_blk_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
int dm_blk_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "dm_blk_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587883184,
      "name": "dm_blk_report_zones",
      "external": false,
      "loc": "drivers/md/dm.c:443",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587883184,
      "name": "dm_blk_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
int dm_blk_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "dm_blk_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588000176,
      "name": "dm_blk_report_zones",
      "external": false,
      "loc": "drivers/md/dm.c:443",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588000176,
      "name": "dm_blk_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int dm_blk_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones, gfp_t gfp_mask)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>report_zones_cb cb</code>
</li>
<li>
<b>Param added. </b>
<code>void * data</code>
</li>
<li>
<b>Param removed. </b>
<code>struct blk_zone * zones</code>
</li>
<li>
<b>Param reordered. </b>
<code>disk, sector, zones, nr_zones</code> ➡️ <code>disk, sector, nr_zones, cb, data</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int * nr_zones</code> ➡️ <code>unsigned int nr_zones</code>
</li>
</ul>
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
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
