# Function: <code>vma_complete</code>

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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void vma_complete(struct vma_prepare * vp, struct vma_iterator * vmi, struct mm_struct * mm)
```

```json
{
  "name": "vma_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583020752,
      "name": "vma_complete",
      "external": false,
      "loc": "mm/mmap.c:528",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_shrink",
        "mm/mmap.c:vma_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583020752,
      "name": "vma_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
void vma_complete(struct vma_prepare * vp, struct vma_iterator * vmi, struct mm_struct * mm)
```

```json
{
  "name": "vma_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583200416,
      "name": "vma_complete",
      "external": false,
      "loc": "mm/mmap.c:510",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_shrink",
        "mm/mmap.c:vma_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583200416,
      "name": "vma_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 688
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void vma_complete(struct vma_prepare * vp, struct vma_iterator * vmi, struct mm_struct * mm)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
