# Function: <code>arch_stack_walk_user</code>

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
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void * cookie, const struct pt_regs * regs)
```

```json
{
  "name": "arch_stack_walk_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579122496,
      "name": "arch_stack_walk_user",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:115",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579122496,
      "name": "arch_stack_walk_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void * cookie, const struct pt_regs * regs)
```

```json
{
  "name": "arch_stack_walk_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579124368,
      "name": "arch_stack_walk_user",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:115",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579124368,
      "name": "arch_stack_walk_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void * cookie, const struct pt_regs * regs)
```

```json
{
  "name": "arch_stack_walk_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579140000,
      "name": "arch_stack_walk_user",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:112",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579140000,
      "name": "arch_stack_walk_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void * cookie, const struct pt_regs * regs)
```

```json
{
  "name": "arch_stack_walk_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579137104,
      "name": "arch_stack_walk_user",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:112",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579137104,
      "name": "arch_stack_walk_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void * cookie, const struct pt_regs * regs)
```

```json
{
  "name": "arch_stack_walk_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579143504,
      "name": "arch_stack_walk_user",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:106",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579143504,
      "name": "arch_stack_walk_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void * cookie, const struct pt_regs * regs)
```

```json
{
  "name": "arch_stack_walk_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579170624,
      "name": "arch_stack_walk_user",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:106",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579170624,
      "name": "arch_stack_walk_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void * cookie, const struct pt_regs * regs)
```

```json
{
  "name": "arch_stack_walk_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579216480,
      "name": "arch_stack_walk_user",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:106",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579216480,
      "name": "arch_stack_walk_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void * cookie, const struct pt_regs * regs)
```

```json
{
  "name": "arch_stack_walk_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579273264,
      "name": "arch_stack_walk_user",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:106",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579273264,
      "name": "arch_stack_walk_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void * cookie, const struct pt_regs * regs)
```

```json
{
  "name": "arch_stack_walk_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579279696,
      "name": "arch_stack_walk_user",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:106",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579279696,
      "name": "arch_stack_walk_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void * cookie, const struct pt_regs * regs)
```

```json
{
  "name": "arch_stack_walk_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579309600,
      "name": "arch_stack_walk_user",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:106",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579309600,
      "name": "arch_stack_walk_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void * cookie, const struct pt_regs * regs)
```

```json
{
  "name": "arch_stack_walk_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579124752,
      "name": "arch_stack_walk_user",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:115",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579124752,
      "name": "arch_stack_walk_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void * cookie, const struct pt_regs * regs)
```

```json
{
  "name": "arch_stack_walk_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579056688,
      "name": "arch_stack_walk_user",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:115",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579056688,
      "name": "arch_stack_walk_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void * cookie, const struct pt_regs * regs)
```

```json
{
  "name": "arch_stack_walk_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579124304,
      "name": "arch_stack_walk_user",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:115",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579124304,
      "name": "arch_stack_walk_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void * cookie, const struct pt_regs * regs)
```

```json
{
  "name": "arch_stack_walk_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579129424,
      "name": "arch_stack_walk_user",
      "external": true,
      "loc": "arch/x86/kernel/stacktrace.c:115",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stacktrace.c:stack_trace_save_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579129424,
      "name": "arch_stack_walk_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void * cookie, const struct pt_regs * regs)
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
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void * cookie, const struct pt_regs * regs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void * cookie, const struct pt_regs * regs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void * cookie, const struct pt_regs * regs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void arch_stack_walk_user(stack_trace_consume_fn consume_entry, void * cookie, const struct pt_regs * regs)
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
