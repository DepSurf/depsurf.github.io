# Function: <code>ioremap_encrypted</code>

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
void * ioremap_encrypted(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579357392,
      "name": "ioremap_encrypted",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:366",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579357392,
      "name": "ioremap_encrypted",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void * ioremap_encrypted(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579371552,
      "name": "ioremap_encrypted",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:386",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371552,
      "name": "ioremap_encrypted",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void * ioremap_encrypted(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579376160,
      "name": "ioremap_encrypted",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:408",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579376160,
      "name": "ioremap_encrypted",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void * ioremap_encrypted(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579404752,
      "name": "ioremap_encrypted",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:408",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:copy_device_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579404752,
      "name": "ioremap_encrypted",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void * ioremap_encrypted(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579405328,
      "name": "ioremap_encrypted",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:408",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev-es.c:sev_es_setup_ap_jump_table",
        "drivers/iommu/amd/init.c:copy_device_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579405328,
      "name": "ioremap_encrypted",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void * ioremap_encrypted(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579408560,
      "name": "ioremap_encrypted",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:410",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table",
        "drivers/iommu/amd/init.c:copy_device_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579408560,
      "name": "ioremap_encrypted",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void * ioremap_encrypted(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579471184,
      "name": "ioremap_encrypted",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:410",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table",
        "drivers/iommu/amd/init.c:copy_device_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579471184,
      "name": "ioremap_encrypted",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void * ioremap_encrypted(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579548496,
      "name": "ioremap_encrypted",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:415",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page",
        "arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table",
        "arch/x86/kernel/sev.c:get_jump_table_addr",
        "drivers/iommu/amd/init.c:copy_device_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579548496,
      "name": "ioremap_encrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void * ioremap_encrypted(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579653520,
      "name": "ioremap_encrypted",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:422",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page",
        "arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table",
        "arch/x86/kernel/sev.c:get_jump_table_addr",
        "drivers/iommu/amd/init.c:__copy_device_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653520,
      "name": "ioremap_encrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void * ioremap_encrypted(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579667744,
      "name": "ioremap_encrypted",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:427",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page",
        "arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table",
        "arch/x86/kernel/sev.c:get_jump_table_addr",
        "drivers/iommu/amd/init.c:__copy_device_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579667744,
      "name": "ioremap_encrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void * ioremap_encrypted(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579702304,
      "name": "ioremap_encrypted",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:427",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page",
        "arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table",
        "arch/x86/kernel/sev.c:get_jump_table_addr",
        "drivers/iommu/amd/init.c:__copy_device_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702304,
      "name": "ioremap_encrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * ioremap_encrypted(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579372064,
      "name": "ioremap_encrypted",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:408",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579372064,
      "name": "ioremap_encrypted",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void * ioremap_encrypted(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579302256,
      "name": "ioremap_encrypted",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:408",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579302256,
      "name": "ioremap_encrypted",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void * ioremap_encrypted(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579371984,
      "name": "ioremap_encrypted",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:408",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371984,
      "name": "ioremap_encrypted",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void * ioremap_encrypted(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_encrypted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579380464,
      "name": "ioremap_encrypted",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:408",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579380464,
      "name": "ioremap_encrypted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * ioremap_encrypted(resource_size_t phys_addr, long unsigned int size)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void * ioremap_encrypted(resource_size_t phys_addr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void * ioremap_encrypted(resource_size_t phys_addr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void * ioremap_encrypted(resource_size_t phys_addr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void * ioremap_encrypted(resource_size_t phys_addr, long unsigned int size)
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
