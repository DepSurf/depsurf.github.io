# Function: <code>free_vm_area</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_vm_area(struct vm_struct * area)
```

```json
{
  "name": "free_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580741488,
      "name": "free_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:2266",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "mm/vmalloc.c:alloc_vm_area",
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/zsmalloc.c:zs_unregister_cpu_notifier",
        "drivers/acpi/apei/ghes.c:ghes_exit",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580741488,
      "name": "free_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void free_vm_area(struct vm_struct * area)
```

```json
{
  "name": "free_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580860672,
      "name": "free_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:2287",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/vmalloc.c:alloc_vm_area",
        "mm/zsmalloc.c:zs_unregister_cpu_notifier",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580860672,
      "name": "free_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void free_vm_area(struct vm_struct * area)
```

```json
{
  "name": "free_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580930880,
      "name": "free_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:2300",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/vmalloc.c:alloc_vm_area",
        "mm/zsmalloc.c:zs_cpu_dead",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580930880,
      "name": "free_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void free_vm_area(struct vm_struct * area)
```

```json
{
  "name": "free_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580975136,
      "name": "free_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:2370",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/vmalloc.c:alloc_vm_area",
        "mm/zsmalloc.c:zs_cpu_dead",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580975136,
      "name": "free_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void free_vm_area(struct vm_struct * area)
```

```json
{
  "name": "free_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581077760,
      "name": "free_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:2366",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/vmalloc.c:alloc_vm_area",
        "mm/zsmalloc.c:zs_cpu_dead",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581077760,
      "name": "free_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void free_vm_area(struct vm_struct * area)
```

```json
{
  "name": "free_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581216688,
      "name": "free_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:2353",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/vmalloc.c:alloc_vm_area",
        "mm/zsmalloc.c:zs_cpu_dead",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581216688,
      "name": "free_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void free_vm_area(struct vm_struct * area)
```

```json
{
  "name": "free_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581300416,
      "name": "free_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:2355",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/vmalloc.c:alloc_vm_area",
        "mm/zsmalloc.c:zs_cpu_dead",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581300416,
      "name": "free_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void free_vm_area(struct vm_struct * area)
```

```json
{
  "name": "free_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581373360,
      "name": "free_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3106",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/vmalloc.c:alloc_vm_area",
        "mm/zsmalloc.c:zs_cpu_dead",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581373360,
      "name": "free_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void free_vm_area(struct vm_struct * area)
```

```json
{
  "name": "free_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581434608,
      "name": "free_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3117",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/vmalloc.c:alloc_vm_area",
        "mm/zsmalloc.c:zs_cpu_dead",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581434608,
      "name": "free_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_vm_area(struct vm_struct * area)
```

```json
{
  "name": "free_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581649672,
      "name": "free_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3117",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/vmalloc.c:alloc_vm_area",
        "mm/vmalloc.c:alloc_vm_area"
      ],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581647200,
      "name": "free_vm_area",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_vm_area(struct vm_struct * area)
```

```json
{
  "name": "free_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581696056,
      "name": "free_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3102",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:vmap_pfn",
        "mm/vmalloc.c:vmap_pfn"
      ],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/xen/grant-table.c:arch_gnttab_valloc",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581693632,
      "name": "free_vm_area",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_vm_area(struct vm_struct * area)
```

```json
{
  "name": "free_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581719544,
      "name": "free_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3354",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/vmalloc.c:vmap_pfn",
        "mm/vmalloc.c:vmap_pfn"
      ],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/xen/grant-table.c:arch_gnttab_valloc",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581716368,
      "name": "free_vm_area",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_vm_area(struct vm_struct * area)
```

```json
{
  "name": "free_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581991880,
      "name": "free_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3465",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/vmalloc.c:vmap_pfn"
      ],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/xen/grant-table.c:arch_gnttab_valloc",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581988608,
      "name": "free_vm_area",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_vm_area(struct vm_struct * area)
```

```json
{
  "name": "free_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582414632,
      "name": "free_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3627",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:vmap_pfn"
      ],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/xen/grant-table.c:arch_gnttab_valloc",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582410880,
      "name": "free_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_vm_area(struct vm_struct * area)
```

```json
{
  "name": "free_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582922392,
      "name": "free_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3689",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:vmap_pfn"
      ],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/xen/grant-table.c:arch_gnttab_valloc",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582917872,
      "name": "free_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_vm_area(struct vm_struct * area)
```

```json
{
  "name": "free_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583138760,
      "name": "free_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3922",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:vmap_pfn"
      ],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/xen/grant-table.c:arch_gnttab_valloc",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583133056,
      "name": "free_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_vm_area(struct vm_struct * area)
```

```json
{
  "name": "free_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583321880,
      "name": "free_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3922",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:vmap_pfn"
      ],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/xen/grant-table.c:arch_gnttab_valloc",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583316048,
      "name": "free_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void free_vm_area(struct vm_struct * area)
```

```json
{
  "name": "free_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492837528,
      "name": "free_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3117",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/vmalloc.c:alloc_vm_area",
        "mm/zsmalloc.c:zs_cpu_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492837528,
      "name": "free_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void free_vm_area(struct vm_struct * area)
```

```json
{
  "name": "free_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226641400,
      "name": "free_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3117",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/vmalloc.c:alloc_vm_area",
        "mm/zsmalloc.c:zs_cpu_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226641400,
      "name": "free_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void free_vm_area(struct vm_struct * area)
```

```json
{
  "name": "free_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286225520,
      "name": "free_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3117",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/ioremap.c:do_ioremap",
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/vmalloc.c:alloc_vm_area",
        "mm/zsmalloc.c:zs_cpu_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286225520,
      "name": "free_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void free_vm_area(struct vm_struct * area)
```

```json
{
  "name": "free_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272790614,
      "name": "free_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3117",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/mm/ioremap.c:ioremap",
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/vmalloc.c:alloc_vm_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272790614,
      "name": "free_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void free_vm_area(struct vm_struct * area)
```

```json
{
  "name": "free_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581403456,
      "name": "free_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3117",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/vmalloc.c:alloc_vm_area",
        "mm/zsmalloc.c:zs_cpu_dead",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581403456,
      "name": "free_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void free_vm_area(struct vm_struct * area)
```

```json
{
  "name": "free_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581345968,
      "name": "free_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3117",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/vmalloc.c:alloc_vm_area",
        "mm/zsmalloc.c:zs_cpu_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581345968,
      "name": "free_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void free_vm_area(struct vm_struct * area)
```

```json
{
  "name": "free_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581394656,
      "name": "free_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3117",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/vmalloc.c:alloc_vm_area",
        "mm/zsmalloc.c:zs_cpu_dead",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581394656,
      "name": "free_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void free_vm_area(struct vm_struct * area)
```

```json
{
  "name": "free_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581458608,
      "name": "free_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3117",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "mm/vmalloc.c:pcpu_free_vm_areas",
        "mm/vmalloc.c:alloc_vm_area",
        "mm/zsmalloc.c:zs_cpu_dead",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581458608,
      "name": "free_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
