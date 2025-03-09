# Function: <code>vfio_unpin_page_external</code>

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
int vfio_unpin_page_external(struct vfio_dma * dma, dma_addr_t iova, bool do_accounting)
```

```json
{
  "name": "vfio_unpin_page_external",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587051472,
      "name": "vfio_unpin_page_external",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:524",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unpin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587051472,
      "name": "vfio_unpin_page_external",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_unpin_page_external",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587885696,
      "name": "vfio_unpin_page_external",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:614",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unpin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587885696,
      "name": "vfio_unpin_page_external.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_unpin_page_external",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587947456,
      "name": "vfio_unpin_page_external",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:637",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unpin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587947456,
      "name": "vfio_unpin_page_external.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_unpin_page_external",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587827984,
      "name": "vfio_unpin_page_external",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:815",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unpin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587827984,
      "name": "vfio_unpin_page_external.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
  "name": "vfio_unpin_page_external",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588432928,
      "name": "vfio_unpin_page_external",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:816",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unpin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588432928,
      "name": "vfio_unpin_page_external.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_unpin_page_external",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589833920,
      "name": "vfio_unpin_page_external",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:814",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unpin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589833920,
      "name": "vfio_unpin_page_external.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
int vfio_unpin_page_external(struct vfio_dma * dma, dma_addr_t iova, bool do_accounting)
```

```json
{
  "name": "vfio_unpin_page_external",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586699392,
      "name": "vfio_unpin_page_external",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:524",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unpin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586699392,
      "name": "vfio_unpin_page_external",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
int vfio_unpin_page_external(struct vfio_dma * dma, dma_addr_t iova, bool do_accounting)
```

```json
{
  "name": "vfio_unpin_page_external",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587006032,
      "name": "vfio_unpin_page_external",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:524",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unpin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587006032,
      "name": "vfio_unpin_page_external",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
int vfio_unpin_page_external(struct vfio_dma * dma, dma_addr_t iova, bool do_accounting)
```

```json
{
  "name": "vfio_unpin_page_external",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587113200,
      "name": "vfio_unpin_page_external",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:524",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unpin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587113200,
      "name": "vfio_unpin_page_external",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
int vfio_unpin_page_external(struct vfio_dma * dma, dma_addr_t iova, bool do_accounting)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int vfio_unpin_page_external(struct vfio_dma * dma, dma_addr_t iova, bool do_accounting)
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
int vfio_unpin_page_external(struct vfio_dma * dma, dma_addr_t iova, bool do_accounting)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int vfio_unpin_page_external(struct vfio_dma * dma, dma_addr_t iova, bool do_accounting)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int vfio_unpin_page_external(struct vfio_dma * dma, dma_addr_t iova, bool do_accounting)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int vfio_unpin_page_external(struct vfio_dma * dma, dma_addr_t iova, bool do_accounting)
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
int vfio_unpin_page_external(struct vfio_dma * dma, dma_addr_t iova, bool do_accounting)
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
