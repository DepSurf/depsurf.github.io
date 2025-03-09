# Function: <code>dm_zone_map_bio_end</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
blk_status_t dm_zone_map_bio_end(struct mapped_device * md, struct bio * orig_bio, unsigned int nr_sectors)
```

```json
{
  "name": "dm_zone_map_bio_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dm_zone_map_bio_end",
      "external": false,
      "loc": "drivers/md/dm-zone.c:428",
      "file": "drivers/md/dm-zone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_zone_map_bio",
        "drivers/md/dm-zone.c:dm_zone_map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589352832,
      "name": "dm_zone_map_bio_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    },
    {
      "addr": 18446744071592648008,
      "name": "dm_zone_map_bio_end.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_zone_map_bio_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "dm_zone_map_bio_end",
      "external": false,
      "loc": "drivers/md/dm-zone.c:429",
      "file": "drivers/md/dm-zone.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_zone_map_bio",
        "drivers/md/dm-zone.c:dm_zone_map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590826592,
      "name": "dm_zone_map_bio_end.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071594533040,
      "name": "dm_zone_map_bio_end.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_zone_map_bio_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592514944,
      "name": "dm_zone_map_bio_end",
      "external": false,
      "loc": "drivers/md/dm-zone.c:424",
      "file": "drivers/md/dm-zone.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_zone_map_bio",
        "drivers/md/dm-zone.c:dm_zone_map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592514944,
      "name": "dm_zone_map_bio_end.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_zone_map_bio_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592945744,
      "name": "dm_zone_map_bio_end",
      "external": false,
      "loc": "drivers/md/dm-zone.c:423",
      "file": "drivers/md/dm-zone.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_zone_map_bio",
        "drivers/md/dm-zone.c:dm_zone_map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592945744,
      "name": "dm_zone_map_bio_end.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
blk_status_t dm_zone_map_bio_end(struct mapped_device * md, unsigned int zno, struct orig_bio_details * orig_bio_details, unsigned int nr_sectors)
```

```json
{
  "name": "dm_zone_map_bio_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dm_zone_map_bio_end",
      "external": false,
      "loc": "drivers/md/dm-zone.c:423",
      "file": "drivers/md/dm-zone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_zone_map_bio",
        "drivers/md/dm-zone.c:dm_zone_map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593695744,
      "name": "dm_zone_map_bio_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    },
    {
      "addr": 18446744071597764932,
      "name": "dm_zone_map_bio_end.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
blk_status_t dm_zone_map_bio_end(struct mapped_device * md, struct bio * orig_bio, unsigned int nr_sectors)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
blk_status_t dm_zone_map_bio_end(struct mapped_device * md, struct bio * orig_bio, unsigned int nr_sectors)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
blk_status_t dm_zone_map_bio_end(struct mapped_device * md, unsigned int zno, struct orig_bio_details * orig_bio_details, unsigned int nr_sectors)
```
</details>
</li>
</ul>
