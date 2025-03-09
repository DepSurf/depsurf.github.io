# Function: <code>vfio_dma_do_unmap</code>

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
  "name": "vfio_dma_do_unmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587060074,
      "name": "vfio_dma_do_unmap",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:871",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
int vfio_dma_do_unmap(struct vfio_iommu * iommu, struct vfio_iommu_type1_dma_unmap * unmap, struct vfio_bitmap * bitmap)
```

```json
{
  "name": "vfio_dma_do_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587894208,
      "name": "vfio_dma_do_unmap",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1070",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587894208,
      "name": "vfio_dma_do_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 731
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
int vfio_dma_do_unmap(struct vfio_iommu * iommu, struct vfio_iommu_type1_dma_unmap * unmap, struct vfio_bitmap * bitmap)
```

```json
{
  "name": "vfio_dma_do_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587955136,
      "name": "vfio_dma_do_unmap",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1095",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unmap_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587955136,
      "name": "vfio_dma_do_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 731
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
int vfio_dma_do_unmap(struct vfio_iommu * iommu, struct vfio_iommu_type1_dma_unmap * unmap, struct vfio_bitmap * bitmap)
```

```json
{
  "name": "vfio_dma_do_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587837520,
      "name": "vfio_dma_do_unmap",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1293",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unmap_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587837520,
      "name": "vfio_dma_do_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1062
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
int vfio_dma_do_unmap(struct vfio_iommu * iommu, struct vfio_iommu_type1_dma_unmap * unmap, struct vfio_bitmap * bitmap)
```

```json
{
  "name": "vfio_dma_do_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_dma_do_unmap",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1294",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unmap_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588442560,
      "name": "vfio_dma_do_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1128
    },
    {
      "addr": 18446744071592549606,
      "name": "vfio_dma_do_unmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
int vfio_dma_do_unmap(struct vfio_iommu * iommu, struct vfio_iommu_type1_dma_unmap * unmap, struct vfio_bitmap * bitmap)
```

```json
{
  "name": "vfio_dma_do_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_dma_do_unmap",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1292",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unmap_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589838304,
      "name": "vfio_dma_do_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1236
    },
    {
      "addr": 18446744071594428292,
      "name": "vfio_dma_do_unmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
  "name": "vfio_dma_do_unmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586707994,
      "name": "vfio_dma_do_unmap",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:871",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "vfio_dma_do_unmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587014634,
      "name": "vfio_dma_do_unmap",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:871",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "vfio_dma_do_unmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587121802,
      "name": "vfio_dma_do_unmap",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:871",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
int vfio_dma_do_unmap(struct vfio_iommu * iommu, struct vfio_iommu_type1_dma_unmap * unmap, struct vfio_bitmap * bitmap)
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
int vfio_dma_do_unmap(struct vfio_iommu * iommu, struct vfio_iommu_type1_dma_unmap * unmap, struct vfio_bitmap * bitmap)
```
</details>
</li>
</ul>
