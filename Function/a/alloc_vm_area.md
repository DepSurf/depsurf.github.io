# Function: <code>alloc_vm_area</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct vm_struct * alloc_vm_area(size_t size, pte_t * * ptes)
```

```json
{
  "name": "alloc_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580741536,
      "name": "alloc_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:2243",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580741536,
      "name": "alloc_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct vm_struct * alloc_vm_area(size_t size, pte_t * * ptes)
```

```json
{
  "name": "alloc_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580860720,
      "name": "alloc_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:2264",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580860720,
      "name": "alloc_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct vm_struct * alloc_vm_area(size_t size, pte_t * * ptes)
```

```json
{
  "name": "alloc_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580930928,
      "name": "alloc_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:2277",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "mm/zsmalloc.c:zs_cpu_prepare",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580930928,
      "name": "alloc_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
struct vm_struct * alloc_vm_area(size_t size, pte_t * * ptes)
```

```json
{
  "name": "alloc_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580975184,
      "name": "alloc_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:2347",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_init",
        "mm/zsmalloc.c:zs_cpu_prepare",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580975184,
      "name": "alloc_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct vm_struct * alloc_vm_area(size_t size, pte_t * * ptes)
```

```json
{
  "name": "alloc_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581077808,
      "name": "alloc_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:2343",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_valloc",
        "mm/zsmalloc.c:zs_cpu_prepare",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581077808,
      "name": "alloc_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct vm_struct * alloc_vm_area(size_t size, pte_t * * ptes)
```

```json
{
  "name": "alloc_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581216736,
      "name": "alloc_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:2330",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_cpu_prepare",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581216736,
      "name": "alloc_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct vm_struct * alloc_vm_area(size_t size, pte_t * * ptes)
```

```json
{
  "name": "alloc_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581300464,
      "name": "alloc_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:2332",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_cpu_prepare",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581300464,
      "name": "alloc_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct vm_struct * alloc_vm_area(size_t size, pte_t * * ptes)
```

```json
{
  "name": "alloc_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581377696,
      "name": "alloc_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3083",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_cpu_prepare",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581377696,
      "name": "alloc_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct vm_struct * alloc_vm_area(size_t size, pte_t * * ptes)
```

```json
{
  "name": "alloc_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581438896,
      "name": "alloc_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3094",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_cpu_prepare",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581438896,
      "name": "alloc_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct vm_struct * alloc_vm_area(size_t size, pte_t * * ptes)
```

```json
{
  "name": "alloc_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581647248,
      "name": "alloc_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3094",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_valloc",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581647248,
      "name": "alloc_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct vm_struct * alloc_vm_area(size_t size, pte_t * * ptes)
```

```json
{
  "name": "alloc_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492842512,
      "name": "alloc_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3094",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_cpu_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492842512,
      "name": "alloc_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
struct vm_struct * alloc_vm_area(size_t size, pte_t * * ptes)
```

```json
{
  "name": "alloc_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226649312,
      "name": "alloc_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3094",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_cpu_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226649312,
      "name": "alloc_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct vm_struct * alloc_vm_area(size_t size, pte_t * * ptes)
```

```json
{
  "name": "alloc_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286231216,
      "name": "alloc_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3094",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_cpu_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286231216,
      "name": "alloc_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
struct vm_struct * alloc_vm_area(size_t size, pte_t * * ptes)
```

```json
{
  "name": "alloc_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272794430,
      "name": "alloc_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3094",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272794430,
      "name": "alloc_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct vm_struct * alloc_vm_area(size_t size, pte_t * * ptes)
```

```json
{
  "name": "alloc_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581407744,
      "name": "alloc_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3094",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_cpu_prepare",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581407744,
      "name": "alloc_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct vm_struct * alloc_vm_area(size_t size, pte_t * * ptes)
```

```json
{
  "name": "alloc_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581350256,
      "name": "alloc_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3094",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_cpu_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581350256,
      "name": "alloc_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct vm_struct * alloc_vm_area(size_t size, pte_t * * ptes)
```

```json
{
  "name": "alloc_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581398944,
      "name": "alloc_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3094",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_cpu_prepare",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581398944,
      "name": "alloc_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct vm_struct * alloc_vm_area(size_t size, pte_t * * ptes)
```

```json
{
  "name": "alloc_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581462960,
      "name": "alloc_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:3094",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_cpu_prepare",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581462960,
      "name": "alloc_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
struct vm_struct * alloc_vm_area(size_t size, pte_t * * ptes)
```
</details>
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
