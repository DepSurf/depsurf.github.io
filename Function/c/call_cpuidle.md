# Function: <code>call_cpuidle</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int call_cpuidle(struct cpuidle_driver * drv, struct cpuidle_device * dev, int next_state)
```

```json
{
  "name": "call_cpuidle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579647264,
      "name": "call_cpuidle",
      "external": false,
      "loc": "kernel/sched/idle.c:97",
      "file": "kernel/sched/idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:cpu_startup_entry",
        "kernel/sched/idle.c:cpu_startup_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579647264,
      "name": "call_cpuidle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
int call_cpuidle(struct cpuidle_driver * drv, struct cpuidle_device * dev, int next_state)
```

```json
{
  "name": "call_cpuidle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579662576,
      "name": "call_cpuidle",
      "external": false,
      "loc": "kernel/sched/idle.c:98",
      "file": "kernel/sched/idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:cpu_startup_entry",
        "kernel/sched/idle.c:cpu_startup_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579662576,
      "name": "call_cpuidle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
int call_cpuidle(struct cpuidle_driver * drv, struct cpuidle_device * dev, int next_state)
```

```json
{
  "name": "call_cpuidle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579686832,
      "name": "call_cpuidle",
      "external": false,
      "loc": "kernel/sched/idle.c:101",
      "file": "kernel/sched/idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686832,
      "name": "call_cpuidle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int call_cpuidle(struct cpuidle_driver * drv, struct cpuidle_device * dev, int next_state)
```

```json
{
  "name": "call_cpuidle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579673040,
      "name": "call_cpuidle",
      "external": false,
      "loc": "kernel/sched/idle.c:103",
      "file": "kernel/sched/idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579673040,
      "name": "call_cpuidle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int call_cpuidle(struct cpuidle_driver * drv, struct cpuidle_device * dev, int next_state)
```

```json
{
  "name": "call_cpuidle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579703840,
      "name": "call_cpuidle",
      "external": false,
      "loc": "kernel/sched/idle.c:103",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579703840,
      "name": "call_cpuidle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int call_cpuidle(struct cpuidle_driver * drv, struct cpuidle_device * dev, int next_state)
```

```json
{
  "name": "call_cpuidle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579648304,
      "name": "call_cpuidle",
      "external": false,
      "loc": "kernel/sched/idle.c:98",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579648304,
      "name": "call_cpuidle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int call_cpuidle(struct cpuidle_driver * drv, struct cpuidle_device * dev, int next_state)
```

```json
{
  "name": "call_cpuidle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579685616,
      "name": "call_cpuidle",
      "external": false,
      "loc": "kernel/sched/idle.c:98",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685616,
      "name": "call_cpuidle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int call_cpuidle(struct cpuidle_driver * drv, struct cpuidle_device * dev, int next_state)
```

```json
{
  "name": "call_cpuidle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579719648,
      "name": "call_cpuidle",
      "external": false,
      "loc": "kernel/sched/idle.c:99",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579719648,
      "name": "call_cpuidle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int call_cpuidle(struct cpuidle_driver * drv, struct cpuidle_device * dev, int next_state)
```

```json
{
  "name": "call_cpuidle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579762160,
      "name": "call_cpuidle",
      "external": false,
      "loc": "kernel/sched/idle.c:99",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579762160,
      "name": "call_cpuidle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
  "name": "call_cpuidle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579796097,
      "name": "call_cpuidle",
      "external": false,
      "loc": "kernel/sched/idle.c:108",
      "file": "kernel/sched/idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:cpuidle_idle_call",
        "kernel/sched/idle.c:cpuidle_idle_call"
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
  "name": "call_cpuidle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579786904,
      "name": "call_cpuidle",
      "external": false,
      "loc": "kernel/sched/idle.c:140",
      "file": "kernel/sched/idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:cpuidle_idle_call",
        "kernel/sched/idle.c:cpuidle_idle_call"
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
  "name": "call_cpuidle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579795032,
      "name": "call_cpuidle",
      "external": false,
      "loc": "kernel/sched/idle.c:140",
      "file": "kernel/sched/idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:cpuidle_idle_call",
        "kernel/sched/idle.c:cpuidle_idle_call"
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
  "name": "call_cpuidle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579890952,
      "name": "call_cpuidle",
      "external": false,
      "loc": "kernel/sched/idle.c:140",
      "file": "kernel/sched/idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:cpuidle_idle_call",
        "kernel/sched/idle.c:cpuidle_idle_call"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int call_cpuidle(struct cpuidle_driver * drv, struct cpuidle_device * dev, int next_state)
```

```json
{
  "name": "call_cpuidle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580086816,
      "name": "call_cpuidle",
      "external": false,
      "loc": "kernel/sched/idle.c:137",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:cpuidle_idle_call",
        "kernel/sched/build_policy.c:cpuidle_idle_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580086816,
      "name": "call_cpuidle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "call_cpuidle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580277037,
      "name": "call_cpuidle",
      "external": false,
      "loc": "kernel/sched/idle.c:137",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:cpuidle_idle_call",
        "kernel/sched/build_policy.c:cpuidle_idle_call"
      ],
      "caller_func": [
        "kernel/sched/build_policy.c:cpuidle_idle_call",
        "kernel/sched/build_policy.c:cpuidle_idle_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580255936,
      "name": "call_cpuidle.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
int call_cpuidle(struct cpuidle_driver * drv, struct cpuidle_device * dev, int next_state)
```

```json
{
  "name": "call_cpuidle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580321824,
      "name": "call_cpuidle",
      "external": false,
      "loc": "kernel/sched/idle.c:116",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:cpuidle_idle_call",
        "kernel/sched/build_policy.c:cpuidle_idle_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580321824,
      "name": "call_cpuidle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
int call_cpuidle(struct cpuidle_driver * drv, struct cpuidle_device * dev, int next_state)
```

```json
{
  "name": "call_cpuidle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580375216,
      "name": "call_cpuidle",
      "external": false,
      "loc": "kernel/sched/idle.c:116",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:cpuidle_idle_call",
        "kernel/sched/build_policy.c:cpuidle_idle_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580375216,
      "name": "call_cpuidle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
int call_cpuidle(struct cpuidle_driver * drv, struct cpuidle_device * dev, int next_state)
```

```json
{
  "name": "call_cpuidle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490941032,
      "name": "call_cpuidle",
      "external": false,
      "loc": "kernel/sched/idle.c:99",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490941032,
      "name": "call_cpuidle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int call_cpuidle(struct cpuidle_driver * drv, struct cpuidle_device * dev, int next_state)
```

```json
{
  "name": "call_cpuidle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224959164,
      "name": "call_cpuidle",
      "external": false,
      "loc": "kernel/sched/idle.c:99",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224959164,
      "name": "call_cpuidle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
int call_cpuidle(struct cpuidle_driver * drv, struct cpuidle_device * dev, int next_state)
```

```json
{
  "name": "call_cpuidle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283796144,
      "name": "call_cpuidle",
      "external": false,
      "loc": "kernel/sched/idle.c:99",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283796144,
      "name": "call_cpuidle",
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
  "name": "call_cpuidle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "call_cpuidle",
      "external": false,
      "loc": "kernel/sched/idle.c:99",
      "file": "kernel/sched/idle.c",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int call_cpuidle(struct cpuidle_driver * drv, struct cpuidle_device * dev, int next_state)
```

```json
{
  "name": "call_cpuidle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579738080,
      "name": "call_cpuidle",
      "external": false,
      "loc": "kernel/sched/idle.c:99",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579738080,
      "name": "call_cpuidle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int call_cpuidle(struct cpuidle_driver * drv, struct cpuidle_device * dev, int next_state)
```

```json
{
  "name": "call_cpuidle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579668432,
      "name": "call_cpuidle",
      "external": false,
      "loc": "kernel/sched/idle.c:99",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579668432,
      "name": "call_cpuidle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int call_cpuidle(struct cpuidle_driver * drv, struct cpuidle_device * dev, int next_state)
```

```json
{
  "name": "call_cpuidle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579722528,
      "name": "call_cpuidle",
      "external": false,
      "loc": "kernel/sched/idle.c:99",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579722528,
      "name": "call_cpuidle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int call_cpuidle(struct cpuidle_driver * drv, struct cpuidle_device * dev, int next_state)
```

```json
{
  "name": "call_cpuidle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579769888,
      "name": "call_cpuidle",
      "external": false,
      "loc": "kernel/sched/idle.c:99",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579769888,
      "name": "call_cpuidle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int call_cpuidle(struct cpuidle_driver * drv, struct cpuidle_device * dev, int next_state)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int call_cpuidle(struct cpuidle_driver * drv, struct cpuidle_device * dev, int next_state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int call_cpuidle(struct cpuidle_driver * drv, struct cpuidle_device * dev, int next_state)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int call_cpuidle(struct cpuidle_driver * drv, struct cpuidle_device * dev, int next_state)
```
</details>
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
int call_cpuidle(struct cpuidle_driver * drv, struct cpuidle_device * dev, int next_state)
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
