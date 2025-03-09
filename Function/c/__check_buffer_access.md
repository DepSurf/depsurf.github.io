# Function: <code>__check_buffer_access</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__check_buffer_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581014030,
      "name": "__check_buffer_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3166",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__check_buffer_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581021731,
      "name": "__check_buffer_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3709",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__check_buffer_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581241337,
      "name": "__check_buffer_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3795",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __check_buffer_access(struct bpf_verifier_env * env, const char * buf_info, const struct bpf_reg_state * reg, int regno, int off, int size)
```

```json
{
  "name": "__check_buffer_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581526000,
      "name": "__check_buffer_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4322",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581457216,
      "name": "__check_buffer_access",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __check_buffer_access(struct bpf_verifier_env * env, const char * buf_info, const struct bpf_reg_state * reg, int regno, int off, int size)
```

```json
{
  "name": "__check_buffer_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581888512,
      "name": "__check_buffer_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4777",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581819424,
      "name": "__check_buffer_access",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __check_buffer_access(struct bpf_verifier_env * env, const char * buf_info, const struct bpf_reg_state * reg, int regno, int off, int size)
```

```json
{
  "name": "__check_buffer_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582065427,
      "name": "__check_buffer_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5721",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581953232,
      "name": "__check_buffer_access",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __check_buffer_access(struct bpf_verifier_env * env, const char * buf_info, const struct bpf_reg_state * reg, int regno, int off, int size)
```

```json
{
  "name": "__check_buffer_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582196269,
      "name": "__check_buffer_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5952",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582085264,
      "name": "__check_buffer_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
int __check_buffer_access(struct bpf_verifier_env * env, const char * buf_info, const struct bpf_reg_state * reg, int regno, int off, int size)
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
