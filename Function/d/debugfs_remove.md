# Function: <code>debugfs_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void debugfs_remove(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582111552,
      "name": "debugfs_remove",
      "external": true,
      "loc": "fs/debugfs/inode.c:551",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:blk_remove_buf_file_callback",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/mfd/ab3100-core.c:ab3100_remove",
        "drivers/mfd/ab3100-core.c:ab3100_remove",
        "drivers/mfd/ab3100-core.c:ab3100_remove",
        "drivers/mfd/ab3100-core.c:ab3100_remove",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/usb/core/usb.c:usb_debugfs_cleanup",
        "drivers/usb/core/usb.c:usb_debugfs_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582111552,
      "name": "debugfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void debugfs_remove(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582327264,
      "name": "debugfs_remove",
      "external": true,
      "loc": "fs/debugfs/inode.c:615",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:blk_remove_buf_file_callback",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/mfd/ab3100-core.c:ab3100_remove",
        "drivers/mfd/ab3100-core.c:ab3100_remove",
        "drivers/mfd/ab3100-core.c:ab3100_remove",
        "drivers/mfd/ab3100-core.c:ab3100_remove",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/usb/core/usb.c:usb_debugfs_cleanup",
        "drivers/usb/core/usb.c:usb_debugfs_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582327264,
      "name": "debugfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void debugfs_remove(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582418064,
      "name": "debugfs_remove",
      "external": true,
      "loc": "fs/debugfs/inode.c:615",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:blk_remove_buf_file_callback",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_enable",
        "drivers/usb/core/usb.c:usb_debugfs_cleanup",
        "drivers/usb/core/usb.c:usb_debugfs_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582418064,
      "name": "debugfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void debugfs_remove(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582501616,
      "name": "debugfs_remove",
      "external": true,
      "loc": "fs/debugfs/inode.c:649",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:blk_remove_buf_file_callback",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/usb/core/usb.c:usb_debugfs_cleanup",
        "drivers/usb/core/usb.c:usb_debugfs_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_unregister_driver",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_unregister_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582501616,
      "name": "debugfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void debugfs_remove(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582652944,
      "name": "debugfs_remove",
      "external": true,
      "loc": "fs/debugfs/inode.c:677",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:blk_remove_buf_file_callback",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/usb/core/usb.c:usb_debugfs_cleanup",
        "drivers/usb/core/usb.c:usb_debugfs_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582652944,
      "name": "debugfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void debugfs_remove(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582846528,
      "name": "debugfs_remove",
      "external": true,
      "loc": "fs/debugfs/inode.c:700",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:blk_remove_buf_file_callback",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/acpi/acpi_dbg.c:acpi_aml_exit",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/component.c:free_master",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582846528,
      "name": "debugfs_remove",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void debugfs_remove(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582954928,
      "name": "debugfs_remove",
      "external": true,
      "loc": "fs/debugfs/inode.c:703",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:debugfs_kprobe_init",
        "kernel/trace/blktrace.c:blk_remove_buf_file_callback",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "lib/error-inject.c:init_error_injection",
        "lib/dynamic_debug.c:dynamic_debug_init_debugfs",
        "drivers/acpi/acpi_dbg.c:acpi_aml_exit",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/component.c:free_master",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582954928,
      "name": "debugfs_remove",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void debugfs_remove(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583135376,
      "name": "debugfs_remove",
      "external": true,
      "loc": "fs/debugfs/inode.c:723",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_remove_buf_file_callback",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "lib/error-inject.c:init_error_injection",
        "drivers/acpi/acpi_dbg.c:acpi_aml_exit",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/component.c:free_master",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583135376,
      "name": "debugfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void debugfs_remove(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583241552,
      "name": "debugfs_remove",
      "external": true,
      "loc": "fs/debugfs/inode.c:725",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_remove_buf_file_callback",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "lib/error-inject.c:init_error_injection",
        "drivers/acpi/acpi_dbg.c:acpi_aml_exit",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/component.c:free_master",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583241552,
      "name": "debugfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void debugfs_remove(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583568112,
      "name": "debugfs_remove",
      "external": true,
      "loc": "fs/debugfs/inode.c:697",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/trace/blktrace.c:blk_remove_buf_file_callback",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "mm/backing-dev.c:bdi_unregister",
        "mm/zswap.c:zswap_debugfs_exit",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister",
        "lib/error-inject.c:init_error_injection",
        "drivers/acpi/acpi_dbg.c:acpi_aml_exit",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/component.c:free_master",
        "drivers/base/dd.c:deferred_probe_exit",
        "drivers/base/power/domain.c:genpd_debug_exit",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/usb/common/common.c:usb_common_exit",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:release_uhci",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_migrate_dentry",
        "drivers/opp/debugfs.c:opp_debug_remove_one",
        "drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_remove",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file",
        "drivers/ras/cec.c:create_debugfs_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583568112,
      "name": "debugfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void debugfs_remove(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583688560,
      "name": "debugfs_remove",
      "external": true,
      "loc": "fs/debugfs/inode.c:722",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/trace/blktrace.c:blk_remove_buf_file_callback",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "mm/backing-dev.c:bdi_unregister",
        "mm/zswap.c:zswap_debugfs_exit",
        "block/blk-sysfs.c:blk_release_queue",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs",
        "lib/error-inject.c:init_error_injection",
        "drivers/acpi/acpi_dbg.c:acpi_aml_exit",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:destroy_regulator",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/component.c:free_master",
        "drivers/base/dd.c:deferred_probe_exit",
        "drivers/base/power/domain.c:genpd_debug_exit",
        "drivers/base/power/domain.c:genpd_remove",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/usb/common/common.c:usb_common_exit",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:release_uhci",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_migrate_dentry",
        "drivers/opp/debugfs.c:opp_debug_remove_one",
        "drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_remove",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file",
        "drivers/ras/cec.c:create_debugfs_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583688560,
      "name": "debugfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void debugfs_remove(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583713072,
      "name": "debugfs_remove",
      "external": true,
      "loc": "fs/debugfs/inode.c:726",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/sched/debug.c:update_sched_domain_debugfs",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:blk_trace_shutdown",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:blk_remove_buf_file_callback",
        "kernel/trace/blktrace.c:blk_trace_remove",
        "mm/backing-dev.c:bdi_unregister",
        "mm/zswap.c:zswap_debugfs_exit",
        "block/blk-sysfs.c:blk_release_queue",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs",
        "lib/error-inject.c:init_error_injection",
        "drivers/acpi/acpi_dbg.c:acpi_aml_exit",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/component.c:free_master",
        "drivers/base/dd.c:deferred_probe_exit",
        "drivers/base/power/domain.c:genpd_debug_exit",
        "drivers/base/power/domain.c:genpd_remove",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/usb/common/common.c:usb_common_exit",
        "drivers/usb/core/usb.c:usb_debugfs_cleanup",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_remove_one",
        "drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_remove",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583713072,
      "name": "debugfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void debugfs_remove(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584073280,
      "name": "debugfs_remove",
      "external": true,
      "loc": "fs/debugfs/inode.c:726",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/sched/debug.c:update_sched_domain_debugfs",
        "kernel/trace/blktrace.c:blk_remove_buf_file_callback",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "mm/backing-dev.c:bdi_unregister",
        "mm/slub.c:debugfs_slab_release",
        "block/blk-sysfs.c:blk_release_queue",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_queue_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs",
        "lib/error-inject.c:init_error_injection",
        "drivers/acpi/acpi_dbg.c:acpi_aml_exit",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/component.c:free_master",
        "drivers/base/dd.c:deferred_probe_exit",
        "drivers/base/power/domain.c:genpd_debug_exit",
        "drivers/base/power/domain.c:genpd_remove",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/usb/common/common.c:usb_common_exit",
        "drivers/usb/core/usb.c:usb_debugfs_cleanup",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_remove_one",
        "drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_remove",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584073280,
      "name": "debugfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void debugfs_remove(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584664768,
      "name": "debugfs_remove",
      "external": true,
      "loc": "fs/debugfs/inode.c:736",
      "file": "fs/debugfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/sched/build_utility.c:update_sched_domain_debugfs",
        "kernel/trace/blktrace.c:blk_remove_buf_file_callback",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "mm/backing-dev.c:bdi_unregister",
        "mm/slub.c:debugfs_slab_release",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs",
        "lib/error-inject.c:init_error_injection",
        "drivers/acpi/acpi_dbg.c:acpi_aml_exit",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:_regulator_put",
        "drivers/char/virtio_console.c:virtio_console_fini",
        "drivers/char/virtio_console.c:virtio_console_init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/component.c:free_aggregate_device",
        "drivers/base/dd.c:deferred_probe_exit",
        "drivers/base/power/domain.c:genpd_debug_exit",
        "drivers/base/power/domain.c:genpd_remove",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/net/wwan/wwan_core.c:wwan_exit",
        "drivers/net/wwan/wwan_core.c:wwan_remove_dev",
        "drivers/usb/common/common.c:usb_common_exit",
        "drivers/usb/core/usb.c:usb_debugfs_cleanup",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_remove_one",
        "drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_remove",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file",
        "drivers/ras/cec.c:cec_init",
        "drivers/hte/hte.c:hte_ts_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584664768,
      "name": "debugfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void debugfs_remove(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585349623,
      "name": "debugfs_remove",
      "external": true,
      "loc": "fs/debugfs/inode.c:759",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_lookup_and_remove"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/trace/blktrace.c:blk_remove_buf_file_callback",
        "kernel/trace/blktrace.c:blk_trace_free",
        "mm/backing-dev.c:bdi_unregister",
        "mm/slub.c:debugfs_slab_release",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs",
        "lib/error-inject.c:init_error_injection",
        "drivers/acpi/acpi_dbg.c:acpi_aml_exit",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/regulator/core.c:regulator_dev_release",
        "drivers/regulator/core.c:_regulator_put",
        "drivers/char/virtio_console.c:virtio_console_fini",
        "drivers/char/virtio_console.c:virtio_console_init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/power/domain.c:genpd_debug_exit",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/net/wwan/wwan_core.c:wwan_exit",
        "drivers/net/wwan/wwan_core.c:wwan_remove_dev",
        "drivers/usb/common/common.c:usb_common_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_remove_one",
        "drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_remove",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file",
        "drivers/ras/cec.c:cec_init",
        "drivers/hte/hte.c:hte_ts_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585347104,
      "name": "debugfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void debugfs_remove(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585579783,
      "name": "debugfs_remove",
      "external": true,
      "loc": "fs/debugfs/inode.c:759",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_lookup_and_remove"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/sched/build_utility.c:sched_verbose_write",
        "kernel/trace/blktrace.c:blk_remove_buf_file_callback",
        "kernel/trace/blktrace.c:blk_trace_free",
        "mm/backing-dev.c:bdi_unregister",
        "crypto/jitterentropy-testing.c:jent_testing_exit",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs",
        "lib/error-inject.c:init_error_injection",
        "drivers/phy/phy-core.c:phy_core_exit",
        "drivers/phy/phy-core.c:phy_release",
        "drivers/acpi/acpi_dbg.c:acpi_aml_exit",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/regulator/core.c:regulator_dev_release",
        "drivers/regulator/core.c:_regulator_put",
        "drivers/char/virtio_console.c:virtio_console_fini",
        "drivers/char/virtio_console.c:virtio_console_init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/power/domain.c:genpd_debug_exit",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/net/wwan/wwan_core.c:wwan_exit",
        "drivers/net/wwan/wwan_core.c:wwan_remove_dev",
        "drivers/usb/common/common.c:usb_common_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_remove_one",
        "drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_remove",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file",
        "drivers/ras/cec.c:cec_init",
        "drivers/hte/hte.c:hte_ts_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585577248,
      "name": "debugfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void debugfs_remove(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585818535,
      "name": "debugfs_remove",
      "external": true,
      "loc": "fs/debugfs/inode.c:806",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/debugfs/inode.c:debugfs_lookup_and_remove"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit",
        "kernel/sched/build_utility.c:sched_verbose_write",
        "kernel/trace/blktrace.c:blk_remove_buf_file_callback",
        "kernel/trace/blktrace.c:blk_trace_free",
        "mm/backing-dev.c:bdi_unregister",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched_hctx",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_rqos",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_sched",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs",
        "lib/error-inject.c:init_error_injection",
        "drivers/phy/phy-core.c:phy_core_exit",
        "drivers/phy/phy-core.c:phy_release",
        "drivers/acpi/acpi_dbg.c:acpi_aml_exit",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/pmdomain/core.c:genpd_debug_exit",
        "drivers/regulator/core.c:regulator_dev_release",
        "drivers/regulator/core.c:_regulator_put",
        "drivers/char/virtio_console.c:virtio_console_fini",
        "drivers/char/virtio_console.c:virtio_console_init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "drivers/gpu/drm/drm_drv.c:drm_core_init",
        "drivers/gpu/drm/drm_debugfs.c:drm_debugfs_encoder_remove",
        "drivers/gpu/drm/drm_debugfs.c:drm_debugfs_crtc_remove",
        "drivers/gpu/drm/drm_debugfs.c:drm_debugfs_connector_remove",
        "drivers/gpu/drm/drm_debugfs.c:drm_debugfs_unregister",
        "drivers/gpu/drm/drm_debugfs.c:drm_debugfs_dev_fini",
        "drivers/gpu/drm/drm_debugfs.c:drm_debugfs_remove_files",
        "drivers/accel/drm_accel.c:accel_core_exit",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_client",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unregister_handler",
        "drivers/usb/common/common.c:usb_common_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_exit",
        "drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_exit",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_slot",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_endpoint",
        "drivers/usb/host/xhci-debugfs.c:xhci_debugfs_remove_root",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/ptp/ptp_clock.c:ptp_clock_release",
        "drivers/ptp/ptp_chardev.c:ptp_release",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_unregister",
        "drivers/opp/debugfs.c:opp_debug_remove_one",
        "drivers/mmc/core/debugfs.c:mmc_remove_card_debugfs",
        "drivers/mmc/core/debugfs.c:mmc_remove_host_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_delete_debug_dir",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file",
        "drivers/ras/cec.c:cec_init",
        "drivers/hte/hte.c:hte_ts_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585815760,
      "name": "debugfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void debugfs_remove(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494965368,
      "name": "debugfs_remove",
      "external": true,
      "loc": "fs/debugfs/inode.c:725",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_remove_buf_file_callback",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "lib/error-inject.c:init_error_injection",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/component.c:free_master",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/mmc/core/block.c:mmc_blk_remove",
        "drivers/mmc/core/block.c:mmc_blk_remove",
        "drivers/firmware/ti_sci.c:ti_sci_remove",
        "drivers/firmware/ti_sci.c:ti_sci_probe",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494965368,
      "name": "debugfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void debugfs_remove(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228373104,
      "name": "debugfs_remove",
      "external": true,
      "loc": "fs/debugfs/inode.c:725",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_remove_buf_file_callback",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/component.c:free_master",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/mmc/core/block.c:mmc_blk_remove",
        "drivers/mmc/core/block.c:mmc_blk_remove",
        "drivers/firmware/tegra/bpmp-debugfs.c:tegra_bpmp_init_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228373104,
      "name": "debugfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void debugfs_remove(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288843808,
      "name": "debugfs_remove",
      "external": true,
      "loc": "fs/debugfs/inode.c:725",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_remove_buf_file_callback",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "lib/error-inject.c:init_error_injection",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/component.c:free_master",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_init",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288843808,
      "name": "debugfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void debugfs_remove(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274266558,
      "name": "debugfs_remove",
      "external": true,
      "loc": "fs/debugfs/inode.c:725",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_remove_buf_file_callback",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/component.c:free_master",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/mmc/core/block.c:mmc_blk_remove",
        "drivers/mmc/core/block.c:mmc_blk_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274266558,
      "name": "debugfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void debugfs_remove(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583210288,
      "name": "debugfs_remove",
      "external": true,
      "loc": "fs/debugfs/inode.c:725",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_remove_buf_file_callback",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "lib/error-inject.c:init_error_injection",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/component.c:free_master",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583210288,
      "name": "debugfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void debugfs_remove(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583147440,
      "name": "debugfs_remove",
      "external": true,
      "loc": "fs/debugfs/inode.c:725",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_remove_buf_file_callback",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "lib/error-inject.c:init_error_injection",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/component.c:free_master",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583147440,
      "name": "debugfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void debugfs_remove(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583194320,
      "name": "debugfs_remove",
      "external": true,
      "loc": "fs/debugfs/inode.c:725",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_remove_buf_file_callback",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "lib/error-inject.c:init_error_injection",
        "drivers/acpi/acpi_dbg.c:acpi_aml_exit",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/component.c:free_master",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583194320,
      "name": "debugfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void debugfs_remove(struct dentry * dentry)
```

```json
{
  "name": "debugfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583288208,
      "name": "debugfs_remove",
      "external": true,
      "loc": "fs/debugfs/inode.c:725",
      "file": "fs/debugfs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_remove_buf_file_callback",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "kernel/trace/blktrace.c:blk_trace_free",
        "lib/error-inject.c:init_error_injection",
        "drivers/acpi/acpi_dbg.c:acpi_aml_exit",
        "drivers/acpi/acpi_dbg.c:acpi_aml_init",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/base/component.c:free_master",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_exit_debugfs",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_remove_trace_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583288208,
      "name": "debugfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
