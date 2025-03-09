# Function: <code>set_memory_encrypted</code>

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
int set_memory_encrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579334128,
      "name": "set_memory_encrypted",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1830",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/mm/mem_encrypt.c:sev_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334128,
      "name": "set_memory_encrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int set_memory_encrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579344992,
      "name": "set_memory_encrypted",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1881",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "kernel/dma/direct.c:dma_direct_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579344992,
      "name": "set_memory_encrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int set_memory_encrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579371584,
      "name": "set_memory_encrypted",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:2065",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem",
        "kernel/dma/direct.c:dma_direct_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371584,
      "name": "set_memory_encrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int set_memory_encrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579386688,
      "name": "set_memory_encrypted",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:2076",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem",
        "kernel/dma/direct.c:dma_direct_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579386688,
      "name": "set_memory_encrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int set_memory_encrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579390080,
      "name": "set_memory_encrypted",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1982",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem",
        "kernel/dma/direct.c:dma_direct_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579390080,
      "name": "set_memory_encrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int set_memory_encrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579430080,
      "name": "set_memory_encrypted",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2018",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/pool.c:atomic_pool_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579430080,
      "name": "set_memory_encrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int set_memory_encrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579429552,
      "name": "set_memory_encrypted",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2018",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/pool.c:atomic_pool_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579429552,
      "name": "set_memory_encrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int set_memory_encrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579432560,
      "name": "set_memory_encrypted",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2026",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/pool.c:atomic_pool_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432560,
      "name": "set_memory_encrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int set_memory_encrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579496752,
      "name": "set_memory_encrypted",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2026",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/swiotlb.c:swiotlb_exit",
        "kernel/dma/pool.c:atomic_pool_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579496752,
      "name": "set_memory_encrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int set_memory_encrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579577440,
      "name": "set_memory_encrypted",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2083",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/mm/mem_encrypt_amd.c:mem_encrypt_free_decrypted_mem",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/swiotlb.c:swiotlb_exit",
        "kernel/dma/pool.c:atomic_pool_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579577440,
      "name": "set_memory_encrypted",
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
int set_memory_encrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579686448,
      "name": "set_memory_encrypted",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2187",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/mm/mem_encrypt_amd.c:mem_encrypt_free_decrypted_mem",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/swiotlb.c:swiotlb_exit",
        "kernel/dma/pool.c:atomic_pool_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686448,
      "name": "set_memory_encrypted",
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
int set_memory_encrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579700416,
      "name": "set_memory_encrypted",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2186",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/mm/mem_encrypt_amd.c:mem_encrypt_free_decrypted_mem",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/swiotlb.c:swiotlb_exit",
        "kernel/dma/pool.c:atomic_pool_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579700416,
      "name": "set_memory_encrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int set_memory_encrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579734944,
      "name": "set_memory_encrypted",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2190",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/mm/mem_encrypt_amd.c:mem_encrypt_free_decrypted_mem",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/swiotlb.c:swiotlb_alloc_pool",
        "kernel/dma/swiotlb.c:swiotlb_exit",
        "kernel/dma/pool.c:atomic_pool_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579734944,
      "name": "set_memory_encrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
  "name": "set_memory_encrypted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "set_memory_encrypted",
      "external": false,
      "loc": "include/linux/set_memory.h:43",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "set_memory_encrypted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "set_memory_encrypted",
      "external": false,
      "loc": "include/linux/set_memory.h:43",
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
int set_memory_encrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283226720,
      "name": "set_memory_encrypted",
      "external": true,
      "loc": "arch/powerpc/platforms/pseries/svm.c:37",
      "file": "arch/powerpc/platforms/pseries/svm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283226720,
      "name": "set_memory_encrypted",
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
  "name": "set_memory_encrypted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "set_memory_encrypted",
      "external": false,
      "loc": "include/linux/set_memory.h:43",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int set_memory_encrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579385984,
      "name": "set_memory_encrypted",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1982",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem",
        "kernel/dma/direct.c:dma_direct_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579385984,
      "name": "set_memory_encrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int set_memory_encrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579315408,
      "name": "set_memory_encrypted",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1982",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem",
        "kernel/dma/direct.c:dma_direct_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579315408,
      "name": "set_memory_encrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int set_memory_encrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579385904,
      "name": "set_memory_encrypted",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1982",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem",
        "kernel/dma/direct.c:dma_direct_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579385904,
      "name": "set_memory_encrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int set_memory_encrypted(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579394416,
      "name": "set_memory_encrypted",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1982",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem",
        "kernel/dma/direct.c:dma_direct_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394416,
      "name": "set_memory_encrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int set_memory_encrypted(long unsigned int addr, int numpages)
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
int set_memory_encrypted(long unsigned int addr, int numpages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int set_memory_encrypted(long unsigned int addr, int numpages)
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
int set_memory_encrypted(long unsigned int addr, int numpages)
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
