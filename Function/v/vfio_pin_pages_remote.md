# Function: <code>vfio_pin_pages_remote</code>

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
long int vfio_pin_pages_remote(struct vfio_dma * dma, long unsigned int vaddr, long int npage, long unsigned int * pfn_base, long unsigned int limit)
```

```json
{
  "name": "vfio_pin_pages_remote",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587055616,
      "name": "vfio_pin_pages_remote",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:397",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587055616,
      "name": "vfio_pin_pages_remote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 852
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
long int vfio_pin_pages_remote(struct vfio_dma * dma, long unsigned int vaddr, long int npage, long unsigned int * pfn_base, long unsigned int limit)
```

```json
{
  "name": "vfio_pin_pages_remote",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587887200,
      "name": "vfio_pin_pages_remote",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:487",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587887200,
      "name": "vfio_pin_pages_remote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 956
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
long int vfio_pin_pages_remote(struct vfio_dma * dma, long unsigned int vaddr, long int npage, long unsigned int * pfn_base, long unsigned int limit)
```

```json
{
  "name": "vfio_pin_pages_remote",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587950240,
      "name": "vfio_pin_pages_remote",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:510",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587950240,
      "name": "vfio_pin_pages_remote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 956
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
long int vfio_pin_pages_remote(struct vfio_dma * dma, long unsigned int vaddr, long int npage, long unsigned int * pfn_base, long unsigned int limit, struct vfio_batch * batch)
```

```json
{
  "name": "vfio_pin_pages_remote",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pin_pages_remote",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:649",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587831168,
      "name": "vfio_pin_pages_remote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1054
    },
    {
      "addr": 18446744071591476825,
      "name": "vfio_pin_pages_remote.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
long int vfio_pin_pages_remote(struct vfio_dma * dma, long unsigned int vaddr, long int npage, long unsigned int * pfn_base, long unsigned int limit, struct vfio_batch * batch)
```

```json
{
  "name": "vfio_pin_pages_remote",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pin_pages_remote",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:650",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588437920,
      "name": "vfio_pin_pages_remote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1092
    },
    {
      "addr": 18446744071592549311,
      "name": "vfio_pin_pages_remote.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
long int vfio_pin_pages_remote(struct vfio_dma * dma, long unsigned int vaddr, long int npage, long unsigned int * pfn_base, long unsigned int limit, struct vfio_batch * batch)
```

```json
{
  "name": "vfio_pin_pages_remote",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_pin_pages_remote",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:648",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589835248,
      "name": "vfio_pin_pages_remote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1137
    },
    {
      "addr": 18446744071594428071,
      "name": "vfio_pin_pages_remote.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
long int vfio_pin_pages_remote(struct vfio_dma * dma, long unsigned int vaddr, long int npage, long unsigned int * pfn_base, long unsigned int limit)
```

```json
{
  "name": "vfio_pin_pages_remote",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586703536,
      "name": "vfio_pin_pages_remote",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:397",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586703536,
      "name": "vfio_pin_pages_remote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 852
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
long int vfio_pin_pages_remote(struct vfio_dma * dma, long unsigned int vaddr, long int npage, long unsigned int * pfn_base, long unsigned int limit)
```

```json
{
  "name": "vfio_pin_pages_remote",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587010176,
      "name": "vfio_pin_pages_remote",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:397",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587010176,
      "name": "vfio_pin_pages_remote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 852
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
long int vfio_pin_pages_remote(struct vfio_dma * dma, long unsigned int vaddr, long int npage, long unsigned int * pfn_base, long unsigned int limit)
```

```json
{
  "name": "vfio_pin_pages_remote",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587117344,
      "name": "vfio_pin_pages_remote",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:397",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587117344,
      "name": "vfio_pin_pages_remote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 852
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
long int vfio_pin_pages_remote(struct vfio_dma * dma, long unsigned int vaddr, long int npage, long unsigned int * pfn_base, long unsigned int limit)
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
<code>struct vfio_batch * batch</code>
</li>
</ul>
</details>
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
long int vfio_pin_pages_remote(struct vfio_dma * dma, long unsigned int vaddr, long int npage, long unsigned int * pfn_base, long unsigned int limit, struct vfio_batch * batch)
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
long int vfio_pin_pages_remote(struct vfio_dma * dma, long unsigned int vaddr, long int npage, long unsigned int * pfn_base, long unsigned int limit)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int vfio_pin_pages_remote(struct vfio_dma * dma, long unsigned int vaddr, long int npage, long unsigned int * pfn_base, long unsigned int limit)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long int vfio_pin_pages_remote(struct vfio_dma * dma, long unsigned int vaddr, long int npage, long unsigned int * pfn_base, long unsigned int limit)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int vfio_pin_pages_remote(struct vfio_dma * dma, long unsigned int vaddr, long int npage, long unsigned int * pfn_base, long unsigned int limit)
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
long int vfio_pin_pages_remote(struct vfio_dma * dma, long unsigned int vaddr, long int npage, long unsigned int * pfn_base, long unsigned int limit)
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
