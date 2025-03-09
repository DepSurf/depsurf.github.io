# Function: <code>strrchr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
char * strrchr(const char * s, int c)
```

```json
{
  "name": "strrchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582980640,
      "name": "strrchr",
      "external": true,
      "loc": "lib/string.c:403",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_uprobe.c:create_trace_uprobe",
        "mm/memory.c:print_vma_addr",
        "fs/exec.c:setup_new_exec",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/usb/core/file.c:usb_register_dev",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582980640,
      "name": "strrchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
char * strrchr(const char * s, int c)
```

```json
{
  "name": "strrchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583269856,
      "name": "strrchr",
      "external": true,
      "loc": "lib/string.c:403",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_uprobe.c:create_trace_uprobe",
        "mm/memory.c:print_vma_addr",
        "fs/exec.c:setup_new_exec",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/usb/core/file.c:usb_register_dev",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583269856,
      "name": "strrchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
char * strrchr(const char * s, int c)
```

```json
{
  "name": "strrchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583388624,
      "name": "strrchr",
      "external": true,
      "loc": "lib/string.c:403",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_uprobe.c:create_trace_uprobe",
        "mm/memory.c:print_vma_addr",
        "fs/exec.c:setup_new_exec",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/usb/core/file.c:usb_register_dev",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583388624,
      "name": "strrchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
char * strrchr(const char * s, int c)
```

```json
{
  "name": "strrchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588245136,
      "name": "strrchr",
      "external": true,
      "loc": "lib/string.c:403",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_uprobe.c:create_trace_uprobe",
        "kernel/trace/trace_uprobe.c:create_trace_uprobe",
        "mm/memory.c:print_vma_addr",
        "fs/exec.c:setup_new_exec",
        "security/security.c:security_setprocattr",
        "security/security.c:security_add_hooks",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588245136,
      "name": "strrchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
char * strrchr(const char * s, int c)
```

```json
{
  "name": "strrchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588796560,
      "name": "strrchr",
      "external": true,
      "loc": "lib/string.c:404",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_uprobe.c:create_trace_uprobe",
        "kernel/trace/trace_uprobe.c:create_trace_uprobe",
        "mm/memory.c:print_vma_addr",
        "fs/exec.c:setup_new_exec",
        "security/security.c:security_add_hooks",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588796560,
      "name": "strrchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
char * strrchr(const char * s, int c)
```

```json
{
  "name": "strrchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589174672,
      "name": "strrchr",
      "external": true,
      "loc": "lib/string.c:404",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_uprobe.c:create_trace_uprobe",
        "kernel/trace/trace_uprobe.c:create_trace_uprobe",
        "mm/memory.c:print_vma_addr",
        "fs/exec.c:setup_new_exec",
        "security/security.c:security_add_hooks",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589174672,
      "name": "strrchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
char * strrchr(const char * s, int c)
```

```json
{
  "name": "strrchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589404592,
      "name": "strrchr",
      "external": true,
      "loc": "lib/string.c:405",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "mm/memory.c:print_vma_addr",
        "fs/exec.c:setup_new_exec",
        "security/security.c:security_add_hooks",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pci/pci.c:pci_dev_str_match",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589404592,
      "name": "strrchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
char * strrchr(const char * s, int c)
```

```json
{
  "name": "strrchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589860464,
      "name": "strrchr",
      "external": true,
      "loc": "lib/string.c:441",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "mm/memory.c:print_vma_addr",
        "fs/exec.c:setup_new_exec",
        "security/security.c:security_add_hooks",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pci/pci.c:pci_dev_str_match",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589860464,
      "name": "strrchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
char * strrchr(const char * s, int c)
```

```json
{
  "name": "strrchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590085952,
      "name": "strrchr",
      "external": true,
      "loc": "lib/string.c:443",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "mm/memory.c:print_vma_addr",
        "fs/exec.c:setup_new_exec",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pci/pci.c:pci_dev_str_match",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590085952,
      "name": "strrchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
char * strrchr(const char * s, int c)
```

```json
{
  "name": "strrchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585083776,
      "name": "strrchr",
      "external": true,
      "loc": "lib/string.c:484",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "mm/memory.c:print_vma_addr",
        "fs/exec.c:begin_new_exec",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_transition_type",
        "lib/dynamic_debug.c:ddebug_change",
        "drivers/pci/pci.c:pci_dev_str_match_path",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:xennet_init_queue",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585083776,
      "name": "strrchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
char * strrchr(const char * s, int c)
```

```json
{
  "name": "strrchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585232944,
      "name": "strrchr",
      "external": true,
      "loc": "lib/string.c:481",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "mm/memory.c:print_vma_addr",
        "fs/exec.c:begin_new_exec",
        "fs/coredump.c:cn_print_exe_file",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_transition_type",
        "lib/dynamic_debug.c:ddebug_change",
        "drivers/pci/pci.c:pci_dev_str_match_path",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/base/auxiliary.c:auxiliary_uevent",
        "drivers/base/auxiliary.c:auxiliary_match_id",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:xennet_init_queue",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585232944,
      "name": "strrchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
char * strrchr(const char * s, int c)
```

```json
{
  "name": "strrchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585115824,
      "name": "strrchr",
      "external": true,
      "loc": "lib/string.c:481",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "mm/memory.c:print_vma_addr",
        "fs/exec.c:begin_new_exec",
        "fs/coredump.c:cn_print_exe_file",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "lib/dynamic_debug.c:ddebug_change",
        "drivers/pci/pci.c:pci_dev_str_match_path",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/base/auxiliary.c:auxiliary_uevent",
        "drivers/base/auxiliary.c:auxiliary_match_id",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585115824,
      "name": "strrchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
char * strrchr(const char * s, int c)
```

```json
{
  "name": "strrchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585564512,
      "name": "strrchr",
      "external": true,
      "loc": "lib/string.c:482",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "mm/memory.c:print_vma_addr",
        "fs/exec.c:begin_new_exec",
        "fs/coredump.c:cn_print_exe_file",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "lib/dynamic_debug.c:ddebug_change",
        "drivers/pci/pci.c:pci_dev_str_match_path",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/base/auxiliary.c:auxiliary_uevent",
        "drivers/base/auxiliary.c:auxiliary_match_id",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585564512,
      "name": "strrchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
char * strrchr(const char * s, int c)
```

```json
{
  "name": "strrchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586717120,
      "name": "strrchr",
      "external": true,
      "loc": "lib/string.c:443",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:contains_operator",
        "kernel/trace/trace_events_hist.c:contains_operator",
        "kernel/trace/trace_events_hist.c:contains_operator",
        "kernel/trace/trace_events_hist.c:contains_operator",
        "kernel/trace/trace_events_hist.c:contains_operator",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "mm/memory.c:print_vma_addr",
        "fs/exec.c:begin_new_exec",
        "fs/coredump.c:cn_print_exe_file",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "lib/dynamic_debug.c:ddebug_change",
        "drivers/pci/pci.c:pci_dev_str_match_path",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/base/auxiliary.c:auxiliary_uevent",
        "drivers/base/auxiliary.c:auxiliary_match_id",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/usb/core/file.c:usb_register_dev",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586717120,
      "name": "strrchr",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
char * strrchr(const char * s, int c)
```

```json
{
  "name": "strrchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595879280,
      "name": "strrchr",
      "external": true,
      "loc": "lib/string.c:378",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:contains_operator",
        "kernel/trace/trace_events_hist.c:contains_operator",
        "kernel/trace/trace_events_hist.c:contains_operator",
        "kernel/trace/trace_events_hist.c:contains_operator",
        "kernel/trace/trace_events_hist.c:contains_operator",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "mm/memory.c:print_vma_addr",
        "fs/exec.c:begin_new_exec",
        "fs/coredump.c:cn_print_exe_file",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "lib/dynamic_debug.c:ddebug_change",
        "drivers/pci/pci.c:pci_dev_str_match_path",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/base/auxiliary.c:auxiliary_uevent",
        "drivers/base/auxiliary.c:auxiliary_match_id",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/usb/core/file.c:usb_register_dev",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595879280,
      "name": "strrchr",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
char * strrchr(const char * s, int c)
```

```json
{
  "name": "strrchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596396672,
      "name": "strrchr",
      "external": true,
      "loc": "lib/string.c:378",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:contains_operator",
        "kernel/trace/trace_events_hist.c:contains_operator",
        "kernel/trace/trace_events_hist.c:contains_operator",
        "kernel/trace/trace_events_hist.c:contains_operator",
        "kernel/trace/trace_events_hist.c:contains_operator",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "mm/memory.c:print_vma_addr",
        "fs/exec.c:begin_new_exec",
        "fs/coredump.c:cn_print_exe_file",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "lib/dynamic_debug.c:ddebug_change",
        "drivers/pci/pci.c:pci_dev_str_match_path",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/base/auxiliary.c:auxiliary_uevent",
        "drivers/base/auxiliary.c:auxiliary_match_id",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/usb/core/file.c:usb_register_dev",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596396672,
      "name": "strrchr",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
char * strrchr(const char * s, int c)
```

```json
{
  "name": "strrchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597291904,
      "name": "strrchr",
      "external": true,
      "loc": "lib/string.c:363",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:contains_operator",
        "kernel/trace/trace_events_hist.c:contains_operator",
        "kernel/trace/trace_events_hist.c:contains_operator",
        "kernel/trace/trace_events_hist.c:contains_operator",
        "kernel/trace/trace_events_hist.c:contains_operator",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "mm/memory.c:print_vma_addr",
        "fs/exec.c:begin_new_exec",
        "fs/coredump.c:cn_print_exe_file",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "lib/dynamic_debug.c:ddebug_change",
        "drivers/pci/pci.c:pci_dev_str_match_path",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/base/auxiliary.c:auxiliary_uevent",
        "drivers/base/auxiliary.c:auxiliary_match_id",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/usb/core/file.c:usb_register_dev",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597291904,
      "name": "strrchr",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "strrchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "strrchr",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "lib/fdt_ro.c:fdt_get_name",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "mm/memory.c:print_vma_addr",
        "fs/exec.c:setup_new_exec",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pci/pci.c:pci_dev_str_match",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "drivers/thermal/armada_thermal.c:armada_thermal_probe",
        "drivers/firmware/dmi_scan.c:dmi_get_date",
        "drivers/of/base.c:__of_find_node_by_path",
        "drivers/of/base.c:of_node_name_prefix",
        "drivers/of/base.c:of_node_name_eq",
        "drivers/of/platform.c:of_device_make_bus_id",
        "drivers/of/kobj.c:__of_attach_node_sysfs",
        "drivers/of/fdt.c:of_scan_flat_dt_subnodes",
        "drivers/of/fdt.c:of_scan_flat_dt",
        "drivers/of/of_reserved_mem.c:of_reserved_mem_lookup",
        "drivers/of/resolver.c:adjust_local_phandle_references",
        "drivers/of/resolver.c:adjust_local_phandle_references",
        "lib/fdt_ro.c:fdt_get_name",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_gen_full_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503800908,
      "name": "strrchr",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "strrchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "strrchr",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "mm/memory.c:print_vma_addr",
        "fs/exec.c:setup_new_exec",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "drivers/pci/pci.c:pci_dev_str_match",
        "drivers/clk/ti/adpll.c:ti_adpll_setup_clock",
        "drivers/soc/samsung/pm_domains.c:exynos4_pm_init_power_domain",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/thermal/armada_thermal.c:armada_thermal_probe",
        "drivers/firmware/dmi_scan.c:dmi_get_date",
        "drivers/of/base.c:__of_find_node_by_path",
        "drivers/of/base.c:of_node_name_prefix",
        "drivers/of/base.c:of_node_name_eq",
        "drivers/of/platform.c:of_device_make_bus_id",
        "drivers/of/kobj.c:__of_attach_node_sysfs",
        "drivers/of/fdt.c:of_scan_flat_dt_subnodes",
        "drivers/of/fdt.c:of_scan_flat_dt",
        "drivers/of/of_reserved_mem.c:of_reserved_mem_lookup",
        "drivers/of/resolver.c:adjust_local_phandle_references",
        "drivers/of/resolver.c:adjust_local_phandle_references",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe",
        "lib/fdt_ro.c:fdt_get_name",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_gen_full_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236423968,
      "name": "strrchr",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
char * strrchr(const char * s, int c)
```

```json
{
  "name": "strrchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297722560,
      "name": "strrchr",
      "external": true,
      "loc": "lib/string.c:443",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/pseries/reconfig.c:ofdt_write",
        "arch/powerpc/platforms/pseries/of_helpers.c:pseries_of_derive_parent",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "mm/memory.c:print_vma_addr",
        "fs/exec.c:setup_new_exec",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pci/pci.c:pci_dev_str_match",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/of/base.c:__of_find_node_by_path",
        "drivers/of/base.c:of_node_name_prefix",
        "drivers/of/base.c:of_node_name_eq",
        "drivers/of/platform.c:of_device_alloc",
        "drivers/of/kobj.c:__of_attach_node_sysfs",
        "drivers/of/fdt.c:of_scan_flat_dt_subnodes",
        "drivers/of/fdt.c:of_scan_flat_dt",
        "drivers/of/of_reserved_mem.c:of_reserved_mem_lookup",
        "drivers/of/resolver.c:adjust_local_phandle_references",
        "drivers/of/resolver.c:adjust_local_phandle_references",
        "lib/fdt_ro.c:fdt_get_name",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_gen_full_name",
        "lib/vsprintf.c:device_node_gen_full_name",
        "lib/vsprintf.c:device_node_gen_full_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297722560,
      "name": "strrchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
char * strrchr(const char * s, int c)
```

```json
{
  "name": "strrchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279759504,
      "name": "strrchr",
      "external": true,
      "loc": "lib/string.c:443",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:print_vma_addr",
        "fs/exec.c:setup_new_exec",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pci/pci.c:pci_dev_str_match",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/of/base.c:__of_find_node_by_path",
        "drivers/of/base.c:of_node_name_prefix",
        "drivers/of/base.c:of_node_name_eq",
        "drivers/of/platform.c:of_device_alloc",
        "drivers/of/kobj.c:__of_attach_node_sysfs",
        "drivers/of/fdt.c:of_scan_flat_dt_subnodes",
        "drivers/of/fdt.c:of_scan_flat_dt",
        "drivers/of/of_reserved_mem.c:of_reserved_mem_lookup",
        "drivers/of/resolver.c:adjust_local_phandle_references",
        "drivers/of/resolver.c:adjust_local_phandle_references",
        "lib/fdt_ro.c:fdt_get_name",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_string",
        "lib/vsprintf.c:device_node_gen_full_name",
        "lib/vsprintf.c:device_node_gen_full_name",
        "lib/vsprintf.c:device_node_gen_full_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279759504,
      "name": "strrchr",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
char * strrchr(const char * s, int c)
```

```json
{
  "name": "strrchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589688208,
      "name": "strrchr",
      "external": true,
      "loc": "lib/string.c:443",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "mm/memory.c:print_vma_addr",
        "fs/exec.c:setup_new_exec",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pci/pci.c:pci_dev_str_match",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589688208,
      "name": "strrchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
char * strrchr(const char * s, int c)
```

```json
{
  "name": "strrchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589414000,
      "name": "strrchr",
      "external": true,
      "loc": "lib/string.c:443",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "mm/memory.c:print_vma_addr",
        "fs/exec.c:setup_new_exec",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pci/pci.c:pci_dev_str_match",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/usb/core/file.c:usb_register_dev",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589414000,
      "name": "strrchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
char * strrchr(const char * s, int c)
```

```json
{
  "name": "strrchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590131584,
      "name": "strrchr",
      "external": true,
      "loc": "lib/string.c:443",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "mm/memory.c:print_vma_addr",
        "fs/exec.c:setup_new_exec",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pci/pci.c:pci_dev_str_match",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590131584,
      "name": "strrchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
char * strrchr(const char * s, int c)
```

```json
{
  "name": "strrchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590181968,
      "name": "strrchr",
      "external": true,
      "loc": "lib/string.c:443",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "mm/memory.c:print_vma_addr",
        "fs/exec.c:setup_new_exec",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pci/pci.c:pci_dev_str_match",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/base/devtmpfs.c:handle_remove",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590181968,
      "name": "strrchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
char * strrchr(const char * s, int c)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
char * strrchr(const char * s, int c)
```
</details>
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
