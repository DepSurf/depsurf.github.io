# Function: <code>btf_check_all_metas</code>

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
  "name": "btf_check_all_metas",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580716288,
      "name": "btf_check_all_metas",
      "external": false,
      "loc": "kernel/bpf/btf.c:1839",
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
  "name": "btf_check_all_metas",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580794630,
      "name": "btf_check_all_metas",
      "external": false,
      "loc": "kernel/bpf/btf.c:2481",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_parse_type_sec"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_check_all_metas",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580885109,
      "name": "btf_check_all_metas",
      "external": false,
      "loc": "kernel/bpf/btf.c:2967",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_check_all_metas",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580936069,
      "name": "btf_check_all_metas",
      "external": false,
      "loc": "kernel/bpf/btf.c:2966",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int btf_check_all_metas(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_check_all_metas",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581076368,
      "name": "btf_check_all_metas",
      "external": false,
      "loc": "kernel/bpf/btf.c:3076",
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
      "addr": 18446744071581076368,
      "name": "btf_check_all_metas",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 385
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
int btf_check_all_metas(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_check_all_metas",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581088416,
      "name": "btf_check_all_metas",
      "external": false,
      "loc": "kernel/bpf/btf.c:3860",
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
      "addr": 18446744071581088416,
      "name": "btf_check_all_metas",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
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
int btf_check_all_metas(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_check_all_metas",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581108064,
      "name": "btf_check_all_metas",
      "external": false,
      "loc": "kernel/bpf/btf.c:3933",
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
      "addr": 18446744071581108064,
      "name": "btf_check_all_metas",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 662
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
int btf_check_all_metas(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_check_all_metas",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581338160,
      "name": "btf_check_all_metas",
      "external": false,
      "loc": "kernel/bpf/btf.c:3982",
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
      "addr": 18446744071581338160,
      "name": "btf_check_all_metas",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 702
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
int btf_check_all_metas(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_check_all_metas",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581645552,
      "name": "btf_check_all_metas",
      "external": false,
      "loc": "kernel/bpf/btf.c:4485",
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
      "addr": 18446744071581645552,
      "name": "btf_check_all_metas",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
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
int btf_check_all_metas(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_check_all_metas",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582037280,
      "name": "btf_check_all_metas",
      "external": false,
      "loc": "kernel/bpf/btf.c:4916",
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
      "addr": 18446744071582037280,
      "name": "btf_check_all_metas",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
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
int btf_check_all_metas(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_check_all_metas",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582230192,
      "name": "btf_check_all_metas",
      "external": false,
      "loc": "kernel/bpf/btf.c:4986",
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
      "addr": 18446744071582230192,
      "name": "btf_check_all_metas",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
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
int btf_check_all_metas(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_check_all_metas",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582386144,
      "name": "btf_check_all_metas",
      "external": false,
      "loc": "kernel/bpf/btf.c:4994",
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
      "addr": 18446744071582386144,
      "name": "btf_check_all_metas",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "btf_check_all_metas",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492275792,
      "name": "btf_check_all_metas",
      "external": false,
      "loc": "kernel/bpf/btf.c:2966",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "btf_check_all_metas",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226164712,
      "name": "btf_check_all_metas",
      "external": false,
      "loc": "kernel/bpf/btf.c:2966",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "btf_check_all_metas",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285507668,
      "name": "btf_check_all_metas",
      "external": false,
      "loc": "kernel/bpf/btf.c:2966",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "btf_check_all_metas",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272411538,
      "name": "btf_check_all_metas",
      "external": false,
      "loc": "kernel/bpf/btf.c:2966",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_check_all_metas",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580904869,
      "name": "btf_check_all_metas",
      "external": false,
      "loc": "kernel/bpf/btf.c:2966",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_check_all_metas",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580850933,
      "name": "btf_check_all_metas",
      "external": false,
      "loc": "kernel/bpf/btf.c:2966",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_check_all_metas",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580896117,
      "name": "btf_check_all_metas",
      "external": false,
      "loc": "kernel/bpf/btf.c:2966",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_check_all_metas",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580954773,
      "name": "btf_check_all_metas",
      "external": false,
      "loc": "kernel/bpf/btf.c:2966",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int btf_check_all_metas(struct btf_verifier_env * env)
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
