# Function: <code>vfio_dma_do_map</code>

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
int vfio_dma_do_map(struct vfio_iommu * iommu, struct vfio_iommu_type1_dma_map * map)
```

```json
{
  "name": "vfio_dma_do_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587058816,
      "name": "vfio_dma_do_map",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1071",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587058816,
      "name": "vfio_dma_do_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1110
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
int vfio_dma_do_map(struct vfio_iommu * iommu, struct vfio_iommu_type1_dma_map * map)
```

```json
{
  "name": "vfio_dma_do_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587890368,
      "name": "vfio_dma_do_map",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1296",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587890368,
      "name": "vfio_dma_do_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 847
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
int vfio_dma_do_map(struct vfio_iommu * iommu, struct vfio_iommu_type1_dma_map * map)
```

```json
{
  "name": "vfio_dma_do_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587951712,
      "name": "vfio_dma_do_map",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1323",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587951712,
      "name": "vfio_dma_do_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 847
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
int vfio_dma_do_map(struct vfio_iommu * iommu, struct vfio_iommu_type1_dma_map * map)
```

```json
{
  "name": "vfio_dma_do_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587838944,
      "name": "vfio_dma_do_map",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1553",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587838944,
      "name": "vfio_dma_do_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1108
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
int vfio_dma_do_map(struct vfio_iommu * iommu, struct vfio_iommu_type1_dma_map * map)
```

```json
{
  "name": "vfio_dma_do_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_dma_do_map",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1554",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588444064,
      "name": "vfio_dma_do_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1069
    },
    {
      "addr": 18446744071592549810,
      "name": "vfio_dma_do_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int vfio_dma_do_map(struct vfio_iommu * iommu, struct vfio_iommu_type1_dma_map * map)
```

```json
{
  "name": "vfio_dma_do_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_dma_do_map",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1552",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589841568,
      "name": "vfio_dma_do_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1182
    },
    {
      "addr": 18446744071594428731,
      "name": "vfio_dma_do_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
int vfio_dma_do_map(struct vfio_iommu * iommu, struct vfio_iommu_type1_dma_map * map)
```

```json
{
  "name": "vfio_dma_do_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586706736,
      "name": "vfio_dma_do_map",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1071",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586706736,
      "name": "vfio_dma_do_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1110
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
int vfio_dma_do_map(struct vfio_iommu * iommu, struct vfio_iommu_type1_dma_map * map)
```

```json
{
  "name": "vfio_dma_do_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587013376,
      "name": "vfio_dma_do_map",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1071",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587013376,
      "name": "vfio_dma_do_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1110
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
int vfio_dma_do_map(struct vfio_iommu * iommu, struct vfio_iommu_type1_dma_map * map)
```

```json
{
  "name": "vfio_dma_do_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587120544,
      "name": "vfio_dma_do_map",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1071",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587120544,
      "name": "vfio_dma_do_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1105
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
int vfio_dma_do_map(struct vfio_iommu * iommu, struct vfio_iommu_type1_dma_map * map)
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
int vfio_dma_do_map(struct vfio_iommu * iommu, struct vfio_iommu_type1_dma_map * map)
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
int vfio_dma_do_map(struct vfio_iommu * iommu, struct vfio_iommu_type1_dma_map * map)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int vfio_dma_do_map(struct vfio_iommu * iommu, struct vfio_iommu_type1_dma_map * map)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int vfio_dma_do_map(struct vfio_iommu * iommu, struct vfio_iommu_type1_dma_map * map)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int vfio_dma_do_map(struct vfio_iommu * iommu, struct vfio_iommu_type1_dma_map * map)
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
int vfio_dma_do_map(struct vfio_iommu * iommu, struct vfio_iommu_type1_dma_map * map)
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
