# Function: <code>xen_page_pinned</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_page_pinned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578975913,
      "name": "xen_page_pinned",
      "external": false,
      "loc": "arch/x86/xen/mmu.c:190",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_set_pud",
        "arch/x86/xen/mmu.c:xen_set_pmd",
        "arch/x86/xen/mmu.c:xen_exit_mmap",
        "arch/x86/xen/mmu.c:xen_set_pgd",
        "arch/x86/xen/mmu.c:xen_set_pgd"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_page_pinned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578978324,
      "name": "xen_page_pinned",
      "external": false,
      "loc": "arch/x86/xen/mmu.c:191",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_exit_mmap",
        "arch/x86/xen/mmu.c:xen_set_pgd",
        "arch/x86/xen/mmu.c:xen_set_pgd",
        "arch/x86/xen/mmu.c:xen_set_pud",
        "arch/x86/xen/mmu.c:xen_set_pmd"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_page_pinned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578980055,
      "name": "xen_page_pinned",
      "external": false,
      "loc": "arch/x86/xen/mmu.c:191",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_exit_mmap",
        "arch/x86/xen/mmu.c:xen_set_pgd",
        "arch/x86/xen/mmu.c:xen_set_pgd",
        "arch/x86/xen/mmu.c:xen_set_pud",
        "arch/x86/xen/mmu.c:xen_set_pmd"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_page_pinned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578984396,
      "name": "xen_page_pinned",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:158",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_page_pinned",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578987185,
      "name": "xen_page_pinned",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:158",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool xen_page_pinned(void * ptr)
```

```json
{
  "name": "xen_page_pinned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578981392,
      "name": "xen_page_pinned",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:164",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578981392,
      "name": "xen_page_pinned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
bool xen_page_pinned(void * ptr)
```

```json
{
  "name": "xen_page_pinned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578979456,
      "name": "xen_page_pinned",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:173",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578979456,
      "name": "xen_page_pinned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
bool xen_page_pinned(void * ptr)
```

```json
{
  "name": "xen_page_pinned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578987616,
      "name": "xen_page_pinned",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:173",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578987616,
      "name": "xen_page_pinned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
bool xen_page_pinned(void * ptr)
```

```json
{
  "name": "xen_page_pinned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578989984,
      "name": "xen_page_pinned",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:173",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578989984,
      "name": "xen_page_pinned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
bool xen_page_pinned(void * ptr)
```

```json
{
  "name": "xen_page_pinned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578999872,
      "name": "xen_page_pinned",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:173",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578999872,
      "name": "xen_page_pinned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
bool xen_page_pinned(void * ptr)
```

```json
{
  "name": "xen_page_pinned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579001696,
      "name": "xen_page_pinned",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:162",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579001696,
      "name": "xen_page_pinned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
bool xen_page_pinned(void * ptr)
```

```json
{
  "name": "xen_page_pinned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579009632,
      "name": "xen_page_pinned",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:162",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579009632,
      "name": "xen_page_pinned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
bool xen_page_pinned(void * ptr)
```

```json
{
  "name": "xen_page_pinned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579027648,
      "name": "xen_page_pinned",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:162",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579027648,
      "name": "xen_page_pinned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
bool xen_page_pinned(void * ptr)
```

```json
{
  "name": "xen_page_pinned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579046784,
      "name": "xen_page_pinned",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:164",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579046784,
      "name": "xen_page_pinned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
bool xen_page_pinned(void * ptr)
```

```json
{
  "name": "xen_page_pinned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579077408,
      "name": "xen_page_pinned",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:164",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579077408,
      "name": "xen_page_pinned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
bool xen_page_pinned(void * ptr)
```

```json
{
  "name": "xen_page_pinned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579077216,
      "name": "xen_page_pinned",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:180",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579077216,
      "name": "xen_page_pinned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
bool xen_page_pinned(void * ptr)
```

```json
{
  "name": "xen_page_pinned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579102752,
      "name": "xen_page_pinned",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:180",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579102752,
      "name": "xen_page_pinned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool xen_page_pinned(void * ptr)
```

```json
{
  "name": "xen_page_pinned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578990336,
      "name": "xen_page_pinned",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:173",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578990336,
      "name": "xen_page_pinned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool xen_page_pinned(void * ptr)
```

```json
{
  "name": "xen_page_pinned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578989920,
      "name": "xen_page_pinned",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:173",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578989920,
      "name": "xen_page_pinned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
bool xen_page_pinned(void * ptr)
```

```json
{
  "name": "xen_page_pinned",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578991120,
      "name": "xen_page_pinned",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:173",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578991120,
      "name": "xen_page_pinned",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
bool xen_page_pinned(void * ptr)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
bool xen_page_pinned(void * ptr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool xen_page_pinned(void * ptr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool xen_page_pinned(void * ptr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool xen_page_pinned(void * ptr)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
bool xen_page_pinned(void * ptr)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
