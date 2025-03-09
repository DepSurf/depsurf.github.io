# Function: <code>alloc_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct gendisk * alloc_disk(int minors)
```

```json
{
  "name": "alloc_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582824096,
      "name": "alloc_disk",
      "external": true,
      "loc": "block/genhd.c:1255",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/brd.c:brd_alloc",
        "drivers/block/loop.c:loop_add",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582824096,
      "name": "alloc_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct gendisk * alloc_disk(int minors)
```

```json
{
  "name": "alloc_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583103328,
      "name": "alloc_disk",
      "external": true,
      "loc": "block/genhd.c:1284",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/brd.c:brd_alloc",
        "drivers/block/loop.c:loop_add",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583103328,
      "name": "alloc_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct gendisk * alloc_disk(int minors)
```

```json
{
  "name": "alloc_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583214832,
      "name": "alloc_disk",
      "external": true,
      "loc": "block/genhd.c:1284",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583214832,
      "name": "alloc_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct gendisk * alloc_disk(int minors)
```

```json
{
  "name": "alloc_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583272704,
      "name": "alloc_disk",
      "external": true,
      "loc": "block/genhd.c:1307",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583272704,
      "name": "alloc_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
struct gendisk * alloc_disk(int minors)
```
</details>
</li>
</ul>
