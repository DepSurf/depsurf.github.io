# Function: <code>arch_stack_walk_reliable</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void * cookie, struct task_struct * task)
```

```json
{
  "name": "arch_stack_walk_reliable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579122272,
      "name": "arch_stack_walk_reliable",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:38",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579122272,
      "name": "arch_stack_walk_reliable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void * cookie, struct task_struct * task)
```

```json
{
  "name": "arch_stack_walk_reliable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579124144,
      "name": "arch_stack_walk_reliable",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:38",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579124144,
      "name": "arch_stack_walk_reliable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void * cookie, struct task_struct * task)
```

```json
{
  "name": "arch_stack_walk_reliable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579139792,
      "name": "arch_stack_walk_reliable",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:38",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579139792,
      "name": "arch_stack_walk_reliable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void * cookie, struct task_struct * task)
```

```json
{
  "name": "arch_stack_walk_reliable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579136896,
      "name": "arch_stack_walk_reliable",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:38",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579136896,
      "name": "arch_stack_walk_reliable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void * cookie, struct task_struct * task)
```

```json
{
  "name": "arch_stack_walk_reliable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579143296,
      "name": "arch_stack_walk_reliable",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:32",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579143296,
      "name": "arch_stack_walk_reliable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void * cookie, struct task_struct * task)
```

```json
{
  "name": "arch_stack_walk_reliable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_stack_walk_reliable",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:32",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592061055,
      "name": "arch_stack_walk_reliable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071579170384,
      "name": "arch_stack_walk_reliable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void * cookie, struct task_struct * task)
```

```json
{
  "name": "arch_stack_walk_reliable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_stack_walk_reliable",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:32",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593827583,
      "name": "arch_stack_walk_reliable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071579216192,
      "name": "arch_stack_walk_reliable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void * cookie, struct task_struct * task)
```

```json
{
  "name": "arch_stack_walk_reliable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_stack_walk_reliable",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:32",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595960110,
      "name": "arch_stack_walk_reliable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071579272960,
      "name": "arch_stack_walk_reliable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void * cookie, struct task_struct * task)
```

```json
{
  "name": "arch_stack_walk_reliable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_stack_walk_reliable",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:32",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596477435,
      "name": "arch_stack_walk_reliable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071579279392,
      "name": "arch_stack_walk_reliable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void * cookie, struct task_struct * task)
```

```json
{
  "name": "arch_stack_walk_reliable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_stack_walk_reliable",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:32",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597373220,
      "name": "arch_stack_walk_reliable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071579309296,
      "name": "arch_stack_walk_reliable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void * cookie, struct task_struct * task)
```

```json
{
  "name": "arch_stack_walk_reliable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579124528,
      "name": "arch_stack_walk_reliable",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:38",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579124528,
      "name": "arch_stack_walk_reliable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void * cookie, struct task_struct * task)
```

```json
{
  "name": "arch_stack_walk_reliable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579056464,
      "name": "arch_stack_walk_reliable",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:38",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579056464,
      "name": "arch_stack_walk_reliable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void * cookie, struct task_struct * task)
```

```json
{
  "name": "arch_stack_walk_reliable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579124080,
      "name": "arch_stack_walk_reliable",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:38",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579124080,
      "name": "arch_stack_walk_reliable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void * cookie, struct task_struct * task)
```

```json
{
  "name": "arch_stack_walk_reliable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579129200,
      "name": "arch_stack_walk_reliable",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:38",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_tsk_reliable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579129200,
      "name": "arch_stack_walk_reliable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void * cookie, struct task_struct * task)
```
</details>
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
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void * cookie, struct task_struct * task)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void * cookie, struct task_struct * task)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void * cookie, struct task_struct * task)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void * cookie, struct task_struct * task)
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
