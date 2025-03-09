# Function: <code>module_enable_ro</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void module_enable_ro(const struct module * mod)
```

```json
{
  "name": "module_enable_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579923408,
      "name": "module_enable_ro",
      "external": true,
      "loc": "kernel/module.c:1902",
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
      "addr": 18446744071579923408,
      "name": "module_enable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void module_enable_ro(const struct module * mod, bool after_init)
```

```json
{
  "name": "module_enable_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579953280,
      "name": "module_enable_ro",
      "external": true,
      "loc": "kernel/module.c:1918",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_write_object_relocations",
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579953280,
      "name": "module_enable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void module_enable_ro(const struct module * mod, bool after_init)
```

```json
{
  "name": "module_enable_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579994337,
      "name": "module_enable_ro",
      "external": true,
      "loc": "kernel/module.c:1913",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579981984,
      "name": "module_enable_ro.part.59",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071579984384,
      "name": "module_enable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void module_enable_ro(const struct module * mod, bool after_init)
```

```json
{
  "name": "module_enable_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579999778,
      "name": "module_enable_ro",
      "external": true,
      "loc": "kernel/module.c:1940",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579986048,
      "name": "module_enable_ro.part.55",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071579989696,
      "name": "module_enable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void module_enable_ro(const struct module * mod, bool after_init)
```

```json
{
  "name": "module_enable_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580046294,
      "name": "module_enable_ro",
      "external": true,
      "loc": "kernel/module.c:1948",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580032640,
      "name": "module_enable_ro.part.56",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071580036256,
      "name": "module_enable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void module_enable_ro(const struct module * mod, bool after_init)
```

```json
{
  "name": "module_enable_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580104608,
      "name": "module_enable_ro",
      "external": true,
      "loc": "kernel/module.c:1947",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580088688,
      "name": "module_enable_ro.part.61",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071580093760,
      "name": "module_enable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void module_enable_ro(const struct module * mod, bool after_init)
```

```json
{
  "name": "module_enable_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580152092,
      "name": "module_enable_ro",
      "external": true,
      "loc": "kernel/module.c:1948",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580135584,
      "name": "module_enable_ro.part.63",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071580141040,
      "name": "module_enable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void module_enable_ro(const struct module * mod, bool after_init)
```

```json
{
  "name": "module_enable_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580198184,
      "name": "module_enable_ro",
      "external": true,
      "loc": "kernel/module.c:1956",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580182096,
      "name": "module_enable_ro.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    },
    {
      "addr": 18446744071580187840,
      "name": "module_enable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void module_enable_ro(const struct module * mod, bool after_init)
```

```json
{
  "name": "module_enable_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580246412,
      "name": "module_enable_ro",
      "external": true,
      "loc": "kernel/module.c:2013",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580230192,
      "name": "module_enable_ro.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    },
    {
      "addr": 18446744071580236544,
      "name": "module_enable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "module_enable_ro",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580300662,
      "name": "module_enable_ro",
      "external": false,
      "loc": "kernel/module.c:2038",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:complete_formation",
        "kernel/module.c:do_init_module"
      ],
      "caller_func": [
        "kernel/module.c:complete_formation",
        "kernel/module.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580298032,
      "name": "module_enable_ro.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "module_enable_ro",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580282486,
      "name": "module_enable_ro",
      "external": false,
      "loc": "kernel/module.c:2097",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:complete_formation",
        "kernel/module.c:do_init_module"
      ],
      "caller_func": [
        "kernel/module.c:complete_formation",
        "kernel/module.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580282224,
      "name": "module_enable_ro.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "module_enable_ro",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580285867,
      "name": "module_enable_ro",
      "external": false,
      "loc": "kernel/module.c:2007",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:complete_formation",
        "kernel/module.c:do_init_module"
      ],
      "caller_func": [
        "kernel/module.c:complete_formation",
        "kernel/module.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580285408,
      "name": "module_enable_ro.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
void module_enable_ro(const struct module * mod, bool after_init)
```

```json
{
  "name": "module_enable_ro",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580447687,
      "name": "module_enable_ro",
      "external": false,
      "loc": "kernel/module.c:2009",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:complete_formation",
        "kernel/module.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580447632,
      "name": "module_enable_ro",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 18446744071592159146,
      "name": "module_enable_ro.cold",
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
void module_enable_ro(const struct module * mod, bool after_init)
```

```json
{
  "name": "module_enable_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "module_enable_ro",
      "external": true,
      "loc": "kernel/module/strict_rwx.c:92",
      "file": "kernel/module/strict_rwx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593925456,
      "name": "module_enable_ro.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580485136,
      "name": "module_enable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
void module_enable_ro(const struct module * mod, bool after_init)
```

```json
{
  "name": "module_enable_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "module_enable_ro",
      "external": true,
      "loc": "kernel/module/strict_rwx.c:92",
      "file": "kernel/module/strict_rwx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595994073,
      "name": "module_enable_ro.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580736256,
      "name": "module_enable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
void module_enable_ro(const struct module * mod, bool after_init)
```

```json
{
  "name": "module_enable_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "module_enable_ro",
      "external": true,
      "loc": "kernel/module/strict_rwx.c:35",
      "file": "kernel/module/strict_rwx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596512379,
      "name": "module_enable_ro.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580816272,
      "name": "module_enable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
void module_enable_ro(const struct module * mod, bool after_init)
```

```json
{
  "name": "module_enable_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "module_enable_ro",
      "external": true,
      "loc": "kernel/module/strict_rwx.c:35",
      "file": "kernel/module/strict_rwx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597411580,
      "name": "module_enable_ro.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580905664,
      "name": "module_enable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void module_enable_ro(const struct module * mod, bool after_init)
```

```json
{
  "name": "module_enable_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491488448,
      "name": "module_enable_ro",
      "external": true,
      "loc": "kernel/module.c:2013",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ],
      "caller_func": [
        "arch/arm64/kernel/ftrace.c:ftrace_make_call",
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491470584,
      "name": "module_enable_ro.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 18446603336491478648,
      "name": "module_enable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void module_enable_ro(const struct module * mod, bool after_init)
```

```json
{
  "name": "module_enable_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225470528,
      "name": "module_enable_ro",
      "external": true,
      "loc": "kernel/module.c:2013",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225454004,
      "name": "module_enable_ro.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 3225460904,
      "name": "module_enable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "module_enable_ro",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "module_enable_ro",
      "external": false,
      "loc": "include/linux/module.h:856",
      "file": "kernel/livepatch/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "module_enable_ro",
      "external": false,
      "loc": "include/linux/module.h:856",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "module_enable_ro",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "module_enable_ro",
      "external": false,
      "loc": "include/linux/module.h:856",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void module_enable_ro(const struct module * mod, bool after_init)
```

```json
{
  "name": "module_enable_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580215212,
      "name": "module_enable_ro",
      "external": true,
      "loc": "kernel/module.c:2013",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580198992,
      "name": "module_enable_ro.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    },
    {
      "addr": 18446744071580205344,
      "name": "module_enable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void module_enable_ro(const struct module * mod, bool after_init)
```

```json
{
  "name": "module_enable_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580162652,
      "name": "module_enable_ro",
      "external": true,
      "loc": "kernel/module.c:2013",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146432,
      "name": "module_enable_ro.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    },
    {
      "addr": 18446744071580152784,
      "name": "module_enable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void module_enable_ro(const struct module * mod, bool after_init)
```

```json
{
  "name": "module_enable_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580206684,
      "name": "module_enable_ro",
      "external": true,
      "loc": "kernel/module.c:2013",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580190464,
      "name": "module_enable_ro.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    },
    {
      "addr": 18446744071580196816,
      "name": "module_enable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void module_enable_ro(const struct module * mod, bool after_init)
```

```json
{
  "name": "module_enable_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580259138,
      "name": "module_enable_ro",
      "external": true,
      "loc": "kernel/module.c:2013",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580242800,
      "name": "module_enable_ro.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    },
    {
      "addr": 18446744071580249264,
      "name": "module_enable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool after_init</code>
</li>
</ul>
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void module_enable_ro(const struct module * mod, bool after_init)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void module_enable_ro(const struct module * mod, bool after_init)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void module_enable_ro(const struct module * mod, bool after_init)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void module_enable_ro(const struct module * mod, bool after_init)
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
