# Function: <code>cpuhp_invoke_callback</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state step, int (*)(unsigned int) cb)
```

```json
{
  "name": "cpuhp_invoke_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579384448,
      "name": "cpuhp_invoke_callback",
      "external": false,
      "loc": "kernel/cpu.c:90",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:notify_cpu_starting",
        "kernel/cpu.c:take_cpu_down",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_up_callbacks",
        "kernel/cpu.c:cpuhp_up_callbacks",
        "kernel/cpu.c:cpuhp_down_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579384448,
      "name": "cpuhp_invoke_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_invoke_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579404304,
      "name": "cpuhp_invoke_callback",
      "external": false,
      "loc": "kernel/cpu.c:122",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:notify_cpu_starting",
        "kernel/cpu.c:take_cpu_down",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_up_callbacks",
        "kernel/cpu.c:cpuhp_up_callbacks",
        "kernel/cpu.c:cpuhp_down_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579404304,
      "name": "cpuhp_invoke_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 941
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
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node)
```

```json
{
  "name": "cpuhp_invoke_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579391616,
      "name": "cpuhp_invoke_callback",
      "external": false,
      "loc": "kernel/cpu.c:131",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:notify_cpu_starting",
        "kernel/cpu.c:take_cpu_down",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_up_callbacks",
        "kernel/cpu.c:cpuhp_up_callbacks",
        "kernel/cpu.c:cpuhp_down_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579391616,
      "name": "cpuhp_invoke_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 931
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
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node, struct hlist_node * * lastp)
```

```json
{
  "name": "cpuhp_invoke_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579419392,
      "name": "cpuhp_invoke_callback",
      "external": false,
      "loc": "kernel/cpu.c:157",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpuhp_issue_call",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:notify_cpu_starting",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:take_cpu_down",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_thread_fun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579419392,
      "name": "cpuhp_invoke_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1379
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
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node, struct hlist_node * * lastp)
```

```json
{
  "name": "cpuhp_invoke_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579434192,
      "name": "cpuhp_invoke_callback",
      "external": false,
      "loc": "kernel/cpu.c:145",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:notify_cpu_starting",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:take_cpu_down",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_thread_fun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579434192,
      "name": "cpuhp_invoke_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1334
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
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node, struct hlist_node * * lastp)
```

```json
{
  "name": "cpuhp_invoke_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579467760,
      "name": "cpuhp_invoke_callback",
      "external": false,
      "loc": "kernel/cpu.c:143",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:notify_cpu_starting",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:take_cpu_down",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_thread_fun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579467760,
      "name": "cpuhp_invoke_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1334
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
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node, struct hlist_node * * lastp)
```

```json
{
  "name": "cpuhp_invoke_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579485568,
      "name": "cpuhp_invoke_callback",
      "external": false,
      "loc": "kernel/cpu.c:144",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:notify_cpu_starting",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:take_cpu_down",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_thread_fun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579485568,
      "name": "cpuhp_invoke_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1393
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
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node, struct hlist_node * * lastp)
```

```json
{
  "name": "cpuhp_invoke_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579511504,
      "name": "cpuhp_invoke_callback",
      "external": false,
      "loc": "kernel/cpu.c:147",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:notify_cpu_starting",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:take_cpu_down",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_thread_fun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579511504,
      "name": "cpuhp_invoke_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1393
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
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node, struct hlist_node * * lastp)
```

```json
{
  "name": "cpuhp_invoke_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579540096,
      "name": "cpuhp_invoke_callback",
      "external": false,
      "loc": "kernel/cpu.c:148",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpuhp_issue_call",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:notify_cpu_starting",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:take_cpu_down",
        "kernel/cpu.c:cpuhp_invoke_ap_callback",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_thread_fun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540096,
      "name": "cpuhp_invoke_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1393
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
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node, struct hlist_node * * lastp)
```

```json
{
  "name": "cpuhp_invoke_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579522176,
      "name": "cpuhp_invoke_callback",
      "external": false,
      "loc": "kernel/cpu.c:148",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpuhp_issue_call",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:notify_cpu_starting",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:take_cpu_down",
        "kernel/cpu.c:cpuhp_invoke_ap_callback",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_thread_fun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579522176,
      "name": "cpuhp_invoke_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1039
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
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node, struct hlist_node * * lastp)
```

```json
{
  "name": "cpuhp_invoke_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579525424,
      "name": "cpuhp_invoke_callback",
      "external": false,
      "loc": "kernel/cpu.c:155",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpuhp_issue_call",
        "kernel/cpu.c:cpuhp_issue_call",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:notify_cpu_starting",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:take_cpu_down",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_thread_fun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525424,
      "name": "cpuhp_invoke_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1050
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
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node, struct hlist_node * * lastp)
```

```json
{
  "name": "cpuhp_invoke_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpuhp_invoke_callback",
      "external": false,
      "loc": "kernel/cpu.c:166",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpuhp_issue_call",
        "kernel/cpu.c:cpuhp_issue_call",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:notify_cpu_starting",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:take_cpu_down",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_thread_fun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579597936,
      "name": "cpuhp_invoke_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1040
    },
    {
      "addr": 18446744071592099375,
      "name": "cpuhp_invoke_callback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node, struct hlist_node * * lastp)
```

```json
{
  "name": "cpuhp_invoke_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpuhp_invoke_callback",
      "external": false,
      "loc": "kernel/cpu.c:167",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpuhp_issue_call",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:notify_cpu_starting",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:take_cpu_down",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_thread_fun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579689888,
      "name": "cpuhp_invoke_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1284
    },
    {
      "addr": 18446744071593866866,
      "name": "cpuhp_invoke_callback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node, struct hlist_node * * lastp)
```

```json
{
  "name": "cpuhp_invoke_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpuhp_invoke_callback",
      "external": false,
      "loc": "kernel/cpu.c:167",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpuhp_issue_call",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:__cpuhp_invoke_callback_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579813216,
      "name": "cpuhp_invoke_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1314
    },
    {
      "addr": 18446744071595973501,
      "name": "cpuhp_invoke_callback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node, struct hlist_node * * lastp)
```

```json
{
  "name": "cpuhp_invoke_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpuhp_invoke_callback",
      "external": false,
      "loc": "kernel/cpu.c:170",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:__cpuhp_invoke_callback_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579861136,
      "name": "cpuhp_invoke_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1314
    },
    {
      "addr": 18446744071596491107,
      "name": "cpuhp_invoke_callback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node, struct hlist_node * * lastp)
```

```json
{
  "name": "cpuhp_invoke_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpuhp_invoke_callback",
      "external": false,
      "loc": "kernel/cpu.c:170",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:__cpuhp_invoke_callback_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899040,
      "name": "cpuhp_invoke_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1314
    },
    {
      "addr": 18446744071597387831,
      "name": "cpuhp_invoke_callback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node, struct hlist_node * * lastp)
```

```json
{
  "name": "cpuhp_invoke_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490647592,
      "name": "cpuhp_invoke_callback",
      "external": false,
      "loc": "kernel/cpu.c:147",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:notify_cpu_starting",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:take_cpu_down",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_thread_fun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490647592,
      "name": "cpuhp_invoke_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1576
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
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node, struct hlist_node * * lastp)
```

```json
{
  "name": "cpuhp_invoke_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224723608,
      "name": "cpuhp_invoke_callback",
      "external": false,
      "loc": "kernel/cpu.c:147",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:notify_cpu_starting",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:take_cpu_down",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_thread_fun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224723608,
      "name": "cpuhp_invoke_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2148
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
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node, struct hlist_node * * lastp)
```

```json
{
  "name": "cpuhp_invoke_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283468176,
      "name": "cpuhp_invoke_callback",
      "external": false,
      "loc": "kernel/cpu.c:147",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpuhp_issue_call",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:notify_cpu_starting",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:take_cpu_down",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_thread_fun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283468176,
      "name": "cpuhp_invoke_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2036
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
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node, struct hlist_node * * lastp)
```

```json
{
  "name": "cpuhp_invoke_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271397188,
      "name": "cpuhp_invoke_callback",
      "external": false,
      "loc": "kernel/cpu.c:147",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpuhp_issue_call",
        "kernel/cpu.c:cpu_up",
        "kernel/cpu.c:cpu_up",
        "kernel/cpu.c:notify_cpu_starting",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_thread_fun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271397188,
      "name": "cpuhp_invoke_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1140
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
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node, struct hlist_node * * lastp)
```

```json
{
  "name": "cpuhp_invoke_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579485168,
      "name": "cpuhp_invoke_callback",
      "external": false,
      "loc": "kernel/cpu.c:147",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:notify_cpu_starting",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:take_cpu_down",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_thread_fun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579485168,
      "name": "cpuhp_invoke_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1393
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
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node, struct hlist_node * * lastp)
```

```json
{
  "name": "cpuhp_invoke_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579414048,
      "name": "cpuhp_invoke_callback",
      "external": false,
      "loc": "kernel/cpu.c:147",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:notify_cpu_starting",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:take_cpu_down",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_thread_fun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579414048,
      "name": "cpuhp_invoke_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1393
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
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node, struct hlist_node * * lastp)
```

```json
{
  "name": "cpuhp_invoke_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579485088,
      "name": "cpuhp_invoke_callback",
      "external": false,
      "loc": "kernel/cpu.c:147",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:notify_cpu_starting",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:take_cpu_down",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_thread_fun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579485088,
      "name": "cpuhp_invoke_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1393
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
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state state, bool bringup, struct hlist_node * node, struct hlist_node * * lastp)
```

```json
{
  "name": "cpuhp_invoke_callback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579517056,
      "name": "cpuhp_invoke_callback",
      "external": false,
      "loc": "kernel/cpu.c:147",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:notify_cpu_starting",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:take_cpu_down",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_thread_fun"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579517056,
      "name": "cpuhp_invoke_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1574
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
int cpuhp_invoke_callback(unsigned int cpu, enum cpuhp_state step, int (*)(unsigned int) cb)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum cpuhp_state state</code>
</li>
<li>
<b>Param added. </b>
<code>bool bringup</code>
</li>
<li>
<b>Param added. </b>
<code>struct hlist_node * node</code>
</li>
<li>
<b>Param removed. </b>
<code>enum cpuhp_state step</code>
</li>
<li>
<b>Param removed. </b>
<code>int (*)(unsigned int) cb</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct hlist_node * * lastp</code>
</li>
</ul>
</details>
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
