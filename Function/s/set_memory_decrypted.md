# Function: <code>set_memory_decrypted</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int set_memory_decrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_decrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579334160,
      "name": "set_memory_decrypted",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1836",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/mm/mem_encrypt.c:swiotlb_set_mem_attributes",
        "arch/x86/mm/mem_encrypt.c:sev_alloc",
        "drivers/video/console/vgacon.c:vgacon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334160,
      "name": "set_memory_decrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int set_memory_decrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_decrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579345024,
      "name": "set_memory_decrypted",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1887",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl",
        "kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl",
        "kernel/dma/swiotlb.c:swiotlb_update_mem_attributes",
        "kernel/dma/swiotlb.c:swiotlb_update_mem_attributes",
        "drivers/video/console/vgacon.c:vgacon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579345024,
      "name": "set_memory_decrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int set_memory_decrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_decrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579371616,
      "name": "set_memory_decrypted",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:2071",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl",
        "kernel/dma/swiotlb.c:swiotlb_update_mem_attributes",
        "drivers/video/console/vgacon.c:vgacon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371616,
      "name": "set_memory_decrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int set_memory_decrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_decrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579386720,
      "name": "set_memory_decrypted",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:2082",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl",
        "kernel/dma/swiotlb.c:swiotlb_update_mem_attributes",
        "drivers/video/console/vgacon.c:vgacon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579386720,
      "name": "set_memory_decrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int set_memory_decrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_decrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579390112,
      "name": "set_memory_decrypted",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1988",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl",
        "kernel/dma/swiotlb.c:swiotlb_update_mem_attributes",
        "drivers/video/console/vgacon.c:vgacon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579390112,
      "name": "set_memory_decrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int set_memory_decrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_decrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579430112,
      "name": "set_memory_decrypted",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2024",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl",
        "kernel/dma/swiotlb.c:swiotlb_update_mem_attributes",
        "kernel/dma/pool.c:atomic_pool_expand",
        "drivers/video/console/vgacon.c:vgacon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579430112,
      "name": "set_memory_decrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int set_memory_decrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_decrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579429584,
      "name": "set_memory_decrypted",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2024",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl",
        "kernel/dma/swiotlb.c:swiotlb_update_mem_attributes",
        "kernel/dma/pool.c:atomic_pool_expand",
        "drivers/video/console/vgacon.c:vgacon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579429584,
      "name": "set_memory_decrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int set_memory_decrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_decrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579432592,
      "name": "set_memory_decrypted",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2032",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl",
        "kernel/dma/swiotlb.c:swiotlb_update_mem_attributes",
        "kernel/dma/pool.c:atomic_pool_expand",
        "drivers/video/console/vgacon.c:vgacon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432592,
      "name": "set_memory_decrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int set_memory_decrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_decrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579496784,
      "name": "set_memory_decrypted",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2032",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl",
        "kernel/dma/swiotlb.c:swiotlb_update_mem_attributes",
        "kernel/dma/pool.c:atomic_pool_expand",
        "drivers/video/console/vgacon.c:vgacon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579496784,
      "name": "set_memory_decrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int set_memory_decrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_decrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579577568,
      "name": "set_memory_decrypted",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2089",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/swiotlb.c:swiotlb_init_late",
        "kernel/dma/swiotlb.c:swiotlb_update_mem_attributes",
        "kernel/dma/pool.c:atomic_pool_expand",
        "drivers/video/console/vgacon.c:vgacon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579577568,
      "name": "set_memory_decrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int set_memory_decrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_decrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579686592,
      "name": "set_memory_decrypted",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2193",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/swiotlb.c:swiotlb_init_late",
        "kernel/dma/swiotlb.c:swiotlb_update_mem_attributes",
        "kernel/dma/pool.c:atomic_pool_expand",
        "drivers/video/console/vgacon.c:vgacon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686592,
      "name": "set_memory_decrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int set_memory_decrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_decrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579700320,
      "name": "set_memory_decrypted",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2192",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/swiotlb.c:swiotlb_init_late",
        "kernel/dma/swiotlb.c:swiotlb_update_mem_attributes",
        "kernel/dma/pool.c:atomic_pool_expand",
        "drivers/video/console/vgacon.c:vgacon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579700320,
      "name": "set_memory_decrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int set_memory_decrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_decrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579734848,
      "name": "set_memory_decrypted",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2196",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/swiotlb.c:swiotlb_alloc_pool",
        "kernel/dma/swiotlb.c:swiotlb_init_late",
        "kernel/dma/swiotlb.c:swiotlb_update_mem_attributes",
        "kernel/dma/pool.c:atomic_pool_expand",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/hv/hv_common.c:hv_common_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579734848,
      "name": "set_memory_decrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "set_memory_decrypted",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "set_memory_decrypted",
      "external": false,
      "loc": "include/linux/set_memory.h:48",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_memory_decrypted",
      "external": false,
      "loc": "include/linux/set_memory.h:48",
      "file": "kernel/dma/swiotlb.c",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "set_memory_decrypted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "set_memory_decrypted",
      "external": false,
      "loc": "include/linux/set_memory.h:48",
      "file": "kernel/dma/direct.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int set_memory_decrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_decrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283226816,
      "name": "set_memory_decrypted",
      "external": true,
      "loc": "arch/powerpc/platforms/pseries/svm.c:47",
      "file": "arch/powerpc/platforms/pseries/svm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl",
        "kernel/dma/swiotlb.c:swiotlb_update_mem_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283226816,
      "name": "set_memory_decrypted",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "set_memory_decrypted",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "set_memory_decrypted",
      "external": false,
      "loc": "include/linux/set_memory.h:48",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_memory_decrypted",
      "external": false,
      "loc": "include/linux/set_memory.h:48",
      "file": "kernel/dma/swiotlb.c",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int set_memory_decrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_decrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579386016,
      "name": "set_memory_decrypted",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1988",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl",
        "kernel/dma/swiotlb.c:swiotlb_update_mem_attributes",
        "drivers/video/console/vgacon.c:vgacon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579386016,
      "name": "set_memory_decrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int set_memory_decrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_decrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579315440,
      "name": "set_memory_decrypted",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1988",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl",
        "kernel/dma/swiotlb.c:swiotlb_update_mem_attributes",
        "drivers/video/console/vgacon.c:vgacon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579315440,
      "name": "set_memory_decrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int set_memory_decrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_decrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579385936,
      "name": "set_memory_decrypted",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1988",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl",
        "kernel/dma/swiotlb.c:swiotlb_update_mem_attributes",
        "drivers/video/console/vgacon.c:vgacon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579385936,
      "name": "set_memory_decrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int set_memory_decrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_decrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579394448,
      "name": "set_memory_decrypted",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1988",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl",
        "kernel/dma/swiotlb.c:swiotlb_update_mem_attributes",
        "drivers/video/console/vgacon.c:vgacon_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394448,
      "name": "set_memory_decrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int set_memory_decrypted(long unsigned int addr, int numpages)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int set_memory_decrypted(long unsigned int addr, int numpages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int set_memory_decrypted(long unsigned int addr, int numpages)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int set_memory_decrypted(long unsigned int addr, int numpages)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
