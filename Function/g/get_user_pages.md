# Function: <code>get_user_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int get_user_pages(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, int write, int force, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "get_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580660896,
      "name": "get_user_pages",
      "external": true,
      "loc": "mm/gup.c:855",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_resolve_fault",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "mm/memory.c:__access_remote_vm",
        "mm/mempolicy.c:do_get_mempolicy",
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580660896,
      "name": "get_user_pages",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, int write, int force, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "get_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580769792,
      "name": "get_user_pages",
      "external": true,
      "loc": "mm/gup.c:978",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_resolve_fault",
        "mm/mempolicy.c:do_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580769792,
      "name": "get_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "get_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580835616,
      "name": "get_user_pages",
      "external": true,
      "loc": "mm/gup.c:982",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "mm/mempolicy.c:SYSC_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580835616,
      "name": "get_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "get_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580878208,
      "name": "get_user_pages",
      "external": true,
      "loc": "mm/gup.c:1063",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "mm/mempolicy.c:SYSC_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580878208,
      "name": "get_user_pages",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "get_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580973504,
      "name": "get_user_pages",
      "external": true,
      "loc": "mm/gup.c:1088",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "mm/gup.c:get_user_pages_longterm",
        "mm/gup.c:get_user_pages_longterm",
        "mm/mempolicy.c:SYSC_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580973504,
      "name": "get_user_pages",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "get_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581107568,
      "name": "get_user_pages",
      "external": true,
      "loc": "mm/gup.c:1094",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "mm/gup.c:get_user_pages_longterm",
        "mm/gup.c:get_user_pages_longterm",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581107568,
      "name": "get_user_pages",
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
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "get_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581187472,
      "name": "get_user_pages",
      "external": true,
      "loc": "mm/gup.c:1119",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "mm/gup.c:get_user_pages_longterm",
        "mm/gup.c:get_user_pages_longterm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581187472,
      "name": "get_user_pages",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "get_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581260480,
      "name": "get_user_pages",
      "external": true,
      "loc": "mm/gup.c:1614",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_unmap_tables",
        "arch/x86/mm/mpx.c:mpx_unmap_tables",
        "fs/io_uring.c:io_sqe_buffer_register",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581260480,
      "name": "get_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "get_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581319152,
      "name": "get_user_pages",
      "external": true,
      "loc": "mm/gup.c:1617",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_unmap_tables",
        "arch/x86/mm/mpx.c:mpx_unmap_tables",
        "fs/io_uring.c:io_sqe_buffer_register",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581319152,
      "name": "get_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "get_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581508768,
      "name": "get_user_pages",
      "external": true,
      "loc": "mm/gup.c:1977",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581508768,
      "name": "get_user_pages",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "get_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581548608,
      "name": "get_user_pages",
      "external": true,
      "loc": "mm/gup.c:1835",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581548608,
      "name": "get_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "get_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581571824,
      "name": "get_user_pages",
      "external": true,
      "loc": "mm/gup.c:1901",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581571824,
      "name": "get_user_pages",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "get_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581836432,
      "name": "get_user_pages",
      "external": true,
      "loc": "mm/gup.c:1989",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581836432,
      "name": "get_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "get_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582228144,
      "name": "get_user_pages",
      "external": true,
      "loc": "mm/gup.c:2178",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582228144,
      "name": "get_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "get_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582718768,
      "name": "get_user_pages",
      "external": true,
      "loc": "mm/gup.c:2215",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582718768,
      "name": "get_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "get_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582931648,
      "name": "get_user_pages",
      "external": true,
      "loc": "mm/gup.c:2361",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582931648,
      "name": "get_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 791
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
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "get_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583106400,
      "name": "get_user_pages",
      "external": true,
      "loc": "mm/gup.c:2379",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583106400,
      "name": "get_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 943
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
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "get_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492725184,
      "name": "get_user_pages",
      "external": true,
      "loc": "mm/gup.c:1617",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:__gfn_to_pfn_memslot",
        "fs/io_uring.c:io_sqe_buffer_register",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492725184,
      "name": "get_user_pages",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "get_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226556192,
      "name": "get_user_pages",
      "external": true,
      "loc": "mm/gup.c:1617",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sqe_buffer_register",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226556192,
      "name": "get_user_pages",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "get_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286071088,
      "name": "get_user_pages",
      "external": true,
      "loc": "mm/gup.c:1617",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_do_alloc",
        "fs/io_uring.c:io_sqe_buffer_register",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286071088,
      "name": "get_user_pages",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "get_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272717400,
      "name": "get_user_pages",
      "external": true,
      "loc": "mm/gup.c:1617",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sqe_buffer_register",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272717400,
      "name": "get_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "get_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581288000,
      "name": "get_user_pages",
      "external": true,
      "loc": "mm/gup.c:1617",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_unmap_tables",
        "arch/x86/mm/mpx.c:mpx_unmap_tables",
        "fs/io_uring.c:io_sqe_buffer_register",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581288000,
      "name": "get_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "get_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581233808,
      "name": "get_user_pages",
      "external": true,
      "loc": "mm/gup.c:1617",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_unmap_tables",
        "arch/x86/mm/mpx.c:mpx_unmap_tables",
        "fs/io_uring.c:io_sqe_buffer_register",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581233808,
      "name": "get_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "get_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581279200,
      "name": "get_user_pages",
      "external": true,
      "loc": "mm/gup.c:1617",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_unmap_tables",
        "arch/x86/mm/mpx.c:mpx_unmap_tables",
        "fs/io_uring.c:io_sqe_buffer_register",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581279200,
      "name": "get_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
long int get_user_pages(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "get_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581343120,
      "name": "get_user_pages",
      "external": true,
      "loc": "mm/gup.c:1617",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_unmap_tables",
        "arch/x86/mm/mpx.c:mpx_unmap_tables",
        "fs/io_uring.c:io_sqe_buffer_register",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581343120,
      "name": "get_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
<code>struct task_struct * tsk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct * mm</code>
</li>
<li>
<b>Param reordered. </b>
<code>tsk, mm, start, nr_pages, write, force, pages, vmas</code> ➡️ <code>start, nr_pages, write, force, pages, vmas</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int gup_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int write</code>
</li>
<li>
<b>Param removed. </b>
<code>int force</code>
</li>
<li>
<b>Param reordered. </b>
<code>start, nr_pages, write, force, pages, vmas</code> ➡️ <code>start, nr_pages, gup_flags, pages, vmas</code>
</li>
</ul>
</details>
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
<b>Param removed. </b>
<code>struct vm_area_struct * * vmas</code>
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
