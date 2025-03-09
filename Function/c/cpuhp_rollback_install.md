# Function: <code>cpuhp_rollback_install</code>

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
  "name": "cpuhp_rollback_install",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579386521,
      "name": "cpuhp_rollback_install",
      "external": false,
      "loc": "kernel/cpu.c:1429",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_setup_state"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_rollback_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579406320,
      "name": "cpuhp_rollback_install",
      "external": false,
      "loc": "kernel/cpu.c:1398",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579406320,
      "name": "cpuhp_rollback_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_rollback_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579394032,
      "name": "cpuhp_rollback_install",
      "external": false,
      "loc": "kernel/cpu.c:1322",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394032,
      "name": "cpuhp_rollback_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_rollback_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579421824,
      "name": "cpuhp_rollback_install",
      "external": false,
      "loc": "kernel/cpu.c:1510",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579421824,
      "name": "cpuhp_rollback_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_rollback_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579436592,
      "name": "cpuhp_rollback_install",
      "external": false,
      "loc": "kernel/cpu.c:1592",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579436592,
      "name": "cpuhp_rollback_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_rollback_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579469552,
      "name": "cpuhp_rollback_install",
      "external": false,
      "loc": "kernel/cpu.c:1614",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579469552,
      "name": "cpuhp_rollback_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_rollback_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579487408,
      "name": "cpuhp_rollback_install",
      "external": false,
      "loc": "kernel/cpu.c:1640",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579487408,
      "name": "cpuhp_rollback_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_rollback_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579513344,
      "name": "cpuhp_rollback_install",
      "external": false,
      "loc": "kernel/cpu.c:1655",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513344,
      "name": "cpuhp_rollback_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_rollback_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579542080,
      "name": "cpuhp_rollback_install",
      "external": false,
      "loc": "kernel/cpu.c:1786",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542080,
      "name": "cpuhp_rollback_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_rollback_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579523792,
      "name": "cpuhp_rollback_install",
      "external": false,
      "loc": "kernel/cpu.c:1797",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579523792,
      "name": "cpuhp_rollback_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_rollback_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579527440,
      "name": "cpuhp_rollback_install",
      "external": false,
      "loc": "kernel/cpu.c:1900",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579527440,
      "name": "cpuhp_rollback_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_rollback_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579599344,
      "name": "cpuhp_rollback_install",
      "external": false,
      "loc": "kernel/cpu.c:1930",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599344,
      "name": "cpuhp_rollback_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_rollback_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579691568,
      "name": "cpuhp_rollback_install",
      "external": false,
      "loc": "kernel/cpu.c:1952",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691568,
      "name": "cpuhp_rollback_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_rollback_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579815408,
      "name": "cpuhp_rollback_install",
      "external": false,
      "loc": "kernel/cpu.c:1976",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579815408,
      "name": "cpuhp_rollback_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_rollback_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579863312,
      "name": "cpuhp_rollback_install",
      "external": false,
      "loc": "kernel/cpu.c:2361",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579863312,
      "name": "cpuhp_rollback_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_rollback_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579901216,
      "name": "cpuhp_rollback_install",
      "external": false,
      "loc": "kernel/cpu.c:2407",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579901216,
      "name": "cpuhp_rollback_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_rollback_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490649768,
      "name": "cpuhp_rollback_install",
      "external": false,
      "loc": "kernel/cpu.c:1655",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490649768,
      "name": "cpuhp_rollback_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_rollback_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224726352,
      "name": "cpuhp_rollback_install",
      "external": false,
      "loc": "kernel/cpu.c:1655",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224726352,
      "name": "cpuhp_rollback_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_rollback_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283471024,
      "name": "cpuhp_rollback_install",
      "external": false,
      "loc": "kernel/cpu.c:1655",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283471024,
      "name": "cpuhp_rollback_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_rollback_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271398618,
      "name": "cpuhp_rollback_install",
      "external": false,
      "loc": "kernel/cpu.c:1655",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271398618,
      "name": "cpuhp_rollback_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_rollback_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579487008,
      "name": "cpuhp_rollback_install",
      "external": false,
      "loc": "kernel/cpu.c:1655",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579487008,
      "name": "cpuhp_rollback_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_rollback_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579415888,
      "name": "cpuhp_rollback_install",
      "external": false,
      "loc": "kernel/cpu.c:1655",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579415888,
      "name": "cpuhp_rollback_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_rollback_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579486928,
      "name": "cpuhp_rollback_install",
      "external": false,
      "loc": "kernel/cpu.c:1655",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579486928,
      "name": "cpuhp_rollback_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_rollback_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579519072,
      "name": "cpuhp_rollback_install",
      "external": false,
      "loc": "kernel/cpu.c:1655",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579519072,
      "name": "cpuhp_rollback_install",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node * node)
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
