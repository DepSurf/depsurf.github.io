# Function: <code>vmap_pages_pud_range</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int vmap_pages_pud_range(p4d_t * p4d, long unsigned int addr, long unsigned int end, pgprot_t prot, struct page * * pages, int * nr, pgtbl_mod_mask * mask)
```

```json
{
  "name": "vmap_pages_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581694912,
      "name": "vmap_pages_pud_range",
      "external": false,
      "loc": "mm/vmalloc.c:477",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap_small_pages_range_noflush",
        "mm/vmalloc.c:vmap_small_pages_range_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581694912,
      "name": "vmap_pages_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 765
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
int vmap_pages_pud_range(p4d_t * p4d, long unsigned int addr, long unsigned int end, pgprot_t prot, struct page * * pages, int * nr, pgtbl_mod_mask * mask)
```

```json
{
  "name": "vmap_pages_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581967088,
      "name": "vmap_pages_pud_range",
      "external": false,
      "loc": "mm/vmalloc.c:505",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap_small_pages_range_noflush",
        "mm/vmalloc.c:vmap_small_pages_range_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581967088,
      "name": "vmap_pages_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 766
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
int vmap_pages_pud_range(p4d_t * p4d, long unsigned int addr, long unsigned int end, pgprot_t prot, struct page * * pages, int * nr, pgtbl_mod_mask * mask)
```

```json
{
  "name": "vmap_pages_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582389728,
      "name": "vmap_pages_pud_range",
      "external": false,
      "loc": "mm/vmalloc.c:506",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap_small_pages_range_noflush",
        "mm/vmalloc.c:vmap_small_pages_range_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582389728,
      "name": "vmap_pages_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1118
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
int vmap_pages_pud_range(p4d_t * p4d, long unsigned int addr, long unsigned int end, pgprot_t prot, struct page * * pages, int * nr, pgtbl_mod_mask * mask)
```

```json
{
  "name": "vmap_pages_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582895984,
      "name": "vmap_pages_pud_range",
      "external": false,
      "loc": "mm/vmalloc.c:518",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap_small_pages_range_noflush",
        "mm/vmalloc.c:vmap_small_pages_range_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582895984,
      "name": "vmap_pages_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1121
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
int vmap_pages_pud_range(p4d_t * p4d, long unsigned int addr, long unsigned int end, pgprot_t prot, struct page * * pages, int * nr, pgtbl_mod_mask * mask)
```

```json
{
  "name": "vmap_pages_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583111136,
      "name": "vmap_pages_pud_range",
      "external": false,
      "loc": "mm/vmalloc.c:507",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap_small_pages_range_noflush",
        "mm/vmalloc.c:vmap_small_pages_range_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583111136,
      "name": "vmap_pages_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1119
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
int vmap_pages_pud_range(p4d_t * p4d, long unsigned int addr, long unsigned int end, pgprot_t prot, struct page * * pages, int * nr, pgtbl_mod_mask * mask)
```

```json
{
  "name": "vmap_pages_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583293392,
      "name": "vmap_pages_pud_range",
      "external": false,
      "loc": "mm/vmalloc.c:507",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap_small_pages_range_noflush",
        "mm/vmalloc.c:vmap_small_pages_range_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583293392,
      "name": "vmap_pages_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1223
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
int vmap_pages_pud_range(p4d_t * p4d, long unsigned int addr, long unsigned int end, pgprot_t prot, struct page * * pages, int * nr, pgtbl_mod_mask * mask)
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
