# Function: <code>iommu_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iommu_free(struct iommu_table * tbl, dma_addr_t dma_addr, unsigned int npages)
```

```json
{
  "name": "iommu_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579270080,
      "name": "iommu_free",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:290",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579270080,
      "name": "iommu_free",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iommu_free(struct iommu_table * tbl, dma_addr_t dma_addr, unsigned int npages)
```

```json
{
  "name": "iommu_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579269408,
      "name": "iommu_free",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:290",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579269408,
      "name": "iommu_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iommu_free(struct iommu_table * tbl, dma_addr_t dma_addr, unsigned int npages)
```

```json
{
  "name": "iommu_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579284848,
      "name": "iommu_free",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:290",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579284848,
      "name": "iommu_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void iommu_free(struct iommu_table * tbl, dma_addr_t dma_addr, unsigned int npages)
```

```json
{
  "name": "iommu_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579280016,
      "name": "iommu_free",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:292",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579280016,
      "name": "iommu_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void iommu_free(struct iommu_table * tbl, dma_addr_t dma_addr, unsigned int npages)
```

```json
{
  "name": "iommu_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579298720,
      "name": "iommu_free",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:292",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579298720,
      "name": "iommu_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void iommu_free(struct iommu_table * tbl, dma_addr_t dma_addr, unsigned int npages)
```

```json
{
  "name": "iommu_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579310704,
      "name": "iommu_free",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:293",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579310704,
      "name": "iommu_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void iommu_free(struct iommu_table * tbl, dma_addr_t dma_addr, unsigned int npages)
```

```json
{
  "name": "iommu_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579335312,
      "name": "iommu_free",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:288",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579335312,
      "name": "iommu_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void iommu_free(struct iommu_table * tbl, dma_addr_t dma_addr, unsigned int npages)
```

```json
{
  "name": "iommu_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579350512,
      "name": "iommu_free",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:276",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579350512,
      "name": "iommu_free",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void iommu_free(struct iommu_table * tbl, dma_addr_t dma_addr, unsigned int npages)
```

```json
{
  "name": "iommu_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579354848,
      "name": "iommu_free",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:276",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579354848,
      "name": "iommu_free",
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
void iommu_free(struct iommu_table * tbl, dma_addr_t dma_addr, unsigned int npages)
```

```json
{
  "name": "iommu_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282498448,
      "name": "iommu_free",
      "external": false,
      "loc": "arch/powerpc/kernel/iommu.c:405",
      "file": "arch/powerpc/kernel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/iommu.c:iommu_free_coherent",
        "arch/powerpc/kernel/iommu.c:iommu_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282498448,
      "name": "iommu_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void iommu_free(struct iommu_table * tbl, dma_addr_t dma_addr, unsigned int npages)
```

```json
{
  "name": "iommu_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579350752,
      "name": "iommu_free",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:276",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579350752,
      "name": "iommu_free",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void iommu_free(struct iommu_table * tbl, dma_addr_t dma_addr, unsigned int npages)
```

```json
{
  "name": "iommu_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579282960,
      "name": "iommu_free",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:276",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579282960,
      "name": "iommu_free",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void iommu_free(struct iommu_table * tbl, dma_addr_t dma_addr, unsigned int npages)
```

```json
{
  "name": "iommu_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579350672,
      "name": "iommu_free",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:276",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579350672,
      "name": "iommu_free",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void iommu_free(struct iommu_table * tbl, dma_addr_t dma_addr, unsigned int npages)
```

```json
{
  "name": "iommu_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579359120,
      "name": "iommu_free",
      "external": false,
      "loc": "arch/x86/kernel/pci-calgary_64.c:276",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359120,
      "name": "iommu_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void iommu_free(struct iommu_table * tbl, dma_addr_t dma_addr, unsigned int npages)
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
void iommu_free(struct iommu_table * tbl, dma_addr_t dma_addr, unsigned int npages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void iommu_free(struct iommu_table * tbl, dma_addr_t dma_addr, unsigned int npages)
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
void iommu_free(struct iommu_table * tbl, dma_addr_t dma_addr, unsigned int npages)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
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
