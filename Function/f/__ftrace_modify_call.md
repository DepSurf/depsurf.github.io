# Function: <code>__ftrace_modify_call</code>

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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__ftrace_modify_call",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282637536,
      "name": "__ftrace_modify_call",
      "external": false,
      "loc": "arch/powerpc/kernel/trace/ftrace.c:700",
      "file": "arch/powerpc/kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/trace/ftrace.c:ftrace_modify_call"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int __ftrace_modify_call(long unsigned int hook_pos, long unsigned int target, bool enable)
```

```json
{
  "name": "__ftrace_modify_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271355660,
      "name": "__ftrace_modify_call",
      "external": false,
      "loc": "arch/riscv/kernel/ftrace.c:44",
      "file": "arch/riscv/kernel/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/ftrace.c:ftrace_disable_ftrace_graph_caller",
        "arch/riscv/kernel/ftrace.c:ftrace_enable_ftrace_graph_caller",
        "arch/riscv/kernel/ftrace.c:ftrace_modify_call",
        "arch/riscv/kernel/ftrace.c:ftrace_update_ftrace_func",
        "arch/riscv/kernel/ftrace.c:ftrace_update_ftrace_func",
        "arch/riscv/kernel/ftrace.c:ftrace_make_nop",
        "arch/riscv/kernel/ftrace.c:ftrace_make_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271355660,
      "name": "__ftrace_modify_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int __ftrace_modify_call(long unsigned int hook_pos, long unsigned int target, bool enable)
```
</details>
</li>
</ul>
