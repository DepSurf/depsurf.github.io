# Function: <code>klp_start_transition</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void klp_start_transition()
```

```json
{
  "name": "klp_start_transition",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579865088,
      "name": "klp_start_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:422",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:__klp_disable_patch",
        "kernel/livepatch/transition.c:klp_reverse_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579865088,
      "name": "klp_start_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
void klp_start_transition()
```

```json
{
  "name": "klp_start_transition",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579908608,
      "name": "klp_start_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:444",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:__klp_disable_patch",
        "kernel/livepatch/transition.c:klp_reverse_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908608,
      "name": "klp_start_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void klp_start_transition()
```

```json
{
  "name": "klp_start_transition",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_start_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:424",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:__klp_disable_patch",
        "kernel/livepatch/transition.c:klp_reverse_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579943687,
      "name": "klp_start_transition.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    },
    {
      "addr": 18446744071579942784,
      "name": "klp_start_transition",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void klp_start_transition()
```

```json
{
  "name": "klp_start_transition",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579990841,
      "name": "klp_start_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:417",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:__klp_disable_patch",
        "kernel/livepatch/transition.c:klp_reverse_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579990775,
      "name": "klp_start_transition.cold.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    },
    {
      "addr": 18446744071579989872,
      "name": "klp_start_transition",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void klp_start_transition()
```

```json
{
  "name": "klp_start_transition",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580032866,
      "name": "klp_start_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:463",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_reverse_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580032807,
      "name": "klp_start_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071580031904,
      "name": "klp_start_transition",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void klp_start_transition()
```

```json
{
  "name": "klp_start_transition",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580083586,
      "name": "klp_start_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:463",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_reverse_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580083527,
      "name": "klp_start_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071580082624,
      "name": "klp_start_transition",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void klp_start_transition()
```

```json
{
  "name": "klp_start_transition",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580143078,
      "name": "klp_start_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:463",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:__klp_enable_patch",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_reverse_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580143078,
      "name": "klp_start_transition.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
    },
    {
      "addr": 18446744071580143375,
      "name": "klp_start_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071580142256,
      "name": "klp_start_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void klp_start_transition()
```

```json
{
  "name": "klp_start_transition",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591310225,
      "name": "klp_start_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:463",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:__klp_enable_patch",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_reverse_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591310225,
      "name": "klp_start_transition.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
    },
    {
      "addr": 18446744071591310522,
      "name": "klp_start_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071580119488,
      "name": "klp_start_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void klp_start_transition()
```

```json
{
  "name": "klp_start_transition",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591252730,
      "name": "klp_start_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:462",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_reverse_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591252664,
      "name": "klp_start_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071580122992,
      "name": "klp_start_transition",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void klp_start_transition()
```

```json
{
  "name": "klp_start_transition",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580266427,
      "name": "klp_start_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:462",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_reverse_transition"
      ],
      "caller_func": [
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_reverse_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592148972,
      "name": "klp_start_transition.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
    },
    {
      "addr": 18446744071592149359,
      "name": "klp_start_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071580265696,
      "name": "klp_start_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void klp_start_transition()
```

```json
{
  "name": "klp_start_transition",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580436672,
      "name": "klp_start_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:462",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_reverse_transition"
      ],
      "caller_func": [
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_reverse_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593921539,
      "name": "klp_start_transition.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071593921956,
      "name": "klp_start_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071580435920,
      "name": "klp_start_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void klp_start_transition()
```

```json
{
  "name": "klp_start_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580678320,
      "name": "klp_start_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:462",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_reverse_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580678320,
      "name": "klp_start_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
void klp_start_transition()
```

```json
{
  "name": "klp_start_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580754832,
      "name": "klp_start_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:530",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_reverse_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580754832,
      "name": "klp_start_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
void klp_start_transition()
```

```json
{
  "name": "klp_start_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580839952,
      "name": "klp_start_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:530",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_reverse_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580839952,
      "name": "klp_start_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void klp_start_transition()
```

```json
{
  "name": "klp_start_transition",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284208528,
      "name": "klp_start_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:463",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_reverse_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284208528,
      "name": "klp_start_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
    }
  ]
}
```
</details>
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
void klp_start_transition()
```

```json
{
  "name": "klp_start_transition",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580052322,
      "name": "klp_start_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:463",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_reverse_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580052263,
      "name": "klp_start_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071580051360,
      "name": "klp_start_transition",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void klp_start_transition()
```

```json
{
  "name": "klp_start_transition",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579997634,
      "name": "klp_start_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:463",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_reverse_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579997575,
      "name": "klp_start_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071579996672,
      "name": "klp_start_transition",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void klp_start_transition()
```

```json
{
  "name": "klp_start_transition",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580043858,
      "name": "klp_start_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:463",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_reverse_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580043799,
      "name": "klp_start_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071580042896,
      "name": "klp_start_transition",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void klp_start_transition()
```

```json
{
  "name": "klp_start_transition",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580094626,
      "name": "klp_start_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:463",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_reverse_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094567,
      "name": "klp_start_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 18446744071580093664,
      "name": "klp_start_transition",
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void klp_start_transition()
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
void klp_start_transition()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void klp_start_transition()
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void klp_start_transition()
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
