# Function: <code>blkdev_put_whole</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blkdev_put_whole(struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "blkdev_put_whole",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584892633,
      "name": "blkdev_put_whole",
      "external": false,
      "loc": "block/bdev.c:686",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bdev.c:blkdev_put",
        "block/bdev.c:blkdev_put"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584891760,
      "name": "blkdev_put_whole",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void blkdev_put_whole(struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "blkdev_put_whole",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585590464,
      "name": "blkdev_put_whole",
      "external": false,
      "loc": "block/bdev.c:691",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bdev.c:blkdev_put",
        "block/bdev.c:blkdev_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585590464,
      "name": "blkdev_put_whole",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
void blkdev_put_whole(struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "blkdev_put_whole",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586357120,
      "name": "blkdev_put_whole",
      "external": false,
      "loc": "block/bdev.c:690",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bdev.c:blkdev_put",
        "block/bdev.c:blkdev_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586357120,
      "name": "blkdev_put_whole",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
void blkdev_put_whole(struct block_device * bdev)
```

```json
{
  "name": "blkdev_put_whole",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586603760,
      "name": "blkdev_put_whole",
      "external": false,
      "loc": "block/bdev.c:675",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bdev.c:blkdev_put",
        "block/bdev.c:blkdev_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586603760,
      "name": "blkdev_put_whole",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void blkdev_put_whole(struct block_device * bdev)
```

```json
{
  "name": "blkdev_put_whole",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586872752,
      "name": "blkdev_put_whole",
      "external": false,
      "loc": "block/bdev.c:666",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bdev.c:bdev_release",
        "block/bdev.c:bdev_release",
        "block/bdev.c:bdev_open_by_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586872752,
      "name": "blkdev_put_whole",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void blkdev_put_whole(struct block_device * bdev, fmode_t mode)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>fmode_t mode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
