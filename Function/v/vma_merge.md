# Function: <code>vma_merge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct vm_area_struct * vma_merge(struct mm_struct * mm, struct vm_area_struct * prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma * anon_vma, struct file * file, long unsigned int pgoff, struct mempolicy * policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx)
```

```json
{
  "name": "vma_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580702224,
      "name": "vma_merge",
      "external": true,
      "loc": "mm/mmap.c:1040",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:do_brk",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:copy_vma",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:SyS_madvise",
        "mm/mempolicy.c:do_mbind",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580702224,
      "name": "vma_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 809
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
struct vm_area_struct * vma_merge(struct mm_struct * mm, struct vm_area_struct * prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma * anon_vma, struct file * file, long unsigned int pgoff, struct mempolicy * policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx)
```

```json
{
  "name": "vma_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580816512,
      "name": "vma_merge",
      "external": true,
      "loc": "mm/mmap.c:942",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:do_brk",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:SyS_madvise",
        "mm/mempolicy.c:do_mbind",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580816512,
      "name": "vma_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
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
struct vm_area_struct * vma_merge(struct mm_struct * mm, struct vm_area_struct * prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma * anon_vma, struct file * file, long unsigned int pgoff, struct mempolicy * policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx)
```

```json
{
  "name": "vma_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580881984,
      "name": "vma_merge",
      "external": true,
      "loc": "mm/mmap.c:1082",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:do_brk",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:SyS_madvise",
        "mm/mempolicy.c:SYSC_mbind",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580881984,
      "name": "vma_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 843
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
struct vm_area_struct * vma_merge(struct mm_struct * mm, struct vm_area_struct * prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma * anon_vma, struct file * file, long unsigned int pgoff, struct mempolicy * policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx)
```

```json
{
  "name": "vma_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580926096,
      "name": "vma_merge",
      "external": true,
      "loc": "mm/mmap.c:1098",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:SyS_madvise",
        "mm/mempolicy.c:SYSC_mbind",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580926096,
      "name": "vma_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 955
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
struct vm_area_struct * vma_merge(struct mm_struct * mm, struct vm_area_struct * prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma * anon_vma, struct file * file, long unsigned int pgoff, struct mempolicy * policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx)
```

```json
{
  "name": "vma_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581025744,
      "name": "vma_merge",
      "external": true,
      "loc": "mm/mmap.c:1099",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:SyS_madvise",
        "mm/mempolicy.c:SYSC_mbind",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581025744,
      "name": "vma_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 955
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
struct vm_area_struct * vma_merge(struct mm_struct * mm, struct vm_area_struct * prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma * anon_vma, struct file * file, long unsigned int pgoff, struct mempolicy * policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx)
```

```json
{
  "name": "vma_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581160576,
      "name": "vma_merge",
      "external": true,
      "loc": "mm/mmap.c:1108",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise",
        "mm/mempolicy.c:kernel_mbind",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581160576,
      "name": "vma_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 845
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
struct vm_area_struct * vma_merge(struct mm_struct * mm, struct vm_area_struct * prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma * anon_vma, struct file * file, long unsigned int pgoff, struct mempolicy * policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx)
```

```json
{
  "name": "vma_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581240320,
      "name": "vma_merge",
      "external": true,
      "loc": "mm/mmap.c:1132",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise",
        "mm/mempolicy.c:kernel_mbind",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581240320,
      "name": "vma_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 969
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
struct vm_area_struct * vma_merge(struct mm_struct * mm, struct vm_area_struct * prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma * anon_vma, struct file * file, long unsigned int pgoff, struct mempolicy * policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx)
```

```json
{
  "name": "vma_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581314720,
      "name": "vma_merge",
      "external": true,
      "loc": "mm/mmap.c:1134",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:__do_sys_madvise",
        "mm/mempolicy.c:kernel_mbind",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581314720,
      "name": "vma_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 998
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
struct vm_area_struct * vma_merge(struct mm_struct * mm, struct vm_area_struct * prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma * anon_vma, struct file * file, long unsigned int pgoff, struct mempolicy * policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx)
```

```json
{
  "name": "vma_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581373856,
      "name": "vma_merge",
      "external": true,
      "loc": "mm/mmap.c:1135",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:__do_sys_madvise",
        "mm/mempolicy.c:kernel_mbind",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581373856,
      "name": "vma_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 998
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
struct vm_area_struct * vma_merge(struct mm_struct * mm, struct vm_area_struct * prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma * anon_vma, struct file * file, long unsigned int pgoff, struct mempolicy * policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx)
```

```json
{
  "name": "vma_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581572672,
      "name": "vma_merge",
      "external": true,
      "loc": "mm/mmap.c:1116",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:madvise_behavior",
        "mm/mempolicy.c:mbind_range",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581572672,
      "name": "vma_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 892
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
struct vm_area_struct * vma_merge(struct mm_struct * mm, struct vm_area_struct * prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma * anon_vma, struct file * file, long unsigned int pgoff, struct mempolicy * policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx)
```

```json
{
  "name": "vma_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581618304,
      "name": "vma_merge",
      "external": true,
      "loc": "mm/mmap.c:1157",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:madvise_behavior",
        "mm/mempolicy.c:mbind_range",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581618304,
      "name": "vma_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 845
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
struct vm_area_struct * vma_merge(struct mm_struct * mm, struct vm_area_struct * prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma * anon_vma, struct file * file, long unsigned int pgoff, struct mempolicy * policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx)
```

```json
{
  "name": "vma_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581640672,
      "name": "vma_merge",
      "external": true,
      "loc": "mm/mmap.c:1161",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:madvise_behavior",
        "mm/mempolicy.c:mbind_range",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581640672,
      "name": "vma_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 897
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
struct vm_area_struct * vma_merge(struct mm_struct * mm, struct vm_area_struct * prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma * anon_vma, struct file * file, long unsigned int pgoff, struct mempolicy * policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx)
```

```json
{
  "name": "vma_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581908480,
      "name": "vma_merge",
      "external": true,
      "loc": "mm/mmap.c:1158",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:madvise_behavior",
        "mm/mempolicy.c:mbind_range",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581908480,
      "name": "vma_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 897
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
struct vm_area_struct * vma_merge(struct mm_struct * mm, struct vm_area_struct * prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma * anon_vma, struct file * file, long unsigned int pgoff, struct mempolicy * policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx, struct anon_vma_name * anon_name)
```

```json
{
  "name": "vma_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582313552,
      "name": "vma_merge",
      "external": true,
      "loc": "mm/mmap.c:1169",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:madvise_update_vma",
        "mm/mempolicy.c:mbind_range",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582313552,
      "name": "vma_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1054
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
struct vm_area_struct * vma_merge(struct mm_struct * mm, struct vm_area_struct * prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma * anon_vma, struct file * file, long unsigned int pgoff, struct mempolicy * policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx, struct anon_vma_name * anon_name)
```

```json
{
  "name": "vma_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582810480,
      "name": "vma_merge",
      "external": true,
      "loc": "mm/mmap.c:999",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:__do_sys_mremap",
        "mm/madvise.c:madvise_update_vma",
        "mm/mempolicy.c:mbind_range",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582810480,
      "name": "vma_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 993
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
struct vm_area_struct * vma_merge(struct vma_iterator * vmi, struct mm_struct * mm, struct vm_area_struct * prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma * anon_vma, struct file * file, long unsigned int pgoff, struct mempolicy * policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx, struct anon_vma_name * anon_name)
```

```json
{
  "name": "vma_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583022464,
      "name": "vma_merge",
      "external": true,
      "loc": "mm/mmap.c:871",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:__do_sys_mremap",
        "mm/madvise.c:madvise_update_vma",
        "mm/mempolicy.c:mbind_range",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583022464,
      "name": "vma_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2489
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
struct vm_area_struct * vma_merge(struct vma_iterator * vmi, struct mm_struct * mm, struct vm_area_struct * prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma * anon_vma, struct file * file, long unsigned int pgoff, struct mempolicy * policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx, struct anon_vma_name * anon_name)
```

```json
{
  "name": "vma_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583203344,
      "name": "vma_merge",
      "external": false,
      "loc": "mm/mmap.c:864",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vma_merge_extend",
        "mm/mmap.c:vma_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583203344,
      "name": "vma_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3027
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
struct vm_area_struct * vma_merge(struct mm_struct * mm, struct vm_area_struct * prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma * anon_vma, struct file * file, long unsigned int pgoff, struct mempolicy * policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx)
```

```json
{
  "name": "vma_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492780136,
      "name": "vma_merge",
      "external": true,
      "loc": "mm/mmap.c:1135",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:__arm64_sys_madvise",
        "mm/mempolicy.c:kernel_mbind",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492780136,
      "name": "vma_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 912
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
struct vm_area_struct * vma_merge(struct mm_struct * mm, struct vm_area_struct * prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma * anon_vma, struct file * file, long unsigned int pgoff, struct mempolicy * policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx)
```

```json
{
  "name": "vma_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226596884,
      "name": "vma_merge",
      "external": true,
      "loc": "mm/mmap.c:1135",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:__se_sys_madvise",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226596884,
      "name": "vma_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 868
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
struct vm_area_struct * vma_merge(struct mm_struct * mm, struct vm_area_struct * prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma * anon_vma, struct file * file, long unsigned int pgoff, struct mempolicy * policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx)
```

```json
{
  "name": "vma_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286147952,
      "name": "vma_merge",
      "external": true,
      "loc": "mm/mmap.c:1135",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:__se_sys_madvise",
        "mm/mempolicy.c:do_mbind",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286147952,
      "name": "vma_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1320
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
struct vm_area_struct * vma_merge(struct mm_struct * mm, struct vm_area_struct * prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma * anon_vma, struct file * file, long unsigned int pgoff, struct mempolicy * policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx)
```

```json
{
  "name": "vma_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272753008,
      "name": "vma_merge",
      "external": true,
      "loc": "mm/mmap.c:1135",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:__se_sys_madvise",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272753008,
      "name": "vma_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
struct vm_area_struct * vma_merge(struct mm_struct * mm, struct vm_area_struct * prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma * anon_vma, struct file * file, long unsigned int pgoff, struct mempolicy * policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx)
```

```json
{
  "name": "vma_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581342704,
      "name": "vma_merge",
      "external": true,
      "loc": "mm/mmap.c:1135",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:__do_sys_madvise",
        "mm/mempolicy.c:kernel_mbind",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581342704,
      "name": "vma_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 998
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
struct vm_area_struct * vma_merge(struct mm_struct * mm, struct vm_area_struct * prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma * anon_vma, struct file * file, long unsigned int pgoff, struct mempolicy * policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx)
```

```json
{
  "name": "vma_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581286416,
      "name": "vma_merge",
      "external": true,
      "loc": "mm/mmap.c:1135",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:__do_sys_madvise",
        "mm/mempolicy.c:kernel_mbind",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581286416,
      "name": "vma_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 998
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
struct vm_area_struct * vma_merge(struct mm_struct * mm, struct vm_area_struct * prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma * anon_vma, struct file * file, long unsigned int pgoff, struct mempolicy * policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx)
```

```json
{
  "name": "vma_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581333904,
      "name": "vma_merge",
      "external": true,
      "loc": "mm/mmap.c:1135",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:__do_sys_madvise",
        "mm/mempolicy.c:kernel_mbind",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581333904,
      "name": "vma_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 998
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
struct vm_area_struct * vma_merge(struct mm_struct * mm, struct vm_area_struct * prev, long unsigned int addr, long unsigned int end, long unsigned int vm_flags, struct anon_vma * anon_vma, struct file * file, long unsigned int pgoff, struct mempolicy * policy, struct vm_userfaultfd_ctx vm_userfaultfd_ctx)
```

```json
{
  "name": "vma_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581397856,
      "name": "vma_merge",
      "external": true,
      "loc": "mm/mmap.c:1135",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:__do_sys_madvise",
        "mm/mempolicy.c:kernel_mbind",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581397856,
      "name": "vma_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 998
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct anon_vma_name * anon_name</code>
</li>
</ul>
</details>
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
<b>Param reordered. </b>
<code>mm, prev, addr, end, vm_flags, anon_vma, file, pgoff, policy, vm_userfaultfd_ctx, anon_name</code> ➡️ <code>vmi, mm, prev, addr, end, vm_flags, anon_vma, file, pgoff, policy, vm_userfaultfd_ctx, anon_name</code>
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
