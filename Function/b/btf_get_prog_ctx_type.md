# Function: <code>btf_get_prog_ctx_type</code>

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
const struct btf_member * btf_get_prog_ctx_type(struct bpf_verifier_log * log, struct btf * btf, const struct btf_type * t, enum bpf_prog_type prog_type, int arg)
```

```json
{
  "name": "btf_get_prog_ctx_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581071616,
      "name": "btf_get_prog_ctx_type",
      "external": false,
      "loc": "kernel/bpf/btf.c:3515",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_ctx_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581071616,
      "name": "btf_get_prog_ctx_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
const struct btf_member * btf_get_prog_ctx_type(struct bpf_verifier_log * log, struct btf * btf, const struct btf_type * t, enum bpf_prog_type prog_type, int arg)
```

```json
{
  "name": "btf_get_prog_ctx_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581101216,
      "name": "btf_get_prog_ctx_type",
      "external": false,
      "loc": "kernel/bpf/btf.c:4306",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_ctx_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581101216,
      "name": "btf_get_prog_ctx_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
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
const struct btf_member * btf_get_prog_ctx_type(struct bpf_verifier_log * log, const struct btf * btf, const struct btf_type * t, enum bpf_prog_type prog_type, int arg)
```

```json
{
  "name": "btf_get_prog_ctx_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581120400,
      "name": "btf_get_prog_ctx_type",
      "external": false,
      "loc": "kernel/bpf/btf.c:4379",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_ctx_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581120400,
      "name": "btf_get_prog_ctx_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
const struct btf_member * btf_get_prog_ctx_type(struct bpf_verifier_log * log, const struct btf * btf, const struct btf_type * t, enum bpf_prog_type prog_type, int arg)
```

```json
{
  "name": "btf_get_prog_ctx_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581351888,
      "name": "btf_get_prog_ctx_type",
      "external": false,
      "loc": "kernel/bpf/btf.c:4427",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_ctx_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581351888,
      "name": "btf_get_prog_ctx_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
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
const struct btf_member * btf_get_prog_ctx_type(struct bpf_verifier_log * log, const struct btf * btf, const struct btf_type * t, enum bpf_prog_type prog_type, int arg)
```

```json
{
  "name": "btf_get_prog_ctx_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581657968,
      "name": "btf_get_prog_ctx_type",
      "external": false,
      "loc": "kernel/bpf/btf.c:4978",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_ctx_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581657968,
      "name": "btf_get_prog_ctx_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 601
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
const struct btf_member * btf_get_prog_ctx_type(struct bpf_verifier_log * log, const struct btf * btf, const struct btf_type * t, enum bpf_prog_type prog_type, int arg)
```

```json
{
  "name": "btf_get_prog_ctx_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582081280,
      "name": "btf_get_prog_ctx_type",
      "external": true,
      "loc": "kernel/bpf/btf.c:5537",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:get_kfunc_ptr_arg_type",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_ctx_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582081280,
      "name": "btf_get_prog_ctx_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 814
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
const struct btf_member * btf_get_prog_ctx_type(struct bpf_verifier_log * log, const struct btf * btf, const struct btf_type * t, enum bpf_prog_type prog_type, int arg)
```

```json
{
  "name": "btf_get_prog_ctx_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582277488,
      "name": "btf_get_prog_ctx_type",
      "external": true,
      "loc": "kernel/bpf/btf.c:5611",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:get_kfunc_ptr_arg_type",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_ctx_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582277488,
      "name": "btf_get_prog_ctx_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 897
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
const struct btf_type * btf_get_prog_ctx_type(struct bpf_verifier_log * log, const struct btf * btf, const struct btf_type * t, enum bpf_prog_type prog_type, int arg)
```

```json
{
  "name": "btf_get_prog_ctx_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582435504,
      "name": "btf_get_prog_ctx_type",
      "external": true,
      "loc": "kernel/bpf/btf.c:5651",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:get_kfunc_ptr_arg_type",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_ctx_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582435504,
      "name": "btf_get_prog_ctx_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 886
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
const struct btf_member * btf_get_prog_ctx_type(struct bpf_verifier_log * log, struct btf * btf, const struct btf_type * t, enum bpf_prog_type prog_type, int arg)
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
<b>Param type changed. </b>
<code>struct btf * btf</code> ➡️ <code>const struct btf * btf</code>
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>const struct btf_member *</code> ➡️ <code>const struct btf_type *</code>
</li>
</ul>
</details>
</li>
</ul>
