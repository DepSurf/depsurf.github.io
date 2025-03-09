# Function: <code>check_stack_read_fixed_off</code>

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
int check_stack_read_fixed_off(struct bpf_verifier_env * env, struct bpf_func_state * reg_state, int off, int size, int dst_regno)
```

```json
{
  "name": "check_stack_read_fixed_off",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581016320,
      "name": "check_stack_read_fixed_off",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2853",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581016320,
      "name": "check_stack_read_fixed_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 695
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int check_stack_read_fixed_off(struct bpf_verifier_env * env, struct bpf_func_state * reg_state, int off, int size, int dst_regno)
```

```json
{
  "name": "check_stack_read_fixed_off",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_stack_read_fixed_off",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2919",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581234848,
      "name": "check_stack_read_fixed_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1010
    },
    {
      "addr": 18446744071592184522,
      "name": "check_stack_read_fixed_off.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int check_stack_read_fixed_off(struct bpf_verifier_env * env, struct bpf_func_state * reg_state, int off, int size, int dst_regno)
```

```json
{
  "name": "check_stack_read_fixed_off",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_stack_read_fixed_off",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3263",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581521824,
      "name": "check_stack_read_fixed_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1365
    },
    {
      "addr": 18446744071593958722,
      "name": "check_stack_read_fixed_off.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int check_stack_read_fixed_off(struct bpf_verifier_env * env, struct bpf_func_state * reg_state, int off, int size, int dst_regno)
```

```json
{
  "name": "check_stack_read_fixed_off",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_stack_read_fixed_off",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3705",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581879232,
      "name": "check_stack_read_fixed_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1367
    },
    {
      "addr": 18446744071596018483,
      "name": "check_stack_read_fixed_off.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int check_stack_read_fixed_off(struct bpf_verifier_env * env, struct bpf_func_state * reg_state, int off, int size, int dst_regno)
```

```json
{
  "name": "check_stack_read_fixed_off",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_stack_read_fixed_off",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4588",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582024896,
      "name": "check_stack_read_fixed_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1470
    },
    {
      "addr": 18446744071596537529,
      "name": "check_stack_read_fixed_off.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int check_stack_read_fixed_off(struct bpf_verifier_env * env, struct bpf_func_state * reg_state, int off, int size, int dst_regno)
```

```json
{
  "name": "check_stack_read_fixed_off",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_stack_read_fixed_off",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4725",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582169648,
      "name": "check_stack_read_fixed_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2033
    },
    {
      "addr": 18446744071597441072,
      "name": "check_stack_read_fixed_off.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
int check_stack_read_fixed_off(struct bpf_verifier_env * env, struct bpf_func_state * reg_state, int off, int size, int dst_regno)
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
