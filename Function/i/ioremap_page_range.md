# Function: <code>ioremap_page_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582953568,
      "name": "ioremap_page_range",
      "external": true,
      "loc": "lib/ioremap.c:123",
      "file": "lib/ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582953568,
      "name": "ioremap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 947
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
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583241184,
      "name": "ioremap_page_range",
      "external": true,
      "loc": "lib/ioremap.c:123",
      "file": "lib/ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583241184,
      "name": "ioremap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 907
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
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583356496,
      "name": "ioremap_page_range",
      "external": true,
      "loc": "lib/ioremap.c:123",
      "file": "lib/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583356496,
      "name": "ioremap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 907
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
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588205312,
      "name": "ioremap_page_range",
      "external": true,
      "loc": "lib/ioremap.c:156",
      "file": "lib/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588205312,
      "name": "ioremap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 903
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
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588754448,
      "name": "ioremap_page_range",
      "external": true,
      "loc": "lib/ioremap.c:159",
      "file": "lib/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588754448,
      "name": "ioremap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1013
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
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589132448,
      "name": "ioremap_page_range",
      "external": true,
      "loc": "lib/ioremap.c:159",
      "file": "lib/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589132448,
      "name": "ioremap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1060
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
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589367008,
      "name": "ioremap_page_range",
      "external": true,
      "loc": "lib/ioremap.c:199",
      "file": "lib/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589367008,
      "name": "ioremap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1356
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
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589825184,
      "name": "ioremap_page_range",
      "external": true,
      "loc": "lib/ioremap.c:210",
      "file": "lib/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589825184,
      "name": "ioremap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590051408,
      "name": "ioremap_page_range",
      "external": true,
      "loc": "lib/ioremap.c:210",
      "file": "lib/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590051408,
      "name": "ioremap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585045632,
      "name": "ioremap_page_range",
      "external": true,
      "loc": "lib/ioremap.c:220",
      "file": "lib/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585045632,
      "name": "ioremap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 736
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
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581696432,
      "name": "ioremap_page_range",
      "external": true,
      "loc": "mm/ioremap.c:222",
      "file": "mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581696432,
      "name": "ioremap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1585
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
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581719712,
      "name": "ioremap_page_range",
      "external": true,
      "loc": "mm/ioremap.c:31",
      "file": "mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581719712,
      "name": "ioremap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581984976,
      "name": "ioremap_page_range",
      "external": true,
      "loc": "mm/vmalloc.c:314",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581984976,
      "name": "ioremap_page_range",
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
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582407088,
      "name": "ioremap_page_range",
      "external": true,
      "loc": "mm/vmalloc.c:315",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582407088,
      "name": "ioremap_page_range",
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
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582913728,
      "name": "ioremap_page_range",
      "external": true,
      "loc": "mm/vmalloc.c:318",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582913728,
      "name": "ioremap_page_range",
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
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583130160,
      "name": "ioremap_page_range",
      "external": true,
      "loc": "mm/vmalloc.c:307",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583130160,
      "name": "ioremap_page_range",
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
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583313152,
      "name": "ioremap_page_range",
      "external": true,
      "loc": "mm/vmalloc.c:307",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583313152,
      "name": "ioremap_page_range",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503825552,
      "name": "ioremap_page_range",
      "external": true,
      "loc": "lib/ioremap.c:210",
      "file": "lib/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/ioremap.c:__ioremap_caller",
        "drivers/pci/pci.c:pci_remap_iospace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503825552,
      "name": "ioremap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1184
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
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236446824,
      "name": "ioremap_page_range",
      "external": true,
      "loc": "lib/ioremap.c:210",
      "file": "lib/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/ioremap.c:__arm_ioremap_pfn_caller",
        "arch/arm/mm/ioremap.c:ioremap_page",
        "drivers/pci/pci.c:pci_remap_iospace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236446824,
      "name": "ioremap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297672448,
      "name": "ioremap_page_range",
      "external": true,
      "loc": "lib/ioremap.c:210",
      "file": "lib/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/ioremap.c:do_ioremap",
        "arch/powerpc/mm/ioremap_64.c:__ioremap_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297672448,
      "name": "ioremap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279720102,
      "name": "ioremap_page_range",
      "external": true,
      "loc": "lib/ioremap.c:210",
      "file": "lib/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/mm/ioremap.c:ioremap",
        "drivers/pci/pci.c:pci_remap_iospace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279720102,
      "name": "ioremap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589653664,
      "name": "ioremap_page_range",
      "external": true,
      "loc": "lib/ioremap.c:210",
      "file": "lib/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589653664,
      "name": "ioremap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589379488,
      "name": "ioremap_page_range",
      "external": true,
      "loc": "lib/ioremap.c:210",
      "file": "lib/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589379488,
      "name": "ioremap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590097040,
      "name": "ioremap_page_range",
      "external": true,
      "loc": "lib/ioremap.c:210",
      "file": "lib/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590097040,
      "name": "ioremap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590147296,
      "name": "ioremap_page_range",
      "external": true,
      "loc": "lib/ioremap.c:210",
      "file": "lib/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590147296,
      "name": "ioremap_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
