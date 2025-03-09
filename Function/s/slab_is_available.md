# Function: <code>slab_is_available</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool slab_is_available()
```

```json
{
  "name": "slab_is_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580633728,
      "name": "slab_is_available",
      "external": true,
      "loc": "mm/slab_common.c:757",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:alloc_p2m_page",
        "arch/x86/xen/p2m.c:free_p2m_page",
        "mm/nobootmem.c:__alloc_bootmem_node_nopanic",
        "mm/nobootmem.c:__alloc_bootmem_low_node",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_virt_alloc_internal",
        "mm/sparse.c:sparse_index_alloc",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "drivers/base/platform.c:early_platform_driver_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580633728,
      "name": "slab_is_available",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool slab_is_available()
```

```json
{
  "name": "slab_is_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580736320,
      "name": "slab_is_available",
      "external": true,
      "loc": "mm/slab_common.c:765",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/p2m.c:alloc_p2m_page",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "mm/nobootmem.c:__alloc_bootmem_low_node",
        "mm/nobootmem.c:__alloc_bootmem_node",
        "mm/nobootmem.c:__alloc_bootmem_node_nopanic",
        "mm/memblock.c:memblock_virt_alloc_internal",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_index_alloc",
        "drivers/base/platform.c:early_platform_driver_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580736320,
      "name": "slab_is_available",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool slab_is_available()
```

```json
{
  "name": "slab_is_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580802192,
      "name": "slab_is_available",
      "external": true,
      "loc": "mm/slab_common.c:794",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/p2m.c:alloc_p2m_page",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "mm/nobootmem.c:__alloc_bootmem_low_node",
        "mm/nobootmem.c:__alloc_bootmem_node",
        "mm/nobootmem.c:__alloc_bootmem_node_nopanic",
        "mm/memblock.c:memblock_virt_alloc_internal",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_index_alloc",
        "drivers/base/platform.c:early_platform_driver_probe",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580802192,
      "name": "slab_is_available",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool slab_is_available()
```

```json
{
  "name": "slab_is_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580842400,
      "name": "slab_is_available",
      "external": true,
      "loc": "mm/slab_common.c:865",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/p2m.c:alloc_p2m_page",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "kernel/params.c:param_set_charp",
        "mm/nobootmem.c:__alloc_bootmem_low_node",
        "mm/nobootmem.c:__alloc_bootmem_node",
        "mm/nobootmem.c:__alloc_bootmem_node_nopanic",
        "mm/memblock.c:memblock_virt_alloc_internal",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_index_alloc",
        "drivers/base/platform.c:early_platform_driver_probe",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580842400,
      "name": "slab_is_available",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool slab_is_available()
```

```json
{
  "name": "slab_is_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580933088,
      "name": "slab_is_available",
      "external": true,
      "loc": "mm/slab_common.c:874",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/p2m.c:alloc_p2m_page",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "kernel/params.c:param_set_charp",
        "mm/nobootmem.c:__alloc_bootmem_low_node",
        "mm/nobootmem.c:__alloc_bootmem_node",
        "mm/nobootmem.c:__alloc_bootmem_node_nopanic",
        "mm/memblock.c:memblock_virt_alloc_internal",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_index_alloc",
        "drivers/base/platform.c:early_platform_driver_probe",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580933088,
      "name": "slab_is_available",
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
bool slab_is_available()
```

```json
{
  "name": "slab_is_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581069072,
      "name": "slab_is_available",
      "external": true,
      "loc": "mm/slab_common.c:930",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/p2m.c:alloc_p2m_page",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "kernel/params.c:param_set_charp",
        "mm/nobootmem.c:__alloc_bootmem_low_node",
        "mm/nobootmem.c:__alloc_bootmem_node",
        "mm/nobootmem.c:__alloc_bootmem_node_nopanic",
        "mm/nobootmem.c:___alloc_bootmem_nopanic",
        "mm/memblock.c:memblock_virt_alloc_internal",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_index_alloc",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "drivers/base/platform.c:early_platform_driver_probe",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069072,
      "name": "slab_is_available",
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
bool slab_is_available()
```

```json
{
  "name": "slab_is_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581146864,
      "name": "slab_is_available",
      "external": true,
      "loc": "mm/slab_common.c:957",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/p2m.c:alloc_p2m_page",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "kernel/params.c:param_set_charp",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_index_alloc",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "drivers/base/platform.c:early_platform_driver_probe",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581146864,
      "name": "slab_is_available",
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
bool slab_is_available()
```

```json
{
  "name": "slab_is_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581213632,
      "name": "slab_is_available",
      "external": true,
      "loc": "mm/slab_common.c:984",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/p2m.c:alloc_p2m_page",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "kernel/params.c:param_set_charp",
        "mm/percpu.c:pcpu_mem_zalloc",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_index_alloc",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "drivers/base/platform.c:early_platform_driver_probe",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581213632,
      "name": "slab_is_available",
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
bool slab_is_available()
```

```json
{
  "name": "slab_is_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581272288,
      "name": "slab_is_available",
      "external": true,
      "loc": "mm/slab_common.c:1035",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/p2m.c:alloc_p2m_page",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "kernel/params.c:param_set_charp",
        "mm/percpu.c:pcpu_mem_zalloc",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_index_alloc",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "security/security.c:security_add_hooks",
        "drivers/base/platform.c:early_platform_driver_probe",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581272288,
      "name": "slab_is_available",
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
bool slab_is_available()
```

```json
{
  "name": "slab_is_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581462352,
      "name": "slab_is_available",
      "external": true,
      "loc": "mm/slab_common.c:1035",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/p2m.c:alloc_p2m_page",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "kernel/params.c:param_set_charp",
        "mm/percpu.c:pcpu_mem_zalloc",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_index_alloc",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "security/security.c:security_add_hooks",
        "drivers/firmware/efi/memmap.c:__efi_memmap_free",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581462352,
      "name": "slab_is_available",
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
bool slab_is_available()
```

```json
{
  "name": "slab_is_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581502400,
      "name": "slab_is_available",
      "external": true,
      "loc": "mm/slab_common.c:535",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/p2m.c:alloc_p2m_page",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "kernel/params.c:param_set_charp",
        "mm/percpu.c:pcpu_mem_zalloc",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_index_alloc",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "security/security.c:security_add_hooks",
        "drivers/firmware/efi/memmap.c:__efi_memmap_free",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581502400,
      "name": "slab_is_available",
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
bool slab_is_available()
```

```json
{
  "name": "slab_is_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581524592,
      "name": "slab_is_available",
      "external": true,
      "loc": "mm/slab_common.c:541",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/p2m.c:alloc_p2m_page",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "kernel/params.c:param_set_charp",
        "mm/percpu.c:pcpu_mem_zalloc",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_index_alloc",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "security/security.c:security_add_hooks",
        "drivers/firmware/efi/memmap.c:__efi_memmap_free",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581524592,
      "name": "slab_is_available",
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
bool slab_is_available()
```

```json
{
  "name": "slab_is_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581786400,
      "name": "slab_is_available",
      "external": true,
      "loc": "mm/slab_common.c:545",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/p2m.c:alloc_p2m_page",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "kernel/params.c:param_set_charp",
        "mm/percpu.c:pcpu_mem_zalloc",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_index_alloc",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "security/security.c:security_add_hooks",
        "drivers/firmware/efi/memmap.c:__efi_memmap_free",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581786400,
      "name": "slab_is_available",
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
bool slab_is_available()
```

```json
{
  "name": "slab_is_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582171600,
      "name": "slab_is_available",
      "external": true,
      "loc": "mm/slab_common.c:536",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/p2m.c:alloc_p2m_page",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "kernel/params.c:param_set_charp",
        "mm/percpu.c:pcpu_mem_zalloc",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_index_alloc",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "security/security.c:security_add_hooks",
        "drivers/firmware/efi/memmap.c:__efi_memmap_free",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582171600,
      "name": "slab_is_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool slab_is_available()
```

```json
{
  "name": "slab_is_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582653664,
      "name": "slab_is_available",
      "external": true,
      "loc": "mm/slab_common.c:525",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/p2m.c:alloc_p2m_page",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/platform/efi/memmap.c:__efi_memmap_free",
        "arch/x86/platform/efi/memmap.c:efi_memmap_alloc",
        "kernel/params.c:param_set_charp",
        "mm/percpu.c:pcpu_mem_zalloc",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_index_alloc",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "security/security.c:security_add_hooks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582653664,
      "name": "slab_is_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool slab_is_available()
```

```json
{
  "name": "slab_is_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582863568,
      "name": "slab_is_available",
      "external": true,
      "loc": "mm/slab_common.c:525",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/p2m.c:alloc_p2m_page",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/platform/efi/memmap.c:__efi_memmap_free",
        "arch/x86/platform/efi/memmap.c:efi_memmap_alloc",
        "kernel/params.c:param_set_charp",
        "mm/percpu.c:pcpu_mem_zalloc",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_index_alloc",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "security/security.c:security_add_hooks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582863568,
      "name": "slab_is_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool slab_is_available()
```

```json
{
  "name": "slab_is_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583036672,
      "name": "slab_is_available",
      "external": true,
      "loc": "mm/slab_common.c:520",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/p2m.c:alloc_p2m_page",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/platform/efi/memmap.c:__efi_memmap_free",
        "arch/x86/platform/efi/memmap.c:efi_memmap_alloc",
        "kernel/params.c:param_set_charp",
        "mm/percpu.c:pcpu_mem_zalloc",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_index_alloc",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "security/security.c:security_add_hooks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583036672,
      "name": "slab_is_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool slab_is_available()
```

```json
{
  "name": "slab_is_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492677576,
      "name": "slab_is_available",
      "external": true,
      "loc": "mm/slab_common.c:1035",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_charp",
        "mm/percpu.c:pcpu_mem_zalloc",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_index_alloc",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "security/security.c:security_add_hooks",
        "drivers/base/platform.c:early_platform_driver_probe",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492677576,
      "name": "slab_is_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool slab_is_available()
```

```json
{
  "name": "slab_is_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226516164,
      "name": "slab_is_available",
      "external": true,
      "loc": "mm/slab_common.c:1035",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_charp",
        "mm/percpu.c:pcpu_mem_zalloc",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memblock.c:memblock_double_array",
        "security/security.c:security_add_hooks",
        "drivers/base/platform.c:early_platform_driver_probe",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226516164,
      "name": "slab_is_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
bool slab_is_available()
```

```json
{
  "name": "slab_is_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286003776,
      "name": "slab_is_available",
      "external": true,
      "loc": "mm/slab_common.c:1035",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/rtas.c:rtas_call",
        "arch/powerpc/kernel/rtas.c:__fetch_rtas_last_error",
        "arch/powerpc/kernel/pci-common.c:pcibios_alloc_controller",
        "arch/powerpc/mm/ioremap_64.c:__ioremap_caller",
        "arch/powerpc/mm/ioremap_64.c:__ioremap_at",
        "arch/powerpc/mm/book3s64/hash_pgtable.c:hash__map_kernel_page",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page",
        "arch/powerpc/lib/alloc.c:zalloc_maybe_bootmem",
        "arch/powerpc/sysdev/msi_bitmap.c:msi_bitmap_alloc",
        "kernel/params.c:param_set_charp",
        "mm/percpu.c:pcpu_mem_zalloc",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_index_alloc",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "security/security.c:security_add_hooks",
        "drivers/base/platform.c:early_platform_driver_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286003776,
      "name": "slab_is_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
bool slab_is_available()
```

```json
{
  "name": "slab_is_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272684282,
      "name": "slab_is_available",
      "external": true,
      "loc": "mm/slab_common.c:1035",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_mem_zalloc",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_index_alloc",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "security/security.c:security_add_hooks",
        "drivers/base/platform.c:early_platform_driver_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272684282,
      "name": "slab_is_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool slab_is_available()
```

```json
{
  "name": "slab_is_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581241136,
      "name": "slab_is_available",
      "external": true,
      "loc": "mm/slab_common.c:1035",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/p2m.c:alloc_p2m_page",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "kernel/params.c:param_set_charp",
        "mm/percpu.c:pcpu_mem_zalloc",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_index_alloc",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "security/security.c:security_add_hooks",
        "drivers/base/platform.c:early_platform_driver_probe",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581241136,
      "name": "slab_is_available",
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
bool slab_is_available()
```

```json
{
  "name": "slab_is_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581187808,
      "name": "slab_is_available",
      "external": true,
      "loc": "mm/slab_common.c:1035",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:reserve_real_mode",
        "kernel/params.c:param_set_charp",
        "mm/percpu.c:pcpu_mem_zalloc",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_index_alloc",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "security/security.c:security_add_hooks",
        "drivers/base/platform.c:early_platform_driver_probe",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581187808,
      "name": "slab_is_available",
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
bool slab_is_available()
```

```json
{
  "name": "slab_is_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581232336,
      "name": "slab_is_available",
      "external": true,
      "loc": "mm/slab_common.c:1035",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/p2m.c:alloc_p2m_page",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "kernel/params.c:param_set_charp",
        "mm/percpu.c:pcpu_mem_zalloc",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_index_alloc",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "security/security.c:security_add_hooks",
        "drivers/base/platform.c:early_platform_driver_probe",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581232336,
      "name": "slab_is_available",
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
bool slab_is_available()
```

```json
{
  "name": "slab_is_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581295872,
      "name": "slab_is_available",
      "external": true,
      "loc": "mm/slab_common.c:1035",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/p2m.c:alloc_p2m_page",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "kernel/params.c:param_set_charp",
        "mm/percpu.c:pcpu_mem_zalloc",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_index_alloc",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "security/security.c:security_add_hooks",
        "drivers/base/platform.c:early_platform_driver_probe",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581295872,
      "name": "slab_is_available",
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
