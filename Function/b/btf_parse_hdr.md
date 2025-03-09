# Function: <code>btf_parse_hdr</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_parse_hdr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580715322,
      "name": "btf_parse_hdr",
      "external": false,
      "loc": "kernel/bpf/btf.c:2070",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_new_fd"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_parse_hdr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580797087,
      "name": "btf_parse_hdr",
      "external": false,
      "loc": "kernel/bpf/btf.c:2727",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_new_fd"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int btf_parse_hdr(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_parse_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580874240,
      "name": "btf_parse_hdr",
      "external": false,
      "loc": "kernel/bpf/btf.c:3217",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580874240,
      "name": "btf_parse_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 991
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
int btf_parse_hdr(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_parse_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580925216,
      "name": "btf_parse_hdr",
      "external": false,
      "loc": "kernel/bpf/btf.c:3216",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580925216,
      "name": "btf_parse_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 991
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
int btf_parse_hdr(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_parse_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581077168,
      "name": "btf_parse_hdr",
      "external": false,
      "loc": "kernel/bpf/btf.c:3326",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_vmlinux",
        "kernel/bpf/btf.c:btf_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581077168,
      "name": "btf_parse_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
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
int btf_parse_hdr(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_parse_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581089232,
      "name": "btf_parse_hdr",
      "external": false,
      "loc": "kernel/bpf/btf.c:4117",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_module",
        "kernel/bpf/btf.c:btf_parse_vmlinux",
        "kernel/bpf/btf.c:btf_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581089232,
      "name": "btf_parse_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
int btf_parse_hdr(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_parse_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581107040,
      "name": "btf_parse_hdr",
      "external": false,
      "loc": "kernel/bpf/btf.c:4190",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_module",
        "kernel/bpf/btf.c:btf_parse_vmlinux",
        "kernel/bpf/btf.c:btf_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581107040,
      "name": "btf_parse_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1010
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
int btf_parse_hdr(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_parse_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581337136,
      "name": "btf_parse_hdr",
      "external": false,
      "loc": "kernel/bpf/btf.c:4239",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_module",
        "kernel/bpf/btf.c:btf_parse_vmlinux",
        "kernel/bpf/btf.c:btf_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581337136,
      "name": "btf_parse_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1010
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
int btf_parse_hdr(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_parse_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581644336,
      "name": "btf_parse_hdr",
      "external": false,
      "loc": "kernel/bpf/btf.c:4740",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_module",
        "kernel/bpf/btf.c:btf_parse_vmlinux",
        "kernel/bpf/btf.c:btf_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581644336,
      "name": "btf_parse_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
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
int btf_parse_hdr(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_parse_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582036032,
      "name": "btf_parse_hdr",
      "external": false,
      "loc": "kernel/bpf/btf.c:5171",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_module",
        "kernel/bpf/btf.c:btf_parse_vmlinux",
        "kernel/bpf/btf.c:btf_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582036032,
      "name": "btf_parse_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
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
int btf_parse_hdr(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_parse_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582226784,
      "name": "btf_parse_hdr",
      "external": false,
      "loc": "kernel/bpf/btf.c:5241",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_module",
        "kernel/bpf/btf.c:btf_parse_vmlinux",
        "kernel/bpf/btf.c:btf_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582226784,
      "name": "btf_parse_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 925
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
int btf_parse_hdr(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_parse_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582382736,
      "name": "btf_parse_hdr",
      "external": false,
      "loc": "kernel/bpf/btf.c:5249",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_module",
        "kernel/bpf/btf.c:btf_parse_vmlinux",
        "kernel/bpf/btf.c:btf_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582382736,
      "name": "btf_parse_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 925
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int btf_parse_hdr(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_parse_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492261968,
      "name": "btf_parse_hdr",
      "external": false,
      "loc": "kernel/bpf/btf.c:3216",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492261968,
      "name": "btf_parse_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 928
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
int btf_parse_hdr(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_parse_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226148528,
      "name": "btf_parse_hdr",
      "external": false,
      "loc": "kernel/bpf/btf.c:3216",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226148528,
      "name": "btf_parse_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 892
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
int btf_parse_hdr(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_parse_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285491808,
      "name": "btf_parse_hdr",
      "external": false,
      "loc": "kernel/bpf/btf.c:3216",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285491808,
      "name": "btf_parse_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1064
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
int btf_parse_hdr(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_parse_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272401282,
      "name": "btf_parse_hdr",
      "external": false,
      "loc": "kernel/bpf/btf.c:3216",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272401282,
      "name": "btf_parse_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 802
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
int btf_parse_hdr(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_parse_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580894016,
      "name": "btf_parse_hdr",
      "external": false,
      "loc": "kernel/bpf/btf.c:3216",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580894016,
      "name": "btf_parse_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 991
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
int btf_parse_hdr(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_parse_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580840080,
      "name": "btf_parse_hdr",
      "external": false,
      "loc": "kernel/bpf/btf.c:3216",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580840080,
      "name": "btf_parse_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 991
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
int btf_parse_hdr(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_parse_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580885264,
      "name": "btf_parse_hdr",
      "external": false,
      "loc": "kernel/bpf/btf.c:3216",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580885264,
      "name": "btf_parse_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 991
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
int btf_parse_hdr(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_parse_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580943904,
      "name": "btf_parse_hdr",
      "external": false,
      "loc": "kernel/bpf/btf.c:3216",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580943904,
      "name": "btf_parse_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 991
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
int btf_parse_hdr(struct btf_verifier_env * env)
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
