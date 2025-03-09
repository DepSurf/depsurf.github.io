# Function: <code>register_ftrace_function_nolock</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int register_ftrace_function_nolock(struct ftrace_ops * ops)
```

```json
{
  "name": "register_ftrace_function_nolock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581319317,
      "name": "register_ftrace_function_nolock",
      "external": false,
      "loc": "kernel/trace/ftrace.c:8214",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:register_ftrace_direct_multi"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:register_ftrace_function",
        "kernel/trace/ftrace.c:modify_ftrace_direct_multi",
        "kernel/trace/ftrace.c:modify_ftrace_direct_multi_nolock",
        "kernel/trace/ftrace.c:ftrace_modify_direct_caller",
        "kernel/trace/ftrace.c:register_ftrace_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581314976,
      "name": "register_ftrace_function_nolock",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int register_ftrace_function_nolock(struct ftrace_ops * ops)
```

```json
{
  "name": "register_ftrace_function_nolock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581412470,
      "name": "register_ftrace_function_nolock",
      "external": false,
      "loc": "kernel/trace/ftrace.c:8029",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:modify_ftrace_direct",
        "kernel/trace/ftrace.c:modify_ftrace_direct_nolock",
        "kernel/trace/ftrace.c:register_ftrace_direct"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:register_ftrace_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581410368,
      "name": "register_ftrace_function_nolock",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int register_ftrace_function_nolock(struct ftrace_ops * ops)
```

```json
{
  "name": "register_ftrace_function_nolock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581521150,
      "name": "register_ftrace_function_nolock",
      "external": false,
      "loc": "kernel/trace/ftrace.c:8029",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:modify_ftrace_direct",
        "kernel/trace/ftrace.c:modify_ftrace_direct_nolock"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:register_ftrace_function",
        "kernel/trace/ftrace.c:register_ftrace_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581518128,
      "name": "register_ftrace_function_nolock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int register_ftrace_function_nolock(struct ftrace_ops * ops)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
