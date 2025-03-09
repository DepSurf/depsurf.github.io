# Function: <code>request_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579394000,
      "name": "request_resource",
      "external": true,
      "loc": "kernel/resource.c:309",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:reserve_standard_io_resources",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/paravirt.c:paravirt_disable_iospace",
        "kernel/resource.c:reserve_setup",
        "mm/memory_hotplug.c:add_memory",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_dbell",
        "drivers/rapidio/rio.c:rio_request_outb_dbell",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/char/agp/intel-gtt.c:i9xx_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394000,
      "name": "request_resource",
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
int request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579405952,
      "name": "request_resource",
      "external": true,
      "loc": "kernel/resource.c:328",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:reserve_standard_io_resources",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/paravirt.c:paravirt_disable_iospace",
        "kernel/resource.c:reserve_setup",
        "mm/memory_hotplug.c:add_memory",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/rapidio/rio.c:rio_request_outb_dbell",
        "drivers/rapidio/rio.c:rio_request_inb_dbell",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/char/agp/intel-gtt.c:i9xx_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579405952,
      "name": "request_resource",
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
int request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579426256,
      "name": "request_resource",
      "external": true,
      "loc": "kernel/resource.c:328",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:reserve_standard_io_resources",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/paravirt.c:paravirt_disable_iospace",
        "kernel/resource.c:reserve_setup",
        "mm/memory_hotplug.c:add_memory",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/rapidio/rio.c:rio_request_outb_dbell",
        "drivers/rapidio/rio.c:rio_request_inb_dbell",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579426256,
      "name": "request_resource",
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
int request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579414016,
      "name": "request_resource",
      "external": true,
      "loc": "kernel/resource.c:328",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:reserve_standard_io_resources",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/paravirt.c:paravirt_disable_iospace",
        "kernel/resource.c:reserve_setup",
        "mm/memory_hotplug.c:add_memory",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/rapidio/rio.c:rio_request_outb_dbell",
        "drivers/rapidio/rio.c:rio_request_inb_dbell",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579414016,
      "name": "request_resource",
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
int request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579441888,
      "name": "request_resource",
      "external": true,
      "loc": "kernel/resource.c:328",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:reserve_standard_io_resources",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/paravirt.c:paravirt_disable_iospace",
        "kernel/resource.c:reserve_setup",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/rapidio/rio.c:rio_request_outb_dbell",
        "drivers/rapidio/rio.c:rio_request_inb_dbell",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579441888,
      "name": "request_resource",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602910470,
      "name": "request_resource",
      "external": true,
      "loc": "kernel/resource.c:295",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:reserve_setup"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:reserve_standard_io_resources",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/paravirt.c:paravirt_disable_iospace",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/rapidio/rio.c:rio_request_outb_dbell",
        "drivers/rapidio/rio.c:rio_request_inb_dbell",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579460592,
      "name": "request_resource",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604708078,
      "name": "request_resource",
      "external": true,
      "loc": "kernel/resource.c:295",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:reserve_setup"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:reserve_standard_io_resources",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/paravirt.c:paravirt_disable_iospace",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/rapidio/rio.c:rio_request_outb_dbell",
        "drivers/rapidio/rio.c:rio_request_inb_dbell",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/eisa/eisa-bus.c:eisa_root_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579494240,
      "name": "request_resource",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604808406,
      "name": "request_resource",
      "external": true,
      "loc": "kernel/resource.c:296",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:reserve_setup"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:reserve_standard_io_resources",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/paravirt.c:paravirt_disable_iospace",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/rapidio/rio.c:rio_request_outb_dbell",
        "drivers/rapidio/rio.c:rio_request_inb_dbell",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/eisa/eisa-bus.c:eisa_root_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579512272,
      "name": "request_resource",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604842719,
      "name": "request_resource",
      "external": true,
      "loc": "kernel/resource.c:296",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:reserve_setup"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:reserve_standard_io_resources",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/paravirt.c:paravirt_disable_iospace",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/rapidio/rio.c:rio_request_outb_dbell",
        "drivers/rapidio/rio.c:rio_request_inb_dbell",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579538448,
      "name": "request_resource",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609177394,
      "name": "request_resource",
      "external": true,
      "loc": "kernel/resource.c:296",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:reserve_setup"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:reserve_standard_io_resources",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/paravirt.c:paravirt_disable_iospace",
        "drivers/pci/setup-bus.c:assign_fixed_resource_on_bus",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/rapidio/rio.c:rio_request_outb_dbell",
        "drivers/rapidio/rio.c:rio_request_inb_dbell",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/char/agp/intel-gtt.c:intel_i9xx_setup_flush",
        "drivers/char/agp/intel-gtt.c:intel_i965_g33_setup_chipset_flush",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe_mmaps",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_request_resources",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579569680,
      "name": "request_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612242828,
      "name": "request_resource",
      "external": true,
      "loc": "kernel/resource.c:296",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:reserve_setup"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:reserve_standard_io_resources",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/paravirt.c:paravirt_disable_iospace",
        "drivers/pci/setup-bus.c:assign_fixed_resource_on_bus",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/rapidio/rio.c:rio_request_outb_dbell",
        "drivers/rapidio/rio.c:rio_request_inb_dbell",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/char/agp/intel-gtt.c:intel_i9xx_setup_flush",
        "drivers/char/agp/intel-gtt.c:intel_i965_g33_setup_chipset_flush",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe_mmaps",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_request_resources",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551088,
      "name": "request_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614383180,
      "name": "request_resource",
      "external": true,
      "loc": "kernel/resource.c:295",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:reserve_setup"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:reserve_standard_io_resources",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/paravirt.c:paravirt_disable_iospace",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/rapidio/rio.c:rio_request_outb_dbell",
        "drivers/rapidio/rio.c:rio_request_inb_dbell",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_request_resources",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579555712,
      "name": "request_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615316190,
      "name": "request_resource",
      "external": true,
      "loc": "kernel/resource.c:295",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:reserve_setup"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:reserve_standard_io_resources",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/paravirt.c:paravirt_disable_iospace",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/rapidio/rio.c:rio_request_outb_dbell",
        "drivers/rapidio/rio.c:rio_request_inb_dbell",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_finish_enable",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_request_resources",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579628288,
      "name": "request_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617098061,
      "name": "request_resource",
      "external": true,
      "loc": "kernel/resource.c:282",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:reserve_setup"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:reserve_standard_io_resources",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/paravirt.c:paravirt_disable_iospace",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/rapidio/rio.c:rio_request_outb_dbell",
        "drivers/rapidio/rio.c:rio_request_inb_dbell",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_finish_enable",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_request_resources",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579723376,
      "name": "request_resource",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627759258,
      "name": "request_resource",
      "external": true,
      "loc": "kernel/resource.c:282",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:reserve_setup"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:reserve_standard_io_resources",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/paravirt.c:paravirt_disable_iospace",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/rapidio/rio.c:rio_request_outb_dbell",
        "drivers/rapidio/rio.c:rio_request_inb_dbell",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_request_resources",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851792,
      "name": "request_resource",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619519850,
      "name": "request_resource",
      "external": true,
      "loc": "kernel/resource.c:282",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:reserve_setup"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:reserve_standard_io_resources",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/paravirt.c:paravirt_disable_iospace",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/rapidio/rio.c:rio_request_outb_dbell",
        "drivers/rapidio/rio.c:rio_request_inb_dbell",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_request_resources",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579902048,
      "name": "request_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621816858,
      "name": "request_resource",
      "external": true,
      "loc": "kernel/resource.c:282",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:reserve_setup"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:reserve_standard_io_resources",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/paravirt.c:paravirt_disable_iospace",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/rapidio/rio.c:rio_request_outb_dbell",
        "drivers/rapidio/rio.c:rio_request_inb_dbell",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_request_resources",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579940848,
      "name": "request_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336510875424,
      "name": "request_resource",
      "external": true,
      "loc": "kernel/resource.c:296",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:reserve_setup"
      ],
      "caller_func": [
        "arch/arm64/kernel/setup.c:setup_arch",
        "arch/arm64/kernel/setup.c:setup_arch",
        "arch/arm64/kernel/setup.c:setup_arch",
        "arch/arm64/kernel/setup.c:setup_arch",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/rapidio/rio.c:rio_request_outb_dbell",
        "drivers/rapidio/rio.c:rio_request_inb_dbell",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/amba/bus.c:amba_device_try_add",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490684736,
      "name": "request_resource",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243362076,
      "name": "request_resource",
      "external": true,
      "loc": "kernel/resource.c:296",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:reserve_setup"
      ],
      "caller_func": [
        "arch/arm/kernel/setup.c:setup_arch",
        "arch/arm/kernel/setup.c:setup_arch",
        "arch/arm/kernel/setup.c:setup_arch",
        "arch/arm/kernel/setup.c:setup_arch",
        "arch/arm/kernel/setup.c:setup_arch",
        "arch/arm/kernel/setup.c:setup_arch",
        "arch/arm/kernel/setup.c:setup_arch",
        "arch/arm/kernel/setup.c:setup_arch",
        "arch/arm/kernel/bios32.c:pci_common_init_dev",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/rapidio/rio.c:rio_request_outb_dbell",
        "drivers/rapidio/rio.c:rio_request_inb_dbell",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/amba/bus.c:amba_device_try_add",
        "drivers/mfd/t7l66xb.c:t7l66xb_probe",
        "drivers/mfd/tc6387xb.c:tc6387xb_probe",
        "drivers/mfd/tc6393xb.c:tc6393xb_probe",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem",
        "drivers/memory/omap-gpmc.c:gpmc_cs_insert_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224754108,
      "name": "request_resource",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302505544,
      "name": "request_resource",
      "external": true,
      "loc": "kernel/resource.c:296",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:reserve_setup"
      ],
      "caller_func": [
        "arch/powerpc/kernel/pci-common.c:pcibios_resource_survey",
        "arch/powerpc/kernel/pci-common.c:pcibios_resource_survey",
        "arch/powerpc/kernel/pci-common.c:pcibios_allocate_resources",
        "arch/powerpc/kernel/pci-common.c:pcibios_allocate_bus_resources",
        "arch/powerpc/mm/mem.c:add_system_ram_resources",
        "arch/powerpc/sysdev/i8259.c:i8259_init",
        "arch/powerpc/sysdev/i8259.c:i8259_init",
        "arch/powerpc/sysdev/i8259.c:i8259_init",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/rapidio/rio.c:rio_request_outb_dbell",
        "drivers/rapidio/rio.c:rio_request_inb_dbell",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283509344,
      "name": "request_resource",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936270617640,
      "name": "request_resource",
      "external": true,
      "loc": "kernel/resource.c:296",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:reserve_setup"
      ],
      "caller_func": [
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/rapidio/rio.c:rio_request_outb_dbell",
        "drivers/rapidio/rio.c:rio_request_inb_dbell",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271418648,
      "name": "request_resource",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604747986,
      "name": "request_resource",
      "external": true,
      "loc": "kernel/resource.c:296",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:reserve_setup"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:reserve_standard_io_resources",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/paravirt.c:paravirt_disable_iospace",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/rapidio/rio.c:rio_request_outb_dbell",
        "drivers/rapidio/rio.c:rio_request_inb_dbell",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579512112,
      "name": "request_resource",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604715603,
      "name": "request_resource",
      "external": true,
      "loc": "kernel/resource.c:296",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:reserve_setup"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:reserve_standard_io_resources",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/paravirt.c:paravirt_disable_iospace",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/rapidio/rio.c:rio_request_outb_dbell",
        "drivers/rapidio/rio.c:rio_request_inb_dbell",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579440912,
      "name": "request_resource",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604825553,
      "name": "request_resource",
      "external": true,
      "loc": "kernel/resource.c:296",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:reserve_setup"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:reserve_standard_io_resources",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/paravirt.c:paravirt_disable_iospace",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/rapidio/rio.c:rio_request_outb_dbell",
        "drivers/rapidio/rio.c:rio_request_inb_dbell",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579512032,
      "name": "request_resource",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604846876,
      "name": "request_resource",
      "external": true,
      "loc": "kernel/resource.c:296",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:reserve_setup"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:reserve_standard_io_resources",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/paravirt.c:paravirt_disable_iospace",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/rapidio/rio.c:rio_request_outb_dbell",
        "drivers/rapidio/rio.c:rio_request_inb_dbell",
        "drivers/rapidio/rio.c:rio_request_outb_mbox",
        "drivers/rapidio/rio.c:rio_request_inb_mbox",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544960,
      "name": "request_resource",
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
