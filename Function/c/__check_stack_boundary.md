# Function: <code>__check_stack_boundary</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __check_stack_boundary(struct bpf_verifier_env * env, u32 regno, int off, int access_size, bool zero_size_allowed)
```

```json
{
  "name": "__check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580799104,
      "name": "__check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2933",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_helper_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580799104,
      "name": "__check_stack_boundary",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int __check_stack_boundary(struct bpf_verifier_env * env, u32 regno, int off, int access_size, bool zero_size_allowed)
```

```json
{
  "name": "__check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580850208,
      "name": "__check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2934",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_helper_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580850208,
      "name": "__check_stack_boundary",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int __check_stack_boundary(struct bpf_verifier_env * env, u32 regno, int off, int access_size, bool zero_size_allowed)
```

```json
{
  "name": "__check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580979296,
      "name": "__check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3425",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_boundary",
        "kernel/bpf/verifier.c:check_stack_boundary",
        "kernel/bpf/verifier.c:check_stack_boundary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580979296,
      "name": "__check_stack_boundary",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
int __check_stack_boundary(struct bpf_verifier_env * env, u32 regno, int off, int access_size, bool zero_size_allowed)
```

```json
{
  "name": "__check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580984624,
      "name": "__check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3655",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_boundary",
        "kernel/bpf/verifier.c:check_stack_boundary",
        "kernel/bpf/verifier.c:check_stack_boundary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580984624,
      "name": "__check_stack_boundary",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __check_stack_boundary(struct bpf_verifier_env * env, u32 regno, int off, int access_size, bool zero_size_allowed)
```

```json
{
  "name": "__check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492175368,
      "name": "__check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2934",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_helper_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492175368,
      "name": "__check_stack_boundary",
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
int __check_stack_boundary(struct bpf_verifier_env * env, u32 regno, int off, int access_size, bool zero_size_allowed)
```

```json
{
  "name": "__check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226072476,
      "name": "__check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2934",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_helper_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226072476,
      "name": "__check_stack_boundary",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __check_stack_boundary(struct bpf_verifier_env * env, u32 regno, int off, int access_size, bool zero_size_allowed)
```

```json
{
  "name": "__check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285389168,
      "name": "__check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2934",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_helper_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285389168,
      "name": "__check_stack_boundary",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int __check_stack_boundary(struct bpf_verifier_env * env, u32 regno, int off, int access_size, bool zero_size_allowed)
```

```json
{
  "name": "__check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272331180,
      "name": "__check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2934",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_helper_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272331180,
      "name": "__check_stack_boundary",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
int __check_stack_boundary(struct bpf_verifier_env * env, u32 regno, int off, int access_size, bool zero_size_allowed)
```

```json
{
  "name": "__check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580819008,
      "name": "__check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2934",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_helper_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580819008,
      "name": "__check_stack_boundary",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int __check_stack_boundary(struct bpf_verifier_env * env, u32 regno, int off, int access_size, bool zero_size_allowed)
```

```json
{
  "name": "__check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580765184,
      "name": "__check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2934",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_helper_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580765184,
      "name": "__check_stack_boundary",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int __check_stack_boundary(struct bpf_verifier_env * env, u32 regno, int off, int access_size, bool zero_size_allowed)
```

```json
{
  "name": "__check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580810256,
      "name": "__check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2934",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_helper_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580810256,
      "name": "__check_stack_boundary",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int __check_stack_boundary(struct bpf_verifier_env * env, u32 regno, int off, int access_size, bool zero_size_allowed)
```

```json
{
  "name": "__check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580868640,
      "name": "__check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2934",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_helper_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580868640,
      "name": "__check_stack_boundary",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int __check_stack_boundary(struct bpf_verifier_env * env, u32 regno, int off, int access_size, bool zero_size_allowed)
```
</details>
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
int __check_stack_boundary(struct bpf_verifier_env * env, u32 regno, int off, int access_size, bool zero_size_allowed)
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
