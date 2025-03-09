# Function: <code>release_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int release_resource(struct resource * old)
```

```json
{
  "name": "release_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579394064,
      "name": "release_resource",
      "external": true,
      "loc": "kernel/resource.c:323",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "kernel/resource.c:devm_resource_release",
        "kernel/kexec_core.c:crash_shrink_memory",
        "mm/memory_hotplug.c:add_memory",
        "drivers/pci/probe.c:pci_bus_release_busn_res",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/rapidio/rio.c:rio_release_inb_mbox",
        "drivers/rapidio/rio.c:rio_release_outb_mbox",
        "drivers/rapidio/rio.c:rio_release_inb_dbell",
        "drivers/rapidio/rio.c:rio_release_outb_dbell",
        "drivers/acpi/pci_root.c:__acpi_pci_root_release_info",
        "drivers/acpi/pci_root.c:acpi_pci_root_release_info",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/char/agp/intel-gtt.c:i9xx_cleanup",
        "drivers/base/platform.c:platform_device_add",
        "drivers/base/platform.c:platform_device_del",
        "arch/x86/pci/mmconfig-shared.c:free_all_mmcfg",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394064,
      "name": "release_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int release_resource(struct resource * old)
```

```json
{
  "name": "release_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579406016,
      "name": "release_resource",
      "external": true,
      "loc": "kernel/resource.c:342",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "kernel/resource.c:devm_resource_release",
        "kernel/kexec_core.c:crash_shrink_memory",
        "mm/memory_hotplug.c:add_memory",
        "drivers/pci/probe.c:pci_bus_release_busn_res",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/rapidio/rio.c:rio_release_outb_dbell",
        "drivers/rapidio/rio.c:rio_release_inb_dbell",
        "drivers/rapidio/rio.c:rio_release_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_release_inb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/acpi/pci_root.c:acpi_pci_root_release_info",
        "drivers/acpi/pci_root.c:__acpi_pci_root_release_info",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/char/agp/intel-gtt.c:i9xx_cleanup",
        "drivers/base/platform.c:platform_device_del",
        "drivers/base/platform.c:platform_device_add",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert",
        "arch/x86/pci/mmconfig-shared.c:free_all_mmcfg",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579406016,
      "name": "release_resource",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int release_resource(struct resource * old)
```

```json
{
  "name": "release_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579426320,
      "name": "release_resource",
      "external": true,
      "loc": "kernel/resource.c:342",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "kernel/resource.c:devm_resource_release",
        "kernel/kexec_core.c:crash_shrink_memory",
        "mm/memory_hotplug.c:add_memory",
        "drivers/pci/probe.c:pci_bus_release_busn_res",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/rapidio/rio.c:rio_release_outb_dbell",
        "drivers/rapidio/rio.c:rio_release_inb_dbell",
        "drivers/rapidio/rio.c:rio_release_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_release_inb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/acpi/pci_root.c:acpi_pci_root_release_info",
        "drivers/acpi/pci_root.c:__acpi_pci_root_release_info",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/char/agp/intel-gtt.c:i9xx_cleanup",
        "drivers/base/platform.c:platform_device_del",
        "drivers/base/platform.c:platform_device_add",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert",
        "arch/x86/pci/mmconfig-shared.c:free_all_mmcfg",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579426320,
      "name": "release_resource",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int release_resource(struct resource * old)
```

```json
{
  "name": "release_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579414080,
      "name": "release_resource",
      "external": true,
      "loc": "kernel/resource.c:342",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "kernel/resource.c:devm_resource_release",
        "kernel/kexec_core.c:crash_shrink_memory",
        "mm/memory_hotplug.c:add_memory",
        "drivers/pci/probe.c:pci_bus_release_busn_res",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/rapidio/rio.c:rio_release_outb_dbell",
        "drivers/rapidio/rio.c:rio_release_inb_dbell",
        "drivers/rapidio/rio.c:rio_release_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_release_inb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/acpi/pci_root.c:acpi_pci_root_release_info",
        "drivers/acpi/pci_root.c:__acpi_pci_root_release_info",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/char/agp/intel-gtt.c:i9xx_cleanup",
        "drivers/base/platform.c:platform_device_add",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert",
        "arch/x86/pci/mmconfig-shared.c:free_all_mmcfg",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579414080,
      "name": "release_resource",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int release_resource(struct resource * old)
```

```json
{
  "name": "release_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579441952,
      "name": "release_resource",
      "external": true,
      "loc": "kernel/resource.c:342",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "kernel/resource.c:devm_resource_release",
        "kernel/kexec_core.c:crash_shrink_memory",
        "mm/memory_hotplug.c:add_memory",
        "drivers/pci/probe.c:pci_bus_release_busn_res",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/setup-res.c:pci_release_resource",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/rapidio/rio.c:rio_release_outb_dbell",
        "drivers/rapidio/rio.c:rio_release_inb_dbell",
        "drivers/rapidio/rio.c:rio_release_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_release_inb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/acpi/pci_root.c:acpi_pci_root_release_info",
        "drivers/acpi/pci_root.c:__acpi_pci_root_release_info",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/char/agp/intel-gtt.c:i9xx_cleanup",
        "drivers/base/platform.c:platform_device_add",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert",
        "arch/x86/pci/mmconfig-shared.c:free_all_mmcfg",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579441952,
      "name": "release_resource",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int release_resource(struct resource * old)
```

```json
{
  "name": "release_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579456976,
      "name": "release_resource",
      "external": true,
      "loc": "kernel/resource.c:309",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "kernel/resource.c:devm_resource_release",
        "kernel/kexec_core.c:crash_shrink_memory",
        "mm/memory_hotplug.c:add_memory",
        "drivers/pci/probe.c:pci_bus_release_busn_res",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/setup-res.c:pci_release_resource",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/rapidio/rio.c:rio_release_outb_dbell",
        "drivers/rapidio/rio.c:rio_release_inb_dbell",
        "drivers/rapidio/rio.c:rio_release_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_release_inb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/acpi/pci_root.c:acpi_pci_root_release_info",
        "drivers/acpi/pci_root.c:__acpi_pci_root_release_info",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/intel-gtt.c:i9xx_cleanup",
        "drivers/base/platform.c:platform_device_add",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert",
        "arch/x86/pci/mmconfig-shared.c:free_all_mmcfg",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579456976,
      "name": "release_resource",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int release_resource(struct resource * old)
```

```json
{
  "name": "release_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579490640,
      "name": "release_resource",
      "external": true,
      "loc": "kernel/resource.c:309",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "kernel/resource.c:devm_resource_release",
        "kernel/kexec_core.c:crash_shrink_memory",
        "mm/memory_hotplug.c:__add_memory",
        "drivers/pci/probe.c:pci_bus_release_busn_res",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/setup-res.c:pci_release_resource",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/rapidio/rio.c:rio_release_outb_dbell",
        "drivers/rapidio/rio.c:rio_release_inb_dbell",
        "drivers/rapidio/rio.c:rio_release_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_release_inb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/acpi/pci_root.c:acpi_pci_root_release_info",
        "drivers/acpi/pci_root.c:__acpi_pci_root_release_info",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/intel-gtt.c:i9xx_cleanup",
        "drivers/base/platform.c:platform_device_add",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_release_resources",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert",
        "arch/x86/pci/mmconfig-shared.c:free_all_mmcfg",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579490640,
      "name": "release_resource",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int release_resource(struct resource * old)
```

```json
{
  "name": "release_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579508480,
      "name": "release_resource",
      "external": true,
      "loc": "kernel/resource.c:310",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "kernel/resource.c:devm_resource_release",
        "kernel/kexec_core.c:crash_shrink_memory",
        "mm/memory_hotplug.c:__add_memory",
        "drivers/pci/probe.c:pci_bus_release_busn_res",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/setup-res.c:pci_release_resource",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/rapidio/rio.c:rio_release_outb_dbell",
        "drivers/rapidio/rio.c:rio_release_inb_dbell",
        "drivers/rapidio/rio.c:rio_release_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_release_inb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/acpi/pci_root.c:acpi_pci_root_release_info",
        "drivers/acpi/pci_root.c:__acpi_pci_root_release_info",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/intel-gtt.c:i9xx_cleanup",
        "drivers/base/platform.c:platform_device_add",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_release_resources",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert",
        "arch/x86/pci/mmconfig-shared.c:free_all_mmcfg",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508480,
      "name": "release_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int release_resource(struct resource * old)
```

```json
{
  "name": "release_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579534528,
      "name": "release_resource",
      "external": true,
      "loc": "kernel/resource.c:310",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "kernel/resource.c:devm_resource_release",
        "kernel/kexec_core.c:crash_shrink_memory",
        "mm/memory_hotplug.c:__add_memory",
        "drivers/pci/probe.c:pci_bus_release_busn_res",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/setup-res.c:pci_release_resource",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/rapidio/rio.c:rio_release_outb_dbell",
        "drivers/rapidio/rio.c:rio_release_inb_dbell",
        "drivers/rapidio/rio.c:rio_release_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_release_inb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/acpi/pci_root.c:acpi_pci_root_release_info",
        "drivers/acpi/pci_root.c:__acpi_pci_root_release_info",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/intel-gtt.c:i9xx_cleanup",
        "drivers/base/platform.c:platform_device_add",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_release_resources",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert",
        "arch/x86/pci/mmconfig-shared.c:free_all_mmcfg",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579534528,
      "name": "release_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int release_resource(struct resource * old)
```

```json
{
  "name": "release_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579567189,
      "name": "release_resource",
      "external": true,
      "loc": "kernel/resource.c:310",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:devm_resource_release"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "kernel/kexec_core.c:crash_shrink_memory",
        "mm/memory_hotplug.c:add_memory_driver_managed",
        "mm/memory_hotplug.c:__add_memory",
        "drivers/pci/probe.c:pci_bus_release_busn_res",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/setup-res.c:pci_release_resource",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/rapidio/rio.c:rio_release_outb_dbell",
        "drivers/rapidio/rio.c:rio_release_inb_dbell",
        "drivers/rapidio/rio.c:rio_release_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_release_inb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/acpi/pci_root.c:acpi_pci_root_release_info",
        "drivers/acpi/pci_root.c:__acpi_pci_root_release_info",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/xen/balloon.c:additional_memory_resource",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/intel-gtt.c:i9xx_cleanup",
        "drivers/base/platform.c:platform_device_add",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_release_resources",
        "drivers/eisa/eisa-bus.c:eisa_request_resources",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert",
        "arch/x86/pci/mmconfig-shared.c:free_all_mmcfg",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565456,
      "name": "release_resource",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int release_resource(struct resource * old)
```

```json
{
  "name": "release_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579548533,
      "name": "release_resource",
      "external": true,
      "loc": "kernel/resource.c:310",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:devm_resource_release"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "kernel/kexec_core.c:crash_shrink_memory",
        "mm/memory_hotplug.c:add_memory_driver_managed",
        "mm/memory_hotplug.c:__add_memory",
        "drivers/pci/probe.c:pci_bus_release_busn_res",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/setup-res.c:pci_release_resource",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/rapidio/rio.c:rio_release_outb_dbell",
        "drivers/rapidio/rio.c:rio_release_inb_dbell",
        "drivers/rapidio/rio.c:rio_release_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_release_inb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/acpi/pci_root.c:acpi_pci_root_release_info",
        "drivers/acpi/pci_root.c:__acpi_pci_root_release_info",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/intel-gtt.c:i9xx_cleanup",
        "drivers/base/platform.c:platform_device_add",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_release_resources",
        "drivers/eisa/eisa-bus.c:eisa_request_resources",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert",
        "arch/x86/pci/mmconfig-shared.c:free_all_mmcfg",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546832,
      "name": "release_resource",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int release_resource(struct resource * old)
```

```json
{
  "name": "release_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579553525,
      "name": "release_resource",
      "external": true,
      "loc": "kernel/resource.c:309",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:devm_resource_release"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "kernel/kexec_core.c:crash_shrink_memory",
        "mm/memory_hotplug.c:add_memory_driver_managed",
        "mm/memory_hotplug.c:__add_memory",
        "drivers/pci/probe.c:pci_bus_release_busn_res",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/setup-res.c:pci_release_resource",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/rapidio/rio.c:rio_release_outb_dbell",
        "drivers/rapidio/rio.c:rio_release_inb_dbell",
        "drivers/rapidio/rio.c:rio_release_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_release_inb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/acpi/pci_root.c:acpi_pci_root_release_info",
        "drivers/acpi/pci_root.c:__acpi_pci_root_release_info",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/intel-gtt.c:i9xx_cleanup",
        "drivers/base/platform.c:platform_device_add",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_release_resources",
        "drivers/eisa/eisa-bus.c:eisa_request_resources",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert",
        "arch/x86/pci/mmconfig-shared.c:free_all_mmcfg",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551312,
      "name": "release_resource",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int release_resource(struct resource * old)
```

```json
{
  "name": "release_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579626085,
      "name": "release_resource",
      "external": true,
      "loc": "kernel/resource.c:309",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:devm_resource_release"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "kernel/kexec_core.c:crash_shrink_memory",
        "mm/memory_hotplug.c:add_memory_driver_managed",
        "mm/memory_hotplug.c:__add_memory",
        "drivers/pci/probe.c:pci_bus_release_busn_res",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/setup-res.c:pci_release_resource",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/rapidio/rio.c:rio_release_outb_dbell",
        "drivers/rapidio/rio.c:rio_release_inb_dbell",
        "drivers/rapidio/rio.c:rio_release_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_release_inb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/acpi/pci_root.c:acpi_pci_root_release_info",
        "drivers/acpi/pci_root.c:__acpi_pci_root_release_info",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/intel-gtt.c:i9xx_cleanup",
        "drivers/base/platform.c:platform_device_add",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_release_resources",
        "drivers/eisa/eisa-bus.c:eisa_request_resources",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert",
        "arch/x86/pci/mmconfig-shared.c:free_all_mmcfg",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579623888,
      "name": "release_resource",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int release_resource(struct resource * old)
```

```json
{
  "name": "release_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579720532,
      "name": "release_resource",
      "external": true,
      "loc": "kernel/resource.c:296",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:devm_resource_release"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "kernel/kexec_core.c:crash_shrink_memory",
        "mm/memory_hotplug.c:add_memory_driver_managed",
        "mm/memory_hotplug.c:__add_memory",
        "drivers/pci/probe.c:pci_bus_release_busn_res",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/setup-res.c:pci_release_resource",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/rapidio/rio.c:rio_release_outb_dbell",
        "drivers/rapidio/rio.c:rio_release_inb_dbell",
        "drivers/rapidio/rio.c:rio_release_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_release_inb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/acpi/pci_root.c:acpi_pci_root_release_info",
        "drivers/acpi/pci_root.c:__acpi_pci_root_release_info",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/intel-gtt.c:i9xx_cleanup",
        "drivers/base/platform.c:platform_device_add",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_release_resources",
        "drivers/eisa/eisa-bus.c:eisa_request_resources",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert",
        "arch/x86/pci/mmconfig-shared.c:free_all_mmcfg",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579718208,
      "name": "release_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int release_resource(struct resource * old)
```

```json
{
  "name": "release_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579847876,
      "name": "release_resource",
      "external": true,
      "loc": "kernel/resource.c:296",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:devm_resource_release"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "kernel/kexec_core.c:crash_shrink_memory",
        "mm/memory_hotplug.c:add_memory_driver_managed",
        "mm/memory_hotplug.c:__add_memory",
        "drivers/pci/probe.c:pci_bus_release_busn_res",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/setup-res.c:pci_release_resource",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/rapidio/rio.c:rio_release_outb_dbell",
        "drivers/rapidio/rio.c:rio_release_inb_dbell",
        "drivers/rapidio/rio.c:rio_release_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_release_inb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/acpi/pci_root.c:acpi_pci_root_release_info",
        "drivers/acpi/pci_root.c:__acpi_pci_root_release_info",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/intel-gtt.c:i9xx_cleanup",
        "drivers/base/platform.c:platform_device_add",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_probe",
        "drivers/eisa/eisa-bus.c:eisa_probe",
        "drivers/eisa/eisa-bus.c:eisa_probe",
        "drivers/eisa/eisa-bus.c:eisa_probe",
        "drivers/eisa/eisa-bus.c:eisa_request_resources",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert",
        "arch/x86/pci/mmconfig-shared.c:free_all_mmcfg",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579845360,
      "name": "release_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int release_resource(struct resource * old)
```

```json
{
  "name": "release_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579898100,
      "name": "release_resource",
      "external": true,
      "loc": "kernel/resource.c:296",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:devm_resource_release"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "kernel/kexec_core.c:crash_shrink_memory",
        "kernel/kexec_core.c:__crash_shrink_memory",
        "mm/memory_hotplug.c:add_memory_driver_managed",
        "mm/memory_hotplug.c:__add_memory",
        "drivers/pci/probe.c:pci_bus_release_busn_res",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/setup-res.c:pci_release_resource",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/rapidio/rio.c:rio_release_outb_dbell",
        "drivers/rapidio/rio.c:rio_release_inb_dbell",
        "drivers/rapidio/rio.c:rio_release_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_release_inb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/acpi/pci_root.c:acpi_pci_root_release_info",
        "drivers/acpi/pci_root.c:__acpi_pci_root_release_info",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/intel-gtt.c:i9xx_cleanup",
        "drivers/base/platform.c:platform_device_add",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_probe",
        "drivers/eisa/eisa-bus.c:eisa_probe",
        "drivers/eisa/eisa-bus.c:eisa_probe",
        "drivers/eisa/eisa-bus.c:eisa_probe",
        "drivers/eisa/eisa-bus.c:eisa_request_resources",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert",
        "arch/x86/pci/mmconfig-shared.c:free_all_mmcfg",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579895584,
      "name": "release_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int release_resource(struct resource * old)
```

```json
{
  "name": "release_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579936884,
      "name": "release_resource",
      "external": true,
      "loc": "kernel/resource.c:296",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:devm_resource_release"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "kernel/kexec_core.c:crash_shrink_memory",
        "kernel/kexec_core.c:__crash_shrink_memory",
        "mm/memory_hotplug.c:add_memory_driver_managed",
        "mm/memory_hotplug.c:__add_memory",
        "drivers/pci/probe.c:pci_bus_release_busn_res",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/setup-res.c:pci_release_resource",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/rapidio/rio.c:rio_release_outb_dbell",
        "drivers/rapidio/rio.c:rio_release_inb_dbell",
        "drivers/rapidio/rio.c:rio_release_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_release_inb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/acpi/pci_root.c:acpi_pci_root_release_info",
        "drivers/acpi/pci_root.c:__acpi_pci_root_release_info",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/intel-gtt.c:i9xx_cleanup",
        "drivers/base/platform.c:platform_device_add",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_probe",
        "drivers/eisa/eisa-bus.c:eisa_probe",
        "drivers/eisa/eisa-bus.c:eisa_probe",
        "drivers/eisa/eisa-bus.c:eisa_probe",
        "drivers/eisa/eisa-bus.c:eisa_request_resources",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert",
        "arch/x86/pci/mmconfig-shared.c:free_all_mmcfg",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579934432,
      "name": "release_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int release_resource(struct resource * old)
```

```json
{
  "name": "release_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490682792,
      "name": "release_resource",
      "external": true,
      "loc": "kernel/resource.c:310",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_resource_release",
        "kernel/kexec_core.c:crash_shrink_memory",
        "mm/memory_hotplug.c:__add_memory",
        "drivers/pci/probe.c:pci_bus_release_busn_res",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/setup-res.c:pci_release_resource",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/ecam.c:pci_ecam_free",
        "drivers/rapidio/rio.c:rio_release_outb_dbell",
        "drivers/rapidio/rio.c:rio_release_inb_dbell",
        "drivers/rapidio/rio.c:rio_release_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_release_inb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/acpi/pci_root.c:acpi_pci_root_release_info",
        "drivers/acpi/pci_root.c:__acpi_pci_root_release_info",
        "drivers/amba/bus.c:amba_device_try_add",
        "drivers/amba/bus.c:amba_device_release",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/base/platform.c:platform_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490682792,
      "name": "release_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int release_resource(struct resource * old)
```

```json
{
  "name": "release_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224749460,
      "name": "release_resource",
      "external": true,
      "loc": "kernel/resource.c:310",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_resource_release",
        "kernel/kexec_core.c:crash_shrink_memory",
        "drivers/pci/probe.c:pci_bus_release_busn_res",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/setup-res.c:pci_release_resource",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/ecam.c:pci_ecam_free",
        "drivers/rapidio/rio.c:rio_release_outb_dbell",
        "drivers/rapidio/rio.c:rio_release_inb_dbell",
        "drivers/rapidio/rio.c:rio_release_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_release_inb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/amba/bus.c:amba_device_try_add",
        "drivers/amba/bus.c:amba_device_release",
        "drivers/base/platform.c:platform_device_add",
        "drivers/mfd/sm501.c:sm501_plat_remove",
        "drivers/mfd/sm501.c:sm501_pci_remove",
        "drivers/mfd/sm501.c:sm501_dev_remove",
        "drivers/mfd/sm501.c:sm501_pci_probe",
        "drivers/mfd/sm501.c:sm501_plat_probe",
        "drivers/mfd/sm501.c:sm501_init_dev",
        "drivers/mfd/t7l66xb.c:t7l66xb_remove",
        "drivers/mfd/t7l66xb.c:t7l66xb_probe",
        "drivers/mfd/t7l66xb.c:t7l66xb_probe",
        "drivers/mfd/tc6387xb.c:tc6387xb_remove",
        "drivers/mfd/tc6387xb.c:tc6387xb_probe",
        "drivers/mfd/tc6393xb.c:tc6393xb_remove",
        "drivers/mfd/tc6393xb.c:tc6393xb_probe",
        "drivers/memory/omap-gpmc.c:gpmc_cs_free",
        "drivers/memory/omap-gpmc.c:gpmc_cs_request",
        "drivers/memory/omap-gpmc.c:gpmc_cs_delete_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224749460,
      "name": "release_resource",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int release_resource(struct resource * old)
```

```json
{
  "name": "release_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283502512,
      "name": "release_resource",
      "external": true,
      "loc": "kernel/resource.c:310",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/pseries/pci_dlpar.c:remove_phb_dynamic",
        "arch/powerpc/platforms/pseries/pci_dlpar.c:remove_phb_dynamic",
        "kernel/resource.c:devm_resource_release",
        "kernel/kexec_core.c:crash_shrink_memory",
        "mm/memory_hotplug.c:__add_memory",
        "drivers/pci/probe.c:pci_bus_release_busn_res",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/setup-res.c:pci_release_resource",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/ecam.c:pci_ecam_free",
        "drivers/rapidio/rio.c:rio_release_outb_dbell",
        "drivers/rapidio/rio.c:rio_release_inb_dbell",
        "drivers/rapidio/rio.c:rio_release_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_release_inb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/base/platform.c:platform_device_add",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283502512,
      "name": "release_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int release_resource(struct resource * old)
```

```json
{
  "name": "release_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271414696,
      "name": "release_resource",
      "external": true,
      "loc": "kernel/resource.c:310",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_resource_release",
        "drivers/pci/probe.c:pci_bus_release_busn_res",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/setup-res.c:pci_release_resource",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/pci/ecam.c:pci_ecam_free",
        "drivers/rapidio/rio.c:rio_release_outb_dbell",
        "drivers/rapidio/rio.c:rio_release_inb_dbell",
        "drivers/rapidio/rio.c:rio_release_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_release_inb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/base/platform.c:platform_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271414696,
      "name": "release_resource",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int release_resource(struct resource * old)
```

```json
{
  "name": "release_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579508192,
      "name": "release_resource",
      "external": true,
      "loc": "kernel/resource.c:310",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "kernel/resource.c:devm_resource_release",
        "kernel/kexec_core.c:crash_shrink_memory",
        "mm/memory_hotplug.c:__add_memory",
        "drivers/pci/probe.c:pci_bus_release_busn_res",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/setup-res.c:pci_release_resource",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/rapidio/rio.c:rio_release_outb_dbell",
        "drivers/rapidio/rio.c:rio_release_inb_dbell",
        "drivers/rapidio/rio.c:rio_release_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_release_inb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/acpi/pci_root.c:acpi_pci_root_release_info",
        "drivers/acpi/pci_root.c:__acpi_pci_root_release_info",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/intel-gtt.c:i9xx_cleanup",
        "drivers/base/platform.c:platform_device_add",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_release_resources",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert",
        "arch/x86/pci/mmconfig-shared.c:free_all_mmcfg",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508192,
      "name": "release_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int release_resource(struct resource * old)
```

```json
{
  "name": "release_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579436992,
      "name": "release_resource",
      "external": true,
      "loc": "kernel/resource.c:310",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "kernel/resource.c:devm_resource_release",
        "kernel/kexec_core.c:crash_shrink_memory",
        "mm/memory_hotplug.c:__add_memory",
        "drivers/pci/probe.c:pci_bus_release_busn_res",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/setup-res.c:pci_release_resource",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/rapidio/rio.c:rio_release_outb_dbell",
        "drivers/rapidio/rio.c:rio_release_inb_dbell",
        "drivers/rapidio/rio.c:rio_release_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_release_inb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/acpi/pci_root.c:acpi_pci_root_release_info",
        "drivers/acpi/pci_root.c:__acpi_pci_root_release_info",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/intel-gtt.c:i9xx_cleanup",
        "drivers/base/platform.c:platform_device_add",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_release_resources",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert",
        "arch/x86/pci/mmconfig-shared.c:free_all_mmcfg",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579436992,
      "name": "release_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int release_resource(struct resource * old)
```

```json
{
  "name": "release_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579508112,
      "name": "release_resource",
      "external": true,
      "loc": "kernel/resource.c:310",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "kernel/resource.c:devm_resource_release",
        "kernel/kexec_core.c:crash_shrink_memory",
        "mm/memory_hotplug.c:__add_memory",
        "drivers/pci/probe.c:pci_bus_release_busn_res",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/setup-res.c:pci_release_resource",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/rapidio/rio.c:rio_release_outb_dbell",
        "drivers/rapidio/rio.c:rio_release_inb_dbell",
        "drivers/rapidio/rio.c:rio_release_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_release_inb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/acpi/pci_root.c:acpi_pci_root_release_info",
        "drivers/acpi/pci_root.c:__acpi_pci_root_release_info",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/intel-gtt.c:i9xx_cleanup",
        "drivers/base/platform.c:platform_device_add",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_release_resources",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert",
        "arch/x86/pci/mmconfig-shared.c:free_all_mmcfg",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508112,
      "name": "release_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int release_resource(struct resource * old)
```

```json
{
  "name": "release_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579540912,
      "name": "release_resource",
      "external": true,
      "loc": "kernel/resource.c:310",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "kernel/resource.c:devm_resource_release",
        "kernel/kexec_core.c:crash_shrink_memory",
        "mm/memory_hotplug.c:__add_memory",
        "drivers/pci/probe.c:pci_bus_release_busn_res",
        "drivers/pci/remove.c:pci_remove_bus_device",
        "drivers/pci/setup-res.c:pci_release_resource",
        "drivers/pci/setup-bus.c:pci_reassign_bridge_resources",
        "drivers/pci/setup-bus.c:pci_bus_release_bridge_resources",
        "drivers/pci/setup-bus.c:__assign_resources_sorted",
        "drivers/rapidio/rio.c:rio_release_outb_dbell",
        "drivers/rapidio/rio.c:rio_release_inb_dbell",
        "drivers/rapidio/rio.c:rio_release_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_release_inb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/acpi/pci_root.c:acpi_pci_root_release_info",
        "drivers/acpi/pci_root.c:__acpi_pci_root_release_info",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/char/agp/amd64-agp.c:agp_amd64_cleanup",
        "drivers/char/agp/intel-gtt.c:i9xx_cleanup",
        "drivers/base/platform.c:platform_device_add",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_release_resources",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert",
        "arch/x86/pci/mmconfig-shared.c:free_all_mmcfg",
        "arch/x86/pci/fixup.c:pci_fixup_video"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540912,
      "name": "release_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
