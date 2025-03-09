# Function: <code>gen_pool_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int gen_pool_alloc(struct gen_pool * pool, size_t size)
```

```json
{
  "name": "gen_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583068032,
      "name": "gen_pool_alloc",
      "external": true,
      "loc": "lib/genalloc.c:271",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add",
        "lib/genalloc.c:gen_pool_dma_alloc",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_notify_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583068032,
      "name": "gen_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
long unsigned int gen_pool_alloc(struct gen_pool * pool, size_t size)
```

```json
{
  "name": "gen_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583362847,
      "name": "gen_pool_alloc",
      "external": true,
      "loc": "lib/genalloc.c:271",
      "file": "lib/genalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_dma_alloc"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add",
        "drivers/acpi/apei/ghes.c:ghes_notify_nmi",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583362800,
      "name": "gen_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
long unsigned int gen_pool_alloc(struct gen_pool * pool, size_t size)
```

```json
{
  "name": "gen_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583488223,
      "name": "gen_pool_alloc",
      "external": true,
      "loc": "lib/genalloc.c:271",
      "file": "lib/genalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_dma_alloc"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add",
        "drivers/acpi/apei/ghes.c:ghes_notify_nmi",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583488176,
      "name": "gen_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
long unsigned int gen_pool_alloc(struct gen_pool * pool, size_t size)
```

```json
{
  "name": "gen_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583510463,
      "name": "gen_pool_alloc",
      "external": true,
      "loc": "lib/genalloc.c:271",
      "file": "lib/genalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_dma_alloc"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583510416,
      "name": "gen_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
long unsigned int gen_pool_alloc(struct gen_pool * pool, size_t size)
```

```json
{
  "name": "gen_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583695695,
      "name": "gen_pool_alloc",
      "external": true,
      "loc": "lib/genalloc.c:271",
      "file": "lib/genalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_dma_alloc"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583695648,
      "name": "gen_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
long unsigned int gen_pool_alloc(struct gen_pool * pool, size_t size)
```

```json
{
  "name": "gen_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583913206,
      "name": "gen_pool_alloc",
      "external": true,
      "loc": "lib/genalloc.c:271",
      "file": "lib/genalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_dma_alloc"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add",
        "drivers/acpi/apei/ghes.c:ghes_notify_nmi",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583913152,
      "name": "gen_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
long unsigned int gen_pool_alloc(struct gen_pool * pool, size_t size)
```

```json
{
  "name": "gen_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583997782,
      "name": "gen_pool_alloc",
      "external": true,
      "loc": "lib/genalloc.c:272",
      "file": "lib/genalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_dma_alloc"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583997728,
      "name": "gen_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gen_pool_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579169434,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "arch/x86/kernel/cpu/mce/genpool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585275735,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gen_pool_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579171866,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "arch/x86/kernel/cpu/mce/genpool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585413687,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gen_pool_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579189530,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "arch/x86/kernel/cpu/mce/genpool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580153829,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "kernel/dma/pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/pool.c:__dma_alloc_from_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586124694,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gen_pool_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579185274,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "arch/x86/kernel/cpu/mce/genpool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580134890,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "kernel/dma/pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/pool.c:__dma_alloc_from_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586244406,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc",
        "drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gen_pool_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579191658,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "arch/x86/kernel/cpu/mce/genpool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580140139,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "kernel/dma/pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/pool.c:dma_alloc_from_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586119047,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gen_pool_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579226810,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "arch/x86/kernel/cpu/mce/genpool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580283790,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "kernel/dma/pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/pool.c:dma_alloc_from_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586618925,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gen_pool_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579277290,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "arch/x86/kernel/cpu/mce/genpool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580456366,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "kernel/dma/pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/pool.c:dma_alloc_from_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587883350,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gen_pool_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579342026,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "arch/x86/kernel/cpu/mce/genpool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580703182,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "kernel/dma/pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/pool.c:dma_alloc_from_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589231734,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc",
        "drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gen_pool_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579350906,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "arch/x86/kernel/cpu/mce/genpool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580779611,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "kernel/dma/pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/pool.c:__dma_alloc_from_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589528454,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc",
        "drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gen_pool_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579380794,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "arch/x86/kernel/cpu/mce/genpool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580868459,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "kernel/dma/pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/pool.c:__dma_alloc_from_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589836950,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc",
        "drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event",
        "drivers/acpi/apei/ghes.c:ghes_handle_aer"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "gen_pool_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491300020,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "kernel/dma/remap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/remap.c:dma_alloc_from_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497691716,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_in_nmi_queue_one_entry",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498095820,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "drivers/soc/fsl/qbman/bman.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/bman.c:bman_new_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498096416,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "drivers/soc/fsl/qbman/qman.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/qman.c:qman_alloc_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500043388,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "drivers/net/ethernet/freescale/fman/fman_muram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fman/fman_muram.c:fman_muram_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501254500,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "drivers/edac/altera_edac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/altera_edac.c:ocram_alloc_mem"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "gen_pool_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224484816,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "arch/arm/mm/dma-mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "arch/arm/mach-imx/pm-imx5.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243311740,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "arch/arm/mach-imx/pm-imx6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-imx/pm-imx6.c:imx6q_suspend_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243330692,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "arch/arm/mach-omap2/omap4-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/omap4-common.c:__omap4_sram_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3232592068,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "drivers/net/ethernet/ti/davinci_cpdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gen_pool_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579172122,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "arch/x86/kernel/cpu/mce/genpool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gen_pool_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579103866,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "arch/x86/kernel/cpu/mce/genpool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gen_pool_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579171786,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "arch/x86/kernel/cpu/mce/genpool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585364087,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gen_pool_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579176970,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "arch/x86/kernel/cpu/mce/genpool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585471415,
      "name": "gen_pool_alloc",
      "external": false,
      "loc": "include/linux/genalloc.h:151",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add"
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
long unsigned int gen_pool_alloc(struct gen_pool * pool, size_t size)
```
</details>
</li>
</ul>
