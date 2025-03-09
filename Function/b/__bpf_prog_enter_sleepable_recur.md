# Function: <code>__bpf_prog_enter_sleepable_recur</code>

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
u64 __bpf_prog_enter_sleepable_recur(struct bpf_prog * prog, struct bpf_tramp_run_ctx * run_ctx)
```

```json
{
  "name": "__bpf_prog_enter_sleepable_recur",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582023408,
      "name": "__bpf_prog_enter_sleepable_recur",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:944",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:kern_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582023408,
      "name": "__bpf_prog_enter_sleepable_recur",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
u64 __bpf_prog_enter_sleepable_recur(struct bpf_prog * prog, struct bpf_tramp_run_ctx * run_ctx)
```

```json
{
  "name": "__bpf_prog_enter_sleepable_recur",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582215616,
      "name": "__bpf_prog_enter_sleepable_recur",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:922",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:kern_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582215616,
      "name": "__bpf_prog_enter_sleepable_recur",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
u64 __bpf_prog_enter_sleepable_recur(struct bpf_prog * prog, struct bpf_tramp_run_ctx * run_ctx)
```

```json
{
  "name": "__bpf_prog_enter_sleepable_recur",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582370880,
      "name": "__bpf_prog_enter_sleepable_recur",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:933",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:kern_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582370880,
      "name": "__bpf_prog_enter_sleepable_recur",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
u64 __bpf_prog_enter_sleepable_recur(struct bpf_prog * prog, struct bpf_tramp_run_ctx * run_ctx)
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
