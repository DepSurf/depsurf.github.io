# Function: <code>btf_check_all_types</code>

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
  "name": "btf_check_all_types",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580717032,
      "name": "btf_check_all_types",
      "external": false,
      "loc": "kernel/bpf/btf.c:1923",
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
  "name": "btf_check_all_types",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580795190,
      "name": "btf_check_all_types",
      "external": false,
      "loc": "kernel/bpf/btf.c:2574",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int btf_check_all_types(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_check_all_types",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580883056,
      "name": "btf_check_all_types",
      "external": false,
      "loc": "kernel/bpf/btf.c:3064",
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
      "addr": 18446744071580883056,
      "name": "btf_check_all_types",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1032
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
int btf_check_all_types(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_check_all_types",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580934016,
      "name": "btf_check_all_types",
      "external": false,
      "loc": "kernel/bpf/btf.c:3063",
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
      "addr": 18446744071580934016,
      "name": "btf_check_all_types",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1032
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
int btf_check_all_types(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_check_all_types",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581090960,
      "name": "btf_check_all_types",
      "external": false,
      "loc": "kernel/bpf/btf.c:3173",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090960,
      "name": "btf_check_all_types",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
int btf_check_all_types(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_check_all_types",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581117488,
      "name": "btf_check_all_types",
      "external": false,
      "loc": "kernel/bpf/btf.c:3957",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581117488,
      "name": "btf_check_all_types",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
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
int btf_check_all_types(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_check_all_types",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581136240,
      "name": "btf_check_all_types",
      "external": false,
      "loc": "kernel/bpf/btf.c:4030",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136240,
      "name": "btf_check_all_types",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 652
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
int btf_check_all_types(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_check_all_types",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581369040,
      "name": "btf_check_all_types",
      "external": false,
      "loc": "kernel/bpf/btf.c:4079",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581369040,
      "name": "btf_check_all_types",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 652
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
int btf_check_all_types(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_check_all_types",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581685248,
      "name": "btf_check_all_types",
      "external": false,
      "loc": "kernel/bpf/btf.c:4586",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581685248,
      "name": "btf_check_all_types",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int btf_check_all_types(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_check_all_types",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582080048,
      "name": "btf_check_all_types",
      "external": false,
      "loc": "kernel/bpf/btf.c:5017",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582080048,
      "name": "btf_check_all_types",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int btf_check_all_types(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_check_all_types",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582276608,
      "name": "btf_check_all_types",
      "external": false,
      "loc": "kernel/bpf/btf.c:5087",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582276608,
      "name": "btf_check_all_types",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
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
int btf_check_all_types(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_check_all_types",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582432144,
      "name": "btf_check_all_types",
      "external": false,
      "loc": "kernel/bpf/btf.c:5095",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582432144,
      "name": "btf_check_all_types",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
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
int btf_check_all_types(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_check_all_types",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492273416,
      "name": "btf_check_all_types",
      "external": false,
      "loc": "kernel/bpf/btf.c:3063",
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
      "addr": 18446603336492273416,
      "name": "btf_check_all_types",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1024
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
int btf_check_all_types(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_check_all_types",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226162464,
      "name": "btf_check_all_types",
      "external": false,
      "loc": "kernel/bpf/btf.c:3063",
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
      "addr": 3226162464,
      "name": "btf_check_all_types",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1104
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
int btf_check_all_types(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_check_all_types",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285504464,
      "name": "btf_check_all_types",
      "external": false,
      "loc": "kernel/bpf/btf.c:3063",
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
      "addr": 13835058055285504464,
      "name": "btf_check_all_types",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1276
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
int btf_check_all_types(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_check_all_types",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272409652,
      "name": "btf_check_all_types",
      "external": false,
      "loc": "kernel/bpf/btf.c:3063",
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
      "addr": 18446743936272409652,
      "name": "btf_check_all_types",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 852
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
int btf_check_all_types(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_check_all_types",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580902816,
      "name": "btf_check_all_types",
      "external": false,
      "loc": "kernel/bpf/btf.c:3063",
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
      "addr": 18446744071580902816,
      "name": "btf_check_all_types",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1032
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
int btf_check_all_types(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_check_all_types",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580848880,
      "name": "btf_check_all_types",
      "external": false,
      "loc": "kernel/bpf/btf.c:3063",
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
      "addr": 18446744071580848880,
      "name": "btf_check_all_types",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1032
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
int btf_check_all_types(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_check_all_types",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580894064,
      "name": "btf_check_all_types",
      "external": false,
      "loc": "kernel/bpf/btf.c:3063",
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
      "addr": 18446744071580894064,
      "name": "btf_check_all_types",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1032
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
int btf_check_all_types(struct btf_verifier_env * env)
```

```json
{
  "name": "btf_check_all_types",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580952704,
      "name": "btf_check_all_types",
      "external": false,
      "loc": "kernel/bpf/btf.c:3063",
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
      "addr": 18446744071580952704,
      "name": "btf_check_all_types",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1032
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
int btf_check_all_types(struct btf_verifier_env * env)
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
