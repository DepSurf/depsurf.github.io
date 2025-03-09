# Function: <code>realloc_stack_state</code>

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
int realloc_stack_state(struct bpf_func_state * state, int size, bool copy_old)
```

```json
{
  "name": "realloc_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580707552,
      "name": "realloc_stack_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:573",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:copy_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580707552,
      "name": "realloc_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
int realloc_stack_state(struct bpf_func_state * state, int size, bool copy_old)
```

```json
{
  "name": "realloc_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580781760,
      "name": "realloc_stack_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:596",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:copy_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580781760,
      "name": "realloc_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
int realloc_stack_state(struct bpf_func_state * state, int size, bool copy_old)
```

```json
{
  "name": "realloc_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580832688,
      "name": "realloc_stack_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:596",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:copy_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580832688,
      "name": "realloc_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
int realloc_stack_state(struct bpf_func_state * state, int size, bool copy_old)
```

```json
{
  "name": "realloc_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580961184,
      "name": "realloc_stack_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:723",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_write",
        "kernel/bpf/verifier.c:copy_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580961184,
      "name": "realloc_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
int realloc_stack_state(struct bpf_func_state * state, int size, bool copy_old)
```

```json
{
  "name": "realloc_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580961120,
      "name": "realloc_stack_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:749",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_write",
        "kernel/bpf/verifier.c:copy_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580961120,
      "name": "realloc_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
int realloc_stack_state(struct bpf_func_state * state, int size, bool copy_old)
```

```json
{
  "name": "realloc_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580960880,
      "name": "realloc_stack_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:798",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_write_var_off",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off",
        "kernel/bpf/verifier.c:copy_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580960880,
      "name": "realloc_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
  "name": "realloc_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492191264,
      "name": "realloc_stack_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:596",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_stack_write",
        "kernel/bpf/verifier.c:copy_verifier_state"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "realloc_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226087624,
      "name": "realloc_stack_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:596",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_stack_write",
        "kernel/bpf/verifier.c:copy_verifier_state"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "realloc_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285407924,
      "name": "realloc_stack_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:596",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_stack_write",
        "kernel/bpf/verifier.c:copy_verifier_state"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "realloc_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272343884,
      "name": "realloc_stack_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:596",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_stack_write",
        "kernel/bpf/verifier.c:copy_verifier_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int realloc_stack_state(struct bpf_func_state * state, int size, bool copy_old)
```

```json
{
  "name": "realloc_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580801488,
      "name": "realloc_stack_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:596",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:copy_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580801488,
      "name": "realloc_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
int realloc_stack_state(struct bpf_func_state * state, int size, bool copy_old)
```

```json
{
  "name": "realloc_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580747664,
      "name": "realloc_stack_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:596",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:copy_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580747664,
      "name": "realloc_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
int realloc_stack_state(struct bpf_func_state * state, int size, bool copy_old)
```

```json
{
  "name": "realloc_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580792736,
      "name": "realloc_stack_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:596",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:copy_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580792736,
      "name": "realloc_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
int realloc_stack_state(struct bpf_func_state * state, int size, bool copy_old)
```

```json
{
  "name": "realloc_stack_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580851120,
      "name": "realloc_stack_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:596",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:copy_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580851120,
      "name": "realloc_stack_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
int realloc_stack_state(struct bpf_func_state * state, int size, bool copy_old)
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
int realloc_stack_state(struct bpf_func_state * state, int size, bool copy_old)
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
int realloc_stack_state(struct bpf_func_state * state, int size, bool copy_old)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int realloc_stack_state(struct bpf_func_state * state, int size, bool copy_old)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int realloc_stack_state(struct bpf_func_state * state, int size, bool copy_old)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int realloc_stack_state(struct bpf_func_state * state, int size, bool copy_old)
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
