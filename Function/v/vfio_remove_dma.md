# Function: <code>vfio_remove_dma</code>

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
void vfio_remove_dma(struct vfio_iommu * iommu, struct vfio_dma * dma)
```

```json
{
  "name": "vfio_remove_dma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587053136,
      "name": "vfio_remove_dma",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:836",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_unmap_unpin_all",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587053136,
      "name": "vfio_remove_dma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void vfio_remove_dma(struct vfio_iommu * iommu, struct vfio_dma * dma)
```

```json
{
  "name": "vfio_remove_dma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587884336,
      "name": "vfio_remove_dma",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:945",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587884336,
      "name": "vfio_remove_dma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void vfio_remove_dma(struct vfio_iommu * iommu, struct vfio_dma * dma)
```

```json
{
  "name": "vfio_remove_dma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587945968,
      "name": "vfio_remove_dma",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:969",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587945968,
      "name": "vfio_remove_dma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void vfio_remove_dma(struct vfio_iommu * iommu, struct vfio_dma * dma)
```

```json
{
  "name": "vfio_remove_dma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587827168,
      "name": "vfio_remove_dma",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1163",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587827168,
      "name": "vfio_remove_dma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void vfio_remove_dma(struct vfio_iommu * iommu, struct vfio_dma * dma)
```

```json
{
  "name": "vfio_remove_dma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_remove_dma",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1164",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588432096,
      "name": "vfio_remove_dma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
    },
    {
      "addr": 18446744071592548654,
      "name": "vfio_remove_dma.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void vfio_remove_dma(struct vfio_iommu * iommu, struct vfio_dma * dma)
```

```json
{
  "name": "vfio_remove_dma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_remove_dma",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1162",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589831248,
      "name": "vfio_remove_dma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
    },
    {
      "addr": 18446744071594427787,
      "name": "vfio_remove_dma.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void vfio_remove_dma(struct vfio_iommu * iommu, struct vfio_dma * dma)
```

```json
{
  "name": "vfio_remove_dma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586701056,
      "name": "vfio_remove_dma",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:836",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_unmap_unpin_all",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586701056,
      "name": "vfio_remove_dma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void vfio_remove_dma(struct vfio_iommu * iommu, struct vfio_dma * dma)
```

```json
{
  "name": "vfio_remove_dma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587007696,
      "name": "vfio_remove_dma",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:836",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_unmap_unpin_all",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587007696,
      "name": "vfio_remove_dma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void vfio_remove_dma(struct vfio_iommu * iommu, struct vfio_dma * dma)
```

```json
{
  "name": "vfio_remove_dma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587114864,
      "name": "vfio_remove_dma",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:836",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_unmap_unpin_all",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587114864,
      "name": "vfio_remove_dma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void vfio_remove_dma(struct vfio_iommu * iommu, struct vfio_dma * dma)
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
void vfio_remove_dma(struct vfio_iommu * iommu, struct vfio_dma * dma)
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
void vfio_remove_dma(struct vfio_iommu * iommu, struct vfio_dma * dma)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void vfio_remove_dma(struct vfio_iommu * iommu, struct vfio_dma * dma)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void vfio_remove_dma(struct vfio_iommu * iommu, struct vfio_dma * dma)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void vfio_remove_dma(struct vfio_iommu * iommu, struct vfio_dma * dma)
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
void vfio_remove_dma(struct vfio_iommu * iommu, struct vfio_dma * dma)
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
