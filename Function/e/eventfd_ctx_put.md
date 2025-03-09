# Function: <code>eventfd_ctx_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx * ctx)
```

```json
{
  "name": "eventfd_ctx_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581307529,
      "name": "eventfd_ctx_put",
      "external": true,
      "loc": "fs/eventfd.c:102",
      "file": "fs/eventfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_release"
      ],
      "caller_func": [
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/aio.c:kiocb_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581307568,
      "name": "eventfd_ctx_put",
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
void eventfd_ctx_put(struct eventfd_ctx * ctx)
```

```json
{
  "name": "eventfd_ctx_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581473897,
      "name": "eventfd_ctx_put",
      "external": true,
      "loc": "fs/eventfd.c:102",
      "file": "fs/eventfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_release"
      ],
      "caller_func": [
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/aio.c:kiocb_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581473920,
      "name": "eventfd_ctx_put",
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
void eventfd_ctx_put(struct eventfd_ctx * ctx)
```

```json
{
  "name": "eventfd_ctx_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581554585,
      "name": "eventfd_ctx_put",
      "external": true,
      "loc": "fs/eventfd.c:102",
      "file": "fs/eventfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_release"
      ],
      "caller_func": [
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/aio.c:kiocb_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581554608,
      "name": "eventfd_ctx_put",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx * ctx)
```

```json
{
  "name": "eventfd_ctx_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581608080,
      "name": "eventfd_ctx_put",
      "external": true,
      "loc": "fs/eventfd.c:102",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/eventfd.c:eventfd_release",
        "fs/aio.c:kiocb_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581608080,
      "name": "eventfd_ctx_put",
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
void eventfd_ctx_put(struct eventfd_ctx * ctx)
```

```json
{
  "name": "eventfd_ctx_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581752601,
      "name": "eventfd_ctx_put",
      "external": true,
      "loc": "fs/eventfd.c:102",
      "file": "fs/eventfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_release"
      ],
      "caller_func": [
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/aio.c:kiocb_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581752640,
      "name": "eventfd_ctx_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void eventfd_ctx_put(struct eventfd_ctx * ctx)
```

```json
{
  "name": "eventfd_ctx_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581921257,
      "name": "eventfd_ctx_put",
      "external": true,
      "loc": "fs/eventfd.c:89",
      "file": "fs/eventfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_release"
      ],
      "caller_func": [
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581921344,
      "name": "eventfd_ctx_put",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx * ctx)
```

```json
{
  "name": "eventfd_ctx_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582005625,
      "name": "eventfd_ctx_put",
      "external": true,
      "loc": "fs/eventfd.c:89",
      "file": "fs/eventfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_release"
      ],
      "caller_func": [
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582005664,
      "name": "eventfd_ctx_put",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx * ctx)
```

```json
{
  "name": "eventfd_ctx_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582142267,
      "name": "eventfd_ctx_put",
      "external": true,
      "loc": "fs/eventfd.c:96",
      "file": "fs/eventfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_release"
      ],
      "caller_func": [
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582142304,
      "name": "eventfd_ctx_put",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx * ctx)
```

```json
{
  "name": "eventfd_ctx_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582219467,
      "name": "eventfd_ctx_put",
      "external": true,
      "loc": "fs/eventfd.c:111",
      "file": "fs/eventfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_release"
      ],
      "caller_func": [
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "drivers/vfio/virqfd.c:vfio_virqfd_enable",
        "drivers/vfio/virqfd.c:virqfd_shutdown",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582219504,
      "name": "eventfd_ctx_put",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx * ctx)
```

```json
{
  "name": "eventfd_ctx_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582456331,
      "name": "eventfd_ctx_put",
      "external": true,
      "loc": "fs/eventfd.c:112",
      "file": "fs/eventfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_release"
      ],
      "caller_func": [
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_free",
        "drivers/vfio/virqfd.c:vfio_virqfd_enable",
        "drivers/vfio/virqfd.c:virqfd_shutdown",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_release",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_release",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582456176,
      "name": "eventfd_ctx_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void eventfd_ctx_put(struct eventfd_ctx * ctx)
```

```json
{
  "name": "eventfd_ctx_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582513099,
      "name": "eventfd_ctx_put",
      "external": true,
      "loc": "fs/eventfd.c:112",
      "file": "fs/eventfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_release"
      ],
      "caller_func": [
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_free",
        "drivers/vfio/virqfd.c:vfio_virqfd_enable",
        "drivers/vfio/virqfd.c:virqfd_shutdown",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_release",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_release",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582512944,
      "name": "eventfd_ctx_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void eventfd_ctx_put(struct eventfd_ctx * ctx)
```

```json
{
  "name": "eventfd_ctx_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582540875,
      "name": "eventfd_ctx_put",
      "external": true,
      "loc": "fs/eventfd.c:112",
      "file": "fs/eventfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_release"
      ],
      "caller_func": [
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_free",
        "drivers/vfio/virqfd.c:vfio_virqfd_enable",
        "drivers/vfio/virqfd.c:virqfd_shutdown",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_release",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_release",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582540720,
      "name": "eventfd_ctx_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void eventfd_ctx_put(struct eventfd_ctx * ctx)
```

```json
{
  "name": "eventfd_ctx_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582856987,
      "name": "eventfd_ctx_put",
      "external": true,
      "loc": "fs/eventfd.c:110",
      "file": "fs/eventfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_release"
      ],
      "caller_func": [
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_free",
        "drivers/vfio/virqfd.c:vfio_virqfd_enable",
        "drivers/vfio/virqfd.c:virqfd_shutdown",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_close_device",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_close_device",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582856832,
      "name": "eventfd_ctx_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void eventfd_ctx_put(struct eventfd_ctx * ctx)
```

```json
{
  "name": "eventfd_ctx_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583420297,
      "name": "eventfd_ctx_put",
      "external": true,
      "loc": "fs/eventfd.c:110",
      "file": "fs/eventfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_release"
      ],
      "caller_func": [
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "io_uring/io_uring.c:io_eventfd_put",
        "drivers/vfio/virqfd.c:vfio_virqfd_enable",
        "drivers/vfio/virqfd.c:virqfd_shutdown",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_close_device",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_close_device",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_ctx_trigger_single",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_ctx_trigger_single",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583420128,
      "name": "eventfd_ctx_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void eventfd_ctx_put(struct eventfd_ctx * ctx)
```

```json
{
  "name": "eventfd_ctx_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584007961,
      "name": "eventfd_ctx_put",
      "external": true,
      "loc": "fs/eventfd.c:115",
      "file": "fs/eventfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_release"
      ],
      "caller_func": [
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "io_uring/io_uring.c:io_eventfd_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584007776,
      "name": "eventfd_ctx_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void eventfd_ctx_put(struct eventfd_ctx * ctx)
```

```json
{
  "name": "eventfd_ctx_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584233065,
      "name": "eventfd_ctx_put",
      "external": true,
      "loc": "fs/eventfd.c:115",
      "file": "fs/eventfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_release"
      ],
      "caller_func": [
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "io_uring/io_uring.c:io_eventfd_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584232880,
      "name": "eventfd_ctx_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void eventfd_ctx_put(struct eventfd_ctx * ctx)
```

```json
{
  "name": "eventfd_ctx_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584447897,
      "name": "eventfd_ctx_put",
      "external": true,
      "loc": "fs/eventfd.c:103",
      "file": "fs/eventfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_release"
      ],
      "caller_func": [
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "io_uring/io_uring.c:io_eventfd_ops",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_eventfd_ioctl",
        "drivers/gpu/drm/drm_syncobj.c:syncobj_eventfd_entry_fence_func",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584447712,
      "name": "eventfd_ctx_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void eventfd_ctx_put(struct eventfd_ctx * ctx)
```

```json
{
  "name": "eventfd_ctx_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493783992,
      "name": "eventfd_ctx_put",
      "external": true,
      "loc": "fs/eventfd.c:111",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/eventfd.c:kvm_deassign_ioeventfd_idx",
        "virt/kvm/eventfd.c:kvm_deassign_ioeventfd_idx",
        "virt/kvm/eventfd.c:kvm_assign_ioeventfd_idx",
        "virt/kvm/eventfd.c:ioeventfd_destructor",
        "virt/kvm/eventfd.c:kvm_irqfd",
        "virt/kvm/eventfd.c:kvm_irqfd_assign",
        "virt/kvm/eventfd.c:kvm_irqfd_assign",
        "virt/kvm/eventfd.c:irqfd_shutdown",
        "virt/kvm/eventfd.c:irqfd_shutdown",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/eventfd.c:eventfd_release",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:__arm64_sys_io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493783992,
      "name": "eventfd_ctx_put",
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
void eventfd_ctx_put(struct eventfd_ctx * ctx)
```

```json
{
  "name": "eventfd_ctx_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227297696,
      "name": "eventfd_ctx_put",
      "external": true,
      "loc": "fs/eventfd.c:111",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/eventfd.c:eventfd_release",
        "fs/aio.c:__se_sys_io_submit",
        "fs/aio.c:__se_sys_io_submit",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:__se_sys_io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227297696,
      "name": "eventfd_ctx_put",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx * ctx)
```

```json
{
  "name": "eventfd_ctx_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287397648,
      "name": "eventfd_ctx_put",
      "external": true,
      "loc": "fs/eventfd.c:111",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/eventfd.c:eventfd_release",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:__se_sys_io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "drivers/vfio/virqfd.c:vfio_virqfd_enable",
        "drivers/vfio/virqfd.c:virqfd_shutdown",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287397648,
      "name": "eventfd_ctx_put",
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
void eventfd_ctx_put(struct eventfd_ctx * ctx)
```

```json
{
  "name": "eventfd_ctx_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273377266,
      "name": "eventfd_ctx_put",
      "external": true,
      "loc": "fs/eventfd.c:111",
      "file": "fs/eventfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_release"
      ],
      "caller_func": [
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:__se_sys_io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273376724,
      "name": "eventfd_ctx_put",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx * ctx)
```

```json
{
  "name": "eventfd_ctx_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582188203,
      "name": "eventfd_ctx_put",
      "external": true,
      "loc": "fs/eventfd.c:111",
      "file": "fs/eventfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_release"
      ],
      "caller_func": [
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582188240,
      "name": "eventfd_ctx_put",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx * ctx)
```

```json
{
  "name": "eventfd_ctx_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582125771,
      "name": "eventfd_ctx_put",
      "external": true,
      "loc": "fs/eventfd.c:111",
      "file": "fs/eventfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_release"
      ],
      "caller_func": [
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "drivers/vfio/virqfd.c:vfio_virqfd_enable",
        "drivers/vfio/virqfd.c:virqfd_shutdown",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582125808,
      "name": "eventfd_ctx_put",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx * ctx)
```

```json
{
  "name": "eventfd_ctx_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582178683,
      "name": "eventfd_ctx_put",
      "external": true,
      "loc": "fs/eventfd.c:111",
      "file": "fs/eventfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_release"
      ],
      "caller_func": [
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "drivers/vfio/virqfd.c:vfio_virqfd_enable",
        "drivers/vfio/virqfd.c:virqfd_shutdown",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582178720,
      "name": "eventfd_ctx_put",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx * ctx)
```

```json
{
  "name": "eventfd_ctx_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582255963,
      "name": "eventfd_ctx_put",
      "external": true,
      "loc": "fs/eventfd.c:111",
      "file": "fs/eventfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_release"
      ],
      "caller_func": [
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "drivers/vfio/virqfd.c:vfio_virqfd_enable",
        "drivers/vfio/virqfd.c:virqfd_shutdown",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582256000,
      "name": "eventfd_ctx_put",
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
