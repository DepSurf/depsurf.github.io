# Function: <code>vma_kernel_pagesize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_kernel_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580789920,
      "name": "vma_kernel_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:633",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:vma_mmu_pagesize"
      ],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smap",
        "fs/proc/task_mmu.c:show_numa_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580789920,
      "name": "vma_kernel_pagesize",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_kernel_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580919397,
      "name": "vma_kernel_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:636",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:vma_mmu_pagesize"
      ],
      "caller_func": [
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580913168,
      "name": "vma_kernel_pagesize",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_kernel_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580987541,
      "name": "vma_kernel_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:636",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:vma_mmu_pagesize"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580981760,
      "name": "vma_kernel_pagesize",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_kernel_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581045289,
      "name": "vma_kernel_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:638",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": [
        "mm/hugetlb.c:huge_pmd_share",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581027280,
      "name": "vma_kernel_pagesize.part.39",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071581027344,
      "name": "vma_kernel_pagesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_kernel_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581155806,
      "name": "vma_kernel_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:639",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": [
        "mm/hugetlb.c:huge_pmd_share",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136736,
      "name": "vma_kernel_pagesize.part.47",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071581136800,
      "name": "vma_kernel_pagesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_kernel_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581286309,
      "name": "vma_kernel_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:638",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:vma_mmu_pagesize"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581275776,
      "name": "vma_kernel_pagesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
long unsigned int vma_kernel_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_kernel_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581369221,
      "name": "vma_kernel_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:638",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:vma_mmu_pagesize"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581358720,
      "name": "vma_kernel_pagesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
long unsigned int vma_kernel_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_kernel_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581480549,
      "name": "vma_kernel_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:640",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:vma_mmu_pagesize"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581469424,
      "name": "vma_kernel_pagesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
long unsigned int vma_kernel_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_kernel_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581544965,
      "name": "vma_kernel_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:641",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:vma_mmu_pagesize"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581533440,
      "name": "vma_kernel_pagesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
long unsigned int vma_kernel_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_kernel_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581754325,
      "name": "vma_kernel_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:780",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:vma_mmu_pagesize"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581741408,
      "name": "vma_kernel_pagesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
long unsigned int vma_kernel_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_kernel_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581802437,
      "name": "vma_kernel_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:810",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:vma_mmu_pagesize"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581789872,
      "name": "vma_kernel_pagesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
long unsigned int vma_kernel_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_kernel_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581829429,
      "name": "vma_kernel_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:817",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:vma_mmu_pagesize"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581817552,
      "name": "vma_kernel_pagesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
long unsigned int vma_kernel_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_kernel_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582116933,
      "name": "vma_kernel_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:819",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:vma_mmu_pagesize"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582103808,
      "name": "vma_kernel_pagesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_kernel_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582561333,
      "name": "vma_kernel_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:836",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:vma_mmu_pagesize"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582544160,
      "name": "vma_kernel_pagesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_kernel_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583075077,
      "name": "vma_kernel_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:980",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:vma_mmu_pagesize"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583060176,
      "name": "vma_kernel_pagesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
long unsigned int vma_kernel_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_kernel_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583285621,
      "name": "vma_kernel_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:974",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:vma_mmu_pagesize"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583270736,
      "name": "vma_kernel_pagesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
long unsigned int vma_kernel_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_kernel_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583525061,
      "name": "vma_kernel_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:1005",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:vma_mmu_pagesize"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583506656,
      "name": "vma_kernel_pagesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
long unsigned int vma_kernel_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_kernel_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492978072,
      "name": "vma_kernel_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:641",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:vma_mmu_pagesize"
      ],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_host_page_size",
        "virt/kvm/arm/mmu.c:user_mem_abort",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492963352,
      "name": "vma_kernel_pagesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "vma_kernel_pagesize",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "vma_kernel_pagesize",
      "external": false,
      "loc": "include/linux/hugetlb.h:659",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "vma_kernel_pagesize",
      "external": false,
      "loc": "include/linux/hugetlb.h:659",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_kernel_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286397920,
      "name": "vma_kernel_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:641",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:vma_mmu_pagesize"
      ],
      "caller_func": [
        "arch/powerpc/mm/hugetlbpage.c:vma_mmu_pagesize",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286378816,
      "name": "vma_kernel_pagesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
long unsigned int vma_kernel_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_kernel_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272884092,
      "name": "vma_kernel_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:641",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:vma_mmu_pagesize"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272874534,
      "name": "vma_kernel_pagesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
long unsigned int vma_kernel_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_kernel_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581513701,
      "name": "vma_kernel_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:641",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:vma_mmu_pagesize"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581502176,
      "name": "vma_kernel_pagesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
long unsigned int vma_kernel_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_kernel_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581455893,
      "name": "vma_kernel_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:641",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:vma_mmu_pagesize"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581444400,
      "name": "vma_kernel_pagesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
long unsigned int vma_kernel_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_kernel_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581505013,
      "name": "vma_kernel_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:641",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:vma_mmu_pagesize"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581493488,
      "name": "vma_kernel_pagesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
long unsigned int vma_kernel_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_kernel_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581570005,
      "name": "vma_kernel_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:641",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:vma_mmu_pagesize"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/proc/task_mmu.c:show_numa_map",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581558496,
      "name": "vma_kernel_pagesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct * vma)
```
</details>
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
