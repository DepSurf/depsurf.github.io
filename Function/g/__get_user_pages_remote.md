# Function: <code>__get_user_pages_remote</code>

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
long int __get_user_pages_remote(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "__get_user_pages_remote",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581508928,
      "name": "__get_user_pages_remote",
      "external": false,
      "loc": "mm/gup.c:1832",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages_remote",
        "mm/gup.c:get_user_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581508928,
      "name": "__get_user_pages_remote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 690
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
long int __get_user_pages_remote(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "__get_user_pages_remote",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581548848,
      "name": "__get_user_pages_remote",
      "external": false,
      "loc": "mm/gup.c:1699",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages_remote",
        "mm/gup.c:get_user_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581548848,
      "name": "__get_user_pages_remote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 832
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
long int __get_user_pages_remote(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "__get_user_pages_remote",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581572016,
      "name": "__get_user_pages_remote",
      "external": false,
      "loc": "mm/gup.c:1765",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages_remote",
        "mm/gup.c:get_user_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581572016,
      "name": "__get_user_pages_remote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 775
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
long int __get_user_pages_remote(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "__get_user_pages_remote",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581836608,
      "name": "__get_user_pages_remote",
      "external": false,
      "loc": "mm/gup.c:1853",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages_remote",
        "mm/gup.c:get_user_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581836608,
      "name": "__get_user_pages_remote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 795
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
long int __get_user_pages_remote(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "__get_user_pages_remote",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582228432,
      "name": "__get_user_pages_remote",
      "external": false,
      "loc": "mm/gup.c:2042",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages_remote",
        "mm/gup.c:get_user_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582228432,
      "name": "__get_user_pages_remote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 828
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
long int __get_user_pages_remote(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
long int __get_user_pages_remote(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```
</details>
</li>
</ul>
