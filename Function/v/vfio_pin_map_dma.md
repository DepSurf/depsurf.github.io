# Function: <code>vfio_pin_map_dma</code>

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
  "name": "vfio_pin_map_dma",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587059451,
      "name": "vfio_pin_map_dma",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1009",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map"
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
int vfio_pin_map_dma(struct vfio_iommu * iommu, struct vfio_dma * dma, size_t map_size)
```

```json
{
  "name": "vfio_pin_map_dma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587888160,
      "name": "vfio_pin_map_dma",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1234",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587888160,
      "name": "vfio_pin_map_dma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 501
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
int vfio_pin_map_dma(struct vfio_iommu * iommu, struct vfio_dma * dma, size_t map_size)
```

```json
{
  "name": "vfio_pin_map_dma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587951200,
      "name": "vfio_pin_map_dma",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1261",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587951200,
      "name": "vfio_pin_map_dma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
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
int vfio_pin_map_dma(struct vfio_iommu * iommu, struct vfio_dma * dma, size_t map_size)
```

```json
{
  "name": "vfio_pin_map_dma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587833344,
      "name": "vfio_pin_map_dma",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1485",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587833344,
      "name": "vfio_pin_map_dma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 742
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
int vfio_pin_map_dma(struct vfio_iommu * iommu, struct vfio_dma * dma, size_t map_size)
```

```json
{
  "name": "vfio_pin_map_dma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588439024,
      "name": "vfio_pin_map_dma",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1486",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588439024,
      "name": "vfio_pin_map_dma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 622
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
int vfio_pin_map_dma(struct vfio_iommu * iommu, struct vfio_dma * dma, size_t map_size)
```

```json
{
  "name": "vfio_pin_map_dma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589836400,
      "name": "vfio_pin_map_dma",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1484",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589836400,
      "name": "vfio_pin_map_dma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 753
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_pin_map_dma",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586707371,
      "name": "vfio_pin_map_dma",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1009",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map"
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
  "name": "vfio_pin_map_dma",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587014011,
      "name": "vfio_pin_map_dma",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1009",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map"
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
  "name": "vfio_pin_map_dma",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587121179,
      "name": "vfio_pin_map_dma",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1009",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map"
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
int vfio_pin_map_dma(struct vfio_iommu * iommu, struct vfio_dma * dma, size_t map_size)
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
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int vfio_pin_map_dma(struct vfio_iommu * iommu, struct vfio_dma * dma, size_t map_size)
```
</details>
</li>
</ul>
