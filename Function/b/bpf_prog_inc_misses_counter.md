# Function: <code>bpf_prog_inc_misses_counter</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void bpf_prog_inc_misses_counter(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc_misses_counter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581776912,
      "name": "bpf_prog_inc_misses_counter",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2100",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable_recur",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_recur"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581776912,
      "name": "bpf_prog_inc_misses_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void bpf_prog_inc_misses_counter(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc_misses_counter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581939072,
      "name": "bpf_prog_inc_misses_counter",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2179",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable_recur",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_recur"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581939072,
      "name": "bpf_prog_inc_misses_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void bpf_prog_inc_misses_counter(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_inc_misses_counter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582065680,
      "name": "bpf_prog_inc_misses_counter",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2219",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:trace_call_bpf",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable_recur",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_recur"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582065680,
      "name": "bpf_prog_inc_misses_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void bpf_prog_inc_misses_counter(struct bpf_prog * prog)
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
