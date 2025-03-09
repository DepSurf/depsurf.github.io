# Function: <code>__blk_flush_plug</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void __blk_flush_plug(struct blk_plug * plug, bool from_schedule)
```

```json
{
  "name": "__blk_flush_plug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585635712,
      "name": "__blk_flush_plug",
      "external": true,
      "loc": "block/blk-core.c:1201",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/core.c:schedule",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "block/blk-core.c:bio_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585635712,
      "name": "__blk_flush_plug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void __blk_flush_plug(struct blk_plug * plug, bool from_schedule)
```

```json
{
  "name": "__blk_flush_plug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586406928,
      "name": "__blk_flush_plug",
      "external": true,
      "loc": "block/blk-core.c:1139",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/core.c:schedule",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "block/blk-core.c:bio_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586406928,
      "name": "__blk_flush_plug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void __blk_flush_plug(struct blk_plug * plug, bool from_schedule)
```

```json
{
  "name": "__blk_flush_plug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586654320,
      "name": "__blk_flush_plug",
      "external": true,
      "loc": "block/blk-core.c:1137",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/core.c:schedule",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "block/blk-core.c:bio_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586654320,
      "name": "__blk_flush_plug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
void __blk_flush_plug(struct blk_plug * plug, bool from_schedule)
```

```json
{
  "name": "__blk_flush_plug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586925584,
      "name": "__blk_flush_plug",
      "external": true,
      "loc": "block/blk-core.c:1172",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:io_schedule",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/core.c:rt_mutex_pre_schedule",
        "kernel/sched/core.c:schedule",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "block/blk-core.c:bio_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586925584,
      "name": "__blk_flush_plug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void __blk_flush_plug(struct blk_plug * plug, bool from_schedule)
```
</details>
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
