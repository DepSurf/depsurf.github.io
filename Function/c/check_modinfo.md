# Function: <code>check_modinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579925808,
      "name": "check_modinfo",
      "external": false,
      "loc": "kernel/module.c:2849",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:layout_and_allocate"
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
  "name": "check_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579955563,
      "name": "check_modinfo",
      "external": false,
      "loc": "kernel/module.c:2940",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:layout_and_allocate"
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
  "name": "check_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579986456,
      "name": "check_modinfo",
      "external": false,
      "loc": "kernel/module.c:2955",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:layout_and_allocate"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579991948,
      "name": "check_modinfo",
      "external": false,
      "loc": "kernel/module.c:2998",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:layout_and_allocate"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580038508,
      "name": "check_modinfo",
      "external": false,
      "loc": "kernel/module.c:3016",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:layout_and_allocate"
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
  "name": "check_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580097186,
      "name": "check_modinfo",
      "external": false,
      "loc": "kernel/module.c:3039",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:layout_and_allocate"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580143863,
      "name": "check_modinfo",
      "external": false,
      "loc": "kernel/module.c:3033",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:layout_and_allocate"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580190855,
      "name": "check_modinfo",
      "external": false,
      "loc": "kernel/module.c:3041",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:layout_and_allocate"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int check_modinfo(struct module * mod, struct load_info * info, int flags)
```

```json
{
  "name": "check_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_modinfo",
      "external": false,
      "loc": "kernel/module.c:3108",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:layout_and_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580232464,
      "name": "check_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 561
    },
    {
      "addr": 18446744071580249614,
      "name": "check_modinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int check_modinfo(struct module * mod, struct load_info * info, int flags)
```

```json
{
  "name": "check_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_modinfo",
      "external": false,
      "loc": "kernel/module.c:3108",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:layout_and_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580302688,
      "name": "check_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
    },
    {
      "addr": 18446744071580318526,
      "name": "check_modinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
int check_modinfo(struct module * mod, struct load_info * info, int flags)
```

```json
{
  "name": "check_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_modinfo",
      "external": false,
      "loc": "kernel/module.c:3287",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:layout_and_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580289248,
      "name": "check_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071591313703,
      "name": "check_modinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
int check_modinfo(struct module * mod, struct load_info * info, int flags)
```

```json
{
  "name": "check_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_modinfo",
      "external": false,
      "loc": "kernel/module.c:3206",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:layout_and_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580289824,
      "name": "check_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
    },
    {
      "addr": 18446744071591255855,
      "name": "check_modinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
int check_modinfo(struct module * mod, struct load_info * info, int flags)
```

```json
{
  "name": "check_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_modinfo",
      "external": false,
      "loc": "kernel/module.c:3228",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:layout_and_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580441824,
      "name": "check_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 629
    },
    {
      "addr": 18446744071592158789,
      "name": "check_modinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int check_modinfo(struct module * mod, struct load_info * info, int flags)
```

```json
{
  "name": "check_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_modinfo",
      "external": false,
      "loc": "kernel/module/main.c:1950",
      "file": "kernel/module/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:layout_and_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580467312,
      "name": "check_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
    },
    {
      "addr": 18446744071593924079,
      "name": "check_modinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int check_modinfo(struct module * mod, struct load_info * info, int flags)
```

```json
{
  "name": "check_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_modinfo",
      "external": false,
      "loc": "kernel/module/main.c:1953",
      "file": "kernel/module/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:layout_and_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580715120,
      "name": "check_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 806
    },
    {
      "addr": 18446744071595993876,
      "name": "check_modinfo.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580801274,
      "name": "check_modinfo",
      "external": false,
      "loc": "kernel/module/main.c:2068",
      "file": "kernel/module/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module/main.c:early_mod_check"
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
  "name": "check_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580890618,
      "name": "check_modinfo",
      "external": false,
      "loc": "kernel/module/main.c:2076",
      "file": "kernel/module/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module/main.c:early_mod_check"
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
  "name": "check_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491481452,
      "name": "check_modinfo",
      "external": false,
      "loc": "kernel/module.c:3108",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:layout_and_allocate"
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
  "name": "check_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225463572,
      "name": "check_modinfo",
      "external": false,
      "loc": "kernel/module.c:3108",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:layout_and_allocate"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "check_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284433144,
      "name": "check_modinfo",
      "external": false,
      "loc": "kernel/module.c:3108",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:layout_and_allocate"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "check_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271927222,
      "name": "check_modinfo",
      "external": false,
      "loc": "kernel/module.c:3108",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:layout_and_allocate"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int check_modinfo(struct module * mod, struct load_info * info, int flags)
```

```json
{
  "name": "check_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_modinfo",
      "external": false,
      "loc": "kernel/module.c:3108",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:layout_and_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580201264,
      "name": "check_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 561
    },
    {
      "addr": 18446744071580218414,
      "name": "check_modinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int check_modinfo(struct module * mod, struct load_info * info, int flags)
```

```json
{
  "name": "check_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_modinfo",
      "external": false,
      "loc": "kernel/module.c:3108",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:layout_and_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580148704,
      "name": "check_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 561
    },
    {
      "addr": 18446744071580165854,
      "name": "check_modinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int check_modinfo(struct module * mod, struct load_info * info, int flags)
```

```json
{
  "name": "check_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_modinfo",
      "external": false,
      "loc": "kernel/module.c:3108",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:layout_and_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580192736,
      "name": "check_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 561
    },
    {
      "addr": 18446744071580209886,
      "name": "check_modinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int check_modinfo(struct module * mod, struct load_info * info, int flags)
```

```json
{
  "name": "check_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_modinfo",
      "external": false,
      "loc": "kernel/module.c:3108",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:layout_and_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580245152,
      "name": "check_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 561
    },
    {
      "addr": 18446744071580262565,
      "name": "check_modinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int check_modinfo(struct module * mod, struct load_info * info, int flags)
```
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int check_modinfo(struct module * mod, struct load_info * info, int flags)
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
int check_modinfo(struct module * mod, struct load_info * info, int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int check_modinfo(struct module * mod, struct load_info * info, int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int check_modinfo(struct module * mod, struct load_info * info, int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int check_modinfo(struct module * mod, struct load_info * info, int flags)
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
