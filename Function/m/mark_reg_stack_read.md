# Function: <code>mark_reg_stack_read</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void mark_reg_stack_read(struct bpf_verifier_env * env, struct bpf_func_state * ptr_state, int min_off, int max_off, int dst_regno)
```

```json
{
  "name": "mark_reg_stack_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580977008,
      "name": "mark_reg_stack_read",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2802",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_read",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580977008,
      "name": "mark_reg_stack_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
void mark_reg_stack_read(struct bpf_verifier_env * env, struct bpf_func_state * ptr_state, int min_off, int max_off, int dst_regno)
```

```json
{
  "name": "mark_reg_stack_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581188464,
      "name": "mark_reg_stack_read",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2868",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_read",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581188464,
      "name": "mark_reg_stack_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
void mark_reg_stack_read(struct bpf_verifier_env * env, struct bpf_func_state * ptr_state, int min_off, int max_off, int dst_regno)
```

```json
{
  "name": "mark_reg_stack_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581474000,
      "name": "mark_reg_stack_read",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3212",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_read",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581474000,
      "name": "mark_reg_stack_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
void mark_reg_stack_read(struct bpf_verifier_env * env, struct bpf_func_state * ptr_state, int min_off, int max_off, int dst_regno)
```

```json
{
  "name": "mark_reg_stack_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581824800,
      "name": "mark_reg_stack_read",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3654",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_read",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581824800,
      "name": "mark_reg_stack_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
void mark_reg_stack_read(struct bpf_verifier_env * env, struct bpf_func_state * ptr_state, int min_off, int max_off, int dst_regno)
```

```json
{
  "name": "mark_reg_stack_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_reg_stack_read",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4536",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582024208,
      "name": "mark_reg_stack_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 671
    },
    {
      "addr": 18446744071596537461,
      "name": "mark_reg_stack_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void mark_reg_stack_read(struct bpf_verifier_env * env, struct bpf_func_state * ptr_state, int min_off, int max_off, int dst_regno)
```

```json
{
  "name": "mark_reg_stack_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mark_reg_stack_read",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4684",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582127216,
      "name": "mark_reg_stack_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
    },
    {
      "addr": 18446744071597437673,
      "name": "mark_reg_stack_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void mark_reg_stack_read(struct bpf_verifier_env * env, struct bpf_func_state * ptr_state, int min_off, int max_off, int dst_regno)
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
