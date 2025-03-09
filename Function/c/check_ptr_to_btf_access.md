# Function: <code>check_ptr_to_btf_access</code>

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
int check_ptr_to_btf_access(struct bpf_verifier_env * env, struct bpf_reg_state * regs, int regno, int off, int size, enum bpf_access_type atype, int value_regno)
```

```json
{
  "name": "check_ptr_to_btf_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580978400,
      "name": "check_ptr_to_btf_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3140",
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
      "addr": 18446744071580978400,
      "name": "check_ptr_to_btf_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
int check_ptr_to_btf_access(struct bpf_verifier_env * env, struct bpf_reg_state * regs, int regno, int off, int size, enum bpf_access_type atype, int value_regno)
```

```json
{
  "name": "check_ptr_to_btf_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580981648,
      "name": "check_ptr_to_btf_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3298",
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
      "addr": 18446744071580981648,
      "name": "check_ptr_to_btf_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
int check_ptr_to_btf_access(struct bpf_verifier_env * env, struct bpf_reg_state * regs, int regno, int off, int size, enum bpf_access_type atype, int value_regno)
```

```json
{
  "name": "check_ptr_to_btf_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580992080,
      "name": "check_ptr_to_btf_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3841",
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
      "addr": 18446744071580992080,
      "name": "check_ptr_to_btf_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
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
int check_ptr_to_btf_access(struct bpf_verifier_env * env, struct bpf_reg_state * regs, int regno, int off, int size, enum bpf_access_type atype, int value_regno)
```

```json
{
  "name": "check_ptr_to_btf_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581205056,
      "name": "check_ptr_to_btf_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3942",
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
      "addr": 18446744071581205056,
      "name": "check_ptr_to_btf_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
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
int check_ptr_to_btf_access(struct bpf_verifier_env * env, struct bpf_reg_state * regs, int regno, int off, int size, enum bpf_access_type atype, int value_regno)
```

```json
{
  "name": "check_ptr_to_btf_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581488688,
      "name": "check_ptr_to_btf_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4469",
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
      "addr": 18446744071581488688,
      "name": "check_ptr_to_btf_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 659
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
int check_ptr_to_btf_access(struct bpf_verifier_env * env, struct bpf_reg_state * regs, int regno, int off, int size, enum bpf_access_type atype, int value_regno)
```

```json
{
  "name": "check_ptr_to_btf_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_ptr_to_btf_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4924",
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
      "addr": 18446744071581825280,
      "name": "check_ptr_to_btf_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1042
    },
    {
      "addr": 18446744071596015812,
      "name": "check_ptr_to_btf_access.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
int check_ptr_to_btf_access(struct bpf_verifier_env * env, struct bpf_reg_state * regs, int regno, int off, int size, enum bpf_access_type atype, int value_regno)
```

```json
{
  "name": "check_ptr_to_btf_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_ptr_to_btf_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5974",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581987008,
      "name": "check_ptr_to_btf_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1303
    },
    {
      "addr": 18446744071596535620,
      "name": "check_ptr_to_btf_access.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
int check_ptr_to_btf_access(struct bpf_verifier_env * env, struct bpf_reg_state * regs, int regno, int off, int size, enum bpf_access_type atype, int value_regno)
```

```json
{
  "name": "check_ptr_to_btf_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_ptr_to_btf_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6348",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582151024,
      "name": "check_ptr_to_btf_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1358
    },
    {
      "addr": 18446744071597438920,
      "name": "check_ptr_to_btf_access.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
int check_ptr_to_btf_access(struct bpf_verifier_env * env, struct bpf_reg_state * regs, int regno, int off, int size, enum bpf_access_type atype, int value_regno)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
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
