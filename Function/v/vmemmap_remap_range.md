# Function: <code>vmemmap_remap_range</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int vmemmap_remap_range(long unsigned int start, long unsigned int end, struct vmemmap_remap_walk * walk)
```

```json
{
  "name": "vmemmap_remap_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmemmap_remap_range",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:178",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_remap_alloc",
        "mm/sparse-vmemmap.c:vmemmap_remap_free",
        "mm/sparse-vmemmap.c:vmemmap_remap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582170784,
      "name": "vmemmap_remap_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1314
    },
    {
      "addr": 18446744071592216472,
      "name": "vmemmap_remap_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int vmemmap_remap_range(long unsigned int start, long unsigned int end, struct vmemmap_remap_walk * walk)
```

```json
{
  "name": "vmemmap_remap_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmemmap_remap_range",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:204",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_remap_alloc",
        "mm/sparse-vmemmap.c:vmemmap_remap_free",
        "mm/sparse-vmemmap.c:vmemmap_remap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582630368,
      "name": "vmemmap_remap_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
    },
    {
      "addr": 18446744071593995281,
      "name": "vmemmap_remap_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int vmemmap_remap_range(long unsigned int start, long unsigned int end, struct vmemmap_remap_walk * walk)
```

```json
{
  "name": "vmemmap_remap_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmemmap_remap_range",
      "external": false,
      "loc": "mm/hugetlb_vmemmap.c:186",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb_vmemmap.c:vmemmap_remap_free",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583119360,
      "name": "vmemmap_remap_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
    },
    {
      "addr": 18446744071596044465,
      "name": "vmemmap_remap_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
int vmemmap_remap_range(long unsigned int start, long unsigned int end, struct vmemmap_remap_walk * walk)
```

```json
{
  "name": "vmemmap_remap_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmemmap_remap_range",
      "external": false,
      "loc": "mm/hugetlb_vmemmap.c:186",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb_vmemmap.c:vmemmap_remap_alloc",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_free",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583329616,
      "name": "vmemmap_remap_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1012
    },
    {
      "addr": 18446744071596566893,
      "name": "vmemmap_remap_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
int vmemmap_remap_range(long unsigned int start, long unsigned int end, struct vmemmap_remap_walk * walk)
```

```json
{
  "name": "vmemmap_remap_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583565184,
      "name": "vmemmap_remap_range",
      "external": false,
      "loc": "mm/hugetlb_vmemmap.c:159",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb_vmemmap.c:hugetlb_vmemmap_optimize_folios",
        "mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_optimize_folio",
        "mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_optimize_folio",
        "mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_restore_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583565184,
      "name": "vmemmap_remap_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
int vmemmap_remap_range(long unsigned int start, long unsigned int end, struct vmemmap_remap_walk * walk)
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
