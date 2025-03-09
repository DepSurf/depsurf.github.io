# Function: <code>sanitize_check_bounds</code>

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
int sanitize_check_bounds(struct bpf_verifier_env * env, const struct bpf_insn * insn, const struct bpf_reg_state * dst_reg)
```

```json
{
  "name": "sanitize_check_bounds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580979792,
      "name": "sanitize_check_bounds",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6671",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580979792,
      "name": "sanitize_check_bounds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
int sanitize_check_bounds(struct bpf_verifier_env * env, const struct bpf_insn * insn, const struct bpf_reg_state * dst_reg)
```

```json
{
  "name": "sanitize_check_bounds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sanitize_check_bounds",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6960",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581191904,
      "name": "sanitize_check_bounds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    },
    {
      "addr": 18446744071592182186,
      "name": "sanitize_check_bounds.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int sanitize_check_bounds(struct bpf_verifier_env * env, const struct bpf_insn * insn, const struct bpf_reg_state * dst_reg)
```

```json
{
  "name": "sanitize_check_bounds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sanitize_check_bounds",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7959",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581475408,
      "name": "sanitize_check_bounds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
    },
    {
      "addr": 18446744071593956297,
      "name": "sanitize_check_bounds.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int sanitize_check_bounds(struct bpf_verifier_env * env, const struct bpf_insn * insn, const struct bpf_reg_state * dst_reg)
```

```json
{
  "name": "sanitize_check_bounds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sanitize_check_bounds",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9895",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581834560,
      "name": "sanitize_check_bounds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
    },
    {
      "addr": 18446744071596016073,
      "name": "sanitize_check_bounds.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int sanitize_check_bounds(struct bpf_verifier_env * env, const struct bpf_insn * insn, const struct bpf_reg_state * dst_reg)
```

```json
{
  "name": "sanitize_check_bounds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sanitize_check_bounds",
      "external": false,
      "loc": "kernel/bpf/verifier.c:11811",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582029968,
      "name": "sanitize_check_bounds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    },
    {
      "addr": 18446744071596537803,
      "name": "sanitize_check_bounds.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int sanitize_check_bounds(struct bpf_verifier_env * env, const struct bpf_insn * insn, const struct bpf_reg_state * dst_reg)
```

```json
{
  "name": "sanitize_check_bounds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sanitize_check_bounds",
      "external": false,
      "loc": "kernel/bpf/verifier.c:12745",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582178304,
      "name": "sanitize_check_bounds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    },
    {
      "addr": 18446744071597441600,
      "name": "sanitize_check_bounds.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int sanitize_check_bounds(struct bpf_verifier_env * env, const struct bpf_insn * insn, const struct bpf_reg_state * dst_reg)
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
