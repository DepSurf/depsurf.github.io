# Function: <code>btf_check_func_arg_match</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int btf_check_func_arg_match(struct bpf_verifier_env * env, int subprog, struct bpf_reg_state * reg)
```

```json
{
  "name": "btf_check_func_arg_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581095504,
      "name": "btf_check_func_arg_match",
      "external": true,
      "loc": "kernel/bpf/btf.c:4374",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:check_func_call",
        "kernel/bpf/verifier.c:check_func_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581095504,
      "name": "btf_check_func_arg_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 817
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int btf_check_func_arg_match(struct bpf_verifier_env * env, int subprog, struct bpf_reg_state * reg)
```

```json
{
  "name": "btf_check_func_arg_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581122208,
      "name": "btf_check_func_arg_match",
      "external": true,
      "loc": "kernel/bpf/btf.c:5298",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:check_func_call",
        "kernel/bpf/verifier.c:check_func_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581122208,
      "name": "btf_check_func_arg_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1000
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int btf_check_func_arg_match(struct bpf_verifier_env * env, const struct btf * btf, u32 func_id, struct bpf_reg_state * regs, bool ptr_to_mem_ok)
```

```json
{
  "name": "btf_check_func_arg_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581140640,
      "name": "btf_check_func_arg_match",
      "external": false,
      "loc": "kernel/bpf/btf.c:5384",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_kfunc_arg_match",
        "kernel/bpf/btf.c:btf_check_subprog_arg_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581140640,
      "name": "btf_check_func_arg_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1522
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
int btf_check_func_arg_match(struct bpf_verifier_env * env, const struct btf * btf, u32 func_id, struct bpf_reg_state * regs, bool ptr_to_mem_ok)
```

```json
{
  "name": "btf_check_func_arg_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "btf_check_func_arg_match",
      "external": false,
      "loc": "kernel/bpf/btf.c:5437",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_kfunc_arg_match",
        "kernel/bpf/btf.c:btf_check_subprog_arg_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581373472,
      "name": "btf_check_func_arg_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1865
    },
    {
      "addr": 18446744071592187126,
      "name": "btf_check_func_arg_match.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int btf_check_func_arg_match(struct bpf_verifier_env * env, const struct btf * btf, u32 func_id, struct bpf_reg_state * regs, bool ptr_to_mem_ok)
```

```json
{
  "name": "btf_check_func_arg_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "btf_check_func_arg_match",
      "external": false,
      "loc": "kernel/bpf/btf.c:6057",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_kfunc_arg_match",
        "kernel/bpf/btf.c:btf_check_subprog_arg_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581696128,
      "name": "btf_check_func_arg_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3251
    },
    {
      "addr": 18446744071593961877,
      "name": "btf_check_func_arg_match.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int btf_check_func_arg_match(struct bpf_verifier_env * env, const struct btf * btf, u32 func_id, struct bpf_reg_state * regs, bool ptr_to_mem_ok, bool processing_call)
```

```json
{
  "name": "btf_check_func_arg_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582082112,
      "name": "btf_check_func_arg_match",
      "external": false,
      "loc": "kernel/bpf/btf.c:6656",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_subprog_call",
        "kernel/bpf/btf.c:btf_check_subprog_arg_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582082112,
      "name": "btf_check_func_arg_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1374
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
int btf_check_func_arg_match(struct bpf_verifier_env * env, const struct btf * btf, u32 func_id, struct bpf_reg_state * regs, bool ptr_to_mem_ok, bool processing_call)
```

```json
{
  "name": "btf_check_func_arg_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582278416,
      "name": "btf_check_func_arg_match",
      "external": false,
      "loc": "kernel/bpf/btf.c:6758",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_subprog_call",
        "kernel/bpf/btf.c:btf_check_subprog_arg_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582278416,
      "name": "btf_check_func_arg_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1402
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_check_func_arg_match",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582209520,
      "name": "btf_check_func_arg_match",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9254",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:btf_check_subprog_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582209520,
      "name": "btf_check_func_arg_match.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
int btf_check_func_arg_match(struct bpf_verifier_env * env, int subprog, struct bpf_reg_state * reg)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct btf * btf</code>
</li>
<li>
<b>Param added. </b>
<code>u32 func_id</code>
</li>
<li>
<b>Param added. </b>
<code>struct bpf_reg_state * regs</code>
</li>
<li>
<b>Param added. </b>
<code>bool ptr_to_mem_ok</code>
</li>
<li>
<b>Param removed. </b>
<code>int subprog</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_reg_state * reg</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool processing_call</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int btf_check_func_arg_match(struct bpf_verifier_env * env, const struct btf * btf, u32 func_id, struct bpf_reg_state * regs, bool ptr_to_mem_ok, bool processing_call)
```
</details>
</li>
</ul>
