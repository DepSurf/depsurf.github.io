# Function: <code>kblockd_schedule_work</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int kblockd_schedule_work(struct work_struct * work)
```

```json
{
  "name": "kblockd_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582735504,
      "name": "kblockd_schedule_work",
      "external": true,
      "loc": "block/blk-core.c:3122",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_kick_requeue_list",
        "block/cfq-iosched.c:cfq_idle_slice_timer",
        "block/cfq-iosched.c:cfq_put_queue",
        "block/cfq-iosched.c:cfq_exit_cfqq",
        "block/cfq-iosched.c:cfq_completed_request",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582735504,
      "name": "kblockd_schedule_work",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kblockd_schedule_work(struct work_struct * work)
```

```json
{
  "name": "kblockd_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583017830,
      "name": "kblockd_schedule_work",
      "external": true,
      "loc": "block/blk-core.c:3094",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_rq_timed_out_timer"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_mq_kick_requeue_list",
        "block/cfq-iosched.c:cfq_idle_slice_timer",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_exit_cfqq",
        "block/cfq-iosched.c:cfq_put_queue",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583017776,
      "name": "kblockd_schedule_work",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kblockd_schedule_work(struct work_struct * work)
```

```json
{
  "name": "kblockd_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583122598,
      "name": "kblockd_schedule_work",
      "external": true,
      "loc": "block/blk-core.c:3088",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_rq_timed_out_timer"
      ],
      "caller_func": [
        "block/cfq-iosched.c:cfq_idle_slice_timer",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_exit_cfqq",
        "block/cfq-iosched.c:cfq_put_queue",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583122544,
      "name": "kblockd_schedule_work",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kblockd_schedule_work(struct work_struct * work)
```

```json
{
  "name": "kblockd_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583178790,
      "name": "kblockd_schedule_work",
      "external": true,
      "loc": "block/blk-core.c:3184",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_rq_timed_out_timer"
      ],
      "caller_func": [
        "block/cfq-iosched.c:cfq_idle_slice_timer",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_exit_cfqq",
        "block/cfq-iosched.c:cfq_put_queue",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583178736,
      "name": "kblockd_schedule_work",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kblockd_schedule_work(struct work_struct * work)
```

```json
{
  "name": "kblockd_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583354518,
      "name": "kblockd_schedule_work",
      "external": true,
      "loc": "block/blk-core.c:3408",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_rq_timed_out_timer"
      ],
      "caller_func": [
        "block/cfq-iosched.c:cfq_idle_slice_timer",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_exit_cfqq",
        "block/cfq-iosched.c:cfq_put_queue",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583354464,
      "name": "kblockd_schedule_work",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kblockd_schedule_work(struct work_struct * work)
```

```json
{
  "name": "kblockd_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583564037,
      "name": "kblockd_schedule_work",
      "external": true,
      "loc": "block/blk-core.c:3559",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_rq_timed_out_timer"
      ],
      "caller_func": [
        "block/cfq-iosched.c:cfq_idle_slice_timer",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_exit_cfqq",
        "block/cfq-iosched.c:cfq_put_queue",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583563984,
      "name": "kblockd_schedule_work",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kblockd_schedule_work(struct work_struct * work)
```

```json
{
  "name": "kblockd_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583682949,
      "name": "kblockd_schedule_work",
      "external": true,
      "loc": "block/blk-core.c:1665",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_rq_timed_out_timer"
      ],
      "caller_func": [
        "block/blk-timeout.c:blk_abort_request",
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583682896,
      "name": "kblockd_schedule_work",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kblockd_schedule_work(struct work_struct * work)
```

```json
{
  "name": "kblockd_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583871781,
      "name": "kblockd_schedule_work",
      "external": true,
      "loc": "block/blk-core.c:1616",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_rq_timed_out_timer"
      ],
      "caller_func": [
        "block/blk-timeout.c:blk_abort_request",
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583871728,
      "name": "kblockd_schedule_work",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kblockd_schedule_work(struct work_struct * work)
```

```json
{
  "name": "kblockd_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583974677,
      "name": "kblockd_schedule_work",
      "external": true,
      "loc": "block/blk-core.c:1657",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_rq_timed_out_timer"
      ],
      "caller_func": [
        "block/blk-timeout.c:blk_abort_request",
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583974624,
      "name": "kblockd_schedule_work",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kblockd_schedule_work(struct work_struct * work)
```

```json
{
  "name": "kblockd_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584362597,
      "name": "kblockd_schedule_work",
      "external": true,
      "loc": "block/blk-core.c:1754",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_rq_timed_out_timer"
      ],
      "caller_func": [
        "block/blk-timeout.c:blk_abort_request",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584361824,
      "name": "kblockd_schedule_work",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kblockd_schedule_work(struct work_struct * work)
```

```json
{
  "name": "kblockd_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584479413,
      "name": "kblockd_schedule_work",
      "external": true,
      "loc": "block/blk-core.c:1648",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_rq_timed_out_timer"
      ],
      "caller_func": [
        "block/blk-timeout.c:blk_abort_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584478832,
      "name": "kblockd_schedule_work",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kblockd_schedule_work(struct work_struct * work)
```

```json
{
  "name": "kblockd_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584514357,
      "name": "kblockd_schedule_work",
      "external": true,
      "loc": "block/blk-core.c:1640",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_rq_timed_out_timer"
      ],
      "caller_func": [
        "block/blk-timeout.c:blk_abort_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584513552,
      "name": "kblockd_schedule_work",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kblockd_schedule_work(struct work_struct * work)
```

```json
{
  "name": "kblockd_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584925477,
      "name": "kblockd_schedule_work",
      "external": true,
      "loc": "block/blk-core.c:1626",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_rq_timed_out_timer"
      ],
      "caller_func": [
        "block/blk-timeout.c:blk_abort_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584924768,
      "name": "kblockd_schedule_work",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kblockd_schedule_work(struct work_struct * work)
```

```json
{
  "name": "kblockd_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585629301,
      "name": "kblockd_schedule_work",
      "external": true,
      "loc": "block/blk-core.c:1091",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_rq_timed_out_timer"
      ],
      "caller_func": [
        "block/blk-timeout.c:blk_abort_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585628704,
      "name": "kblockd_schedule_work",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kblockd_schedule_work(struct work_struct * work)
```

```json
{
  "name": "kblockd_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586400597,
      "name": "kblockd_schedule_work",
      "external": true,
      "loc": "block/blk-core.c:1029",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_rq_timed_out_timer"
      ],
      "caller_func": [
        "block/blk-timeout.c:blk_abort_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586396384,
      "name": "kblockd_schedule_work",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kblockd_schedule_work(struct work_struct * work)
```

```json
{
  "name": "kblockd_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586647845,
      "name": "kblockd_schedule_work",
      "external": true,
      "loc": "block/blk-core.c:1028",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_rq_timed_out_timer"
      ],
      "caller_func": [
        "block/blk-timeout.c:blk_abort_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586643200,
      "name": "kblockd_schedule_work",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kblockd_schedule_work(struct work_struct * work)
```

```json
{
  "name": "kblockd_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586919141,
      "name": "kblockd_schedule_work",
      "external": true,
      "loc": "block/blk-core.c:1063",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_rq_timed_out_timer"
      ],
      "caller_func": [
        "block/blk-timeout.c:blk_abort_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586914160,
      "name": "kblockd_schedule_work",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int kblockd_schedule_work(struct work_struct * work)
```

```json
{
  "name": "kblockd_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495794424,
      "name": "kblockd_schedule_work",
      "external": true,
      "loc": "block/blk-core.c:1657",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_rq_timed_out_timer"
      ],
      "caller_func": [
        "block/blk-timeout.c:blk_abort_request",
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495794336,
      "name": "kblockd_schedule_work",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int kblockd_schedule_work(struct work_struct * work)
```

```json
{
  "name": "kblockd_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229150100,
      "name": "kblockd_schedule_work",
      "external": true,
      "loc": "block/blk-core.c:1657",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_rq_timed_out_timer"
      ],
      "caller_func": [
        "block/blk-timeout.c:blk_abort_request",
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229150032,
      "name": "kblockd_schedule_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int kblockd_schedule_work(struct work_struct * work)
```

```json
{
  "name": "kblockd_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289982348,
      "name": "kblockd_schedule_work",
      "external": true,
      "loc": "block/blk-core.c:1657",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_rq_timed_out_timer"
      ],
      "caller_func": [
        "block/blk-timeout.c:blk_abort_request",
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289982240,
      "name": "kblockd_schedule_work",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int kblockd_schedule_work(struct work_struct * work)
```

```json
{
  "name": "kblockd_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274938926,
      "name": "kblockd_schedule_work",
      "external": true,
      "loc": "block/blk-core.c:1657",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_rq_timed_out_timer"
      ],
      "caller_func": [
        "block/blk-timeout.c:blk_abort_request",
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274938850,
      "name": "kblockd_schedule_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int kblockd_schedule_work(struct work_struct * work)
```

```json
{
  "name": "kblockd_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583943413,
      "name": "kblockd_schedule_work",
      "external": true,
      "loc": "block/blk-core.c:1657",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_rq_timed_out_timer"
      ],
      "caller_func": [
        "block/blk-timeout.c:blk_abort_request",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/nvme/host/multipath.c:nvme_mpath_remove_disk",
        "drivers/nvme/host/multipath.c:nvme_mpath_set_live",
        "drivers/nvme/host/multipath.c:nvme_mpath_clear_ctrl_paths",
        "drivers/nvme/host/multipath.c:nvme_kick_requeue_lists",
        "drivers/nvme/host/multipath.c:nvme_failover_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583943360,
      "name": "kblockd_schedule_work",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int kblockd_schedule_work(struct work_struct * work)
```

```json
{
  "name": "kblockd_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583880357,
      "name": "kblockd_schedule_work",
      "external": true,
      "loc": "block/blk-core.c:1657",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_rq_timed_out_timer"
      ],
      "caller_func": [
        "block/blk-timeout.c:blk_abort_request",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/nvme/host/multipath.c:nvme_mpath_remove_disk",
        "drivers/nvme/host/multipath.c:nvme_mpath_set_live",
        "drivers/nvme/host/multipath.c:nvme_mpath_clear_ctrl_paths",
        "drivers/nvme/host/multipath.c:nvme_kick_requeue_lists",
        "drivers/nvme/host/multipath.c:nvme_failover_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583880304,
      "name": "kblockd_schedule_work",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int kblockd_schedule_work(struct work_struct * work)
```

```json
{
  "name": "kblockd_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583927173,
      "name": "kblockd_schedule_work",
      "external": true,
      "loc": "block/blk-core.c:1657",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_rq_timed_out_timer"
      ],
      "caller_func": [
        "block/blk-timeout.c:blk_abort_request",
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583927120,
      "name": "kblockd_schedule_work",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int kblockd_schedule_work(struct work_struct * work)
```

```json
{
  "name": "kblockd_schedule_work",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584028565,
      "name": "kblockd_schedule_work",
      "external": true,
      "loc": "block/blk-core.c:1657",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_rq_timed_out_timer"
      ],
      "caller_func": [
        "block/blk-timeout.c:blk_abort_request",
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584028512,
      "name": "kblockd_schedule_work",
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
