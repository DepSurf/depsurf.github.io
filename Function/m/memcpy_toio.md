# Function: <code>memcpy_toio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_toio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580687993,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:223",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583487213,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:223",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583782395,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:223",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584295179,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:223",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:enable_iommus_v2",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584585754,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:223",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_write"
      ],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_toio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580801455,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:223",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583807498,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:223",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584108414,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:223",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:223",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584934110,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:223",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_write"
      ],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_toio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580865759,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:223",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583946762,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:223",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584256366,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:223",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:223",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585117502,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:223",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_write"
      ],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_toio",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:247",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:247",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:247",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584918726,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:247",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci"
      ]
    },
    {
      "addr": 0,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:247",
      "file": "drivers/misc/sram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584918726,
      "name": "memcpy_toio.constprop.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_toio",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "memcpy_toio",
      "external": false,
      "loc": "include/asm-generic/io.h:1005",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "memcpy_toio",
      "external": false,
      "loc": "include/asm-generic/io.h:1005",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "memcpy_toio",
      "external": false,
      "loc": "include/asm-generic/io.h:1005",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585340038,
      "name": "memcpy_toio",
      "external": false,
      "loc": "include/asm-generic/io.h:1005",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci"
      ]
    },
    {
      "addr": 0,
      "name": "memcpy_toio",
      "external": false,
      "loc": "include/asm-generic/io.h:1005",
      "file": "drivers/misc/sram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585340038,
      "name": "memcpy_toio.constprop.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_toio",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "memcpy_toio",
      "external": false,
      "loc": "include/asm-generic/io.h:1130",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "memcpy_toio",
      "external": false,
      "loc": "include/asm-generic/io.h:1130",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "memcpy_toio",
      "external": false,
      "loc": "include/asm-generic/io.h:1130",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "memcpy_toio",
      "external": false,
      "loc": "include/asm-generic/io.h:1130",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585578967,
      "name": "memcpy_toio",
      "external": false,
      "loc": "include/asm-generic/io.h:1130",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:enable_iommus_v2",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci"
      ]
    },
    {
      "addr": 0,
      "name": "memcpy_toio",
      "external": false,
      "loc": "include/asm-generic/io.h:1130",
      "file": "drivers/misc/sram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585580534,
      "name": "memcpy_toio.constprop.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
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
void memcpy_toio(volatile void * to, const void * from, size_t n)
```

```json
{
  "name": "memcpy_toio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584146928,
      "name": "memcpy_toio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:43",
      "file": "arch/x86/lib/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:generic_access_phys",
        "drivers/video/fbdev/core/fbmem.c:fb_write",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/iommu/amd_iommu_init.c:enable_iommus_v2",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/misc/sram.c:sram_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584146928,
      "name": "memcpy_toio",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void memcpy_toio(volatile void * to, const void * from, size_t n)
```

```json
{
  "name": "memcpy_toio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584336992,
      "name": "memcpy_toio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:43",
      "file": "arch/x86/lib/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:generic_access_phys",
        "drivers/video/fbdev/core/fbmem.c:fb_write",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/iommu/amd_iommu_init.c:enable_iommus_v2",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/misc/sram.c:sram_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584336992,
      "name": "memcpy_toio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void memcpy_toio(volatile void * to, const void * from, size_t n)
```

```json
{
  "name": "memcpy_toio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584471664,
      "name": "memcpy_toio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:43",
      "file": "arch/x86/lib/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:generic_access_phys",
        "drivers/video/fbdev/core/fbmem.c:fb_write",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/iommu/amd_iommu_init.c:enable_iommus_v2",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/misc/sram.c:sram_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584471664,
      "name": "memcpy_toio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void memcpy_toio(volatile void * to, const void * from, size_t n)
```

```json
{
  "name": "memcpy_toio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585035488,
      "name": "memcpy_toio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:43",
      "file": "arch/x86/lib/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:generic_access_phys",
        "drivers/video/fbdev/core/fbmem.c:fb_write",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/iommu/amd/init.c:enable_iommus_v2",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:iommu_init_ga_log",
        "drivers/iommu/amd/init.c:iommu_init_ga_log",
        "drivers/iommu/amd/init.c:iommu_enable_event_buffer",
        "drivers/iommu/amd/init.c:iommu_enable_command_buffer",
        "drivers/iommu/amd/init.c:iommu_set_device_table",
        "drivers/misc/sram.c:sram_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585035488,
      "name": "memcpy_toio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void memcpy_toio(volatile void * to, const void * from, size_t n)
```

```json
{
  "name": "memcpy_toio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585187552,
      "name": "memcpy_toio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:43",
      "file": "arch/x86/lib/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:generic_access_phys",
        "drivers/video/fbdev/core/fbmem.c:fb_write",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/iommu/amd/init.c:enable_iommus_v2",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:amd_iommu_init_pci",
        "drivers/iommu/amd/init.c:amd_iommu_init_pci",
        "drivers/iommu/amd/init.c:iommu_init_ga_log",
        "drivers/iommu/amd/init.c:iommu_init_ga_log",
        "drivers/iommu/amd/init.c:iommu_enable_event_buffer",
        "drivers/iommu/amd/init.c:iommu_enable_command_buffer",
        "drivers/misc/sram.c:sram_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585187552,
      "name": "memcpy_toio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void memcpy_toio(volatile void * to, const void * from, size_t n)
```

```json
{
  "name": "memcpy_toio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585069440,
      "name": "memcpy_toio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:43",
      "file": "arch/x86/lib/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:generic_access_phys",
        "drivers/video/fbdev/core/fbmem.c:fb_write",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/iommu/amd/init.c:enable_iommus_v2",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:amd_iommu_init_pci",
        "drivers/iommu/amd/init.c:amd_iommu_init_pci",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/amd/init.c:iommu_enable_event_buffer",
        "drivers/iommu/amd/init.c:iommu_enable_command_buffer",
        "drivers/misc/sram.c:sram_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585069440,
      "name": "memcpy_toio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void memcpy_toio(volatile void * to, const void * from, size_t n)
```

```json
{
  "name": "memcpy_toio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585516176,
      "name": "memcpy_toio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:43",
      "file": "arch/x86/lib/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:generic_access_phys",
        "drivers/video/fbdev/core/fbmem.c:fb_write",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/iommu/amd/init.c:enable_iommus_v2",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:amd_iommu_init_pci",
        "drivers/iommu/amd/init.c:amd_iommu_init_pci",
        "drivers/iommu/amd/init.c:iommu_enable_event_buffer",
        "drivers/iommu/amd/init.c:iommu_enable_command_buffer",
        "drivers/misc/sram.c:sram_write",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585516176,
      "name": "memcpy_toio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void memcpy_toio(volatile void * to, const void * from, size_t n)
```

```json
{
  "name": "memcpy_toio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586667936,
      "name": "memcpy_toio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:97",
      "file": "arch/x86/lib/iomem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:generic_access_phys",
        "drivers/video/fbdev/core/fbmem.c:fb_write",
        "drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/iommu/amd/init.c:enable_iommus_v2",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:amd_iommu_init_pci",
        "drivers/iommu/amd/init.c:amd_iommu_init_pci",
        "drivers/iommu/amd/init.c:iommu_enable_event_buffer",
        "drivers/iommu/amd/init.c:iommu_enable_command_buffer",
        "drivers/misc/sram.c:sram_write",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586667936,
      "name": "memcpy_toio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void memcpy_toio(volatile void * to, const void * from, size_t n)
```

```json
{
  "name": "memcpy_toio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587916528,
      "name": "memcpy_toio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:102",
      "file": "arch/x86/lib/iomem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:generic_access_phys",
        "drivers/video/fbdev/core/fbmem.c:fb_write",
        "drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/iommu/amd/init.c:enable_iommus_vapic",
        "drivers/iommu/amd/init.c:enable_iommus_vapic",
        "drivers/iommu/amd/init.c:enable_iommus_v2",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:amd_iommu_init_pci",
        "drivers/iommu/amd/init.c:amd_iommu_init_pci",
        "drivers/iommu/amd/init.c:iommu_enable_event_buffer",
        "drivers/iommu/amd/init.c:iommu_enable_command_buffer",
        "drivers/iommu/amd/init.c:iommu_set_device_table",
        "drivers/misc/sram.c:sram_write",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587916528,
      "name": "memcpy_toio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void memcpy_toio(volatile void * to, const void * from, size_t n)
```

```json
{
  "name": "memcpy_toio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588190560,
      "name": "memcpy_toio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:102",
      "file": "arch/x86/lib/iomem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:generic_access_phys",
        "drivers/video/fbdev/core/fb_io_fops.c:fb_io_write",
        "drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/iommu/amd/init.c:enable_iommus_vapic",
        "drivers/iommu/amd/init.c:enable_iommus_vapic",
        "drivers/iommu/amd/init.c:enable_iommus_v2",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:amd_iommu_init_pci",
        "drivers/iommu/amd/init.c:amd_iommu_init_pci",
        "drivers/iommu/amd/init.c:iommu_enable_event_buffer",
        "drivers/iommu/amd/init.c:iommu_enable_command_buffer",
        "drivers/iommu/amd/init.c:iommu_set_device_table",
        "drivers/misc/sram.c:sram_write",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588190560,
      "name": "memcpy_toio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void memcpy_toio(volatile void * to, const void * from, size_t n)
```

```json
{
  "name": "memcpy_toio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588482560,
      "name": "memcpy_toio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:102",
      "file": "arch/x86/lib/iomem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:generic_access_phys",
        "drivers/video/fbdev/core/fb_io_fops.c:fb_io_write",
        "drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts",
        "drivers/iommu/amd/init.c:enable_iommus_vapic",
        "drivers/iommu/amd/init.c:enable_iommus_vapic",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:early_enable_iommus",
        "drivers/iommu/amd/init.c:amd_iommu_init_pci",
        "drivers/iommu/amd/init.c:amd_iommu_init_pci",
        "drivers/iommu/amd/init.c:iommu_enable_event_buffer",
        "drivers/iommu/amd/init.c:iommu_enable_command_buffer",
        "drivers/iommu/amd/init.c:iommu_set_device_table",
        "drivers/misc/sram.c:sram_write",
        "drivers/gpu/drm/drm_cache.c:memcpy_fallback",
        "drivers/gpu/drm/drm_cache.c:memcpy_fallback",
        "drivers/gpu/drm/drm_format_helper.c:drm_fb_memcpy",
        "drivers/gpu/drm/drm_fbdev_generic.c:drm_fbdev_generic_damage_blit_real",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588482560,
      "name": "memcpy_toio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_toio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224589548,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:334",
      "file": "arch/arm/mach-omap2/control.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents",
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents",
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents",
        "arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents"
      ],
      "caller_func": []
    },
    {
      "addr": 3243353120,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:334",
      "file": "arch/arm/mach-shmobile/pm-rcar-gen2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init",
        "arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3228399412,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:334",
      "file": "fs/pstore/ram_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pstore/ram_core.c:persistent_ram_write",
        "fs/pstore/ram_core.c:persistent_ram_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3230435752,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:334",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3230845540,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:334",
      "file": "drivers/dma/ti/edma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/ti/edma.c:edma_pm_resume",
        "drivers/dma/ti/edma.c:edma_probe",
        "drivers/dma/ti/edma.c:edma_execute",
        "drivers/dma/ti/edma.c:edma_free_slot",
        "drivers/dma/ti/edma.c:edma_alloc_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 3231749984,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:334",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3232339508,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:334",
      "file": "drivers/mtd/maps/map_funcs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mtd/maps/map_funcs.c:simple_map_copy_to"
      ],
      "caller_func": []
    },
    {
      "addr": 3234036176,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:334",
      "file": "drivers/firmware/arm_scmi/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 3234352196,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:334",
      "file": "sound/core/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "sound/core/memory.c:copy_from_user_toio"
      ],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_toio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286123288,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/powerpc/include/asm/io-defs.h:60",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291230612,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/powerpc/include/asm/io-defs.h:60",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_write"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292428556,
      "name": "memcpy_toio",
      "external": false,
      "loc": "arch/powerpc/include/asm/io-defs.h:60",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_write"
      ],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_toio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276507106,
      "name": "memcpy_toio",
      "external": false,
      "loc": "include/asm-generic/io.h:1115",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_write"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void memcpy_toio(volatile void * to, const void * from, size_t n)
```

```json
{
  "name": "memcpy_toio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584440416,
      "name": "memcpy_toio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:43",
      "file": "arch/x86/lib/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:generic_access_phys",
        "drivers/video/fbdev/core/fbmem.c:fb_write",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/iommu/amd_iommu_init.c:enable_iommus_v2",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/misc/sram.c:sram_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584440416,
      "name": "memcpy_toio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void memcpy_toio(volatile void * to, const void * from, size_t n)
```

```json
{
  "name": "memcpy_toio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584376096,
      "name": "memcpy_toio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:43",
      "file": "arch/x86/lib/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:generic_access_phys",
        "drivers/video/fbdev/core/fbmem.c:fb_write",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/iommu/amd_iommu_init.c:enable_iommus_v2",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/misc/sram.c:sram_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584376096,
      "name": "memcpy_toio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void memcpy_toio(volatile void * to, const void * from, size_t n)
```

```json
{
  "name": "memcpy_toio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584423328,
      "name": "memcpy_toio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:43",
      "file": "arch/x86/lib/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:generic_access_phys",
        "drivers/video/fbdev/core/fbmem.c:fb_write",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/iommu/amd_iommu_init.c:enable_iommus_v2",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/misc/sram.c:sram_write",
        "drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584423328,
      "name": "memcpy_toio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void memcpy_toio(volatile void * to, const void * from, size_t n)
```

```json
{
  "name": "memcpy_toio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584529456,
      "name": "memcpy_toio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:43",
      "file": "arch/x86/lib/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:generic_access_phys",
        "drivers/video/fbdev/core/fbmem.c:fb_write",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/iommu/amd_iommu_init.c:enable_iommus_v2",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/misc/sram.c:sram_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584529456,
      "name": "memcpy_toio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void memcpy_toio(volatile void * to, const void * from, size_t n)
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
void memcpy_toio(volatile void * to, const void * from, size_t n)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void memcpy_toio(volatile void * to, const void * from, size_t n)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void memcpy_toio(volatile void * to, const void * from, size_t n)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void memcpy_toio(volatile void * to, const void * from, size_t n)
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
