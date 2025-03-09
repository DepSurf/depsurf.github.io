# Function: <code>follow_pmd_mask</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "follow_pmd_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580874128,
      "name": "follow_pmd_mask",
      "external": false,
      "loc": "mm/gup.c:211",
      "file": "mm/gup.c",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct page * follow_pmd_mask(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, unsigned int flags, unsigned int * page_mask)
```

```json
{
  "name": "follow_pmd_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580968352,
      "name": "follow_pmd_mask",
      "external": false,
      "loc": "mm/gup.c:211",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580968352,
      "name": "follow_pmd_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1558
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "follow_pmd_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581103407,
      "name": "follow_pmd_mask",
      "external": false,
      "loc": "mm/gup.c:211",
      "file": "mm/gup.c",
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
  "name": "follow_pmd_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581183186,
      "name": "follow_pmd_mask",
      "external": false,
      "loc": "mm/gup.c:209",
      "file": "mm/gup.c",
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
  "name": "follow_pmd_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581253280,
      "name": "follow_pmd_mask",
      "external": false,
      "loc": "mm/gup.c:323",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581253280,
      "name": "follow_pmd_mask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1809
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "follow_pmd_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581311888,
      "name": "follow_pmd_mask",
      "external": false,
      "loc": "mm/gup.c:318",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581311888,
      "name": "follow_pmd_mask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1877
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "follow_pmd_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581501552,
      "name": "follow_pmd_mask",
      "external": false,
      "loc": "mm/gup.c:552",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581501552,
      "name": "follow_pmd_mask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1623
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "follow_pmd_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581541712,
      "name": "follow_pmd_mask",
      "external": false,
      "loc": "mm/gup.c:516",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581541712,
      "name": "follow_pmd_mask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1623
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
  "name": "follow_pmd_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581564912,
      "name": "follow_pmd_mask",
      "external": false,
      "loc": "mm/gup.c:613",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581564912,
      "name": "follow_pmd_mask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1531
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
  "name": "follow_pmd_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581829680,
      "name": "follow_pmd_mask",
      "external": false,
      "loc": "mm/gup.c:636",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581829680,
      "name": "follow_pmd_mask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1529
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "follow_pmd_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582222912,
      "name": "follow_pmd_mask",
      "external": false,
      "loc": "mm/gup.c:647",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582222912,
      "name": "follow_pmd_mask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1394
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "follow_pmd_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582712544,
      "name": "follow_pmd_mask",
      "external": false,
      "loc": "mm/gup.c:646",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_p4d_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582712544,
      "name": "follow_pmd_mask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1509
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "follow_pmd_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582927024,
      "name": "follow_pmd_mask",
      "external": false,
      "loc": "mm/gup.c:691",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_p4d_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582927024,
      "name": "follow_pmd_mask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "follow_pmd_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583101200,
      "name": "follow_pmd_mask",
      "external": false,
      "loc": "mm/gup.c:691",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583101200,
      "name": "follow_pmd_mask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1076
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
struct page * follow_pmd_mask(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, unsigned int flags, struct follow_page_context * ctx)
```

```json
{
  "name": "follow_pmd_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492719728,
      "name": "follow_pmd_mask",
      "external": false,
      "loc": "mm/gup.c:318",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492719728,
      "name": "follow_pmd_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1268
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "follow_pmd_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226552256,
      "name": "follow_pmd_mask",
      "external": false,
      "loc": "mm/gup.c:318",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct page * follow_pmd_mask(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, unsigned int flags, struct follow_page_context * ctx)
```

```json
{
  "name": "follow_pmd_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286061584,
      "name": "follow_pmd_mask",
      "external": false,
      "loc": "mm/gup.c:318",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286061584,
      "name": "follow_pmd_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "follow_pmd_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272714214,
      "name": "follow_pmd_mask",
      "external": false,
      "loc": "mm/gup.c:318",
      "file": "mm/gup.c",
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
  "name": "follow_pmd_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581280736,
      "name": "follow_pmd_mask",
      "external": false,
      "loc": "mm/gup.c:318",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581280736,
      "name": "follow_pmd_mask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1877
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
struct page * follow_pmd_mask(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, unsigned int flags, struct follow_page_context * ctx)
```

```json
{
  "name": "follow_pmd_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581226896,
      "name": "follow_pmd_mask",
      "external": false,
      "loc": "mm/gup.c:318",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581226896,
      "name": "follow_pmd_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1740
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "follow_pmd_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581271936,
      "name": "follow_pmd_mask",
      "external": false,
      "loc": "mm/gup.c:318",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581271936,
      "name": "follow_pmd_mask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1877
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "follow_pmd_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581335808,
      "name": "follow_pmd_mask",
      "external": false,
      "loc": "mm/gup.c:318",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581335808,
      "name": "follow_pmd_mask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1878
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct page * follow_pmd_mask(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, unsigned int flags, unsigned int * page_mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
struct page * follow_pmd_mask(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, unsigned int flags, unsigned int * page_mask)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct page * follow_pmd_mask(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, unsigned int flags, struct follow_page_context * ctx)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct page * follow_pmd_mask(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, unsigned int flags, struct follow_page_context * ctx)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➕</summary>

```c
struct page * follow_pmd_mask(struct vm_area_struct * vma, long unsigned int address, pud_t * pudp, unsigned int flags, struct follow_page_context * ctx)
```
</details>
</li>
</ul>
