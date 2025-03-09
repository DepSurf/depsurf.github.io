# Function: <code>vfio_pci_set_msi_trigger</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int vfio_pci_set_msi_trigger(struct vfio_pci_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
```

```json
{
  "name": "vfio_pci_set_msi_trigger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587073600,
      "name": "vfio_pci_set_msi_trigger",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:494",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587073600,
      "name": "vfio_pci_set_msi_trigger",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
int vfio_pci_set_msi_trigger(struct vfio_pci_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
```

```json
{
  "name": "vfio_pci_set_msi_trigger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587915920,
      "name": "vfio_pci_set_msi_trigger",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:508",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587915920,
      "name": "vfio_pci_set_msi_trigger",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
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
int vfio_pci_set_msi_trigger(struct vfio_pci_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
```

```json
{
  "name": "vfio_pci_set_msi_trigger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587977088,
      "name": "vfio_pci_set_msi_trigger",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:510",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587977088,
      "name": "vfio_pci_set_msi_trigger",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
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
int vfio_pci_set_msi_trigger(struct vfio_pci_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
```

```json
{
  "name": "vfio_pci_set_msi_trigger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587859488,
      "name": "vfio_pci_set_msi_trigger",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:510",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587859488,
      "name": "vfio_pci_set_msi_trigger",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
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
int vfio_pci_set_msi_trigger(struct vfio_pci_core_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
```

```json
{
  "name": "vfio_pci_set_msi_trigger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588464176,
      "name": "vfio_pci_set_msi_trigger",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:510",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588464176,
      "name": "vfio_pci_set_msi_trigger",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
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
int vfio_pci_set_msi_trigger(struct vfio_pci_core_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
```

```json
{
  "name": "vfio_pci_set_msi_trigger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589866608,
      "name": "vfio_pci_set_msi_trigger",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:510",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589866608,
      "name": "vfio_pci_set_msi_trigger",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int vfio_pci_set_msi_trigger(struct vfio_pci_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
```

```json
{
  "name": "vfio_pci_set_msi_trigger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293406672,
      "name": "vfio_pci_set_msi_trigger",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:494",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293406672,
      "name": "vfio_pci_set_msi_trigger",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 976
    }
  ]
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int vfio_pci_set_msi_trigger(struct vfio_pci_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
```

```json
{
  "name": "vfio_pci_set_msi_trigger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586721520,
      "name": "vfio_pci_set_msi_trigger",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:494",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586721520,
      "name": "vfio_pci_set_msi_trigger",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
int vfio_pci_set_msi_trigger(struct vfio_pci_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
```

```json
{
  "name": "vfio_pci_set_msi_trigger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587028160,
      "name": "vfio_pci_set_msi_trigger",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:494",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587028160,
      "name": "vfio_pci_set_msi_trigger",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
int vfio_pci_set_msi_trigger(struct vfio_pci_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
```

```json
{
  "name": "vfio_pci_set_msi_trigger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587135328,
      "name": "vfio_pci_set_msi_trigger",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:494",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587135328,
      "name": "vfio_pci_set_msi_trigger",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int vfio_pci_set_msi_trigger(struct vfio_pci_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
```
</details>
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
int vfio_pci_set_msi_trigger(struct vfio_pci_core_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int vfio_pci_set_msi_trigger(struct vfio_pci_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int vfio_pci_set_msi_trigger(struct vfio_pci_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int vfio_pci_set_msi_trigger(struct vfio_pci_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int vfio_pci_set_msi_trigger(struct vfio_pci_device * vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void * data)
```
</details>
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
