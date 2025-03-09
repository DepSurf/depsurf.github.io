# Function: <code>__vmalloc_area_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__vmalloc_area_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580741843,
      "name": "__vmalloc_area_node",
      "external": false,
      "loc": "mm/vmalloc.c:1579",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__vmalloc_area_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580861027,
      "name": "__vmalloc_area_node",
      "external": false,
      "loc": "mm/vmalloc.c:1601",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__vmalloc_area_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580931331,
      "name": "__vmalloc_area_node",
      "external": false,
      "loc": "mm/vmalloc.c:1616",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_node_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__vmalloc_area_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580975563,
      "name": "__vmalloc_area_node",
      "external": false,
      "loc": "mm/vmalloc.c:1668",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__vmalloc_area_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581078183,
      "name": "__vmalloc_area_node",
      "external": false,
      "loc": "mm/vmalloc.c:1666",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__vmalloc_area_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581217112,
      "name": "__vmalloc_area_node",
      "external": false,
      "loc": "mm/vmalloc.c:1653",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__vmalloc_area_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581300840,
      "name": "__vmalloc_area_node",
      "external": false,
      "loc": "mm/vmalloc.c:1659",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__vmalloc_area_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581377976,
      "name": "__vmalloc_area_node",
      "external": false,
      "loc": "mm/vmalloc.c:2393",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__vmalloc_area_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581439176,
      "name": "__vmalloc_area_node",
      "external": false,
      "loc": "mm/vmalloc.c:2399",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void * __vmalloc_area_node(struct vm_struct * area, gfp_t gfp_mask, pgprot_t prot, int node)
```

```json
{
  "name": "__vmalloc_area_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581647600,
      "name": "__vmalloc_area_node",
      "external": false,
      "loc": "mm/vmalloc.c:2444",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_node_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581647600,
      "name": "__vmalloc_area_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
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
void * __vmalloc_area_node(struct vm_struct * area, gfp_t gfp_mask, pgprot_t prot, int node)
```

```json
{
  "name": "__vmalloc_area_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581694080,
      "name": "__vmalloc_area_node",
      "external": false,
      "loc": "mm/vmalloc.c:2478",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_node_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581694080,
      "name": "__vmalloc_area_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__vmalloc_area_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581717056,
      "name": "__vmalloc_area_node",
      "external": false,
      "loc": "mm/vmalloc.c:2762",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_node_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581717056,
      "name": "__vmalloc_area_node.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__vmalloc_area_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581989296,
      "name": "__vmalloc_area_node",
      "external": false,
      "loc": "mm/vmalloc.c:2886",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_node_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989296,
      "name": "__vmalloc_area_node.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 634
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
void * __vmalloc_area_node(struct vm_struct * area, gfp_t gfp_mask, pgprot_t prot, unsigned int page_shift, int node)
```

```json
{
  "name": "__vmalloc_area_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582411424,
      "name": "__vmalloc_area_node",
      "external": false,
      "loc": "mm/vmalloc.c:2958",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_node_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582411424,
      "name": "__vmalloc_area_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 924
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void * __vmalloc_area_node(struct vm_struct * area, gfp_t gfp_mask, pgprot_t prot, unsigned int page_shift, int node)
```

```json
{
  "name": "__vmalloc_area_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__vmalloc_area_node",
      "external": false,
      "loc": "mm/vmalloc.c:3020",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_node_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582918480,
      "name": "__vmalloc_area_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1403
    },
    {
      "addr": 18446744071596035277,
      "name": "__vmalloc_area_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void * __vmalloc_area_node(struct vm_struct * area, gfp_t gfp_mask, pgprot_t prot, unsigned int page_shift, int node)
```

```json
{
  "name": "__vmalloc_area_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__vmalloc_area_node",
      "external": false,
      "loc": "mm/vmalloc.c:3102",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_node_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583134464,
      "name": "__vmalloc_area_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1580
    },
    {
      "addr": 18446744071596557420,
      "name": "__vmalloc_area_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void * __vmalloc_area_node(struct vm_struct * area, gfp_t gfp_mask, pgprot_t prot, unsigned int page_shift, int node)
```

```json
{
  "name": "__vmalloc_area_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__vmalloc_area_node",
      "external": false,
      "loc": "mm/vmalloc.c:3102",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_node_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583317520,
      "name": "__vmalloc_area_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1636
    },
    {
      "addr": 18446744071597461664,
      "name": "__vmalloc_area_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__vmalloc_area_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492842820,
      "name": "__vmalloc_area_node",
      "external": false,
      "loc": "mm/vmalloc.c:2399",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__vmalloc_area_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226649572,
      "name": "__vmalloc_area_node",
      "external": false,
      "loc": "mm/vmalloc.c:2399",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__vmalloc_area_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286231576,
      "name": "__vmalloc_area_node",
      "external": false,
      "loc": "mm/vmalloc.c:2399",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__vmalloc_area_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272794678,
      "name": "__vmalloc_area_node",
      "external": false,
      "loc": "mm/vmalloc.c:2399",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__vmalloc_area_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581408024,
      "name": "__vmalloc_area_node",
      "external": false,
      "loc": "mm/vmalloc.c:2399",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__vmalloc_area_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581350536,
      "name": "__vmalloc_area_node",
      "external": false,
      "loc": "mm/vmalloc.c:2399",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__vmalloc_area_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581399224,
      "name": "__vmalloc_area_node",
      "external": false,
      "loc": "mm/vmalloc.c:2399",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__vmalloc_area_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581463240,
      "name": "__vmalloc_area_node",
      "external": false,
      "loc": "mm/vmalloc.c:2399",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void * __vmalloc_area_node(struct vm_struct * area, gfp_t gfp_mask, pgprot_t prot, int node)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void * __vmalloc_area_node(struct vm_struct * area, gfp_t gfp_mask, pgprot_t prot, int node)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void * __vmalloc_area_node(struct vm_struct * area, gfp_t gfp_mask, pgprot_t prot, unsigned int page_shift, int node)
```
</details>
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
