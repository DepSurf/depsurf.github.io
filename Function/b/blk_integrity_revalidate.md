# Function: <code>blk_integrity_revalidate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_integrity_revalidate(struct gendisk * disk)
```

```json
{
  "name": "blk_integrity_revalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582940053,
      "name": "blk_integrity_revalidate",
      "external": true,
      "loc": "block/blk-integrity.c:438",
      "file": "block/blk-integrity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-integrity.c:blk_integrity_register",
        "block/blk-integrity.c:blk_integrity_unregister"
      ],
      "caller_func": [
        "fs/block_dev.c:revalidate_disk",
        "block/partition-generic.c:rescan_partitions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582943040,
      "name": "blk_integrity_revalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_integrity_revalidate(struct gendisk * disk)
```

```json
{
  "name": "blk_integrity_revalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583228629,
      "name": "blk_integrity_revalidate",
      "external": true,
      "loc": "block/blk-integrity.c:438",
      "file": "block/blk-integrity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-integrity.c:blk_integrity_unregister",
        "block/blk-integrity.c:blk_integrity_register"
      ],
      "caller_func": [
        "fs/block_dev.c:revalidate_disk",
        "block/partition-generic.c:rescan_partitions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583230368,
      "name": "blk_integrity_revalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_integrity_revalidate(struct gendisk * disk)
```

```json
{
  "name": "blk_integrity_revalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583334517,
      "name": "blk_integrity_revalidate",
      "external": true,
      "loc": "block/blk-integrity.c:438",
      "file": "block/blk-integrity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-integrity.c:blk_integrity_unregister",
        "block/blk-integrity.c:blk_integrity_register"
      ],
      "caller_func": [
        "fs/block_dev.c:revalidate_disk",
        "block/partition-generic.c:rescan_partitions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583336224,
      "name": "blk_integrity_revalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void blk_integrity_revalidate(struct gendisk * disk)
```
</details>
</li>
</ul>
