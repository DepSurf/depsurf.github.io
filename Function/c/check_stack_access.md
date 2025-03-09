# Function: <code>check_stack_access</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int check_stack_access(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size)
```

```json
{
  "name": "check_stack_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580712512,
      "name": "check_stack_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1393",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580712512,
      "name": "check_stack_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int check_stack_access(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size)
```

```json
{
  "name": "check_stack_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580792240,
      "name": "check_stack_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2103",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580792240,
      "name": "check_stack_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int check_stack_access(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size)
```

```json
{
  "name": "check_stack_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580843264,
      "name": "check_stack_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2104",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580843264,
      "name": "check_stack_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int check_stack_access(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size)
```

```json
{
  "name": "check_stack_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580997584,
      "name": "check_stack_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2433",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580997584,
      "name": "check_stack_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int check_stack_access(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size)
```

```json
{
  "name": "check_stack_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580999584,
      "name": "check_stack_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2506",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580999584,
      "name": "check_stack_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int check_stack_access(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size)
```

```json
{
  "name": "check_stack_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492169120,
      "name": "check_stack_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2104",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492169120,
      "name": "check_stack_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int check_stack_access(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size)
```

```json
{
  "name": "check_stack_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226064924,
      "name": "check_stack_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2104",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226064924,
      "name": "check_stack_access",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int check_stack_access(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size)
```

```json
{
  "name": "check_stack_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285381136,
      "name": "check_stack_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2104",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285381136,
      "name": "check_stack_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int check_stack_access(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size)
```

```json
{
  "name": "check_stack_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272325870,
      "name": "check_stack_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2104",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272325870,
      "name": "check_stack_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int check_stack_access(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size)
```

```json
{
  "name": "check_stack_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580812064,
      "name": "check_stack_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2104",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580812064,
      "name": "check_stack_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int check_stack_access(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size)
```

```json
{
  "name": "check_stack_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580758240,
      "name": "check_stack_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2104",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580758240,
      "name": "check_stack_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int check_stack_access(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size)
```

```json
{
  "name": "check_stack_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580803312,
      "name": "check_stack_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2104",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580803312,
      "name": "check_stack_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int check_stack_access(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size)
```

```json
{
  "name": "check_stack_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580861696,
      "name": "check_stack_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2104",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580861696,
      "name": "check_stack_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int check_stack_access(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size)
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int check_stack_access(struct bpf_verifier_env * env, const struct bpf_reg_state * reg, int off, int size)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
