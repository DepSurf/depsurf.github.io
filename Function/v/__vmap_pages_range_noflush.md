# Function: <code>__vmap_pages_range_noflush</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __vmap_pages_range_noflush(long unsigned int addr, long unsigned int end, pgprot_t prot, struct page * * pages, unsigned int page_shift)
```

```json
{
  "name": "__vmap_pages_range_noflush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582917745,
      "name": "__vmap_pages_range_noflush",
      "external": true,
      "loc": "mm/vmalloc.c:590",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap",
        "mm/vmalloc.c:vm_map_ram"
      ],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_area_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596035056,
      "name": "__vmap_pages_range_noflush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071582915168,
      "name": "__vmap_pages_range_noflush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __vmap_pages_range_noflush(long unsigned int addr, long unsigned int end, pgprot_t prot, struct page * * pages, unsigned int page_shift)
```

```json
{
  "name": "__vmap_pages_range_noflush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583132918,
      "name": "__vmap_pages_range_noflush",
      "external": true,
      "loc": "mm/vmalloc.c:579",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap",
        "mm/vmalloc.c:vm_map_ram"
      ],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_area_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596557200,
      "name": "__vmap_pages_range_noflush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071583131632,
      "name": "__vmap_pages_range_noflush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __vmap_pages_range_noflush(long unsigned int addr, long unsigned int end, pgprot_t prot, struct page * * pages, unsigned int page_shift)
```

```json
{
  "name": "__vmap_pages_range_noflush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583315910,
      "name": "__vmap_pages_range_noflush",
      "external": true,
      "loc": "mm/vmalloc.c:579",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap",
        "mm/vmalloc.c:vm_map_ram"
      ],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_area_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597461444,
      "name": "__vmap_pages_range_noflush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071583314624,
      "name": "__vmap_pages_range_noflush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int __vmap_pages_range_noflush(long unsigned int addr, long unsigned int end, pgprot_t prot, struct page * * pages, unsigned int page_shift)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
