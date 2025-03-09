# Function: <code>ftrace_graph_get_ret_stack</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ftrace_ret_stack * ftrace_graph_get_ret_stack(struct task_struct * task, int idx)
```

```json
{
  "name": "ftrace_graph_get_ret_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580550736,
      "name": "ftrace_graph_get_ret_stack",
      "external": true,
      "loc": "kernel/trace/fgraph.c:247",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:profile_graph_return",
        "kernel/trace/ftrace.c:profile_graph_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580550736,
      "name": "ftrace_graph_get_ret_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct ftrace_ret_stack * ftrace_graph_get_ret_stack(struct task_struct * task, int idx)
```

```json
{
  "name": "ftrace_graph_get_ret_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580607664,
      "name": "ftrace_graph_get_ret_stack",
      "external": true,
      "loc": "kernel/trace/fgraph.c:247",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:profile_graph_return",
        "kernel/trace/ftrace.c:profile_graph_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580607664,
      "name": "ftrace_graph_get_ret_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct ftrace_ret_stack * ftrace_graph_get_ret_stack(struct task_struct * task, int idx)
```

```json
{
  "name": "ftrace_graph_get_ret_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580654656,
      "name": "ftrace_graph_get_ret_stack",
      "external": true,
      "loc": "kernel/trace/fgraph.c:247",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:profile_graph_return",
        "kernel/trace/ftrace.c:profile_graph_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580654656,
      "name": "ftrace_graph_get_ret_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct ftrace_ret_stack * ftrace_graph_get_ret_stack(struct task_struct * task, int idx)
```

```json
{
  "name": "ftrace_graph_get_ret_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580756944,
      "name": "ftrace_graph_get_ret_stack",
      "external": true,
      "loc": "kernel/trace/fgraph.c:270",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:profile_graph_return",
        "kernel/trace/ftrace.c:profile_graph_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580756944,
      "name": "ftrace_graph_get_ret_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct ftrace_ret_stack * ftrace_graph_get_ret_stack(struct task_struct * task, int idx)
```

```json
{
  "name": "ftrace_graph_get_ret_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580745024,
      "name": "ftrace_graph_get_ret_stack",
      "external": true,
      "loc": "kernel/trace/fgraph.c:270",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:profile_graph_return",
        "kernel/trace/ftrace.c:profile_graph_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580745024,
      "name": "ftrace_graph_get_ret_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct ftrace_ret_stack * ftrace_graph_get_ret_stack(struct task_struct * task, int idx)
```

```json
{
  "name": "ftrace_graph_get_ret_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580749520,
      "name": "ftrace_graph_get_ret_stack",
      "external": true,
      "loc": "kernel/trace/fgraph.c:270",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:profile_graph_return",
        "kernel/trace/ftrace.c:profile_graph_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580749520,
      "name": "ftrace_graph_get_ret_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct ftrace_ret_stack * ftrace_graph_get_ret_stack(struct task_struct * task, int idx)
```

```json
{
  "name": "ftrace_graph_get_ret_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580932944,
      "name": "ftrace_graph_get_ret_stack",
      "external": true,
      "loc": "kernel/trace/fgraph.c:270",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:profile_graph_return",
        "kernel/trace/ftrace.c:profile_graph_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580932944,
      "name": "ftrace_graph_get_ret_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct ftrace_ret_stack * ftrace_graph_get_ret_stack(struct task_struct * task, int idx)
```

```json
{
  "name": "ftrace_graph_get_ret_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581172880,
      "name": "ftrace_graph_get_ret_stack",
      "external": true,
      "loc": "kernel/trace/fgraph.c:281",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:profile_graph_return",
        "kernel/trace/ftrace.c:profile_graph_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581172880,
      "name": "ftrace_graph_get_ret_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct ftrace_ret_stack * ftrace_graph_get_ret_stack(struct task_struct * task, int idx)
```

```json
{
  "name": "ftrace_graph_get_ret_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581487824,
      "name": "ftrace_graph_get_ret_stack",
      "external": true,
      "loc": "kernel/trace/fgraph.c:281",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:profile_graph_return",
        "kernel/trace/ftrace.c:profile_graph_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581487824,
      "name": "ftrace_graph_get_ret_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct ftrace_ret_stack * ftrace_graph_get_ret_stack(struct task_struct * task, int idx)
```

```json
{
  "name": "ftrace_graph_get_ret_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581605760,
      "name": "ftrace_graph_get_ret_stack",
      "external": true,
      "loc": "kernel/trace/fgraph.c:306",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:profile_graph_return",
        "kernel/trace/ftrace.c:profile_graph_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581605760,
      "name": "ftrace_graph_get_ret_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct ftrace_ret_stack * ftrace_graph_get_ret_stack(struct task_struct * task, int idx)
```

```json
{
  "name": "ftrace_graph_get_ret_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581718192,
      "name": "ftrace_graph_get_ret_stack",
      "external": true,
      "loc": "kernel/trace/fgraph.c:306",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:profile_graph_return",
        "kernel/trace/ftrace.c:profile_graph_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581718192,
      "name": "ftrace_graph_get_ret_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct ftrace_ret_stack * ftrace_graph_get_ret_stack(struct task_struct * task, int idx)
```

```json
{
  "name": "ftrace_graph_get_ret_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491959224,
      "name": "ftrace_graph_get_ret_stack",
      "external": true,
      "loc": "kernel/trace/fgraph.c:247",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/stacktrace.c:unwind_frame",
        "kernel/trace/ftrace.c:profile_graph_return",
        "kernel/trace/ftrace.c:profile_graph_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491959224,
      "name": "ftrace_graph_get_ret_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct ftrace_ret_stack * ftrace_graph_get_ret_stack(struct task_struct * task, int idx)
```

```json
{
  "name": "ftrace_graph_get_ret_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225894780,
      "name": "ftrace_graph_get_ret_stack",
      "external": true,
      "loc": "kernel/trace/fgraph.c:247",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:profile_graph_return",
        "kernel/trace/ftrace.c:profile_graph_return",
        "kernel/trace/ftrace.c:profile_graph_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225894780,
      "name": "ftrace_graph_get_ret_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct ftrace_ret_stack * ftrace_graph_get_ret_stack(struct task_struct * task, int idx)
```

```json
{
  "name": "ftrace_graph_get_ret_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285065376,
      "name": "ftrace_graph_get_ret_stack",
      "external": true,
      "loc": "kernel/trace/fgraph.c:247",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:profile_graph_return",
        "kernel/trace/ftrace.c:profile_graph_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285065376,
      "name": "ftrace_graph_get_ret_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct ftrace_ret_stack * ftrace_graph_get_ret_stack(struct task_struct * task, int idx)
```

```json
{
  "name": "ftrace_graph_get_ret_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272233158,
      "name": "ftrace_graph_get_ret_stack",
      "external": true,
      "loc": "kernel/trace/fgraph.c:247",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:profile_graph_return",
        "kernel/trace/ftrace.c:profile_graph_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272233158,
      "name": "ftrace_graph_get_ret_stack",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct ftrace_ret_stack * ftrace_graph_get_ret_stack(struct task_struct * task, int idx)
```

```json
{
  "name": "ftrace_graph_get_ret_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580623456,
      "name": "ftrace_graph_get_ret_stack",
      "external": true,
      "loc": "kernel/trace/fgraph.c:247",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:profile_graph_return",
        "kernel/trace/ftrace.c:profile_graph_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580623456,
      "name": "ftrace_graph_get_ret_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct ftrace_ret_stack * ftrace_graph_get_ret_stack(struct task_struct * task, int idx)
```

```json
{
  "name": "ftrace_graph_get_ret_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580569712,
      "name": "ftrace_graph_get_ret_stack",
      "external": true,
      "loc": "kernel/trace/fgraph.c:247",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:profile_graph_return",
        "kernel/trace/ftrace.c:profile_graph_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580569712,
      "name": "ftrace_graph_get_ret_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct ftrace_ret_stack * ftrace_graph_get_ret_stack(struct task_struct * task, int idx)
```

```json
{
  "name": "ftrace_graph_get_ret_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580614704,
      "name": "ftrace_graph_get_ret_stack",
      "external": true,
      "loc": "kernel/trace/fgraph.c:247",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:profile_graph_return",
        "kernel/trace/ftrace.c:profile_graph_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580614704,
      "name": "ftrace_graph_get_ret_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct ftrace_ret_stack * ftrace_graph_get_ret_stack(struct task_struct * task, int idx)
```

```json
{
  "name": "ftrace_graph_get_ret_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580672160,
      "name": "ftrace_graph_get_ret_stack",
      "external": true,
      "loc": "kernel/trace/fgraph.c:247",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:profile_graph_return",
        "kernel/trace/ftrace.c:profile_graph_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580672160,
      "name": "ftrace_graph_get_ret_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct ftrace_ret_stack * ftrace_graph_get_ret_stack(struct task_struct * task, int idx)
```
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
