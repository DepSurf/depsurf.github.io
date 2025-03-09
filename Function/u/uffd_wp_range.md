# Function: <code>uffd_wp_range</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void uffd_wp_range(struct mm_struct * dst_mm, struct vm_area_struct * dst_vma, long unsigned int start, long unsigned int len, bool enable_wp)
```

```json
{
  "name": "uffd_wp_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582933072,
      "name": "uffd_wp_range",
      "external": true,
      "loc": "mm/userfaultfd.c:706",
      "file": "mm/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mwriteprotect_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582933072,
      "name": "uffd_wp_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
void uffd_wp_range(struct mm_struct * dst_mm, struct vm_area_struct * dst_vma, long unsigned int start, long unsigned int len, bool enable_wp)
```

```json
{
  "name": "uffd_wp_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583488768,
      "name": "uffd_wp_range",
      "external": true,
      "loc": "mm/userfaultfd.c:727",
      "file": "mm/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mwriteprotect_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583488768,
      "name": "uffd_wp_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
long int uffd_wp_range(struct vm_area_struct * dst_vma, long unsigned int start, long unsigned int len, bool enable_wp)
```

```json
{
  "name": "uffd_wp_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583704352,
      "name": "uffd_wp_range",
      "external": true,
      "loc": "mm/userfaultfd.c:705",
      "file": "mm/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mwriteprotect_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583704352,
      "name": "uffd_wp_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
long int uffd_wp_range(struct vm_area_struct * dst_vma, long unsigned int start, long unsigned int len, bool enable_wp)
```

```json
{
  "name": "uffd_wp_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583901152,
      "name": "uffd_wp_range",
      "external": true,
      "loc": "mm/userfaultfd.c:767",
      "file": "mm/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mwriteprotect_range",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/proc/task_mmu.c:pagemap_scan_pte_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583901152,
      "name": "uffd_wp_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void uffd_wp_range(struct mm_struct * dst_mm, struct vm_area_struct * dst_vma, long unsigned int start, long unsigned int len, bool enable_wp)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct mm_struct * dst_mm</code>
</li>
<li>
<b>Param reordered. </b>
<code>dst_mm, dst_vma, start, len, enable_wp</code> ➡️ <code>dst_vma, start, len, enable_wp</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>long int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
