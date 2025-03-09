# Function: <code>fill_pud</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fill_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595064030,
      "name": "fill_pud",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:233",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:populate_extra_pmd"
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
  "name": "fill_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595229731,
      "name": "fill_pud",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:162",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:populate_extra_pmd"
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
  "name": "fill_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595472781,
      "name": "fill_pud",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:152",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:populate_extra_pmd"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
pud_t * fill_pud(p4d_t * p4d, long unsigned int vaddr)
```

```json
{
  "name": "fill_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579287136,
      "name": "fill_pud",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:213",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579287136,
      "name": "fill_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
pud_t * fill_pud(p4d_t * p4d, long unsigned int vaddr)
```

```json
{
  "name": "fill_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579306096,
      "name": "fill_pud",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:213",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579306096,
      "name": "fill_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
pud_t * fill_pud(p4d_t * p4d, long unsigned int vaddr)
```

```json
{
  "name": "fill_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579317888,
      "name": "fill_pud",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:224",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579317888,
      "name": "fill_pud",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
pud_t * fill_pud(p4d_t * p4d, long unsigned int vaddr)
```

```json
{
  "name": "fill_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579342576,
      "name": "fill_pud",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:223",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579342576,
      "name": "fill_pud",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
pud_t * fill_pud(p4d_t * p4d, long unsigned int vaddr)
```

```json
{
  "name": "fill_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579358240,
      "name": "fill_pud",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:255",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579358240,
      "name": "fill_pud",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
pud_t * fill_pud(p4d_t * p4d, long unsigned int vaddr)
```

```json
{
  "name": "fill_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579362480,
      "name": "fill_pud",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:255",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579362480,
      "name": "fill_pud",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
pud_t * fill_pud(p4d_t * p4d, long unsigned int vaddr)
```

```json
{
  "name": "fill_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579388992,
      "name": "fill_pud",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:260",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579388992,
      "name": "fill_pud",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
pud_t * fill_pud(p4d_t * p4d, long unsigned int vaddr)
```

```json
{
  "name": "fill_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579394384,
      "name": "fill_pud",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:255",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394384,
      "name": "fill_pud",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
pud_t * fill_pud(p4d_t * p4d, long unsigned int vaddr)
```

```json
{
  "name": "fill_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579397216,
      "name": "fill_pud",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:255",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579397216,
      "name": "fill_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
pud_t * fill_pud(p4d_t * p4d, long unsigned int vaddr)
```

```json
{
  "name": "fill_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579459440,
      "name": "fill_pud",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:256",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579459440,
      "name": "fill_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
pud_t * fill_pud(p4d_t * p4d, long unsigned int vaddr)
```

```json
{
  "name": "fill_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579535328,
      "name": "fill_pud",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:255",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579535328,
      "name": "fill_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
pud_t * fill_pud(p4d_t * p4d, long unsigned int vaddr)
```

```json
{
  "name": "fill_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579638496,
      "name": "fill_pud",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:261",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579638496,
      "name": "fill_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
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
pud_t * fill_pud(p4d_t * p4d, long unsigned int vaddr)
```

```json
{
  "name": "fill_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579652544,
      "name": "fill_pud",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:261",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579652544,
      "name": "fill_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
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
pud_t * fill_pud(p4d_t * p4d, long unsigned int vaddr)
```

```json
{
  "name": "fill_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579686720,
      "name": "fill_pud",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:261",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686720,
      "name": "fill_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
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
pud_t * fill_pud(p4d_t * p4d, long unsigned int vaddr)
```

```json
{
  "name": "fill_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579358384,
      "name": "fill_pud",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:255",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579358384,
      "name": "fill_pud",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
pud_t * fill_pud(p4d_t * p4d, long unsigned int vaddr)
```

```json
{
  "name": "fill_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fill_pud",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:255",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579290544,
      "name": "fill_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071579293434,
      "name": "fill_pud.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
pud_t * fill_pud(p4d_t * p4d, long unsigned int vaddr)
```

```json
{
  "name": "fill_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579358304,
      "name": "fill_pud",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:255",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579358304,
      "name": "fill_pud",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
pud_t * fill_pud(p4d_t * p4d, long unsigned int vaddr)
```

```json
{
  "name": "fill_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579366736,
      "name": "fill_pud",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:255",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579366736,
      "name": "fill_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
pud_t * fill_pud(p4d_t * p4d, long unsigned int vaddr)
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
pud_t * fill_pud(p4d_t * p4d, long unsigned int vaddr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
pud_t * fill_pud(p4d_t * p4d, long unsigned int vaddr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
pud_t * fill_pud(p4d_t * p4d, long unsigned int vaddr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
pud_t * fill_pud(p4d_t * p4d, long unsigned int vaddr)
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
