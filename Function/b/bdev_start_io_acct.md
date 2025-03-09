# Function: <code>bdev_start_io_acct</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int bdev_start_io_acct(struct block_device * bdev, unsigned int sectors, unsigned int op, long unsigned int start_time)
```

```json
{
  "name": "bdev_start_io_acct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585634864,
      "name": "bdev_start_io_acct",
      "external": true,
      "loc": "block/blk-core.c:999",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:bio_start_io_acct",
        "block/blk-core.c:bio_start_io_acct_time",
        "drivers/md/dm.c:dm_io_acct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585634864,
      "name": "bdev_start_io_acct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
long unsigned int bdev_start_io_acct(struct block_device * bdev, unsigned int sectors, enum req_op op, long unsigned int start_time)
```

```json
{
  "name": "bdev_start_io_acct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586406048,
      "name": "bdev_start_io_acct",
      "external": true,
      "loc": "block/blk-core.c:949",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:bio_start_io_acct",
        "drivers/md/dm.c:dm_io_acct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586406048,
      "name": "bdev_start_io_acct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
long unsigned int bdev_start_io_acct(struct block_device * bdev, enum req_op op, long unsigned int start_time)
```

```json
{
  "name": "bdev_start_io_acct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586654031,
      "name": "bdev_start_io_acct",
      "external": true,
      "loc": "block/blk-core.c:952",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:bio_start_io_acct"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_io_acct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586653312,
      "name": "bdev_start_io_acct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
long unsigned int bdev_start_io_acct(struct block_device * bdev, enum req_op op, long unsigned int start_time)
```

```json
{
  "name": "bdev_start_io_acct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586925295,
      "name": "bdev_start_io_acct",
      "external": true,
      "loc": "block/blk-core.c:987",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:bio_start_io_acct"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_io_acct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586924576,
      "name": "bdev_start_io_acct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
long unsigned int bdev_start_io_acct(struct block_device * bdev, unsigned int sectors, unsigned int op, long unsigned int start_time)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int op</code> ➡️ <code>enum req_op op</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int sectors</code>
</li>
<li>
<b>Param reordered. </b>
<code>bdev, sectors, op, start_time</code> ➡️ <code>bdev, op, start_time</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
