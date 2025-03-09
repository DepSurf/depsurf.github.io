# Function: <code>vfio_pci_mmap</code>

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
int vfio_pci_mmap(void * device_data, struct vm_area_struct * vma)
```

```json
{
  "name": "vfio_pci_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587061728,
      "name": "vfio_pci_mmap",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:1195",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587061728,
      "name": "vfio_pci_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
int vfio_pci_mmap(void * device_data, struct vm_area_struct * vma)
```

```json
{
  "name": "vfio_pci_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587900864,
      "name": "vfio_pci_mmap",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:1576",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587900864,
      "name": "vfio_pci_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
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
int vfio_pci_mmap(void * device_data, struct vm_area_struct * vma)
```

```json
{
  "name": "vfio_pci_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587961440,
      "name": "vfio_pci_mmap",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:1651",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587961440,
      "name": "vfio_pci_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
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
int vfio_pci_mmap(struct vfio_device * core_vdev, struct vm_area_struct * vma)
```

```json
{
  "name": "vfio_pci_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587843632,
      "name": "vfio_pci_mmap",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:1644",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587843632,
      "name": "vfio_pci_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 534
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int vfio_pci_mmap(void * device_data, struct vm_area_struct * vma)
```

```json
{
  "name": "vfio_pci_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293389760,
      "name": "vfio_pci_mmap",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:1195",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293389760,
      "name": "vfio_pci_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
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
int vfio_pci_mmap(void * device_data, struct vm_area_struct * vma)
```

```json
{
  "name": "vfio_pci_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586709648,
      "name": "vfio_pci_mmap",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:1195",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586709648,
      "name": "vfio_pci_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
int vfio_pci_mmap(void * device_data, struct vm_area_struct * vma)
```

```json
{
  "name": "vfio_pci_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587016288,
      "name": "vfio_pci_mmap",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:1195",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587016288,
      "name": "vfio_pci_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
int vfio_pci_mmap(void * device_data, struct vm_area_struct * vma)
```

```json
{
  "name": "vfio_pci_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587123456,
      "name": "vfio_pci_mmap",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci.c:1195",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587123456,
      "name": "vfio_pci_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
int vfio_pci_mmap(void * device_data, struct vm_area_struct * vma)
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vfio_device * core_vdev</code>
</li>
<li>
<b>Param removed. </b>
<code>void * device_data</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int vfio_pci_mmap(struct vfio_device * core_vdev, struct vm_area_struct * vma)
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
int vfio_pci_mmap(void * device_data, struct vm_area_struct * vma)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int vfio_pci_mmap(void * device_data, struct vm_area_struct * vma)
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
int vfio_pci_mmap(void * device_data, struct vm_area_struct * vma)
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
int vfio_pci_mmap(void * device_data, struct vm_area_struct * vma)
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
