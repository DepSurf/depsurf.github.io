# Function: <code>percpu_ref_resurrect</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void percpu_ref_resurrect(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_resurrect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583958240,
      "name": "percpu_ref_resurrect",
      "external": true,
      "loc": "lib/percpu-refcount.c:379",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583958240,
      "name": "percpu_ref_resurrect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void percpu_ref_resurrect(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_resurrect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584138368,
      "name": "percpu_ref_resurrect",
      "external": true,
      "loc": "lib/percpu-refcount.c:389",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_unfreeze_queue",
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584138368,
      "name": "percpu_ref_resurrect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void percpu_ref_resurrect(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_resurrect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584260816,
      "name": "percpu_ref_resurrect",
      "external": true,
      "loc": "lib/percpu-refcount.c:389",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_unfreeze_queue",
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584260816,
      "name": "percpu_ref_resurrect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void percpu_ref_resurrect(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_resurrect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584668144,
      "name": "percpu_ref_resurrect",
      "external": true,
      "loc": "lib/percpu-refcount.c:390",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register",
        "block/blk-mq.c:blk_mq_unfreeze_queue",
        "lib/percpu-refcount.c:percpu_ref_reinit",
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584668144,
      "name": "percpu_ref_resurrect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void percpu_ref_resurrect(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_resurrect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584786032,
      "name": "percpu_ref_resurrect",
      "external": true,
      "loc": "lib/percpu-refcount.c:455",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_sqe_files_unregister",
        "block/blk-mq.c:blk_mq_unfreeze_queue",
        "lib/percpu-refcount.c:percpu_ref_reinit",
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584786032,
      "name": "percpu_ref_resurrect",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void percpu_ref_resurrect(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_resurrect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584830096,
      "name": "percpu_ref_resurrect",
      "external": true,
      "loc": "lib/percpu-refcount.c:461",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:__io_uring_register",
        "block/blk-mq.c:blk_mq_unfreeze_queue",
        "lib/percpu-refcount.c:percpu_ref_reinit",
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584830096,
      "name": "percpu_ref_resurrect",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void percpu_ref_resurrect(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_resurrect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585248816,
      "name": "percpu_ref_resurrect",
      "external": true,
      "loc": "lib/percpu-refcount.c:461",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:enable_swap_info",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:__io_uring_register",
        "lib/percpu-refcount.c:percpu_ref_reinit",
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585248816,
      "name": "percpu_ref_resurrect",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void percpu_ref_resurrect(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_resurrect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586090560,
      "name": "percpu_ref_resurrect",
      "external": true,
      "loc": "lib/percpu-refcount.c:462",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586090560,
      "name": "percpu_ref_resurrect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void percpu_ref_resurrect(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_resurrect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587073792,
      "name": "percpu_ref_resurrect",
      "external": true,
      "loc": "lib/percpu-refcount.c:463",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587073792,
      "name": "percpu_ref_resurrect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void percpu_ref_resurrect(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_resurrect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587332368,
      "name": "percpu_ref_resurrect",
      "external": true,
      "loc": "lib/percpu-refcount.c:463",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587332368,
      "name": "percpu_ref_resurrect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void percpu_ref_resurrect(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_resurrect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587615760,
      "name": "percpu_ref_resurrect",
      "external": true,
      "loc": "lib/percpu-refcount.c:463",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "lib/percpu-refcount.c:percpu_ref_reinit",
        "drivers/md/md.c:__mddev_resume",
        "drivers/md/md.c:mddev_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587615760,
      "name": "percpu_ref_resurrect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void percpu_ref_resurrect(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_resurrect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496141784,
      "name": "percpu_ref_resurrect",
      "external": true,
      "loc": "lib/percpu-refcount.c:389",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_unfreeze_queue",
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496141784,
      "name": "percpu_ref_resurrect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void percpu_ref_resurrect(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_resurrect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229463628,
      "name": "percpu_ref_resurrect",
      "external": true,
      "loc": "lib/percpu-refcount.c:389",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_unfreeze_queue",
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229463628,
      "name": "percpu_ref_resurrect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void percpu_ref_resurrect(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_resurrect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290400080,
      "name": "percpu_ref_resurrect",
      "external": true,
      "loc": "lib/percpu-refcount.c:389",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_unfreeze_queue",
        "lib/percpu-refcount.c:percpu_ref_reinit",
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290400080,
      "name": "percpu_ref_resurrect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void percpu_ref_resurrect(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_resurrect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275197456,
      "name": "percpu_ref_resurrect",
      "external": true,
      "loc": "lib/percpu-refcount.c:389",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_unfreeze_queue",
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275197456,
      "name": "percpu_ref_resurrect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void percpu_ref_resurrect(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_resurrect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584229552,
      "name": "percpu_ref_resurrect",
      "external": true,
      "loc": "lib/percpu-refcount.c:389",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_unfreeze_queue",
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584229552,
      "name": "percpu_ref_resurrect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void percpu_ref_resurrect(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_resurrect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584164752,
      "name": "percpu_ref_resurrect",
      "external": true,
      "loc": "lib/percpu-refcount.c:389",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_unfreeze_queue",
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584164752,
      "name": "percpu_ref_resurrect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void percpu_ref_resurrect(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_resurrect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584213312,
      "name": "percpu_ref_resurrect",
      "external": true,
      "loc": "lib/percpu-refcount.c:389",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_unfreeze_queue",
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584213312,
      "name": "percpu_ref_resurrect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void percpu_ref_resurrect(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_resurrect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584317920,
      "name": "percpu_ref_resurrect",
      "external": true,
      "loc": "lib/percpu-refcount.c:389",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_unfreeze_queue",
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584317920,
      "name": "percpu_ref_resurrect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void percpu_ref_resurrect(struct percpu_ref * ref)
```
</details>
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
