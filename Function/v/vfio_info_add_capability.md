# Function: <code>vfio_info_add_capability</code>

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
int vfio_info_add_capability(struct vfio_info_cap * caps, struct vfio_info_cap_header * cap, size_t size)
```

```json
{
  "name": "vfio_info_add_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587039456,
      "name": "vfio_info_add_capability",
      "external": true,
      "loc": "drivers/vfio/vfio.c:1860",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587039456,
      "name": "vfio_info_add_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int vfio_info_add_capability(struct vfio_info_cap * caps, struct vfio_info_cap_header * cap, size_t size)
```

```json
{
  "name": "vfio_info_add_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587869472,
      "name": "vfio_info_add_capability",
      "external": true,
      "loc": "drivers/vfio/vfio.c:1880",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587869472,
      "name": "vfio_info_add_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int vfio_info_add_capability(struct vfio_info_cap * caps, struct vfio_info_cap_header * cap, size_t size)
```

```json
{
  "name": "vfio_info_add_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587929904,
      "name": "vfio_info_add_capability",
      "external": true,
      "loc": "drivers/vfio/vfio.c:1881",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587929904,
      "name": "vfio_info_add_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int vfio_info_add_capability(struct vfio_info_cap * caps, struct vfio_info_cap_header * cap, size_t size)
```

```json
{
  "name": "vfio_info_add_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587812048,
      "name": "vfio_info_add_capability",
      "external": true,
      "loc": "drivers/vfio/vfio.c:1780",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587812048,
      "name": "vfio_info_add_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int vfio_info_add_capability(struct vfio_info_cap * caps, struct vfio_info_cap_header * cap, size_t size)
```

```json
{
  "name": "vfio_info_add_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588414464,
      "name": "vfio_info_add_capability",
      "external": true,
      "loc": "drivers/vfio/vfio.c:1887",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588414464,
      "name": "vfio_info_add_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int vfio_info_add_capability(struct vfio_info_cap * caps, struct vfio_info_cap_header * cap, size_t size)
```

```json
{
  "name": "vfio_info_add_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589815376,
      "name": "vfio_info_add_capability",
      "external": true,
      "loc": "drivers/vfio/vfio.c:1852",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589815376,
      "name": "vfio_info_add_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int vfio_info_add_capability(struct vfio_info_cap * caps, struct vfio_info_cap_header * cap, size_t size)
```

```json
{
  "name": "vfio_info_add_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293369728,
      "name": "vfio_info_add_capability",
      "external": true,
      "loc": "drivers/vfio/vfio.c:1860",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_npu2_add_capability",
        "drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_npu2_add_capability",
        "drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_nvgpu_add_capability"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293369728,
      "name": "vfio_info_add_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int vfio_info_add_capability(struct vfio_info_cap * caps, struct vfio_info_cap_header * cap, size_t size)
```

```json
{
  "name": "vfio_info_add_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586687376,
      "name": "vfio_info_add_capability",
      "external": true,
      "loc": "drivers/vfio/vfio.c:1860",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586687376,
      "name": "vfio_info_add_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int vfio_info_add_capability(struct vfio_info_cap * caps, struct vfio_info_cap_header * cap, size_t size)
```

```json
{
  "name": "vfio_info_add_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586994016,
      "name": "vfio_info_add_capability",
      "external": true,
      "loc": "drivers/vfio/vfio.c:1860",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586994016,
      "name": "vfio_info_add_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int vfio_info_add_capability(struct vfio_info_cap * caps, struct vfio_info_cap_header * cap, size_t size)
```

```json
{
  "name": "vfio_info_add_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587101184,
      "name": "vfio_info_add_capability",
      "external": true,
      "loc": "drivers/vfio/vfio.c:1860",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587101184,
      "name": "vfio_info_add_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int vfio_info_add_capability(struct vfio_info_cap * caps, struct vfio_info_cap_header * cap, size_t size)
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
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int vfio_info_add_capability(struct vfio_info_cap * caps, struct vfio_info_cap_header * cap, size_t size)
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
int vfio_info_add_capability(struct vfio_info_cap * caps, struct vfio_info_cap_header * cap, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int vfio_info_add_capability(struct vfio_info_cap * caps, struct vfio_info_cap_header * cap, size_t size)
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
int vfio_info_add_capability(struct vfio_info_cap * caps, struct vfio_info_cap_header * cap, size_t size)
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
int vfio_info_add_capability(struct vfio_info_cap * caps, struct vfio_info_cap_header * cap, size_t size)
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
