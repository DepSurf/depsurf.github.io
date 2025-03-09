# Function: <code>e820__update_table</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int e820__update_table(struct e820_table * table)
```

```json
{
  "name": "e820__update_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596324243,
      "name": "e820__update_table",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:272",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_auto_xlated_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__finish_early_params",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/e820.c:e820__update_table_print",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596324243,
      "name": "e820__update_table",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 556
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
int e820__update_table(struct e820_table * table)
```

```json
{
  "name": "e820__update_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602642281,
      "name": "e820__update_table",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:292",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_auto_xlated_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__finish_early_params",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/e820.c:e820__update_table_print",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602642281,
      "name": "e820__update_table",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 556
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
int e820__update_table(struct e820_table * table)
```

```json
{
  "name": "e820__update_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602811968,
      "name": "e820__update_table",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:294",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_auto_xlated_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__finish_early_params",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/e820.c:e820__update_table_print",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602811968,
      "name": "e820__update_table",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 545
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
int e820__update_table(struct e820_table * table)
```

```json
{
  "name": "e820__update_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604607015,
      "name": "e820__update_table",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:293",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__finish_early_params",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/e820.c:e820__update_table_print",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604607015,
      "name": "e820__update_table",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 545
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
int e820__update_table(struct e820_table * table)
```

```json
{
  "name": "e820__update_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604702616,
      "name": "e820__update_table",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:307",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__finish_early_params",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/e820.c:e820__update_table_print",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604702616,
      "name": "e820__update_table",
      "section": ".init.text",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int e820__update_table(struct e820_table * table)
```

```json
{
  "name": "e820__update_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604715004,
      "name": "e820__update_table",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:307",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__finish_early_params",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/e820.c:e820__update_table_print",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604715004,
      "name": "e820__update_table",
      "section": ".init.text",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int e820__update_table(struct e820_table * table)
```

```json
{
  "name": "e820__update_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609061639,
      "name": "e820__update_table",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:308",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__finish_early_params",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/e820.c:e820__update_table_print",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/efi.c:do_add_efi_memmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609061639,
      "name": "e820__update_table",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 530
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
int e820__update_table(struct e820_table * table)
```

```json
{
  "name": "e820__update_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612124999,
      "name": "e820__update_table",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:322",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__finish_early_params",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/e820.c:e820__update_table_print",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/efi.c:do_add_efi_memmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612124999,
      "name": "e820__update_table",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 546
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
int e820__update_table(struct e820_table * table)
```

```json
{
  "name": "e820__update_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614264920,
      "name": "e820__update_table",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:322",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__finish_early_params",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/e820.c:e820__update_table_print",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614264920,
      "name": "e820__update_table",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 546
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
int e820__update_table(struct e820_table * table)
```

```json
{
  "name": "e820__update_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615186252,
      "name": "e820__update_table",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:322",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__finish_early_params",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/e820.c:e820__update_table_print",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615186252,
      "name": "e820__update_table",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 1301
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
int e820__update_table(struct e820_table * table)
```

```json
{
  "name": "e820__update_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616952840,
      "name": "e820__update_table",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:322",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__finish_early_params",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/e820.c:e820__update_table_print",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616952840,
      "name": "e820__update_table",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 1593
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
int e820__update_table(struct e820_table * table)
```

```json
{
  "name": "e820__update_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627564208,
      "name": "e820__update_table",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:322",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__finish_early_params",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/e820.c:e820__update_table_print",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627564208,
      "name": "e820__update_table",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 3005
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
int e820__update_table(struct e820_table * table)
```

```json
{
  "name": "e820__update_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619314944,
      "name": "e820__update_table",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:322",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__finish_early_params",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/e820.c:e820__update_table_print",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619314944,
      "name": "e820__update_table",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 3016
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
int e820__update_table(struct e820_table * table)
```

```json
{
  "name": "e820__update_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621608064,
      "name": "e820__update_table",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:322",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__finish_early_params",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/e820.c:e820__update_table_print",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621608064,
      "name": "e820__update_table",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 3016
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
int e820__update_table(struct e820_table * table)
```

```json
{
  "name": "e820__update_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604641294,
      "name": "e820__update_table",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:307",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__finish_early_params",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/e820.c:e820__update_table_print",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604641294,
      "name": "e820__update_table",
      "section": ".init.text",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int e820__update_table(struct e820_table * table)
```

```json
{
  "name": "e820__update_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604609228,
      "name": "e820__update_table",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:307",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__finish_early_params",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/e820.c:e820__update_table_print",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604609228,
      "name": "e820__update_table",
      "section": ".init.text",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int e820__update_table(struct e820_table * table)
```

```json
{
  "name": "e820__update_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604719086,
      "name": "e820__update_table",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:307",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__finish_early_params",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/e820.c:e820__update_table_print",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604719086,
      "name": "e820__update_table",
      "section": ".init.text",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int e820__update_table(struct e820_table * table)
```

```json
{
  "name": "e820__update_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604719116,
      "name": "e820__update_table",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:307",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__finish_early_params",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/e820.c:e820__update_table_print",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604719116,
      "name": "e820__update_table",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 525
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int e820__update_table(struct e820_table * table)
```
</details>
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
int e820__update_table(struct e820_table * table)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int e820__update_table(struct e820_table * table)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int e820__update_table(struct e820_table * table)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int e820__update_table(struct e820_table * table)
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
