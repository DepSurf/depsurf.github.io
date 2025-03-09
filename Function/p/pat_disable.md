# Function: <code>pat_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pat_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595065446,
      "name": "pat_disable",
      "external": false,
      "loc": "arch/x86/mm/pat.c:43",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:nopat",
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pat_disable(const char * reason)
```

```json
{
  "name": "pat_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579302496,
      "name": "pat_disable",
      "external": true,
      "loc": "arch/x86/mm/pat.c:44",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init",
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:nopat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579302496,
      "name": "pat_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void pat_disable(const char * reason)
```

```json
{
  "name": "pat_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579317904,
      "name": "pat_disable",
      "external": true,
      "loc": "arch/x86/mm/pat.c:44",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init",
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:nopat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579317904,
      "name": "pat_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void pat_disable(const char * reason)
```

```json
{
  "name": "pat_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579315232,
      "name": "pat_disable",
      "external": true,
      "loc": "arch/x86/mm/pat.c:45",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init",
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:nopat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579315232,
      "name": "pat_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void pat_disable(const char * reason)
```

```json
{
  "name": "pat_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579338144,
      "name": "pat_disable",
      "external": true,
      "loc": "arch/x86/mm/pat.c:45",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init",
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:nopat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579338144,
      "name": "pat_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pat_disable(const char * reason)
```

```json
{
  "name": "pat_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "pat_disable",
      "external": true,
      "loc": "arch/x86/mm/pat.c:45",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:nopat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579352730,
      "name": "pat_disable.cold.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579349536,
      "name": "pat_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pat_disable(const char * reason)
```

```json
{
  "name": "pat_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579379722,
      "name": "pat_disable",
      "external": true,
      "loc": "arch/x86/mm/pat.c:45",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:nopat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579379722,
      "name": "pat_disable.cold.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579376480,
      "name": "pat_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pat_disable(const char * reason)
```

```json
{
  "name": "pat_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579395172,
      "name": "pat_disable",
      "external": true,
      "loc": "arch/x86/mm/pat.c:46",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:nopat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579395172,
      "name": "pat_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579392000,
      "name": "pat_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pat_disable(const char * reason)
```

```json
{
  "name": "pat_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579398484,
      "name": "pat_disable",
      "external": true,
      "loc": "arch/x86/mm/pat.c:46",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:nopat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579398484,
      "name": "pat_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579395312,
      "name": "pat_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pat_disable(const char * msg_reason)
```

```json
{
  "name": "pat_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579437183,
      "name": "pat_disable",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:72",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/mm/pat/memtype.c:pat_init",
        "arch/x86/mm/pat/memtype.c:pat_init",
        "arch/x86/mm/pat/memtype.c:nopat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579437183,
      "name": "pat_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579434096,
      "name": "pat_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pat_disable(const char * msg_reason)
```

```json
{
  "name": "pat_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591270780,
      "name": "pat_disable",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:72",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/mm/pat/memtype.c:pat_init",
        "arch/x86/mm/pat/memtype.c:pat_init",
        "arch/x86/mm/pat/memtype.c:nopat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591270780,
      "name": "pat_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579433328,
      "name": "pat_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pat_disable(const char * msg_reason)
```

```json
{
  "name": "pat_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591213465,
      "name": "pat_disable",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:72",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/mm/pat/memtype.c:pat_init",
        "arch/x86/mm/pat/memtype.c:pat_init",
        "arch/x86/mm/pat/memtype.c:nopat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591213465,
      "name": "pat_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579436144,
      "name": "pat_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void pat_disable(const char * msg_reason)
```

```json
{
  "name": "pat_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579500164,
      "name": "pat_disable",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:72",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/mm/pat/memtype.c:pat_init",
        "arch/x86/mm/pat/memtype.c:pat_init",
        "arch/x86/mm/pat/memtype.c:nopat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592088732,
      "name": "pat_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071579500128,
      "name": "pat_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void pat_disable(const char * msg_reason)
```

```json
{
  "name": "pat_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579581895,
      "name": "pat_disable",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:73",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/mm/pat/memtype.c:pat_init",
        "arch/x86/mm/pat/memtype.c:pat_init",
        "arch/x86/mm/pat/memtype.c:nopat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593855674,
      "name": "pat_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071579581856,
      "name": "pat_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pat_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627722360,
      "name": "pat_disable",
      "external": false,
      "loc": "arch/x86/mm/pat/memtype.c:71",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_bp_init",
        "arch/x86/mm/pat/memtype.c:pat_bp_init",
        "arch/x86/mm/pat/memtype.c:nopat"
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
  "name": "pat_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619479960,
      "name": "pat_disable",
      "external": false,
      "loc": "arch/x86/mm/pat/memtype.c:71",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_bp_init",
        "arch/x86/mm/pat/memtype.c:pat_bp_init",
        "arch/x86/mm/pat/memtype.c:nopat"
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
  "name": "pat_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621776568,
      "name": "pat_disable",
      "external": false,
      "loc": "arch/x86/mm/pat/memtype.c:71",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_bp_init",
        "arch/x86/mm/pat/memtype.c:pat_bp_init",
        "arch/x86/mm/pat/memtype.c:nopat"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pat_disable(const char * reason)
```

```json
{
  "name": "pat_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579394388,
      "name": "pat_disable",
      "external": true,
      "loc": "arch/x86/mm/pat.c:46",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:nopat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394388,
      "name": "pat_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579391216,
      "name": "pat_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pat_disable(const char * reason)
```

```json
{
  "name": "pat_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579324116,
      "name": "pat_disable",
      "external": true,
      "loc": "arch/x86/mm/pat.c:46",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:nopat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579324116,
      "name": "pat_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579320768,
      "name": "pat_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pat_disable(const char * reason)
```

```json
{
  "name": "pat_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579394308,
      "name": "pat_disable",
      "external": true,
      "loc": "arch/x86/mm/pat.c:46",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:nopat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394308,
      "name": "pat_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579391136,
      "name": "pat_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pat_disable(const char * reason)
```

```json
{
  "name": "pat_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579402836,
      "name": "pat_disable",
      "external": true,
      "loc": "arch/x86/mm/pat.c:46",
      "file": "arch/x86/mm/pat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:nopat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579402836,
      "name": "pat_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579399664,
      "name": "pat_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void pat_disable(const char * reason)
```
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char * msg_reason</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * reason</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void pat_disable(const char * msg_reason)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void pat_disable(const char * reason)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void pat_disable(const char * reason)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void pat_disable(const char * reason)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void pat_disable(const char * reason)
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
