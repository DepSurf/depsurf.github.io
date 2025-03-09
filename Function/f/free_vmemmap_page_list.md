# Function: <code>free_vmemmap_page_list</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_vmemmap_page_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582172839,
      "name": "free_vmemmap_page_list",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:223",
      "file": "mm/sparse-vmemmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_remap_free"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_vmemmap_page_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582631717,
      "name": "free_vmemmap_page_list",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:249",
      "file": "mm/sparse-vmemmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_remap_free"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_vmemmap_page_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583120677,
      "name": "free_vmemmap_page_list",
      "external": false,
      "loc": "mm/hugetlb_vmemmap.c:226",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_remap_free"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_vmemmap_page_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583331365,
      "name": "free_vmemmap_page_list",
      "external": false,
      "loc": "mm/hugetlb_vmemmap.c:226",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_remap_free"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void free_vmemmap_page_list(struct list_head * list)
```

```json
{
  "name": "free_vmemmap_page_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583564752,
      "name": "free_vmemmap_page_list",
      "external": false,
      "loc": "mm/hugetlb_vmemmap.c:194",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb_vmemmap.c:hugetlb_vmemmap_optimize_folios",
        "mm/hugetlb_vmemmap.c:hugetlb_vmemmap_optimize_folios",
        "mm/hugetlb_vmemmap.c:hugetlb_vmemmap_optimize_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583564752,
      "name": "free_vmemmap_page_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void free_vmemmap_page_list(struct list_head * list)
```
</details>
</li>
</ul>
