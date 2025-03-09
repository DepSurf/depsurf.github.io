# Function: <code>dma_direct_free</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void dma_direct_free(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579946848,
      "name": "dma_direct_free",
      "external": true,
      "loc": "kernel/dma/direct.c:126",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/swiotlb.c:swiotlb_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579946848,
      "name": "dma_direct_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void dma_direct_free(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579995536,
      "name": "dma_direct_free",
      "external": true,
      "loc": "kernel/dma/direct.c:204",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579995536,
      "name": "dma_direct_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void dma_direct_free(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580037760,
      "name": "dma_direct_free",
      "external": true,
      "loc": "kernel/dma/direct.c:213",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_attrs",
        "drivers/iommu/intel-iommu.c:intel_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580037760,
      "name": "dma_direct_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void dma_direct_free(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580088000,
      "name": "dma_direct_free",
      "external": true,
      "loc": "kernel/dma/direct.c:213",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_attrs",
        "drivers/iommu/intel-iommu.c:intel_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580088000,
      "name": "dma_direct_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void dma_direct_free(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580148400,
      "name": "dma_direct_free",
      "external": true,
      "loc": "kernel/dma/direct.c:299",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580148400,
      "name": "dma_direct_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void dma_direct_free(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580126368,
      "name": "dma_direct_free",
      "external": true,
      "loc": "kernel/dma/direct.c:244",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/mapping.c:dma_free_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580126368,
      "name": "dma_direct_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
void dma_direct_free(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580130688,
      "name": "dma_direct_free",
      "external": true,
      "loc": "kernel/dma/direct.c:244",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/mapping.c:dma_free_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580130688,
      "name": "dma_direct_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
void dma_direct_free(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_free",
      "external": true,
      "loc": "kernel/dma/direct.c:274",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/mapping.c:dma_free_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592149980,
      "name": "dma_direct_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071580274144,
      "name": "dma_direct_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void dma_direct_free(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_free",
      "external": true,
      "loc": "kernel/dma/direct.c:322",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/mapping.c:dma_free_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593922655,
      "name": "dma_direct_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580445632,
      "name": "dma_direct_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
void dma_direct_free(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580690016,
      "name": "dma_direct_free",
      "external": true,
      "loc": "kernel/dma/direct.c:322",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/mapping.c:dma_free_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580690016,
      "name": "dma_direct_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
void dma_direct_free(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580766624,
      "name": "dma_direct_free",
      "external": true,
      "loc": "kernel/dma/direct.c:321",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/mapping.c:dma_free_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580766624,
      "name": "dma_direct_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
void dma_direct_free(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580852368,
      "name": "dma_direct_free",
      "external": true,
      "loc": "kernel/dma/direct.c:312",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/mapping.c:dma_free_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580852368,
      "name": "dma_direct_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void dma_direct_free(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491290992,
      "name": "dma_direct_free",
      "external": true,
      "loc": "kernel/dma/direct.c:213",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_attrs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491290992,
      "name": "dma_direct_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void dma_direct_free(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225296504,
      "name": "dma_direct_free",
      "external": true,
      "loc": "kernel/dma/direct.c:213",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225296504,
      "name": "dma_direct_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void dma_direct_free(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284217056,
      "name": "dma_direct_free",
      "external": true,
      "loc": "kernel/dma/direct.c:213",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/dma-iommu.c:dma_iommu_free_coherent",
        "kernel/dma/mapping.c:dma_free_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284217056,
      "name": "dma_direct_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void dma_direct_free(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271806164,
      "name": "dma_direct_free",
      "external": true,
      "loc": "kernel/dma/direct.c:213",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271806164,
      "name": "dma_direct_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void dma_direct_free(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580056832,
      "name": "dma_direct_free",
      "external": true,
      "loc": "kernel/dma/direct.c:213",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_attrs",
        "drivers/iommu/intel-iommu.c:intel_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580056832,
      "name": "dma_direct_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void dma_direct_free(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580002048,
      "name": "dma_direct_free",
      "external": true,
      "loc": "kernel/dma/direct.c:213",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_attrs",
        "drivers/iommu/intel-iommu.c:intel_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580002048,
      "name": "dma_direct_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void dma_direct_free(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580048272,
      "name": "dma_direct_free",
      "external": true,
      "loc": "kernel/dma/direct.c:213",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_attrs",
        "drivers/iommu/intel-iommu.c:intel_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580048272,
      "name": "dma_direct_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void dma_direct_free(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580099024,
      "name": "dma_direct_free",
      "external": true,
      "loc": "kernel/dma/direct.c:213",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_free_attrs",
        "drivers/iommu/intel-iommu.c:intel_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580099024,
      "name": "dma_direct_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void dma_direct_free(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_addr, long unsigned int attrs)
```
</details>
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
