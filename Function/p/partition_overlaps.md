# Function: <code>partition_overlaps</code>

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
bool partition_overlaps(struct gendisk * disk, sector_t start, sector_t length, int skip_partno)
```

```json
{
  "name": "partition_overlaps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584468912,
      "name": "partition_overlaps",
      "external": false,
      "loc": "block/partitions/core.c:486",
      "file": "block/partitions/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/core.c:bdev_resize_partition",
        "block/partitions/core.c:bdev_add_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584468912,
      "name": "partition_overlaps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
bool partition_overlaps(struct gendisk * disk, sector_t start, sector_t length, int skip_partno)
```

```json
{
  "name": "partition_overlaps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584583872,
      "name": "partition_overlaps",
      "external": false,
      "loc": "block/partitions/core.c:430",
      "file": "block/partitions/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/core.c:bdev_resize_partition",
        "block/partitions/core.c:bdev_add_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584583872,
      "name": "partition_overlaps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
bool partition_overlaps(struct gendisk * disk, sector_t start, sector_t length, int skip_partno)
```

```json
{
  "name": "partition_overlaps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584615920,
      "name": "partition_overlaps",
      "external": false,
      "loc": "block/partitions/core.c:427",
      "file": "block/partitions/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/core.c:bdev_resize_partition",
        "block/partitions/core.c:bdev_add_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584615920,
      "name": "partition_overlaps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
bool partition_overlaps(struct gendisk * disk, sector_t start, sector_t length, int skip_partno)
```

```json
{
  "name": "partition_overlaps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585030400,
      "name": "partition_overlaps",
      "external": false,
      "loc": "block/partitions/core.c:433",
      "file": "block/partitions/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/core.c:bdev_resize_partition",
        "block/partitions/core.c:bdev_add_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585030400,
      "name": "partition_overlaps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
bool partition_overlaps(struct gendisk * disk, sector_t start, sector_t length, int skip_partno)
```

```json
{
  "name": "partition_overlaps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585747472,
      "name": "partition_overlaps",
      "external": false,
      "loc": "block/partitions/core.c:424",
      "file": "block/partitions/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/core.c:bdev_resize_partition",
        "block/partitions/core.c:bdev_add_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585747472,
      "name": "partition_overlaps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
bool partition_overlaps(struct gendisk * disk, sector_t start, sector_t length, int skip_partno)
```

```json
{
  "name": "partition_overlaps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586530000,
      "name": "partition_overlaps",
      "external": false,
      "loc": "block/partitions/core.c:423",
      "file": "block/partitions/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/core.c:bdev_resize_partition",
        "block/partitions/core.c:bdev_add_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586530000,
      "name": "partition_overlaps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
bool partition_overlaps(struct gendisk * disk, sector_t start, sector_t length, int skip_partno)
```

```json
{
  "name": "partition_overlaps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586776208,
      "name": "partition_overlaps",
      "external": false,
      "loc": "block/partitions/core.c:420",
      "file": "block/partitions/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/core.c:bdev_resize_partition",
        "block/partitions/core.c:bdev_add_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586776208,
      "name": "partition_overlaps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
bool partition_overlaps(struct gendisk * disk, sector_t start, sector_t length, int skip_partno)
```

```json
{
  "name": "partition_overlaps",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587052848,
      "name": "partition_overlaps",
      "external": false,
      "loc": "block/partitions/core.c:398",
      "file": "block/partitions/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/core.c:bdev_resize_partition",
        "block/partitions/core.c:bdev_add_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587052848,
      "name": "partition_overlaps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
bool partition_overlaps(struct gendisk * disk, sector_t start, sector_t length, int skip_partno)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
