# Function: <code>__gup_longterm_locked</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long int __gup_longterm_locked(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, struct page * * pages, struct vm_area_struct * * vmas, unsigned int gup_flags)
```

```json
{
  "name": "__gup_longterm_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581259184,
      "name": "__gup_longterm_locked",
      "external": false,
      "loc": "mm/gup.c:1543",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_fast",
        "mm/gup.c:get_user_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581259184,
      "name": "__gup_longterm_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1281
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
long int __gup_longterm_locked(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, struct page * * pages, struct vm_area_struct * * vmas, unsigned int gup_flags)
```

```json
{
  "name": "__gup_longterm_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581317856,
      "name": "__gup_longterm_locked",
      "external": false,
      "loc": "mm/gup.c:1546",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_fast",
        "mm/gup.c:get_user_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581317856,
      "name": "__gup_longterm_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1288
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long int __gup_longterm_locked(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, struct page * * pages, struct vm_area_struct * * vmas, unsigned int gup_flags)
```

```json
{
  "name": "__gup_longterm_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581508240,
      "name": "__gup_longterm_locked",
      "external": false,
      "loc": "mm/gup.c:1767",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages",
        "mm/gup.c:internal_get_user_pages_fast",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:__get_user_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581508240,
      "name": "__gup_longterm_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__gup_longterm_locked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581548794,
      "name": "__gup_longterm_locked",
      "external": false,
      "loc": "mm/gup.c:1654",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:pin_user_pages",
        "mm/gup.c:internal_get_user_pages_fast",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:__get_user_pages_remote"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
long int __gup_longterm_locked(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, struct page * * pages, struct vm_area_struct * * vmas, unsigned int gup_flags)
```

```json
{
  "name": "__gup_longterm_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581571536,
      "name": "__gup_longterm_locked",
      "external": false,
      "loc": "mm/gup.c:1719",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages",
        "mm/gup.c:internal_get_user_pages_fast",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:__get_user_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581571536,
      "name": "__gup_longterm_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
long int __gup_longterm_locked(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, struct page * * pages, struct vm_area_struct * * vmas, unsigned int gup_flags)
```

```json
{
  "name": "__gup_longterm_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581836112,
      "name": "__gup_longterm_locked",
      "external": false,
      "loc": "mm/gup.c:1807",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages",
        "mm/gup.c:internal_get_user_pages_fast",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:__get_user_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581836112,
      "name": "__gup_longterm_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
long int __gup_longterm_locked(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, struct page * * pages, struct vm_area_struct * * vmas, unsigned int gup_flags)
```

```json
{
  "name": "__gup_longterm_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582227808,
      "name": "__gup_longterm_locked",
      "external": false,
      "loc": "mm/gup.c:1996",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages",
        "mm/gup.c:internal_get_user_pages_fast",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:__get_user_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582227808,
      "name": "__gup_longterm_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
long int __gup_longterm_locked(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, struct page * * pages, struct vm_area_struct * * vmas, int * locked, unsigned int gup_flags)
```

```json
{
  "name": "__gup_longterm_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582716720,
      "name": "__gup_longterm_locked",
      "external": false,
      "loc": "mm/gup.c:2042",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages",
        "mm/gup.c:pin_user_pages_remote",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:get_user_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582716720,
      "name": "__gup_longterm_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1879
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
long int __gup_longterm_locked(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, struct page * * pages, int * locked, unsigned int gup_flags)
```

```json
{
  "name": "__gup_longterm_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582933312,
      "name": "__gup_longterm_locked",
      "external": false,
      "loc": "mm/gup.c:2174",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages_unlocked",
        "mm/gup.c:pin_user_pages",
        "mm/gup.c:pin_user_pages_remote",
        "mm/gup.c:internal_get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582933312,
      "name": "__gup_longterm_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2108
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
long int __gup_longterm_locked(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, struct page * * pages, int * locked, unsigned int gup_flags)
```

```json
{
  "name": "__gup_longterm_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583108256,
      "name": "__gup_longterm_locked",
      "external": false,
      "loc": "mm/gup.c:2200",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages_unlocked",
        "mm/gup.c:pin_user_pages",
        "mm/gup.c:pin_user_pages_remote",
        "mm/gup.c:internal_get_user_pages_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583108256,
      "name": "__gup_longterm_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2421
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
long int __gup_longterm_locked(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, struct page * * pages, struct vm_area_struct * * vmas, unsigned int gup_flags)
```

```json
{
  "name": "__gup_longterm_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492723944,
      "name": "__gup_longterm_locked",
      "external": false,
      "loc": "mm/gup.c:1546",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_fast",
        "mm/gup.c:get_user_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492723944,
      "name": "__gup_longterm_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
long int __gup_longterm_locked(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, struct page * * pages, struct vm_area_struct * * vmas, unsigned int gup_flags)
```

```json
{
  "name": "__gup_longterm_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226555156,
      "name": "__gup_longterm_locked",
      "external": false,
      "loc": "mm/gup.c:1546",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_fast",
        "mm/gup.c:get_user_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226555156,
      "name": "__gup_longterm_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1036
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int __gup_longterm_locked(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, struct page * * pages, struct vm_area_struct * * vmas, unsigned int gup_flags)
```

```json
{
  "name": "__gup_longterm_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286069312,
      "name": "__gup_longterm_locked",
      "external": false,
      "loc": "mm/gup.c:1546",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_fast",
        "mm/gup.c:get_user_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286069312,
      "name": "__gup_longterm_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1772
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
long int __gup_longterm_locked(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, struct page * * pages, struct vm_area_struct * * vmas, unsigned int gup_flags)
```

```json
{
  "name": "__gup_longterm_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272716490,
      "name": "__gup_longterm_locked",
      "external": false,
      "loc": "mm/gup.c:1546",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_fast",
        "mm/gup.c:get_user_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272716490,
      "name": "__gup_longterm_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 910
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long int __gup_longterm_locked(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, struct page * * pages, struct vm_area_struct * * vmas, unsigned int gup_flags)
```

```json
{
  "name": "__gup_longterm_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581286704,
      "name": "__gup_longterm_locked",
      "external": false,
      "loc": "mm/gup.c:1546",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_fast",
        "mm/gup.c:get_user_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581286704,
      "name": "__gup_longterm_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1288
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
long int __gup_longterm_locked(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, struct page * * pages, struct vm_area_struct * * vmas, unsigned int gup_flags)
```

```json
{
  "name": "__gup_longterm_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581232512,
      "name": "__gup_longterm_locked",
      "external": false,
      "loc": "mm/gup.c:1546",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_fast",
        "mm/gup.c:get_user_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581232512,
      "name": "__gup_longterm_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1288
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
long int __gup_longterm_locked(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, struct page * * pages, struct vm_area_struct * * vmas, unsigned int gup_flags)
```

```json
{
  "name": "__gup_longterm_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581277904,
      "name": "__gup_longterm_locked",
      "external": false,
      "loc": "mm/gup.c:1546",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_fast",
        "mm/gup.c:get_user_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581277904,
      "name": "__gup_longterm_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1288
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
long int __gup_longterm_locked(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, struct page * * pages, struct vm_area_struct * * vmas, unsigned int gup_flags)
```

```json
{
  "name": "__gup_longterm_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581341824,
      "name": "__gup_longterm_locked",
      "external": false,
      "loc": "mm/gup.c:1546",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_fast",
        "mm/gup.c:get_user_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581341824,
      "name": "__gup_longterm_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1288
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
long int __gup_longterm_locked(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, struct page * * pages, struct vm_area_struct * * vmas, unsigned int gup_flags)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
long int __gup_longterm_locked(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, struct page * * pages, struct vm_area_struct * * vmas, unsigned int gup_flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
long int __gup_longterm_locked(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, struct page * * pages, struct vm_area_struct * * vmas, unsigned int gup_flags)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int * locked</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, start, nr_pages, pages, vmas, gup_flags</code> ➡️ <code>mm, start, nr_pages, pages, vmas, locked, gup_flags</code>
</li>
</ul>
</details>
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
<code>mm, start, nr_pages, pages, vmas, locked, gup_flags</code> ➡️ <code>mm, start, nr_pages, pages, locked, gup_flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
