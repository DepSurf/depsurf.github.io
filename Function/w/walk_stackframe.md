# Function: <code>walk_stackframe</code>

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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void walk_stackframe(struct task_struct * tsk, struct stackframe * frame, int (*)(struct stackframe *, void *) fn, void * data)
```

```json
{
  "name": "walk_stackframe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490236600,
      "name": "walk_stackframe",
      "external": true,
      "loc": "arch/arm64/kernel/stacktrace.c:117",
      "file": "arch/arm64/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/stacktrace.c:__save_stack_trace",
        "arch/arm64/kernel/stacktrace.c:save_stack_trace_regs",
        "arch/arm64/kernel/return_address.c:return_address",
        "arch/arm64/kernel/perf_callchain.c:perf_callchain_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490236600,
      "name": "walk_stackframe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void walk_stackframe(struct stackframe * frame, int (*)(struct stackframe *, void *) fn, void * data)
```

```json
{
  "name": "walk_stackframe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224431960,
      "name": "walk_stackframe",
      "external": true,
      "loc": "arch/arm/kernel/stacktrace.c:50",
      "file": "arch/arm/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/return_address.c:return_address",
        "arch/arm/kernel/stacktrace.c:save_stack_trace_regs",
        "arch/arm/kernel/stacktrace.c:__save_stack_trace",
        "arch/arm/kernel/perf_callchain.c:perf_callchain_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224431960,
      "name": "walk_stackframe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void walk_stackframe(struct task_struct * task, struct pt_regs * regs, bool (*)(long unsigned int, void *) fn, void * arg)
```

```json
{
  "name": "walk_stackframe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271348112,
      "name": "walk_stackframe",
      "external": true,
      "loc": "arch/riscv/kernel/stacktrace.c:22",
      "file": "arch/riscv/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/stacktrace.c:save_stack_trace",
        "arch/riscv/kernel/stacktrace.c:get_wchan",
        "arch/riscv/kernel/stacktrace.c:show_stack",
        "arch/riscv/kernel/perf_callchain.c:perf_callchain_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271348112,
      "name": "walk_stackframe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void walk_stackframe(struct task_struct * tsk, struct stackframe * frame, int (*)(struct stackframe *, void *) fn, void * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void walk_stackframe(struct stackframe * frame, int (*)(struct stackframe *, void *) fn, void * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void walk_stackframe(struct task_struct * task, struct pt_regs * regs, bool (*)(long unsigned int, void *) fn, void * arg)
```
</details>
</li>
</ul>
