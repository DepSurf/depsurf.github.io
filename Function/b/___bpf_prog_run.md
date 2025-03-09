# Function: <code>___bpf_prog_run</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
unsigned int ___bpf_prog_run(u64 * regs, const struct bpf_insn * insn, u64 * stack)
```

```json
{
  "name": "___bpf_prog_run",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580482880,
      "name": "___bpf_prog_run",
      "external": false,
      "loc": "kernel/bpf/core.c:766",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:__bpf_prog_run512",
        "kernel/bpf/core.c:__bpf_prog_run480",
        "kernel/bpf/core.c:__bpf_prog_run448",
        "kernel/bpf/core.c:__bpf_prog_run416",
        "kernel/bpf/core.c:__bpf_prog_run384",
        "kernel/bpf/core.c:__bpf_prog_run352",
        "kernel/bpf/core.c:__bpf_prog_run320",
        "kernel/bpf/core.c:__bpf_prog_run288",
        "kernel/bpf/core.c:__bpf_prog_run256",
        "kernel/bpf/core.c:__bpf_prog_run224",
        "kernel/bpf/core.c:__bpf_prog_run192",
        "kernel/bpf/core.c:__bpf_prog_run160",
        "kernel/bpf/core.c:__bpf_prog_run128",
        "kernel/bpf/core.c:__bpf_prog_run96",
        "kernel/bpf/core.c:__bpf_prog_run64",
        "kernel/bpf/core.c:__bpf_prog_run32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580482880,
      "name": "___bpf_prog_run",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4565
    }
  ]
}
```
</details>
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
unsigned int ___bpf_prog_run(u64 * regs, const struct bpf_insn * insn, u64 * stack)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
unsigned int ___bpf_prog_run(u64 * regs, const struct bpf_insn * insn, u64 * stack)
```
</details>
</li>
</ul>
