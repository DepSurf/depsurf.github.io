# Function: <code>__get_user_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int __get_user_pages(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * nonblocking)
```

```json
{
  "name": "__get_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580658384,
      "name": "__get_user_pages",
      "external": true,
      "loc": "mm/gup.c:453",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:populate_vma_page_range",
        "mm/gup.c:get_dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580658384,
      "name": "__get_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1562
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long int __get_user_pages(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * nonblocking)
```

```json
{
  "name": "__get_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580767040,
      "name": "__get_user_pages",
      "external": true,
      "loc": "mm/gup.c:519",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_dump_page",
        "mm/gup.c:populate_vma_page_range",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:get_user_pages_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580767040,
      "name": "__get_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1693
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
long int __get_user_pages(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * nonblocking)
```

```json
{
  "name": "__get_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580832608,
      "name": "__get_user_pages",
      "external": false,
      "loc": "mm/gup.c:530",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_dump_page",
        "mm/gup.c:populate_vma_page_range",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:get_user_pages_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580832608,
      "name": "__get_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1655
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
long int __get_user_pages(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * nonblocking)
```

```json
{
  "name": "__get_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580875296,
      "name": "__get_user_pages",
      "external": false,
      "loc": "mm/gup.c:613",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_dump_page",
        "mm/gup.c:populate_vma_page_range",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:get_user_pages_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580875296,
      "name": "__get_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1601
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
long int __get_user_pages(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * nonblocking)
```

```json
{
  "name": "__get_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580970448,
      "name": "__get_user_pages",
      "external": false,
      "loc": "mm/gup.c:638",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_dump_page",
        "mm/gup.c:populate_vma_page_range",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:get_user_pages_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580970448,
      "name": "__get_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1759
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long int __get_user_pages(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * nonblocking)
```

```json
{
  "name": "__get_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581104960,
      "name": "__get_user_pages",
      "external": false,
      "loc": "mm/gup.c:657",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_dump_page",
        "mm/gup.c:populate_vma_page_range",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:get_user_pages_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581104960,
      "name": "__get_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1739
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long int __get_user_pages(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * nonblocking)
```

```json
{
  "name": "__get_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581184800,
      "name": "__get_user_pages",
      "external": false,
      "loc": "mm/gup.c:674",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_dump_page",
        "mm/gup.c:populate_vma_page_range",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:get_user_pages_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581184800,
      "name": "__get_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1807
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long int __get_user_pages(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * nonblocking)
```

```json
{
  "name": "__get_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581255680,
      "name": "__get_user_pages",
      "external": false,
      "loc": "mm/gup.c:790",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:populate_vma_page_range",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:get_user_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581255680,
      "name": "__get_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1904
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
long int __get_user_pages(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * nonblocking)
```

```json
{
  "name": "__get_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581314352,
      "name": "__get_user_pages",
      "external": false,
      "loc": "mm/gup.c:789",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:populate_vma_page_range",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:get_user_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581314352,
      "name": "__get_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1904
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
long int __get_user_pages(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "__get_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581504768,
      "name": "__get_user_pages",
      "external": false,
      "loc": "mm/gup.c:1031",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:populate_vma_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581504768,
      "name": "__get_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1420
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
long int __get_user_pages(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "__get_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581544928,
      "name": "__get_user_pages",
      "external": false,
      "loc": "mm/gup.c:990",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:pin_user_pages",
        "mm/gup.c:internal_get_user_pages_fast",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:populate_vma_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581544928,
      "name": "__get_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1351
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
long int __get_user_pages(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "__get_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581567856,
      "name": "__get_user_pages",
      "external": false,
      "loc": "mm/gup.c:1075",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:populate_vma_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581567856,
      "name": "__get_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1374
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
long int __get_user_pages(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "__get_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581832688,
      "name": "__get_user_pages",
      "external": false,
      "loc": "mm/gup.c:1104",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:faultin_vma_page_range",
        "mm/gup.c:populate_vma_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581832688,
      "name": "__get_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1053
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
long int __get_user_pages(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "__get_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582225904,
      "name": "__get_user_pages",
      "external": false,
      "loc": "mm/gup.c:1122",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:faultin_vma_page_range",
        "mm/gup.c:populate_vma_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582225904,
      "name": "__get_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1025
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
long int __get_user_pages(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "__get_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582715648,
      "name": "__get_user_pages",
      "external": false,
      "loc": "mm/gup.c:1082",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:faultin_vma_page_range",
        "mm/gup.c:populate_vma_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582715648,
      "name": "__get_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1050
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
long int __get_user_pages(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, int * locked)
```

```json
{
  "name": "__get_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582929664,
      "name": "__get_user_pages",
      "external": false,
      "loc": "mm/gup.c:1191",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:faultin_vma_page_range",
        "mm/gup.c:populate_vma_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582929664,
      "name": "__get_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
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
long int __get_user_pages(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, int * locked)
```

```json
{
  "name": "__get_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583103888,
      "name": "__get_user_pages",
      "external": false,
      "loc": "mm/gup.c:1186",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:faultin_vma_page_range",
        "mm/gup.c:populate_vma_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583103888,
      "name": "__get_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1258
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
long int __get_user_pages(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * nonblocking)
```

```json
{
  "name": "__get_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492721336,
      "name": "__get_user_pages",
      "external": false,
      "loc": "mm/gup.c:789",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:populate_vma_page_range",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:get_user_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492721336,
      "name": "__get_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
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
long int __get_user_pages(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * nonblocking)
```

```json
{
  "name": "__get_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226551992,
      "name": "__get_user_pages",
      "external": false,
      "loc": "mm/gup.c:789",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:populate_vma_page_range",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:get_user_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226551992,
      "name": "__get_user_pages",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int __get_user_pages(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * nonblocking)
```

```json
{
  "name": "__get_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286065648,
      "name": "__get_user_pages",
      "external": false,
      "loc": "mm/gup.c:789",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:populate_vma_page_range",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:get_user_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286065648,
      "name": "__get_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1440
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
long int __get_user_pages(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * nonblocking)
```

```json
{
  "name": "__get_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272714420,
      "name": "__get_user_pages",
      "external": false,
      "loc": "mm/gup.c:789",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:populate_vma_page_range",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:get_user_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272714420,
      "name": "__get_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 898
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
long int __get_user_pages(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * nonblocking)
```

```json
{
  "name": "__get_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581283200,
      "name": "__get_user_pages",
      "external": false,
      "loc": "mm/gup.c:789",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:populate_vma_page_range",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:get_user_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581283200,
      "name": "__get_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1904
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
long int __get_user_pages(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * nonblocking)
```

```json
{
  "name": "__get_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581229152,
      "name": "__get_user_pages",
      "external": false,
      "loc": "mm/gup.c:789",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:populate_vma_page_range",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:get_user_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581229152,
      "name": "__get_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1755
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
long int __get_user_pages(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * nonblocking)
```

```json
{
  "name": "__get_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581274400,
      "name": "__get_user_pages",
      "external": false,
      "loc": "mm/gup.c:789",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:populate_vma_page_range",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:get_user_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581274400,
      "name": "__get_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1904
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
long int __get_user_pages(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * nonblocking)
```

```json
{
  "name": "__get_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581338272,
      "name": "__get_user_pages",
      "external": false,
      "loc": "mm/gup.c:789",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:populate_vma_page_range",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:get_user_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581338272,
      "name": "__get_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1945
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int * locked</code>
</li>
<li>
<b>Param removed. </b>
<code>int * nonblocking</code>
</li>
</ul>
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
