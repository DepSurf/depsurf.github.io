# Function: <code>check_init_srcu_struct</code>

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
void check_init_srcu_struct(struct srcu_struct * sp)
```

```json
{
  "name": "check_init_srcu_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579833424,
      "name": "check_init_srcu_struct",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:204",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579833424,
      "name": "check_init_srcu_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void check_init_srcu_struct(struct srcu_struct * sp)
```

```json
{
  "name": "check_init_srcu_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579873712,
      "name": "check_init_srcu_struct",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:205",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579873712,
      "name": "check_init_srcu_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void check_init_srcu_struct(struct srcu_struct * sp)
```

```json
{
  "name": "check_init_srcu_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579907648,
      "name": "check_init_srcu_struct",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:232",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579907648,
      "name": "check_init_srcu_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
  "name": "check_init_srcu_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604724674,
      "name": "check_init_srcu_struct",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:238",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_init",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_init",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579955184,
      "name": "check_init_srcu_struct.part.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
  "name": "check_init_srcu_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604825506,
      "name": "check_init_srcu_struct",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:227",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_init",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_init",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579994016,
      "name": "check_init_srcu_struct.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
  "name": "check_init_srcu_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604859831,
      "name": "check_init_srcu_struct",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:227",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_init",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_init",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580044144,
      "name": "check_init_srcu_struct.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void check_init_srcu_struct(struct srcu_struct * ssp)
```

```json
{
  "name": "check_init_srcu_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580099280,
      "name": "check_init_srcu_struct",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:240",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_init",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580099280,
      "name": "check_init_srcu_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void check_init_srcu_struct(struct srcu_struct * ssp)
```

```json
{
  "name": "check_init_srcu_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580080800,
      "name": "check_init_srcu_struct",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:229",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_init",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_might_be_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580080800,
      "name": "check_init_srcu_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void check_init_srcu_struct(struct srcu_struct * ssp)
```

```json
{
  "name": "check_init_srcu_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580082384,
      "name": "check_init_srcu_struct",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:232",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_init",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580082384,
      "name": "check_init_srcu_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void check_init_srcu_struct(struct srcu_struct * ssp)
```

```json
{
  "name": "check_init_srcu_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580218752,
      "name": "check_init_srcu_struct",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:224",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580218752,
      "name": "check_init_srcu_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void check_init_srcu_struct(struct srcu_struct * ssp)
```

```json
{
  "name": "check_init_srcu_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580379296,
      "name": "check_init_srcu_struct",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:392",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__synchronize_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580379296,
      "name": "check_init_srcu_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void check_init_srcu_struct(struct srcu_struct * ssp)
```

```json
{
  "name": "check_init_srcu_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580607216,
      "name": "check_init_srcu_struct",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:392",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__synchronize_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580607216,
      "name": "check_init_srcu_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void check_init_srcu_struct(struct srcu_struct * ssp)
```

```json
{
  "name": "check_init_srcu_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580680912,
      "name": "check_init_srcu_struct",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:401",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__synchronize_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580680912,
      "name": "check_init_srcu_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void check_init_srcu_struct(struct srcu_struct * ssp)
```

```json
{
  "name": "check_init_srcu_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580747632,
      "name": "check_init_srcu_struct",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:403",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__synchronize_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580747632,
      "name": "check_init_srcu_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
  "name": "check_init_srcu_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336510892752,
      "name": "check_init_srcu_struct",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:227",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_init",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_init",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491246576,
      "name": "check_init_srcu_struct.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "check_init_srcu_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243381108,
      "name": "check_init_srcu_struct",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:227",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_init",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_init",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225258804,
      "name": "check_init_srcu_struct.part.0",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "check_init_srcu_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302527508,
      "name": "check_init_srcu_struct",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:227",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_init",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_init",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284148800,
      "name": "check_init_srcu_struct.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
  "name": "check_init_srcu_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936270632318,
      "name": "check_init_srcu_struct",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:227",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_init",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_init",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271774170,
      "name": "check_init_srcu_struct.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_init_srcu_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604764847,
      "name": "check_init_srcu_struct",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:227",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_init",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_init",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012880,
      "name": "check_init_srcu_struct.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
  "name": "check_init_srcu_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604732719,
      "name": "check_init_srcu_struct",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:227",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_init",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_init",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951632,
      "name": "check_init_srcu_struct.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
  "name": "check_init_srcu_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604842475,
      "name": "check_init_srcu_struct",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:227",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_init",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_init",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580004416,
      "name": "check_init_srcu_struct.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
  "name": "check_init_srcu_struct",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604863972,
      "name": "check_init_srcu_struct",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:227",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_init",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_init",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580051744,
      "name": "check_init_srcu_struct.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void check_init_srcu_struct(struct srcu_struct * sp)
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void check_init_srcu_struct(struct srcu_struct * sp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void check_init_srcu_struct(struct srcu_struct * ssp)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
