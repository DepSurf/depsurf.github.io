# Function: <code>eventfd_signal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
__u64 eventfd_signal(struct eventfd_ctx * ctx, __u64 n)
```

```json
{
  "name": "eventfd_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581306752,
      "name": "eventfd_signal",
      "external": true,
      "loc": "fs/eventfd.c:54",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_oom_register_event",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "fs/aio.c:aio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581306752,
      "name": "eventfd_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
__u64 eventfd_signal(struct eventfd_ctx * ctx, __u64 n)
```

```json
{
  "name": "eventfd_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581473120,
      "name": "eventfd_signal",
      "external": true,
      "loc": "fs/eventfd.c:54",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_oom_register_event",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/vmpressure.c:vmpressure_work_fn",
        "fs/aio.c:aio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581473120,
      "name": "eventfd_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
__u64 eventfd_signal(struct eventfd_ctx * ctx, __u64 n)
```

```json
{
  "name": "eventfd_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581553808,
      "name": "eventfd_signal",
      "external": true,
      "loc": "fs/eventfd.c:54",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_oom_register_event",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/vmpressure.c:vmpressure_work_fn",
        "fs/aio.c:aio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581553808,
      "name": "eventfd_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
__u64 eventfd_signal(struct eventfd_ctx * ctx, __u64 n)
```

```json
{
  "name": "eventfd_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581607760,
      "name": "eventfd_signal",
      "external": true,
      "loc": "fs/eventfd.c:54",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_oom_register_event",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/vmpressure.c:vmpressure_work_fn",
        "fs/aio.c:aio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581607760,
      "name": "eventfd_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
__u64 eventfd_signal(struct eventfd_ctx * ctx, __u64 n)
```

```json
{
  "name": "eventfd_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581751904,
      "name": "eventfd_signal",
      "external": true,
      "loc": "fs/eventfd.c:54",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_oom_register_event",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/vmpressure.c:vmpressure_work_fn",
        "fs/aio.c:aio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581751904,
      "name": "eventfd_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
__u64 eventfd_signal(struct eventfd_ctx * ctx, __u64 n)
```

```json
{
  "name": "eventfd_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581920400,
      "name": "eventfd_signal",
      "external": true,
      "loc": "fs/eventfd.c:54",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_oom_register_event",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/vmpressure.c:vmpressure_work_fn",
        "fs/aio.c:aio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581920400,
      "name": "eventfd_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
__u64 eventfd_signal(struct eventfd_ctx * ctx, __u64 n)
```

```json
{
  "name": "eventfd_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582004768,
      "name": "eventfd_signal",
      "external": true,
      "loc": "fs/eventfd.c:54",
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
        "fs/aio.c:aio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582004768,
      "name": "eventfd_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
__u64 eventfd_signal(struct eventfd_ctx * ctx, __u64 n)
```

```json
{
  "name": "eventfd_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582141328,
      "name": "eventfd_signal",
      "external": true,
      "loc": "fs/eventfd.c:59",
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
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:io_cqring_ev_posted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582141328,
      "name": "eventfd_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
__u64 eventfd_signal(struct eventfd_ctx * ctx, __u64 n)
```

```json
{
  "name": "eventfd_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582218480,
      "name": "eventfd_signal",
      "external": true,
      "loc": "fs/eventfd.c:61",
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
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:io_cqring_ev_posted",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_request",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_ctx_trigger_single",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msihandler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_send_intx_eventfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582218480,
      "name": "eventfd_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
__u64 eventfd_signal(struct eventfd_ctx * ctx, __u64 n)
```

```json
{
  "name": "eventfd_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582455040,
      "name": "eventfd_signal",
      "external": true,
      "loc": "fs/eventfd.c:62",
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
        "fs/io_uring.c:io_cqring_ev_posted",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_request",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msihandler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582455040,
      "name": "eventfd_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
__u64 eventfd_signal(struct eventfd_ctx * ctx, __u64 n)
```

```json
{
  "name": "eventfd_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582511808,
      "name": "eventfd_signal",
      "external": true,
      "loc": "fs/eventfd.c:62",
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
        "fs/io_uring.c:io_cqring_ev_posted_iopoll",
        "fs/io_uring.c:io_cqring_ev_posted",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_request",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msihandler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582511808,
      "name": "eventfd_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
__u64 eventfd_signal(struct eventfd_ctx * ctx, __u64 n)
```

```json
{
  "name": "eventfd_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582539584,
      "name": "eventfd_signal",
      "external": true,
      "loc": "fs/eventfd.c:62",
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
        "fs/io_uring.c:io_iopoll_complete",
        "fs/io_uring.c:io_cqring_ev_posted",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_request",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msihandler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582539584,
      "name": "eventfd_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
__u64 eventfd_signal(struct eventfd_ctx * ctx, __u64 n)
```

```json
{
  "name": "eventfd_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582855680,
      "name": "eventfd_signal",
      "external": true,
      "loc": "fs/eventfd.c:60",
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
        "fs/io_uring.c:io_iopoll_complete",
        "fs/io_uring.c:io_cqring_ev_posted",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_aer_err_detected",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_request",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msihandler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582855680,
      "name": "eventfd_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
__u64 eventfd_signal(struct eventfd_ctx * ctx, __u64 n)
```

```json
{
  "name": "eventfd_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583418160,
      "name": "eventfd_signal",
      "external": true,
      "loc": "fs/eventfd.c:60",
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
        "io_uring/io_uring.c:__io_commit_cqring_flush",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_aer_err_detected",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_request",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_ctx_trigger_single",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_unmask",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msihandler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583418160,
      "name": "eventfd_signal",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
__u64 eventfd_signal(struct eventfd_ctx * ctx, __u64 n)
```

```json
{
  "name": "eventfd_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584009024,
      "name": "eventfd_signal",
      "external": true,
      "loc": "fs/eventfd.c:88",
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
        "fs/aio.c:aio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584009024,
      "name": "eventfd_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
__u64 eventfd_signal(struct eventfd_ctx * ctx, __u64 n)
```

```json
{
  "name": "eventfd_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584233440,
      "name": "eventfd_signal",
      "external": true,
      "loc": "fs/eventfd.c:88",
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
        "fs/aio.c:aio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584233440,
      "name": "eventfd_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eventfd_signal",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583791478,
      "name": "eventfd_signal",
      "external": false,
      "loc": "include/linux/eventfd.h:87",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_oom_register_event",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:__mem_cgroup_threshold"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583829930,
      "name": "eventfd_signal",
      "external": false,
      "loc": "include/linux/eventfd.h:87",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584471088,
      "name": "eventfd_signal",
      "external": false,
      "loc": "include/linux/eventfd.h:87",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592145391,
      "name": "eventfd_signal",
      "external": false,
      "loc": "include/linux/eventfd.h:87",
      "file": "drivers/gpu/drm/drm_syncobj.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_syncobj.c:syncobj_eventfd_entry_fence_func"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
__u64 eventfd_signal(struct eventfd_ctx * ctx, __u64 n)
```

```json
{
  "name": "eventfd_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493785360,
      "name": "eventfd_signal",
      "external": true,
      "loc": "fs/eventfd.c:61",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/eventfd.c:ioeventfd_write",
        "virt/kvm/eventfd.c:irqfd_resampler_ack",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_oom_register_event",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/vmpressure.c:vmpressure_work_fn",
        "fs/aio.c:aio_complete",
        "fs/io_uring.c:io_cqring_ev_posted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493785360,
      "name": "eventfd_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
__u64 eventfd_signal(struct eventfd_ctx * ctx, __u64 n)
```

```json
{
  "name": "eventfd_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227297112,
      "name": "eventfd_signal",
      "external": true,
      "loc": "fs/eventfd.c:61",
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
        "fs/io_uring.c:io_cqring_ev_posted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227297112,
      "name": "eventfd_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
__u64 eventfd_signal(struct eventfd_ctx * ctx, __u64 n)
```

```json
{
  "name": "eventfd_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287396848,
      "name": "eventfd_signal",
      "external": true,
      "loc": "fs/eventfd.c:61",
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
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:io_cqring_ev_posted",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_request",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_ctx_trigger_single",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msihandler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_send_intx_eventfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287396848,
      "name": "eventfd_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
__u64 eventfd_signal(struct eventfd_ctx * ctx, __u64 n)
```

```json
{
  "name": "eventfd_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273376246,
      "name": "eventfd_signal",
      "external": true,
      "loc": "fs/eventfd.c:61",
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
        "fs/io_uring.c:io_cqring_ev_posted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273376246,
      "name": "eventfd_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
__u64 eventfd_signal(struct eventfd_ctx * ctx, __u64 n)
```

```json
{
  "name": "eventfd_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582187216,
      "name": "eventfd_signal",
      "external": true,
      "loc": "fs/eventfd.c:61",
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
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:io_cqring_ev_posted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582187216,
      "name": "eventfd_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
__u64 eventfd_signal(struct eventfd_ctx * ctx, __u64 n)
```

```json
{
  "name": "eventfd_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582124784,
      "name": "eventfd_signal",
      "external": true,
      "loc": "fs/eventfd.c:61",
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
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:io_cqring_ev_posted",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_request",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_ctx_trigger_single",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msihandler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_send_intx_eventfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582124784,
      "name": "eventfd_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
__u64 eventfd_signal(struct eventfd_ctx * ctx, __u64 n)
```

```json
{
  "name": "eventfd_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582177696,
      "name": "eventfd_signal",
      "external": true,
      "loc": "fs/eventfd.c:61",
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
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:io_cqring_ev_posted",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_request",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_ctx_trigger_single",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msihandler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_send_intx_eventfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582177696,
      "name": "eventfd_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
__u64 eventfd_signal(struct eventfd_ctx * ctx, __u64 n)
```

```json
{
  "name": "eventfd_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582253840,
      "name": "eventfd_signal",
      "external": true,
      "loc": "fs/eventfd.c:61",
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
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:io_cqring_ev_posted",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_request",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_ctx_trigger_single",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msihandler",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_send_intx_eventfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582253840,
      "name": "eventfd_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
__u64 eventfd_signal(struct eventfd_ctx * ctx, __u64 n)
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
