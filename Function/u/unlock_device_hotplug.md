# Function: <code>unlock_device_hotplug</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_device_hotplug()
```

```json
{
  "name": "unlock_device_hotplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584382304,
      "name": "unlock_device_hotplug",
      "external": true,
      "loc": "drivers/base/core.c:60",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/sysfs.c:force_remove_store",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584382304,
      "name": "unlock_device_hotplug",
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
void unlock_device_hotplug()
```

```json
{
  "name": "unlock_device_hotplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584722623,
      "name": "unlock_device_hotplug",
      "external": true,
      "loc": "drivers/base/core.c:60",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": [
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/sysfs.c:force_remove_store",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584717248,
      "name": "unlock_device_hotplug",
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
void unlock_device_hotplug()
```

```json
{
  "name": "unlock_device_hotplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584912415,
      "name": "unlock_device_hotplug",
      "external": true,
      "loc": "drivers/base/core.c:626",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": [
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:devm_memremap_pages_release",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/sysfs.c:force_remove_store",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584906384,
      "name": "unlock_device_hotplug",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_device_hotplug()
```

```json
{
  "name": "unlock_device_hotplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584997695,
      "name": "unlock_device_hotplug",
      "external": true,
      "loc": "drivers/base/core.c:627",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": [
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584991520,
      "name": "unlock_device_hotplug",
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
void unlock_device_hotplug()
```

```json
{
  "name": "unlock_device_hotplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585419583,
      "name": "unlock_device_hotplug",
      "external": true,
      "loc": "drivers/base/core.c:630",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": [
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585413472,
      "name": "unlock_device_hotplug",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_device_hotplug()
```

```json
{
  "name": "unlock_device_hotplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585662335,
      "name": "unlock_device_hotplug",
      "external": true,
      "loc": "drivers/base/core.c:663",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": [
        "kernel/cpu.c:store_smt_control",
        "kernel/cpu.c:store_smt_control",
        "kernel/cpu.c:store_smt_control",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585656080,
      "name": "unlock_device_hotplug",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_device_hotplug()
```

```json
{
  "name": "unlock_device_hotplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585792015,
      "name": "unlock_device_hotplug",
      "external": true,
      "loc": "drivers/base/core.c:705",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": [
        "kernel/cpu.c:store_smt_control",
        "kernel/cpu.c:store_smt_control",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/base/memory.c:probe_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585788240,
      "name": "unlock_device_hotplug",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_device_hotplug()
```

```json
{
  "name": "unlock_device_hotplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586023295,
      "name": "unlock_device_hotplug",
      "external": true,
      "loc": "drivers/base/core.c:850",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": [
        "kernel/cpu.c:store_smt_control",
        "kernel/cpu.c:store_smt_control",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/base/memory.c:probe_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586019216,
      "name": "unlock_device_hotplug",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_device_hotplug()
```

```json
{
  "name": "unlock_device_hotplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586171007,
      "name": "unlock_device_hotplug",
      "external": true,
      "loc": "drivers/base/core.c:887",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": [
        "kernel/cpu.c:store_smt_control",
        "kernel/cpu.c:store_smt_control",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/base/memory.c:probe_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586166960,
      "name": "unlock_device_hotplug",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_device_hotplug()
```

```json
{
  "name": "unlock_device_hotplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586931190,
      "name": "unlock_device_hotplug",
      "external": true,
      "loc": "drivers/base/core.c:1365",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": [
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:add_cpu",
        "kernel/cpu.c:remove_cpu",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl",
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:add_memory_driver_managed",
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/base/memory.c:probe_store",
        "drivers/base/memory.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586926672,
      "name": "unlock_device_hotplug",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_device_hotplug()
```

```json
{
  "name": "unlock_device_hotplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587018342,
      "name": "unlock_device_hotplug",
      "external": true,
      "loc": "drivers/base/core.c:1766",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": [
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:add_cpu",
        "kernel/cpu.c:remove_cpu",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl",
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:add_memory_driver_managed",
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/base/memory.c:probe_store",
        "drivers/base/memory.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587010368,
      "name": "unlock_device_hotplug",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_device_hotplug()
```

```json
{
  "name": "unlock_device_hotplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586901974,
      "name": "unlock_device_hotplug",
      "external": true,
      "loc": "drivers/base/core.c:1978",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": [
        "kernel/cpu.c:store_smt_control",
        "kernel/cpu.c:store_smt_control",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:add_cpu",
        "kernel/cpu.c:remove_cpu",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl",
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:add_memory_driver_managed",
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/base/memory.c:probe_store",
        "drivers/base/memory.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586893616,
      "name": "unlock_device_hotplug",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_device_hotplug()
```

```json
{
  "name": "unlock_device_hotplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587463667,
      "name": "unlock_device_hotplug",
      "external": true,
      "loc": "drivers/base/core.c:2015",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": [
        "kernel/cpu.c:control_store",
        "kernel/cpu.c:control_store",
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:add_cpu",
        "kernel/cpu.c:remove_cpu",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl",
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:add_memory_driver_managed",
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/base/memory.c:probe_store",
        "drivers/base/memory.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587455520,
      "name": "unlock_device_hotplug",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_device_hotplug()
```

```json
{
  "name": "unlock_device_hotplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588783451,
      "name": "unlock_device_hotplug",
      "external": true,
      "loc": "drivers/base/core.c:2027",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": [
        "kernel/cpu.c:control_store",
        "kernel/cpu.c:control_store",
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:add_cpu",
        "kernel/cpu.c:remove_cpu",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl",
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:add_memory_driver_managed",
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/base/memory.c:probe_store",
        "drivers/base/memory.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588774384,
      "name": "unlock_device_hotplug",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_device_hotplug()
```

```json
{
  "name": "unlock_device_hotplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590278075,
      "name": "unlock_device_hotplug",
      "external": true,
      "loc": "drivers/base/core.c:2264",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": [
        "kernel/cpu.c:control_store",
        "kernel/cpu.c:control_store",
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:add_cpu",
        "kernel/cpu.c:remove_cpu",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl",
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:add_memory_driver_managed",
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/base/memory.c:probe_store",
        "drivers/base/memory.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590267424,
      "name": "unlock_device_hotplug",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_device_hotplug()
```

```json
{
  "name": "unlock_device_hotplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590598635,
      "name": "unlock_device_hotplug",
      "external": true,
      "loc": "drivers/base/core.c:2270",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": [
        "kernel/cpu.c:control_store",
        "kernel/cpu.c:control_store",
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:add_cpu",
        "kernel/cpu.c:remove_cpu",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl",
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:add_memory_driver_managed",
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/base/memory.c:probe_store",
        "drivers/base/memory.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590587824,
      "name": "unlock_device_hotplug",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_device_hotplug()
```

```json
{
  "name": "unlock_device_hotplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590957579,
      "name": "unlock_device_hotplug",
      "external": true,
      "loc": "drivers/base/core.c:2285",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": [
        "kernel/cpu.c:control_store",
        "kernel/cpu.c:control_store",
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:add_cpu",
        "kernel/cpu.c:remove_cpu",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl",
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:add_memory_driver_managed",
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/base/memory.c:probe_store",
        "drivers/base/memory.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590946496,
      "name": "unlock_device_hotplug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void unlock_device_hotplug()
```

```json
{
  "name": "unlock_device_hotplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498967096,
      "name": "unlock_device_hotplug",
      "external": true,
      "loc": "drivers/base/core.c:887",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": [
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:write_cpuhp_target",
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/xen/balloon.c:reserve_additional_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498962744,
      "name": "unlock_device_hotplug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void unlock_device_hotplug()
```

```json
{
  "name": "unlock_device_hotplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231537188,
      "name": "unlock_device_hotplug",
      "external": true,
      "loc": "drivers/base/core.c:887",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": [
        "arch/arm/common/bL_switcher.c:bL_switcher_active_store",
        "arch/arm/common/bL_switcher.c:bL_switcher_active_store",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231532972,
      "name": "unlock_device_hotplug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void unlock_device_hotplug()
```

```json
{
  "name": "unlock_device_hotplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292114020,
      "name": "unlock_device_hotplug",
      "external": true,
      "loc": "drivers/base/core.c:887",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": [
        "arch/powerpc/kernel/rtas.c:rtas_ibm_suspend_me",
        "arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_regions_runtime",
        "arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_regions_runtime",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu",
        "arch/powerpc/platforms/pseries/hotplug-memory.c:dlpar_memory",
        "arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_remove_memblock",
        "arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_remove_memblock",
        "arch/powerpc/platforms/pseries/pmem.c:dlpar_hp_pmem",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:write_cpuhp_target",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:add_memory",
        "drivers/base/memory.c:probe_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292108096,
      "name": "unlock_device_hotplug",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void unlock_device_hotplug()
```

```json
{
  "name": "unlock_device_hotplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276347424,
      "name": "unlock_device_hotplug",
      "external": true,
      "loc": "drivers/base/core.c:887",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276343850,
      "name": "unlock_device_hotplug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void unlock_device_hotplug()
```

```json
{
  "name": "unlock_device_hotplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585931375,
      "name": "unlock_device_hotplug",
      "external": true,
      "loc": "drivers/base/core.c:887",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": [
        "kernel/cpu.c:store_smt_control",
        "kernel/cpu.c:store_smt_control",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/base/memory.c:probe_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585927328,
      "name": "unlock_device_hotplug",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_device_hotplug()
```

```json
{
  "name": "unlock_device_hotplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585780511,
      "name": "unlock_device_hotplug",
      "external": true,
      "loc": "drivers/base/core.c:887",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": [
        "kernel/cpu.c:store_smt_control",
        "kernel/cpu.c:store_smt_control",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/base/memory.c:probe_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585776464,
      "name": "unlock_device_hotplug",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_device_hotplug()
```

```json
{
  "name": "unlock_device_hotplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586121023,
      "name": "unlock_device_hotplug",
      "external": true,
      "loc": "drivers/base/core.c:887",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": [
        "kernel/cpu.c:store_smt_control",
        "kernel/cpu.c:store_smt_control",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/base/memory.c:probe_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586116976,
      "name": "unlock_device_hotplug",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_device_hotplug()
```

```json
{
  "name": "unlock_device_hotplug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586229631,
      "name": "unlock_device_hotplug",
      "external": true,
      "loc": "drivers/base/core.c:887",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": [
        "kernel/cpu.c:store_smt_control",
        "kernel/cpu.c:store_smt_control",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl",
        "mm/memory_hotplug.c:remove_memory",
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/base/memory.c:probe_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586225584,
      "name": "unlock_device_hotplug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
