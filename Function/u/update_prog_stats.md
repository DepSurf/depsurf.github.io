# Function: <code>update_prog_stats</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void update_prog_stats(struct bpf_prog * prog, u64 start)
```

```json
{
  "name": "update_prog_stats",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581101488,
      "name": "update_prog_stats",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:570",
      "file": "kernel/bpf/trampoline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable",
        "kernel/bpf/trampoline.c:__bpf_prog_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581101488,
      "name": "update_prog_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void update_prog_stats(struct bpf_prog * prog, u64 start)
```

```json
{
  "name": "update_prog_stats",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581331120,
      "name": "update_prog_stats",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:577",
      "file": "kernel/bpf/trampoline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable",
        "kernel/bpf/trampoline.c:__bpf_prog_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581331120,
      "name": "update_prog_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void update_prog_stats(struct bpf_prog * prog, u64 start)
```

```json
{
  "name": "update_prog_stats",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581635680,
      "name": "update_prog_stats",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:595",
      "file": "kernel/bpf/trampoline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable",
        "kernel/bpf/trampoline.c:__bpf_prog_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581635680,
      "name": "update_prog_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void update_prog_stats(struct bpf_prog * prog, u64 start)
```

```json
{
  "name": "update_prog_stats",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582024288,
      "name": "update_prog_stats",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:885",
      "file": "kernel/bpf/trampoline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:__bpf_prog_exit",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_recur"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582024288,
      "name": "update_prog_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_prog_stats",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582217627,
      "name": "update_prog_stats",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:863",
      "file": "kernel/bpf/trampoline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:__bpf_prog_exit",
        "kernel/bpf/trampoline.c:__bpf_prog_exit",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_recur",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_recur"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_prog_stats",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582372827,
      "name": "update_prog_stats",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:874",
      "file": "kernel/bpf/trampoline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:__bpf_prog_exit",
        "kernel/bpf/trampoline.c:__bpf_prog_exit",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_recur",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_recur"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void update_prog_stats(struct bpf_prog * prog, u64 start)
```
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void update_prog_stats(struct bpf_prog * prog, u64 start)
```
</details>
</li>
</ul>
