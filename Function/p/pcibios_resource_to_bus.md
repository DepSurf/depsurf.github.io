# Function: <code>pcibios_resource_to_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus * bus, struct pci_bus_region * region, struct resource * res)
```

```json
{
  "name": "pcibios_resource_to_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583248000,
      "name": "pcibios_resource_to_bus",
      "external": true,
      "loc": "drivers/pci/host-bridge.c:48",
      "file": "drivers/pci/host-bridge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-bus.c:iov_resources_unassigned",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583248000,
      "name": "pcibios_resource_to_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void pcibios_resource_to_bus(struct pci_bus * bus, struct pci_bus_region * region, struct resource * res)
```

```json
{
  "name": "pcibios_resource_to_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583557376,
      "name": "pcibios_resource_to_bus",
      "external": true,
      "loc": "drivers/pci/host-bridge.c:49",
      "file": "drivers/pci/host-bridge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-bus.c:iov_resources_unassigned",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583557376,
      "name": "pcibios_resource_to_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void pcibios_resource_to_bus(struct pci_bus * bus, struct pci_bus_region * region, struct resource * res)
```

```json
{
  "name": "pcibios_resource_to_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583694240,
      "name": "pcibios_resource_to_bus",
      "external": true,
      "loc": "drivers/pci/host-bridge.c:49",
      "file": "drivers/pci/host-bridge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-bus.c:iov_resources_unassigned",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583694240,
      "name": "pcibios_resource_to_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void pcibios_resource_to_bus(struct pci_bus * bus, struct pci_bus_region * region, struct resource * res)
```

```json
{
  "name": "pcibios_resource_to_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583734768,
      "name": "pcibios_resource_to_bus",
      "external": true,
      "loc": "drivers/pci/host-bridge.c:49",
      "file": "drivers/pci/host-bridge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-bus.c:iov_resources_unassigned",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583734768,
      "name": "pcibios_resource_to_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void pcibios_resource_to_bus(struct pci_bus * bus, struct pci_bus_region * region, struct resource * res)
```

```json
{
  "name": "pcibios_resource_to_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583993424,
      "name": "pcibios_resource_to_bus",
      "external": true,
      "loc": "drivers/pci/host-bridge.c:49",
      "file": "drivers/pci/host-bridge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-res.c:pci_update_resource",
        "drivers/pci/setup-bus.c:iov_resources_unassigned",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583993424,
      "name": "pcibios_resource_to_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void pcibios_resource_to_bus(struct pci_bus * bus, struct pci_bus_region * region, struct resource * res)
```

```json
{
  "name": "pcibios_resource_to_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584187872,
      "name": "pcibios_resource_to_bus",
      "external": true,
      "loc": "drivers/pci/host-bridge.c:50",
      "file": "drivers/pci/host-bridge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-bus.c:iov_resources_unassigned",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584187872,
      "name": "pcibios_resource_to_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void pcibios_resource_to_bus(struct pci_bus * bus, struct pci_bus_region * region, struct resource * res)
```

```json
{
  "name": "pcibios_resource_to_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584276576,
      "name": "pcibios_resource_to_bus",
      "external": true,
      "loc": "drivers/pci/host-bridge.c:50",
      "file": "drivers/pci/host-bridge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-bus.c:iov_resources_unassigned",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584276576,
      "name": "pcibios_resource_to_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void pcibios_resource_to_bus(struct pci_bus * bus, struct pci_bus_region * region, struct resource * res)
```

```json
{
  "name": "pcibios_resource_to_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584471056,
      "name": "pcibios_resource_to_bus",
      "external": true,
      "loc": "drivers/pci/host-bridge.c:50",
      "file": "drivers/pci/host-bridge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-bus.c:iov_resources_unassigned",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584471056,
      "name": "pcibios_resource_to_bus",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus * bus, struct pci_bus_region * region, struct resource * res)
```

```json
{
  "name": "pcibios_resource_to_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584606336,
      "name": "pcibios_resource_to_bus",
      "external": true,
      "loc": "drivers/pci/host-bridge.c:50",
      "file": "drivers/pci/host-bridge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-bus.c:iov_resources_unassigned",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584606336,
      "name": "pcibios_resource_to_bus",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus * bus, struct pci_bus_region * region, struct resource * res)
```

```json
{
  "name": "pcibios_resource_to_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585283488,
      "name": "pcibios_resource_to_bus",
      "external": true,
      "loc": "drivers/pci/host-bridge.c:50",
      "file": "drivers/pci/host-bridge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-res.c:pci_std_update_resource",
        "drivers/pci/setup-bus.c:iov_resources_unassigned",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/amd64-agp.c:fix_northbridge",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585283488,
      "name": "pcibios_resource_to_bus",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus * bus, struct pci_bus_region * region, struct resource * res)
```

```json
{
  "name": "pcibios_resource_to_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585438048,
      "name": "pcibios_resource_to_bus",
      "external": true,
      "loc": "drivers/pci/host-bridge.c:50",
      "file": "drivers/pci/host-bridge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-res.c:pci_std_update_resource",
        "drivers/pci/setup-bus.c:iov_resources_unassigned",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/amd64-agp.c:fix_northbridge",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585438048,
      "name": "pcibios_resource_to_bus",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus * bus, struct pci_bus_region * region, struct resource * res)
```

```json
{
  "name": "pcibios_resource_to_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585318176,
      "name": "pcibios_resource_to_bus",
      "external": true,
      "loc": "drivers/pci/host-bridge.c:50",
      "file": "drivers/pci/host-bridge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-res.c:pci_std_update_resource",
        "drivers/pci/setup-bus.c:iov_resources_unassigned",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/amd64-agp.c:fix_northbridge",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585318176,
      "name": "pcibios_resource_to_bus",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus * bus, struct pci_bus_region * region, struct resource * res)
```

```json
{
  "name": "pcibios_resource_to_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585774096,
      "name": "pcibios_resource_to_bus",
      "external": true,
      "loc": "drivers/pci/host-bridge.c:51",
      "file": "drivers/pci/host-bridge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-res.c:pci_std_update_resource",
        "drivers/pci/setup-bus.c:iov_resources_unassigned",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/amd64-agp.c:fix_northbridge",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585774096,
      "name": "pcibios_resource_to_bus",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus * bus, struct pci_bus_region * region, struct resource * res)
```

```json
{
  "name": "pcibios_resource_to_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586959968,
      "name": "pcibios_resource_to_bus",
      "external": true,
      "loc": "drivers/pci/host-bridge.c:51",
      "file": "drivers/pci/host-bridge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-res.c:pci_std_update_resource",
        "drivers/pci/setup-bus.c:iov_resources_unassigned",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/amd64-agp.c:fix_northbridge",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586959968,
      "name": "pcibios_resource_to_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void pcibios_resource_to_bus(struct pci_bus * bus, struct pci_bus_region * region, struct resource * res)
```

```json
{
  "name": "pcibios_resource_to_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588123424,
      "name": "pcibios_resource_to_bus",
      "external": true,
      "loc": "drivers/pci/host-bridge.c:51",
      "file": "drivers/pci/host-bridge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-res.c:pci_std_update_resource",
        "drivers/pci/setup-bus.c:iov_resources_unassigned",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/pci/p2pdma.c:pci_p2pdma_add_resource",
        "drivers/pci/p2pdma.c:pci_p2pdma_add_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/amd64-agp.c:fix_northbridge",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588123424,
      "name": "pcibios_resource_to_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void pcibios_resource_to_bus(struct pci_bus * bus, struct pci_bus_region * region, struct resource * res)
```

```json
{
  "name": "pcibios_resource_to_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588398672,
      "name": "pcibios_resource_to_bus",
      "external": true,
      "loc": "drivers/pci/host-bridge.c:51",
      "file": "drivers/pci/host-bridge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-res.c:pci_std_update_resource",
        "drivers/pci/setup-bus.c:iov_resources_unassigned",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/pci/p2pdma.c:pci_p2pdma_add_resource",
        "drivers/pci/p2pdma.c:pci_p2pdma_add_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/amd64-agp.c:fix_northbridge",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588398672,
      "name": "pcibios_resource_to_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void pcibios_resource_to_bus(struct pci_bus * bus, struct pci_bus_region * region, struct resource * res)
```

```json
{
  "name": "pcibios_resource_to_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588694656,
      "name": "pcibios_resource_to_bus",
      "external": true,
      "loc": "drivers/pci/host-bridge.c:51",
      "file": "drivers/pci/host-bridge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-res.c:pci_std_update_resource",
        "drivers/pci/setup-bus.c:iov_resources_unassigned",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/pci/p2pdma.c:pci_p2pdma_add_resource",
        "drivers/pci/p2pdma.c:pci_p2pdma_add_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/amd64-agp.c:fix_northbridge",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588694656,
      "name": "pcibios_resource_to_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void pcibios_resource_to_bus(struct pci_bus * bus, struct pci_bus_region * region, struct resource * res)
```

```json
{
  "name": "pcibios_resource_to_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496845120,
      "name": "pcibios_resource_to_bus",
      "external": true,
      "loc": "drivers/pci/host-bridge.c:50",
      "file": "drivers/pci/host-bridge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-bus.c:iov_resources_unassigned",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496845120,
      "name": "pcibios_resource_to_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void pcibios_resource_to_bus(struct pci_bus * bus, struct pci_bus_region * region, struct resource * res)
```

```json
{
  "name": "pcibios_resource_to_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230125592,
      "name": "pcibios_resource_to_bus",
      "external": true,
      "loc": "drivers/pci/host-bridge.c:50",
      "file": "drivers/pci/host-bridge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_resource",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-bus.c:iov_resources_unassigned",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230125592,
      "name": "pcibios_resource_to_bus",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus * bus, struct pci_bus_region * region, struct resource * res)
```

```json
{
  "name": "pcibios_resource_to_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290921824,
      "name": "pcibios_resource_to_bus",
      "external": true,
      "loc": "drivers/pci/host-bridge.c:50",
      "file": "drivers/pci/host-bridge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/pci-common.c:pcibios_setup_bus_self",
        "arch/powerpc/kernel/pci-common.c:pci_resource_to_user",
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-bus.c:iov_resources_unassigned",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init",
        "drivers/char/agp/generic.c:agp3_generic_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290921824,
      "name": "pcibios_resource_to_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void pcibios_resource_to_bus(struct pci_bus * bus, struct pci_bus_region * region, struct resource * res)
```

```json
{
  "name": "pcibios_resource_to_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275549636,
      "name": "pcibios_resource_to_bus",
      "external": true,
      "loc": "drivers/pci/host-bridge.c:50",
      "file": "drivers/pci/host-bridge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-bus.c:iov_resources_unassigned",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275549636,
      "name": "pcibios_resource_to_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void pcibios_resource_to_bus(struct pci_bus * bus, struct pci_bus_region * region, struct resource * res)
```

```json
{
  "name": "pcibios_resource_to_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584558496,
      "name": "pcibios_resource_to_bus",
      "external": true,
      "loc": "drivers/pci/host-bridge.c:50",
      "file": "drivers/pci/host-bridge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-bus.c:iov_resources_unassigned",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584558496,
      "name": "pcibios_resource_to_bus",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus * bus, struct pci_bus_region * region, struct resource * res)
```

```json
{
  "name": "pcibios_resource_to_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584486656,
      "name": "pcibios_resource_to_bus",
      "external": true,
      "loc": "drivers/pci/host-bridge.c:50",
      "file": "drivers/pci/host-bridge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-bus.c:iov_resources_unassigned",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584486656,
      "name": "pcibios_resource_to_bus",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus * bus, struct pci_bus_region * region, struct resource * res)
```

```json
{
  "name": "pcibios_resource_to_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584556496,
      "name": "pcibios_resource_to_bus",
      "external": true,
      "loc": "drivers/pci/host-bridge.c:50",
      "file": "drivers/pci/host-bridge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-bus.c:iov_resources_unassigned",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584556496,
      "name": "pcibios_resource_to_bus",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus * bus, struct pci_bus_region * region, struct resource * res)
```

```json
{
  "name": "pcibios_resource_to_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584664240,
      "name": "pcibios_resource_to_bus",
      "external": true,
      "loc": "drivers/pci/host-bridge.c:50",
      "file": "drivers/pci/host-bridge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:__pci_read_base",
        "drivers/pci/rom.c:pci_enable_rom",
        "drivers/pci/setup-bus.c:iov_resources_unassigned",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref",
        "drivers/pci/setup-bus.c:pci_setup_bridge_mmio",
        "drivers/pci/setup-bus.c:pci_setup_bridge_io",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/setup-bus.c:pci_setup_cardbus",
        "drivers/pci/iov.c:pci_iov_update_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init",
        "drivers/char/agp/generic.c:agp3_generic_configure",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:intel_7505_configure",
        "drivers/char/agp/intel-agp.c:intel_830mp_configure",
        "drivers/char/agp/intel-agp.c:intel_860_configure",
        "drivers/char/agp/intel-agp.c:intel_850_configure",
        "drivers/char/agp/intel-agp.c:intel_845_configure",
        "drivers/char/agp/intel-agp.c:intel_840_configure",
        "drivers/char/agp/intel-agp.c:intel_820_configure",
        "drivers/char/agp/intel-agp.c:intel_815_configure",
        "drivers/char/agp/intel-agp.c:intel_configure",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/via-agp.c:via_configure_agp3",
        "drivers/char/agp/via-agp.c:via_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584664240,
      "name": "pcibios_resource_to_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
