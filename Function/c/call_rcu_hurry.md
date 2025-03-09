# Function: <code>call_rcu_hurry</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void call_rcu_hurry(struct callback_head * head, rcu_callback_t func)
```

```json
{
  "name": "call_rcu_hurry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579958989,
      "name": "call_rcu_hurry",
      "external": false,
      "loc": "include/linux/rcupdate.h:114",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_rcu_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580599724,
      "name": "call_rcu_hurry",
      "external": false,
      "loc": "include/linux/rcupdate.h:114",
      "file": "kernel/rcu/sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/sync.c:rcu_sync_exit",
        "kernel/rcu/sync.c:rcu_sync_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580651856,
      "name": "call_rcu_hurry",
      "external": false,
      "loc": "include/linux/rcupdate.h:114",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586744650,
      "name": "call_rcu_hurry",
      "external": false,
      "loc": "include/linux/rcupdate.h:114",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_eventfd_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587073281,
      "name": "call_rcu_hurry",
      "external": false,
      "loc": "include/linux/rcupdate.h:114",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:__percpu_ref_switch_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590885830,
      "name": "call_rcu_hurry",
      "external": false,
      "loc": "include/linux/rcupdate.h:114",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593344304,
      "name": "call_rcu_hurry",
      "external": false,
      "loc": "include/linux/rcupdate.h:114",
      "file": "net/core/dst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst.c:dst_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580651856,
      "name": "call_rcu_hurry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void call_rcu_hurry(struct callback_head * head, rcu_callback_t func)
```

```json
{
  "name": "call_rcu_hurry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580009677,
      "name": "call_rcu_hurry",
      "external": false,
      "loc": "include/linux/rcupdate.h:115",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_rcu_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580673228,
      "name": "call_rcu_hurry",
      "external": false,
      "loc": "include/linux/rcupdate.h:115",
      "file": "kernel/rcu/sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/sync.c:rcu_sync_exit",
        "kernel/rcu/sync.c:rcu_sync_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580725616,
      "name": "call_rcu_hurry",
      "external": false,
      "loc": "include/linux/rcupdate.h:115",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587008554,
      "name": "call_rcu_hurry",
      "external": false,
      "loc": "include/linux/rcupdate.h:115",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_eventfd_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587331297,
      "name": "call_rcu_hurry",
      "external": false,
      "loc": "include/linux/rcupdate.h:115",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:__percpu_ref_switch_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591229142,
      "name": "call_rcu_hurry",
      "external": false,
      "loc": "include/linux/rcupdate.h:115",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593807034,
      "name": "call_rcu_hurry",
      "external": false,
      "loc": "include/linux/rcupdate.h:115",
      "file": "net/core/dst.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580725616,
      "name": "call_rcu_hurry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void call_rcu_hurry(struct callback_head * head, rcu_callback_t func)
```

```json
{
  "name": "call_rcu_hurry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580814272,
      "name": "call_rcu_hurry",
      "external": true,
      "loc": "kernel/rcu/tree.c:2779",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:queue_rcu_work",
        "kernel/rcu/sync.c:rcu_sync_exit",
        "kernel/rcu/sync.c:rcu_sync_func",
        "kernel/bpf/memalloc.c:bpf_mem_refill",
        "io_uring/io_uring.c:io_eventfd_signal",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580814272,
      "name": "call_rcu_hurry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void call_rcu_hurry(struct callback_head * head, rcu_callback_t func)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
