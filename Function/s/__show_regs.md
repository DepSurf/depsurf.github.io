# Function: <code>__show_regs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __show_regs(struct pt_regs * regs, int all)
```

```json
{
  "name": "__show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579029856,
      "name": "__show_regs",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:57",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:show_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579029856,
      "name": "__show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 653
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
void __show_regs(struct pt_regs * regs, int all)
```

```json
{
  "name": "__show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579025760,
      "name": "__show_regs",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:58",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:show_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579025760,
      "name": "__show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 665
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
void __show_regs(struct pt_regs * regs, int all)
```

```json
{
  "name": "__show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579025712,
      "name": "__show_regs",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:57",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:show_regs",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579025712,
      "name": "__show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 694
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
void __show_regs(struct pt_regs * regs, int all)
```

```json
{
  "name": "__show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579018016,
      "name": "__show_regs",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:65",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:show_regs",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579018016,
      "name": "__show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 694
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
void __show_regs(struct pt_regs * regs, int all)
```

```json
{
  "name": "__show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579021520,
      "name": "__show_regs",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:65",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:show_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579021520,
      "name": "__show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 615
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void __show_regs(struct pt_regs * regs, enum show_regs_mode mode)
```

```json
{
  "name": "__show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__show_regs",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:65",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579029094,
      "name": "__show_regs.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
    },
    {
      "addr": 18446744071579026272,
      "name": "__show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void __show_regs(struct pt_regs * regs, enum show_regs_mode mode)
```

```json
{
  "name": "__show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__show_regs",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:66",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579033782,
      "name": "__show_regs.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
    },
    {
      "addr": 18446744071579030752,
      "name": "__show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __show_regs(struct pt_regs * regs, enum show_regs_mode mode)
```

```json
{
  "name": "__show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__show_regs",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:67",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579041302,
      "name": "__show_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
    },
    {
      "addr": 18446744071579038416,
      "name": "__show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __show_regs(struct pt_regs * regs, enum show_regs_mode mode)
```

```json
{
  "name": "__show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__show_regs",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:67",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579043702,
      "name": "__show_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
    },
    {
      "addr": 18446744071579040816,
      "name": "__show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __show_regs(struct pt_regs * regs, enum show_regs_mode mode)
```

```json
{
  "name": "__show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__show_regs",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:65",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:__die_body",
        "arch/x86/kernel/dumpstack.c:oops_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579053478,
      "name": "__show_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
    },
    {
      "addr": 18446744071579051216,
      "name": "__show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __show_regs(struct pt_regs * regs, enum show_regs_mode mode, const char * log_lvl)
```

```json
{
  "name": "__show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__show_regs",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:65",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:__die_body",
        "arch/x86/kernel/dumpstack.c:oops_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591243695,
      "name": "__show_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 647
    },
    {
      "addr": 18446744071579054032,
      "name": "__show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void __show_regs(struct pt_regs * regs, enum show_regs_mode mode, const char * log_lvl)
```

```json
{
  "name": "__show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__show_regs",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:65",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:__die_body",
        "arch/x86/kernel/dumpstack.c:oops_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591187359,
      "name": "__show_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 644
    },
    {
      "addr": 18446744071579060832,
      "name": "__show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void __show_regs(struct pt_regs * regs, enum show_regs_mode mode, const char * log_lvl)
```

```json
{
  "name": "__show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__show_regs",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:66",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:__die_body",
        "arch/x86/kernel/dumpstack.c:oops_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592050623,
      "name": "__show_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 635
    },
    {
      "addr": 18446744071579082080,
      "name": "__show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void __show_regs(struct pt_regs * regs, enum show_regs_mode mode, const char * log_lvl)
```

```json
{
  "name": "__show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__show_regs",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:66",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:__die_body",
        "arch/x86/kernel/dumpstack.c:oops_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593817141,
      "name": "__show_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
    },
    {
      "addr": 18446744071579110656,
      "name": "__show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void __show_regs(struct pt_regs * regs, enum show_regs_mode mode, const char * log_lvl)
```

```json
{
  "name": "__show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579148464,
      "name": "__show_regs",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:66",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579148464,
      "name": "__show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 830
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
void __show_regs(struct pt_regs * regs, enum show_regs_mode mode, const char * log_lvl)
```

```json
{
  "name": "__show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579150576,
      "name": "__show_regs",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:67",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579150576,
      "name": "__show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 830
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
void __show_regs(struct pt_regs * regs, enum show_regs_mode mode, const char * log_lvl)
```

```json
{
  "name": "__show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579179872,
      "name": "__show_regs",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:67",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579179872,
      "name": "__show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 830
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
void __show_regs(struct pt_regs * regs)
```

```json
{
  "name": "__show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490195288,
      "name": "__show_regs",
      "external": true,
      "loc": "arch/arm64/kernel/process.c:245",
      "file": "arch/arm64/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/process.c:show_regs",
        "arch/arm64/kernel/traps.c:arm64_serror_panic",
        "arch/arm64/kernel/traps.c:handle_bad_stack",
        "arch/arm64/kernel/traps.c:arm64_show_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490195288,
      "name": "__show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 728
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
void __show_regs(struct pt_regs * regs)
```

```json
{
  "name": "__show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224416212,
      "name": "__show_regs",
      "external": true,
      "loc": "arch/arm/kernel/process.c:93",
      "file": "arch/arm/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/process.c:show_regs",
        "arch/arm/kernel/traps.c:die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224416212,
      "name": "__show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
    }
  ]
}
```
</details>
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
void __show_regs(struct pt_regs * regs, enum show_regs_mode mode)
```

```json
{
  "name": "__show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__show_regs",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:67",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579044054,
      "name": "__show_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
    },
    {
      "addr": 18446744071579041168,
      "name": "__show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __show_regs(struct pt_regs * regs, enum show_regs_mode mode)
```

```json
{
  "name": "__show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__show_regs",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:67",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578977126,
      "name": "__show_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
    },
    {
      "addr": 18446744071578974128,
      "name": "__show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __show_regs(struct pt_regs * regs, enum show_regs_mode mode)
```

```json
{
  "name": "__show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__show_regs",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:67",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579043638,
      "name": "__show_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
    },
    {
      "addr": 18446744071579040752,
      "name": "__show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __show_regs(struct pt_regs * regs, enum show_regs_mode mode)
```

```json
{
  "name": "__show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__show_regs",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:67",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579047366,
      "name": "__show_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
    },
    {
      "addr": 18446744071579044416,
      "name": "__show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum show_regs_mode mode</code>
</li>
<li>
<b>Param removed. </b>
<code>int all</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char * log_lvl</code>
</li>
</ul>
</details>
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>enum show_regs_mode mode</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>enum show_regs_mode mode</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __show_regs(struct pt_regs * regs, enum show_regs_mode mode)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __show_regs(struct pt_regs * regs, enum show_regs_mode mode)
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
