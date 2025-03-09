# Function: <code>pci_reset_bridge_secondary_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_reset_bridge_secondary_bus(struct pci_dev * dev)
```

```json
{
  "name": "pci_reset_bridge_secondary_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583269376,
      "name": "pci_reset_bridge_secondary_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:3549",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_try_reset_bus"
      ],
      "caller_func": [
        "drivers/pci/pcie/aer/aerdrv_core.c:do_recovery",
        "drivers/pci/pcie/aer/aerdrv.c:aer_root_reset",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583269376,
      "name": "pci_reset_bridge_secondary_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void pci_reset_bridge_secondary_bus(struct pci_dev * dev)
```

```json
{
  "name": "pci_reset_bridge_secondary_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583581268,
      "name": "pci_reset_bridge_secondary_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:3870",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_try_reset_bus"
      ],
      "caller_func": [
        "drivers/pci/pcie/aer/aerdrv_core.c:do_recovery",
        "drivers/pci/pcie/aer/aerdrv.c:aer_root_reset",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583579808,
      "name": "pci_reset_bridge_secondary_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void pci_reset_bridge_secondary_bus(struct pci_dev * dev)
```

```json
{
  "name": "pci_reset_bridge_secondary_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583718324,
      "name": "pci_reset_bridge_secondary_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:3908",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_try_reset_bus"
      ],
      "caller_func": [
        "drivers/pci/pcie/aer/aerdrv_core.c:do_recovery",
        "drivers/pci/pcie/aer/aerdrv.c:aer_root_reset",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583716864,
      "name": "pci_reset_bridge_secondary_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void pci_reset_bridge_secondary_bus(struct pci_dev * dev)
```

```json
{
  "name": "pci_reset_bridge_secondary_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583758638,
      "name": "pci_reset_bridge_secondary_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:4026",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_try_reset_bus",
        "drivers/pci/pci.c:pci_reset_bus",
        "drivers/pci/pci.c:pci_parent_bus_reset"
      ],
      "caller_func": [
        "drivers/pci/pcie/aer/aerdrv_core.c:do_recovery",
        "drivers/pci/pcie/aer/aerdrv.c:aer_root_reset",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583757808,
      "name": "pci_reset_bridge_secondary_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void pci_reset_bridge_secondary_bus(struct pci_dev * dev)
```

```json
{
  "name": "pci_reset_bridge_secondary_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584017281,
      "name": "pci_reset_bridge_secondary_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:4063",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_parent_bus_reset"
      ],
      "caller_func": [
        "drivers/pci/pcie/aer/aerdrv_core.c:do_recovery",
        "drivers/pci/pcie/aer/aerdrv.c:aer_root_reset",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584017168,
      "name": "pci_reset_bridge_secondary_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int pci_reset_bridge_secondary_bus(struct pci_dev * dev)
```

```json
{
  "name": "pci_reset_bridge_secondary_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584213072,
      "name": "pci_reset_bridge_secondary_bus",
      "external": true,
      "loc": "drivers/pci/pci.c:4310",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_try_reset_bus",
        "drivers/pci/pci.c:pci_reset_bus",
        "drivers/pci/pci.c:pci_parent_bus_reset",
        "drivers/pci/pcie/err.c:pcie_do_fatal_recovery",
        "drivers/pci/pcie/aer.c:aer_root_reset",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584213072,
      "name": "pci_reset_bridge_secondary_bus",
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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int pci_reset_bridge_secondary_bus(struct pci_dev * dev)
```
</details>
</li>
</ul>
