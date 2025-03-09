# Function: <code>lookup_address_in_pgd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
pte_t * lookup_address_in_pgd(pgd_t * pgd, long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address_in_pgd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579292048,
      "name": "lookup_address_in_pgd",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:327",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579292048,
      "name": "lookup_address_in_pgd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
pte_t * lookup_address_in_pgd(pgd_t * pgd, long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address_in_pgd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579291584,
      "name": "lookup_address_in_pgd",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:333",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291584,
      "name": "lookup_address_in_pgd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
pte_t * lookup_address_in_pgd(pgd_t * pgd, long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address_in_pgd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579307008,
      "name": "lookup_address_in_pgd",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:333",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579307008,
      "name": "lookup_address_in_pgd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
pte_t * lookup_address_in_pgd(pgd_t * pgd, long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address_in_pgd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579304768,
      "name": "lookup_address_in_pgd",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:353",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304768,
      "name": "lookup_address_in_pgd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
pte_t * lookup_address_in_pgd(pgd_t * pgd, long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address_in_pgd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579326512,
      "name": "lookup_address_in_pgd",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:353",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:cpa_flush_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326512,
      "name": "lookup_address_in_pgd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
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
pte_t * lookup_address_in_pgd(pgd_t * pgd, long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address_in_pgd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579337488,
      "name": "lookup_address_in_pgd",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:373",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:cpa_flush_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579337488,
      "name": "lookup_address_in_pgd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
pte_t * lookup_address_in_pgd(pgd_t * pgd, long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address_in_pgd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579364032,
      "name": "lookup_address_in_pgd",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:557",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/pageattr.c:protect_kernel_text_ro",
        "arch/x86/mm/pageattr.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579364032,
      "name": "lookup_address_in_pgd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
pte_t * lookup_address_in_pgd(pgd_t * pgd, long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address_in_pgd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579378592,
      "name": "lookup_address_in_pgd",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:566",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/pageattr.c:kernel_page_present",
        "arch/x86/mm/pageattr.c:protect_kernel_text_ro",
        "arch/x86/mm/pageattr.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579378592,
      "name": "lookup_address_in_pgd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
pte_t * lookup_address_in_pgd(pgd_t * pgd, long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address_in_pgd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579382880,
      "name": "lookup_address_in_pgd",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:566",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/pageattr.c:kernel_page_present",
        "arch/x86/mm/pageattr.c:protect_kernel_text_ro",
        "arch/x86/mm/pageattr.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579382880,
      "name": "lookup_address_in_pgd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
pte_t * lookup_address_in_pgd(pgd_t * pgd, long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address_in_pgd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579422832,
      "name": "lookup_address_in_pgd",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:575",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:show_fault_oops",
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_mm",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579422832,
      "name": "lookup_address_in_pgd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
pte_t * lookup_address_in_pgd(pgd_t * pgd, long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address_in_pgd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579422528,
      "name": "lookup_address_in_pgd",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:575",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:show_fault_oops",
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_mm",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579422528,
      "name": "lookup_address_in_pgd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
pte_t * lookup_address_in_pgd(pgd_t * pgd, long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address_in_pgd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579425584,
      "name": "lookup_address_in_pgd",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:583",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:show_fault_oops",
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_mm",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579425584,
      "name": "lookup_address_in_pgd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
pte_t * lookup_address_in_pgd(pgd_t * pgd, long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address_in_pgd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579489248,
      "name": "lookup_address_in_pgd",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:583",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:show_fault_oops",
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:_lookup_address_cpa",
        "arch/x86/mm/pat/set_memory.c:_lookup_address_cpa",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_mm",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579489248,
      "name": "lookup_address_in_pgd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
pte_t * lookup_address_in_pgd(pgd_t * pgd, long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address_in_pgd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579569328,
      "name": "lookup_address_in_pgd",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:586",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:show_fault_oops",
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:_lookup_address_cpa",
        "arch/x86/mm/pat/set_memory.c:_lookup_address_cpa",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579569328,
      "name": "lookup_address_in_pgd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
pte_t * lookup_address_in_pgd(pgd_t * pgd, long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address_in_pgd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579677632,
      "name": "lookup_address_in_pgd",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:661",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:show_fault_oops",
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:_lookup_address_cpa",
        "arch/x86/mm/pat/set_memory.c:_lookup_address_cpa",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579677632,
      "name": "lookup_address_in_pgd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
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
pte_t * lookup_address_in_pgd(pgd_t * pgd, long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address_in_pgd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579691472,
      "name": "lookup_address_in_pgd",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:662",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:show_fault_oops",
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:_lookup_address_cpa",
        "arch/x86/mm/pat/set_memory.c:_lookup_address_cpa",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691472,
      "name": "lookup_address_in_pgd",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
pte_t * lookup_address_in_pgd(pgd_t * pgd, long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address_in_pgd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579726000,
      "name": "lookup_address_in_pgd",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:662",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:show_fault_oops",
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:_lookup_address_cpa",
        "arch/x86/mm/pat/set_memory.c:_lookup_address_cpa",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579726000,
      "name": "lookup_address_in_pgd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
pte_t * lookup_address_in_pgd(pgd_t * pgd, long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address_in_pgd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579378784,
      "name": "lookup_address_in_pgd",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:566",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/pageattr.c:kernel_page_present",
        "arch/x86/mm/pageattr.c:protect_kernel_text_ro",
        "arch/x86/mm/pageattr.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579378784,
      "name": "lookup_address_in_pgd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
pte_t * lookup_address_in_pgd(pgd_t * pgd, long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address_in_pgd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579308624,
      "name": "lookup_address_in_pgd",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:566",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/pageattr.c:kernel_page_present",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys",
        "arch/x86/mm/pageattr.c:protect_kernel_text_ro",
        "arch/x86/mm/pageattr.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579308624,
      "name": "lookup_address_in_pgd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
pte_t * lookup_address_in_pgd(pgd_t * pgd, long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address_in_pgd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579378704,
      "name": "lookup_address_in_pgd",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:566",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/pageattr.c:kernel_page_present",
        "arch/x86/mm/pageattr.c:protect_kernel_text_ro",
        "arch/x86/mm/pageattr.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579378704,
      "name": "lookup_address_in_pgd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
pte_t * lookup_address_in_pgd(pgd_t * pgd, long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address_in_pgd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579387184,
      "name": "lookup_address_in_pgd",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:566",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/pageattr.c:kernel_page_present",
        "arch/x86/mm/pageattr.c:protect_kernel_text_ro",
        "arch/x86/mm/pageattr.c:cpa_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579387184,
      "name": "lookup_address_in_pgd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
pte_t * lookup_address_in_pgd(pgd_t * pgd, long unsigned int address, unsigned int * level)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
pte_t * lookup_address_in_pgd(pgd_t * pgd, long unsigned int address, unsigned int * level)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
pte_t * lookup_address_in_pgd(pgd_t * pgd, long unsigned int address, unsigned int * level)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
pte_t * lookup_address_in_pgd(pgd_t * pgd, long unsigned int address, unsigned int * level)
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
