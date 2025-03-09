# Function: <code>__blkdev_issue_write_same</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blkdev_issue_write_same",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583172676,
      "name": "__blkdev_issue_write_same",
      "external": false,
      "loc": "block/blk-lib.c:151",
      "file": "block/blk-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:blkdev_issue_write_same"
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
  "name": "__blkdev_issue_write_same",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583229916,
      "name": "__blkdev_issue_write_same",
      "external": false,
      "loc": "block/blk-lib.c:146",
      "file": "block/blk-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:blkdev_issue_write_same"
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
  "name": "__blkdev_issue_write_same",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583406844,
      "name": "__blkdev_issue_write_same",
      "external": false,
      "loc": "block/blk-lib.c:147",
      "file": "block/blk-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:blkdev_issue_write_same"
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
  "name": "__blkdev_issue_write_same",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583617382,
      "name": "__blkdev_issue_write_same",
      "external": false,
      "loc": "block/blk-lib.c:166",
      "file": "block/blk-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:blkdev_issue_write_same"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blkdev_issue_write_same",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583721574,
      "name": "__blkdev_issue_write_same",
      "external": false,
      "loc": "block/blk-lib.c:131",
      "file": "block/blk-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:blkdev_issue_write_same"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blkdev_issue_write_same",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583909755,
      "name": "__blkdev_issue_write_same",
      "external": false,
      "loc": "block/blk-lib.c:131",
      "file": "block/blk-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:blkdev_issue_write_same"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blkdev_issue_write_same",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584012939,
      "name": "__blkdev_issue_write_same",
      "external": false,
      "loc": "block/blk-lib.c:131",
      "file": "block/blk-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:blkdev_issue_write_same"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __blkdev_issue_write_same(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct page * page, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_write_same",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584406400,
      "name": "__blkdev_issue_write_same",
      "external": false,
      "loc": "block/blk-lib.c:131",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_write_same"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584406400,
      "name": "__blkdev_issue_write_same",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
int __blkdev_issue_write_same(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct page * page, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_write_same",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584522304,
      "name": "__blkdev_issue_write_same",
      "external": false,
      "loc": "block/blk-lib.c:165",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_write_same"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584522304,
      "name": "__blkdev_issue_write_same",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 518
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blkdev_issue_write_same",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584555014,
      "name": "__blkdev_issue_write_same",
      "external": false,
      "loc": "block/blk-lib.c:165",
      "file": "block/blk-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:blkdev_issue_write_same"
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
  "name": "__blkdev_issue_write_same",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584966422,
      "name": "__blkdev_issue_write_same",
      "external": false,
      "loc": "block/blk-lib.c:166",
      "file": "block/blk-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:blkdev_issue_write_same"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__blkdev_issue_write_same",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495842944,
      "name": "__blkdev_issue_write_same",
      "external": false,
      "loc": "block/blk-lib.c:131",
      "file": "block/blk-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:blkdev_issue_write_same"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__blkdev_issue_write_same",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229190948,
      "name": "__blkdev_issue_write_same",
      "external": false,
      "loc": "block/blk-lib.c:131",
      "file": "block/blk-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:blkdev_issue_write_same"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__blkdev_issue_write_same",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290035668,
      "name": "__blkdev_issue_write_same",
      "external": false,
      "loc": "block/blk-lib.c:131",
      "file": "block/blk-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:blkdev_issue_write_same"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__blkdev_issue_write_same",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274973208,
      "name": "__blkdev_issue_write_same",
      "external": false,
      "loc": "block/blk-lib.c:131",
      "file": "block/blk-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:blkdev_issue_write_same"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blkdev_issue_write_same",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583981675,
      "name": "__blkdev_issue_write_same",
      "external": false,
      "loc": "block/blk-lib.c:131",
      "file": "block/blk-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:blkdev_issue_write_same"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blkdev_issue_write_same",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583917531,
      "name": "__blkdev_issue_write_same",
      "external": false,
      "loc": "block/blk-lib.c:131",
      "file": "block/blk-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:blkdev_issue_write_same"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blkdev_issue_write_same",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583965435,
      "name": "__blkdev_issue_write_same",
      "external": false,
      "loc": "block/blk-lib.c:131",
      "file": "block/blk-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:blkdev_issue_write_same"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blkdev_issue_write_same",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584067494,
      "name": "__blkdev_issue_write_same",
      "external": false,
      "loc": "block/blk-lib.c:131",
      "file": "block/blk-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:blkdev_issue_write_same"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __blkdev_issue_write_same(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct page * page, struct bio * * biop)
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
int __blkdev_issue_write_same(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct page * page, struct bio * * biop)
```
</details>
</li>
</ul>
