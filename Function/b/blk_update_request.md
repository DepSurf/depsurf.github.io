# Function: <code>blk_update_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool blk_update_request(struct request * req, int error, unsigned int nr_bytes)
```

```json
{
  "name": "blk_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582753184,
      "name": "blk_update_request",
      "external": true,
      "loc": "block/blk-core.c:2567",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/md/dm.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582753184,
      "name": "blk_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 779
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
bool blk_update_request(struct request * req, int error, unsigned int nr_bytes)
```

```json
{
  "name": "blk_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583031136,
      "name": "blk_update_request",
      "external": true,
      "loc": "block/blk-core.c:2539",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583031136,
      "name": "blk_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 759
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
bool blk_update_request(struct request * req, int error, unsigned int nr_bytes)
```

```json
{
  "name": "blk_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583135904,
      "name": "blk_update_request",
      "external": true,
      "loc": "block/blk-core.c:2528",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583135904,
      "name": "blk_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 852
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
bool blk_update_request(struct request * req, blk_status_t error, unsigned int nr_bytes)
```

```json
{
  "name": "blk_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583192800,
      "name": "blk_update_request",
      "external": true,
      "loc": "block/blk-core.c:2708",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583192800,
      "name": "blk_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 717
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
bool blk_update_request(struct request * req, blk_status_t error, unsigned int nr_bytes)
```

```json
{
  "name": "blk_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583369344,
      "name": "blk_update_request",
      "external": true,
      "loc": "block/blk-core.c:2932",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583369344,
      "name": "blk_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
bool blk_update_request(struct request * req, blk_status_t error, unsigned int nr_bytes)
```

```json
{
  "name": "blk_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_update_request",
      "external": true,
      "loc": "block/blk-core.c:3076",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583586153,
      "name": "blk_update_request.cold.101",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071583579024,
      "name": "blk_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 601
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
bool blk_update_request(struct request * req, blk_status_t error, unsigned int nr_bytes)
```

```json
{
  "name": "blk_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_update_request",
      "external": true,
      "loc": "block/blk-core.c:1432",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583694812,
      "name": "blk_update_request.cold.65",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071583691088,
      "name": "blk_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 601
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
bool blk_update_request(struct request * req, blk_status_t error, unsigned int nr_bytes)
```

```json
{
  "name": "blk_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_update_request",
      "external": true,
      "loc": "block/blk-core.c:1398",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583883306,
      "name": "blk_update_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071583879728,
      "name": "blk_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 630
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
bool blk_update_request(struct request * req, blk_status_t error, unsigned int nr_bytes)
```

```json
{
  "name": "blk_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_update_request",
      "external": true,
      "loc": "block/blk-core.c:1433",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583986506,
      "name": "blk_update_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071583982784,
      "name": "blk_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
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
bool blk_update_request(struct request * req, blk_status_t error, unsigned int nr_bytes)
```

```json
{
  "name": "blk_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_update_request",
      "external": true,
      "loc": "block/blk-core.c:1538",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584375598,
      "name": "blk_update_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071584364368,
      "name": "blk_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 909
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
bool blk_update_request(struct request * req, blk_status_t error, unsigned int nr_bytes)
```

```json
{
  "name": "blk_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_update_request",
      "external": true,
      "loc": "block/blk-core.c:1430",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591372421,
      "name": "blk_update_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071584482864,
      "name": "blk_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 878
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
bool blk_update_request(struct request * req, blk_status_t error, unsigned int nr_bytes)
```

```json
{
  "name": "blk_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_update_request",
      "external": true,
      "loc": "block/blk-core.c:1422",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591314871,
      "name": "blk_update_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071584517264,
      "name": "blk_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 917
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
bool blk_update_request(struct request * req, blk_status_t error, unsigned int nr_bytes)
```

```json
{
  "name": "blk_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_update_request",
      "external": true,
      "loc": "block/blk-core.c:1408",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592312991,
      "name": "blk_update_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071584927520,
      "name": "blk_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1232
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
bool blk_update_request(struct request * req, blk_status_t error, unsigned int nr_bytes)
```

```json
{
  "name": "blk_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_update_request",
      "external": true,
      "loc": "block/blk-mq.c:783",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594097351,
      "name": "blk_update_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071585689024,
      "name": "blk_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1112
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
bool blk_update_request(struct request * req, blk_status_t error, unsigned int nr_bytes)
```

```json
{
  "name": "blk_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586466464,
      "name": "blk_update_request",
      "external": true,
      "loc": "block/blk-mq.c:892",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586466464,
      "name": "blk_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1231
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
bool blk_update_request(struct request * req, blk_status_t error, unsigned int nr_bytes)
```

```json
{
  "name": "blk_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586711744,
      "name": "blk_update_request",
      "external": true,
      "loc": "block/blk-mq.c:885",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_end_request",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586711744,
      "name": "blk_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1333
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
bool blk_update_request(struct request * req, blk_status_t error, unsigned int nr_bytes)
```

```json
{
  "name": "blk_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586983552,
      "name": "blk_update_request",
      "external": true,
      "loc": "block/blk-mq.c:895",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_end_request",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586983552,
      "name": "blk_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1331
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
bool blk_update_request(struct request * req, blk_status_t error, unsigned int nr_bytes)
```

```json
{
  "name": "blk_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495807368,
      "name": "blk_update_request",
      "external": true,
      "loc": "block/blk-core.c:1433",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/md/dm-rq.c:end_clone_bio",
        "drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery",
        "drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery",
        "drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495807368,
      "name": "blk_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 968
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
bool blk_update_request(struct request * req, blk_status_t error, unsigned int nr_bytes)
```

```json
{
  "name": "blk_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229158976,
      "name": "blk_update_request",
      "external": true,
      "loc": "block/blk-core.c:1433",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/mtd/mtd_blkdevs.c:mtd_blktrans_work",
        "drivers/md/dm-rq.c:end_clone_bio",
        "drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery",
        "drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery",
        "drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229158976,
      "name": "blk_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1004
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
bool blk_update_request(struct request * req, blk_status_t error, unsigned int nr_bytes)
```

```json
{
  "name": "blk_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289992880,
      "name": "blk_update_request",
      "external": true,
      "loc": "block/blk-core.c:1433",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289992880,
      "name": "blk_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1368
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
bool blk_update_request(struct request * req, blk_status_t error, unsigned int nr_bytes)
```

```json
{
  "name": "blk_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274945396,
      "name": "blk_update_request",
      "external": true,
      "loc": "block/blk-core.c:1433",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/md/dm-rq.c:end_clone_bio",
        "drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery",
        "drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery",
        "drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274945396,
      "name": "blk_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 848
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
bool blk_update_request(struct request * req, blk_status_t error, unsigned int nr_bytes)
```

```json
{
  "name": "blk_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_update_request",
      "external": true,
      "loc": "block/blk-core.c:1433",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583955242,
      "name": "blk_update_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071583951520,
      "name": "blk_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
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
bool blk_update_request(struct request * req, blk_status_t error, unsigned int nr_bytes)
```

```json
{
  "name": "blk_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_update_request",
      "external": true,
      "loc": "block/blk-core.c:1433",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583892170,
      "name": "blk_update_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071583888448,
      "name": "blk_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
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
bool blk_update_request(struct request * req, blk_status_t error, unsigned int nr_bytes)
```

```json
{
  "name": "blk_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_update_request",
      "external": true,
      "loc": "block/blk-core.c:1433",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583939002,
      "name": "blk_update_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071583935280,
      "name": "blk_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
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
bool blk_update_request(struct request * req, blk_status_t error, unsigned int nr_bytes)
```

```json
{
  "name": "blk_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_update_request",
      "external": true,
      "loc": "block/blk-core.c:1433",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584041007,
      "name": "blk_update_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071584037040,
      "name": "blk_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 741
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int error</code> ➡️ <code>blk_status_t error</code>
</li>
</ul>
</details>
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
