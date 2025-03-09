# Function: <code>vfio_msi_enable</code>

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
  "name": "vfio_msi_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587073681,
      "name": "vfio_msi_enable",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:247",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int vfio_msi_enable(struct vfio_pci_device * vdev, int nvec, bool msix)
```

```json
{
  "name": "vfio_msi_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587915568,
      "name": "vfio_msi_enable",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:247",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587915568,
      "name": "vfio_msi_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
int vfio_msi_enable(struct vfio_pci_device * vdev, int nvec, bool msix)
```

```json
{
  "name": "vfio_msi_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587976736,
      "name": "vfio_msi_enable",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:247",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587976736,
      "name": "vfio_msi_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
int vfio_msi_enable(struct vfio_pci_device * vdev, int nvec, bool msix)
```

```json
{
  "name": "vfio_msi_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587859136,
      "name": "vfio_msi_enable",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:247",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587859136,
      "name": "vfio_msi_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
int vfio_msi_enable(struct vfio_pci_core_device * vdev, int nvec, bool msix)
```

```json
{
  "name": "vfio_msi_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588463824,
      "name": "vfio_msi_enable",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:247",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588463824,
      "name": "vfio_msi_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
int vfio_msi_enable(struct vfio_pci_core_device * vdev, int nvec, bool msix)
```

```json
{
  "name": "vfio_msi_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589866240,
      "name": "vfio_msi_enable",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:247",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589866240,
      "name": "vfio_msi_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    }
  ]
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
  "name": "vfio_msi_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293406820,
      "name": "vfio_msi_enable",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:247",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger"
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
  "name": "vfio_msi_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586721601,
      "name": "vfio_msi_enable",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:247",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger"
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
  "name": "vfio_msi_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587028241,
      "name": "vfio_msi_enable",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:247",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger"
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
  "name": "vfio_msi_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587135409,
      "name": "vfio_msi_enable",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:247",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger"
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
int vfio_msi_enable(struct vfio_pci_device * vdev, int nvec, bool msix)
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
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct vfio_pci_device * vdev</code> ➡️ <code>struct vfio_pci_core_device * vdev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int vfio_msi_enable(struct vfio_pci_core_device * vdev, int nvec, bool msix)
```
</details>
</li>
</ul>
