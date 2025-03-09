# Function: <code>unwind_get_return_address</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
long unsigned int unwind_get_return_address(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579277824,
      "name": "unwind_get_return_address",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:55",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/stacktrace.c:__save_stack_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579277824,
      "name": "unwind_get_return_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
long unsigned int unwind_get_return_address(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579275008,
      "name": "unwind_get_return_address",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:69",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/stacktrace.c:__save_stack_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275008,
      "name": "unwind_get_return_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
long unsigned int unwind_get_return_address(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579293568,
      "name": "unwind_get_return_address",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:13",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable",
        "arch/x86/kernel/stacktrace.c:__save_stack_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579293568,
      "name": "unwind_get_return_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
long unsigned int unwind_get_return_address(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579305424,
      "name": "unwind_get_return_address",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:13",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable",
        "arch/x86/kernel/stacktrace.c:__save_stack_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305424,
      "name": "unwind_get_return_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
long unsigned int unwind_get_return_address(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579329952,
      "name": "unwind_get_return_address",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:13",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable",
        "arch/x86/kernel/stacktrace.c:__save_stack_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579329952,
      "name": "unwind_get_return_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
long unsigned int unwind_get_return_address(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579345232,
      "name": "unwind_get_return_address",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:14",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579345232,
      "name": "unwind_get_return_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
long unsigned int unwind_get_return_address(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579349568,
      "name": "unwind_get_return_address",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:14",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579349568,
      "name": "unwind_get_return_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
long unsigned int unwind_get_return_address(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579379280,
      "name": "unwind_get_return_address",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:14",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579379280,
      "name": "unwind_get_return_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
long unsigned int unwind_get_return_address(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579377920,
      "name": "unwind_get_return_address",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:14",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579377920,
      "name": "unwind_get_return_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
long unsigned int unwind_get_return_address(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579381536,
      "name": "unwind_get_return_address",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:14",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579381536,
      "name": "unwind_get_return_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
long unsigned int unwind_get_return_address(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579443184,
      "name": "unwind_get_return_address",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:14",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579443184,
      "name": "unwind_get_return_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
long unsigned int unwind_get_return_address(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579512832,
      "name": "unwind_get_return_address",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:14",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/process.c:__get_wchan",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579512832,
      "name": "unwind_get_return_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
long unsigned int unwind_get_return_address(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579611888,
      "name": "unwind_get_return_address",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:14",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/process.c:__get_wchan",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611888,
      "name": "unwind_get_return_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
long unsigned int unwind_get_return_address(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579624496,
      "name": "unwind_get_return_address",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:14",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/process.c:__get_wchan",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579624496,
      "name": "unwind_get_return_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
long unsigned int unwind_get_return_address(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579653552,
      "name": "unwind_get_return_address",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:14",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/process.c:__get_wchan",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653552,
      "name": "unwind_get_return_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int unwind_get_return_address(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579345472,
      "name": "unwind_get_return_address",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:14",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579345472,
      "name": "unwind_get_return_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
long unsigned int unwind_get_return_address(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579277680,
      "name": "unwind_get_return_address",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:14",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579277680,
      "name": "unwind_get_return_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
long unsigned int unwind_get_return_address(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579345392,
      "name": "unwind_get_return_address",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:14",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579345392,
      "name": "unwind_get_return_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
long unsigned int unwind_get_return_address(struct unwind_state * state)
```

```json
{
  "name": "unwind_get_return_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579353840,
      "name": "unwind_get_return_address",
      "external": true,
      "loc": "arch/x86/kernel/unwind_frame.c:14",
      "file": "arch/x86/kernel/unwind_frame.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_kernel",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable",
        "arch/x86/kernel/stacktrace.c:arch_stack_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579353840,
      "name": "unwind_get_return_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
long unsigned int unwind_get_return_address(struct unwind_state * state)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
long unsigned int unwind_get_return_address(struct unwind_state * state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int unwind_get_return_address(struct unwind_state * state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int unwind_get_return_address(struct unwind_state * state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int unwind_get_return_address(struct unwind_state * state)
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
