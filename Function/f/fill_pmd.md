# Function: <code>fill_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
pmd_t * fill_pmd(pud_t * pud, long unsigned int vaddr)
```

```json
{
  "name": "fill_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579275776,
      "name": "fill_pmd",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:245",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:populate_extra_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275776,
      "name": "fill_pmd",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
pmd_t * fill_pmd(pud_t * pud, long unsigned int vaddr)
```

```json
{
  "name": "fill_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579275136,
      "name": "fill_pmd",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:174",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275136,
      "name": "fill_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
pmd_t * fill_pmd(pud_t * pud, long unsigned int vaddr)
```

```json
{
  "name": "fill_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579290576,
      "name": "fill_pmd",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:164",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579290576,
      "name": "fill_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
pmd_t * fill_pmd(pud_t * pud, long unsigned int vaddr)
```

```json
{
  "name": "fill_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579287456,
      "name": "fill_pmd",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:225",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:__set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579287456,
      "name": "fill_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
pmd_t * fill_pmd(pud_t * pud, long unsigned int vaddr)
```

```json
{
  "name": "fill_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579306448,
      "name": "fill_pmd",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:225",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:__set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579306448,
      "name": "fill_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
pmd_t * fill_pmd(pud_t * pud, long unsigned int vaddr)
```

```json
{
  "name": "fill_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579318192,
      "name": "fill_pmd",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:236",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:__set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579318192,
      "name": "fill_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
pmd_t * fill_pmd(pud_t * pud, long unsigned int vaddr)
```

```json
{
  "name": "fill_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579343360,
      "name": "fill_pmd",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:235",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:__set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579343360,
      "name": "fill_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
pmd_t * fill_pmd(pud_t * pud, long unsigned int vaddr)
```

```json
{
  "name": "fill_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579359008,
      "name": "fill_pmd",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:267",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:__set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359008,
      "name": "fill_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
pmd_t * fill_pmd(pud_t * pud, long unsigned int vaddr)
```

```json
{
  "name": "fill_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579363248,
      "name": "fill_pmd",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:267",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:__set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579363248,
      "name": "fill_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
pmd_t * fill_pmd(pud_t * pud, long unsigned int vaddr)
```

```json
{
  "name": "fill_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579388640,
      "name": "fill_pmd",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:272",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579388640,
      "name": "fill_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
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
pmd_t * fill_pmd(pud_t * pud, long unsigned int vaddr)
```

```json
{
  "name": "fill_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579394032,
      "name": "fill_pmd",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:267",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394032,
      "name": "fill_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
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
pmd_t * fill_pmd(pud_t * pud, long unsigned int vaddr)
```

```json
{
  "name": "fill_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579397520,
      "name": "fill_pmd",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:267",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579397520,
      "name": "fill_pmd",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
pmd_t * fill_pmd(pud_t * pud, long unsigned int vaddr)
```

```json
{
  "name": "fill_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579459744,
      "name": "fill_pmd",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:268",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579459744,
      "name": "fill_pmd",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
pmd_t * fill_pmd(pud_t * pud, long unsigned int vaddr)
```

```json
{
  "name": "fill_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579535648,
      "name": "fill_pmd",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:267",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579535648,
      "name": "fill_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
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
pmd_t * fill_pmd(pud_t * pud, long unsigned int vaddr)
```

```json
{
  "name": "fill_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579639536,
      "name": "fill_pmd",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:273",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579639536,
      "name": "fill_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
pmd_t * fill_pmd(pud_t * pud, long unsigned int vaddr)
```

```json
{
  "name": "fill_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579653584,
      "name": "fill_pmd",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:273",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653584,
      "name": "fill_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
pmd_t * fill_pmd(pud_t * pud, long unsigned int vaddr)
```

```json
{
  "name": "fill_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579687456,
      "name": "fill_pmd",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:273",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579687456,
      "name": "fill_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
pmd_t * fill_pmd(pud_t * pud, long unsigned int vaddr)
```

```json
{
  "name": "fill_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579359152,
      "name": "fill_pmd",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:267",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:__set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359152,
      "name": "fill_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
pmd_t * fill_pmd(pud_t * pud, long unsigned int vaddr)
```

```json
{
  "name": "fill_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fill_pmd",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:267",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:__set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579289552,
      "name": "fill_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
    },
    {
      "addr": 18446744071579293389,
      "name": "fill_pmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
pmd_t * fill_pmd(pud_t * pud, long unsigned int vaddr)
```

```json
{
  "name": "fill_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579359072,
      "name": "fill_pmd",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:267",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:__set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359072,
      "name": "fill_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
pmd_t * fill_pmd(pud_t * pud, long unsigned int vaddr)
```

```json
{
  "name": "fill_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579367504,
      "name": "fill_pmd",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:267",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:__set_pte_vaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579367504,
      "name": "fill_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
pmd_t * fill_pmd(pud_t * pud, long unsigned int vaddr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
pmd_t * fill_pmd(pud_t * pud, long unsigned int vaddr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
pmd_t * fill_pmd(pud_t * pud, long unsigned int vaddr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
pmd_t * fill_pmd(pud_t * pud, long unsigned int vaddr)
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
