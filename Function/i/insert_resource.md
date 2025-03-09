# Function: <code>insert_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int insert_resource(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579399808,
      "name": "insert_resource",
      "external": true,
      "loc": "kernel/resource.c:834",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820_reserve_resources",
        "arch/x86/kernel/acpi/boot.c:hpet_insert_resource",
        "arch/x86/kernel/apic/apic.c:lapic_insert_resource",
        "arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources",
        "kernel/kexec_core.c:crash_shrink_memory",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/platform.c:platform_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579399808,
      "name": "insert_resource",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int insert_resource(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579407360,
      "name": "insert_resource",
      "external": true,
      "loc": "kernel/resource.c:871",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820_reserve_resources",
        "arch/x86/kernel/acpi/boot.c:hpet_insert_resource",
        "arch/x86/kernel/apic/apic.c:lapic_insert_resource",
        "arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources",
        "kernel/kexec_core.c:crash_shrink_memory",
        "drivers/base/platform.c:platform_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579407360,
      "name": "insert_resource",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int insert_resource(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579427664,
      "name": "insert_resource",
      "external": true,
      "loc": "kernel/resource.c:871",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820_reserve_resources",
        "arch/x86/kernel/acpi/boot.c:hpet_insert_resource",
        "arch/x86/kernel/apic/apic.c:lapic_insert_resource",
        "arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources",
        "kernel/kexec_core.c:crash_shrink_memory",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/base/platform.c:platform_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579427664,
      "name": "insert_resource",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int insert_resource(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579415408,
      "name": "insert_resource",
      "external": true,
      "loc": "kernel/resource.c:871",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/acpi/boot.c:hpet_insert_resource",
        "arch/x86/kernel/apic/apic.c:lapic_insert_resource",
        "arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources",
        "kernel/kexec_core.c:crash_shrink_memory",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/base/platform.c:platform_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579415408,
      "name": "insert_resource",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int insert_resource(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579443280,
      "name": "insert_resource",
      "external": true,
      "loc": "kernel/resource.c:889",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:arch_xen_balloon_init",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/acpi/boot.c:hpet_insert_resource",
        "arch/x86/kernel/apic/apic.c:lapic_insert_resource",
        "arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources",
        "kernel/kexec_core.c:crash_shrink_memory",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/base/platform.c:platform_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579443280,
      "name": "insert_resource",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int insert_resource(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579462672,
      "name": "insert_resource",
      "external": true,
      "loc": "kernel/resource.c:858",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:arch_xen_balloon_init",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/acpi/boot.c:hpet_insert_resource",
        "arch/x86/kernel/apic/apic.c:lapic_insert_resource",
        "arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources",
        "kernel/kexec_core.c:crash_shrink_memory",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/base/platform.c:platform_device_add",
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579462672,
      "name": "insert_resource",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int insert_resource(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579496240,
      "name": "insert_resource",
      "external": true,
      "loc": "kernel/resource.c:852",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/acpi/boot.c:hpet_insert_resource",
        "arch/x86/kernel/apic/apic.c:lapic_insert_resource",
        "arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources",
        "kernel/kexec_core.c:crash_shrink_memory",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/base/platform.c:platform_device_add",
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579496240,
      "name": "insert_resource",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int insert_resource(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579514208,
      "name": "insert_resource",
      "external": true,
      "loc": "kernel/resource.c:866",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/acpi/boot.c:hpet_insert_resource",
        "arch/x86/kernel/apic/apic.c:lapic_insert_resource",
        "arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources",
        "kernel/kexec_core.c:crash_shrink_memory",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/base/platform.c:platform_device_add",
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579514208,
      "name": "insert_resource",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int insert_resource(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579540368,
      "name": "insert_resource",
      "external": true,
      "loc": "kernel/resource.c:866",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/acpi/boot.c:hpet_insert_resource",
        "arch/x86/kernel/apic/apic.c:lapic_insert_resource",
        "arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources",
        "kernel/kexec_core.c:crash_shrink_memory",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/base/platform.c:platform_device_add",
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540368,
      "name": "insert_resource",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int insert_resource(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579569600,
      "name": "insert_resource",
      "external": true,
      "loc": "kernel/resource.c:866",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel_low",
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/acpi/boot.c:hpet_insert_resource",
        "arch/x86/kernel/apic/apic.c:lapic_insert_resource",
        "arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources",
        "kernel/kexec_core.c:crash_shrink_memory",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/base/platform.c:platform_device_add",
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579569600,
      "name": "insert_resource",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int insert_resource(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579551008,
      "name": "insert_resource",
      "external": true,
      "loc": "kernel/resource.c:873",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel_low",
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/acpi/boot.c:hpet_insert_resource",
        "arch/x86/kernel/apic/apic.c:lapic_insert_resource",
        "arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources",
        "kernel/kexec_core.c:crash_shrink_memory",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/base/platform.c:platform_device_add",
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551008,
      "name": "insert_resource",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int insert_resource(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579555648,
      "name": "insert_resource",
      "external": true,
      "loc": "kernel/resource.c:865",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/acpi/boot.c:hpet_insert_resource",
        "arch/x86/kernel/apic/apic.c:lapic_insert_resource",
        "arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources",
        "kernel/kexec_core.c:crash_shrink_memory",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/base/platform.c:platform_device_add",
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579555648,
      "name": "insert_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int insert_resource(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579628224,
      "name": "insert_resource",
      "external": true,
      "loc": "kernel/resource.c:865",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/acpi/boot.c:hpet_insert_resource",
        "arch/x86/kernel/apic/apic.c:lapic_insert_resource",
        "arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources",
        "kernel/kexec_core.c:crash_shrink_memory",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/base/platform.c:platform_device_add",
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579628224,
      "name": "insert_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int insert_resource(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579723296,
      "name": "insert_resource",
      "external": true,
      "loc": "kernel/resource.c:852",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/acpi/boot.c:hpet_insert_resource",
        "arch/x86/kernel/apic/apic.c:lapic_insert_resource",
        "arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources",
        "kernel/kexec_core.c:crash_shrink_memory",
        "drivers/pci/quirks.c:quirk_alder_ioapic",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/base/platform.c:platform_device_add",
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579723296,
      "name": "insert_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int insert_resource(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579850592,
      "name": "insert_resource",
      "external": true,
      "loc": "kernel/resource.c:853",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/acpi/boot.c:hpet_insert_resource",
        "arch/x86/kernel/apic/apic.c:lapic_insert_resource",
        "arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources",
        "kernel/kexec_core.c:crash_shrink_memory",
        "drivers/pci/quirks.c:quirk_alder_ioapic",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/platform.c:platform_device_add",
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579850592,
      "name": "insert_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int insert_resource(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579900832,
      "name": "insert_resource",
      "external": true,
      "loc": "kernel/resource.c:853",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/acpi/boot.c:hpet_insert_resource",
        "arch/x86/kernel/apic/apic.c:lapic_insert_resource",
        "arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources",
        "kernel/kexec_core.c:crash_shrink_memory",
        "kernel/kexec_core.c:__crash_shrink_memory",
        "drivers/pci/quirks.c:quirk_alder_ioapic",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/platform.c:platform_device_add",
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900832,
      "name": "insert_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int insert_resource(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579939568,
      "name": "insert_resource",
      "external": true,
      "loc": "kernel/resource.c:908",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/acpi/boot.c:hpet_insert_resource",
        "arch/x86/kernel/apic/apic.c:lapic_insert_resource",
        "arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources",
        "kernel/crash_core.c:insert_crashkernel_resources",
        "kernel/crash_core.c:insert_crashkernel_resources",
        "kernel/kexec_core.c:crash_shrink_memory",
        "kernel/kexec_core.c:__crash_shrink_memory",
        "drivers/pci/quirks.c:quirk_alder_ioapic",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/platform.c:platform_device_add",
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939568,
      "name": "insert_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int insert_resource(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490687296,
      "name": "insert_resource",
      "external": true,
      "loc": "kernel/resource.c:866",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:crash_shrink_memory",
        "drivers/base/platform.c:platform_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490687296,
      "name": "insert_resource",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int insert_resource(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224756092,
      "name": "insert_resource",
      "external": true,
      "loc": "kernel/resource.c:866",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/setup.c:setup_arch",
        "arch/arm/kernel/setup.c:setup_arch",
        "kernel/kexec_core.c:crash_shrink_memory",
        "drivers/base/platform.c:platform_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224756092,
      "name": "insert_resource",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int insert_resource(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283512080,
      "name": "insert_resource",
      "external": true,
      "loc": "kernel/resource.c:866",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:crash_shrink_memory",
        "drivers/base/platform.c:platform_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283512080,
      "name": "insert_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int insert_resource(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271420416,
      "name": "insert_resource",
      "external": true,
      "loc": "kernel/resource.c:866",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:platform_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271420416,
      "name": "insert_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int insert_resource(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579514032,
      "name": "insert_resource",
      "external": true,
      "loc": "kernel/resource.c:866",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/acpi/boot.c:hpet_insert_resource",
        "arch/x86/kernel/apic/apic.c:lapic_insert_resource",
        "arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources",
        "kernel/kexec_core.c:crash_shrink_memory",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/base/platform.c:platform_device_add",
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579514032,
      "name": "insert_resource",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int insert_resource(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579442832,
      "name": "insert_resource",
      "external": true,
      "loc": "kernel/resource.c:866",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/acpi/boot.c:hpet_insert_resource",
        "arch/x86/kernel/apic/apic.c:lapic_insert_resource",
        "arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources",
        "kernel/kexec_core.c:crash_shrink_memory",
        "drivers/acpi/nfit/core.c:acpi_nfit_register_region",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/base/platform.c:platform_device_add",
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579442832,
      "name": "insert_resource",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int insert_resource(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579513952,
      "name": "insert_resource",
      "external": true,
      "loc": "kernel/resource.c:866",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/acpi/boot.c:hpet_insert_resource",
        "arch/x86/kernel/apic/apic.c:lapic_insert_resource",
        "arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources",
        "kernel/kexec_core.c:crash_shrink_memory",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/base/platform.c:platform_device_add",
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513952,
      "name": "insert_resource",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int insert_resource(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579546896,
      "name": "insert_resource",
      "external": true,
      "loc": "kernel/resource.c:866",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/acpi/boot.c:hpet_insert_resource",
        "arch/x86/kernel/apic/apic.c:lapic_insert_resource",
        "arch/x86/kernel/apic/io_apic.c:ioapic_insert_resources",
        "kernel/kexec_core.c:crash_shrink_memory",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/base/platform.c:platform_device_add",
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_insert_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546896,
      "name": "insert_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
