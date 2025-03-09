# Function: <code>bdev_discard_alignment</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bdev_discard_alignment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582787287,
      "name": "bdev_discard_alignment",
      "external": false,
      "loc": "include/linux/blkdev.h:1295",
      "file": "block/blk-lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:blkdev_issue_discard"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bdev_discard_alignment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583064918,
      "name": "bdev_discard_alignment",
      "external": false,
      "loc": "include/linux/blkdev.h:1324",
      "file": "block/blk-lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:__blkdev_issue_discard"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bdev_discard_alignment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583172117,
      "name": "bdev_discard_alignment",
      "external": false,
      "loc": "include/linux/blkdev.h:1489",
      "file": "block/blk-lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:__blkdev_issue_discard"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bdev_discard_alignment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583229355,
      "name": "bdev_discard_alignment",
      "external": false,
      "loc": "include/linux/blkdev.h:1527",
      "file": "block/blk-lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:__blkdev_issue_discard"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bdev_discard_alignment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583405995,
      "name": "bdev_discard_alignment",
      "external": false,
      "loc": "include/linux/blkdev.h:1542",
      "file": "block/blk-lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:__blkdev_issue_discard"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bdev_discard_alignment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583616339,
      "name": "bdev_discard_alignment",
      "external": false,
      "loc": "include/linux/blkdev.h:1583",
      "file": "block/blk-lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:__blkdev_issue_discard"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int bdev_discard_alignment(struct block_device * bdev)
```

```json
{
  "name": "bdev_discard_alignment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585649584,
      "name": "bdev_discard_alignment",
      "external": true,
      "loc": "block/blk-settings.c:966",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/core.c:part_discard_alignment_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585649584,
      "name": "bdev_discard_alignment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
unsigned int bdev_discard_alignment(struct block_device * bdev)
```

```json
{
  "name": "bdev_discard_alignment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586422384,
      "name": "bdev_discard_alignment",
      "external": true,
      "loc": "block/blk-settings.c:968",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/core.c:part_discard_alignment_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586422384,
      "name": "bdev_discard_alignment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
unsigned int bdev_discard_alignment(struct block_device * bdev)
```

```json
{
  "name": "bdev_discard_alignment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586669904,
      "name": "bdev_discard_alignment",
      "external": true,
      "loc": "block/blk-settings.c:978",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/core.c:part_discard_alignment_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586669904,
      "name": "bdev_discard_alignment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
unsigned int bdev_discard_alignment(struct block_device * bdev)
```

```json
{
  "name": "bdev_discard_alignment",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586941056,
      "name": "bdev_discard_alignment",
      "external": true,
      "loc": "block/blk-settings.c:919",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/core.c:part_discard_alignment_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586941056,
      "name": "bdev_discard_alignment",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
unsigned int bdev_discard_alignment(struct block_device * bdev)
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
