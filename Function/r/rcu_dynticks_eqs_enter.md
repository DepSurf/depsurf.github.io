# Function: <code>rcu_dynticks_eqs_enter</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_dynticks_eqs_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579852345,
      "name": "rcu_dynticks_eqs_enter",
      "external": false,
      "loc": "kernel/rcu/tree.c:293",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_dynticks_eqs_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579892953,
      "name": "rcu_dynticks_eqs_enter",
      "external": false,
      "loc": "kernel/rcu/tree.c:290",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_dynticks_eqs_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579926127,
      "name": "rcu_dynticks_eqs_enter",
      "external": false,
      "loc": "kernel/rcu/tree.c:277",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_nmi_exit",
        "kernel/rcu/tree.c:rcu_idle_enter"
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
  "name": "rcu_dynticks_eqs_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579972523,
      "name": "rcu_dynticks_eqs_enter",
      "external": false,
      "loc": "kernel/rcu/tree.c:233",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_idle_enter"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_dynticks_eqs_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580012539,
      "name": "rcu_dynticks_eqs_enter",
      "external": false,
      "loc": "kernel/rcu/tree.c:228",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_nmi_exit",
        "kernel/rcu/tree.c:rcu_idle_enter"
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
  "name": "rcu_dynticks_eqs_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580062967,
      "name": "rcu_dynticks_eqs_enter",
      "external": false,
      "loc": "kernel/rcu/tree.c:229",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_nmi_exit",
        "kernel/rcu/tree.c:rcu_idle_enter"
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
void rcu_dynticks_eqs_enter()
```

```json
{
  "name": "rcu_dynticks_eqs_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591163984,
      "name": "rcu_dynticks_eqs_enter",
      "external": false,
      "loc": "kernel/rcu/tree.c:242",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_nmi_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591163984,
      "name": "rcu_dynticks_eqs_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
void rcu_dynticks_eqs_enter()
```

```json
{
  "name": "rcu_dynticks_eqs_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591659056,
      "name": "rcu_dynticks_eqs_enter",
      "external": false,
      "loc": "kernel/rcu/tree.c:247",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_nmi_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591659056,
      "name": "rcu_dynticks_eqs_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
void rcu_dynticks_eqs_enter()
```

```json
{
  "name": "rcu_dynticks_eqs_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591602752,
      "name": "rcu_dynticks_eqs_enter",
      "external": false,
      "loc": "kernel/rcu/tree.c:253",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_nmi_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591602752,
      "name": "rcu_dynticks_eqs_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
void rcu_dynticks_eqs_enter()
```

```json
{
  "name": "rcu_dynticks_eqs_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592775712,
      "name": "rcu_dynticks_eqs_enter",
      "external": false,
      "loc": "kernel/rcu/tree.c:269",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_nmi_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592775712,
      "name": "rcu_dynticks_eqs_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void rcu_dynticks_eqs_enter()
```

```json
{
  "name": "rcu_dynticks_eqs_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594673136,
      "name": "rcu_dynticks_eqs_enter",
      "external": false,
      "loc": "kernel/rcu/tree.c:280",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_nmi_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594673136,
      "name": "rcu_dynticks_eqs_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void rcu_dynticks_eqs_enter()
```

```json
{
  "name": "rcu_dynticks_eqs_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491255280,
      "name": "rcu_dynticks_eqs_enter",
      "external": false,
      "loc": "kernel/rcu/tree.c:229",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491255280,
      "name": "rcu_dynticks_eqs_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void rcu_dynticks_eqs_enter()
```

```json
{
  "name": "rcu_dynticks_eqs_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225263356,
      "name": "rcu_dynticks_eqs_enter",
      "external": false,
      "loc": "kernel/rcu/tree.c:229",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225263356,
      "name": "rcu_dynticks_eqs_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
  "name": "rcu_dynticks_eqs_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284178588,
      "name": "rcu_dynticks_eqs_enter",
      "external": false,
      "loc": "kernel/rcu/tree.c:229",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_nmi_exit",
        "kernel/rcu/tree.c:rcu_idle_enter"
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
  "name": "rcu_dynticks_eqs_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271794170,
      "name": "rcu_dynticks_eqs_enter",
      "external": false,
      "loc": "kernel/rcu/tree.c:229",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_idle_enter"
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
  "name": "rcu_dynticks_eqs_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580031703,
      "name": "rcu_dynticks_eqs_enter",
      "external": false,
      "loc": "kernel/rcu/tree.c:229",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_nmi_exit",
        "kernel/rcu/tree.c:rcu_idle_enter"
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
  "name": "rcu_dynticks_eqs_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579976007,
      "name": "rcu_dynticks_eqs_enter",
      "external": false,
      "loc": "kernel/rcu/tree.c:229",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_irq_exit",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_dynticks_eqs_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580023239,
      "name": "rcu_dynticks_eqs_enter",
      "external": false,
      "loc": "kernel/rcu/tree.c:229",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_nmi_exit",
        "kernel/rcu/tree.c:rcu_idle_enter"
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
  "name": "rcu_dynticks_eqs_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580072759,
      "name": "rcu_dynticks_eqs_enter",
      "external": false,
      "loc": "kernel/rcu/tree.c:229",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_nmi_exit",
        "kernel/rcu/tree.c:rcu_idle_enter"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void rcu_dynticks_eqs_enter()
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void rcu_dynticks_eqs_enter()
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void rcu_dynticks_eqs_enter()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void rcu_dynticks_eqs_enter()
```
</details>
</li>
</ul>
