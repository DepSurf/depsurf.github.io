# Function: <code>dm_zone_map_bio_begin</code>

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
bool dm_zone_map_bio_begin(struct mapped_device * md, struct bio * orig_bio, struct bio * clone)
```

```json
{
  "name": "dm_zone_map_bio_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dm_zone_map_bio_begin",
      "external": false,
      "loc": "drivers/md/dm-zone.c:369",
      "file": "drivers/md/dm-zone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_zone_map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589353184,
      "name": "dm_zone_map_bio_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 567
    },
    {
      "addr": 18446744071592648089,
      "name": "dm_zone_map_bio_begin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool dm_zone_map_bio_begin(struct mapped_device * md, unsigned int zno, struct bio * clone)
```

```json
{
  "name": "dm_zone_map_bio_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dm_zone_map_bio_begin",
      "external": false,
      "loc": "drivers/md/dm-zone.c:373",
      "file": "drivers/md/dm-zone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_zone_map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590827024,
      "name": "dm_zone_map_bio_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
    },
    {
      "addr": 18446744071594533074,
      "name": "dm_zone_map_bio_begin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
bool dm_zone_map_bio_begin(struct mapped_device * md, unsigned int zno, struct bio * clone)
```

```json
{
  "name": "dm_zone_map_bio_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592515456,
      "name": "dm_zone_map_bio_begin",
      "external": false,
      "loc": "drivers/md/dm-zone.c:368",
      "file": "drivers/md/dm-zone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_zone_map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592515456,
      "name": "dm_zone_map_bio_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
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
bool dm_zone_map_bio_begin(struct mapped_device * md, unsigned int zno, struct bio * clone)
```

```json
{
  "name": "dm_zone_map_bio_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592946256,
      "name": "dm_zone_map_bio_begin",
      "external": false,
      "loc": "drivers/md/dm-zone.c:367",
      "file": "drivers/md/dm-zone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_zone_map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592946256,
      "name": "dm_zone_map_bio_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
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
bool dm_zone_map_bio_begin(struct mapped_device * md, unsigned int zno, struct bio * clone)
```

```json
{
  "name": "dm_zone_map_bio_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dm_zone_map_bio_begin",
      "external": false,
      "loc": "drivers/md/dm-zone.c:367",
      "file": "drivers/md/dm-zone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_zone_map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593696016,
      "name": "dm_zone_map_bio_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
    },
    {
      "addr": 18446744071597764964,
      "name": "dm_zone_map_bio_begin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
bool dm_zone_map_bio_begin(struct mapped_device * md, struct bio * orig_bio, struct bio * clone)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int zno</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bio * orig_bio</code>
</li>
</ul>
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
