# Function: <code>copy_nonpresent_pte</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_nonpresent_pte",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581562112,
      "name": "copy_nonpresent_pte",
      "external": false,
      "loc": "mm/memory.c:698",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581562112,
      "name": "copy_nonpresent_pte.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 793
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
  "name": "copy_nonpresent_pte",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581588096,
      "name": "copy_nonpresent_pte",
      "external": false,
      "loc": "mm/memory.c:710",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581588096,
      "name": "copy_nonpresent_pte.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 745
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
long unsigned int copy_nonpresent_pte(struct mm_struct * dst_mm, struct mm_struct * src_mm, pte_t * dst_pte, pte_t * src_pte, struct vm_area_struct * dst_vma, struct vm_area_struct * src_vma, long unsigned int addr, int * rss)
```

```json
{
  "name": "copy_nonpresent_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581854256,
      "name": "copy_nonpresent_pte",
      "external": false,
      "loc": "mm/memory.c:771",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581854256,
      "name": "copy_nonpresent_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 815
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
long unsigned int copy_nonpresent_pte(struct mm_struct * dst_mm, struct mm_struct * src_mm, pte_t * dst_pte, pte_t * src_pte, struct vm_area_struct * dst_vma, struct vm_area_struct * src_vma, long unsigned int addr, int * rss)
```

```json
{
  "name": "copy_nonpresent_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582248672,
      "name": "copy_nonpresent_pte",
      "external": false,
      "loc": "mm/memory.c:777",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582248672,
      "name": "copy_nonpresent_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 980
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
long unsigned int copy_nonpresent_pte(struct mm_struct * dst_mm, struct mm_struct * src_mm, pte_t * dst_pte, pte_t * src_pte, struct vm_area_struct * dst_vma, struct vm_area_struct * src_vma, long unsigned int addr, int * rss)
```

```json
{
  "name": "copy_nonpresent_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582737088,
      "name": "copy_nonpresent_pte",
      "external": false,
      "loc": "mm/memory.c:738",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582737088,
      "name": "copy_nonpresent_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 956
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
long unsigned int copy_nonpresent_pte(struct mm_struct * dst_mm, struct mm_struct * src_mm, pte_t * dst_pte, pte_t * src_pte, struct vm_area_struct * dst_vma, struct vm_area_struct * src_vma, long unsigned int addr, int * rss)
```

```json
{
  "name": "copy_nonpresent_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582956576,
      "name": "copy_nonpresent_pte",
      "external": false,
      "loc": "mm/memory.c:769",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582956576,
      "name": "copy_nonpresent_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1160
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
long unsigned int copy_nonpresent_pte(struct mm_struct * dst_mm, struct mm_struct * src_mm, pte_t * dst_pte, pte_t * src_pte, struct vm_area_struct * dst_vma, struct vm_area_struct * src_vma, long unsigned int addr, int * rss)
```

```json
{
  "name": "copy_nonpresent_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583132400,
      "name": "copy_nonpresent_pte",
      "external": false,
      "loc": "mm/memory.c:779",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583132400,
      "name": "copy_nonpresent_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1178
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
long unsigned int copy_nonpresent_pte(struct mm_struct * dst_mm, struct mm_struct * src_mm, pte_t * dst_pte, pte_t * src_pte, struct vm_area_struct * dst_vma, struct vm_area_struct * src_vma, long unsigned int addr, int * rss)
```
</details>
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
