# Function: <code>hpage_collapse_scan_pmd</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int hpage_collapse_scan_pmd(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, bool * mmap_locked, struct collapse_control * cc)
```

```json
{
  "name": "hpage_collapse_scan_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hpage_collapse_scan_pmd",
      "external": false,
      "loc": "mm/khugepaged.c:1128",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:madvise_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583345984,
      "name": "hpage_collapse_scan_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2411
    },
    {
      "addr": 18446744071596047845,
      "name": "hpage_collapse_scan_pmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
int hpage_collapse_scan_pmd(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, bool * mmap_locked, struct collapse_control * cc)
```

```json
{
  "name": "hpage_collapse_scan_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hpage_collapse_scan_pmd",
      "external": false,
      "loc": "mm/khugepaged.c:1246",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:madvise_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583558368,
      "name": "hpage_collapse_scan_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2343
    },
    {
      "addr": 18446744071596570326,
      "name": "hpage_collapse_scan_pmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int hpage_collapse_scan_pmd(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, bool * mmap_locked, struct collapse_control * cc)
```

```json
{
  "name": "hpage_collapse_scan_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hpage_collapse_scan_pmd",
      "external": false,
      "loc": "mm/khugepaged.c:1247",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:madvise_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583758272,
      "name": "hpage_collapse_scan_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1883
    },
    {
      "addr": 18446744071597474786,
      "name": "hpage_collapse_scan_pmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
int hpage_collapse_scan_pmd(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, bool * mmap_locked, struct collapse_control * cc)
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
