# Function: <code>vmap_pages_range_noflush</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vmap_pages_range_noflush(long unsigned int addr, long unsigned int end, pgprot_t prot, struct page * * pages, unsigned int page_shift)
```

```json
{
  "name": "vmap_pages_range_noflush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581716276,
      "name": "vmap_pages_range_noflush",
      "external": true,
      "loc": "mm/vmalloc.c:549",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap",
        "mm/vmalloc.c:vm_map_ram"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_map_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581714672,
      "name": "vmap_pages_range_noflush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int vmap_pages_range_noflush(long unsigned int addr, long unsigned int end, pgprot_t prot, struct page * * pages, unsigned int page_shift)
```

```json
{
  "name": "vmap_pages_range_noflush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581988516,
      "name": "vmap_pages_range_noflush",
      "external": true,
      "loc": "mm/vmalloc.c:577",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap",
        "mm/vmalloc.c:vm_map_ram"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_map_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581986944,
      "name": "vmap_pages_range_noflush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int vmap_pages_range_noflush(long unsigned int addr, long unsigned int end, pgprot_t prot, struct page * * pages, unsigned int page_shift)
```

```json
{
  "name": "vmap_pages_range_noflush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582410769,
      "name": "vmap_pages_range_noflush",
      "external": true,
      "loc": "mm/vmalloc.c:578",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap",
        "mm/vmalloc.c:vm_map_ram"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_map_pages",
        "mm/vmalloc.c:__vmalloc_area_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593979147,
      "name": "vmap_pages_range_noflush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071582408400,
      "name": "vmap_pages_range_noflush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
int vmap_pages_range_noflush(long unsigned int addr, long unsigned int end, pgprot_t prot, struct page * * pages, unsigned int page_shift)
```

```json
{
  "name": "vmap_pages_range_noflush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582919164,
      "name": "vmap_pages_range_noflush",
      "external": true,
      "loc": "mm/vmalloc.c:616",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:vmap",
        "mm/vmalloc.c:vm_map_ram"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_map_pages",
        "mm/percpu.c:pcpu_page_first_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582915520,
      "name": "vmap_pages_range_noflush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int vmap_pages_range_noflush(long unsigned int addr, long unsigned int end, pgprot_t prot, struct page * * pages, unsigned int page_shift)
```

```json
{
  "name": "vmap_pages_range_noflush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583135180,
      "name": "vmap_pages_range_noflush",
      "external": true,
      "loc": "mm/vmalloc.c:605",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:vmap",
        "mm/vmalloc.c:vm_map_ram"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_map_pages",
        "mm/percpu.c:pcpu_page_first_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583131984,
      "name": "vmap_pages_range_noflush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int vmap_pages_range_noflush(long unsigned int addr, long unsigned int end, pgprot_t prot, struct page * * pages, unsigned int page_shift)
```

```json
{
  "name": "vmap_pages_range_noflush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583318236,
      "name": "vmap_pages_range_noflush",
      "external": true,
      "loc": "mm/vmalloc.c:605",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:vmap",
        "mm/vmalloc.c:vm_map_ram"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_map_pages",
        "mm/percpu.c:pcpu_page_first_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583314976,
      "name": "vmap_pages_range_noflush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int vmap_pages_range_noflush(long unsigned int addr, long unsigned int end, pgprot_t prot, struct page * * pages, unsigned int page_shift)
```
</details>
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
