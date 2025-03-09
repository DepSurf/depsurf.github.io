# Function: <code>update_adapter_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_adapter_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583353927,
      "name": "update_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:94",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot",
        "drivers/pci/hotplug/cpci_hotplug_core.c:check_slots",
        "drivers/pci/hotplug/cpci_hotplug_core.c:check_slots"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_adapter_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583668618,
      "name": "update_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:94",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:check_slots",
        "drivers/pci/hotplug/cpci_hotplug_core.c:check_slots",
        "drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_adapter_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583806842,
      "name": "update_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:94",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:check_slots",
        "drivers/pci/hotplug/cpci_hotplug_core.c:check_slots",
        "drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int update_adapter_status(struct hotplug_slot * hotplug_slot, u8 value)
```

```json
{
  "name": "update_adapter_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583848128,
      "name": "update_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:95",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:check_slots",
        "drivers/pci/hotplug/cpci_hotplug_core.c:check_slots",
        "drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583848128,
      "name": "update_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
int update_adapter_status(struct hotplug_slot * hotplug_slot, u8 value)
```

```json
{
  "name": "update_adapter_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584111696,
      "name": "update_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:95",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:check_slots",
        "drivers/pci/hotplug/cpci_hotplug_core.c:check_slots",
        "drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584111696,
      "name": "update_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
int update_adapter_status(struct hotplug_slot * hotplug_slot, u8 value)
```

```json
{
  "name": "update_adapter_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584312336,
      "name": "update_adapter_status",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:81",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:check_slots",
        "drivers/pci/hotplug/cpci_hotplug_core.c:check_slots",
        "drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584312336,
      "name": "update_adapter_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int update_adapter_status(struct hotplug_slot * hotplug_slot, u8 value)
```
</details>
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
int update_adapter_status(struct hotplug_slot * hotplug_slot, u8 value)
```
</details>
</li>
</ul>
