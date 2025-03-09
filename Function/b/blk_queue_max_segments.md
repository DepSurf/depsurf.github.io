# Function: <code>blk_queue_max_segments</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_max_segments(struct request_queue * q, short unsigned int max_segments)
```

```json
{
  "name": "blk_queue_max_segments",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582770400,
      "name": "blk_queue_max_segments",
      "external": true,
      "loc": "block/blk-settings.c:309",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-settings.c:blk_queue_dma_drain"
      ],
      "caller_func": [
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/block/xen-blkfront.c:blkif_recover",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582770400,
      "name": "blk_queue_max_segments",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void blk_queue_max_segments(struct request_queue * q, short unsigned int max_segments)
```

```json
{
  "name": "blk_queue_max_segments",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583048800,
      "name": "blk_queue_max_segments",
      "external": true,
      "loc": "block/blk-settings.c:309",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583048800,
      "name": "blk_queue_max_segments",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void blk_queue_max_segments(struct request_queue * q, short unsigned int max_segments)
```

```json
{
  "name": "blk_queue_max_segments",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583154400,
      "name": "blk_queue_max_segments",
      "external": true,
      "loc": "block/blk-settings.c:327",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583154400,
      "name": "blk_queue_max_segments",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_max_segments(struct request_queue * q, short unsigned int max_segments)
```

```json
{
  "name": "blk_queue_max_segments",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583211632,
      "name": "blk_queue_max_segments",
      "external": true,
      "loc": "block/blk-settings.c:322",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583211632,
      "name": "blk_queue_max_segments",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_max_segments(struct request_queue * q, short unsigned int max_segments)
```

```json
{
  "name": "blk_queue_max_segments",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583388336,
      "name": "blk_queue_max_segments",
      "external": true,
      "loc": "block/blk-settings.c:323",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583388336,
      "name": "blk_queue_max_segments",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void blk_queue_max_segments(struct request_queue * q, short unsigned int max_segments)
```

```json
{
  "name": "blk_queue_max_segments",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583597622,
      "name": "blk_queue_max_segments",
      "external": true,
      "loc": "block/blk-settings.c:323",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-settings.c:blk_queue_dma_drain"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583600075,
      "name": "blk_queue_max_segments.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071583598192,
      "name": "blk_queue_max_segments",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void blk_queue_max_segments(struct request_queue * q, short unsigned int max_segments)
```

```json
{
  "name": "blk_queue_max_segments",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583704150,
      "name": "blk_queue_max_segments",
      "external": true,
      "loc": "block/blk-settings.c:267",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-settings.c:blk_queue_dma_drain"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583706315,
      "name": "blk_queue_max_segments.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071583704464,
      "name": "blk_queue_max_segments",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void blk_queue_max_segments(struct request_queue * q, short unsigned int max_segments)
```

```json
{
  "name": "blk_queue_max_segments",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583892758,
      "name": "blk_queue_max_segments",
      "external": true,
      "loc": "block/blk-settings.c:268",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-settings.c:blk_queue_dma_drain"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583894909,
      "name": "blk_queue_max_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071583893088,
      "name": "blk_queue_max_segments",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void blk_queue_max_segments(struct request_queue * q, short unsigned int max_segments)
```

```json
{
  "name": "blk_queue_max_segments",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583996022,
      "name": "blk_queue_max_segments",
      "external": true,
      "loc": "block/blk-settings.c:269",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-settings.c:blk_queue_dma_drain"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583998269,
      "name": "blk_queue_max_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071583996384,
      "name": "blk_queue_max_segments",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void blk_queue_max_segments(struct request_queue * q, short unsigned int max_segments)
```

```json
{
  "name": "blk_queue_max_segments",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_max_segments",
      "external": true,
      "loc": "block/blk-settings.c:262",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584387295,
      "name": "blk_queue_max_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071584385072,
      "name": "blk_queue_max_segments",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void blk_queue_max_segments(struct request_queue * q, short unsigned int max_segments)
```

```json
{
  "name": "blk_queue_max_segments",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_max_segments",
      "external": true,
      "loc": "block/blk-settings.c:266",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591372561,
      "name": "blk_queue_max_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071584499216,
      "name": "blk_queue_max_segments",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void blk_queue_max_segments(struct request_queue * q, short unsigned int max_segments)
```

```json
{
  "name": "blk_queue_max_segments",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_max_segments",
      "external": true,
      "loc": "block/blk-settings.c:239",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591315160,
      "name": "blk_queue_max_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071584533728,
      "name": "blk_queue_max_segments",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void blk_queue_max_segments(struct request_queue * q, short unsigned int max_segments)
```

```json
{
  "name": "blk_queue_max_segments",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_max_segments",
      "external": true,
      "loc": "block/blk-settings.c:242",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592313211,
      "name": "blk_queue_max_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071584944688,
      "name": "blk_queue_max_segments",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void blk_queue_max_segments(struct request_queue * q, short unsigned int max_segments)
```

```json
{
  "name": "blk_queue_max_segments",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_max_segments",
      "external": true,
      "loc": "block/blk-settings.c:241",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594095937,
      "name": "blk_queue_max_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071585647632,
      "name": "blk_queue_max_segments",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void blk_queue_max_segments(struct request_queue * q, short unsigned int max_segments)
```

```json
{
  "name": "blk_queue_max_segments",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586420128,
      "name": "blk_queue_max_segments",
      "external": true,
      "loc": "block/blk-settings.c:241",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586420128,
      "name": "blk_queue_max_segments",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void blk_queue_max_segments(struct request_queue * q, short unsigned int max_segments)
```

```json
{
  "name": "blk_queue_max_segments",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586667632,
      "name": "blk_queue_max_segments",
      "external": true,
      "loc": "block/blk-settings.c:247",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586667632,
      "name": "blk_queue_max_segments",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void blk_queue_max_segments(struct request_queue * q, short unsigned int max_segments)
```

```json
{
  "name": "blk_queue_max_segments",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586938688,
      "name": "blk_queue_max_segments",
      "external": true,
      "loc": "block/blk-settings.c:246",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586938688,
      "name": "blk_queue_max_segments",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void blk_queue_max_segments(struct request_queue * q, short unsigned int max_segments)
```

```json
{
  "name": "blk_queue_max_segments",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495823516,
      "name": "blk_queue_max_segments",
      "external": true,
      "loc": "block/blk-settings.c:269",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-settings.c:blk_queue_dma_drain"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/mmc/core/queue.c:mmc_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495823888,
      "name": "blk_queue_max_segments",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void blk_queue_max_segments(struct request_queue * q, short unsigned int max_segments)
```

```json
{
  "name": "blk_queue_max_segments",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229172824,
      "name": "blk_queue_max_segments",
      "external": true,
      "loc": "block/blk-settings.c:269",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-settings.c:blk_queue_dma_drain"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/mmc/core/queue.c:mmc_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229173180,
      "name": "blk_queue_max_segments",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void blk_queue_max_segments(struct request_queue * q, short unsigned int max_segments)
```

```json
{
  "name": "blk_queue_max_segments",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290012392,
      "name": "blk_queue_max_segments",
      "external": true,
      "loc": "block/blk-settings.c:269",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-settings.c:blk_queue_dma_drain"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290012720,
      "name": "blk_queue_max_segments",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void blk_queue_max_segments(struct request_queue * q, short unsigned int max_segments)
```

```json
{
  "name": "blk_queue_max_segments",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274958272,
      "name": "blk_queue_max_segments",
      "external": true,
      "loc": "block/blk-settings.c:269",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-settings.c:blk_queue_dma_drain"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/mmc/core/queue.c:mmc_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274958596,
      "name": "blk_queue_max_segments",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void blk_queue_max_segments(struct request_queue * q, short unsigned int max_segments)
```

```json
{
  "name": "blk_queue_max_segments",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583964758,
      "name": "blk_queue_max_segments",
      "external": true,
      "loc": "block/blk-settings.c:269",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-settings.c:blk_queue_dma_drain"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/nvme/host/core.c:nvme_set_queue_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583967005,
      "name": "blk_queue_max_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071583965120,
      "name": "blk_queue_max_segments",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void blk_queue_max_segments(struct request_queue * q, short unsigned int max_segments)
```

```json
{
  "name": "blk_queue_max_segments",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583901670,
      "name": "blk_queue_max_segments",
      "external": true,
      "loc": "block/blk-settings.c:269",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-settings.c:blk_queue_dma_drain"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/nvme/host/core.c:nvme_set_queue_limits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583903917,
      "name": "blk_queue_max_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071583902032,
      "name": "blk_queue_max_segments",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void blk_queue_max_segments(struct request_queue * q, short unsigned int max_segments)
```

```json
{
  "name": "blk_queue_max_segments",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583948518,
      "name": "blk_queue_max_segments",
      "external": true,
      "loc": "block/blk-settings.c:269",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-settings.c:blk_queue_dma_drain"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583950765,
      "name": "blk_queue_max_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071583948880,
      "name": "blk_queue_max_segments",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void blk_queue_max_segments(struct request_queue * q, short unsigned int max_segments)
```

```json
{
  "name": "blk_queue_max_segments",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584050502,
      "name": "blk_queue_max_segments",
      "external": true,
      "loc": "block/blk-settings.c:269",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-settings.c:blk_queue_dma_drain"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584052749,
      "name": "blk_queue_max_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071584050864,
      "name": "blk_queue_max_segments",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
