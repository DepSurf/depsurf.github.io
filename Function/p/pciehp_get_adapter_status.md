# Function: <code>pciehp_get_adapter_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pciehp_get_adapter_status(struct slot * slot, u8 * status)
```

```json
{
  "name": "pciehp_get_adapter_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583369152,
      "name": "pciehp_get_adapter_status",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:416",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_isr"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:get_adapter_status",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_resume",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe",
        "drivers/pci/hotplug/pciehp_ctrl.c:handle_surprise_event",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583370608,
      "name": "pciehp_get_adapter_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void pciehp_get_adapter_status(struct slot * slot, u8 * status)
```

```json
{
  "name": "pciehp_get_adapter_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583682496,
      "name": "pciehp_get_adapter_status",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:416",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_isr"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_resume",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe",
        "drivers/pci/hotplug/pciehp_core.c:get_adapter_status",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:handle_surprise_event",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583683968,
      "name": "pciehp_get_adapter_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void pciehp_get_adapter_status(struct slot * slot, u8 * status)
```

```json
{
  "name": "pciehp_get_adapter_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583822192,
      "name": "pciehp_get_adapter_status",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:428",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_resume",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe",
        "drivers/pci/hotplug/pciehp_core.c:get_adapter_status",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583822192,
      "name": "pciehp_get_adapter_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void pciehp_get_adapter_status(struct slot * slot, u8 * status)
```

```json
{
  "name": "pciehp_get_adapter_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583865072,
      "name": "pciehp_get_adapter_status",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:428",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_resume",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe",
        "drivers/pci/hotplug/pciehp_core.c:get_adapter_status",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583865072,
      "name": "pciehp_get_adapter_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void pciehp_get_adapter_status(struct slot * slot, u8 * status)
```

```json
{
  "name": "pciehp_get_adapter_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584128672,
      "name": "pciehp_get_adapter_status",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:425",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_resume",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe",
        "drivers/pci/hotplug/pciehp_core.c:get_adapter_status",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584128672,
      "name": "pciehp_get_adapter_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void pciehp_get_adapter_status(struct slot * slot, u8 * status)
```

```json
{
  "name": "pciehp_get_adapter_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584329216,
      "name": "pciehp_get_adapter_status",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:405",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_resume",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe",
        "drivers/pci/hotplug/pciehp_core.c:get_adapter_status",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584329216,
      "name": "pciehp_get_adapter_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void pciehp_get_adapter_status(struct slot * slot, u8 * status)
```
</details>
</li>
</ul>
