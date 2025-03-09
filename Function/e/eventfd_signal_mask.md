# Function: <code>eventfd_signal_mask</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
__u64 eventfd_signal_mask(struct eventfd_ctx * ctx, __u64 n, unsigned int mask)
```

```json
{
  "name": "eventfd_signal_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584008800,
      "name": "eventfd_signal_mask",
      "external": true,
      "loc": "fs/eventfd.c:46",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventfd.c:eventfd_signal",
        "io_uring/io_uring.c:io_eventfd_signal",
        "io_uring/io_uring.c:io_eventfd_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584008800,
      "name": "eventfd_signal_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
__u64 eventfd_signal_mask(struct eventfd_ctx * ctx, __u64 n, __poll_t mask)
```

```json
{
  "name": "eventfd_signal_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584233216,
      "name": "eventfd_signal_mask",
      "external": true,
      "loc": "fs/eventfd.c:46",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventfd.c:eventfd_signal",
        "io_uring/io_uring.c:io_eventfd_signal",
        "io_uring/io_uring.c:io_eventfd_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584233216,
      "name": "eventfd_signal_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void eventfd_signal_mask(struct eventfd_ctx * ctx, __poll_t mask)
```

```json
{
  "name": "eventfd_signal_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584445040,
      "name": "eventfd_signal_mask",
      "external": true,
      "loc": "fs/eventfd.c:56",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_oom_register_event",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/vmpressure.c:vmpressure_work_fn",
        "fs/aio.c:aio_complete",
        "io_uring/io_uring.c:io_eventfd_signal",
        "io_uring/io_uring.c:io_eventfd_ops",
        "drivers/gpu/drm/drm_syncobj.c:syncobj_eventfd_entry_fence_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584445040,
      "name": "eventfd_signal_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
__u64 eventfd_signal_mask(struct eventfd_ctx * ctx, __u64 n, unsigned int mask)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int mask</code> ➡️ <code>__poll_t mask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>__u64 n</code>
</li>
<li>
<b>Param reordered. </b>
<code>ctx, n, mask</code> ➡️ <code>ctx, mask</code>
</li>
<li>
<b>Return type changed. </b>
<code>__u64</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
</ul>
