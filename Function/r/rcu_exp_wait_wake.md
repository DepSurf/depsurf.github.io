# Function: <code>rcu_exp_wait_wake</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_exp_wait_wake",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579810967,
      "name": "rcu_exp_wait_wake",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:490",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void rcu_exp_wait_wake(struct rcu_state * rsp, long unsigned int s)
```

```json
{
  "name": "rcu_exp_wait_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579837088,
      "name": "rcu_exp_wait_wake",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:498",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579837088,
      "name": "rcu_exp_wait_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1443
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
void rcu_exp_wait_wake(struct rcu_state * rsp, long unsigned int s)
```

```json
{
  "name": "rcu_exp_wait_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579840112,
      "name": "rcu_exp_wait_wake",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:514",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579840112,
      "name": "rcu_exp_wait_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1499
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
void rcu_exp_wait_wake(struct rcu_state * rsp, long unsigned int s)
```

```json
{
  "name": "rcu_exp_wait_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579883952,
      "name": "rcu_exp_wait_wake",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:514",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579883952,
      "name": "rcu_exp_wait_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1479
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
void rcu_exp_wait_wake(struct rcu_state * rsp, long unsigned int s)
```

```json
{
  "name": "rcu_exp_wait_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_exp_wait_wake",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:592",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579920160,
      "name": "rcu_exp_wait_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
    },
    {
      "addr": 18446744071579930004,
      "name": "rcu_exp_wait_wake.cold.77",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 649
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
void rcu_exp_wait_wake(long unsigned int s)
```

```json
{
  "name": "rcu_exp_wait_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_exp_wait_wake",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:550",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579964960,
      "name": "rcu_exp_wait_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 603
    },
    {
      "addr": 18446744071579977173,
      "name": "rcu_exp_wait_wake.cold.74",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void rcu_exp_wait_wake(long unsigned int s)
```

```json
{
  "name": "rcu_exp_wait_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580004000,
      "name": "rcu_exp_wait_wake",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:539",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580004000,
      "name": "rcu_exp_wait_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void rcu_exp_wait_wake(long unsigned int s)
```

```json
{
  "name": "rcu_exp_wait_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580054160,
      "name": "rcu_exp_wait_wake",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:538",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054160,
      "name": "rcu_exp_wait_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void rcu_exp_wait_wake(long unsigned int s)
```

```json
{
  "name": "rcu_exp_wait_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580121280,
      "name": "rcu_exp_wait_wake",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:579",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580121280,
      "name": "rcu_exp_wait_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
void rcu_exp_wait_wake(long unsigned int s)
```

```json
{
  "name": "rcu_exp_wait_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580102400,
      "name": "rcu_exp_wait_wake",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:579",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580102400,
      "name": "rcu_exp_wait_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
void rcu_exp_wait_wake(long unsigned int s)
```

```json
{
  "name": "rcu_exp_wait_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580099696,
      "name": "rcu_exp_wait_wake",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:580",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580099696,
      "name": "rcu_exp_wait_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void rcu_exp_wait_wake(long unsigned int s)
```

```json
{
  "name": "rcu_exp_wait_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580239952,
      "name": "rcu_exp_wait_wake",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:581",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580239952,
      "name": "rcu_exp_wait_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void rcu_exp_wait_wake(long unsigned int s)
```

```json
{
  "name": "rcu_exp_wait_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580412928,
      "name": "rcu_exp_wait_wake",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:681",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580412928,
      "name": "rcu_exp_wait_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
void rcu_exp_wait_wake(long unsigned int s)
```

```json
{
  "name": "rcu_exp_wait_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580632720,
      "name": "rcu_exp_wait_wake",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:686",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580632720,
      "name": "rcu_exp_wait_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
void rcu_exp_wait_wake(long unsigned int s)
```

```json
{
  "name": "rcu_exp_wait_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580714912,
      "name": "rcu_exp_wait_wake",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:689",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580714912,
      "name": "rcu_exp_wait_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
void rcu_exp_wait_wake(long unsigned int s)
```

```json
{
  "name": "rcu_exp_wait_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580788752,
      "name": "rcu_exp_wait_wake",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:692",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580788752,
      "name": "rcu_exp_wait_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
void rcu_exp_wait_wake(long unsigned int s)
```

```json
{
  "name": "rcu_exp_wait_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491259368,
      "name": "rcu_exp_wait_wake",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:538",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491259368,
      "name": "rcu_exp_wait_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
void rcu_exp_wait_wake(long unsigned int s)
```

```json
{
  "name": "rcu_exp_wait_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225269356,
      "name": "rcu_exp_wait_wake",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:538",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225269356,
      "name": "rcu_exp_wait_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
void rcu_exp_wait_wake(long unsigned int s)
```

```json
{
  "name": "rcu_exp_wait_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284161968,
      "name": "rcu_exp_wait_wake",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:538",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284161968,
      "name": "rcu_exp_wait_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
void rcu_exp_wait_wake(long unsigned int s)
```

```json
{
  "name": "rcu_exp_wait_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271785872,
      "name": "rcu_exp_wait_wake",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:538",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271785872,
      "name": "rcu_exp_wait_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void rcu_exp_wait_wake(long unsigned int s)
```

```json
{
  "name": "rcu_exp_wait_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580022896,
      "name": "rcu_exp_wait_wake",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:538",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022896,
      "name": "rcu_exp_wait_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void rcu_exp_wait_wake(long unsigned int s)
```

```json
{
  "name": "rcu_exp_wait_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579964160,
      "name": "rcu_exp_wait_wake",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:538",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579964160,
      "name": "rcu_exp_wait_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void rcu_exp_wait_wake(long unsigned int s)
```

```json
{
  "name": "rcu_exp_wait_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580014432,
      "name": "rcu_exp_wait_wake",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:538",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014432,
      "name": "rcu_exp_wait_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void rcu_exp_wait_wake(long unsigned int s)
```

```json
{
  "name": "rcu_exp_wait_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580059264,
      "name": "rcu_exp_wait_wake",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:538",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580059264,
      "name": "rcu_exp_wait_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void rcu_exp_wait_wake(struct rcu_state * rsp, long unsigned int s)
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct rcu_state * rsp</code>
</li>
<li>
<b>Param reordered. </b>
<code>rsp, s</code> ➡️ <code>s</code>
</li>
</ul>
</details>
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
