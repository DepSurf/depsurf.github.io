# Function: <code>module_flags_taint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "module_flags_taint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579917296,
      "name": "module_flags_taint",
      "external": false,
      "loc": "kernel/module.c:1133",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:show_taint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579917296,
      "name": "module_flags_taint.isra.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "module_flags_taint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579948256,
      "name": "module_flags_taint",
      "external": false,
      "loc": "kernel/module.c:1138",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:show_taint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579948256,
      "name": "module_flags_taint.isra.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
size_t module_flags_taint(struct module * mod, char * buf)
```

```json
{
  "name": "module_flags_taint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579973616,
      "name": "module_flags_taint",
      "external": false,
      "loc": "kernel/module.c:1141",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:show_taint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579973616,
      "name": "module_flags_taint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
size_t module_flags_taint(struct module * mod, char * buf)
```

```json
{
  "name": "module_flags_taint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579978976,
      "name": "module_flags_taint",
      "external": false,
      "loc": "kernel/module.c:1163",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:show_taint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579978976,
      "name": "module_flags_taint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
size_t module_flags_taint(struct module * mod, char * buf)
```

```json
{
  "name": "module_flags_taint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580025424,
      "name": "module_flags_taint",
      "external": false,
      "loc": "kernel/module.c:1171",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:show_taint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580025424,
      "name": "module_flags_taint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
size_t module_flags_taint(struct module * mod, char * buf)
```

```json
{
  "name": "module_flags_taint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580081376,
      "name": "module_flags_taint",
      "external": false,
      "loc": "kernel/module.c:1170",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:show_taint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580081376,
      "name": "module_flags_taint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
size_t module_flags_taint(struct module * mod, char * buf)
```

```json
{
  "name": "module_flags_taint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580128720,
      "name": "module_flags_taint",
      "external": false,
      "loc": "kernel/module.c:1171",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:show_taint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580128720,
      "name": "module_flags_taint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
  "name": "module_flags_taint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580177135,
      "name": "module_flags_taint",
      "external": false,
      "loc": "kernel/module.c:1167",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:module_flags",
        "kernel/module.c:show_taint"
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
  "name": "module_flags_taint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580225023,
      "name": "module_flags_taint",
      "external": false,
      "loc": "kernel/module.c:1181",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:module_flags",
        "kernel/module.c:show_taint"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
size_t module_flags_taint(struct module * mod, char * buf)
```

```json
{
  "name": "module_flags_taint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580298896,
      "name": "module_flags_taint",
      "external": false,
      "loc": "kernel/module.c:1184",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_flags",
        "kernel/module.c:show_taint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580298896,
      "name": "module_flags_taint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
size_t module_flags_taint(struct module * mod, char * buf)
```

```json
{
  "name": "module_flags_taint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580283328,
      "name": "module_flags_taint",
      "external": false,
      "loc": "kernel/module.c:1216",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_flags",
        "kernel/module.c:show_taint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580283328,
      "name": "module_flags_taint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
size_t module_flags_taint(struct module * mod, char * buf)
```

```json
{
  "name": "module_flags_taint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580286064,
      "name": "module_flags_taint",
      "external": false,
      "loc": "kernel/module.c:1124",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_flags",
        "kernel/module.c:show_taint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580286064,
      "name": "module_flags_taint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
size_t module_flags_taint(struct module * mod, char * buf)
```

```json
{
  "name": "module_flags_taint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "module_flags_taint",
      "external": false,
      "loc": "kernel/module.c:1124",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_flags",
        "kernel/module.c:show_taint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580437920,
      "name": "module_flags_taint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    },
    {
      "addr": 18446744071592158490,
      "name": "module_flags_taint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
size_t module_flags_taint(long unsigned int taints, char * buf)
```

```json
{
  "name": "module_flags_taint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "module_flags_taint",
      "external": true,
      "loc": "kernel/module/main.c:872",
      "file": "kernel/module/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:module_flags",
        "kernel/module/main.c:show_taint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593924649,
      "name": "module_flags_taint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580474880,
      "name": "module_flags_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
size_t module_flags_taint(long unsigned int taints, char * buf)
```

```json
{
  "name": "module_flags_taint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "module_flags_taint",
      "external": true,
      "loc": "kernel/module/main.c:875",
      "file": "kernel/module/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:module_flags",
        "kernel/module/main.c:module_flags",
        "kernel/module/main.c:show_taint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595993918,
      "name": "module_flags_taint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580723616,
      "name": "module_flags_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
size_t module_flags_taint(long unsigned int taints, char * buf)
```

```json
{
  "name": "module_flags_taint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "module_flags_taint",
      "external": true,
      "loc": "kernel/module/main.c:873",
      "file": "kernel/module/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:module_flags",
        "kernel/module/main.c:module_flags",
        "kernel/module/main.c:show_taint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596512239,
      "name": "module_flags_taint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580802032,
      "name": "module_flags_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
size_t module_flags_taint(long unsigned int taints, char * buf)
```

```json
{
  "name": "module_flags_taint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "module_flags_taint",
      "external": true,
      "loc": "kernel/module/main.c:873",
      "file": "kernel/module/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:module_flags",
        "kernel/module/main.c:module_flags",
        "kernel/module/main.c:show_taint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597411440,
      "name": "module_flags_taint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580891376,
      "name": "module_flags_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "module_flags_taint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491465832,
      "name": "module_flags_taint",
      "external": false,
      "loc": "kernel/module.c:1181",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:module_flags",
        "kernel/module.c:show_taint"
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
  "name": "module_flags_taint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225449456,
      "name": "module_flags_taint",
      "external": false,
      "loc": "kernel/module.c:1181",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:module_flags",
        "kernel/module.c:show_taint"
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
  "name": "module_flags_taint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284413840,
      "name": "module_flags_taint",
      "external": false,
      "loc": "kernel/module.c:1181",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:module_flags",
        "kernel/module.c:show_taint"
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
  "name": "module_flags_taint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271917022,
      "name": "module_flags_taint",
      "external": false,
      "loc": "kernel/module.c:1181",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:module_flags",
        "kernel/module.c:show_taint"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "module_flags_taint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580193823,
      "name": "module_flags_taint",
      "external": false,
      "loc": "kernel/module.c:1181",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:module_flags",
        "kernel/module.c:show_taint"
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
  "name": "module_flags_taint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580141263,
      "name": "module_flags_taint",
      "external": false,
      "loc": "kernel/module.c:1181",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:module_flags",
        "kernel/module.c:show_taint"
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
  "name": "module_flags_taint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580185295,
      "name": "module_flags_taint",
      "external": false,
      "loc": "kernel/module.c:1181",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:module_flags",
        "kernel/module.c:show_taint"
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
  "name": "module_flags_taint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580237535,
      "name": "module_flags_taint",
      "external": false,
      "loc": "kernel/module.c:1181",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:module_flags",
        "kernel/module.c:show_taint"
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
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
size_t module_flags_taint(struct module * mod, char * buf)
```
</details>
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
size_t module_flags_taint(struct module * mod, char * buf)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
size_t module_flags_taint(struct module * mod, char * buf)
```
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int taints</code>
</li>
<li>
<b>Param removed. </b>
<code>struct module * mod</code>
</li>
</ul>
</details>
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
