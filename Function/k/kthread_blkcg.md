# Function: <code>kthread_blkcg</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state * kthread_blkcg()
```

```json
{
  "name": "kthread_blkcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579549072,
      "name": "kthread_blkcg",
      "external": true,
      "loc": "kernel/kthread.c:1212",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:get_request",
        "block/blk-mq.c:blk_mq_bio_to_request",
        "block/cfq-iosched.c:cfq_set_request",
        "block/cfq-iosched.c:cfq_get_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579549072,
      "name": "kthread_blkcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct cgroup_subsys_state * kthread_blkcg()
```

```json
{
  "name": "kthread_blkcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579580048,
      "name": "kthread_blkcg",
      "external": true,
      "loc": "kernel/kthread.c:1230",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:get_request",
        "block/blk-mq.c:blk_mq_bio_to_request",
        "block/cfq-iosched.c:cfq_set_request",
        "block/cfq-iosched.c:cfq_get_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579580048,
      "name": "kthread_blkcg",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * kthread_blkcg()
```

```json
{
  "name": "kthread_blkcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579617792,
      "name": "kthread_blkcg",
      "external": true,
      "loc": "kernel/kthread.c:1232",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:mem_cgroup_throttle_swaprate",
        "block/bio.c:bio_associate_blkg",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579617792,
      "name": "kthread_blkcg",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * kthread_blkcg()
```

```json
{
  "name": "kthread_blkcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579642320,
      "name": "kthread_blkcg",
      "external": true,
      "loc": "kernel/kthread.c:1242",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:mem_cgroup_throttle_swaprate",
        "block/bio.c:bio_associate_blkg",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579642320,
      "name": "kthread_blkcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct cgroup_subsys_state * kthread_blkcg()
```

```json
{
  "name": "kthread_blkcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579663872,
      "name": "kthread_blkcg",
      "external": true,
      "loc": "kernel/kthread.c:1242",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:mem_cgroup_throttle_swaprate",
        "block/bio.c:bio_associate_blkg",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663872,
      "name": "kthread_blkcg",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * kthread_blkcg()
```

```json
{
  "name": "kthread_blkcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579699328,
      "name": "kthread_blkcg",
      "external": true,
      "loc": "kernel/kthread.c:1338",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:cgroup_throttle_swaprate",
        "block/bio.c:bio_associate_blkg",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579699328,
      "name": "kthread_blkcg",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * kthread_blkcg()
```

```json
{
  "name": "kthread_blkcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579677792,
      "name": "kthread_blkcg",
      "external": true,
      "loc": "kernel/kthread.c:1412",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:page_cache_sync_ra",
        "mm/swapfile.c:cgroup_throttle_swaprate",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_grab_identity",
        "fs/io_uring.c:io_init_identity",
        "block/blk-cgroup.c:bio_associate_blkg",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579677792,
      "name": "kthread_blkcg",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * kthread_blkcg()
```

```json
{
  "name": "kthread_blkcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579683856,
      "name": "kthread_blkcg",
      "external": true,
      "loc": "kernel/kthread.c:1470",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:page_cache_sync_ra",
        "mm/swapfile.c:cgroup_throttle_swaprate",
        "block/blk-cgroup.c:bio_associate_blkg",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683856,
      "name": "kthread_blkcg",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state * kthread_blkcg()
```

```json
{
  "name": "kthread_blkcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579760304,
      "name": "kthread_blkcg",
      "external": true,
      "loc": "kernel/kthread.c:1470",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:page_cache_sync_ra",
        "mm/swapfile.c:__cgroup_throttle_swaprate",
        "block/blk-cgroup.c:bio_associate_blkg",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579760304,
      "name": "kthread_blkcg",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state * kthread_blkcg()
```

```json
{
  "name": "kthread_blkcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579874512,
      "name": "kthread_blkcg",
      "external": true,
      "loc": "kernel/kthread.c:1526",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blk_cgroup_congested",
        "block/blk-cgroup.c:bio_associate_blkg",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579874512,
      "name": "kthread_blkcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct cgroup_subsys_state * kthread_blkcg()
```

```json
{
  "name": "kthread_blkcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580017680,
      "name": "kthread_blkcg",
      "external": true,
      "loc": "kernel/kthread.c:1526",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blk_cgroup_congested",
        "block/blk-cgroup.c:bio_associate_blkg",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580017680,
      "name": "kthread_blkcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct cgroup_subsys_state * kthread_blkcg()
```

```json
{
  "name": "kthread_blkcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580071552,
      "name": "kthread_blkcg",
      "external": true,
      "loc": "kernel/kthread.c:1536",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blk_cgroup_congested",
        "block/blk-cgroup.c:bio_associate_blkg",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071552,
      "name": "kthread_blkcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct cgroup_subsys_state * kthread_blkcg()
```

```json
{
  "name": "kthread_blkcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580114384,
      "name": "kthread_blkcg",
      "external": true,
      "loc": "kernel/kthread.c:1552",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blk_cgroup_congested",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580114384,
      "name": "kthread_blkcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct cgroup_subsys_state * kthread_blkcg()
```

```json
{
  "name": "kthread_blkcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490840480,
      "name": "kthread_blkcg",
      "external": true,
      "loc": "kernel/kthread.c:1242",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:mem_cgroup_throttle_swaprate",
        "block/bio.c:bio_associate_blkg",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490840480,
      "name": "kthread_blkcg",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cgroup_subsys_state * kthread_blkcg()
```

```json
{
  "name": "kthread_blkcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224869384,
      "name": "kthread_blkcg",
      "external": true,
      "loc": "kernel/kthread.c:1242",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:mem_cgroup_throttle_swaprate",
        "block/bio.c:bio_associate_blkg",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224869384,
      "name": "kthread_blkcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct cgroup_subsys_state * kthread_blkcg()
```

```json
{
  "name": "kthread_blkcg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283684336,
      "name": "kthread_blkcg",
      "external": true,
      "loc": "kernel/kthread.c:1242",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:mem_cgroup_throttle_swaprate",
        "block/bio.c:bio_associate_blkg",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283684336,
      "name": "kthread_blkcg",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct cgroup_subsys_state * kthread_blkcg()
```

```json
{
  "name": "kthread_blkcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271509978,
      "name": "kthread_blkcg",
      "external": true,
      "loc": "kernel/kthread.c:1242",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:mem_cgroup_throttle_swaprate",
        "block/bio.c:bio_associate_blkg",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271509978,
      "name": "kthread_blkcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct cgroup_subsys_state * kthread_blkcg()
```

```json
{
  "name": "kthread_blkcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579640192,
      "name": "kthread_blkcg",
      "external": true,
      "loc": "kernel/kthread.c:1242",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:mem_cgroup_throttle_swaprate",
        "block/bio.c:bio_associate_blkg",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579640192,
      "name": "kthread_blkcg",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state * kthread_blkcg()
```

```json
{
  "name": "kthread_blkcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579568592,
      "name": "kthread_blkcg",
      "external": true,
      "loc": "kernel/kthread.c:1242",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:mem_cgroup_throttle_swaprate",
        "block/bio.c:bio_associate_blkg",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568592,
      "name": "kthread_blkcg",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state * kthread_blkcg()
```

```json
{
  "name": "kthread_blkcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579637456,
      "name": "kthread_blkcg",
      "external": true,
      "loc": "kernel/kthread.c:1242",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:mem_cgroup_throttle_swaprate",
        "block/bio.c:bio_associate_blkg",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579637456,
      "name": "kthread_blkcg",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state * kthread_blkcg()
```

```json
{
  "name": "kthread_blkcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579671296,
      "name": "kthread_blkcg",
      "external": true,
      "loc": "kernel/kthread.c:1242",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:mem_cgroup_throttle_swaprate",
        "block/bio.c:bio_associate_blkg",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671296,
      "name": "kthread_blkcg",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct cgroup_subsys_state * kthread_blkcg()
```
</details>
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
