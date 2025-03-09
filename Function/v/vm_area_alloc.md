# Function: <code>vm_area_alloc</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct vm_area_struct * vm_area_alloc(struct mm_struct * mm)
```

```json
{
  "name": "vm_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579416048,
      "name": "vm_area_alloc",
      "external": true,
      "loc": "kernel/fork.c:316",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416048,
      "name": "vm_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct vm_area_struct * vm_area_alloc(struct mm_struct * mm)
```

```json
{
  "name": "vm_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579448544,
      "name": "vm_area_alloc",
      "external": true,
      "loc": "kernel/fork.c:334",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579448544,
      "name": "vm_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct vm_area_struct * vm_area_alloc(struct mm_struct * mm)
```

```json
{
  "name": "vm_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579465200,
      "name": "vm_area_alloc",
      "external": true,
      "loc": "kernel/fork.c:340",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579465200,
      "name": "vm_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct vm_area_struct * vm_area_alloc(struct mm_struct * mm)
```

```json
{
  "name": "vm_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579491504,
      "name": "vm_area_alloc",
      "external": true,
      "loc": "kernel/fork.c:349",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491504,
      "name": "vm_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct vm_area_struct * vm_area_alloc(struct mm_struct * mm)
```

```json
{
  "name": "vm_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579521728,
      "name": "vm_area_alloc",
      "external": true,
      "loc": "kernel/fork.c:352",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "fs/exec.c:__bprm_mm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579521728,
      "name": "vm_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct vm_area_struct * vm_area_alloc(struct mm_struct * mm)
```

```json
{
  "name": "vm_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579503072,
      "name": "vm_area_alloc",
      "external": true,
      "loc": "kernel/fork.c:349",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "fs/exec.c:__bprm_mm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579503072,
      "name": "vm_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct vm_area_struct * vm_area_alloc(struct mm_struct * mm)
```

```json
{
  "name": "vm_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579506544,
      "name": "vm_area_alloc",
      "external": true,
      "loc": "kernel/fork.c:350",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "fs/exec.c:__bprm_mm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579506544,
      "name": "vm_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct vm_area_struct * vm_area_alloc(struct mm_struct * mm)
```

```json
{
  "name": "vm_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579577248,
      "name": "vm_area_alloc",
      "external": true,
      "loc": "kernel/fork.c:350",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "fs/exec.c:__bprm_mm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579577248,
      "name": "vm_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct vm_area_struct * vm_area_alloc(struct mm_struct * mm)
```

```json
{
  "name": "vm_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579667872,
      "name": "vm_area_alloc",
      "external": true,
      "loc": "kernel/fork.c:460",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "fs/exec.c:alloc_bprm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579667872,
      "name": "vm_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct vm_area_struct * vm_area_alloc(struct mm_struct * mm)
```

```json
{
  "name": "vm_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579787872,
      "name": "vm_area_alloc",
      "external": true,
      "loc": "kernel/fork.c:459",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "fs/exec.c:alloc_bprm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579787872,
      "name": "vm_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct vm_area_struct * vm_area_alloc(struct mm_struct * mm)
```

```json
{
  "name": "vm_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579835104,
      "name": "vm_area_alloc",
      "external": true,
      "loc": "kernel/fork.c:486",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "fs/exec.c:alloc_bprm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579835104,
      "name": "vm_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
struct vm_area_struct * vm_area_alloc(struct mm_struct * mm)
```

```json
{
  "name": "vm_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872880,
      "name": "vm_area_alloc",
      "external": true,
      "loc": "kernel/fork.c:466",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "fs/exec.c:alloc_bprm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872880,
      "name": "vm_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
struct vm_area_struct * vm_area_alloc(struct mm_struct * mm)
```

```json
{
  "name": "vm_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490625192,
      "name": "vm_area_alloc",
      "external": true,
      "loc": "kernel/fork.c:349",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490625192,
      "name": "vm_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct vm_area_struct * vm_area_alloc(struct mm_struct * mm)
```

```json
{
  "name": "vm_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224703388,
      "name": "vm_area_alloc",
      "external": true,
      "loc": "kernel/fork.c:349",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "fs/exec.c:__do_execve_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224703388,
      "name": "vm_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct vm_area_struct * vm_area_alloc(struct mm_struct * mm)
```

```json
{
  "name": "vm_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283442768,
      "name": "vm_area_alloc",
      "external": true,
      "loc": "kernel/fork.c:349",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283442768,
      "name": "vm_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct vm_area_struct * vm_area_alloc(struct mm_struct * mm)
```

```json
{
  "name": "vm_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271381756,
      "name": "vm_area_alloc",
      "external": true,
      "loc": "kernel/fork.c:349",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "fs/exec.c:__do_execve_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271381756,
      "name": "vm_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct vm_area_struct * vm_area_alloc(struct mm_struct * mm)
```

```json
{
  "name": "vm_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579465168,
      "name": "vm_area_alloc",
      "external": true,
      "loc": "kernel/fork.c:349",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579465168,
      "name": "vm_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct vm_area_struct * vm_area_alloc(struct mm_struct * mm)
```

```json
{
  "name": "vm_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579394128,
      "name": "vm_area_alloc",
      "external": true,
      "loc": "kernel/fork.c:349",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394128,
      "name": "vm_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct vm_area_struct * vm_area_alloc(struct mm_struct * mm)
```

```json
{
  "name": "vm_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579465088,
      "name": "vm_area_alloc",
      "external": true,
      "loc": "kernel/fork.c:349",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579465088,
      "name": "vm_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct vm_area_struct * vm_area_alloc(struct mm_struct * mm)
```

```json
{
  "name": "vm_area_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579496832,
      "name": "vm_area_alloc",
      "external": true,
      "loc": "kernel/fork.c:349",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579496832,
      "name": "vm_area_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct vm_area_struct * vm_area_alloc(struct mm_struct * mm)
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
