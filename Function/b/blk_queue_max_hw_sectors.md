# Function: <code>blk_queue_max_hw_sectors</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue * q, unsigned int max_hw_sectors)
```

```json
{
  "name": "blk_queue_max_hw_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582770272,
      "name": "blk_queue_max_hw_sectors",
      "external": true,
      "loc": "block/blk-settings.c:237",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/brd.c:brd_alloc",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582770272,
      "name": "blk_queue_max_hw_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void blk_queue_max_hw_sectors(struct request_queue * q, unsigned int max_hw_sectors)
```

```json
{
  "name": "blk_queue_max_hw_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583048672,
      "name": "blk_queue_max_hw_sectors",
      "external": true,
      "loc": "block/blk-settings.c:237",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/brd.c:brd_alloc",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583048672,
      "name": "blk_queue_max_hw_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void blk_queue_max_hw_sectors(struct request_queue * q, unsigned int max_hw_sectors)
```

```json
{
  "name": "blk_queue_max_hw_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583154256,
      "name": "blk_queue_max_hw_sectors",
      "external": true,
      "loc": "block/blk-settings.c:241",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583154256,
      "name": "blk_queue_max_hw_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void blk_queue_max_hw_sectors(struct request_queue * q, unsigned int max_hw_sectors)
```

```json
{
  "name": "blk_queue_max_hw_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583211488,
      "name": "blk_queue_max_hw_sectors",
      "external": true,
      "loc": "block/blk-settings.c:236",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583211488,
      "name": "blk_queue_max_hw_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void blk_queue_max_hw_sectors(struct request_queue * q, unsigned int max_hw_sectors)
```

```json
{
  "name": "blk_queue_max_hw_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583388192,
      "name": "blk_queue_max_hw_sectors",
      "external": true,
      "loc": "block/blk-settings.c:237",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583388192,
      "name": "blk_queue_max_hw_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue * q, unsigned int max_hw_sectors)
```

```json
{
  "name": "blk_queue_max_hw_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_max_hw_sectors",
      "external": true,
      "loc": "block/blk-settings.c:237",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583600025,
      "name": "blk_queue_max_hw_sectors.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071583598096,
      "name": "blk_queue_max_hw_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue * q, unsigned int max_hw_sectors)
```

```json
{
  "name": "blk_queue_max_hw_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_max_hw_sectors",
      "external": true,
      "loc": "block/blk-settings.c:181",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583706265,
      "name": "blk_queue_max_hw_sectors.cold.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071583704368,
      "name": "blk_queue_max_hw_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue * q, unsigned int max_hw_sectors)
```

```json
{
  "name": "blk_queue_max_hw_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_max_hw_sectors",
      "external": true,
      "loc": "block/blk-settings.c:182",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583894859,
      "name": "blk_queue_max_hw_sectors.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071583892992,
      "name": "blk_queue_max_hw_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue * q, unsigned int max_hw_sectors)
```

```json
{
  "name": "blk_queue_max_hw_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_max_hw_sectors",
      "external": true,
      "loc": "block/blk-settings.c:183",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583998219,
      "name": "blk_queue_max_hw_sectors.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071583996288,
      "name": "blk_queue_max_hw_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue * q, unsigned int max_hw_sectors)
```

```json
{
  "name": "blk_queue_max_hw_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_max_hw_sectors",
      "external": true,
      "loc": "block/blk-settings.c:149",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584387245,
      "name": "blk_queue_max_hw_sectors.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071584384976,
      "name": "blk_queue_max_hw_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue * q, unsigned int max_hw_sectors)
```

```json
{
  "name": "blk_queue_max_hw_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_max_hw_sectors",
      "external": true,
      "loc": "block/blk-settings.c:149",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591372527,
      "name": "blk_queue_max_hw_sectors.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071584499104,
      "name": "blk_queue_max_hw_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue * q, unsigned int max_hw_sectors)
```

```json
{
  "name": "blk_queue_max_hw_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_max_hw_sectors",
      "external": true,
      "loc": "block/blk-settings.c:122",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591315126,
      "name": "blk_queue_max_hw_sectors.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071584533616,
      "name": "blk_queue_max_hw_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue * q, unsigned int max_hw_sectors)
```

```json
{
  "name": "blk_queue_max_hw_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_max_hw_sectors",
      "external": true,
      "loc": "block/blk-settings.c:123",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592313177,
      "name": "blk_queue_max_hw_sectors.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071584944560,
      "name": "blk_queue_max_hw_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue * q, unsigned int max_hw_sectors)
```

```json
{
  "name": "blk_queue_max_hw_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_max_hw_sectors",
      "external": true,
      "loc": "block/blk-settings.c:122",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594095903,
      "name": "blk_queue_max_hw_sectors.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071585647488,
      "name": "blk_queue_max_hw_sectors",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue * q, unsigned int max_hw_sectors)
```

```json
{
  "name": "blk_queue_max_hw_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586419936,
      "name": "blk_queue_max_hw_sectors",
      "external": true,
      "loc": "block/blk-settings.c:122",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586419936,
      "name": "blk_queue_max_hw_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void blk_queue_max_hw_sectors(struct request_queue * q, unsigned int max_hw_sectors)
```

```json
{
  "name": "blk_queue_max_hw_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586667424,
      "name": "blk_queue_max_hw_sectors",
      "external": true,
      "loc": "block/blk-settings.c:123",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_add",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586667424,
      "name": "blk_queue_max_hw_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void blk_queue_max_hw_sectors(struct request_queue * q, unsigned int max_hw_sectors)
```

```json
{
  "name": "blk_queue_max_hw_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586938480,
      "name": "blk_queue_max_hw_sectors",
      "external": true,
      "loc": "block/blk-settings.c:123",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_add",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586938480,
      "name": "blk_queue_max_hw_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue * q, unsigned int max_hw_sectors)
```

```json
{
  "name": "blk_queue_max_hw_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495823720,
      "name": "blk_queue_max_hw_sectors",
      "external": true,
      "loc": "block/blk-settings.c:183",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config",
        "drivers/mmc/core/queue.c:mmc_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495823720,
      "name": "blk_queue_max_hw_sectors",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue * q, unsigned int max_hw_sectors)
```

```json
{
  "name": "blk_queue_max_hw_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229173036,
      "name": "blk_queue_max_hw_sectors",
      "external": true,
      "loc": "block/blk-settings.c:183",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config",
        "drivers/mmc/core/queue.c:mmc_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229173036,
      "name": "blk_queue_max_hw_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void blk_queue_max_hw_sectors(struct request_queue * q, unsigned int max_hw_sectors)
```

```json
{
  "name": "blk_queue_max_hw_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290012496,
      "name": "blk_queue_max_hw_sectors",
      "external": true,
      "loc": "block/blk-settings.c:183",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290012496,
      "name": "blk_queue_max_hw_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void blk_queue_max_hw_sectors(struct request_queue * q, unsigned int max_hw_sectors)
```

```json
{
  "name": "blk_queue_max_hw_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274958446,
      "name": "blk_queue_max_hw_sectors",
      "external": true,
      "loc": "block/blk-settings.c:183",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config",
        "drivers/mmc/core/queue.c:mmc_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274958446,
      "name": "blk_queue_max_hw_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue * q, unsigned int max_hw_sectors)
```

```json
{
  "name": "blk_queue_max_hw_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_max_hw_sectors",
      "external": true,
      "loc": "block/blk-settings.c:183",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/nvme/host/core.c:nvme_set_queue_limits",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583966955,
      "name": "blk_queue_max_hw_sectors.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071583965024,
      "name": "blk_queue_max_hw_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue * q, unsigned int max_hw_sectors)
```

```json
{
  "name": "blk_queue_max_hw_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_max_hw_sectors",
      "external": true,
      "loc": "block/blk-settings.c:183",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_add",
        "drivers/nvdimm/pmem.c:pmem_attach_disk",
        "drivers/nvdimm/blk.c:nd_blk_probe",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/nvme/host/core.c:nvme_set_queue_limits",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583903867,
      "name": "blk_queue_max_hw_sectors.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071583901936,
      "name": "blk_queue_max_hw_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue * q, unsigned int max_hw_sectors)
```

```json
{
  "name": "blk_queue_max_hw_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_max_hw_sectors",
      "external": true,
      "loc": "block/blk-settings.c:183",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583950715,
      "name": "blk_queue_max_hw_sectors.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071583948784,
      "name": "blk_queue_max_hw_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue * q, unsigned int max_hw_sectors)
```

```json
{
  "name": "blk_queue_max_hw_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_max_hw_sectors",
      "external": true,
      "loc": "block/blk-settings.c:183",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/scsi/scsi_scan.c:scsi_add_lun",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584052699,
      "name": "blk_queue_max_hw_sectors.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071584050768,
      "name": "blk_queue_max_hw_sectors",
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
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
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
