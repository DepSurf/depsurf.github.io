# Function: <code>xen_destroy_contiguous_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order)
```

```json
{
  "name": "xen_destroy_contiguous_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578974800,
      "name": "xen_destroy_contiguous_region",
      "external": true,
      "loc": "arch/x86/xen/mmu.c:2669",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578974800,
      "name": "xen_destroy_contiguous_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order)
```

```json
{
  "name": "xen_destroy_contiguous_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578971792,
      "name": "xen_destroy_contiguous_region",
      "external": true,
      "loc": "arch/x86/xen/mmu.c:2659",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578971792,
      "name": "xen_destroy_contiguous_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order)
```

```json
{
  "name": "xen_destroy_contiguous_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578973568,
      "name": "xen_destroy_contiguous_region",
      "external": true,
      "loc": "arch/x86/xen/mmu.c:2659",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578973568,
      "name": "xen_destroy_contiguous_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order)
```

```json
{
  "name": "xen_destroy_contiguous_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578985872,
      "name": "xen_destroy_contiguous_region",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2657",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578985872,
      "name": "xen_destroy_contiguous_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order)
```

```json
{
  "name": "xen_destroy_contiguous_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578988656,
      "name": "xen_destroy_contiguous_region",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2598",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578988656,
      "name": "xen_destroy_contiguous_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order)
```

```json
{
  "name": "xen_destroy_contiguous_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578997968,
      "name": "xen_destroy_contiguous_region",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2634",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578997968,
      "name": "xen_destroy_contiguous_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order)
```

```json
{
  "name": "xen_destroy_contiguous_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578990240,
      "name": "xen_destroy_contiguous_region",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2642",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578990240,
      "name": "xen_destroy_contiguous_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order)
```

```json
{
  "name": "xen_destroy_contiguous_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578993296,
      "name": "xen_destroy_contiguous_region",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2630",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578993296,
      "name": "xen_destroy_contiguous_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order)
```

```json
{
  "name": "xen_destroy_contiguous_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579009792,
      "name": "xen_destroy_contiguous_region",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2629",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579009792,
      "name": "xen_destroy_contiguous_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order)
```

```json
{
  "name": "xen_destroy_contiguous_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579017744,
      "name": "xen_destroy_contiguous_region",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2629",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579017744,
      "name": "xen_destroy_contiguous_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order)
```

```json
{
  "name": "xen_destroy_contiguous_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579020272,
      "name": "xen_destroy_contiguous_region",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2311",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579020272,
      "name": "xen_destroy_contiguous_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order)
```

```json
{
  "name": "xen_destroy_contiguous_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579023328,
      "name": "xen_destroy_contiguous_region",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2310",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579023328,
      "name": "xen_destroy_contiguous_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order)
```

```json
{
  "name": "xen_destroy_contiguous_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579041600,
      "name": "xen_destroy_contiguous_region",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2313",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579041600,
      "name": "xen_destroy_contiguous_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order)
```

```json
{
  "name": "xen_destroy_contiguous_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579063632,
      "name": "xen_destroy_contiguous_region",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2339",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579063632,
      "name": "xen_destroy_contiguous_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order)
```

```json
{
  "name": "xen_destroy_contiguous_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579095472,
      "name": "xen_destroy_contiguous_region",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2339",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579095472,
      "name": "xen_destroy_contiguous_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order)
```

```json
{
  "name": "xen_destroy_contiguous_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579095184,
      "name": "xen_destroy_contiguous_region",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2347",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579095184,
      "name": "xen_destroy_contiguous_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order)
```

```json
{
  "name": "xen_destroy_contiguous_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579120976,
      "name": "xen_destroy_contiguous_region",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2358",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579120976,
      "name": "xen_destroy_contiguous_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order)
```

```json
{
  "name": "xen_destroy_contiguous_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490618072,
      "name": "xen_destroy_contiguous_region",
      "external": true,
      "loc": "arch/arm/xen/mm.c:131",
      "file": "arch/arm/xen/mm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490618072,
      "name": "xen_destroy_contiguous_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order)
```

```json
{
  "name": "xen_destroy_contiguous_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579010144,
      "name": "xen_destroy_contiguous_region",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2629",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579010144,
      "name": "xen_destroy_contiguous_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order)
```

```json
{
  "name": "xen_destroy_contiguous_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579009728,
      "name": "xen_destroy_contiguous_region",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2629",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579009728,
      "name": "xen_destroy_contiguous_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order)
```

```json
{
  "name": "xen_destroy_contiguous_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579012944,
      "name": "xen_destroy_contiguous_region",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2629",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579012944,
      "name": "xen_destroy_contiguous_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void xen_destroy_contiguous_region(phys_addr_t pstart, unsigned int order)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
