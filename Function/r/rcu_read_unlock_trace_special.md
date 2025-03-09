# Function: <code>rcu_read_unlock_trace_special</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_read_unlock_trace_special(struct task_struct * t, int nesting)
```

```json
{
  "name": "rcu_read_unlock_trace_special",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580090704,
      "name": "rcu_read_unlock_trace_special",
      "external": true,
      "loc": "kernel/rcu/tasks.h:757",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:exit_tasks_rcu_finish"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580090704,
      "name": "rcu_read_unlock_trace_special",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void rcu_read_unlock_trace_special(struct task_struct * t, int nesting)
```

```json
{
  "name": "rcu_read_unlock_trace_special",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580073872,
      "name": "rcu_read_unlock_trace_special",
      "external": true,
      "loc": "kernel/rcu/tasks.h:767",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580073872,
      "name": "rcu_read_unlock_trace_special",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void rcu_read_unlock_trace_special(struct task_struct * t, int nesting)
```

```json
{
  "name": "rcu_read_unlock_trace_special",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580075200,
      "name": "rcu_read_unlock_trace_special",
      "external": true,
      "loc": "kernel/rcu/tasks.h:803",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580075200,
      "name": "rcu_read_unlock_trace_special",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void rcu_read_unlock_trace_special(struct task_struct * t, int nesting)
```

```json
{
  "name": "rcu_read_unlock_trace_special",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580209600,
      "name": "rcu_read_unlock_trace_special",
      "external": true,
      "loc": "kernel/rcu/tasks.h:850",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580209600,
      "name": "rcu_read_unlock_trace_special",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_read_unlock_trace_special(struct task_struct * t)
```

```json
{
  "name": "rcu_read_unlock_trace_special",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580368208,
      "name": "rcu_read_unlock_trace_special",
      "external": true,
      "loc": "kernel/rcu/tasks.h:1195",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580368208,
      "name": "rcu_read_unlock_trace_special",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void rcu_read_unlock_trace_special(struct task_struct * t)
```

```json
{
  "name": "rcu_read_unlock_trace_special",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_read_unlock_trace_special",
      "external": true,
      "loc": "kernel/rcu/tasks.h:1273",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595990671,
      "name": "rcu_read_unlock_trace_special.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071580597920,
      "name": "rcu_read_unlock_trace_special",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
void rcu_read_unlock_trace_special(struct task_struct * t)
```

```json
{
  "name": "rcu_read_unlock_trace_special",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_read_unlock_trace_special",
      "external": true,
      "loc": "kernel/rcu/tasks.h:1310",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596508806,
      "name": "rcu_read_unlock_trace_special.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071580671424,
      "name": "rcu_read_unlock_trace_special",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
void rcu_read_unlock_trace_special(struct task_struct * t)
```

```json
{
  "name": "rcu_read_unlock_trace_special",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_read_unlock_trace_special",
      "external": true,
      "loc": "kernel/rcu/tasks.h:1426",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "kernel/trace/bpf_trace.c:uprobe_prog_run",
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597406544,
      "name": "rcu_read_unlock_trace_special.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071580738272,
      "name": "rcu_read_unlock_trace_special",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void rcu_read_unlock_trace_special(struct task_struct * t, int nesting)
```
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int nesting</code>
</li>
</ul>
</details>
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
