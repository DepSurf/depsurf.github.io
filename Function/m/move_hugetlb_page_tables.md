# Function: <code>move_hugetlb_page_tables</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int move_hugetlb_page_tables(struct vm_area_struct * vma, struct vm_area_struct * new_vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int len)
```

```json
{
  "name": "move_hugetlb_page_tables",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "move_hugetlb_page_tables",
      "external": true,
      "loc": "mm/hugetlb.c:4931",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593993074,
      "name": "move_hugetlb_page_tables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071582590048,
      "name": "move_hugetlb_page_tables",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1144
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
int move_hugetlb_page_tables(struct vm_area_struct * vma, struct vm_area_struct * new_vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int len)
```

```json
{
  "name": "move_hugetlb_page_tables",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "move_hugetlb_page_tables",
      "external": true,
      "loc": "mm/hugetlb.c:5171",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596042962,
      "name": "move_hugetlb_page_tables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071583102000,
      "name": "move_hugetlb_page_tables",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1253
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
int move_hugetlb_page_tables(struct vm_area_struct * vma, struct vm_area_struct * new_vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int len)
```

```json
{
  "name": "move_hugetlb_page_tables",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "move_hugetlb_page_tables",
      "external": true,
      "loc": "mm/hugetlb.c:5257",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596565180,
      "name": "move_hugetlb_page_tables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071583311840,
      "name": "move_hugetlb_page_tables",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1270
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
int move_hugetlb_page_tables(struct vm_area_struct * vma, struct vm_area_struct * new_vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int len)
```

```json
{
  "name": "move_hugetlb_page_tables",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "move_hugetlb_page_tables",
      "external": true,
      "loc": "mm/hugetlb.c:5512",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597470792,
      "name": "move_hugetlb_page_tables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071583549968,
      "name": "move_hugetlb_page_tables",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1217
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int move_hugetlb_page_tables(struct vm_area_struct * vma, struct vm_area_struct * new_vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int len)
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
