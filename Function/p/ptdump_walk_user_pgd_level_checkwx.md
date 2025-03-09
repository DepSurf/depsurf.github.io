# Function: <code>ptdump_walk_user_pgd_level_checkwx</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptdump_walk_user_pgd_level_checkwx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579355913,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:543",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptdump_walk_user_pgd_level_checkwx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579367417,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:566",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void ptdump_walk_user_pgd_level_checkwx()
```

```json
{
  "name": "ptdump_walk_user_pgd_level_checkwx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "external": true,
      "loc": "arch/x86/mm/dump_pagetables.c:589",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_finalize",
        "arch/x86/mm/pti.c:pti_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579395615,
      "name": "ptdump_walk_user_pgd_level_checkwx.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071579394864,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void ptdump_walk_user_pgd_level_checkwx()
```

```json
{
  "name": "ptdump_walk_user_pgd_level_checkwx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "external": true,
      "loc": "arch/x86/mm/dump_pagetables.c:584",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_finalize",
        "arch/x86/mm/pti.c:pti_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579410983,
      "name": "ptdump_walk_user_pgd_level_checkwx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071579410128,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void ptdump_walk_user_pgd_level_checkwx()
```

```json
{
  "name": "ptdump_walk_user_pgd_level_checkwx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "external": true,
      "loc": "arch/x86/mm/dump_pagetables.c:584",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_finalize",
        "arch/x86/mm/pti.c:pti_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579414179,
      "name": "ptdump_walk_user_pgd_level_checkwx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071579413312,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void ptdump_walk_user_pgd_level_checkwx()
```

```json
{
  "name": "ptdump_walk_user_pgd_level_checkwx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "external": true,
      "loc": "arch/x86/mm/dump_pagetables.c:419",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579443779,
      "name": "ptdump_walk_user_pgd_level_checkwx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579443104,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void ptdump_walk_user_pgd_level_checkwx()
```

```json
{
  "name": "ptdump_walk_user_pgd_level_checkwx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "external": true,
      "loc": "arch/x86/mm/dump_pagetables.c:419",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591272136,
      "name": "ptdump_walk_user_pgd_level_checkwx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579441344,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void ptdump_walk_user_pgd_level_checkwx()
```

```json
{
  "name": "ptdump_walk_user_pgd_level_checkwx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "external": true,
      "loc": "arch/x86/mm/dump_pagetables.c:419",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_finalize",
        "arch/x86/mm/pti.c:pti_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591214899,
      "name": "ptdump_walk_user_pgd_level_checkwx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071579444144,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void ptdump_walk_user_pgd_level_checkwx()
```

```json
{
  "name": "ptdump_walk_user_pgd_level_checkwx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "external": true,
      "loc": "arch/x86/mm/dump_pagetables.c:419",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_finalize",
        "arch/x86/mm/pti.c:pti_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592090965,
      "name": "ptdump_walk_user_pgd_level_checkwx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071579508848,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void ptdump_walk_user_pgd_level_checkwx()
```

```json
{
  "name": "ptdump_walk_user_pgd_level_checkwx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "external": true,
      "loc": "arch/x86/mm/dump_pagetables.c:419",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_finalize",
        "arch/x86/mm/pti.c:pti_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593857957,
      "name": "ptdump_walk_user_pgd_level_checkwx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071579592112,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void ptdump_walk_user_pgd_level_checkwx()
```

```json
{
  "name": "ptdump_walk_user_pgd_level_checkwx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579703328,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "external": true,
      "loc": "arch/x86/mm/dump_pagetables.c:419",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_finalize",
        "arch/x86/mm/pti.c:pti_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579703328,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void ptdump_walk_user_pgd_level_checkwx()
```

```json
{
  "name": "ptdump_walk_user_pgd_level_checkwx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579716816,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "external": true,
      "loc": "arch/x86/mm/dump_pagetables.c:419",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_finalize",
        "arch/x86/mm/pti.c:pti_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579716816,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void ptdump_walk_user_pgd_level_checkwx()
```

```json
{
  "name": "ptdump_walk_user_pgd_level_checkwx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579751536,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "external": true,
      "loc": "arch/x86/mm/dump_pagetables.c:419",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_finalize",
        "arch/x86/mm/pti.c:pti_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579751536,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void ptdump_walk_user_pgd_level_checkwx()
```

```json
{
  "name": "ptdump_walk_user_pgd_level_checkwx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "external": true,
      "loc": "arch/x86/mm/dump_pagetables.c:584",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_finalize",
        "arch/x86/mm/pti.c:pti_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579410019,
      "name": "ptdump_walk_user_pgd_level_checkwx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071579409152,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void ptdump_walk_user_pgd_level_checkwx()
```

```json
{
  "name": "ptdump_walk_user_pgd_level_checkwx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "external": true,
      "loc": "arch/x86/mm/dump_pagetables.c:584",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_finalize",
        "arch/x86/mm/pti.c:pti_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579339331,
      "name": "ptdump_walk_user_pgd_level_checkwx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071579338464,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void ptdump_walk_user_pgd_level_checkwx()
```

```json
{
  "name": "ptdump_walk_user_pgd_level_checkwx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "external": true,
      "loc": "arch/x86/mm/dump_pagetables.c:584",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_finalize",
        "arch/x86/mm/pti.c:pti_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579409939,
      "name": "ptdump_walk_user_pgd_level_checkwx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071579409072,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void ptdump_walk_user_pgd_level_checkwx()
```

```json
{
  "name": "ptdump_walk_user_pgd_level_checkwx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "external": true,
      "loc": "arch/x86/mm/dump_pagetables.c:584",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_finalize",
        "arch/x86/mm/pti.c:pti_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579418803,
      "name": "ptdump_walk_user_pgd_level_checkwx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071579417936,
      "name": "ptdump_walk_user_pgd_level_checkwx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void ptdump_walk_user_pgd_level_checkwx()
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
void ptdump_walk_user_pgd_level_checkwx()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void ptdump_walk_user_pgd_level_checkwx()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void ptdump_walk_user_pgd_level_checkwx()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void ptdump_walk_user_pgd_level_checkwx()
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
