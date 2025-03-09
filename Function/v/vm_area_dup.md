# Function: <code>vm_area_dup</code>

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
struct vm_area_struct * vm_area_dup(struct vm_area_struct * orig)
```

```json
{
  "name": "vm_area_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579416128,
      "name": "vm_area_dup",
      "external": true,
      "loc": "kernel/fork.c:325",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_mm",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416128,
      "name": "vm_area_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct vm_area_struct * vm_area_dup(struct vm_area_struct * orig)
```

```json
{
  "name": "vm_area_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579448640,
      "name": "vm_area_dup",
      "external": true,
      "loc": "kernel/fork.c:344",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579448640,
      "name": "vm_area_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct vm_area_struct * vm_area_dup(struct vm_area_struct * orig)
```

```json
{
  "name": "vm_area_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579465296,
      "name": "vm_area_dup",
      "external": true,
      "loc": "kernel/fork.c:350",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579465296,
      "name": "vm_area_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct vm_area_struct * vm_area_dup(struct vm_area_struct * orig)
```

```json
{
  "name": "vm_area_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579491600,
      "name": "vm_area_dup",
      "external": true,
      "loc": "kernel/fork.c:359",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491600,
      "name": "vm_area_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct vm_area_struct * vm_area_dup(struct vm_area_struct * orig)
```

```json
{
  "name": "vm_area_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579521824,
      "name": "vm_area_dup",
      "external": true,
      "loc": "kernel/fork.c:362",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579521824,
      "name": "vm_area_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct vm_area_struct * vm_area_dup(struct vm_area_struct * orig)
```

```json
{
  "name": "vm_area_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579503168,
      "name": "vm_area_dup",
      "external": true,
      "loc": "kernel/fork.c:359",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579503168,
      "name": "vm_area_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct vm_area_struct * vm_area_dup(struct vm_area_struct * orig)
```

```json
{
  "name": "vm_area_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579506640,
      "name": "vm_area_dup",
      "external": true,
      "loc": "kernel/fork.c:360",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579506640,
      "name": "vm_area_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct vm_area_struct * vm_area_dup(struct vm_area_struct * orig)
```

```json
{
  "name": "vm_area_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579577344,
      "name": "vm_area_dup",
      "external": true,
      "loc": "kernel/fork.c:360",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579577344,
      "name": "vm_area_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct vm_area_struct * vm_area_dup(struct vm_area_struct * orig)
```

```json
{
  "name": "vm_area_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579667984,
      "name": "vm_area_dup",
      "external": true,
      "loc": "kernel/fork.c:470",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579667984,
      "name": "vm_area_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
struct vm_area_struct * vm_area_dup(struct vm_area_struct * orig)
```

```json
{
  "name": "vm_area_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579787984,
      "name": "vm_area_dup",
      "external": true,
      "loc": "kernel/fork.c:469",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579787984,
      "name": "vm_area_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
struct vm_area_struct * vm_area_dup(struct vm_area_struct * orig)
```

```json
{
  "name": "vm_area_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579835296,
      "name": "vm_area_dup",
      "external": true,
      "loc": "kernel/fork.c:503",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579835296,
      "name": "vm_area_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
struct vm_area_struct * vm_area_dup(struct vm_area_struct * orig)
```

```json
{
  "name": "vm_area_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579873072,
      "name": "vm_area_dup",
      "external": true,
      "loc": "kernel/fork.c:483",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579873072,
      "name": "vm_area_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
struct vm_area_struct * vm_area_dup(struct vm_area_struct * orig)
```

```json
{
  "name": "vm_area_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490625336,
      "name": "vm_area_dup",
      "external": true,
      "loc": "kernel/fork.c:359",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490625336,
      "name": "vm_area_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct vm_area_struct * vm_area_dup(struct vm_area_struct * orig)
```

```json
{
  "name": "vm_area_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224703488,
      "name": "vm_area_dup",
      "external": true,
      "loc": "kernel/fork.c:359",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224703488,
      "name": "vm_area_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct vm_area_struct * vm_area_dup(struct vm_area_struct * orig)
```

```json
{
  "name": "vm_area_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283442912,
      "name": "vm_area_dup",
      "external": true,
      "loc": "kernel/fork.c:359",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283442912,
      "name": "vm_area_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct vm_area_struct * vm_area_dup(struct vm_area_struct * orig)
```

```json
{
  "name": "vm_area_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271381856,
      "name": "vm_area_dup",
      "external": true,
      "loc": "kernel/fork.c:359",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271381856,
      "name": "vm_area_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct vm_area_struct * vm_area_dup(struct vm_area_struct * orig)
```

```json
{
  "name": "vm_area_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579465264,
      "name": "vm_area_dup",
      "external": true,
      "loc": "kernel/fork.c:359",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579465264,
      "name": "vm_area_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct vm_area_struct * vm_area_dup(struct vm_area_struct * orig)
```

```json
{
  "name": "vm_area_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579394224,
      "name": "vm_area_dup",
      "external": true,
      "loc": "kernel/fork.c:359",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394224,
      "name": "vm_area_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct vm_area_struct * vm_area_dup(struct vm_area_struct * orig)
```

```json
{
  "name": "vm_area_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579465184,
      "name": "vm_area_dup",
      "external": true,
      "loc": "kernel/fork.c:359",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579465184,
      "name": "vm_area_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct vm_area_struct * vm_area_dup(struct vm_area_struct * orig)
```

```json
{
  "name": "vm_area_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579496928,
      "name": "vm_area_dup",
      "external": true,
      "loc": "kernel/fork.c:359",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579496928,
      "name": "vm_area_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct vm_area_struct * vm_area_dup(struct vm_area_struct * orig)
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
