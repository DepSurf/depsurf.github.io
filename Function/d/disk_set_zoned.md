# Function: <code>disk_set_zoned</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void disk_set_zoned(struct gendisk * disk, enum blk_zoned_model model)
```

```json
{
  "name": "disk_set_zoned",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586422880,
      "name": "disk_set_zoned",
      "external": true,
      "loc": "block/blk-settings.c:909",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/core.c:add_partition",
        "drivers/scsi/sd.c:sd_read_block_characteristics",
        "drivers/scsi/sd.c:sd_read_block_characteristics",
        "drivers/scsi/sd.c:sd_read_block_characteristics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586422880,
      "name": "disk_set_zoned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
void disk_set_zoned(struct gendisk * disk, enum blk_zoned_model model)
```

```json
{
  "name": "disk_set_zoned",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586670400,
      "name": "disk_set_zoned",
      "external": true,
      "loc": "block/blk-settings.c:918",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/core.c:add_partition",
        "drivers/block/virtio_blk.c:virtblk_config_changed_work",
        "drivers/block/virtio_blk.c:virtblk_probe_zoned_device",
        "drivers/scsi/sd.c:sd_read_block_characteristics",
        "drivers/scsi/sd.c:sd_read_block_characteristics",
        "drivers/scsi/sd.c:sd_read_block_characteristics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586670400,
      "name": "disk_set_zoned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
void disk_set_zoned(struct gendisk * disk)
```

```json
{
  "name": "disk_set_zoned",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586941376,
      "name": "disk_set_zoned",
      "external": true,
      "loc": "block/blk-settings.c:891",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/virtio_blk.c:virtblk_probe_zoned_device",
        "drivers/scsi/sd.c:sd_read_block_characteristics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586941376,
      "name": "disk_set_zoned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void disk_set_zoned(struct gendisk * disk, enum blk_zoned_model model)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>enum blk_zoned_model model</code>
</li>
</ul>
</details>
</li>
</ul>
