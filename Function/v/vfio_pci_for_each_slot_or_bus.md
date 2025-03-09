# Function: <code>vfio_pci_for_each_slot_or_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_pci_for_each_slot_or_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587067490,
      "name": "vfio_pci_for_each_slot_or_bus",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:640",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfio_pci_for_each_slot_or_bus(struct pci_dev * pdev, int (*)(struct pci_dev *, void *) fn, void * data, bool slot)
```

```json
{
  "name": "vfio_pci_for_each_slot_or_bus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587910147,
      "name": "vfio_pci_for_each_slot_or_bus",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:703",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_attach",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl"
      ],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587901968,
      "name": "vfio_pci_for_each_slot_or_bus",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int vfio_pci_for_each_slot_or_bus(struct pci_dev * pdev, int (*)(struct pci_dev *, void *) fn, void * data, bool slot)
```

```json
{
  "name": "vfio_pci_for_each_slot_or_bus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587971907,
      "name": "vfio_pci_for_each_slot_or_bus",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:743",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_attach",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl"
      ],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587962560,
      "name": "vfio_pci_for_each_slot_or_bus",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int vfio_pci_for_each_slot_or_bus(struct pci_dev * pdev, int (*)(struct pci_dev *, void *) fn, void * data, bool slot)
```

```json
{
  "name": "vfio_pci_for_each_slot_or_bus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587853960,
      "name": "vfio_pci_for_each_slot_or_bus",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:725",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl"
      ],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587844848,
      "name": "vfio_pci_for_each_slot_or_bus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_pci_for_each_slot_or_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588452990,
      "name": "vfio_pci_for_each_slot_or_bus",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_core.c:585",
      "file": "drivers/vfio/pci/vfio_pci_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_dev_set_resettable",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_pci_for_each_slot_or_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589853963,
      "name": "vfio_pci_for_each_slot_or_bus",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_core.c:622",
      "file": "drivers/vfio/pci/vfio_pci_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_dev_set_resettable",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl"
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "vfio_pci_for_each_slot_or_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293397864,
      "name": "vfio_pci_for_each_slot_or_bus",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:640",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_pci_for_each_slot_or_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586715410,
      "name": "vfio_pci_for_each_slot_or_bus",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:640",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_pci_for_each_slot_or_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587022050,
      "name": "vfio_pci_for_each_slot_or_bus",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:640",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_pci_for_each_slot_or_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587129218,
      "name": "vfio_pci_for_each_slot_or_bus",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:640",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int vfio_pci_for_each_slot_or_bus(struct pci_dev * pdev, int (*)(struct pci_dev *, void *) fn, void * data, bool slot)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int vfio_pci_for_each_slot_or_bus(struct pci_dev * pdev, int (*)(struct pci_dev *, void *) fn, void * data, bool slot)
```
</details>
</li>
</ul>
