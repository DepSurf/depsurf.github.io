# Function: <code>rcu_dynticks_curr_cpu_in_eqs</code>

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
bool rcu_dynticks_curr_cpu_in_eqs()
```

```json
{
  "name": "rcu_dynticks_curr_cpu_in_eqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579852306,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": true,
      "loc": "kernel/rcu/tree.c:361",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_nmi_exit",
        "kernel/rcu/tree.c:rcu_nmi_enter"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851760,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
bool rcu_dynticks_curr_cpu_in_eqs()
```

```json
{
  "name": "rcu_dynticks_curr_cpu_in_eqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579892914,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": true,
      "loc": "kernel/rcu/tree.c:358",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_nmi_exit",
        "kernel/rcu/tree.c:rcu_nmi_enter"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892208,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool rcu_dynticks_curr_cpu_in_eqs()
```

```json
{
  "name": "rcu_dynticks_curr_cpu_in_eqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579926405,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": true,
      "loc": "kernel/rcu/tree.c:345",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_nmi_enter",
        "kernel/rcu/tree.c:rcu_nmi_exit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579925760,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool rcu_dynticks_curr_cpu_in_eqs()
```

```json
{
  "name": "rcu_dynticks_curr_cpu_in_eqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579972808,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": true,
      "loc": "kernel/rcu/tree.c:301",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_irq_enter",
        "kernel/rcu/tree.c:rcu_irq_exit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579972128,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool rcu_dynticks_curr_cpu_in_eqs()
```

```json
{
  "name": "rcu_dynticks_curr_cpu_in_eqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580012808,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": true,
      "loc": "kernel/rcu/tree.c:296",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_irq_enter",
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_nmi_exit"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_nmi_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580011920,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool rcu_dynticks_curr_cpu_in_eqs()
```

```json
{
  "name": "rcu_dynticks_curr_cpu_in_eqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580058316,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": true,
      "loc": "kernel/rcu/tree.c:297",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:rcu_irq_enter",
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_nmi_exit"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_nmi_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062320,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_dynticks_curr_cpu_in_eqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580117920,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": false,
      "loc": "kernel/rcu/tree.c:312",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:__rcu_is_watching",
        "kernel/rcu/tree.c:rcu_nmi_enter",
        "kernel/rcu/tree.c:rcu_nmi_exit"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_dynticks_curr_cpu_in_eqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580099072,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": false,
      "loc": "kernel/rcu/tree.c:317",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:rcu_nmi_enter",
        "kernel/rcu/tree.c:rcu_nmi_exit"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_dynticks_curr_cpu_in_eqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580101096,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": false,
      "loc": "kernel/rcu/tree.c:323",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:rcu_nmi_enter",
        "kernel/rcu/tree.c:rcu_nmi_exit"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_dynticks_curr_cpu_in_eqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580240924,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": false,
      "loc": "kernel/rcu/tree.c:328",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:rcu_nmi_enter",
        "kernel/rcu/tree.c:rcu_nmi_exit"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_dynticks_curr_cpu_in_eqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580409699,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": false,
      "loc": "kernel/rcu/tree.c:339",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:call_rcu",
        "kernel/rcu/tree.c:call_rcu",
        "kernel/rcu/tree.c:rcu_nmi_enter",
        "kernel/rcu/tree.c:rcu_nmi_exit"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_dynticks_curr_cpu_in_eqs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579803413,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": false,
      "loc": "include/linux/context_tracking.h:119",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:__warn_printk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580613143,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": false,
      "loc": "include/linux/context_tracking.h:119",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596409334,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": false,
      "loc": "include/linux/context_tracking.h:119",
      "file": "kernel/context_tracking.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/context_tracking.c:ct_nmi_enter",
        "kernel/context_tracking.c:ct_nmi_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595748270,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": false,
      "loc": "include/linux/context_tracking.h:119",
      "file": "lib/bug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bug.c:report_bug"
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
  "name": "rcu_dynticks_curr_cpu_in_eqs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579851541,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": false,
      "loc": "include/linux/context_tracking.h:120",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:__warn_printk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580686983,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": false,
      "loc": "include/linux/context_tracking.h:120",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596941430,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": false,
      "loc": "include/linux/context_tracking.h:120",
      "file": "kernel/context_tracking.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/context_tracking.c:ct_nmi_enter",
        "kernel/context_tracking.c:ct_nmi_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596272574,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": false,
      "loc": "include/linux/context_tracking.h:120",
      "file": "lib/bug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bug.c:report_bug"
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
  "name": "rcu_dynticks_curr_cpu_in_eqs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579889349,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": false,
      "loc": "include/linux/context_tracking.h:120",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:__warn_printk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580813949,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": false,
      "loc": "include/linux/context_tracking.h:120",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:__call_rcu_common",
        "kernel/rcu/tree.c:__call_rcu_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597868823,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": false,
      "loc": "include/linux/context_tracking.h:120",
      "file": "kernel/context_tracking.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/context_tracking.c:ct_nmi_enter",
        "kernel/context_tracking.c:ct_nmi_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597157310,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": false,
      "loc": "include/linux/context_tracking.h:120",
      "file": "lib/bug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bug.c:report_bug"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool rcu_dynticks_curr_cpu_in_eqs()
```

```json
{
  "name": "rcu_dynticks_curr_cpu_in_eqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491266188,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": true,
      "loc": "kernel/rcu/tree.c:297",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:rcu_irq_enter",
        "kernel/rcu/tree.c:rcu_irq_exit"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_nmi_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491272192,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool rcu_dynticks_curr_cpu_in_eqs()
```

```json
{
  "name": "rcu_dynticks_curr_cpu_in_eqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225273536,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": true,
      "loc": "kernel/rcu/tree.c:297",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:rcu_irq_enter",
        "kernel/rcu/tree.c:rcu_irq_exit"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_nmi_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225281380,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool rcu_dynticks_curr_cpu_in_eqs()
```

```json
{
  "name": "rcu_dynticks_curr_cpu_in_eqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284169152,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": true,
      "loc": "kernel/rcu/tree.c:297",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:rcu_irq_enter",
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_nmi_exit"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_nmi_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284177696,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool rcu_dynticks_curr_cpu_in_eqs()
```

```json
{
  "name": "rcu_dynticks_curr_cpu_in_eqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271790752,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": true,
      "loc": "kernel/rcu/tree.c:297",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:rcu_irq_enter",
        "kernel/rcu/tree.c:rcu_irq_exit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271793718,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool rcu_dynticks_curr_cpu_in_eqs()
```

```json
{
  "name": "rcu_dynticks_curr_cpu_in_eqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580027052,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": true,
      "loc": "kernel/rcu/tree.c:297",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:rcu_irq_enter",
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_nmi_exit"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_nmi_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580031056,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool rcu_dynticks_curr_cpu_in_eqs()
```

```json
{
  "name": "rcu_dynticks_curr_cpu_in_eqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579974983,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": true,
      "loc": "kernel/rcu/tree.c:297",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:rcu_irq_enter",
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_nmi_exit"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_nmi_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579975472,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool rcu_dynticks_curr_cpu_in_eqs()
```

```json
{
  "name": "rcu_dynticks_curr_cpu_in_eqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580018588,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": true,
      "loc": "kernel/rcu/tree.c:297",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:rcu_irq_enter",
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_nmi_exit"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_nmi_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022592,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool rcu_dynticks_curr_cpu_in_eqs()
```

```json
{
  "name": "rcu_dynticks_curr_cpu_in_eqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580067887,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
      "external": true,
      "loc": "kernel/rcu/tree.c:297",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_handler",
        "kernel/rcu/tree.c:rcu_exp_handler",
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:rcu_irq_enter",
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_nmi_exit"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_nmi_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580072080,
      "name": "rcu_dynticks_curr_cpu_in_eqs",
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
bool rcu_dynticks_curr_cpu_in_eqs()
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
bool rcu_dynticks_curr_cpu_in_eqs()
```
</details>
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
