# Function: <code>get_vm_area_caller</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct vm_struct * get_vm_area_caller(long unsigned int size, long unsigned int flags, const void * caller)
```

```json
{
  "name": "get_vm_area_caller",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580740608,
      "name": "get_vm_area_caller",
      "external": true,
      "loc": "mm/vmalloc.c:1396",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap",
        "mm/vmalloc.c:alloc_vm_area"
      ],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "drivers/base/dma-mapping.c:dma_common_pages_remap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580740608,
      "name": "get_vm_area_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
struct vm_struct * get_vm_area_caller(long unsigned int size, long unsigned int flags, const void * caller)
```

```json
{
  "name": "get_vm_area_caller",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580860726,
      "name": "get_vm_area_caller",
      "external": true,
      "loc": "mm/vmalloc.c:1420",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:alloc_vm_area",
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "drivers/base/dma-mapping.c:dma_common_pages_remap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580859808,
      "name": "get_vm_area_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct vm_struct * get_vm_area_caller(long unsigned int size, long unsigned int flags, const void * caller)
```

```json
{
  "name": "get_vm_area_caller",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580930934,
      "name": "get_vm_area_caller",
      "external": true,
      "loc": "mm/vmalloc.c:1403",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:alloc_vm_area",
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "drivers/base/dma-mapping.c:dma_common_pages_remap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580930000,
      "name": "get_vm_area_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct vm_struct * get_vm_area_caller(long unsigned int size, long unsigned int flags, const void * caller)
```

```json
{
  "name": "get_vm_area_caller",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580975190,
      "name": "get_vm_area_caller",
      "external": true,
      "loc": "mm/vmalloc.c:1454",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:alloc_vm_area",
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "drivers/base/dma-mapping.c:dma_common_contiguous_remap",
        "drivers/base/dma-mapping.c:dma_common_pages_remap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580974288,
      "name": "get_vm_area_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct vm_struct * get_vm_area_caller(long unsigned int size, long unsigned int flags, const void * caller)
```

```json
{
  "name": "get_vm_area_caller",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581077814,
      "name": "get_vm_area_caller",
      "external": true,
      "loc": "mm/vmalloc.c:1452",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:alloc_vm_area",
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "drivers/base/dma-mapping.c:dma_common_contiguous_remap",
        "drivers/base/dma-mapping.c:dma_common_pages_remap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581076928,
      "name": "get_vm_area_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct vm_struct * get_vm_area_caller(long unsigned int size, long unsigned int flags, const void * caller)
```

```json
{
  "name": "get_vm_area_caller",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581216741,
      "name": "get_vm_area_caller",
      "external": true,
      "loc": "mm/vmalloc.c:1439",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:alloc_vm_area",
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "kernel/dma/mapping.c:dma_common_contiguous_remap",
        "kernel/dma/mapping.c:dma_common_pages_remap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581215840,
      "name": "get_vm_area_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct vm_struct * get_vm_area_caller(long unsigned int size, long unsigned int flags, const void * caller)
```

```json
{
  "name": "get_vm_area_caller",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581300469,
      "name": "get_vm_area_caller",
      "external": true,
      "loc": "mm/vmalloc.c:1441",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:alloc_vm_area",
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581299520,
      "name": "get_vm_area_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct vm_struct * get_vm_area_caller(long unsigned int size, long unsigned int flags, const void * caller)
```

```json
{
  "name": "get_vm_area_caller",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581377701,
      "name": "get_vm_area_caller",
      "external": true,
      "loc": "mm/vmalloc.c:2104",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:alloc_vm_area",
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581377456,
      "name": "get_vm_area_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct vm_struct * get_vm_area_caller(long unsigned int size, long unsigned int flags, const void * caller)
```

```json
{
  "name": "get_vm_area_caller",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581438901,
      "name": "get_vm_area_caller",
      "external": true,
      "loc": "mm/vmalloc.c:2110",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:alloc_vm_area",
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581438656,
      "name": "get_vm_area_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
struct vm_struct * get_vm_area_caller(long unsigned int size, long unsigned int flags, const void * caller)
```

```json
{
  "name": "get_vm_area_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581645776,
      "name": "get_vm_area_caller",
      "external": true,
      "loc": "mm/vmalloc.c:2155",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "mm/vmalloc.c:alloc_vm_area",
        "mm/vmalloc.c:vmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581645776,
      "name": "get_vm_area_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct vm_struct * get_vm_area_caller(long unsigned int size, long unsigned int flags, const void * caller)
```

```json
{
  "name": "get_vm_area_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581692144,
      "name": "get_vm_area_caller",
      "external": true,
      "loc": "mm/vmalloc.c:2137",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "mm/vmalloc.c:vmap_pfn",
        "mm/vmalloc.c:vmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581692144,
      "name": "get_vm_area_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct vm_struct * get_vm_area_caller(long unsigned int size, long unsigned int flags, const void * caller)
```

```json
{
  "name": "get_vm_area_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581714880,
      "name": "get_vm_area_caller",
      "external": true,
      "loc": "mm/vmalloc.c:2412",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "mm/vmalloc.c:vmap_pfn",
        "mm/vmalloc.c:vmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581714880,
      "name": "get_vm_area_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct vm_struct * get_vm_area_caller(long unsigned int size, long unsigned int flags, const void * caller)
```

```json
{
  "name": "get_vm_area_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581987152,
      "name": "get_vm_area_caller",
      "external": true,
      "loc": "mm/vmalloc.c:2464",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "mm/vmalloc.c:vmap_pfn",
        "mm/vmalloc.c:vmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581987152,
      "name": "get_vm_area_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct vm_struct * get_vm_area_caller(long unsigned int size, long unsigned int flags, const void * caller)
```

```json
{
  "name": "get_vm_area_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582409056,
      "name": "get_vm_area_caller",
      "external": true,
      "loc": "mm/vmalloc.c:2504",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "mm/vmalloc.c:vmap_pfn",
        "mm/vmalloc.c:vmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582409056,
      "name": "get_vm_area_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct vm_struct * get_vm_area_caller(long unsigned int size, long unsigned int flags, const void * caller)
```

```json
{
  "name": "get_vm_area_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582915904,
      "name": "get_vm_area_caller",
      "external": true,
      "loc": "mm/vmalloc.c:2566",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "mm/vmalloc.c:vmap_pfn",
        "mm/vmalloc.c:vmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582915904,
      "name": "get_vm_area_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct vm_struct * get_vm_area_caller(long unsigned int size, long unsigned int flags, const void * caller)
```

```json
{
  "name": "get_vm_area_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583132288,
      "name": "get_vm_area_caller",
      "external": true,
      "loc": "mm/vmalloc.c:2646",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "mm/vmalloc.c:vmap_pfn",
        "mm/vmalloc.c:vmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583132288,
      "name": "get_vm_area_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct vm_struct * get_vm_area_caller(long unsigned int size, long unsigned int flags, const void * caller)
```

```json
{
  "name": "get_vm_area_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583315280,
      "name": "get_vm_area_caller",
      "external": true,
      "loc": "mm/vmalloc.c:2646",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "mm/vmalloc.c:vmap_pfn",
        "mm/vmalloc.c:vmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583315280,
      "name": "get_vm_area_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct vm_struct * get_vm_area_caller(long unsigned int size, long unsigned int flags, const void * caller)
```

```json
{
  "name": "get_vm_area_caller",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492842544,
      "name": "get_vm_area_caller",
      "external": true,
      "loc": "mm/vmalloc.c:2110",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:alloc_vm_area",
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": [
        "arch/arm64/mm/ioremap.c:__ioremap_caller",
        "kernel/dma/remap.c:__dma_common_pages_remap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492842208,
      "name": "get_vm_area_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct vm_struct * get_vm_area_caller(long unsigned int size, long unsigned int flags, const void * caller)
```

```json
{
  "name": "get_vm_area_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226649092,
      "name": "get_vm_area_caller",
      "external": true,
      "loc": "mm/vmalloc.c:2110",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/ioremap.c:__arm_ioremap_pfn_caller",
        "kernel/dma/remap.c:__dma_common_pages_remap",
        "mm/vmalloc.c:alloc_vm_area",
        "mm/vmalloc.c:vmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226649092,
      "name": "get_vm_area_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct vm_struct * get_vm_area_caller(long unsigned int size, long unsigned int flags, const void * caller)
```

```json
{
  "name": "get_vm_area_caller",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286231252,
      "name": "get_vm_area_caller",
      "external": true,
      "loc": "mm/vmalloc.c:2110",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:alloc_vm_area",
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286230864,
      "name": "get_vm_area_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct vm_struct * get_vm_area_caller(long unsigned int size, long unsigned int flags, const void * caller)
```

```json
{
  "name": "get_vm_area_caller",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272794460,
      "name": "get_vm_area_caller",
      "external": true,
      "loc": "mm/vmalloc.c:2110",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:alloc_vm_area",
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": [
        "arch/riscv/mm/ioremap.c:ioremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272794206,
      "name": "get_vm_area_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct vm_struct * get_vm_area_caller(long unsigned int size, long unsigned int flags, const void * caller)
```

```json
{
  "name": "get_vm_area_caller",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581407749,
      "name": "get_vm_area_caller",
      "external": true,
      "loc": "mm/vmalloc.c:2110",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:alloc_vm_area",
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581407504,
      "name": "get_vm_area_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct vm_struct * get_vm_area_caller(long unsigned int size, long unsigned int flags, const void * caller)
```

```json
{
  "name": "get_vm_area_caller",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581350261,
      "name": "get_vm_area_caller",
      "external": true,
      "loc": "mm/vmalloc.c:2110",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:alloc_vm_area",
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581350016,
      "name": "get_vm_area_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct vm_struct * get_vm_area_caller(long unsigned int size, long unsigned int flags, const void * caller)
```

```json
{
  "name": "get_vm_area_caller",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581398949,
      "name": "get_vm_area_caller",
      "external": true,
      "loc": "mm/vmalloc.c:2110",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:alloc_vm_area",
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581398704,
      "name": "get_vm_area_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct vm_struct * get_vm_area_caller(long unsigned int size, long unsigned int flags, const void * caller)
```

```json
{
  "name": "get_vm_area_caller",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581462965,
      "name": "get_vm_area_caller",
      "external": true,
      "loc": "mm/vmalloc.c:2110",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:alloc_vm_area",
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581462736,
      "name": "get_vm_area_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
