# Function: <code>__do_munmap</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf, bool downgrade)
```

```json
{
  "name": "__do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581243968,
      "name": "__do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2724",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581243968,
      "name": "__do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1122
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
int __do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf, bool downgrade)
```

```json
{
  "name": "__do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581318496,
      "name": "__do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2729",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581318496,
      "name": "__do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1098
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
int __do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf, bool downgrade)
```

```json
{
  "name": "__do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581377616,
      "name": "__do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2734",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581377616,
      "name": "__do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1202
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
int __do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf, bool downgrade)
```

```json
{
  "name": "__do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581576864,
      "name": "__do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2743",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__do_sys_brk",
        "mm/mremap.c:__do_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581576864,
      "name": "__do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1269
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
int __do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf, bool downgrade)
```

```json
{
  "name": "__do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581622368,
      "name": "__do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2806",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__do_sys_brk",
        "mm/mremap.c:__do_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581622368,
      "name": "__do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1303
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
int __do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf, bool downgrade)
```

```json
{
  "name": "__do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581643712,
      "name": "__do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2810",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__do_sys_brk",
        "mm/mremap.c:__do_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581643712,
      "name": "__do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1239
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
int __do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf, bool downgrade)
```

```json
{
  "name": "__do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581911712,
      "name": "__do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2796",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__do_sys_brk",
        "mm/mremap.c:__do_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581911712,
      "name": "__do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1272
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
int __do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf, bool downgrade)
```

```json
{
  "name": "__do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582318000,
      "name": "__do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2803",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__do_sys_brk",
        "mm/mremap.c:__do_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582318000,
      "name": "__do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1359
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf, bool downgrade)
```

```json
{
  "name": "__do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492784560,
      "name": "__do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2734",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__arm64_sys_brk",
        "mm/mremap.c:__arm64_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492784560,
      "name": "__do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1100
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
int __do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf, bool downgrade)
```

```json
{
  "name": "__do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226600204,
      "name": "__do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2734",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__se_sys_brk",
        "mm/mremap.c:__se_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226600204,
      "name": "__do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1084
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
int __do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf, bool downgrade)
```

```json
{
  "name": "__do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286152704,
      "name": "__do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2734",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__se_sys_brk",
        "mm/mremap.c:__se_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286152704,
      "name": "__do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1492
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
int __do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf, bool downgrade)
```

```json
{
  "name": "__do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272756038,
      "name": "__do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2734",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__se_sys_brk",
        "mm/mremap.c:__se_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272756038,
      "name": "__do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 804
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
int __do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf, bool downgrade)
```

```json
{
  "name": "__do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581346464,
      "name": "__do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2734",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581346464,
      "name": "__do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1202
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
int __do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf, bool downgrade)
```

```json
{
  "name": "__do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581290176,
      "name": "__do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2734",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581290176,
      "name": "__do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1202
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
int __do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf, bool downgrade)
```

```json
{
  "name": "__do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581337664,
      "name": "__do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2734",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581337664,
      "name": "__do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1202
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
int __do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf, bool downgrade)
```

```json
{
  "name": "__do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581401616,
      "name": "__do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2734",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581401616,
      "name": "__do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1202
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int __do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf, bool downgrade)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int __do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf, bool downgrade)
```
</details>
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
