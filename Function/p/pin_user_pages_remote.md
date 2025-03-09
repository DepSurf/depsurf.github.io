# Function: <code>pin_user_pages_remote</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long int pin_user_pages_remote(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "pin_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581509680,
      "name": "pin_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:2994",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw_single_vec",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581509680,
      "name": "pin_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
long int pin_user_pages_remote(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "pin_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581549792,
      "name": "pin_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:2781",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581549792,
      "name": "pin_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
long int pin_user_pages_remote(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "pin_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581572912,
      "name": "pin_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:2847",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581572912,
      "name": "pin_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
long int pin_user_pages_remote(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "pin_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581837472,
      "name": "pin_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:2942",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581837472,
      "name": "pin_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
long int pin_user_pages_remote(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "pin_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582229376,
      "name": "pin_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:3097",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582229376,
      "name": "pin_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
long int pin_user_pages_remote(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "pin_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582719312,
      "name": "pin_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:3123",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582719312,
      "name": "pin_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
long int pin_user_pages_remote(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, int * locked)
```

```json
{
  "name": "pin_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582935440,
      "name": "pin_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:3330",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_user.c:user_event_enabler_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582935440,
      "name": "pin_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
long int pin_user_pages_remote(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, int * locked)
```

```json
{
  "name": "pin_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583110704,
      "name": "pin_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:3348",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_user.c:user_event_enabler_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583110704,
      "name": "pin_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long int pin_user_pages_remote(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct * tsk</code>
</li>
<li>
<b>Param reordered. </b>
<code>tsk, mm, start, nr_pages, gup_flags, pages, vmas, locked</code> ➡️ <code>mm, start, nr_pages, gup_flags, pages, vmas, locked</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct * * vmas</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, start, nr_pages, gup_flags, pages, vmas, locked</code> ➡️ <code>mm, start, nr_pages, gup_flags, pages, locked</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
