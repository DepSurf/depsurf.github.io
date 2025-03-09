# Function: <code>disk_has_partitions</code>

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
bool disk_has_partitions(struct gendisk * disk)
```

```json
{
  "name": "disk_has_partitions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584451344,
      "name": "disk_has_partitions",
      "external": true,
      "loc": "block/genhd.c:367",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-settings.c:blk_queue_set_zoned"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584451344,
      "name": "disk_has_partitions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
bool disk_has_partitions(struct gendisk * disk)
```

```json
{
  "name": "disk_has_partitions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584567984,
      "name": "disk_has_partitions",
      "external": true,
      "loc": "block/genhd.c:351",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-settings.c:blk_queue_set_zoned"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584567984,
      "name": "disk_has_partitions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "disk_has_partitions",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584946847,
      "name": "disk_has_partitions",
      "external": false,
      "loc": "block/blk-settings.c:845",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-settings.c:blk_queue_set_zoned"
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
  "name": "disk_has_partitions",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585650205,
      "name": "disk_has_partitions",
      "external": false,
      "loc": "block/blk-settings.c:877",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-settings.c:blk_queue_set_zoned"
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
  "name": "disk_has_partitions",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586423088,
      "name": "disk_has_partitions",
      "external": false,
      "loc": "block/blk-settings.c:878",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-settings.c:disk_set_zoned"
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
  "name": "disk_has_partitions",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586670624,
      "name": "disk_has_partitions",
      "external": false,
      "loc": "block/blk-settings.c:887",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-settings.c:disk_set_zoned"
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
bool disk_has_partitions(struct gendisk * disk)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
bool disk_has_partitions(struct gendisk * disk)
```
</details>
</li>
</ul>
