# Function: <code>vm_area_free</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vm_area_free(struct vm_area_struct * vma)
```

```json
{
  "name": "vm_area_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579417511,
      "name": "vm_area_free",
      "external": true,
      "loc": "kernel/fork.c:336",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_mm"
      ],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417872,
      "name": "vm_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vm_area_free(struct vm_area_struct * vma)
```

```json
{
  "name": "vm_area_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579448720,
      "name": "vm_area_free",
      "external": true,
      "loc": "kernel/fork.c:355",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579448720,
      "name": "vm_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vm_area_free(struct vm_area_struct * vma)
```

```json
{
  "name": "vm_area_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579466143,
      "name": "vm_area_free",
      "external": true,
      "loc": "kernel/fork.c:361",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579466928,
      "name": "vm_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vm_area_free(struct vm_area_struct * vma)
```

```json
{
  "name": "vm_area_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579492447,
      "name": "vm_area_free",
      "external": true,
      "loc": "kernel/fork.c:370",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579493232,
      "name": "vm_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vm_area_free(struct vm_area_struct * vma)
```

```json
{
  "name": "vm_area_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579523028,
      "name": "vm_area_free",
      "external": true,
      "loc": "kernel/fork.c:374",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma",
        "fs/exec.c:__bprm_mm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579523424,
      "name": "vm_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vm_area_free(struct vm_area_struct * vma)
```

```json
{
  "name": "vm_area_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579504588,
      "name": "vm_area_free",
      "external": true,
      "loc": "kernel/fork.c:377",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma",
        "fs/exec.c:__bprm_mm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579504976,
      "name": "vm_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vm_area_free(struct vm_area_struct * vma)
```

```json
{
  "name": "vm_area_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579508035,
      "name": "vm_area_free",
      "external": true,
      "loc": "kernel/fork.c:378",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma",
        "fs/exec.c:__bprm_mm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508416,
      "name": "vm_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vm_area_free(struct vm_area_struct * vma)
```

```json
{
  "name": "vm_area_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579580699,
      "name": "vm_area_free",
      "external": true,
      "loc": "kernel/fork.c:378",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma",
        "fs/exec.c:__bprm_mm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579577504,
      "name": "vm_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void vm_area_free(struct vm_area_struct * vma)
```

```json
{
  "name": "vm_area_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579668288,
      "name": "vm_area_free",
      "external": true,
      "loc": "kernel/fork.c:489",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma",
        "fs/exec.c:alloc_bprm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579668288,
      "name": "vm_area_free",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void vm_area_free(struct vm_area_struct * vma)
```

```json
{
  "name": "vm_area_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579788288,
      "name": "vm_area_free",
      "external": true,
      "loc": "kernel/fork.c:487",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:vma_expand",
        "mm/mmap.c:remove_vma",
        "fs/exec.c:alloc_bprm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579788288,
      "name": "vm_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vm_area_free(struct vm_area_struct * vma)
```

```json
{
  "name": "vm_area_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579838954,
      "name": "vm_area_free",
      "external": true,
      "loc": "kernel/fork.c:548",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:vma_complete",
        "mm/mmap.c:vma_complete",
        "mm/mmap.c:remove_vma",
        "fs/exec.c:alloc_bprm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579835824,
      "name": "vm_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vm_area_free(struct vm_area_struct * vma)
```

```json
{
  "name": "vm_area_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579874976,
      "name": "vm_area_free",
      "external": true,
      "loc": "kernel/fork.c:528",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:vma_complete",
        "mm/mmap.c:vma_complete",
        "mm/mmap.c:remove_vma",
        "fs/exec.c:alloc_bprm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579875888,
      "name": "vm_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void vm_area_free(struct vm_area_struct * vma)
```

```json
{
  "name": "vm_area_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490626060,
      "name": "vm_area_free",
      "external": true,
      "loc": "kernel/fork.c:370",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490626816,
      "name": "vm_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void vm_area_free(struct vm_area_struct * vma)
```

```json
{
  "name": "vm_area_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224704316,
      "name": "vm_area_free",
      "external": true,
      "loc": "kernel/fork.c:370",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma",
        "fs/exec.c:__do_execve_file",
        "fs/exec.c:__do_execve_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224704908,
      "name": "vm_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void vm_area_free(struct vm_area_struct * vma)
```

```json
{
  "name": "vm_area_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283443876,
      "name": "vm_area_free",
      "external": true,
      "loc": "kernel/fork.c:370",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283444832,
      "name": "vm_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void vm_area_free(struct vm_area_struct * vma)
```

```json
{
  "name": "vm_area_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271382566,
      "name": "vm_area_free",
      "external": true,
      "loc": "kernel/fork.c:370",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma",
        "fs/exec.c:__do_execve_file",
        "fs/exec.c:__do_execve_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271383288,
      "name": "vm_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void vm_area_free(struct vm_area_struct * vma)
```

```json
{
  "name": "vm_area_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579466111,
      "name": "vm_area_free",
      "external": true,
      "loc": "kernel/fork.c:370",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579466896,
      "name": "vm_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void vm_area_free(struct vm_area_struct * vma)
```

```json
{
  "name": "vm_area_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579395071,
      "name": "vm_area_free",
      "external": true,
      "loc": "kernel/fork.c:370",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579395840,
      "name": "vm_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void vm_area_free(struct vm_area_struct * vma)
```

```json
{
  "name": "vm_area_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579466031,
      "name": "vm_area_free",
      "external": true,
      "loc": "kernel/fork.c:370",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579466816,
      "name": "vm_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void vm_area_free(struct vm_area_struct * vma)
```

```json
{
  "name": "vm_area_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579497775,
      "name": "vm_area_free",
      "external": true,
      "loc": "kernel/fork.c:370",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:remove_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579498560,
      "name": "vm_area_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void vm_area_free(struct vm_area_struct * vma)
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
