# Function: <code>srcu_reschedule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void srcu_reschedule(struct srcu_struct * sp)
```

```json
{
  "name": "srcu_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579778560,
      "name": "srcu_reschedule",
      "external": false,
      "loc": "kernel/rcu/srcu.c:637",
      "file": "kernel/rcu/srcu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcu.c:process_srcu",
        "kernel/rcu/srcu.c:__synchronize_srcu",
        "kernel/rcu/srcu.c:__synchronize_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579778560,
      "name": "srcu_reschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
void srcu_reschedule(struct srcu_struct * sp)
```

```json
{
  "name": "srcu_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579803904,
      "name": "srcu_reschedule",
      "external": false,
      "loc": "kernel/rcu/srcu.c:637",
      "file": "kernel/rcu/srcu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcu.c:process_srcu",
        "kernel/rcu/srcu.c:__synchronize_srcu",
        "kernel/rcu/srcu.c:__synchronize_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579803904,
      "name": "srcu_reschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void srcu_reschedule(struct srcu_struct * sp)
```

```json
{
  "name": "srcu_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579832288,
      "name": "srcu_reschedule",
      "external": false,
      "loc": "kernel/rcu/srcu.c:637",
      "file": "kernel/rcu/srcu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcu.c:process_srcu",
        "kernel/rcu/srcu.c:__synchronize_srcu",
        "kernel/rcu/srcu.c:__synchronize_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579832288,
      "name": "srcu_reschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void srcu_reschedule(struct srcu_struct * sp, long unsigned int delay)
```

```json
{
  "name": "srcu_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579834176,
      "name": "srcu_reschedule",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1183",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:process_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579834176,
      "name": "srcu_reschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void srcu_reschedule(struct srcu_struct * sp, long unsigned int delay)
```

```json
{
  "name": "srcu_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579874464,
      "name": "srcu_reschedule",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1184",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:process_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579874464,
      "name": "srcu_reschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void srcu_reschedule(struct srcu_struct * sp, long unsigned int delay)
```

```json
{
  "name": "srcu_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579907936,
      "name": "srcu_reschedule",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1214",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:process_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579907936,
      "name": "srcu_reschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void srcu_reschedule(struct srcu_struct * ssp, long unsigned int delay)
```

```json
{
  "name": "srcu_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579955936,
      "name": "srcu_reschedule",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1232",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:process_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579955936,
      "name": "srcu_reschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void srcu_reschedule(struct srcu_struct * ssp, long unsigned int delay)
```

```json
{
  "name": "srcu_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579996240,
      "name": "srcu_reschedule",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1208",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:process_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579996240,
      "name": "srcu_reschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void srcu_reschedule(struct srcu_struct * ssp, long unsigned int delay)
```

```json
{
  "name": "srcu_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580046368,
      "name": "srcu_reschedule",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1209",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:process_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046368,
      "name": "srcu_reschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void srcu_reschedule(struct srcu_struct * ssp, long unsigned int delay)
```

```json
{
  "name": "srcu_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580101664,
      "name": "srcu_reschedule",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1224",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580101664,
      "name": "srcu_reschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void srcu_reschedule(struct srcu_struct * ssp, long unsigned int delay)
```

```json
{
  "name": "srcu_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580083200,
      "name": "srcu_reschedule",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1213",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580083200,
      "name": "srcu_reschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void srcu_reschedule(struct srcu_struct * ssp, long unsigned int delay)
```

```json
{
  "name": "srcu_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580084768,
      "name": "srcu_reschedule",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1301",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580084768,
      "name": "srcu_reschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void srcu_reschedule(struct srcu_struct * ssp, long unsigned int delay)
```

```json
{
  "name": "srcu_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580221184,
      "name": "srcu_reschedule",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1296",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580221184,
      "name": "srcu_reschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void srcu_reschedule(struct srcu_struct * ssp, long unsigned int delay)
```

```json
{
  "name": "srcu_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580379696,
      "name": "srcu_reschedule",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1591",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:process_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580379696,
      "name": "srcu_reschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void srcu_reschedule(struct srcu_struct * ssp, long unsigned int delay)
```

```json
{
  "name": "srcu_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580601872,
      "name": "srcu_reschedule",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1660",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:process_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580601872,
      "name": "srcu_reschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void srcu_reschedule(struct srcu_struct * ssp, long unsigned int delay)
```

```json
{
  "name": "srcu_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580675408,
      "name": "srcu_reschedule",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1736",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580675408,
      "name": "srcu_reschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
void srcu_reschedule(struct srcu_struct * ssp, long unsigned int delay)
```

```json
{
  "name": "srcu_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580742080,
      "name": "srcu_reschedule",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1762",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580742080,
      "name": "srcu_reschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
void srcu_reschedule(struct srcu_struct * ssp, long unsigned int delay)
```

```json
{
  "name": "srcu_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491246296,
      "name": "srcu_reschedule",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1209",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:process_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491246296,
      "name": "srcu_reschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
void srcu_reschedule(struct srcu_struct * ssp, long unsigned int delay)
```

```json
{
  "name": "srcu_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225259832,
      "name": "srcu_reschedule",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1209",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225259832,
      "name": "srcu_reschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
void srcu_reschedule(struct srcu_struct * ssp, long unsigned int delay)
```

```json
{
  "name": "srcu_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284151920,
      "name": "srcu_reschedule",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1209",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:process_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284151920,
      "name": "srcu_reschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
void srcu_reschedule(struct srcu_struct * ssp, long unsigned int delay)
```

```json
{
  "name": "srcu_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271774988,
      "name": "srcu_reschedule",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1209",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:process_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271774988,
      "name": "srcu_reschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void srcu_reschedule(struct srcu_struct * ssp, long unsigned int delay)
```

```json
{
  "name": "srcu_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580015104,
      "name": "srcu_reschedule",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1209",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:process_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580015104,
      "name": "srcu_reschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void srcu_reschedule(struct srcu_struct * ssp, long unsigned int delay)
```

```json
{
  "name": "srcu_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579953824,
      "name": "srcu_reschedule",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1209",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:process_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579953824,
      "name": "srcu_reschedule",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void srcu_reschedule(struct srcu_struct * ssp, long unsigned int delay)
```

```json
{
  "name": "srcu_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580006640,
      "name": "srcu_reschedule",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1209",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:process_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580006640,
      "name": "srcu_reschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void srcu_reschedule(struct srcu_struct * ssp, long unsigned int delay)
```

```json
{
  "name": "srcu_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580052512,
      "name": "srcu_reschedule",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1209",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:process_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580052512,
      "name": "srcu_reschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int delay</code>
</li>
</ul>
</details>
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
<b>Param added. </b>
<code>struct srcu_struct * ssp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct srcu_struct * sp</code>
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
