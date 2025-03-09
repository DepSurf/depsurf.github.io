# Function: <code>swiotlb_init_remap</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void swiotlb_init_remap(bool addressing_limit, unsigned int flags, int (*)(void *, long unsigned int) remap)
```

```json
{
  "name": "swiotlb_init_remap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617120759,
      "name": "swiotlb_init_remap",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:231",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:pci_iommu_alloc",
        "kernel/dma/swiotlb.c:swiotlb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617120759,
      "name": "swiotlb_init_remap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 466
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void swiotlb_init_remap(bool addressing_limit, unsigned int flags, int (*)(void *, long unsigned int) remap)
```

```json
{
  "name": "swiotlb_init_remap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627788704,
      "name": "swiotlb_init_remap",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:339",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:pci_iommu_alloc",
        "kernel/dma/swiotlb.c:swiotlb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627788704,
      "name": "swiotlb_init_remap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 759
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void swiotlb_init_remap(bool addressing_limit, unsigned int flags, int (*)(void *, long unsigned int) remap)
```

```json
{
  "name": "swiotlb_init_remap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619551744,
      "name": "swiotlb_init_remap",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:312",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:pci_iommu_alloc",
        "kernel/dma/swiotlb.c:swiotlb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619551744,
      "name": "swiotlb_init_remap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 758
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void swiotlb_init_remap(bool addressing_limit, unsigned int flags, int (*)(void *, long unsigned int) remap)
```

```json
{
  "name": "swiotlb_init_remap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621852848,
      "name": "swiotlb_init_remap",
      "external": true,
      "loc": "kernel/dma/swiotlb.c:350",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-dma.c:pci_iommu_alloc",
        "kernel/dma/swiotlb.c:swiotlb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621852848,
      "name": "swiotlb_init_remap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 1027
    }
  ]
}
```
</details>
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void swiotlb_init_remap(bool addressing_limit, unsigned int flags, int (*)(void *, long unsigned int) remap)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
