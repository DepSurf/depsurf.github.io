# Function: <code>blk_queue_max_write_zeroes_sectors</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void blk_queue_max_write_zeroes_sectors(struct request_queue * q, unsigned int max_write_zeroes_sectors)
```

```json
{
  "name": "blk_queue_max_write_zeroes_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583153280,
      "name": "blk_queue_max_write_zeroes_sectors",
      "external": true,
      "loc": "block/blk-settings.c:311",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583153280,
      "name": "blk_queue_max_write_zeroes_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void blk_queue_max_write_zeroes_sectors(struct request_queue * q, unsigned int max_write_zeroes_sectors)
```

```json
{
  "name": "blk_queue_max_write_zeroes_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583210528,
      "name": "blk_queue_max_write_zeroes_sectors",
      "external": true,
      "loc": "block/blk-settings.c:306",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/scsi/sd.c:sd_config_write_same"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583210528,
      "name": "blk_queue_max_write_zeroes_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void blk_queue_max_write_zeroes_sectors(struct request_queue * q, unsigned int max_write_zeroes_sectors)
```

```json
{
  "name": "blk_queue_max_write_zeroes_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583387104,
      "name": "blk_queue_max_write_zeroes_sectors",
      "external": true,
      "loc": "block/blk-settings.c:307",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/scsi/sd.c:sd_config_write_same"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583387104,
      "name": "blk_queue_max_write_zeroes_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void blk_queue_max_write_zeroes_sectors(struct request_queue * q, unsigned int max_write_zeroes_sectors)
```

```json
{
  "name": "blk_queue_max_write_zeroes_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583597136,
      "name": "blk_queue_max_write_zeroes_sectors",
      "external": true,
      "loc": "block/blk-settings.c:307",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/scsi/sd.c:sd_config_write_same"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583597136,
      "name": "blk_queue_max_write_zeroes_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void blk_queue_max_write_zeroes_sectors(struct request_queue * q, unsigned int max_write_zeroes_sectors)
```

```json
{
  "name": "blk_queue_max_write_zeroes_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583703664,
      "name": "blk_queue_max_write_zeroes_sectors",
      "external": true,
      "loc": "block/blk-settings.c:251",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/scsi/sd.c:sd_config_write_same"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583703664,
      "name": "blk_queue_max_write_zeroes_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void blk_queue_max_write_zeroes_sectors(struct request_queue * q, unsigned int max_write_zeroes_sectors)
```

```json
{
  "name": "blk_queue_max_write_zeroes_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583892304,
      "name": "blk_queue_max_write_zeroes_sectors",
      "external": true,
      "loc": "block/blk-settings.c:252",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/scsi/sd.c:sd_config_write_same"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583892304,
      "name": "blk_queue_max_write_zeroes_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void blk_queue_max_write_zeroes_sectors(struct request_queue * q, unsigned int max_write_zeroes_sectors)
```

```json
{
  "name": "blk_queue_max_write_zeroes_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583995568,
      "name": "blk_queue_max_write_zeroes_sectors",
      "external": true,
      "loc": "block/blk-settings.c:253",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/scsi/sd.c:sd_config_write_same"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583995568,
      "name": "blk_queue_max_write_zeroes_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void blk_queue_max_write_zeroes_sectors(struct request_queue * q, unsigned int max_write_zeroes_sectors)
```

```json
{
  "name": "blk_queue_max_write_zeroes_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584384320,
      "name": "blk_queue_max_write_zeroes_sectors",
      "external": true,
      "loc": "block/blk-settings.c:219",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/scsi/sd.c:sd_config_write_same"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584384320,
      "name": "blk_queue_max_write_zeroes_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void blk_queue_max_write_zeroes_sectors(struct request_queue * q, unsigned int max_write_zeroes_sectors)
```

```json
{
  "name": "blk_queue_max_write_zeroes_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584498336,
      "name": "blk_queue_max_write_zeroes_sectors",
      "external": true,
      "loc": "block/blk-settings.c:223",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/scsi/sd.c:sd_config_write_same"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584498336,
      "name": "blk_queue_max_write_zeroes_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void blk_queue_max_write_zeroes_sectors(struct request_queue * q, unsigned int max_write_zeroes_sectors)
```

```json
{
  "name": "blk_queue_max_write_zeroes_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584533024,
      "name": "blk_queue_max_write_zeroes_sectors",
      "external": true,
      "loc": "block/blk-settings.c:196",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_config_discard",
        "drivers/block/loop.c:loop_config_discard",
        "drivers/scsi/sd.c:sd_config_write_same"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584533024,
      "name": "blk_queue_max_write_zeroes_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void blk_queue_max_write_zeroes_sectors(struct request_queue * q, unsigned int max_write_zeroes_sectors)
```

```json
{
  "name": "blk_queue_max_write_zeroes_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584943936,
      "name": "blk_queue_max_write_zeroes_sectors",
      "external": true,
      "loc": "block/blk-settings.c:199",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_config_discard",
        "drivers/block/loop.c:loop_config_discard",
        "drivers/scsi/sd.c:sd_config_write_same"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584943936,
      "name": "blk_queue_max_write_zeroes_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void blk_queue_max_write_zeroes_sectors(struct request_queue * q, unsigned int max_write_zeroes_sectors)
```

```json
{
  "name": "blk_queue_max_write_zeroes_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585646624,
      "name": "blk_queue_max_write_zeroes_sectors",
      "external": true,
      "loc": "block/blk-settings.c:198",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_config_write_same"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585646624,
      "name": "blk_queue_max_write_zeroes_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void blk_queue_max_write_zeroes_sectors(struct request_queue * q, unsigned int max_write_zeroes_sectors)
```

```json
{
  "name": "blk_queue_max_write_zeroes_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586418832,
      "name": "blk_queue_max_write_zeroes_sectors",
      "external": true,
      "loc": "block/blk-settings.c:198",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_config_write_same"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586418832,
      "name": "blk_queue_max_write_zeroes_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void blk_queue_max_write_zeroes_sectors(struct request_queue * q, unsigned int max_write_zeroes_sectors)
```

```json
{
  "name": "blk_queue_max_write_zeroes_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586666336,
      "name": "blk_queue_max_write_zeroes_sectors",
      "external": true,
      "loc": "block/blk-settings.c:204",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/scsi/sd.c:sd_config_write_same"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586666336,
      "name": "blk_queue_max_write_zeroes_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void blk_queue_max_write_zeroes_sectors(struct request_queue * q, unsigned int max_write_zeroes_sectors)
```

```json
{
  "name": "blk_queue_max_write_zeroes_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586937360,
      "name": "blk_queue_max_write_zeroes_sectors",
      "external": true,
      "loc": "block/blk-settings.c:203",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/scsi/sd.c:sd_config_write_same"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586937360,
      "name": "blk_queue_max_write_zeroes_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void blk_queue_max_write_zeroes_sectors(struct request_queue * q, unsigned int max_write_zeroes_sectors)
```

```json
{
  "name": "blk_queue_max_write_zeroes_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495822824,
      "name": "blk_queue_max_write_zeroes_sectors",
      "external": true,
      "loc": "block/blk-settings.c:253",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/scsi/sd.c:sd_config_write_same"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495822824,
      "name": "blk_queue_max_write_zeroes_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void blk_queue_max_write_zeroes_sectors(struct request_queue * q, unsigned int max_write_zeroes_sectors)
```

```json
{
  "name": "blk_queue_max_write_zeroes_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229172364,
      "name": "blk_queue_max_write_zeroes_sectors",
      "external": true,
      "loc": "block/blk-settings.c:253",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/scsi/sd.c:sd_config_write_same"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229172364,
      "name": "blk_queue_max_write_zeroes_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void blk_queue_max_write_zeroes_sectors(struct request_queue * q, unsigned int max_write_zeroes_sectors)
```

```json
{
  "name": "blk_queue_max_write_zeroes_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290011968,
      "name": "blk_queue_max_write_zeroes_sectors",
      "external": true,
      "loc": "block/blk-settings.c:253",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/scsi/sd.c:sd_config_write_same",
        "drivers/scsi/sd.c:sd_config_write_same",
        "drivers/scsi/sd.c:sd_config_write_same",
        "drivers/scsi/sd.c:sd_config_write_same"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290011968,
      "name": "blk_queue_max_write_zeroes_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void blk_queue_max_write_zeroes_sectors(struct request_queue * q, unsigned int max_write_zeroes_sectors)
```

```json
{
  "name": "blk_queue_max_write_zeroes_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274957690,
      "name": "blk_queue_max_write_zeroes_sectors",
      "external": true,
      "loc": "block/blk-settings.c:253",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/scsi/sd.c:sd_config_write_same"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274957690,
      "name": "blk_queue_max_write_zeroes_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void blk_queue_max_write_zeroes_sectors(struct request_queue * q, unsigned int max_write_zeroes_sectors)
```

```json
{
  "name": "blk_queue_max_write_zeroes_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583964304,
      "name": "blk_queue_max_write_zeroes_sectors",
      "external": true,
      "loc": "block/blk-settings.c:253",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/scsi/sd.c:sd_config_write_same",
        "drivers/nvme/host/core.c:nvme_update_disk_info",
        "drivers/nvme/host/core.c:nvme_update_disk_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583964304,
      "name": "blk_queue_max_write_zeroes_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void blk_queue_max_write_zeroes_sectors(struct request_queue * q, unsigned int max_write_zeroes_sectors)
```

```json
{
  "name": "blk_queue_max_write_zeroes_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583901216,
      "name": "blk_queue_max_write_zeroes_sectors",
      "external": true,
      "loc": "block/blk-settings.c:253",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/scsi/sd.c:sd_config_write_same",
        "drivers/nvme/host/core.c:nvme_update_disk_info",
        "drivers/nvme/host/core.c:nvme_update_disk_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583901216,
      "name": "blk_queue_max_write_zeroes_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void blk_queue_max_write_zeroes_sectors(struct request_queue * q, unsigned int max_write_zeroes_sectors)
```

```json
{
  "name": "blk_queue_max_write_zeroes_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583948064,
      "name": "blk_queue_max_write_zeroes_sectors",
      "external": true,
      "loc": "block/blk-settings.c:253",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/scsi/sd.c:sd_config_write_same"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583948064,
      "name": "blk_queue_max_write_zeroes_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void blk_queue_max_write_zeroes_sectors(struct request_queue * q, unsigned int max_write_zeroes_sectors)
```

```json
{
  "name": "blk_queue_max_write_zeroes_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584050048,
      "name": "blk_queue_max_write_zeroes_sectors",
      "external": true,
      "loc": "block/blk-settings.c:253",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/scsi/sd.c:sd_config_write_same"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584050048,
      "name": "blk_queue_max_write_zeroes_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void blk_queue_max_write_zeroes_sectors(struct request_queue * q, unsigned int max_write_zeroes_sectors)
```
</details>
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
