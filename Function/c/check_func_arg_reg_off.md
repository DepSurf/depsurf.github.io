# Function: <code>check_func_arg_reg_off</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int check_func_arg_reg_off(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int regno, enum bpf_arg_type arg_type)
```

```json
{
  "name": "check_func_arg_reg_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581533872,
      "name": "check_func_arg_reg_off",
      "external": true,
      "loc": "kernel/bpf/verifier.c:5778",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/btf.c:btf_check_func_arg_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581533872,
      "name": "check_func_arg_reg_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int check_func_arg_reg_off(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int regno, enum bpf_arg_type arg_type)
```

```json
{
  "name": "check_func_arg_reg_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581899120,
      "name": "check_func_arg_reg_off",
      "external": true,
      "loc": "kernel/bpf/verifier.c:6482",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/btf.c:btf_check_func_arg_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581899120,
      "name": "check_func_arg_reg_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int check_func_arg_reg_off(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int regno, enum bpf_arg_type arg_type)
```

```json
{
  "name": "check_func_arg_reg_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582078496,
      "name": "check_func_arg_reg_off",
      "external": true,
      "loc": "kernel/bpf/verifier.c:7788",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/btf.c:btf_check_func_arg_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582078496,
      "name": "check_func_arg_reg_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int check_func_arg_reg_off(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int regno, enum bpf_arg_type arg_type)
```

```json
{
  "name": "check_func_arg_reg_off",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582084944,
      "name": "check_func_arg_reg_off",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8291",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:check_func_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582084944,
      "name": "check_func_arg_reg_off",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int check_func_arg_reg_off(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int regno, enum bpf_arg_type arg_type)
```
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
