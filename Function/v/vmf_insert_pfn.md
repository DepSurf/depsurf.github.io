# Function: <code>vmf_insert_pfn</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn)
```

```json
{
  "name": "vmf_insert_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581222272,
      "name": "vmf_insert_pfn",
      "external": true,
      "loc": "mm/memory.c:1643",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581222272,
      "name": "vmf_insert_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
vm_fault_t vmf_insert_pfn(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn)
```

```json
{
  "name": "vmf_insert_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581295936,
      "name": "vmf_insert_pfn",
      "external": true,
      "loc": "mm/memory.c:1696",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581295936,
      "name": "vmf_insert_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
vm_fault_t vmf_insert_pfn(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn)
```

```json
{
  "name": "vmf_insert_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581354704,
      "name": "vmf_insert_pfn",
      "external": true,
      "loc": "mm/memory.c:1701",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581354704,
      "name": "vmf_insert_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
vm_fault_t vmf_insert_pfn(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn)
```

```json
{
  "name": "vmf_insert_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581543760,
      "name": "vmf_insert_pfn",
      "external": true,
      "loc": "mm/memory.c:1867",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581543760,
      "name": "vmf_insert_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
vm_fault_t vmf_insert_pfn(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn)
```

```json
{
  "name": "vmf_insert_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581586928,
      "name": "vmf_insert_pfn",
      "external": true,
      "loc": "mm/memory.c:2041",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581586928,
      "name": "vmf_insert_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
vm_fault_t vmf_insert_pfn(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn)
```

```json
{
  "name": "vmf_insert_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581608992,
      "name": "vmf_insert_pfn",
      "external": true,
      "loc": "mm/memory.c:2059",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581608992,
      "name": "vmf_insert_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
vm_fault_t vmf_insert_pfn(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn)
```

```json
{
  "name": "vmf_insert_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581884560,
      "name": "vmf_insert_pfn",
      "external": true,
      "loc": "mm/memory.c:2154",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581884560,
      "name": "vmf_insert_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
vm_fault_t vmf_insert_pfn(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn)
```

```json
{
  "name": "vmf_insert_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582275216,
      "name": "vmf_insert_pfn",
      "external": true,
      "loc": "mm/memory.c:2247",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582275216,
      "name": "vmf_insert_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
vm_fault_t vmf_insert_pfn(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn)
```

```json
{
  "name": "vmf_insert_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582767568,
      "name": "vmf_insert_pfn",
      "external": true,
      "loc": "mm/memory.c:2218",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582767568,
      "name": "vmf_insert_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
vm_fault_t vmf_insert_pfn(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn)
```

```json
{
  "name": "vmf_insert_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582983888,
      "name": "vmf_insert_pfn",
      "external": true,
      "loc": "mm/memory.c:2251",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582983888,
      "name": "vmf_insert_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
vm_fault_t vmf_insert_pfn(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn)
```

```json
{
  "name": "vmf_insert_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583159312,
      "name": "vmf_insert_pfn",
      "external": true,
      "loc": "mm/memory.c:2274",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583159312,
      "name": "vmf_insert_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
vm_fault_t vmf_insert_pfn(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn)
```

```json
{
  "name": "vmf_insert_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492758880,
      "name": "vmf_insert_pfn",
      "external": true,
      "loc": "mm/memory.c:1701",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492758880,
      "name": "vmf_insert_pfn",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn)
```

```json
{
  "name": "vmf_insert_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226574732,
      "name": "vmf_insert_pfn",
      "external": true,
      "loc": "mm/memory.c:1701",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226574732,
      "name": "vmf_insert_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
vm_fault_t vmf_insert_pfn(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn)
```

```json
{
  "name": "vmf_insert_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286122464,
      "name": "vmf_insert_pfn",
      "external": true,
      "loc": "mm/memory.c:1701",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_nvgpu_mmap_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286122464,
      "name": "vmf_insert_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
vm_fault_t vmf_insert_pfn(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn)
```

```json
{
  "name": "vmf_insert_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272739874,
      "name": "vmf_insert_pfn",
      "external": true,
      "loc": "mm/memory.c:1701",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272739874,
      "name": "vmf_insert_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
vm_fault_t vmf_insert_pfn(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn)
```

```json
{
  "name": "vmf_insert_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581323552,
      "name": "vmf_insert_pfn",
      "external": true,
      "loc": "mm/memory.c:1701",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581323552,
      "name": "vmf_insert_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
vm_fault_t vmf_insert_pfn(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn)
```

```json
{
  "name": "vmf_insert_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581267328,
      "name": "vmf_insert_pfn",
      "external": true,
      "loc": "mm/memory.c:1701",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581267328,
      "name": "vmf_insert_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
vm_fault_t vmf_insert_pfn(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn)
```

```json
{
  "name": "vmf_insert_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581314752,
      "name": "vmf_insert_pfn",
      "external": true,
      "loc": "mm/memory.c:1701",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581314752,
      "name": "vmf_insert_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
vm_fault_t vmf_insert_pfn(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn)
```

```json
{
  "name": "vmf_insert_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581378704,
      "name": "vmf_insert_pfn",
      "external": true,
      "loc": "mm/memory.c:1701",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/entry/vdso/vma.c:vvar_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581378704,
      "name": "vmf_insert_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
vm_fault_t vmf_insert_pfn(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn)
```
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
