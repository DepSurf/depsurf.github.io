# Function: <code>blk_flush_plug_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void blk_flush_plug_list(struct blk_plug * plug, bool from_schedule)
```

```json
{
  "name": "blk_flush_plug_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582758192,
      "name": "blk_flush_plug_list",
      "external": true,
      "loc": "block/blk-core.c:3247",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/core.c:schedule",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:blk_poll",
        "block/blk-mq.c:blk_sq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582758192,
      "name": "blk_flush_plug_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 570
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
void blk_flush_plug_list(struct blk_plug * plug, bool from_schedule)
```

```json
{
  "name": "blk_flush_plug_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583036208,
      "name": "blk_flush_plug_list",
      "external": true,
      "loc": "block/blk-core.c:3219",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/core.c:schedule",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-mq.c:blk_sq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583036208,
      "name": "blk_flush_plug_list",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void blk_flush_plug_list(struct blk_plug * plug, bool from_schedule)
```

```json
{
  "name": "blk_flush_plug_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583141200,
      "name": "blk_flush_plug_list",
      "external": true,
      "loc": "block/blk-core.c:3219",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/core.c:schedule",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-mq.c:blk_sq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583141200,
      "name": "blk_flush_plug_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
void blk_flush_plug_list(struct blk_plug * plug, bool from_schedule)
```

```json
{
  "name": "blk_flush_plug_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583198304,
      "name": "blk_flush_plug_list",
      "external": true,
      "loc": "block/blk-core.c:3324",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule_prepare",
        "kernel/sched/core.c:schedule",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583198304,
      "name": "blk_flush_plug_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 610
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
void blk_flush_plug_list(struct blk_plug * plug, bool from_schedule)
```

```json
{
  "name": "blk_flush_plug_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583374448,
      "name": "blk_flush_plug_list",
      "external": true,
      "loc": "block/blk-core.c:3548",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule_prepare",
        "kernel/sched/core.c:schedule",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583374448,
      "name": "blk_flush_plug_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 613
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
void blk_flush_plug_list(struct blk_plug * plug, bool from_schedule)
```

```json
{
  "name": "blk_flush_plug_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583583952,
      "name": "blk_flush_plug_list",
      "external": true,
      "loc": "block/blk-core.c:3685",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule_prepare",
        "kernel/sched/core.c:schedule",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583583952,
      "name": "blk_flush_plug_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 551
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
void blk_flush_plug_list(struct blk_plug * plug, bool from_schedule)
```

```json
{
  "name": "blk_flush_plug_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583694192,
      "name": "blk_flush_plug_list",
      "external": true,
      "loc": "block/blk-core.c:1772",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule_prepare",
        "kernel/sched/core.c:schedule",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583694192,
      "name": "blk_flush_plug_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
void blk_flush_plug_list(struct blk_plug * plug, bool from_schedule)
```

```json
{
  "name": "blk_flush_plug_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583882688,
      "name": "blk_flush_plug_list",
      "external": true,
      "loc": "block/blk-core.c:1723",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule_prepare",
        "kernel/sched/core.c:schedule",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583882688,
      "name": "blk_flush_plug_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
void blk_flush_plug_list(struct blk_plug * plug, bool from_schedule)
```

```json
{
  "name": "blk_flush_plug_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583985888,
      "name": "blk_flush_plug_list",
      "external": true,
      "loc": "block/blk-core.c:1764",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule_prepare",
        "kernel/sched/core.c:schedule",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583985888,
      "name": "blk_flush_plug_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
void blk_flush_plug_list(struct blk_plug * plug, bool from_schedule)
```

```json
{
  "name": "blk_flush_plug_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584374880,
      "name": "blk_flush_plug_list",
      "external": true,
      "loc": "block/blk-core.c:1855",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/core.c:schedule",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584374880,
      "name": "blk_flush_plug_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
void blk_flush_plug_list(struct blk_plug * plug, bool from_schedule)
```

```json
{
  "name": "blk_flush_plug_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584489104,
      "name": "blk_flush_plug_list",
      "external": true,
      "loc": "block/blk-core.c:1750",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/core.c:schedule",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "block/blk-mq.c:blk_mq_submit_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584489104,
      "name": "blk_flush_plug_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
void blk_flush_plug_list(struct blk_plug * plug, bool from_schedule)
```

```json
{
  "name": "blk_flush_plug_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584523760,
      "name": "blk_flush_plug_list",
      "external": true,
      "loc": "block/blk-core.c:1742",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/core.c:schedule",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "block/blk-mq.c:blk_mq_submit_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584523760,
      "name": "blk_flush_plug_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
void blk_flush_plug_list(struct blk_plug * plug, bool from_schedule)
```

```json
{
  "name": "blk_flush_plug_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584934640,
      "name": "blk_flush_plug_list",
      "external": true,
      "loc": "block/blk-core.c:1728",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/core.c:schedule",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "block/blk-mq.c:blk_mq_submit_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584934640,
      "name": "blk_flush_plug_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
    }
  ]
}
```
</details>
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
void blk_flush_plug_list(struct blk_plug * plug, bool from_schedule)
```

```json
{
  "name": "blk_flush_plug_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495811272,
      "name": "blk_flush_plug_list",
      "external": true,
      "loc": "block/blk-core.c:1764",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule_prepare",
        "kernel/sched/core.c:schedule",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495811272,
      "name": "blk_flush_plug_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void blk_flush_plug_list(struct blk_plug * plug, bool from_schedule)
```

```json
{
  "name": "blk_flush_plug_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229162732,
      "name": "blk_flush_plug_list",
      "external": true,
      "loc": "block/blk-core.c:1764",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule_prepare",
        "kernel/sched/core.c:schedule",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229162732,
      "name": "blk_flush_plug_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void blk_flush_plug_list(struct blk_plug * plug, bool from_schedule)
```

```json
{
  "name": "blk_flush_plug_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289997888,
      "name": "blk_flush_plug_list",
      "external": true,
      "loc": "block/blk-core.c:1764",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule_prepare",
        "kernel/sched/core.c:schedule",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289997888,
      "name": "blk_flush_plug_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
void blk_flush_plug_list(struct blk_plug * plug, bool from_schedule)
```

```json
{
  "name": "blk_flush_plug_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274948494,
      "name": "blk_flush_plug_list",
      "external": true,
      "loc": "block/blk-core.c:1764",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule_prepare",
        "kernel/sched/core.c:schedule",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274948494,
      "name": "blk_flush_plug_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void blk_flush_plug_list(struct blk_plug * plug, bool from_schedule)
```

```json
{
  "name": "blk_flush_plug_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583954624,
      "name": "blk_flush_plug_list",
      "external": true,
      "loc": "block/blk-core.c:1764",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule_prepare",
        "kernel/sched/core.c:schedule",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583954624,
      "name": "blk_flush_plug_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
void blk_flush_plug_list(struct blk_plug * plug, bool from_schedule)
```

```json
{
  "name": "blk_flush_plug_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583891552,
      "name": "blk_flush_plug_list",
      "external": true,
      "loc": "block/blk-core.c:1764",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule_prepare",
        "kernel/sched/core.c:schedule",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583891552,
      "name": "blk_flush_plug_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
void blk_flush_plug_list(struct blk_plug * plug, bool from_schedule)
```

```json
{
  "name": "blk_flush_plug_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583938384,
      "name": "blk_flush_plug_list",
      "external": true,
      "loc": "block/blk-core.c:1764",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule_prepare",
        "kernel/sched/core.c:schedule",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583938384,
      "name": "blk_flush_plug_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
void blk_flush_plug_list(struct blk_plug * plug, bool from_schedule)
```

```json
{
  "name": "blk_flush_plug_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584040384,
      "name": "blk_flush_plug_list",
      "external": true,
      "loc": "block/blk-core.c:1764",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule_prepare",
        "kernel/sched/core.c:schedule",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584040384,
      "name": "blk_flush_plug_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void blk_flush_plug_list(struct blk_plug * plug, bool from_schedule)
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
