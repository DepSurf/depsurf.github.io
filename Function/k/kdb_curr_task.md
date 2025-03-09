# Function: <code>kdb_curr_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * kdb_curr_task(int cpu)
```

```json
{
  "name": "kdb_curr_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580109872,
      "name": "kdb_curr_task",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:188",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_main_loop",
        "kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed",
        "kernel/debug/kdb/kdb_main.c:kdb_ps"
      ],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580109872,
      "name": "kdb_curr_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * kdb_curr_task(int cpu)
```

```json
{
  "name": "kdb_curr_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580155299,
      "name": "kdb_curr_task",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:188",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed",
        "kernel/debug/kdb/kdb_main.c:kdb_main_loop"
      ],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580143824,
      "name": "kdb_curr_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct task_struct * kdb_curr_task(int cpu)
```

```json
{
  "name": "kdb_curr_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580195701,
      "name": "kdb_curr_task",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:187",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed",
        "kernel/debug/kdb/kdb_main.c:kdb_main_loop"
      ],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580184192,
      "name": "kdb_curr_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct task_struct * kdb_curr_task(int cpu)
```

```json
{
  "name": "kdb_curr_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580203380,
      "name": "kdb_curr_task",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:190",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed",
        "kernel/debug/kdb/kdb_main.c:kdb_main_loop"
      ],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580191696,
      "name": "kdb_curr_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct task_struct * kdb_curr_task(int cpu)
```

```json
{
  "name": "kdb_curr_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580254774,
      "name": "kdb_curr_task",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:190",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed"
      ],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580243072,
      "name": "kdb_curr_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct task_struct * kdb_curr_task(int cpu)
```

```json
{
  "name": "kdb_curr_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580315190,
      "name": "kdb_curr_task",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:190",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed"
      ],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580303328,
      "name": "kdb_curr_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct task_struct * kdb_curr_task(int cpu)
```

```json
{
  "name": "kdb_curr_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580367766,
      "name": "kdb_curr_task",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:190",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed"
      ],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580355856,
      "name": "kdb_curr_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct task_struct * kdb_curr_task(int cpu)
```

```json
{
  "name": "kdb_curr_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580420452,
      "name": "kdb_curr_task",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:190",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed"
      ],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580408448,
      "name": "kdb_curr_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct task_struct * kdb_curr_task(int cpu)
```

```json
{
  "name": "kdb_curr_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580469204,
      "name": "kdb_curr_task",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:190",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed"
      ],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580457216,
      "name": "kdb_curr_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * kdb_curr_task(int cpu)
```

```json
{
  "name": "kdb_curr_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580553207,
      "name": "kdb_curr_task",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:189",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed"
      ],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580542688,
      "name": "kdb_curr_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * kdb_curr_task(int cpu)
```

```json
{
  "name": "kdb_curr_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580541292,
      "name": "kdb_curr_task",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:189",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed"
      ],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580530592,
      "name": "kdb_curr_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * kdb_curr_task(int cpu)
```

```json
{
  "name": "kdb_curr_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580544460,
      "name": "kdb_curr_task",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:159",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed"
      ],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580534032,
      "name": "kdb_curr_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * kdb_curr_task(int cpu)
```

```json
{
  "name": "kdb_curr_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580716100,
      "name": "kdb_curr_task",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:158",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed"
      ],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580705360,
      "name": "kdb_curr_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * kdb_curr_task(int cpu)
```

```json
{
  "name": "kdb_curr_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580927982,
      "name": "kdb_curr_task",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:158",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed"
      ],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916432,
      "name": "kdb_curr_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * kdb_curr_task(int cpu)
```

```json
{
  "name": "kdb_curr_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581220532,
      "name": "kdb_curr_task",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:158",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed"
      ],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581208624,
      "name": "kdb_curr_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * kdb_curr_task(int cpu)
```

```json
{
  "name": "kdb_curr_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581314964,
      "name": "kdb_curr_task",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:158",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed"
      ],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581302976,
      "name": "kdb_curr_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * kdb_curr_task(int cpu)
```

```json
{
  "name": "kdb_curr_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581421156,
      "name": "kdb_curr_task",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:158",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed"
      ],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581409200,
      "name": "kdb_curr_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct task_struct * kdb_curr_task(int cpu)
```

```json
{
  "name": "kdb_curr_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491743948,
      "name": "kdb_curr_task",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:190",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed"
      ],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491731728,
      "name": "kdb_curr_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct task_struct * kdb_curr_task(int cpu)
```

```json
{
  "name": "kdb_curr_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225692744,
      "name": "kdb_curr_task",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:190",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed"
      ],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225680872,
      "name": "kdb_curr_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct task_struct * kdb_curr_task(int cpu)
```

```json
{
  "name": "kdb_curr_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284777616,
      "name": "kdb_curr_task",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:190",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed"
      ],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284758496,
      "name": "kdb_curr_task",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * kdb_curr_task(int cpu)
```

```json
{
  "name": "kdb_curr_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580438004,
      "name": "kdb_curr_task",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:190",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed"
      ],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580426016,
      "name": "kdb_curr_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct task_struct * kdb_curr_task(int cpu)
```

```json
{
  "name": "kdb_curr_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580385076,
      "name": "kdb_curr_task",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:190",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed"
      ],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580373088,
      "name": "kdb_curr_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct task_struct * kdb_curr_task(int cpu)
```

```json
{
  "name": "kdb_curr_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580429252,
      "name": "kdb_curr_task",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:190",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed"
      ],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580417264,
      "name": "kdb_curr_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct task_struct * kdb_curr_task(int cpu)
```

```json
{
  "name": "kdb_curr_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580484836,
      "name": "kdb_curr_task",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:190",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed"
      ],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580472848,
      "name": "kdb_curr_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct task_struct * kdb_curr_task(int cpu)
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
