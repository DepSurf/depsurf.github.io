# Function: <code>map_vm_area</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int map_vm_area(struct vm_struct * area, pgprot_t prot, struct page * * pages)
```

```json
{
  "name": "map_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580738032,
      "name": "map_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:1294",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap",
        "drivers/base/dma-mapping.c:dma_common_pages_remap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580738032,
      "name": "map_vm_area",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int map_vm_area(struct vm_struct * area, pgprot_t prot, struct page * * pages)
```

```json
{
  "name": "map_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580855696,
      "name": "map_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:1318",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap",
        "mm/zsmalloc.c:zs_map_object",
        "drivers/base/dma-mapping.c:dma_common_pages_remap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580855696,
      "name": "map_vm_area",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int map_vm_area(struct vm_struct * area, pgprot_t prot, struct page * * pages)
```

```json
{
  "name": "map_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580925936,
      "name": "map_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:1301",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:vmap",
        "mm/zsmalloc.c:zs_map_object",
        "drivers/base/dma-mapping.c:dma_common_pages_remap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580925936,
      "name": "map_vm_area",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int map_vm_area(struct vm_struct * area, pgprot_t prot, struct page * * pages)
```

```json
{
  "name": "map_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580970192,
      "name": "map_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:1352",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap",
        "mm/zsmalloc.c:zs_map_object",
        "drivers/base/dma-mapping.c:dma_common_contiguous_remap",
        "drivers/base/dma-mapping.c:dma_common_pages_remap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580970192,
      "name": "map_vm_area",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int map_vm_area(struct vm_struct * area, pgprot_t prot, struct page * * pages)
```

```json
{
  "name": "map_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581072720,
      "name": "map_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:1350",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap",
        "mm/zsmalloc.c:zs_map_object",
        "drivers/base/dma-mapping.c:dma_common_contiguous_remap",
        "drivers/base/dma-mapping.c:dma_common_pages_remap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581072720,
      "name": "map_vm_area",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int map_vm_area(struct vm_struct * area, pgprot_t prot, struct page * * pages)
```

```json
{
  "name": "map_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581208032,
      "name": "map_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:1337",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_common_contiguous_remap",
        "kernel/dma/mapping.c:dma_common_pages_remap",
        "mm/vmalloc.c:vmap",
        "mm/zsmalloc.c:zs_map_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581208032,
      "name": "map_vm_area",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int map_vm_area(struct vm_struct * area, pgprot_t prot, struct page * * pages)
```

```json
{
  "name": "map_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581292192,
      "name": "map_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:1338",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap",
        "mm/zsmalloc.c:zs_map_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581292192,
      "name": "map_vm_area",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int map_vm_area(struct vm_struct * area, pgprot_t prot, struct page * * pages)
```

```json
{
  "name": "map_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581366784,
      "name": "map_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:1999",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap",
        "mm/zsmalloc.c:zs_map_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581366784,
      "name": "map_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int map_vm_area(struct vm_struct * area, pgprot_t prot, struct page * * pages)
```

```json
{
  "name": "map_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581426512,
      "name": "map_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:2006",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap",
        "mm/zsmalloc.c:zs_map_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581426512,
      "name": "map_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int map_vm_area(struct vm_struct * area, pgprot_t prot, struct page * * pages)
```

```json
{
  "name": "map_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492827800,
      "name": "map_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:2006",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/remap.c:__dma_common_pages_remap",
        "mm/vmalloc.c:vmap",
        "mm/zsmalloc.c:zs_map_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492827800,
      "name": "map_vm_area",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int map_vm_area(struct vm_struct * area, pgprot_t prot, struct page * * pages)
```

```json
{
  "name": "map_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226634492,
      "name": "map_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:2006",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/remap.c:__dma_common_pages_remap",
        "mm/vmalloc.c:vmap",
        "mm/zsmalloc.c:zs_map_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226634492,
      "name": "map_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int map_vm_area(struct vm_struct * area, pgprot_t prot, struct page * * pages)
```

```json
{
  "name": "map_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286212576,
      "name": "map_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:2006",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap",
        "mm/zsmalloc.c:zs_map_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286212576,
      "name": "map_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int map_vm_area(struct vm_struct * area, pgprot_t prot, struct page * * pages)
```

```json
{
  "name": "map_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272783700,
      "name": "map_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:2006",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272783700,
      "name": "map_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int map_vm_area(struct vm_struct * area, pgprot_t prot, struct page * * pages)
```

```json
{
  "name": "map_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581395360,
      "name": "map_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:2006",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap",
        "mm/zsmalloc.c:zs_map_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581395360,
      "name": "map_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int map_vm_area(struct vm_struct * area, pgprot_t prot, struct page * * pages)
```

```json
{
  "name": "map_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581338224,
      "name": "map_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:2006",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap",
        "mm/zsmalloc.c:zs_map_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581338224,
      "name": "map_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int map_vm_area(struct vm_struct * area, pgprot_t prot, struct page * * pages)
```

```json
{
  "name": "map_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581386560,
      "name": "map_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:2006",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap",
        "mm/zsmalloc.c:zs_map_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581386560,
      "name": "map_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int map_vm_area(struct vm_struct * area, pgprot_t prot, struct page * * pages)
```

```json
{
  "name": "map_vm_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581450880,
      "name": "map_vm_area",
      "external": true,
      "loc": "mm/vmalloc.c:2006",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap",
        "mm/zsmalloc.c:zs_map_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581450880,
      "name": "map_vm_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int map_vm_area(struct vm_struct * area, pgprot_t prot, struct page * * pages)
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
