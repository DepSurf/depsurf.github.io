# Function: <code>vsnprintf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int vsnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vsnprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582994960,
      "name": "vsnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:1837",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/kmod.c:__request_module",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/kthread.c:kthread_create_on_node",
        "kernel/printk/printk.c:dump_stack_set_arch_desc",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "mm/slub.c:slab_err",
        "fs/dcache.c:dynamic_dname",
        "fs/seq_file.c:seq_vprintf",
        "fs/coredump.c:cn_vprintf",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_write_log",
        "security/tomoyo/common.c:tomoyo_addprintf",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "lib/kobject_uevent.c:add_uevent_var",
        "lib/seq_buf.c:seq_buf_vprintf",
        "lib/vsprintf.c:vsprintf",
        "lib/vsprintf.c:snprintf",
        "lib/vsprintf.c:scnprintf",
        "lib/vsprintf.c:sprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/kasprintf.c:kvasprintf",
        "drivers/pnp/interface.c:pnp_printf",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg",
        "net/netfilter/nf_log.c:nf_log_packet",
        "net/netfilter/nf_log.c:nf_log_trace",
        "net/netfilter/nf_log.c:nf_log_buf_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582994960,
      "name": "vsnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1315
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
int vsnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vsnprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583284720,
      "name": "vsnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:1974",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/kmod.c:__request_module",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/kthread.c:kthread_create_on_node",
        "kernel/printk/printk.c:dump_stack_set_arch_desc",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "mm/slub.c:slab_err",
        "fs/dcache.c:dynamic_dname",
        "fs/seq_file.c:seq_vprintf",
        "fs/coredump.c:cn_vprintf",
        "security/tomoyo/audit.c:tomoyo_write_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_addprintf",
        "lib/kobject_uevent.c:add_uevent_var",
        "lib/seq_buf.c:seq_buf_vprintf",
        "lib/vsprintf.c:sprintf",
        "lib/vsprintf.c:vsprintf",
        "lib/vsprintf.c:scnprintf",
        "lib/vsprintf.c:snprintf",
        "lib/vsprintf.c:pointer",
        "lib/kasprintf.c:kvasprintf",
        "lib/kasprintf.c:kvasprintf",
        "drivers/pnp/interface.c:pnp_printf",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg",
        "net/netfilter/nf_log.c:nf_log_buf_add",
        "net/netfilter/nf_log.c:nf_log_trace",
        "net/netfilter/nf_log.c:nf_log_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583284720,
      "name": "vsnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1266
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
int vsnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vsnprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583403472,
      "name": "vsnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2002",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/kmod.c:__request_module",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/printk/printk.c:dump_stack_set_arch_desc",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "mm/slub.c:slab_err",
        "fs/dcache.c:dynamic_dname",
        "fs/seq_file.c:seq_vprintf",
        "fs/coredump.c:cn_vprintf",
        "security/tomoyo/audit.c:tomoyo_write_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_addprintf",
        "lib/kobject_uevent.c:add_uevent_var",
        "lib/seq_buf.c:seq_buf_vprintf",
        "lib/vsprintf.c:sprintf",
        "lib/vsprintf.c:vsprintf",
        "lib/vsprintf.c:scnprintf",
        "lib/vsprintf.c:snprintf",
        "lib/vsprintf.c:pointer",
        "lib/kasprintf.c:kvasprintf",
        "lib/kasprintf.c:kvasprintf",
        "drivers/pnp/interface.c:pnp_printf",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg",
        "net/netfilter/nf_log.c:nf_log_buf_add",
        "net/netfilter/nf_log.c:nf_log_trace",
        "net/netfilter/nf_log.c:nf_log_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583403472,
      "name": "vsnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1266
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
int vsnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vsnprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588259776,
      "name": "vsnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2142",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/kmod.c:__request_module",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/printk/printk.c:dump_stack_set_arch_desc",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "mm/slub.c:slab_err",
        "fs/dcache.c:dynamic_dname",
        "fs/seq_file.c:seq_vprintf",
        "fs/coredump.c:cn_vprintf",
        "fs/configfs/item.c:config_item_set_name",
        "fs/configfs/item.c:config_item_set_name",
        "security/tomoyo/audit.c:tomoyo_write_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_addprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/kasprintf.c:kvasprintf",
        "drivers/pnp/interface.c:pnp_printf",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg",
        "net/netfilter/nf_log.c:nf_log_buf_add",
        "net/netfilter/nf_log.c:nf_log_trace",
        "net/netfilter/nf_log.c:nf_log_packet",
        "lib/kobject_uevent.c:add_uevent_var",
        "lib/seq_buf.c:seq_buf_vprintf",
        "lib/vsprintf.c:sprintf",
        "lib/vsprintf.c:vsprintf",
        "lib/vsprintf.c:scnprintf",
        "lib/vsprintf.c:snprintf",
        "lib/vsprintf.c:pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588259776,
      "name": "vsnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1229
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
int vsnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vsnprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588811776,
      "name": "vsnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2240",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/kmod.c:__request_module",
        "kernel/printk/printk.c:dump_stack_set_arch_desc",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "mm/slub.c:slab_err",
        "fs/dcache.c:dynamic_dname",
        "fs/seq_file.c:seq_vprintf",
        "fs/coredump.c:cn_vprintf",
        "fs/configfs/item.c:config_item_set_name",
        "fs/configfs/item.c:config_item_set_name",
        "security/tomoyo/audit.c:tomoyo_write_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_addprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/kasprintf.c:kvasprintf",
        "drivers/pnp/interface.c:pnp_printf",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset",
        "net/netfilter/nf_log.c:nf_log_buf_add",
        "net/netfilter/nf_log.c:nf_log_trace",
        "net/netfilter/nf_log.c:nf_log_packet",
        "lib/kobject_uevent.c:add_uevent_var",
        "lib/seq_buf.c:seq_buf_vprintf",
        "lib/vsprintf.c:sprintf",
        "lib/vsprintf.c:vsprintf",
        "lib/vsprintf.c:scnprintf",
        "lib/vsprintf.c:snprintf",
        "lib/vsprintf.c:pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588811776,
      "name": "vsnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1241
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
int vsnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vsnprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589188640,
      "name": "vsnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2226",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/kmod.c:__request_module",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "mm/slub.c:slab_err",
        "fs/seq_file.c:seq_vprintf",
        "fs/d_path.c:dynamic_dname",
        "fs/coredump.c:cn_vprintf",
        "fs/configfs/item.c:config_item_set_name",
        "fs/configfs/item.c:config_item_set_name",
        "security/tomoyo/audit.c:tomoyo_write_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_addprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/kasprintf.c:kvasprintf",
        "drivers/pnp/interface.c:pnp_printf",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset",
        "net/netfilter/nf_log.c:nf_log_buf_add",
        "net/netfilter/nf_log.c:nf_log_trace",
        "net/netfilter/nf_log.c:nf_log_packet",
        "lib/dump_stack.c:dump_stack_set_arch_desc",
        "lib/kobject_uevent.c:add_uevent_var",
        "lib/seq_buf.c:seq_buf_vprintf",
        "lib/vsprintf.c:sprintf",
        "lib/vsprintf.c:vsprintf",
        "lib/vsprintf.c:scnprintf",
        "lib/vsprintf.c:snprintf",
        "lib/vsprintf.c:pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589188640,
      "name": "vsnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1183
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
int vsnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vsnprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589419424,
      "name": "vsnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2354",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/kmod.c:__request_module",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "mm/slub.c:slab_err",
        "fs/seq_file.c:seq_vprintf",
        "fs/d_path.c:dynamic_dname",
        "fs/coredump.c:cn_vprintf",
        "fs/configfs/item.c:config_item_set_name",
        "security/tomoyo/audit.c:tomoyo_write_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_addprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/kasprintf.c:kvasprintf",
        "drivers/pnp/interface.c:pnp_printf",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset",
        "net/netfilter/nf_log.c:nf_log_buf_add",
        "net/netfilter/nf_log.c:nf_log_trace",
        "net/netfilter/nf_log.c:nf_log_packet",
        "lib/dump_stack.c:dump_stack_set_arch_desc",
        "lib/kobject_uevent.c:add_uevent_var",
        "lib/seq_buf.c:seq_buf_vprintf",
        "lib/vsprintf.c:sprintf",
        "lib/vsprintf.c:vsprintf",
        "lib/vsprintf.c:scnprintf",
        "lib/vsprintf.c:snprintf",
        "lib/vsprintf.c:pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589419424,
      "name": "vsnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1306
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
int vsnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vsnprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589876912,
      "name": "vsnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2461",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/kmod.c:__request_module",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "mm/slub.c:slab_err",
        "fs/seq_file.c:seq_vprintf",
        "fs/d_path.c:dynamic_dname",
        "fs/coredump.c:cn_vprintf",
        "fs/configfs/item.c:config_item_set_name",
        "security/tomoyo/audit.c:tomoyo_write_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_addprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/kasprintf.c:kvasprintf",
        "drivers/pnp/interface.c:pnp_printf",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset",
        "net/netfilter/nf_log.c:nf_log_buf_add",
        "net/netfilter/nf_log.c:nf_log_trace",
        "net/netfilter/nf_log.c:nf_log_packet",
        "lib/dump_stack.c:dump_stack_set_arch_desc",
        "lib/kobject_uevent.c:add_uevent_var",
        "lib/seq_buf.c:seq_buf_vprintf",
        "lib/vsprintf.c:sprintf",
        "lib/vsprintf.c:vsprintf",
        "lib/vsprintf.c:scnprintf",
        "lib/vsprintf.c:snprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589876912,
      "name": "vsnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1247
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
int vsnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vsnprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590102832,
      "name": "vsnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2468",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/kmod.c:__request_module",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "mm/slub.c:slab_err",
        "fs/seq_file.c:seq_vprintf",
        "fs/d_path.c:dynamic_dname",
        "fs/coredump.c:cn_vprintf",
        "fs/configfs/item.c:config_item_set_name",
        "security/tomoyo/audit.c:tomoyo_write_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_addprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/kasprintf.c:kvasprintf",
        "drivers/pnp/interface.c:pnp_printf",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset",
        "drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name",
        "net/netfilter/nf_log.c:nf_log_buf_add",
        "net/netfilter/nf_log.c:nf_log_trace",
        "net/netfilter/nf_log.c:nf_log_packet",
        "lib/dump_stack.c:dump_stack_set_arch_desc",
        "lib/kobject_uevent.c:add_uevent_var",
        "lib/seq_buf.c:seq_buf_vprintf",
        "lib/vsprintf.c:sprintf",
        "lib/vsprintf.c:vsprintf",
        "lib/vsprintf.c:scnprintf",
        "lib/vsprintf.c:snprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590102832,
      "name": "vsnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1247
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
int vsnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vsnprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585105744,
      "name": "vsnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2578",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/kmod.c:__request_module",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "mm/slub.c:slab_err",
        "fs/seq_file.c:seq_printf",
        "fs/d_path.c:dynamic_dname",
        "fs/coredump.c:cn_vprintf",
        "fs/configfs/item.c:config_item_set_name",
        "security/tomoyo/audit.c:tomoyo_write_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_addprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/dump_stack.c:dump_stack_set_arch_desc",
        "lib/kobject_uevent.c:add_uevent_var",
        "lib/seq_buf.c:seq_buf_printf",
        "lib/vsprintf.c:sprintf",
        "lib/vsprintf.c:vsprintf",
        "lib/vsprintf.c:scnprintf",
        "lib/vsprintf.c:snprintf",
        "drivers/pnp/interface.c:pnp_printf",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset",
        "drivers/leds/led-triggers.c:led_trigger_snprintf",
        "drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name",
        "net/netfilter/nf_log.c:nf_log_buf_add",
        "net/netfilter/nf_log.c:nf_log_trace",
        "net/netfilter/nf_log.c:nf_log_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585105744,
      "name": "vsnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1247
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
int vsnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vsnprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585254928,
      "name": "vsnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2577",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/kmod.c:__request_module",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/trace/bpf_trace.c:bpf_do_trace_printk",
        "kernel/bpf/btf.c:btf_snprintf_show",
        "mm/slub.c:slab_err",
        "fs/seq_file.c:seq_printf",
        "fs/d_path.c:dynamic_dname",
        "fs/coredump.c:cn_vprintf",
        "fs/configfs/item.c:config_item_set_name",
        "security/tomoyo/audit.c:tomoyo_write_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_addprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/dump_stack.c:dump_stack_set_arch_desc",
        "lib/kobject_uevent.c:add_uevent_var",
        "lib/seq_buf.c:seq_buf_printf",
        "lib/vsprintf.c:sprintf",
        "lib/vsprintf.c:vsprintf",
        "lib/vsprintf.c:scnprintf",
        "lib/vsprintf.c:snprintf",
        "drivers/pnp/interface.c:pnp_printf",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset",
        "drivers/leds/led-triggers.c:led_trigger_snprintf",
        "drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name",
        "net/netfilter/nf_log.c:nf_log_buf_add",
        "net/netfilter/nf_log.c:nf_log_trace",
        "net/netfilter/nf_log.c:nf_log_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585254928,
      "name": "vsnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1247
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
int vsnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vsnprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585138352,
      "name": "vsnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2708",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/kmod.c:__request_module",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/bpf/btf.c:btf_snprintf_show",
        "mm/slub.c:slab_err",
        "fs/seq_file.c:seq_printf",
        "fs/d_path.c:dynamic_dname",
        "fs/coredump.c:cn_vprintf",
        "fs/configfs/item.c:config_item_set_name",
        "security/tomoyo/audit.c:tomoyo_write_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_addprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/dump_stack.c:dump_stack_set_arch_desc",
        "lib/kobject_uevent.c:add_uevent_var",
        "lib/seq_buf.c:seq_buf_printf",
        "lib/vsprintf.c:sprintf",
        "lib/vsprintf.c:vsprintf",
        "lib/vsprintf.c:scnprintf",
        "lib/vsprintf.c:snprintf",
        "drivers/pnp/interface.c:pnp_printf",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset",
        "drivers/leds/led-triggers.c:led_trigger_snprintf",
        "drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name",
        "net/ethtool/ioctl.c:ethtool_sprintf",
        "net/netfilter/nf_log.c:nf_log_buf_add",
        "net/netfilter/nf_log.c:nf_log_trace",
        "net/netfilter/nf_log.c:nf_log_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585138352,
      "name": "vsnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1347
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
int vsnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vsnprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585588752,
      "name": "vsnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2727",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/kmod.c:__request_module",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/trace/trace_boot.c:append_printf",
        "kernel/bpf/btf.c:btf_snprintf_show",
        "mm/slub.c:slab_err",
        "fs/seq_file.c:seq_printf",
        "fs/d_path.c:dynamic_dname",
        "fs/coredump.c:cn_vprintf",
        "fs/configfs/item.c:config_item_set_name",
        "security/tomoyo/audit.c:tomoyo_write_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_addprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/dump_stack.c:dump_stack_set_arch_desc",
        "lib/kobject_uevent.c:add_uevent_var",
        "lib/seq_buf.c:seq_buf_printf",
        "lib/vsprintf.c:sprintf",
        "lib/vsprintf.c:vsprintf",
        "lib/vsprintf.c:scnprintf",
        "lib/vsprintf.c:snprintf",
        "drivers/pnp/interface.c:pnp_printf",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset",
        "drivers/leds/led-triggers.c:led_trigger_snprintf",
        "drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name",
        "net/ethtool/ioctl.c:ethtool_sprintf",
        "net/netfilter/nf_log.c:nf_log_buf_add",
        "net/netfilter/nf_log.c:nf_log_trace",
        "net/netfilter/nf_log.c:nf_log_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585588752,
      "name": "vsnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1347
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
int vsnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vsnprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586744464,
      "name": "vsnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2712",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/kmod.c:__request_module",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/trace/trace_boot.c:append_printf",
        "kernel/bpf/btf.c:btf_snprintf_show",
        "mm/backing-dev.c:bdi_register_va",
        "mm/slub.c:slab_err",
        "fs/seq_file.c:seq_printf",
        "fs/d_path.c:dynamic_dname",
        "fs/coredump.c:cn_vprintf",
        "fs/configfs/item.c:config_item_set_name",
        "security/tomoyo/audit.c:tomoyo_write_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_addprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/dump_stack.c:dump_stack_set_arch_desc",
        "lib/kobject_uevent.c:add_uevent_var",
        "lib/seq_buf.c:seq_buf_printf",
        "lib/vsprintf.c:sprintf",
        "lib/vsprintf.c:vsprintf",
        "lib/vsprintf.c:scnprintf",
        "lib/vsprintf.c:snprintf",
        "drivers/pnp/interface.c:pnp_printf",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset",
        "drivers/leds/led-triggers.c:led_trigger_snprintf",
        "drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name",
        "net/ethtool/ioctl.c:ethtool_sprintf",
        "net/netfilter/nf_log.c:nf_log_buf_add",
        "net/netfilter/nf_log.c:nf_log_trace",
        "net/netfilter/nf_log.c:nf_log_packet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586744464,
      "name": "vsnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1337
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
int vsnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vsnprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595908032,
      "name": "vsnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2726",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/kmod.c:__request_module",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/trace/trace_boot.c:append_printf",
        "kernel/bpf/btf.c:btf_snprintf_show",
        "mm/backing-dev.c:bdi_register_va",
        "mm/slub.c:slab_err",
        "fs/seq_file.c:seq_printf",
        "fs/d_path.c:dynamic_dname",
        "fs/coredump.c:cn_vprintf",
        "fs/configfs/item.c:config_item_set_name",
        "security/tomoyo/audit.c:tomoyo_write_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_addprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/kasprintf.c:kvasprintf",
        "drivers/pnp/interface.c:pnp_printf",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_get_offsets_xhci_log_msg",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset",
        "drivers/leds/led-triggers.c:led_trigger_snprintf",
        "drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name",
        "net/ethtool/ioctl.c:ethtool_sprintf",
        "net/netfilter/nf_log.c:nf_log_buf_add",
        "net/netfilter/nf_log.c:nf_log_trace",
        "net/netfilter/nf_log.c:nf_log_packet",
        "lib/dump_stack.c:dump_stack_set_arch_desc",
        "lib/kobject_uevent.c:add_uevent_var",
        "lib/seq_buf.c:seq_buf_printf",
        "lib/vsprintf.c:sprintf",
        "lib/vsprintf.c:vsprintf",
        "lib/vsprintf.c:scnprintf",
        "lib/vsprintf.c:snprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595908032,
      "name": "vsnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1326
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
int vsnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vsnprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596425696,
      "name": "vsnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2747",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/module/kmod.c:__request_module",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/trace/trace_boot.c:append_printf",
        "kernel/bpf/btf.c:btf_snprintf_show",
        "mm/backing-dev.c:bdi_register_va",
        "mm/slub.c:slab_err",
        "fs/seq_file.c:seq_printf",
        "fs/d_path.c:dynamic_dname",
        "fs/coredump.c:cn_vprintf",
        "fs/configfs/item.c:config_item_set_name",
        "security/tomoyo/audit.c:tomoyo_write_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_addprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/kasprintf.c:kvasprintf",
        "drivers/pnp/interface.c:pnp_printf",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_get_offsets_xhci_log_msg",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset",
        "drivers/leds/led-triggers.c:led_trigger_snprintf",
        "drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name",
        "net/ethtool/ioctl.c:ethtool_sprintf",
        "net/netfilter/nf_log.c:nf_log_buf_add",
        "net/netfilter/nf_log.c:nf_log_trace",
        "net/netfilter/nf_log.c:nf_log_packet",
        "lib/dump_stack.c:dump_stack_set_arch_desc",
        "lib/kobject_uevent.c:add_uevent_var",
        "lib/seq_buf.c:seq_buf_printf",
        "lib/vsprintf.c:sprintf",
        "lib/vsprintf.c:vsprintf",
        "lib/vsprintf.c:scnprintf",
        "lib/vsprintf.c:snprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596425696,
      "name": "vsnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1382
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
int vsnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vsnprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597321056,
      "name": "vsnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2754",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/module/kmod.c:__request_module",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/trace/trace_boot.c:append_printf",
        "kernel/bpf/btf.c:btf_snprintf_show",
        "mm/backing-dev.c:bdi_register_va",
        "mm/slub.c:slab_err",
        "fs/seq_file.c:seq_printf",
        "fs/d_path.c:dynamic_dname",
        "fs/coredump.c:cn_vprintf",
        "fs/configfs/item.c:config_item_set_name",
        "security/tomoyo/audit.c:tomoyo_write_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_addprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/kasprintf.c:kvasprintf",
        "drivers/pnp/interface.c:pnp_printf",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_get_offsets_xhci_log_msg",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset",
        "drivers/leds/led-triggers.c:led_trigger_snprintf",
        "drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name",
        "net/ethtool/ioctl.c:ethtool_sprintf",
        "net/netfilter/nf_log.c:nf_log_buf_add",
        "net/netfilter/nf_log.c:nf_log_trace",
        "net/netfilter/nf_log.c:nf_log_packet",
        "lib/dump_stack.c:dump_stack_set_arch_desc",
        "lib/kobject_uevent.c:add_uevent_var",
        "lib/seq_buf.c:seq_buf_printf",
        "lib/vsprintf.c:sprintf",
        "lib/vsprintf.c:vsprintf",
        "lib/vsprintf.c:scnprintf",
        "lib/vsprintf.c:snprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597321056,
      "name": "vsnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1382
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
int vsnprintf(char * buf, size_t size, const char * fmt, va_list args)
```

```json
{
  "name": "vsnprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503880192,
      "name": "vsnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2468",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/kmod.c:__request_module",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "mm/slub.c:slab_err",
        "fs/seq_file.c:seq_vprintf",
        "fs/d_path.c:dynamic_dname",
        "fs/coredump.c:cn_vprintf",
        "fs/configfs/item.c:config_item_set_name",
        "security/tomoyo/audit.c:tomoyo_write_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_addprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/kasprintf.c:kvasprintf",
        "drivers/pnp/interface.c:pnp_printf",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset",
        "drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name",
        "net/netfilter/nf_log.c:nf_log_buf_add",
        "net/netfilter/nf_log.c:nf_log_trace",
        "net/netfilter/nf_log.c:nf_log_packet",
        "lib/dump_stack.c:dump_stack_set_arch_desc",
        "lib/kobject_uevent.c:add_uevent_var",
        "lib/seq_buf.c:seq_buf_vprintf",
        "lib/vsprintf.c:sprintf",
        "lib/vsprintf.c:vsprintf",
        "lib/vsprintf.c:scnprintf",
        "lib/vsprintf.c:snprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503880192,
      "name": "vsnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1820
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
int vsnprintf(char * buf, size_t size, const char * fmt, va_list args)
```

```json
{
  "name": "vsnprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236512420,
      "name": "vsnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2468",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/setup.c:early_print",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/kmod.c:__request_module",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "mm/slub.c:slab_err",
        "fs/seq_file.c:seq_vprintf",
        "fs/d_path.c:dynamic_dname",
        "fs/coredump.c:cn_vprintf",
        "fs/configfs/item.c:config_item_set_name",
        "security/tomoyo/audit.c:tomoyo_write_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_addprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/kasprintf.c:kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset",
        "drivers/usb/musb/musb_trace.c:perf_trace_musb_log",
        "drivers/usb/musb/musb_trace.c:trace_event_raw_event_musb_log",
        "drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name",
        "sound/soc/soc-dapm.c:pop_dbg",
        "net/netfilter/nf_log.c:nf_log_buf_add",
        "net/netfilter/nf_log.c:nf_log_trace",
        "net/netfilter/nf_log.c:nf_log_packet",
        "lib/dump_stack.c:dump_stack_set_arch_desc",
        "lib/kobject_uevent.c:add_uevent_var",
        "lib/seq_buf.c:seq_buf_vprintf",
        "lib/vsprintf.c:sprintf",
        "lib/vsprintf.c:vsprintf",
        "lib/vsprintf.c:scnprintf",
        "lib/vsprintf.c:snprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236512420,
      "name": "vsnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1028
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
int vsnprintf(char * buf, size_t size, const char * fmt, va_list args)
```

```json
{
  "name": "vsnprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297748480,
      "name": "vsnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2468",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/udbg.c:udbg_printf",
        "arch/powerpc/xmon/nonstdio.c:xmon_printf",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/kmod.c:__request_module",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "mm/slub.c:slab_err",
        "fs/seq_file.c:seq_vprintf",
        "fs/d_path.c:dynamic_dname",
        "fs/coredump.c:cn_vprintf",
        "fs/configfs/item.c:config_item_set_name",
        "security/tomoyo/audit.c:tomoyo_write_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_addprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/kasprintf.c:kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset",
        "drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name",
        "net/netfilter/nf_log.c:nf_log_buf_add",
        "net/netfilter/nf_log.c:nf_log_trace",
        "net/netfilter/nf_log.c:nf_log_packet",
        "lib/dump_stack.c:dump_stack_set_arch_desc",
        "lib/kobject_uevent.c:add_uevent_var",
        "lib/seq_buf.c:seq_buf_vprintf",
        "lib/vsprintf.c:sprintf",
        "lib/vsprintf.c:vsprintf",
        "lib/vsprintf.c:scnprintf",
        "lib/vsprintf.c:snprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297748480,
      "name": "vsnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1268
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
int vsnprintf(char * buf, size_t size, const char * fmt, va_list args)
```

```json
{
  "name": "vsnprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279776130,
      "name": "vsnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2468",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/kmod.c:__request_module",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "mm/slub.c:slab_err",
        "fs/seq_file.c:seq_vprintf",
        "fs/d_path.c:dynamic_dname",
        "fs/coredump.c:cn_vprintf",
        "fs/configfs/item.c:config_item_set_name",
        "security/tomoyo/audit.c:tomoyo_write_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_addprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/kasprintf.c:kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset",
        "net/netfilter/nf_log.c:nf_log_buf_add",
        "net/netfilter/nf_log.c:nf_log_trace",
        "net/netfilter/nf_log.c:nf_log_packet",
        "lib/dump_stack.c:dump_stack_set_arch_desc",
        "lib/kobject_uevent.c:add_uevent_var",
        "lib/seq_buf.c:seq_buf_vprintf",
        "lib/vsprintf.c:sprintf",
        "lib/vsprintf.c:vsprintf",
        "lib/vsprintf.c:scnprintf",
        "lib/vsprintf.c:snprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279776130,
      "name": "vsnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 782
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
int vsnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vsnprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589705088,
      "name": "vsnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2468",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/kmod.c:__request_module",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "mm/slub.c:slab_err",
        "fs/seq_file.c:seq_vprintf",
        "fs/d_path.c:dynamic_dname",
        "fs/coredump.c:cn_vprintf",
        "fs/configfs/item.c:config_item_set_name",
        "security/tomoyo/audit.c:tomoyo_write_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_addprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/kasprintf.c:kvasprintf",
        "drivers/pnp/interface.c:pnp_printf",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset",
        "drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name",
        "net/netfilter/nf_log.c:nf_log_buf_add",
        "net/netfilter/nf_log.c:nf_log_trace",
        "net/netfilter/nf_log.c:nf_log_packet",
        "lib/dump_stack.c:dump_stack_set_arch_desc",
        "lib/kobject_uevent.c:add_uevent_var",
        "lib/seq_buf.c:seq_buf_vprintf",
        "lib/vsprintf.c:sprintf",
        "lib/vsprintf.c:vsprintf",
        "lib/vsprintf.c:scnprintf",
        "lib/vsprintf.c:snprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589705088,
      "name": "vsnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1247
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
int vsnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vsnprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589430880,
      "name": "vsnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2468",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/kmod.c:__request_module",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "mm/slub.c:slab_err",
        "fs/seq_file.c:seq_vprintf",
        "fs/d_path.c:dynamic_dname",
        "fs/coredump.c:cn_vprintf",
        "fs/configfs/item.c:config_item_set_name",
        "security/tomoyo/audit.c:tomoyo_write_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_addprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/kasprintf.c:kvasprintf",
        "drivers/pnp/interface.c:pnp_printf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset",
        "net/netfilter/nf_log.c:nf_log_buf_add",
        "net/netfilter/nf_log.c:nf_log_trace",
        "net/netfilter/nf_log.c:nf_log_packet",
        "lib/dump_stack.c:dump_stack_set_arch_desc",
        "lib/kobject_uevent.c:add_uevent_var",
        "lib/seq_buf.c:seq_buf_vprintf",
        "lib/vsprintf.c:sprintf",
        "lib/vsprintf.c:vsprintf",
        "lib/vsprintf.c:scnprintf",
        "lib/vsprintf.c:snprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589430880,
      "name": "vsnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1247
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
int vsnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vsnprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590148464,
      "name": "vsnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2468",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/kmod.c:__request_module",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "mm/slub.c:slab_err",
        "fs/seq_file.c:seq_vprintf",
        "fs/d_path.c:dynamic_dname",
        "fs/coredump.c:cn_vprintf",
        "fs/configfs/item.c:config_item_set_name",
        "security/tomoyo/audit.c:tomoyo_write_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_addprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/kasprintf.c:kvasprintf",
        "drivers/pnp/interface.c:pnp_printf",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset",
        "net/netfilter/nf_log.c:nf_log_buf_add",
        "net/netfilter/nf_log.c:nf_log_trace",
        "net/netfilter/nf_log.c:nf_log_packet",
        "lib/dump_stack.c:dump_stack_set_arch_desc",
        "lib/kobject_uevent.c:add_uevent_var",
        "lib/seq_buf.c:seq_buf_vprintf",
        "lib/vsprintf.c:sprintf",
        "lib/vsprintf.c:vsprintf",
        "lib/vsprintf.c:scnprintf",
        "lib/vsprintf.c:snprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590148464,
      "name": "vsnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1247
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
int vsnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vsnprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590198864,
      "name": "vsnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2468",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:alloc_workqueue",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/kmod.c:__request_module",
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_vformat",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "mm/slub.c:slab_err",
        "fs/seq_file.c:seq_vprintf",
        "fs/d_path.c:dynamic_dname",
        "fs/coredump.c:cn_vprintf",
        "fs/configfs/item.c:config_item_set_name",
        "security/tomoyo/audit.c:tomoyo_write_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_io_printf",
        "security/tomoyo/common.c:tomoyo_addprintf",
        "lib/kasprintf.c:kvasprintf",
        "lib/kasprintf.c:kvasprintf",
        "drivers/pnp/interface.c:pnp_printf",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/base/devres.c:devm_kvasprintf",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset",
        "drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name",
        "net/netfilter/nf_log.c:nf_log_buf_add",
        "net/netfilter/nf_log.c:nf_log_trace",
        "net/netfilter/nf_log.c:nf_log_packet",
        "lib/dump_stack.c:dump_stack_set_arch_desc",
        "lib/kobject_uevent.c:add_uevent_var",
        "lib/seq_buf.c:seq_buf_vprintf",
        "lib/vsprintf.c:sprintf",
        "lib/vsprintf.c:vsprintf",
        "lib/vsprintf.c:scnprintf",
        "lib/vsprintf.c:snprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590198864,
      "name": "vsnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1247
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
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
