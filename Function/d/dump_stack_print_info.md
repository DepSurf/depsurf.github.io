# Function: <code>dump_stack_print_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void dump_stack_print_info(const char * log_lvl)
```

```json
{
  "name": "dump_stack_print_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579737744,
      "name": "dump_stack_print_info",
      "external": true,
      "loc": "kernel/printk/printk.c:3150",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:show_regs_print_info",
        "lib/dump_stack.c:dump_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579737744,
      "name": "dump_stack_print_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void dump_stack_print_info(const char * log_lvl)
```

```json
{
  "name": "dump_stack_print_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579758688,
      "name": "dump_stack_print_info",
      "external": true,
      "loc": "kernel/printk/printk.c:3292",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:show_regs_print_info",
        "lib/dump_stack.c:dump_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758688,
      "name": "dump_stack_print_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void dump_stack_print_info(const char * log_lvl)
```

```json
{
  "name": "dump_stack_print_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579784656,
      "name": "dump_stack_print_info",
      "external": true,
      "loc": "kernel/printk/printk.c:3118",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:show_regs_print_info",
        "lib/dump_stack.c:dump_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579784656,
      "name": "dump_stack_print_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void dump_stack_print_info(const char * log_lvl)
```

```json
{
  "name": "dump_stack_print_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579781456,
      "name": "dump_stack_print_info",
      "external": true,
      "loc": "kernel/printk/printk.c:3125",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:show_regs_print_info",
        "lib/dump_stack.c:dump_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579781456,
      "name": "dump_stack_print_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void dump_stack_print_info(const char * log_lvl)
```

```json
{
  "name": "dump_stack_print_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579814928,
      "name": "dump_stack_print_info",
      "external": true,
      "loc": "kernel/printk/printk.c:3119",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:show_regs_print_info",
        "lib/dump_stack.c:dump_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579814928,
      "name": "dump_stack_print_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void dump_stack_print_info(const char * log_lvl)
```

```json
{
  "name": "dump_stack_print_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "dump_stack_print_info",
      "external": true,
      "loc": "lib/dump_stack.c:45",
      "file": "lib/dump_stack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/dump_stack.c:dump_stack",
        "lib/dump_stack.c:show_regs_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589126923,
      "name": "dump_stack_print_info.cold.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071589126752,
      "name": "dump_stack_print_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void dump_stack_print_info(const char * log_lvl)
```

```json
{
  "name": "dump_stack_print_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dump_stack_print_info",
      "external": true,
      "loc": "lib/dump_stack.c:45",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dump_stack.c:dump_stack",
        "lib/dump_stack.c:show_regs_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589361627,
      "name": "dump_stack_print_info.cold.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589361440,
      "name": "dump_stack_print_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void dump_stack_print_info(const char * log_lvl)
```

```json
{
  "name": "dump_stack_print_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dump_stack_print_info",
      "external": true,
      "loc": "lib/dump_stack.c:45",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dump_stack.c:dump_stack",
        "lib/dump_stack.c:show_regs_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589818731,
      "name": "dump_stack_print_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589818544,
      "name": "dump_stack_print_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void dump_stack_print_info(const char * log_lvl)
```

```json
{
  "name": "dump_stack_print_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dump_stack_print_info",
      "external": true,
      "loc": "lib/dump_stack.c:45",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dump_stack.c:dump_stack",
        "lib/dump_stack.c:show_regs_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590045003,
      "name": "dump_stack_print_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071590044816,
      "name": "dump_stack_print_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void dump_stack_print_info(const char * log_lvl)
```

```json
{
  "name": "dump_stack_print_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dump_stack_print_info",
      "external": true,
      "loc": "lib/dump_stack.c:45",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dump_stack.c:dump_stack",
        "lib/dump_stack.c:show_regs_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585039016,
      "name": "dump_stack_print_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071585038816,
      "name": "dump_stack_print_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void dump_stack_print_info(const char * log_lvl)
```

```json
{
  "name": "dump_stack_print_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dump_stack_print_info",
      "external": true,
      "loc": "lib/dump_stack.c:46",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dump_stack.c:dump_stack",
        "lib/dump_stack.c:show_regs_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591381416,
      "name": "dump_stack_print_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071585190768,
      "name": "dump_stack_print_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void dump_stack_print_info(const char * log_lvl)
```

```json
{
  "name": "dump_stack_print_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dump_stack_print_info",
      "external": true,
      "loc": "lib/dump_stack.c:46",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dump_stack.c:dump_stack",
        "lib/dump_stack.c:show_regs_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591323808,
      "name": "dump_stack_print_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071585073872,
      "name": "dump_stack_print_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void dump_stack_print_info(const char * log_lvl)
```

```json
{
  "name": "dump_stack_print_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dump_stack_print_info",
      "external": true,
      "loc": "lib/dump_stack.c:55",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/report.c:kfence_report_error",
        "lib/dump_stack.c:dump_stack_lvl",
        "lib/dump_stack.c:show_regs_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592341819,
      "name": "dump_stack_print_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071585520656,
      "name": "dump_stack_print_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void dump_stack_print_info(const char * log_lvl)
```

```json
{
  "name": "dump_stack_print_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dump_stack_print_info",
      "external": true,
      "loc": "lib/dump_stack.c:55",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/report.c:kfence_report_error",
        "lib/dump_stack.c:dump_stack_lvl",
        "lib/dump_stack.c:show_regs_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594203401,
      "name": "dump_stack_print_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071586673200,
      "name": "dump_stack_print_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void dump_stack_print_info(const char * log_lvl)
```

```json
{
  "name": "dump_stack_print_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595752656,
      "name": "dump_stack_print_info",
      "external": true,
      "loc": "lib/dump_stack.c:55",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/report.c:kfence_report_error",
        "lib/dump_stack.c:dump_stack_lvl",
        "lib/dump_stack.c:show_regs_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595752656,
      "name": "dump_stack_print_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
void dump_stack_print_info(const char * log_lvl)
```

```json
{
  "name": "dump_stack_print_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596276704,
      "name": "dump_stack_print_info",
      "external": true,
      "loc": "lib/dump_stack.c:55",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/report.c:kfence_report_error",
        "lib/dump_stack.c:dump_stack_lvl",
        "lib/dump_stack.c:show_regs_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596276704,
      "name": "dump_stack_print_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
void dump_stack_print_info(const char * log_lvl)
```

```json
{
  "name": "dump_stack_print_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597161392,
      "name": "dump_stack_print_info",
      "external": true,
      "loc": "lib/dump_stack.c:55",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/report.c:kfence_report_error",
        "lib/dump_stack.c:dump_stack_lvl",
        "lib/dump_stack.c:show_regs_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597161392,
      "name": "dump_stack_print_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
void dump_stack_print_info(const char * log_lvl)
```

```json
{
  "name": "dump_stack_print_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503806512,
      "name": "dump_stack_print_info",
      "external": true,
      "loc": "lib/dump_stack.c:45",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dump_stack.c:dump_stack",
        "lib/dump_stack.c:show_regs_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503806512,
      "name": "dump_stack_print_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void dump_stack_print_info(const char * log_lvl)
```

```json
{
  "name": "dump_stack_print_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236429092,
      "name": "dump_stack_print_info",
      "external": true,
      "loc": "lib/dump_stack.c:45",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dump_stack.c:dump_stack",
        "lib/dump_stack.c:show_regs_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236429092,
      "name": "dump_stack_print_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void dump_stack_print_info(const char * log_lvl)
```

```json
{
  "name": "dump_stack_print_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297645632,
      "name": "dump_stack_print_info",
      "external": true,
      "loc": "lib/dump_stack.c:45",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dump_stack.c:dump_stack",
        "lib/dump_stack.c:show_regs_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297645632,
      "name": "dump_stack_print_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void dump_stack_print_info(const char * log_lvl)
```

```json
{
  "name": "dump_stack_print_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279702900,
      "name": "dump_stack_print_info",
      "external": true,
      "loc": "lib/dump_stack.c:45",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dump_stack.c:dump_stack",
        "lib/dump_stack.c:show_regs_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279702900,
      "name": "dump_stack_print_info",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void dump_stack_print_info(const char * log_lvl)
```

```json
{
  "name": "dump_stack_print_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dump_stack_print_info",
      "external": true,
      "loc": "lib/dump_stack.c:45",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dump_stack.c:dump_stack",
        "lib/dump_stack.c:show_regs_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589647259,
      "name": "dump_stack_print_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589647072,
      "name": "dump_stack_print_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void dump_stack_print_info(const char * log_lvl)
```

```json
{
  "name": "dump_stack_print_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dump_stack_print_info",
      "external": true,
      "loc": "lib/dump_stack.c:45",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dump_stack.c:dump_stack",
        "lib/dump_stack.c:show_regs_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589373131,
      "name": "dump_stack_print_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589372944,
      "name": "dump_stack_print_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void dump_stack_print_info(const char * log_lvl)
```

```json
{
  "name": "dump_stack_print_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dump_stack_print_info",
      "external": true,
      "loc": "lib/dump_stack.c:45",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dump_stack.c:dump_stack",
        "lib/dump_stack.c:show_regs_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590090635,
      "name": "dump_stack_print_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071590090448,
      "name": "dump_stack_print_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void dump_stack_print_info(const char * log_lvl)
```

```json
{
  "name": "dump_stack_print_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dump_stack_print_info",
      "external": true,
      "loc": "lib/dump_stack.c:45",
      "file": "lib/dump_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dump_stack.c:dump_stack",
        "lib/dump_stack.c:show_regs_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590140891,
      "name": "dump_stack_print_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071590140704,
      "name": "dump_stack_print_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
