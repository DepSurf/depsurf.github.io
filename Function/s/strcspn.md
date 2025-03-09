# Function: <code>strcspn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
__kernel_size_t strcspn(const char * s, const char * reject)
```

```json
{
  "name": "strcspn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582980976,
      "name": "strcspn",
      "external": true,
      "loc": "lib/string.c:538",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/params.c:param_array_set",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/printk/printk.c:dump_stack_print_info",
        "kernel/module.c:layout_and_allocate",
        "kernel/hung_task.c:watchdog",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/iommu/intel-iommu.c:intel_iommu_setup",
        "drivers/iommu/irq_remapping.c:setup_irqremap",
        "drivers/base/platform.c:early_platform_driver_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582980976,
      "name": "strcspn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
__kernel_size_t strcspn(const char * s, const char * reject)
```

```json
{
  "name": "strcspn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583270160,
      "name": "strcspn",
      "external": true,
      "loc": "lib/string.c:538",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/params.c:param_array_set",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/printk/printk.c:dump_stack_print_info",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/hung_task.c:watchdog",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/iommu/intel-iommu.c:intel_iommu_setup",
        "drivers/iommu/irq_remapping.c:setup_irqremap",
        "drivers/base/platform.c:early_platform_driver_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583270160,
      "name": "strcspn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
__kernel_size_t strcspn(const char * s, const char * reject)
```

```json
{
  "name": "strcspn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583388928,
      "name": "strcspn",
      "external": true,
      "loc": "lib/string.c:538",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/params.c:param_array_set",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/printk/printk.c:dump_stack_print_info",
        "kernel/module.c:layout_and_allocate",
        "kernel/hung_task.c:watchdog",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/iommu/intel-iommu.c:intel_iommu_setup",
        "drivers/iommu/irq_remapping.c:setup_irqremap",
        "drivers/base/platform.c:early_platform_driver_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583388928,
      "name": "strcspn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
__kernel_size_t strcspn(const char * s, const char * reject)
```

```json
{
  "name": "strcspn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588245360,
      "name": "strcspn",
      "external": true,
      "loc": "lib/string.c:538",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/params.c:param_array_set",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/printk/printk.c:dump_stack_print_info",
        "kernel/module.c:layout_and_allocate",
        "kernel/hung_task.c:watchdog",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/base/platform.c:early_platform_driver_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588245360,
      "name": "strcspn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
__kernel_size_t strcspn(const char * s, const char * reject)
```

```json
{
  "name": "strcspn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588796784,
      "name": "strcspn",
      "external": true,
      "loc": "lib/string.c:539",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/params.c:param_array_set",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/printk/printk.c:dump_stack_print_info",
        "kernel/module.c:layout_and_allocate",
        "kernel/hung_task.c:watchdog",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/base/platform.c:early_platform_driver_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588796784,
      "name": "strcspn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
__kernel_size_t strcspn(const char * s, const char * reject)
```

```json
{
  "name": "strcspn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589174896,
      "name": "strcspn",
      "external": true,
      "loc": "lib/string.c:539",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/params.c:param_array_set",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/module.c:layout_and_allocate",
        "kernel/hung_task.c:watchdog",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/iommu/intel-iommu.c:intel_iommu_setup",
        "drivers/iommu/irq_remapping.c:setup_irqremap",
        "drivers/base/platform.c:early_platform_driver_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589174896,
      "name": "strcspn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
__kernel_size_t strcspn(const char * s, const char * reject)
```

```json
{
  "name": "strcspn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589404816,
      "name": "strcspn",
      "external": true,
      "loc": "lib/string.c:540",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/params.c:param_array_set",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/module.c:load_module",
        "kernel/hung_task.c:watchdog",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/iommu/intel-iommu.c:intel_iommu_setup",
        "drivers/iommu/irq_remapping.c:setup_irqremap",
        "drivers/base/platform.c:early_platform_driver_register",
        "lib/dump_stack.c:dump_stack_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589404816,
      "name": "strcspn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
__kernel_size_t strcspn(const char * s, const char * reject)
```

```json
{
  "name": "strcspn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589860640,
      "name": "strcspn",
      "external": true,
      "loc": "lib/string.c:582",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/params.c:param_array_set",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/module.c:load_module",
        "kernel/hung_task.c:watchdog",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/iommu/intel-iommu.c:intel_iommu_setup",
        "drivers/iommu/irq_remapping.c:setup_irqremap",
        "drivers/base/platform.c:early_platform_driver_register",
        "lib/dump_stack.c:dump_stack_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589860640,
      "name": "strcspn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
__kernel_size_t strcspn(const char * s, const char * reject)
```

```json
{
  "name": "strcspn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590086128,
      "name": "strcspn",
      "external": true,
      "loc": "lib/string.c:584",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "arch/x86/platform/uv/tlb_uv.c:tunables_write",
        "arch/x86/platform/uv/tlb_uv.c:tunables_write",
        "kernel/params.c:param_array_set",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/module.c:load_module",
        "kernel/hung_task.c:watchdog",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/iommu/intel-iommu.c:intel_iommu_setup",
        "drivers/iommu/irq_remapping.c:setup_irqremap",
        "drivers/base/platform.c:early_platform_driver_register",
        "drivers/remoteproc/remoteproc_sysfs.c:firmware_store",
        "lib/dump_stack.c:dump_stack_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590086128,
      "name": "strcspn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
__kernel_size_t strcspn(const char * s, const char * reject)
```

```json
{
  "name": "strcspn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585083952,
      "name": "strcspn",
      "external": true,
      "loc": "lib/string.c:625",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/module.c:blacklisted",
        "kernel/hung_task.c:check_hung_task",
        "lib/dump_stack.c:dump_stack_print_info",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/iommu/intel/iommu.c:intel_iommu_setup",
        "drivers/iommu/irq_remapping.c:setup_irqremap",
        "drivers/remoteproc/remoteproc_sysfs.c:firmware_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585083952,
      "name": "strcspn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
__kernel_size_t strcspn(const char * s, const char * reject)
```

```json
{
  "name": "strcspn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585233120,
      "name": "strcspn",
      "external": true,
      "loc": "lib/string.c:622",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/module.c:blacklisted",
        "kernel/module.c:check_modinfo",
        "kernel/hung_task.c:check_hung_task",
        "lib/dump_stack.c:dump_stack_print_info",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/iommu/intel/iommu.c:intel_iommu_setup",
        "drivers/iommu/irq_remapping.c:setup_irqremap",
        "drivers/remoteproc/remoteproc_core.c:rproc_set_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585233120,
      "name": "strcspn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
__kernel_size_t strcspn(const char * s, const char * reject)
```

```json
{
  "name": "strcspn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585116000,
      "name": "strcspn",
      "external": true,
      "loc": "lib/string.c:622",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/params.c:param_array_set",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/hung_task.c:check_hung_task",
        "lib/dump_stack.c:dump_stack_print_info",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/iommu/intel/iommu.c:intel_iommu_setup",
        "drivers/iommu/irq_remapping.c:setup_irqremap",
        "drivers/remoteproc/remoteproc_core.c:rproc_set_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585116000,
      "name": "strcspn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
__kernel_size_t strcspn(const char * s, const char * reject)
```

```json
{
  "name": "strcspn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585564688,
      "name": "strcspn",
      "external": true,
      "loc": "lib/string.c:623",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/params.c:param_array_set",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/hung_task.c:check_hung_task",
        "lib/dump_stack.c:dump_stack_print_info",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/iommu/intel/iommu.c:intel_iommu_setup",
        "drivers/iommu/irq_remapping.c:setup_irqremap",
        "drivers/remoteproc/remoteproc_core.c:rproc_set_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585564688,
      "name": "strcspn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
__kernel_size_t strcspn(const char * s, const char * reject)
```

```json
{
  "name": "strcspn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586717504,
      "name": "strcspn",
      "external": true,
      "loc": "lib/string.c:536",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/params.c:param_array_set",
        "kernel/sched/build_utility.c:sched_debug_header",
        "kernel/module/main.c:load_module",
        "kernel/module/version.c:same_magic",
        "kernel/module/version.c:same_magic",
        "kernel/hung_task.c:check_hung_task",
        "lib/dump_stack.c:dump_stack_print_info",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/iommu/intel/iommu.c:intel_iommu_setup",
        "drivers/iommu/irq_remapping.c:setup_irqremap",
        "drivers/remoteproc/remoteproc_core.c:rproc_set_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586717504,
      "name": "strcspn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
__kernel_size_t strcspn(const char * s, const char * reject)
```

```json
{
  "name": "strcspn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595879744,
      "name": "strcspn",
      "external": true,
      "loc": "lib/string.c:462",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/params.c:param_array_set",
        "kernel/sched/build_utility.c:sched_debug_header",
        "kernel/module/main.c:load_module",
        "kernel/module/version.c:same_magic",
        "kernel/module/version.c:same_magic",
        "kernel/hung_task.c:check_hung_task",
        "security/apparmor/lib.c:aa_parse_debug_params",
        "drivers/pci/p2pdma.c:pci_p2pdma_enable_store",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/iommu/amd/init.c:parse_amd_iommu_options",
        "drivers/iommu/intel/iommu.c:intel_iommu_setup",
        "drivers/iommu/irq_remapping.c:setup_irqremap",
        "drivers/remoteproc/remoteproc_core.c:rproc_set_firmware",
        "lib/dump_stack.c:dump_stack_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595879744,
      "name": "strcspn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
__kernel_size_t strcspn(const char * s, const char * reject)
```

```json
{
  "name": "strcspn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596397136,
      "name": "strcspn",
      "external": true,
      "loc": "lib/string.c:462",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/params.c:param_array_set",
        "kernel/sched/build_utility.c:sched_debug_header",
        "kernel/module/main.c:blacklisted",
        "kernel/module/version.c:same_magic",
        "kernel/module/version.c:same_magic",
        "kernel/hung_task.c:check_hung_task",
        "security/apparmor/lib.c:aa_parse_debug_params",
        "drivers/pci/p2pdma.c:pci_p2pdma_enable_store",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/iommu/amd/init.c:parse_amd_iommu_options",
        "drivers/iommu/intel/iommu.c:intel_iommu_setup",
        "drivers/iommu/irq_remapping.c:setup_irqremap",
        "drivers/remoteproc/remoteproc_core.c:rproc_set_firmware",
        "lib/dump_stack.c:dump_stack_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596397136,
      "name": "strcspn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
__kernel_size_t strcspn(const char * s, const char * reject)
```

```json
{
  "name": "strcspn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597292368,
      "name": "strcspn",
      "external": true,
      "loc": "lib/string.c:447",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/params.c:param_array_set",
        "kernel/sched/build_utility.c:sched_debug_header",
        "kernel/module/main.c:blacklisted",
        "kernel/module/version.c:same_magic",
        "kernel/module/version.c:same_magic",
        "kernel/hung_task.c:check_hung_task",
        "security/apparmor/lib.c:aa_parse_debug_params",
        "drivers/pci/p2pdma.c:pci_p2pdma_enable_store",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/iommu/amd/init.c:parse_amd_iommu_options",
        "drivers/iommu/intel/iommu.c:intel_iommu_setup",
        "drivers/iommu/irq_remapping.c:setup_irqremap",
        "drivers/remoteproc/remoteproc_core.c:rproc_set_firmware",
        "lib/dump_stack.c:dump_stack_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597292368,
      "name": "strcspn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
__kernel_size_t strcspn(const char * s, const char * reject)
```

```json
{
  "name": "strcspn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503863920,
      "name": "strcspn",
      "external": true,
      "loc": "lib/string.c:584",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_array_set",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/module.c:load_module",
        "kernel/hung_task.c:watchdog",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/base/platform.c:early_platform_driver_register",
        "drivers/of/base.c:__of_find_node_by_path",
        "drivers/remoteproc/remoteproc_sysfs.c:firmware_store",
        "lib/dump_stack.c:dump_stack_print_info",
        "lib/vsprintf.c:device_node_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503863920,
      "name": "strcspn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
__kernel_size_t strcspn(const char * s, const char * reject)
```

```json
{
  "name": "strcspn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236491776,
      "name": "strcspn",
      "external": true,
      "loc": "lib/string.c:584",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_array_set",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/module.c:load_module",
        "kernel/hung_task.c:watchdog",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/base/platform.c:early_platform_driver_register",
        "drivers/of/base.c:__of_find_node_by_path",
        "drivers/remoteproc/remoteproc_sysfs.c:firmware_store",
        "lib/dump_stack.c:dump_stack_print_info",
        "lib/vsprintf.c:device_node_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236491776,
      "name": "strcspn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
__kernel_size_t strcspn(const char * s, const char * reject)
```

```json
{
  "name": "strcspn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297722880,
      "name": "strcspn",
      "external": true,
      "loc": "lib/string.c:584",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/pci-ioda.c:iommu_setup",
        "kernel/params.c:param_array_set",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/module.c:load_module",
        "kernel/hung_task.c:watchdog",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/base/platform.c:early_platform_driver_register",
        "drivers/of/base.c:__of_find_node_by_path",
        "drivers/remoteproc/remoteproc_sysfs.c:firmware_store",
        "lib/dump_stack.c:dump_stack_print_info",
        "lib/vsprintf.c:device_node_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297722880,
      "name": "strcspn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
__kernel_size_t strcspn(const char * s, const char * reject)
```

```json
{
  "name": "strcspn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279759772,
      "name": "strcspn",
      "external": true,
      "loc": "lib/string.c:584",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_array_set",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/module.c:load_module",
        "kernel/hung_task.c:watchdog",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/base/platform.c:early_platform_driver_register",
        "drivers/of/base.c:__of_find_node_by_path",
        "lib/dump_stack.c:dump_stack_print_info",
        "lib/vsprintf.c:device_node_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279759772,
      "name": "strcspn",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
__kernel_size_t strcspn(const char * s, const char * reject)
```

```json
{
  "name": "strcspn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589688384,
      "name": "strcspn",
      "external": true,
      "loc": "lib/string.c:584",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/params.c:param_array_set",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/module.c:load_module",
        "kernel/hung_task.c:watchdog",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/iommu/intel-iommu.c:intel_iommu_setup",
        "drivers/iommu/irq_remapping.c:setup_irqremap",
        "drivers/base/platform.c:early_platform_driver_register",
        "drivers/remoteproc/remoteproc_sysfs.c:firmware_store",
        "lib/dump_stack.c:dump_stack_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589688384,
      "name": "strcspn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
__kernel_size_t strcspn(const char * s, const char * reject)
```

```json
{
  "name": "strcspn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589414176,
      "name": "strcspn",
      "external": true,
      "loc": "lib/string.c:584",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/params.c:param_array_set",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/module.c:load_module",
        "kernel/hung_task.c:watchdog",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/iommu/intel-iommu.c:intel_iommu_setup",
        "drivers/iommu/irq_remapping.c:setup_irqremap",
        "drivers/base/platform.c:early_platform_driver_register",
        "lib/dump_stack.c:dump_stack_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589414176,
      "name": "strcspn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
__kernel_size_t strcspn(const char * s, const char * reject)
```

```json
{
  "name": "strcspn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590131760,
      "name": "strcspn",
      "external": true,
      "loc": "lib/string.c:584",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/params.c:param_array_set",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/module.c:load_module",
        "kernel/hung_task.c:watchdog",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/iommu/intel-iommu.c:intel_iommu_setup",
        "drivers/iommu/irq_remapping.c:setup_irqremap",
        "drivers/base/platform.c:early_platform_driver_register",
        "lib/dump_stack.c:dump_stack_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590131760,
      "name": "strcspn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
__kernel_size_t strcspn(const char * s, const char * reject)
```

```json
{
  "name": "strcspn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590182144,
      "name": "strcspn",
      "external": true,
      "loc": "lib/string.c:584",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:iommu_setup",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "arch/x86/platform/uv/tlb_uv.c:tunables_write",
        "arch/x86/platform/uv/tlb_uv.c:tunables_write",
        "kernel/params.c:param_array_set",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/module.c:load_module",
        "kernel/hung_task.c:watchdog",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed",
        "drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/iommu/intel-iommu.c:intel_iommu_setup",
        "drivers/iommu/irq_remapping.c:setup_irqremap",
        "drivers/base/platform.c:early_platform_driver_register",
        "drivers/remoteproc/remoteproc_sysfs.c:firmware_store",
        "lib/dump_stack.c:dump_stack_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590182144,
      "name": "strcspn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
