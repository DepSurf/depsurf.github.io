# Function: <code>realloc_reference_state</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int realloc_reference_state(struct bpf_func_state * state, int size, bool copy_old)
```

```json
{
  "name": "realloc_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580707216,
      "name": "realloc_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:571",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:copy_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580707216,
      "name": "realloc_reference_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int realloc_reference_state(struct bpf_func_state * state, int size, bool copy_old)
```

```json
{
  "name": "realloc_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580781440,
      "name": "realloc_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:594",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:copy_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580781440,
      "name": "realloc_reference_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int realloc_reference_state(struct bpf_func_state * state, int size, bool copy_old)
```

```json
{
  "name": "realloc_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580832368,
      "name": "realloc_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:594",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:copy_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580832368,
      "name": "realloc_reference_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int realloc_reference_state(struct bpf_func_state * state, int size, bool copy_old)
```

```json
{
  "name": "realloc_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580960928,
      "name": "realloc_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:721",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:prepare_func_exit",
        "kernel/bpf/verifier.c:check_func_call",
        "kernel/bpf/verifier.c:check_stack_write",
        "kernel/bpf/verifier.c:copy_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580960928,
      "name": "realloc_reference_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
int realloc_reference_state(struct bpf_func_state * state, int size, bool copy_old)
```

```json
{
  "name": "realloc_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580960864,
      "name": "realloc_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:747",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:prepare_func_exit",
        "kernel/bpf/verifier.c:check_func_call",
        "kernel/bpf/verifier.c:check_stack_write",
        "kernel/bpf/verifier.c:copy_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580960864,
      "name": "realloc_reference_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int realloc_reference_state(struct bpf_func_state * state, int size, bool copy_old)
```

```json
{
  "name": "realloc_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580960624,
      "name": "realloc_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:796",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:prepare_func_exit",
        "kernel/bpf/verifier.c:check_stack_write_var_off",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off",
        "kernel/bpf/verifier.c:copy_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580960624,
      "name": "realloc_reference_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "realloc_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492156168,
      "name": "realloc_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:594",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_stack_write",
        "kernel/bpf/verifier.c:copy_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492156168,
      "name": "realloc_reference_state.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int realloc_reference_state(struct bpf_func_state * state, int size, bool copy_old)
```

```json
{
  "name": "realloc_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226053016,
      "name": "realloc_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:594",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_stack_write",
        "kernel/bpf/verifier.c:copy_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226053016,
      "name": "realloc_reference_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "realloc_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285366960,
      "name": "realloc_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:594",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_stack_write",
        "kernel/bpf/verifier.c:copy_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285366960,
      "name": "realloc_reference_state.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "realloc_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272316226,
      "name": "realloc_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:594",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_stack_write",
        "kernel/bpf/verifier.c:copy_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272316226,
      "name": "realloc_reference_state.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int realloc_reference_state(struct bpf_func_state * state, int size, bool copy_old)
```

```json
{
  "name": "realloc_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580801168,
      "name": "realloc_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:594",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:copy_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580801168,
      "name": "realloc_reference_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int realloc_reference_state(struct bpf_func_state * state, int size, bool copy_old)
```

```json
{
  "name": "realloc_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580747344,
      "name": "realloc_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:594",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:copy_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580747344,
      "name": "realloc_reference_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int realloc_reference_state(struct bpf_func_state * state, int size, bool copy_old)
```

```json
{
  "name": "realloc_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580792416,
      "name": "realloc_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:594",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:copy_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580792416,
      "name": "realloc_reference_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int realloc_reference_state(struct bpf_func_state * state, int size, bool copy_old)
```

```json
{
  "name": "realloc_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580850800,
      "name": "realloc_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:594",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:copy_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580850800,
      "name": "realloc_reference_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int realloc_reference_state(struct bpf_func_state * state, int size, bool copy_old)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int realloc_reference_state(struct bpf_func_state * state, int size, bool copy_old)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int realloc_reference_state(struct bpf_func_state * state, int size, bool copy_old)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int realloc_reference_state(struct bpf_func_state * state, int size, bool copy_old)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int realloc_reference_state(struct bpf_func_state * state, int size, bool copy_old)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
