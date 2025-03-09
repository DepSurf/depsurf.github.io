# Function: <code>bdev_check_media_change</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool bdev_check_media_change(struct block_device * bdev)
```

```json
{
  "name": "bdev_check_media_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584577814,
      "name": "bdev_check_media_change",
      "external": true,
      "loc": "block/genhd.c:1885",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_open",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/md/md.c:md_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591373081,
      "name": "bdev_check_media_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071584577616,
      "name": "bdev_check_media_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool bdev_check_media_change(struct block_device * bdev)
```

```json
{
  "name": "bdev_check_media_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584609881,
      "name": "bdev_check_media_change",
      "external": true,
      "loc": "block/genhd.c:1590",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_open",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/md/md.c:md_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591315695,
      "name": "bdev_check_media_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071584609680,
      "name": "bdev_check_media_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool bdev_check_media_change(struct block_device * bdev)
```

```json
{
  "name": "bdev_check_media_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585066697,
      "name": "bdev_check_media_change",
      "external": true,
      "loc": "block/disk-events.c:275",
      "file": "block/disk-events.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_open",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/md/md.c:md_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592319922,
      "name": "bdev_check_media_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071585066496,
      "name": "bdev_check_media_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool bdev_check_media_change(struct block_device * bdev)
```

```json
{
  "name": "bdev_check_media_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585790024,
      "name": "bdev_check_media_change",
      "external": true,
      "loc": "block/disk-events.c:275",
      "file": "block/disk-events.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_open",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/md/md.c:md_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594104386,
      "name": "bdev_check_media_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071585789840,
      "name": "bdev_check_media_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool bdev_check_media_change(struct block_device * bdev)
```

```json
{
  "name": "bdev_check_media_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586570528,
      "name": "bdev_check_media_change",
      "external": true,
      "loc": "block/disk-events.c:275",
      "file": "block/disk-events.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_open",
        "drivers/scsi/sr.c:sr_block_open",
        "drivers/md/md.c:md_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586570528,
      "name": "bdev_check_media_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
    }
  ]
}
```
</details>
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
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
bool bdev_check_media_change(struct block_device * bdev)
```
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
bool bdev_check_media_change(struct block_device * bdev)
```
</details>
</li>
</ul>
