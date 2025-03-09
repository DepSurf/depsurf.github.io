# Function: <code>find_module_sections</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_module_sections",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579929266,
      "name": "find_module_sections",
      "external": false,
      "loc": "kernel/module.c:2883",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
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
  "name": "find_module_sections",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579959365,
      "name": "find_module_sections",
      "external": false,
      "loc": "kernel/module.c:2982",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
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
  "name": "find_module_sections",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579990262,
      "name": "find_module_sections",
      "external": false,
      "loc": "kernel/module.c:2997",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
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
  "name": "find_module_sections",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579995846,
      "name": "find_module_sections",
      "external": false,
      "loc": "kernel/module.c:3040",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
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
  "name": "find_module_sections",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580042354,
      "name": "find_module_sections",
      "external": false,
      "loc": "kernel/module.c:3060",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
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
  "name": "find_module_sections",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580101032,
      "name": "find_module_sections",
      "external": false,
      "loc": "kernel/module.c:3083",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
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
  "name": "find_module_sections",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580148417,
      "name": "find_module_sections",
      "external": false,
      "loc": "kernel/module.c:3077",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int find_module_sections(struct module * mod, struct load_info * info)
```

```json
{
  "name": "find_module_sections",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_module_sections",
      "external": false,
      "loc": "kernel/module.c:3085",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580175376,
      "name": "find_module_sections",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1292
    },
    {
      "addr": 18446744071580201270,
      "name": "find_module_sections.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int find_module_sections(struct module * mod, struct load_info * info)
```

```json
{
  "name": "find_module_sections",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_module_sections",
      "external": false,
      "loc": "kernel/module.c:3152",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580223232,
      "name": "find_module_sections",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1326
    },
    {
      "addr": 18446744071580249528,
      "name": "find_module_sections.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int find_module_sections(struct module * mod, struct load_info * info)
```

```json
{
  "name": "find_module_sections",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_module_sections",
      "external": false,
      "loc": "kernel/module.c:3152",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580307328,
      "name": "find_module_sections",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1485
    },
    {
      "addr": 18446744071580318693,
      "name": "find_module_sections.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
int find_module_sections(struct module * mod, struct load_info * info)
```

```json
{
  "name": "find_module_sections",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_module_sections",
      "external": false,
      "loc": "kernel/module.c:3331",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580292640,
      "name": "find_module_sections",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1693
    },
    {
      "addr": 18446744071591313882,
      "name": "find_module_sections.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
int find_module_sections(struct module * mod, struct load_info * info)
```

```json
{
  "name": "find_module_sections",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_module_sections",
      "external": false,
      "loc": "kernel/module.c:3250",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580295584,
      "name": "find_module_sections",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1403
    },
    {
      "addr": 18446744071591256191,
      "name": "find_module_sections.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
int find_module_sections(struct module * mod, struct load_info * info)
```

```json
{
  "name": "find_module_sections",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_module_sections",
      "external": false,
      "loc": "kernel/module.c:3272",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580448432,
      "name": "find_module_sections",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1403
    },
    {
      "addr": 18446744071592159239,
      "name": "find_module_sections.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
int find_module_sections(struct module * mod, struct load_info * info)
```

```json
{
  "name": "find_module_sections",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_module_sections",
      "external": false,
      "loc": "kernel/module/main.c:1994",
      "file": "kernel/module/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580469680,
      "name": "find_module_sections",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1376
    },
    {
      "addr": 18446744071593924305,
      "name": "find_module_sections.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
int find_module_sections(struct module * mod, struct load_info * info)
```

```json
{
  "name": "find_module_sections",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580717728,
      "name": "find_module_sections",
      "external": false,
      "loc": "kernel/module/main.c:2004",
      "file": "kernel/module/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580717728,
      "name": "find_module_sections",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1614
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
int find_module_sections(struct module * mod, struct load_info * info)
```

```json
{
  "name": "find_module_sections",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580795568,
      "name": "find_module_sections",
      "external": false,
      "loc": "kernel/module/main.c:2094",
      "file": "kernel/module/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580795568,
      "name": "find_module_sections",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1642
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
int find_module_sections(struct module * mod, struct load_info * info)
```

```json
{
  "name": "find_module_sections",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580885248,
      "name": "find_module_sections",
      "external": false,
      "loc": "kernel/module/main.c:2102",
      "file": "kernel/module/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580885248,
      "name": "find_module_sections",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1642
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int find_module_sections(struct module * mod, struct load_info * info)
```

```json
{
  "name": "find_module_sections",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491463968,
      "name": "find_module_sections",
      "external": false,
      "loc": "kernel/module.c:3152",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491463968,
      "name": "find_module_sections",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1296
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int find_module_sections(struct module * mod, struct load_info * info)
```

```json
{
  "name": "find_module_sections",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225447776,
      "name": "find_module_sections",
      "external": false,
      "loc": "kernel/module.c:3152",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225447776,
      "name": "find_module_sections",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int find_module_sections(struct module * mod, struct load_info * info)
```

```json
{
  "name": "find_module_sections",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284411904,
      "name": "find_module_sections",
      "external": false,
      "loc": "kernel/module.c:3152",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284411904,
      "name": "find_module_sections",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1456
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int find_module_sections(struct module * mod, struct load_info * info)
```

```json
{
  "name": "find_module_sections",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271915848,
      "name": "find_module_sections",
      "external": false,
      "loc": "kernel/module.c:3152",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271915848,
      "name": "find_module_sections",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 922
    }
  ]
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
int find_module_sections(struct module * mod, struct load_info * info)
```

```json
{
  "name": "find_module_sections",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_module_sections",
      "external": false,
      "loc": "kernel/module.c:3152",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580192032,
      "name": "find_module_sections",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1326
    },
    {
      "addr": 18446744071580218328,
      "name": "find_module_sections.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int find_module_sections(struct module * mod, struct load_info * info)
```

```json
{
  "name": "find_module_sections",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_module_sections",
      "external": false,
      "loc": "kernel/module.c:3152",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580139472,
      "name": "find_module_sections",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1326
    },
    {
      "addr": 18446744071580165768,
      "name": "find_module_sections.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int find_module_sections(struct module * mod, struct load_info * info)
```

```json
{
  "name": "find_module_sections",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_module_sections",
      "external": false,
      "loc": "kernel/module.c:3152",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580183504,
      "name": "find_module_sections",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1326
    },
    {
      "addr": 18446744071580209800,
      "name": "find_module_sections.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int find_module_sections(struct module * mod, struct load_info * info)
```

```json
{
  "name": "find_module_sections",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_module_sections",
      "external": false,
      "loc": "kernel/module.c:3152",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580235744,
      "name": "find_module_sections",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1326
    },
    {
      "addr": 18446744071580262479,
      "name": "find_module_sections.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int find_module_sections(struct module * mod, struct load_info * info)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
