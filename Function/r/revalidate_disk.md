# Function: <code>revalidate_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk * disk)
```

```json
{
  "name": "revalidate_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581237744,
      "name": "revalidate_disk",
      "external": true,
      "loc": "fs/block_dev.c:1094",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/virtio_blk.c:virtblk_update_cache_mode",
        "drivers/block/virtio_blk.c:virtblk_update_cache_mode",
        "drivers/block/virtio_blk.c:virtblk_config_changed_work",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/scsi/sd.c:sd_rescan",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/md/md.c:array_size_store",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237744,
      "name": "revalidate_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int revalidate_disk(struct gendisk * disk)
```

```json
{
  "name": "revalidate_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581403504,
      "name": "revalidate_disk",
      "external": true,
      "loc": "fs/block_dev.c:1166",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/virtio_blk.c:virtblk_update_cache_mode",
        "drivers/block/virtio_blk.c:virtblk_config_changed_work",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/scsi/sd.c:sd_rescan",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:array_size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581403504,
      "name": "revalidate_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int revalidate_disk(struct gendisk * disk)
```

```json
{
  "name": "revalidate_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581483744,
      "name": "revalidate_disk",
      "external": true,
      "loc": "fs/block_dev.c:1418",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/sd.c:sd_rescan",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:array_size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581483744,
      "name": "revalidate_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int revalidate_disk(struct gendisk * disk)
```

```json
{
  "name": "revalidate_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581538704,
      "name": "revalidate_disk",
      "external": true,
      "loc": "fs/block_dev.c:1343",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/scsi/sd.c:sd_rescan",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581538704,
      "name": "revalidate_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk * disk)
```

```json
{
  "name": "revalidate_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581681392,
      "name": "revalidate_disk",
      "external": true,
      "loc": "fs/block_dev.c:1333",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/scsi/sd.c:sd_rescan",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581681392,
      "name": "revalidate_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk * disk)
```

```json
{
  "name": "revalidate_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581850944,
      "name": "revalidate_disk",
      "external": true,
      "loc": "fs/block_dev.c:1359",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/scsi/sd.c:sd_rescan",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581850944,
      "name": "revalidate_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk * disk)
```

```json
{
  "name": "revalidate_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581938480,
      "name": "revalidate_disk",
      "external": true,
      "loc": "fs/block_dev.c:1398",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/scsi/sd.c:sd_rescan",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581938480,
      "name": "revalidate_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk * disk)
```

```json
{
  "name": "revalidate_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582076304,
      "name": "revalidate_disk",
      "external": true,
      "loc": "fs/block_dev.c:1450",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/sd.c:sd_rescan",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582076304,
      "name": "revalidate_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk * disk)
```

```json
{
  "name": "revalidate_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582151600,
      "name": "revalidate_disk",
      "external": true,
      "loc": "fs/block_dev.c:1446",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/sd.c:sd_rescan",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582151600,
      "name": "revalidate_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk * disk)
```

```json
{
  "name": "revalidate_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582384384,
      "name": "revalidate_disk",
      "external": true,
      "loc": "fs/block_dev.c:1428",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_rescan",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582384384,
      "name": "revalidate_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk * disk)
```

```json
{
  "name": "revalidate_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493703960,
      "name": "revalidate_disk",
      "external": true,
      "loc": "fs/block_dev.c:1446",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/sd.c:sd_rescan",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493703960,
      "name": "revalidate_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk * disk)
```

```json
{
  "name": "revalidate_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227231508,
      "name": "revalidate_disk",
      "external": true,
      "loc": "fs/block_dev.c:1446",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_rescan",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227231508,
      "name": "revalidate_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk * disk)
```

```json
{
  "name": "revalidate_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287307936,
      "name": "revalidate_disk",
      "external": true,
      "loc": "fs/block_dev.c:1446",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_rescan",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287307936,
      "name": "revalidate_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk * disk)
```

```json
{
  "name": "revalidate_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273320200,
      "name": "revalidate_disk",
      "external": true,
      "loc": "fs/block_dev.c:1446",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_rescan",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273320200,
      "name": "revalidate_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk * disk)
```

```json
{
  "name": "revalidate_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582120336,
      "name": "revalidate_disk",
      "external": true,
      "loc": "fs/block_dev.c:1446",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/sd.c:sd_rescan",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/nvme/host/core.c:nvme_validate_ns",
        "drivers/nvme/host/core.c:__nvme_revalidate_disk",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582120336,
      "name": "revalidate_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk * disk)
```

```json
{
  "name": "revalidate_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582057776,
      "name": "revalidate_disk",
      "external": true,
      "loc": "fs/block_dev.c:1446",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/pmem.c:pmem_attach_disk",
        "drivers/nvdimm/blk.c:nd_blk_probe",
        "drivers/scsi/sd.c:sd_rescan",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/nvme/host/core.c:nvme_validate_ns",
        "drivers/nvme/host/core.c:__nvme_revalidate_disk",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582057776,
      "name": "revalidate_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk * disk)
```

```json
{
  "name": "revalidate_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582110816,
      "name": "revalidate_disk",
      "external": true,
      "loc": "fs/block_dev.c:1446",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/sd.c:sd_rescan",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582110816,
      "name": "revalidate_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int revalidate_disk(struct gendisk * disk)
```

```json
{
  "name": "revalidate_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582183776,
      "name": "revalidate_disk",
      "external": true,
      "loc": "fs/block_dev.c:1446",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/sd.c:sd_rescan",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582183776,
      "name": "revalidate_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
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
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int revalidate_disk(struct gendisk * disk)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
