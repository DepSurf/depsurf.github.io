# Function: <code>blk_get_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool blk_get_queue(struct request_queue * q)
```

```json
{
  "name": "blk_get_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582735072,
      "name": "blk_get_queue",
      "external": true,
      "loc": "block/blk-core.c:879",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:add_disk",
        "block/bsg.c:bsg_open",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582735072,
      "name": "blk_get_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
bool blk_get_queue(struct request_queue * q)
```

```json
{
  "name": "blk_get_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583017296,
      "name": "blk_get_queue",
      "external": true,
      "loc": "block/blk-core.c:889",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:device_add_disk",
        "block/bsg.c:bsg_open",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583017296,
      "name": "blk_get_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
bool blk_get_queue(struct request_queue * q)
```

```json
{
  "name": "blk_get_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583122128,
      "name": "blk_get_queue",
      "external": true,
      "loc": "block/blk-core.c:891",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:device_add_disk",
        "block/bsg.c:bsg_open",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583122128,
      "name": "blk_get_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
bool blk_get_queue(struct request_queue * q)
```

```json
{
  "name": "blk_get_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583189943,
      "name": "blk_get_queue",
      "external": true,
      "loc": "block/blk-core.c:1015",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_init_rl"
      ],
      "caller_func": [
        "block/genhd.c:device_add_disk",
        "block/bsg.c:bsg_open",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583178144,
      "name": "blk_get_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
bool blk_get_queue(struct request_queue * q)
```

```json
{
  "name": "blk_get_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583353040,
      "name": "blk_get_queue",
      "external": true,
      "loc": "block/blk-core.c:1093",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:device_add_disk",
        "block/bsg.c:bsg_open",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583353040,
      "name": "blk_get_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool blk_get_queue(struct request_queue * q)
```

```json
{
  "name": "blk_get_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583562720,
      "name": "blk_get_queue",
      "external": true,
      "loc": "block/blk-core.c:1198",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:__device_add_disk",
        "block/bsg.c:bsg_open",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583562720,
      "name": "blk_get_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
bool blk_get_queue(struct request_queue * q)
```

```json
{
  "name": "blk_get_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583682352,
      "name": "blk_get_queue",
      "external": true,
      "loc": "block/blk-core.c:558",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:__device_add_disk",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583682352,
      "name": "blk_get_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
bool blk_get_queue(struct request_queue * q)
```

```json
{
  "name": "blk_get_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583871168,
      "name": "blk_get_queue",
      "external": true,
      "loc": "block/blk-core.c:556",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:__device_add_disk",
        "block/genhd.c:__device_add_disk",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583871168,
      "name": "blk_get_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
bool blk_get_queue(struct request_queue * q)
```

```json
{
  "name": "blk_get_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583974064,
      "name": "blk_get_queue",
      "external": true,
      "loc": "block/blk-core.c:560",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:__device_add_disk",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583974064,
      "name": "blk_get_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
bool blk_get_queue(struct request_queue * q)
```

```json
{
  "name": "blk_get_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584360928,
      "name": "blk_get_queue",
      "external": true,
      "loc": "block/blk-core.c:602",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:__device_add_disk",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "drivers/scsi/scsi_lib.c:scsi_starved_list_run",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584360928,
      "name": "blk_get_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
bool blk_get_queue(struct request_queue * q)
```

```json
{
  "name": "blk_get_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584478016,
      "name": "blk_get_queue",
      "external": true,
      "loc": "block/blk-core.c:611",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "block/genhd.c:__device_add_disk",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "drivers/scsi/scsi_lib.c:scsi_starved_list_run",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584478016,
      "name": "blk_get_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
bool blk_get_queue(struct request_queue * q)
```

```json
{
  "name": "blk_get_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584512944,
      "name": "blk_get_queue",
      "external": true,
      "loc": "block/blk-core.c:612",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "block/genhd.c:__device_add_disk",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "drivers/scsi/scsi_lib.c:scsi_starved_list_run",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584512944,
      "name": "blk_get_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
bool blk_get_queue(struct request_queue * q)
```

```json
{
  "name": "blk_get_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584924128,
      "name": "blk_get_queue",
      "external": true,
      "loc": "block/blk-core.c:610",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "block/genhd.c:__alloc_disk_node",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "drivers/scsi/scsi_lib.c:scsi_starved_list_run",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584924128,
      "name": "blk_get_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
bool blk_get_queue(struct request_queue * q)
```

```json
{
  "name": "blk_get_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585628640,
      "name": "blk_get_queue",
      "external": true,
      "loc": "block/blk-core.c:505",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "block/genhd.c:__alloc_disk_node",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "block/blk-cgroup.c:blkg_alloc",
        "drivers/scsi/scsi_lib.c:scsi_starved_list_run",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585628640,
      "name": "blk_get_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
bool blk_get_queue(struct request_queue * q)
```

```json
{
  "name": "blk_get_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586400192,
      "name": "blk_get_queue",
      "external": true,
      "loc": "block/blk-core.c:465",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_disk_for_queue",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "block/blk-cgroup.c:blkg_alloc",
        "drivers/scsi/scsi_lib.c:scsi_starved_list_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586400192,
      "name": "blk_get_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
bool blk_get_queue(struct request_queue * q)
```

```json
{
  "name": "blk_get_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586647056,
      "name": "blk_get_queue",
      "external": true,
      "loc": "block/blk-core.c:463",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_disk_for_queue",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkg_alloc",
        "drivers/scsi/scsi_lib.c:scsi_starved_list_run",
        "drivers/scsi/sg.c:sg_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586647056,
      "name": "blk_get_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
bool blk_get_queue(struct request_queue * q)
```

```json
{
  "name": "blk_get_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586918000,
      "name": "blk_get_queue",
      "external": true,
      "loc": "block/blk-core.c:465",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_disk_for_queue",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkg_alloc",
        "drivers/scsi/scsi_lib.c:scsi_starved_list_run",
        "drivers/scsi/sg.c:sg_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586918000,
      "name": "blk_get_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
bool blk_get_queue(struct request_queue * q)
```

```json
{
  "name": "blk_get_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495793312,
      "name": "blk_get_queue",
      "external": true,
      "loc": "block/blk-core.c:560",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:__device_add_disk",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/mmc/core/block.c:mmc_blk_alloc_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495793312,
      "name": "blk_get_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
bool blk_get_queue(struct request_queue * q)
```

```json
{
  "name": "blk_get_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229148936,
      "name": "blk_get_queue",
      "external": true,
      "loc": "block/blk-core.c:560",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:__device_add_disk",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/mmc/core/block.c:mmc_blk_alloc_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229148936,
      "name": "blk_get_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
bool blk_get_queue(struct request_queue * q)
```

```json
{
  "name": "blk_get_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289980672,
      "name": "blk_get_queue",
      "external": true,
      "loc": "block/blk-core.c:560",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:__device_add_disk",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289980672,
      "name": "blk_get_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
bool blk_get_queue(struct request_queue * q)
```

```json
{
  "name": "blk_get_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274938300,
      "name": "blk_get_queue",
      "external": true,
      "loc": "block/blk-core.c:560",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:__device_add_disk",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/mmc/core/block.c:mmc_blk_alloc_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274938300,
      "name": "blk_get_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool blk_get_queue(struct request_queue * q)
```

```json
{
  "name": "blk_get_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583942800,
      "name": "blk_get_queue",
      "external": true,
      "loc": "block/blk-core.c:560",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:__device_add_disk",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/nvme/host/pci.c:nvme_reset_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583942800,
      "name": "blk_get_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
bool blk_get_queue(struct request_queue * q)
```

```json
{
  "name": "blk_get_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583879744,
      "name": "blk_get_queue",
      "external": true,
      "loc": "block/blk-core.c:560",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:__device_add_disk",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/nvme/host/pci.c:nvme_reset_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583879744,
      "name": "blk_get_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
bool blk_get_queue(struct request_queue * q)
```

```json
{
  "name": "blk_get_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583926560,
      "name": "blk_get_queue",
      "external": true,
      "loc": "block/blk-core.c:560",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:__device_add_disk",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583926560,
      "name": "blk_get_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
bool blk_get_queue(struct request_queue * q)
```

```json
{
  "name": "blk_get_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584027952,
      "name": "blk_get_queue",
      "external": true,
      "loc": "block/blk-core.c:560",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:__device_add_disk",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584027952,
      "name": "blk_get_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
