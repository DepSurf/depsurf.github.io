# Function: <code>handle_mm_fault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int handle_mm_fault(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "handle_mm_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580675024,
      "name": "handle_mm_fault",
      "external": true,
      "loc": "mm/memory.c:3432",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:fixup_user_fault",
        "mm/ksm.c:break_ksm",
        "drivers/iommu/intel-svm.c:prq_event_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580675024,
      "name": "handle_mm_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 6173
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
int handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "handle_mm_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580789312,
      "name": "handle_mm_fault",
      "external": true,
      "loc": "mm/memory.c:3619",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/ksm.c:break_ksm",
        "drivers/iommu/intel-svm.c:prq_event_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580789312,
      "name": "handle_mm_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5048
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
int handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "handle_mm_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580853680,
      "name": "handle_mm_fault",
      "external": true,
      "loc": "mm/memory.c:3661",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/ksm.c:break_ksm",
        "drivers/iommu/intel-svm.c:prq_event_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580853680,
      "name": "handle_mm_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4950
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "handle_mm_fault",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580902976,
      "name": "handle_mm_fault",
      "external": true,
      "loc": "mm/memory.c:3914",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/ksm.c:break_ksm",
        "drivers/iommu/intel-svm.c:prq_event_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580902976,
      "name": "handle_mm_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "handle_mm_fault",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581002464,
      "name": "handle_mm_fault",
      "external": true,
      "loc": "mm/memory.c:4090",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/ksm.c:break_ksm",
        "mm/hmm.c:hmm_vma_walk_clear",
        "mm/hmm.c:hmm_vma_walk_hole",
        "drivers/iommu/intel-svm.c:prq_event_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581002464,
      "name": "handle_mm_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 485
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
int handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "handle_mm_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581139568,
      "name": "handle_mm_fault",
      "external": true,
      "loc": "mm/memory.c:4135",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/ksm.c:break_ksm",
        "mm/hmm.c:hmm_vma_walk_hole_",
        "drivers/iommu/intel-svm.c:prq_event_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139568,
      "name": "handle_mm_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
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
vm_fault_t handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "handle_mm_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581215776,
      "name": "handle_mm_fault",
      "external": true,
      "loc": "mm/memory.c:3925",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/ksm.c:break_ksm",
        "mm/hmm.c:hmm_vma_walk_hole_",
        "drivers/iommu/intel-svm.c:prq_event_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581215776,
      "name": "handle_mm_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
vm_fault_t handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "handle_mm_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "handle_mm_fault",
      "external": true,
      "loc": "mm/memory.c:3974",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/ksm.c:break_ksm",
        "mm/hmm.c:hmm_vma_walk_hole_",
        "drivers/iommu/intel-svm.c:prq_event_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581299802,
      "name": "handle_mm_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071581289152,
      "name": "handle_mm_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 483
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
vm_fault_t handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "handle_mm_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581347872,
      "name": "handle_mm_fault",
      "external": true,
      "loc": "mm/memory.c:3999",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/ksm.c:break_ksm",
        "mm/hmm.c:hmm_vma_walk_hole_",
        "drivers/iommu/intel-svm.c:prq_event_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581347872,
      "name": "handle_mm_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
vm_fault_t handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "handle_mm_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581552128,
      "name": "handle_mm_fault",
      "external": true,
      "loc": "mm/memory.c:4380",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/ksm.c:break_ksm",
        "drivers/iommu/intel/svm.c:prq_event_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581552128,
      "name": "handle_mm_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
vm_fault_t handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, struct pt_regs * regs)
```

```json
{
  "name": "handle_mm_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581595264,
      "name": "handle_mm_fault",
      "external": true,
      "loc": "mm/memory.c:4601",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/ksm.c:break_ksm",
        "drivers/iommu/intel/svm.c:prq_event_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581595264,
      "name": "handle_mm_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 681
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
vm_fault_t handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, struct pt_regs * regs)
```

```json
{
  "name": "handle_mm_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581615744,
      "name": "handle_mm_fault",
      "external": true,
      "loc": "mm/memory.c:4628",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/ksm.c:break_ksm",
        "mm/hmm.c:hmm_vma_fault",
        "drivers/iommu/intel/svm.c:prq_event_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581615744,
      "name": "handle_mm_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
vm_fault_t handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, struct pt_regs * regs)
```

```json
{
  "name": "handle_mm_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581882672,
      "name": "handle_mm_fault",
      "external": true,
      "loc": "mm/memory.c:4774",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/ksm.c:break_ksm",
        "mm/hmm.c:hmm_vma_fault",
        "drivers/iommu/io-pgfault.c:iopf_handle_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581882672,
      "name": "handle_mm_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 689
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
vm_fault_t handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, struct pt_regs * regs)
```

```json
{
  "name": "handle_mm_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582284864,
      "name": "handle_mm_fault",
      "external": true,
      "loc": "mm/memory.c:5117",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/ksm.c:break_ksm",
        "drivers/iommu/io-pgfault.c:iopf_handle_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582284864,
      "name": "handle_mm_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
vm_fault_t handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, struct pt_regs * regs)
```

```json
{
  "name": "handle_mm_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582777392,
      "name": "handle_mm_fault",
      "external": true,
      "loc": "mm/memory.c:5192",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/ksm.c:break_ksm",
        "drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582777392,
      "name": "handle_mm_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 808
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
vm_fault_t handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, struct pt_regs * regs)
```

```json
{
  "name": "handle_mm_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582993648,
      "name": "handle_mm_fault",
      "external": true,
      "loc": "mm/memory.c:5202",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/ksm.c:break_ksm",
        "drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582993648,
      "name": "handle_mm_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 863
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
vm_fault_t handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, struct pt_regs * regs)
```

```json
{
  "name": "handle_mm_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583175520,
      "name": "handle_mm_fault",
      "external": true,
      "loc": "mm/memory.c:5439",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/ksm.c:break_ksm",
        "drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583175520,
      "name": "handle_mm_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 887
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
vm_fault_t handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "handle_mm_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492753640,
      "name": "handle_mm_fault",
      "external": true,
      "loc": "mm/memory.c:3999",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/fault.c:do_page_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/ksm.c:break_ksm",
        "mm/hmm.c:hmm_vma_walk_hole_"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492753640,
      "name": "handle_mm_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
vm_fault_t handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "handle_mm_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226582028,
      "name": "handle_mm_fault",
      "external": true,
      "loc": "mm/memory.c:3999",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/fault.c:do_page_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/ksm.c:break_ksm",
        "mm/hmm.c:hmm_vma_walk_hole_"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226582028,
      "name": "handle_mm_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1004
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
vm_fault_t handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "handle_mm_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286113328,
      "name": "handle_mm_fault",
      "external": true,
      "loc": "mm/memory.c:3999",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/fault.c:__do_page_fault",
        "arch/powerpc/mm/copro_fault.c:copro_handle_mm_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/ksm.c:break_ksm",
        "mm/hmm.c:hmm_vma_walk_hole_"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286113328,
      "name": "handle_mm_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
vm_fault_t handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "handle_mm_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272734880,
      "name": "handle_mm_fault",
      "external": true,
      "loc": "mm/memory.c:3999",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/mm/fault.c:do_page_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/ksm.c:break_ksm",
        "mm/hmm.c:hmm_vma_walk_hole_"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272734880,
      "name": "handle_mm_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
vm_fault_t handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "handle_mm_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581316720,
      "name": "handle_mm_fault",
      "external": true,
      "loc": "mm/memory.c:3999",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/ksm.c:break_ksm",
        "mm/hmm.c:hmm_vma_walk_hole_",
        "drivers/iommu/intel-svm.c:prq_event_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581316720,
      "name": "handle_mm_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
vm_fault_t handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "handle_mm_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581260880,
      "name": "handle_mm_fault",
      "external": true,
      "loc": "mm/memory.c:3999",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/ksm.c:break_ksm",
        "mm/hmm.c:hmm_vma_walk_hole_",
        "drivers/iommu/intel-svm.c:prq_event_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581260880,
      "name": "handle_mm_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
vm_fault_t handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "handle_mm_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581307920,
      "name": "handle_mm_fault",
      "external": true,
      "loc": "mm/memory.c:3999",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/ksm.c:break_ksm",
        "mm/hmm.c:hmm_vma_walk_hole_",
        "drivers/iommu/intel-svm.c:prq_event_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581307920,
      "name": "handle_mm_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
vm_fault_t handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "handle_mm_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581371920,
      "name": "handle_mm_fault",
      "external": true,
      "loc": "mm/memory.c:3999",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/ksm.c:break_ksm",
        "mm/hmm.c:hmm_vma_walk_hole_",
        "drivers/iommu/intel-svm.c:prq_event_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581371920,
      "name": "handle_mm_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct mm_struct * mm</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, vma, address, flags</code> ➡️ <code>vma, address, flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pt_regs * regs</code>
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
