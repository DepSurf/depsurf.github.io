# Function: <code>split_vma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580705824,
      "name": "split_vma",
      "external": true,
      "loc": "mm/mmap.c:2518",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:SyS_madvise",
        "mm/madvise.c:SyS_madvise",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580705824,
      "name": "split_vma",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580819120,
      "name": "split_vma",
      "external": true,
      "loc": "mm/mmap.c:2415",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:SyS_madvise",
        "mm/madvise.c:SyS_madvise",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580819120,
      "name": "split_vma",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580884640,
      "name": "split_vma",
      "external": true,
      "loc": "mm/mmap.c:2568",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:SyS_madvise",
        "mm/madvise.c:SyS_madvise",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:SYSC_mbind",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580884640,
      "name": "split_vma",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580929568,
      "name": "split_vma",
      "external": true,
      "loc": "mm/mmap.c:2603",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:SYSC_mbind",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580929568,
      "name": "split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581029312,
      "name": "split_vma",
      "external": true,
      "loc": "mm/mmap.c:2621",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:SYSC_mbind",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581029312,
      "name": "split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581164016,
      "name": "split_vma",
      "external": true,
      "loc": "mm/mmap.c:2676",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581164016,
      "name": "split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581243920,
      "name": "split_vma",
      "external": true,
      "loc": "mm/mmap.c:2710",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581243920,
      "name": "split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581318448,
      "name": "split_vma",
      "external": true,
      "loc": "mm/mmap.c:2715",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581318448,
      "name": "split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581377568,
      "name": "split_vma",
      "external": true,
      "loc": "mm/mmap.c:2720",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581377568,
      "name": "split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581576816,
      "name": "split_vma",
      "external": true,
      "loc": "mm/mmap.c:2729",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mempolicy.c:mbind_range",
        "mm/mempolicy.c:mbind_range",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581576816,
      "name": "split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581622320,
      "name": "split_vma",
      "external": true,
      "loc": "mm/mmap.c:2792",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mempolicy.c:mbind_range",
        "mm/mempolicy.c:mbind_range",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581622320,
      "name": "split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581643664,
      "name": "split_vma",
      "external": true,
      "loc": "mm/mmap.c:2796",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mempolicy.c:mbind_range",
        "mm/mempolicy.c:mbind_range",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581643664,
      "name": "split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581911664,
      "name": "split_vma",
      "external": true,
      "loc": "mm/mmap.c:2766",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mempolicy.c:mbind_range",
        "mm/mempolicy.c:mbind_range",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581911664,
      "name": "split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582317936,
      "name": "split_vma",
      "external": true,
      "loc": "mm/mmap.c:2789",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mempolicy.c:mbind_range",
        "mm/mempolicy.c:mbind_range",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582317936,
      "name": "split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582816672,
      "name": "split_vma",
      "external": true,
      "loc": "mm/mmap.c:2267",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mempolicy.c:mbind_range",
        "mm/mempolicy.c:mbind_range",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582816672,
      "name": "split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int split_vma(struct vma_iterator * vmi, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583030784,
      "name": "split_vma",
      "external": true,
      "loc": "mm/mmap.c:2405",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:madvise_update_vma",
        "mm/madvise.c:madvise_update_vma",
        "mm/mempolicy.c:mbind_range",
        "mm/mempolicy.c:mbind_range",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583030784,
      "name": "split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "split_vma",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583211809,
      "name": "split_vma",
      "external": false,
      "loc": "mm/mmap.c:2409",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:vma_modify",
        "mm/mmap.c:vma_modify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492784456,
      "name": "split_vma",
      "external": true,
      "loc": "mm/mmap.c:2720",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492784456,
      "name": "split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226600144,
      "name": "split_vma",
      "external": true,
      "loc": "mm/mmap.c:2720",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226600144,
      "name": "split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286152640,
      "name": "split_vma",
      "external": true,
      "loc": "mm/mmap.c:2720",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286152640,
      "name": "split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272755954,
      "name": "split_vma",
      "external": true,
      "loc": "mm/mmap.c:2720",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272755954,
      "name": "split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581346416,
      "name": "split_vma",
      "external": true,
      "loc": "mm/mmap.c:2720",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581346416,
      "name": "split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581290128,
      "name": "split_vma",
      "external": true,
      "loc": "mm/mmap.c:2720",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581290128,
      "name": "split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581337616,
      "name": "split_vma",
      "external": true,
      "loc": "mm/mmap.c:2720",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581337616,
      "name": "split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581401568,
      "name": "split_vma",
      "external": true,
      "loc": "mm/mmap.c:2720",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581401568,
      "name": "split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vma_iterator * vmi</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct * mm</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int split_vma(struct vma_iterator * vmi, struct vm_area_struct * vma, long unsigned int addr, int new_below)
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
