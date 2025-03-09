# Function: <code>fill_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
pte_t * fill_pte(pmd_t * pmd, long unsigned int vaddr)
```

```json
{
  "name": "fill_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579275472,
      "name": "fill_pte",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:257",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:populate_extra_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275472,
      "name": "fill_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
pte_t * fill_pte(pmd_t * pmd, long unsigned int vaddr)
```

```json
{
  "name": "fill_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579274800,
      "name": "fill_pte",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:186",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pte",
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274800,
      "name": "fill_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
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
pte_t * fill_pte(pmd_t * pmd, long unsigned int vaddr)
```

```json
{
  "name": "fill_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579290240,
      "name": "fill_pte",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:176",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pte",
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579290240,
      "name": "fill_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
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
pte_t * fill_pte(pmd_t * pmd, long unsigned int vaddr)
```

```json
{
  "name": "fill_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579286800,
      "name": "fill_pte",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:237",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pte",
        "arch/x86/mm/init_64.c:__set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579286800,
      "name": "fill_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
pte_t * fill_pte(pmd_t * pmd, long unsigned int vaddr)
```

```json
{
  "name": "fill_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579305712,
      "name": "fill_pte",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:237",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pte",
        "arch/x86/mm/init_64.c:__set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305712,
      "name": "fill_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
pte_t * fill_pte(pmd_t * pmd, long unsigned int vaddr)
```

```json
{
  "name": "fill_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fill_pte",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:248",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pte",
        "arch/x86/mm/init_64.c:__set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579317568,
      "name": "fill_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
    },
    {
      "addr": 18446744071579322634,
      "name": "fill_pte.cold.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
pte_t * fill_pte(pmd_t * pmd, long unsigned int vaddr)
```

```json
{
  "name": "fill_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fill_pte",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:247",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pte",
        "arch/x86/mm/init_64.c:__set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579342256,
      "name": "fill_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
    },
    {
      "addr": 18446744071579346973,
      "name": "fill_pte.cold.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
pte_t * fill_pte(pmd_t * pmd, long unsigned int vaddr)
```

```json
{
  "name": "fill_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fill_pte",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:279",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pte",
        "arch/x86/mm/init_64.c:__set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579357920,
      "name": "fill_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
    },
    {
      "addr": 18446744071579362700,
      "name": "fill_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
pte_t * fill_pte(pmd_t * pmd, long unsigned int vaddr)
```

```json
{
  "name": "fill_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fill_pte",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:279",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pte",
        "arch/x86/mm/init_64.c:__set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579362160,
      "name": "fill_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
    },
    {
      "addr": 18446744071579366940,
      "name": "fill_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
pte_t * fill_pte(pmd_t * pmd, long unsigned int vaddr)
```

```json
{
  "name": "fill_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fill_pte",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:284",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pte",
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579388320,
      "name": "fill_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
    },
    {
      "addr": 18446744071579395392,
      "name": "fill_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
pte_t * fill_pte(pmd_t * pmd, long unsigned int vaddr)
```

```json
{
  "name": "fill_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fill_pte",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:279",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pte",
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579393712,
      "name": "fill_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
    },
    {
      "addr": 18446744071591268794,
      "name": "fill_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
pte_t * fill_pte(pmd_t * pmd, long unsigned int vaddr)
```

```json
{
  "name": "fill_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fill_pte",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:279",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pte",
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579397872,
      "name": "fill_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 18446744071591211327,
      "name": "fill_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
pte_t * fill_pte(pmd_t * pmd, long unsigned int vaddr)
```

```json
{
  "name": "fill_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fill_pte",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:280",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pte",
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579460096,
      "name": "fill_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 18446744071592085257,
      "name": "fill_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
pte_t * fill_pte(pmd_t * pmd, long unsigned int vaddr)
```

```json
{
  "name": "fill_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fill_pte",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:279",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pte",
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579536016,
      "name": "fill_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
    },
    {
      "addr": 18446744071593851953,
      "name": "fill_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
pte_t * fill_pte(pmd_t * pmd, long unsigned int vaddr)
```

```json
{
  "name": "fill_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579639168,
      "name": "fill_pte",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:285",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pte",
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579639168,
      "name": "fill_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
pte_t * fill_pte(pmd_t * pmd, long unsigned int vaddr)
```

```json
{
  "name": "fill_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579653216,
      "name": "fill_pte",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:285",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pte",
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653216,
      "name": "fill_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
pte_t * fill_pte(pmd_t * pmd, long unsigned int vaddr)
```

```json
{
  "name": "fill_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579687088,
      "name": "fill_pte",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:285",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pte",
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579687088,
      "name": "fill_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
pte_t * fill_pte(pmd_t * pmd, long unsigned int vaddr)
```

```json
{
  "name": "fill_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fill_pte",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:279",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pte",
        "arch/x86/mm/init_64.c:__set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579358064,
      "name": "fill_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
    },
    {
      "addr": 18446744071579362844,
      "name": "fill_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
pte_t * fill_pte(pmd_t * pmd, long unsigned int vaddr)
```

```json
{
  "name": "fill_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fill_pte",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:279",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pte",
        "arch/x86/mm/init_64.c:__set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579289824,
      "name": "fill_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
    },
    {
      "addr": 18446744071579293413,
      "name": "fill_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
pte_t * fill_pte(pmd_t * pmd, long unsigned int vaddr)
```

```json
{
  "name": "fill_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fill_pte",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:279",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pte",
        "arch/x86/mm/init_64.c:__set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579357984,
      "name": "fill_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
    },
    {
      "addr": 18446744071579362764,
      "name": "fill_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
pte_t * fill_pte(pmd_t * pmd, long unsigned int vaddr)
```

```json
{
  "name": "fill_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fill_pte",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:279",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pte",
        "arch/x86/mm/init_64.c:__set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579366416,
      "name": "fill_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
    },
    {
      "addr": 18446744071579371196,
      "name": "fill_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
pte_t * fill_pte(pmd_t * pmd, long unsigned int vaddr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
pte_t * fill_pte(pmd_t * pmd, long unsigned int vaddr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
pte_t * fill_pte(pmd_t * pmd, long unsigned int vaddr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
pte_t * fill_pte(pmd_t * pmd, long unsigned int vaddr)
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
