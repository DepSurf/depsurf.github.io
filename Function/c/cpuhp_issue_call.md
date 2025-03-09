# Function: <code>cpuhp_issue_call</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, int (*)(unsigned int) cb, bool bringup)
```

```json
{
  "name": "cpuhp_issue_call",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579386032,
      "name": "cpuhp_issue_call",
      "external": false,
      "loc": "kernel/cpu.c:1401",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_setup_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579386032,
      "name": "cpuhp_issue_call",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_issue_call",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579406096,
      "name": "cpuhp_issue_call",
      "external": false,
      "loc": "kernel/cpu.c:1368",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/cpu.c:cpuhp_rollback_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579406096,
      "name": "cpuhp_issue_call",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_issue_call",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579393808,
      "name": "cpuhp_issue_call",
      "external": false,
      "loc": "kernel/cpu.c:1292",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked",
        "kernel/cpu.c:cpuhp_rollback_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579393808,
      "name": "cpuhp_issue_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_issue_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579421536,
      "name": "cpuhp_issue_call",
      "external": false,
      "loc": "kernel/cpu.c:1476",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked",
        "kernel/cpu.c:cpuhp_rollback_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579421536,
      "name": "cpuhp_issue_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_issue_call",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579436304,
      "name": "cpuhp_issue_call",
      "external": false,
      "loc": "kernel/cpu.c:1558",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked",
        "kernel/cpu.c:cpuhp_rollback_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579436304,
      "name": "cpuhp_issue_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_issue_call",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579469264,
      "name": "cpuhp_issue_call",
      "external": false,
      "loc": "kernel/cpu.c:1580",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked",
        "kernel/cpu.c:cpuhp_rollback_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579469264,
      "name": "cpuhp_issue_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_issue_call",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579487136,
      "name": "cpuhp_issue_call",
      "external": false,
      "loc": "kernel/cpu.c:1606",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked",
        "kernel/cpu.c:cpuhp_rollback_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579487136,
      "name": "cpuhp_issue_call",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_issue_call",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579513072,
      "name": "cpuhp_issue_call",
      "external": false,
      "loc": "kernel/cpu.c:1621",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked",
        "kernel/cpu.c:cpuhp_rollback_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513072,
      "name": "cpuhp_issue_call",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_issue_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579541952,
      "name": "cpuhp_issue_call",
      "external": false,
      "loc": "kernel/cpu.c:1752",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked",
        "kernel/cpu.c:cpuhp_rollback_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579541952,
      "name": "cpuhp_issue_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_issue_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579523664,
      "name": "cpuhp_issue_call",
      "external": false,
      "loc": "kernel/cpu.c:1763",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked",
        "kernel/cpu.c:cpuhp_rollback_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579523664,
      "name": "cpuhp_issue_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_issue_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579527024,
      "name": "cpuhp_issue_call",
      "external": false,
      "loc": "kernel/cpu.c:1867",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked",
        "kernel/cpu.c:cpuhp_rollback_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579527024,
      "name": "cpuhp_issue_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_issue_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579598976,
      "name": "cpuhp_issue_call",
      "external": false,
      "loc": "kernel/cpu.c:1897",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked",
        "kernel/cpu.c:cpuhp_rollback_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579598976,
      "name": "cpuhp_issue_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_issue_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579691184,
      "name": "cpuhp_issue_call",
      "external": false,
      "loc": "kernel/cpu.c:1919",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked",
        "kernel/cpu.c:cpuhp_rollback_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691184,
      "name": "cpuhp_issue_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_issue_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579815008,
      "name": "cpuhp_issue_call",
      "external": false,
      "loc": "kernel/cpu.c:1943",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked",
        "kernel/cpu.c:cpuhp_rollback_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579815008,
      "name": "cpuhp_issue_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_issue_call",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579862928,
      "name": "cpuhp_issue_call",
      "external": false,
      "loc": "kernel/cpu.c:2328",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked",
        "kernel/cpu.c:cpuhp_rollback_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579862928,
      "name": "cpuhp_issue_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_issue_call",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579900832,
      "name": "cpuhp_issue_call",
      "external": false,
      "loc": "kernel/cpu.c:2374",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked",
        "kernel/cpu.c:cpuhp_rollback_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900832,
      "name": "cpuhp_issue_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_issue_call",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490649392,
      "name": "cpuhp_issue_call",
      "external": false,
      "loc": "kernel/cpu.c:1621",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked",
        "kernel/cpu.c:cpuhp_rollback_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490649392,
      "name": "cpuhp_issue_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_issue_call",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224726032,
      "name": "cpuhp_issue_call",
      "external": false,
      "loc": "kernel/cpu.c:1621",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked",
        "kernel/cpu.c:cpuhp_rollback_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224726032,
      "name": "cpuhp_issue_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_issue_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283470544,
      "name": "cpuhp_issue_call",
      "external": false,
      "loc": "kernel/cpu.c:1621",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked",
        "kernel/cpu.c:cpuhp_rollback_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283470544,
      "name": "cpuhp_issue_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
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
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_issue_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271398328,
      "name": "cpuhp_issue_call",
      "external": false,
      "loc": "kernel/cpu.c:1621",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked",
        "kernel/cpu.c:cpuhp_rollback_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271398328,
      "name": "cpuhp_issue_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_issue_call",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579486736,
      "name": "cpuhp_issue_call",
      "external": false,
      "loc": "kernel/cpu.c:1621",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked",
        "kernel/cpu.c:cpuhp_rollback_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579486736,
      "name": "cpuhp_issue_call",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_issue_call",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579415616,
      "name": "cpuhp_issue_call",
      "external": false,
      "loc": "kernel/cpu.c:1621",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked",
        "kernel/cpu.c:cpuhp_rollback_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579415616,
      "name": "cpuhp_issue_call",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_issue_call",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579486656,
      "name": "cpuhp_issue_call",
      "external": false,
      "loc": "kernel/cpu.c:1621",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked",
        "kernel/cpu.c:cpuhp_rollback_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579486656,
      "name": "cpuhp_issue_call",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_issue_call",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579518800,
      "name": "cpuhp_issue_call",
      "external": false,
      "loc": "kernel/cpu.c:1621",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked",
        "kernel/cpu.c:cpuhp_rollback_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579518800,
      "name": "cpuhp_issue_call",
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, int (*)(unsigned int) cb, bool bringup)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct hlist_node * node</code>
</li>
<li>
<b>Param removed. </b>
<code>int (*)(unsigned int) cb</code>
</li>
<li>
<b>Param reordered. </b>
<code>cpu, state, cb, bringup</code> ➡️ <code>cpu, state, bringup, node</code>
</li>
</ul>
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
