# Function: <code>pat_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool pat_enabled()
```

```json
{
  "name": "pat_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579302160,
      "name": "pat_enabled",
      "external": true,
      "loc": "arch/x86/mm/pat.c:56",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:track_pfn_remap"
      ],
      "caller_func": [
        "arch/x86/pci/i386.c:pci_mmap_page_range",
        "arch/x86/pci/i386.c:pci_mmap_page_range",
        "arch/x86/pci/i386.c:pci_mmap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579302160,
      "name": "pat_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool pat_enabled()
```

```json
{
  "name": "pat_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579305826,
      "name": "pat_enabled",
      "external": true,
      "loc": "arch/x86/mm/pat.c:67",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:track_pfn_remap"
      ],
      "caller_func": [
        "arch/x86/pci/i386.c:pci_mmap_page_range",
        "arch/x86/pci/i386.c:pci_mmap_page_range",
        "arch/x86/pci/i386.c:pci_mmap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579301392,
      "name": "pat_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool pat_enabled()
```

```json
{
  "name": "pat_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579321330,
      "name": "pat_enabled",
      "external": true,
      "loc": "arch/x86/mm/pat.c:67",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:track_pfn_remap"
      ],
      "caller_func": [
        "arch/x86/pci/i386.c:pci_mmap_page_range",
        "arch/x86/pci/i386.c:pci_mmap_page_range",
        "arch/x86/pci/i386.c:pci_mmap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579316800,
      "name": "pat_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool pat_enabled()
```

```json
{
  "name": "pat_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579314240,
      "name": "pat_enabled",
      "external": true,
      "loc": "arch/x86/mm/pat.c:66",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579314240,
      "name": "pat_enabled",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool pat_enabled()
```

```json
{
  "name": "pat_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579337120,
      "name": "pat_enabled",
      "external": true,
      "loc": "arch/x86/mm/pat.c:66",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579337120,
      "name": "pat_enabled",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool pat_enabled()
```

```json
{
  "name": "pat_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602887636,
      "name": "pat_enabled",
      "external": true,
      "loc": "arch/x86/mm/pat.c:66",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_memtype_list_init",
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:track_pfn_insert",
        "arch/x86/mm/pat.c:track_pfn_remap",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat.c:io_reserve_memtype",
        "arch/x86/mm/pat.c:reserve_memtype"
      ],
      "caller_func": [
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579348224,
      "name": "pat_enabled",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool pat_enabled()
```

```json
{
  "name": "pat_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604685048,
      "name": "pat_enabled",
      "external": true,
      "loc": "arch/x86/mm/pat.c:66",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_memtype_list_init",
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:track_pfn_insert",
        "arch/x86/mm/pat.c:track_pfn_remap",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat.c:io_reserve_memtype",
        "arch/x86/mm/pat.c:reserve_memtype"
      ],
      "caller_func": [
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579375168,
      "name": "pat_enabled",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool pat_enabled()
```

```json
{
  "name": "pat_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604784591,
      "name": "pat_enabled",
      "external": true,
      "loc": "arch/x86/mm/pat.c:67",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_memtype_list_init",
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:track_pfn_insert",
        "arch/x86/mm/pat.c:track_pfn_remap",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat.c:io_reserve_memtype",
        "arch/x86/mm/pat.c:reserve_memtype"
      ],
      "caller_func": [
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579390688,
      "name": "pat_enabled",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool pat_enabled()
```

```json
{
  "name": "pat_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604810340,
      "name": "pat_enabled",
      "external": true,
      "loc": "arch/x86/mm/pat.c:67",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_memtype_list_init",
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:track_pfn_insert",
        "arch/x86/mm/pat.c:track_pfn_remap",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat.c:io_reserve_memtype",
        "arch/x86/mm/pat.c:reserve_memtype"
      ],
      "caller_func": [
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394000,
      "name": "pat_enabled",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool pat_enabled()
```

```json
{
  "name": "pat_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609150029,
      "name": "pat_enabled",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:93",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_memtype_list_init",
        "arch/x86/mm/pat/memtype.c:untrack_pfn",
        "arch/x86/mm/pat/memtype.c:track_pfn_insert",
        "arch/x86/mm/pat/memtype.c:track_pfn_remap",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io",
        "arch/x86/mm/pat/memtype.c:memtype_reserve"
      ],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_create_resource_files",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432640,
      "name": "pat_enabled",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool pat_enabled()
```

```json
{
  "name": "pat_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612220307,
      "name": "pat_enabled",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:93",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_memtype_list_init",
        "arch/x86/mm/pat/memtype.c:untrack_pfn",
        "arch/x86/mm/pat/memtype.c:track_pfn_insert",
        "arch/x86/mm/pat/memtype.c:track_pfn_remap",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io",
        "arch/x86/mm/pat/memtype.c:memtype_reserve"
      ],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_create_resource_files",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579431856,
      "name": "pat_enabled",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool pat_enabled()
```

```json
{
  "name": "pat_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614361244,
      "name": "pat_enabled",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:93",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_memtype_list_init",
        "arch/x86/mm/pat/memtype.c:untrack_pfn",
        "arch/x86/mm/pat/memtype.c:track_pfn_insert",
        "arch/x86/mm/pat/memtype.c:track_pfn_remap",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat/memtype.c:memtype_reserve_io",
        "arch/x86/mm/pat/memtype.c:memtype_reserve"
      ],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_create_resource_files",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579434816,
      "name": "pat_enabled",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pat_enabled()
```

```json
{
  "name": "pat_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579503221,
      "name": "pat_enabled",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:93",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:track_pfn_insert",
        "arch/x86/mm/pat/memtype.c:track_pfn_remap",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:memtype_reserve"
      ],
      "caller_func": [
        "arch/x86/mm/pat/memtype.c:pat_memtype_list_init",
        "drivers/pci/pci-sysfs.c:pci_create_resource_files",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592088628,
      "name": "pat_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579499456,
      "name": "pat_enabled",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pat_enabled()
```

```json
{
  "name": "pat_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579585125,
      "name": "pat_enabled",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:95",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:track_pfn_insert",
        "arch/x86/mm/pat/memtype.c:track_pfn_remap",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:memtype_free",
        "arch/x86/mm/pat/memtype.c:memtype_reserve"
      ],
      "caller_func": [
        "arch/x86/mm/pat/memtype.c:pat_memtype_list_init",
        "drivers/pci/pci-sysfs.c:pci_create_resource_files",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593855548,
      "name": "pat_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579581312,
      "name": "pat_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pat_enabled()
```

```json
{
  "name": "pat_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627721989,
      "name": "pat_enabled",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:89",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_memtype_list_init",
        "arch/x86/mm/pat/memtype.c:track_pfn_insert",
        "arch/x86/mm/pat/memtype.c:track_pfn_remap",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:memtype_free",
        "arch/x86/mm/pat/memtype.c:memtype_reserve"
      ],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_create_resource_files",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595970286,
      "name": "pat_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071579691040,
      "name": "pat_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pat_enabled()
```

```json
{
  "name": "pat_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619479589,
      "name": "pat_enabled",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:89",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_memtype_list_init",
        "arch/x86/mm/pat/memtype.c:track_pfn_insert",
        "arch/x86/mm/pat/memtype.c:track_pfn_remap",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:memtype_free",
        "arch/x86/mm/pat/memtype.c:memtype_reserve"
      ],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_create_resource_files",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596487869,
      "name": "pat_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071579704800,
      "name": "pat_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pat_enabled()
```

```json
{
  "name": "pat_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621776197,
      "name": "pat_enabled",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:89",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_memtype_list_init",
        "arch/x86/mm/pat/memtype.c:track_pfn_insert",
        "arch/x86/mm/pat/memtype.c:track_pfn_remap",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:memtype_free",
        "arch/x86/mm/pat/memtype.c:memtype_reserve"
      ],
      "caller_func": [
        "drivers/pci/pci-sysfs.c:pci_create_resource_files",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597384491,
      "name": "pat_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071579739408,
      "name": "pat_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool pat_enabled()
```

```json
{
  "name": "pat_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604724282,
      "name": "pat_enabled",
      "external": true,
      "loc": "arch/x86/mm/pat.c:67",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_memtype_list_init",
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:track_pfn_insert",
        "arch/x86/mm/pat.c:track_pfn_remap",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat.c:io_reserve_memtype",
        "arch/x86/mm/pat.c:reserve_memtype"
      ],
      "caller_func": [
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579389904,
      "name": "pat_enabled",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool pat_enabled()
```

```json
{
  "name": "pat_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604692012,
      "name": "pat_enabled",
      "external": true,
      "loc": "arch/x86/mm/pat.c:67",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_memtype_list_init",
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:track_pfn_insert",
        "arch/x86/mm/pat.c:track_pfn_remap",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat.c:io_reserve_memtype",
        "arch/x86/mm/pat.c:reserve_memtype"
      ],
      "caller_func": [
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579319456,
      "name": "pat_enabled",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool pat_enabled()
```

```json
{
  "name": "pat_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604801849,
      "name": "pat_enabled",
      "external": true,
      "loc": "arch/x86/mm/pat.c:67",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_memtype_list_init",
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:track_pfn_insert",
        "arch/x86/mm/pat.c:track_pfn_remap",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat.c:io_reserve_memtype",
        "arch/x86/mm/pat.c:reserve_memtype"
      ],
      "caller_func": [
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579389824,
      "name": "pat_enabled",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool pat_enabled()
```

```json
{
  "name": "pat_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604814468,
      "name": "pat_enabled",
      "external": true,
      "loc": "arch/x86/mm/pat.c:67",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_memtype_list_init",
        "arch/x86/mm/pat.c:untrack_pfn",
        "arch/x86/mm/pat.c:track_pfn_insert",
        "arch/x86/mm/pat.c:track_pfn_remap",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:arch_io_free_memtype_wc",
        "arch/x86/mm/pat.c:io_reserve_memtype",
        "arch/x86/mm/pat.c:reserve_memtype"
      ],
      "caller_func": [
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579398352,
      "name": "pat_enabled",
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
bool pat_enabled()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool pat_enabled()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool pat_enabled()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool pat_enabled()
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
