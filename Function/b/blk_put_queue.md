# Function: <code>blk_put_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_put_queue(struct request_queue * q)
```

```json
{
  "name": "blk_put_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582734240,
      "name": "blk_put_queue",
      "external": true,
      "loc": "block/blk-core.c:379",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue"
      ],
      "caller_func": [
        "block/genhd.c:disk_release",
        "block/bsg.c:bsg_open",
        "block/bsg.c:bsg_release",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582734240,
      "name": "blk_put_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void blk_put_queue(struct request_queue * q)
```

```json
{
  "name": "blk_put_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583025889,
      "name": "blk_put_queue",
      "external": true,
      "loc": "block/blk-core.c:379",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue"
      ],
      "caller_func": [
        "block/genhd.c:disk_release",
        "block/bsg.c:bsg_release",
        "block/bsg.c:bsg_open",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583016464,
      "name": "blk_put_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void blk_put_queue(struct request_queue * q)
```

```json
{
  "name": "blk_put_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583130753,
      "name": "blk_put_queue",
      "external": true,
      "loc": "block/blk-core.c:380",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue"
      ],
      "caller_func": [
        "block/genhd.c:disk_release",
        "block/bsg.c:bsg_release",
        "block/bsg.c:bsg_open",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583121296,
      "name": "blk_put_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void blk_put_queue(struct request_queue * q)
```

```json
{
  "name": "blk_put_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583190541,
      "name": "blk_put_queue",
      "external": true,
      "loc": "block/blk-core.c:443",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_exit_rl",
        "block/blk-core.c:blk_cleanup_queue"
      ],
      "caller_func": [
        "block/genhd.c:disk_release",
        "block/bsg.c:bsg_release",
        "block/bsg.c:bsg_open",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583177088,
      "name": "blk_put_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void blk_put_queue(struct request_queue * q)
```

```json
{
  "name": "blk_put_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583366285,
      "name": "blk_put_queue",
      "external": true,
      "loc": "block/blk-core.c:476",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_exit_rl",
        "block/blk-core.c:blk_cleanup_queue"
      ],
      "caller_func": [
        "block/genhd.c:disk_release",
        "block/bsg.c:bsg_release",
        "block/bsg.c:bsg_open",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583352000,
      "name": "blk_put_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void blk_put_queue(struct request_queue * q)
```

```json
{
  "name": "blk_put_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583575741,
      "name": "blk_put_queue",
      "external": true,
      "loc": "block/blk-core.c:537",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_exit_rl",
        "block/blk-core.c:blk_cleanup_queue"
      ],
      "caller_func": [
        "block/genhd.c:disk_release",
        "block/bsg.c:bsg_release",
        "block/bsg.c:bsg_open",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583561568,
      "name": "blk_put_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_put_queue(struct request_queue * q)
```

```json
{
  "name": "blk_put_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583688717,
      "name": "blk_put_queue",
      "external": true,
      "loc": "block/blk-core.c:268",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue"
      ],
      "caller_func": [
        "block/genhd.c:disk_release",
        "block/bsg.c:bsg_release",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_exit",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583681600,
      "name": "blk_put_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_put_queue(struct request_queue * q)
```

```json
{
  "name": "blk_put_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583872537,
      "name": "blk_put_queue",
      "external": true,
      "loc": "block/blk-core.c:302",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue"
      ],
      "caller_func": [
        "block/genhd.c:disk_release",
        "block/bsg.c:bsg_release",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_exit",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583870416,
      "name": "blk_put_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_put_queue(struct request_queue * q)
```

```json
{
  "name": "blk_put_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583975433,
      "name": "blk_put_queue",
      "external": true,
      "loc": "block/blk-core.c:305",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue"
      ],
      "caller_func": [
        "block/genhd.c:disk_release",
        "block/bsg.c:bsg_release",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_exit",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583973296,
      "name": "blk_put_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_put_queue(struct request_queue * q)
```

```json
{
  "name": "blk_put_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584362883,
      "name": "blk_put_queue",
      "external": true,
      "loc": "block/blk-core.c:324",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue"
      ],
      "caller_func": [
        "block/genhd.c:disk_release",
        "block/bsg.c:bsg_put_device",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_exit",
        "drivers/scsi/scsi_lib.c:scsi_starved_list_run",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584360896,
      "name": "blk_put_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_put_queue(struct request_queue * q)
```

```json
{
  "name": "blk_put_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584479701,
      "name": "blk_put_queue",
      "external": true,
      "loc": "block/blk-core.c:337",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue"
      ],
      "caller_func": [
        "fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "block/genhd.c:disk_release",
        "block/bsg.c:bsg_put_device",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_exit",
        "drivers/scsi/scsi_lib.c:scsi_starved_list_run",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584477280,
      "name": "blk_put_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_put_queue(struct request_queue * q)
```

```json
{
  "name": "blk_put_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584514325,
      "name": "blk_put_queue",
      "external": true,
      "loc": "block/blk-core.c:338",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue"
      ],
      "caller_func": [
        "fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "block/genhd.c:disk_release",
        "block/bsg.c:bsg_release",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_exit",
        "drivers/scsi/scsi_lib.c:scsi_starved_list_run",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584512208,
      "name": "blk_put_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_put_queue(struct request_queue * q)
```

```json
{
  "name": "blk_put_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584927481,
      "name": "blk_put_queue",
      "external": true,
      "loc": "block/blk-core.c:333",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue"
      ],
      "caller_func": [
        "fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "block/genhd.c:__alloc_disk_node",
        "block/genhd.c:disk_release",
        "block/bsg.c:bsg_release",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_exit",
        "drivers/scsi/scsi_lib.c:scsi_starved_list_run",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584924096,
      "name": "blk_put_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_put_queue(struct request_queue * q)
```

```json
{
  "name": "blk_put_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585629608,
      "name": "blk_put_queue",
      "external": true,
      "loc": "block/blk-core.c:267",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue"
      ],
      "caller_func": [
        "fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "block/genhd.c:__alloc_disk_node",
        "block/genhd.c:disk_release",
        "block/bsg.c:bsg_release",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_exit",
        "block/blk-cgroup.c:blkg_free_workfn",
        "drivers/scsi/scsi_lib.c:scsi_starved_list_run",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585628608,
      "name": "blk_put_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void blk_put_queue(struct request_queue * q)
```

```json
{
  "name": "blk_put_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586399968,
      "name": "blk_put_queue",
      "external": true,
      "loc": "block/blk-core.c:287",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_disk_for_queue",
        "block/blk-mq.c:__blk_mq_alloc_disk",
        "block/blk-mq.c:__blk_mq_alloc_disk",
        "block/blk-mq.c:blk_mq_init_queue",
        "block/genhd.c:__blk_alloc_disk",
        "block/genhd.c:disk_release",
        "block/bsg.c:bsg_release",
        "block/bsg-lib.c:bsg_setup_queue",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_exit",
        "block/blk-cgroup.c:blkg_free_workfn",
        "drivers/scsi/scsi_lib.c:scsi_starved_list_run",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586399968,
      "name": "blk_put_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void blk_put_queue(struct request_queue * q)
```

```json
{
  "name": "blk_put_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586646864,
      "name": "blk_put_queue",
      "external": true,
      "loc": "block/blk-core.c:284",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_disk_for_queue",
        "block/blk-mq.c:__blk_mq_alloc_disk",
        "block/blk-mq.c:__blk_mq_alloc_disk",
        "block/blk-mq.c:blk_mq_init_queue",
        "block/genhd.c:__blk_alloc_disk",
        "block/genhd.c:disk_release",
        "block/bsg.c:bsg_release",
        "block/bsg-lib.c:bsg_setup_queue",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_free_workfn",
        "drivers/scsi/scsi_lib.c:scsi_starved_list_run",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586646864,
      "name": "blk_put_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void blk_put_queue(struct request_queue * q)
```

```json
{
  "name": "blk_put_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586917824,
      "name": "blk_put_queue",
      "external": true,
      "loc": "block/blk-core.c:286",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_disk_for_queue",
        "block/blk-mq.c:__blk_mq_alloc_disk",
        "block/blk-mq.c:__blk_mq_alloc_disk",
        "block/blk-mq.c:blk_mq_init_queue",
        "block/genhd.c:__blk_alloc_disk",
        "block/genhd.c:disk_release",
        "block/bsg.c:bsg_release",
        "block/bsg-lib.c:bsg_setup_queue",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_free_workfn",
        "drivers/scsi/scsi_lib.c:scsi_starved_list_run",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586917824,
      "name": "blk_put_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void blk_put_queue(struct request_queue * q)
```

```json
{
  "name": "blk_put_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495796120,
      "name": "blk_put_queue",
      "external": true,
      "loc": "block/blk-core.c:305",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue"
      ],
      "caller_func": [
        "block/genhd.c:disk_release",
        "block/bsg.c:bsg_release",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_exit",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/mmc/core/block.c:mmc_blk_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495792600,
      "name": "blk_put_queue",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void blk_put_queue(struct request_queue * q)
```

```json
{
  "name": "blk_put_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229148284,
      "name": "blk_put_queue",
      "external": true,
      "loc": "block/blk-core.c:305",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue"
      ],
      "caller_func": [
        "block/genhd.c:disk_release",
        "block/bsg.c:bsg_release",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_exit",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/mmc/core/block.c:mmc_blk_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229147940,
      "name": "blk_put_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void blk_put_queue(struct request_queue * q)
```

```json
{
  "name": "blk_put_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289979760,
      "name": "blk_put_queue",
      "external": true,
      "loc": "block/blk-core.c:305",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue"
      ],
      "caller_func": [
        "block/genhd.c:disk_release",
        "block/bsg.c:bsg_release",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_exit",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289979232,
      "name": "blk_put_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void blk_put_queue(struct request_queue * q)
```

```json
{
  "name": "blk_put_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274937638,
      "name": "blk_put_queue",
      "external": true,
      "loc": "block/blk-core.c:305",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue"
      ],
      "caller_func": [
        "block/genhd.c:disk_release",
        "block/bsg.c:bsg_release",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_exit",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/mmc/core/block.c:mmc_blk_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274937292,
      "name": "blk_put_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void blk_put_queue(struct request_queue * q)
```

```json
{
  "name": "blk_put_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583944169,
      "name": "blk_put_queue",
      "external": true,
      "loc": "block/blk-core.c:305",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue"
      ],
      "caller_func": [
        "block/genhd.c:disk_release",
        "block/bsg.c:bsg_release",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_exit",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/nvme/host/pci.c:nvme_pci_free_ctrl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583942032,
      "name": "blk_put_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void blk_put_queue(struct request_queue * q)
```

```json
{
  "name": "blk_put_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583881113,
      "name": "blk_put_queue",
      "external": true,
      "loc": "block/blk-core.c:305",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue"
      ],
      "caller_func": [
        "block/genhd.c:disk_release",
        "block/bsg.c:bsg_release",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_exit",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/nvme/host/pci.c:nvme_pci_free_ctrl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583878976,
      "name": "blk_put_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void blk_put_queue(struct request_queue * q)
```

```json
{
  "name": "blk_put_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583927929,
      "name": "blk_put_queue",
      "external": true,
      "loc": "block/blk-core.c:305",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue"
      ],
      "caller_func": [
        "block/genhd.c:disk_release",
        "block/bsg.c:bsg_release",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_exit",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583925792,
      "name": "blk_put_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void blk_put_queue(struct request_queue * q)
```

```json
{
  "name": "blk_put_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584029321,
      "name": "blk_put_queue",
      "external": true,
      "loc": "block/blk-core.c:305",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue"
      ],
      "caller_func": [
        "block/genhd.c:disk_release",
        "block/bsg.c:bsg_release",
        "block/bsg.c:bsg_open",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_exit",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584027184,
      "name": "blk_put_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
