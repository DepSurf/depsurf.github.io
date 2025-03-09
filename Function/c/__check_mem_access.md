# Function: <code>__check_mem_access</code>

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
int __check_mem_access(struct bpf_verifier_env * env, int regno, int off, int size, u32 mem_size, bool zero_size_allowed)
```

```json
{
  "name": "__check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580973056,
      "name": "__check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2481",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_packet_access",
        "kernel/bpf/verifier.c:check_mem_region_access",
        "kernel/bpf/verifier.c:check_mem_region_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580973056,
      "name": "__check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
int __check_mem_access(struct bpf_verifier_env * env, int regno, int off, int size, u32 mem_size, bool zero_size_allowed)
```

```json
{
  "name": "__check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580975344,
      "name": "__check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2554",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_packet_access",
        "kernel/bpf/verifier.c:check_mem_region_access",
        "kernel/bpf/verifier.c:check_mem_region_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580975344,
      "name": "__check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
int __check_mem_access(struct bpf_verifier_env * env, int regno, int off, int size, u32 mem_size, bool zero_size_allowed)
```

```json
{
  "name": "__check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580966576,
      "name": "__check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3095",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_packet_access",
        "kernel/bpf/verifier.c:check_mem_region_access",
        "kernel/bpf/verifier.c:check_mem_region_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580966576,
      "name": "__check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
int __check_mem_access(struct bpf_verifier_env * env, int regno, int off, int size, u32 mem_size, bool zero_size_allowed)
```

```json
{
  "name": "__check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581175008,
      "name": "__check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3161",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_packet_access",
        "kernel/bpf/verifier.c:check_mem_region_access",
        "kernel/bpf/verifier.c:check_mem_region_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581175008,
      "name": "__check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __check_mem_access(struct bpf_verifier_env * env, int regno, int off, int size, u32 mem_size, bool zero_size_allowed)
```

```json
{
  "name": "__check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581455184,
      "name": "__check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3524",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_packet_access",
        "kernel/bpf/verifier.c:check_mem_region_access",
        "kernel/bpf/verifier.c:check_mem_region_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581455184,
      "name": "__check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
int __check_mem_access(struct bpf_verifier_env * env, int regno, int off, int size, u32 mem_size, bool zero_size_allowed)
```

```json
{
  "name": "__check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581817248,
      "name": "__check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3966",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_packet_access",
        "kernel/bpf/verifier.c:check_mem_region_access",
        "kernel/bpf/verifier.c:check_mem_region_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581817248,
      "name": "__check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
int __check_mem_access(struct bpf_verifier_env * env, int regno, int off, int size, u32 mem_size, bool zero_size_allowed)
```

```json
{
  "name": "__check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581968256,
      "name": "__check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4851",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_packet_access",
        "kernel/bpf/verifier.c:check_mem_region_access",
        "kernel/bpf/verifier.c:check_mem_region_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581968256,
      "name": "__check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
int __check_mem_access(struct bpf_verifier_env * env, int regno, int off, int size, u32 mem_size, bool zero_size_allowed)
```

```json
{
  "name": "__check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582097456,
      "name": "__check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5009",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_packet_access",
        "kernel/bpf/verifier.c:check_mem_region_access",
        "kernel/bpf/verifier.c:check_mem_region_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582097456,
      "name": "__check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
int __check_mem_access(struct bpf_verifier_env * env, int regno, int off, int size, u32 mem_size, bool zero_size_allowed)
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
