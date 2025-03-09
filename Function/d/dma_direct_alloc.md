# Function: <code>dma_direct_alloc</code>

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
void * dma_direct_alloc(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579946336,
      "name": "dma_direct_alloc",
      "external": true,
      "loc": "kernel/dma/direct.c:61",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/swiotlb.c:swiotlb_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579946336,
      "name": "dma_direct_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
void * dma_direct_alloc(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579995520,
      "name": "dma_direct_alloc",
      "external": true,
      "loc": "kernel/dma/direct.c:196",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_alloc_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579995520,
      "name": "dma_direct_alloc",
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
void * dma_direct_alloc(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580037744,
      "name": "dma_direct_alloc",
      "external": true,
      "loc": "kernel/dma/direct.c:204",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_alloc_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580037744,
      "name": "dma_direct_alloc",
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
void * dma_direct_alloc(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580087984,
      "name": "dma_direct_alloc",
      "external": true,
      "loc": "kernel/dma/direct.c:204",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_alloc_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580087984,
      "name": "dma_direct_alloc",
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
void * dma_direct_alloc(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580148384,
      "name": "dma_direct_alloc",
      "external": true,
      "loc": "kernel/dma/direct.c:289",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_alloc_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580148384,
      "name": "dma_direct_alloc",
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
void * dma_direct_alloc(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580125696,
      "name": "dma_direct_alloc",
      "external": true,
      "loc": "kernel/dma/direct.c:133",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/mapping.c:dma_alloc_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580125696,
      "name": "dma_direct_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 666
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
void * dma_direct_alloc(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580130016,
      "name": "dma_direct_alloc",
      "external": true,
      "loc": "kernel/dma/direct.c:133",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/mapping.c:dma_alloc_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580130016,
      "name": "dma_direct_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 666
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
void * dma_direct_alloc(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_alloc",
      "external": true,
      "loc": "kernel/dma/direct.c:152",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/mapping.c:dma_alloc_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592149949,
      "name": "dma_direct_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071580273456,
      "name": "dma_direct_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 686
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
void * dma_direct_alloc(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580444976,
      "name": "dma_direct_alloc",
      "external": true,
      "loc": "kernel/dma/direct.c:208",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/mapping.c:dma_alloc_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580444976,
      "name": "dma_direct_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 647
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
void * dma_direct_alloc(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580689344,
      "name": "dma_direct_alloc",
      "external": true,
      "loc": "kernel/dma/direct.c:208",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/mapping.c:dma_alloc_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580689344,
      "name": "dma_direct_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 647
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
void * dma_direct_alloc(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580765952,
      "name": "dma_direct_alloc",
      "external": true,
      "loc": "kernel/dma/direct.c:207",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/mapping.c:dma_alloc_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580765952,
      "name": "dma_direct_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 647
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
void * dma_direct_alloc(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580851696,
      "name": "dma_direct_alloc",
      "external": true,
      "loc": "kernel/dma/direct.c:207",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/mapping.c:dma_alloc_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580851696,
      "name": "dma_direct_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 653
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
void * dma_direct_alloc(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491290840,
      "name": "dma_direct_alloc",
      "external": true,
      "loc": "kernel/dma/direct.c:204",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_alloc_attrs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491290840,
      "name": "dma_direct_alloc",
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
void * dma_direct_alloc(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225296460,
      "name": "dma_direct_alloc",
      "external": true,
      "loc": "kernel/dma/direct.c:204",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_alloc_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225296460,
      "name": "dma_direct_alloc",
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
void * dma_direct_alloc(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284217024,
      "name": "dma_direct_alloc",
      "external": true,
      "loc": "kernel/dma/direct.c:204",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_alloc_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284217024,
      "name": "dma_direct_alloc",
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
void * dma_direct_alloc(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271806090,
      "name": "dma_direct_alloc",
      "external": true,
      "loc": "kernel/dma/direct.c:204",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_alloc_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271806090,
      "name": "dma_direct_alloc",
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
void * dma_direct_alloc(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580056816,
      "name": "dma_direct_alloc",
      "external": true,
      "loc": "kernel/dma/direct.c:204",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_alloc_attrs",
        "drivers/iommu/intel-iommu.c:intel_alloc_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580056816,
      "name": "dma_direct_alloc",
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
void * dma_direct_alloc(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580002032,
      "name": "dma_direct_alloc",
      "external": true,
      "loc": "kernel/dma/direct.c:204",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_alloc_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580002032,
      "name": "dma_direct_alloc",
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
void * dma_direct_alloc(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580048256,
      "name": "dma_direct_alloc",
      "external": true,
      "loc": "kernel/dma/direct.c:204",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_alloc_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580048256,
      "name": "dma_direct_alloc",
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
void * dma_direct_alloc(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580099008,
      "name": "dma_direct_alloc",
      "external": true,
      "loc": "kernel/dma/direct.c:204",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_alloc_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580099008,
      "name": "dma_direct_alloc",
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
void * dma_direct_alloc(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
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
