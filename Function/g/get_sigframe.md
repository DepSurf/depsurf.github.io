# Function: <code>get_sigframe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_sigframe",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579033808,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:202",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "arch/x86/kernel/signal.c:do_signal"
      ]
    },
    {
      "addr": 18446744071579336992,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/ia32/ia32_signal.c:214",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/ia32_signal.c:ia32_setup_frame",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579033808,
      "name": "get_sigframe.isra.8.constprop.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
    },
    {
      "addr": 18446744071579336992,
      "name": "get_sigframe.isra.3.constprop.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
  "name": "get_sigframe",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579029904,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:237",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "arch/x86/kernel/signal.c:do_signal"
      ]
    },
    {
      "addr": 18446744071579342336,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/ia32/ia32_signal.c:214",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579029904,
      "name": "get_sigframe.isra.12.constprop.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
    },
    {
      "addr": 18446744071579342336,
      "name": "get_sigframe.isra.5.constprop.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_sigframe",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579029552,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:238",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "arch/x86/kernel/signal.c:do_signal"
      ]
    },
    {
      "addr": 18446744071579358192,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/ia32/ia32_signal.c:214",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579029552,
      "name": "get_sigframe.isra.13.constprop.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
    },
    {
      "addr": 18446744071579358192,
      "name": "get_sigframe.isra.4.constprop.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_sigframe",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579021968,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:239",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "arch/x86/kernel/signal.c:do_signal"
      ]
    },
    {
      "addr": 18446744071579352048,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/ia32/ia32_signal.c:215",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579021968,
      "name": "get_sigframe.isra.13.constprop.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
    },
    {
      "addr": 18446744071579352048,
      "name": "get_sigframe.isra.4.constprop.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_sigframe",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579025344,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:240",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "arch/x86/kernel/signal.c:do_signal"
      ]
    },
    {
      "addr": 18446744071579378416,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/ia32/ia32_signal.c:216",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579025344,
      "name": "get_sigframe.isra.13.constprop.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
    },
    {
      "addr": 18446744071579378416,
      "name": "get_sigframe.isra.4.constprop.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_sigframe",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579030160,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:241",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "arch/x86/kernel/signal.c:do_signal"
      ]
    },
    {
      "addr": 18446744071579392432,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/ia32/ia32_signal.c:215",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579030160,
      "name": "get_sigframe.isra.13.constprop.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
    },
    {
      "addr": 18446744071579392432,
      "name": "get_sigframe.isra.4.constprop.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_sigframe",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579034848,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:241",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "arch/x86/kernel/signal.c:do_signal"
      ]
    },
    {
      "addr": 18446744071579420448,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/ia32/ia32_signal.c:215",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579034848,
      "name": "get_sigframe.isra.13.constprop.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
    },
    {
      "addr": 18446744071579420448,
      "name": "get_sigframe.isra.4.constprop.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
  "name": "get_sigframe",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579042368,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:240",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:x32_setup_rt_frame",
        "arch/x86/kernel/signal.c:__setup_rt_frame"
      ]
    },
    {
      "addr": 18446744071579436160,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/ia32/ia32_signal.c:220",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579042368,
      "name": "get_sigframe.isra.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
    },
    {
      "addr": 18446744071579436160,
      "name": "get_sigframe.isra.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_sigframe",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579044736,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:240",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "arch/x86/kernel/signal.c:do_signal"
      ]
    },
    {
      "addr": 18446744071579439072,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/ia32/ia32_signal.c:221",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579044736,
      "name": "get_sigframe.isra.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
    },
    {
      "addr": 18446744071579439072,
      "name": "get_sigframe.isra.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
  "name": "get_sigframe",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579054240,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:232",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:x32_setup_rt_frame",
        "arch/x86/kernel/signal.c:__setup_rt_frame"
      ]
    },
    {
      "addr": 18446744071579462640,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/ia32/ia32_signal.c:203",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579054240,
      "name": "get_sigframe.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
    },
    {
      "addr": 18446744071579462640,
      "name": "get_sigframe.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
  "name": "get_sigframe",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579056880,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:233",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:x32_setup_rt_frame",
        "arch/x86/kernel/signal.c:__setup_rt_frame"
      ]
    },
    {
      "addr": 18446744071579459120,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/ia32/ia32_signal.c:203",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579056880,
      "name": "get_sigframe.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
    },
    {
      "addr": 18446744071579459120,
      "name": "get_sigframe.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
  "name": "get_sigframe",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:233",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:x32_setup_rt_frame",
        "arch/x86/kernel/signal.c:__setup_rt_frame"
      ]
    },
    {
      "addr": 18446744071579461456,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/ia32/ia32_signal.c:203",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579063856,
      "name": "get_sigframe.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    },
    {
      "addr": 18446744071591188003,
      "name": "get_sigframe.constprop.0.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071579461456,
      "name": "get_sigframe.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_sigframe",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:238",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:x32_setup_rt_frame",
        "arch/x86/kernel/signal.c:__setup_rt_frame"
      ]
    },
    {
      "addr": 18446744071579526896,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/ia32/ia32_signal.c:203",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579085072,
      "name": "get_sigframe.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    },
    {
      "addr": 18446744071592051258,
      "name": "get_sigframe.constprop.0.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071579526896,
      "name": "get_sigframe.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_sigframe",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:241",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:__setup_rt_frame"
      ]
    },
    {
      "addr": 18446744071579613568,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/ia32/ia32_signal.c:202",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579114368,
      "name": "get_sigframe.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
    },
    {
      "addr": 18446744071593817813,
      "name": "get_sigframe.constprop.0.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071579613568,
      "name": "get_sigframe.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
void * get_sigframe(struct ksignal * ksig, struct pt_regs * regs, size_t frame_size, void * * fpstate)
```

```json
{
  "name": "get_sigframe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579153072,
      "name": "get_sigframe",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:74",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal_64.c:x64_setup_rt_frame",
        "arch/x86/kernel/signal_32.c:ia32_setup_rt_frame",
        "arch/x86/kernel/signal_32.c:ia32_setup_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579153072,
      "name": "get_sigframe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 702
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
void * get_sigframe(struct ksignal * ksig, struct pt_regs * regs, size_t frame_size, void * * fpstate)
```

```json
{
  "name": "get_sigframe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579155280,
      "name": "get_sigframe",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:74",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal_64.c:x64_setup_rt_frame",
        "arch/x86/kernel/signal_32.c:ia32_setup_rt_frame",
        "arch/x86/kernel/signal_32.c:ia32_setup_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579155280,
      "name": "get_sigframe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 686
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
void * get_sigframe(struct ksignal * ksig, struct pt_regs * regs, size_t frame_size, void * * fpstate)
```

```json
{
  "name": "get_sigframe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579184592,
      "name": "get_sigframe",
      "external": true,
      "loc": "arch/x86/kernel/signal.c:76",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal_64.c:x64_setup_rt_frame",
        "arch/x86/kernel/signal_32.c:ia32_setup_rt_frame",
        "arch/x86/kernel/signal_32.c:ia32_setup_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579184592,
      "name": "get_sigframe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 686
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
  "name": "get_sigframe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490228368,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/arm64/kernel/signal.c:695",
      "file": "arch/arm64/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/signal.c:setup_rt_frame"
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
  "name": "get_sigframe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224431112,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/arm/kernel/signal.c:342",
      "file": "arch/arm/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/signal.c:do_work_pending",
        "arch/arm/kernel/signal.c:do_work_pending"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * get_sigframe(struct ksignal * ksig, long unsigned int sp, size_t frame_size, int is_32)
```

```json
{
  "name": "get_sigframe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282308608,
      "name": "get_sigframe",
      "external": true,
      "loc": "arch/powerpc/kernel/signal.c:36",
      "file": "arch/powerpc/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/signal_32.c:handle_signal32",
        "arch/powerpc/kernel/signal_32.c:handle_rt_signal32",
        "arch/powerpc/kernel/signal_64.c:handle_rt_signal64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282308608,
      "name": "get_sigframe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "get_sigframe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271345172,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/riscv/kernel/signal.c:146",
      "file": "arch/riscv/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/kernel/signal.c:handle_signal"
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
  "name": "get_sigframe",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579045088,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:240",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "arch/x86/kernel/signal.c:do_signal"
      ]
    },
    {
      "addr": 18446744071579434912,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/ia32/ia32_signal.c:221",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579045088,
      "name": "get_sigframe.isra.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
    },
    {
      "addr": 18446744071579434912,
      "name": "get_sigframe.isra.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_sigframe",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578978048,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:240",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "arch/x86/kernel/signal.c:do_signal"
      ]
    },
    {
      "addr": 18446744071579364016,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/ia32/ia32_signal.c:221",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578978048,
      "name": "get_sigframe.isra.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
    },
    {
      "addr": 18446744071579364016,
      "name": "get_sigframe.isra.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_sigframe",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579044672,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:240",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "arch/x86/kernel/signal.c:do_signal"
      ]
    },
    {
      "addr": 18446744071579434832,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/ia32/ia32_signal.c:221",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579044672,
      "name": "get_sigframe.isra.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
    },
    {
      "addr": 18446744071579434832,
      "name": "get_sigframe.isra.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_sigframe",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579048400,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:240",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "arch/x86/kernel/signal.c:do_signal"
      ]
    },
    {
      "addr": 18446744071579444016,
      "name": "get_sigframe",
      "external": false,
      "loc": "arch/x86/ia32/ia32_signal.c:221",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame",
        "arch/x86/ia32/ia32_signal.c:ia32_setup_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579048400,
      "name": "get_sigframe.isra.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
    },
    {
      "addr": 18446744071579444016,
      "name": "get_sigframe.isra.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void * get_sigframe(struct ksignal * ksig, struct pt_regs * regs, size_t frame_size, void * * fpstate)
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void * get_sigframe(struct ksignal * ksig, long unsigned int sp, size_t frame_size, int is_32)
```
</details>
</li>
</ul>
