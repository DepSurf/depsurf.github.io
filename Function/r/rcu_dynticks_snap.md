# Function: <code>rcu_dynticks_snap</code>

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
int rcu_dynticks_snap(struct rcu_dynticks * rdtp)
```

```json
{
  "name": "rcu_dynticks_snap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579856119,
      "name": "rcu_dynticks_snap",
      "external": true,
      "loc": "kernel/rcu/tree.c:372",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/rcu/tree.c:rcu_init_one"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851808,
      "name": "rcu_dynticks_snap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int rcu_dynticks_snap(struct rcu_dynticks * rdtp)
```

```json
{
  "name": "rcu_dynticks_snap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579897143,
      "name": "rcu_dynticks_snap",
      "external": true,
      "loc": "kernel/rcu/tree.c:369",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892256,
      "name": "rcu_dynticks_snap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int rcu_dynticks_snap(struct rcu_dynticks * rdtp)
```

```json
{
  "name": "rcu_dynticks_snap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579912911,
      "name": "rcu_dynticks_snap",
      "external": true,
      "loc": "kernel/rcu/tree.c:356",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579925808,
      "name": "rcu_dynticks_snap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int rcu_dynticks_snap(struct rcu_data * rdp)
```

```json
{
  "name": "rcu_dynticks_snap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579976338,
      "name": "rcu_dynticks_snap",
      "external": true,
      "loc": "kernel/rcu/tree.c:312",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579972176,
      "name": "rcu_dynticks_snap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int rcu_dynticks_snap(struct rcu_data * rdp)
```

```json
{
  "name": "rcu_dynticks_snap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580002611,
      "name": "rcu_dynticks_snap",
      "external": true,
      "loc": "kernel/rcu/tree.c:307",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012064,
      "name": "rcu_dynticks_snap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int rcu_dynticks_snap(struct rcu_data * rdp)
```

```json
{
  "name": "rcu_dynticks_snap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580052815,
      "name": "rcu_dynticks_snap",
      "external": true,
      "loc": "kernel/rcu/tree.c:308",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062464,
      "name": "rcu_dynticks_snap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
  "name": "rcu_dynticks_snap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580109294,
      "name": "rcu_dynticks_snap",
      "external": false,
      "loc": "kernel/rcu/tree.c:323",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_boot_init_percpu_data",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs"
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
  "name": "rcu_dynticks_snap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580091534,
      "name": "rcu_dynticks_snap",
      "external": false,
      "loc": "kernel/rcu/tree.c:328",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_boot_init_percpu_data",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs",
        "kernel/rcu/tree.c:rcu_is_idle_cpu"
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
  "name": "rcu_dynticks_snap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580093005,
      "name": "rcu_dynticks_snap",
      "external": false,
      "loc": "kernel/rcu/tree.c:334",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs",
        "kernel/rcu/tree.c:rcu_is_idle_cpu"
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
  "name": "rcu_dynticks_snap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580231257,
      "name": "rcu_dynticks_snap",
      "external": false,
      "loc": "kernel/rcu/tree.c:337",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs",
        "kernel/rcu/tree.c:rcu_is_idle_cpu"
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
  "name": "rcu_dynticks_snap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580396153,
      "name": "rcu_dynticks_snap",
      "external": false,
      "loc": "kernel/rcu/tree.c:348",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs",
        "kernel/rcu/tree.c:rcu_is_idle_cpu"
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
  "name": "rcu_dynticks_snap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580637093,
      "name": "rcu_dynticks_snap",
      "external": false,
      "loc": "kernel/rcu/tree.c:289",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs"
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
  "name": "rcu_dynticks_snap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580706613,
      "name": "rcu_dynticks_snap",
      "external": false,
      "loc": "kernel/rcu/tree.c:270",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs"
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
  "name": "rcu_dynticks_snap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580772757,
      "name": "rcu_dynticks_snap",
      "external": false,
      "loc": "kernel/rcu/tree.c:271",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs"
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
int rcu_dynticks_snap(struct rcu_data * rdp)
```

```json
{
  "name": "rcu_dynticks_snap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491267760,
      "name": "rcu_dynticks_snap",
      "external": true,
      "loc": "kernel/rcu/tree.c:308",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491272352,
      "name": "rcu_dynticks_snap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int rcu_dynticks_snap(struct rcu_data * rdp)
```

```json
{
  "name": "rcu_dynticks_snap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225267968,
      "name": "rcu_dynticks_snap",
      "external": true,
      "loc": "kernel/rcu/tree.c:308",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225281576,
      "name": "rcu_dynticks_snap",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int rcu_dynticks_snap(struct rcu_data * rdp)
```

```json
{
  "name": "rcu_dynticks_snap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284160112,
      "name": "rcu_dynticks_snap",
      "external": true,
      "loc": "kernel/rcu/tree.c:308",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284177888,
      "name": "rcu_dynticks_snap",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int rcu_dynticks_snap(struct rcu_data * rdp)
```

```json
{
  "name": "rcu_dynticks_snap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271784320,
      "name": "rcu_dynticks_snap",
      "external": true,
      "loc": "kernel/rcu/tree.c:308",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271793790,
      "name": "rcu_dynticks_snap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int rcu_dynticks_snap(struct rcu_data * rdp)
```

```json
{
  "name": "rcu_dynticks_snap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580021551,
      "name": "rcu_dynticks_snap",
      "external": true,
      "loc": "kernel/rcu/tree.c:308",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580031200,
      "name": "rcu_dynticks_snap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int rcu_dynticks_snap(struct rcu_data * rdp)
```

```json
{
  "name": "rcu_dynticks_snap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579962783,
      "name": "rcu_dynticks_snap",
      "external": true,
      "loc": "kernel/rcu/tree.c:308",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579975616,
      "name": "rcu_dynticks_snap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int rcu_dynticks_snap(struct rcu_data * rdp)
```

```json
{
  "name": "rcu_dynticks_snap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580013087,
      "name": "rcu_dynticks_snap",
      "external": true,
      "loc": "kernel/rcu/tree.c:308",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022736,
      "name": "rcu_dynticks_snap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int rcu_dynticks_snap(struct rcu_data * rdp)
```

```json
{
  "name": "rcu_dynticks_snap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580057839,
      "name": "rcu_dynticks_snap",
      "external": true,
      "loc": "kernel/rcu/tree.c:308",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580072224,
      "name": "rcu_dynticks_snap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int rcu_dynticks_snap(struct rcu_dynticks * rdtp)
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
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rcu_data * rdp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct rcu_dynticks * rdtp</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int rcu_dynticks_snap(struct rcu_data * rdp)
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
