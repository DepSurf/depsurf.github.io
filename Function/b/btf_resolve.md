# Function: <code>btf_resolve</code>

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
  "name": "btf_resolve",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580717272,
      "name": "btf_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:1866",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int btf_resolve(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "btf_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580794000,
      "name": "btf_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:2541",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_type_sec",
        "kernel/bpf/btf.c:btf_parse_type_sec",
        "kernel/bpf/btf.c:btf_parse_type_sec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580794000,
      "name": "btf_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
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
int btf_resolve(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "btf_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580882480,
      "name": "btf_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:3031",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580882480,
      "name": "btf_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
int btf_resolve(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "btf_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580933440,
      "name": "btf_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:3030",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580933440,
      "name": "btf_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
int btf_resolve(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "btf_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581089824,
      "name": "btf_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:3140",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581089824,
      "name": "btf_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 567
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
int btf_resolve(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "btf_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581116528,
      "name": "btf_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:3924",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581116528,
      "name": "btf_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
int btf_resolve(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "btf_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581135280,
      "name": "btf_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:3997",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581135280,
      "name": "btf_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
int btf_resolve(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "btf_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581367984,
      "name": "btf_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:4046",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581367984,
      "name": "btf_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
int btf_resolve(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "btf_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581684112,
      "name": "btf_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:4553",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581684112,
      "name": "btf_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
int btf_resolve(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "btf_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582078784,
      "name": "btf_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:4984",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582078784,
      "name": "btf_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
int btf_resolve(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "btf_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582275344,
      "name": "btf_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:5054",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582275344,
      "name": "btf_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
int btf_resolve(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "btf_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582430880,
      "name": "btf_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:5062",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582430880,
      "name": "btf_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
int btf_resolve(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "btf_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492272808,
      "name": "btf_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:3030",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492272808,
      "name": "btf_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
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
int btf_resolve(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "btf_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226161856,
      "name": "btf_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:3030",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226161856,
      "name": "btf_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
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
int btf_resolve(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "btf_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285503760,
      "name": "btf_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:3030",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285503760,
      "name": "btf_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
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
int btf_resolve(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "btf_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272409166,
      "name": "btf_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:3030",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272409166,
      "name": "btf_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
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
int btf_resolve(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "btf_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580902240,
      "name": "btf_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:3030",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580902240,
      "name": "btf_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
int btf_resolve(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "btf_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580848304,
      "name": "btf_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:3030",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580848304,
      "name": "btf_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
int btf_resolve(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "btf_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580893488,
      "name": "btf_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:3030",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580893488,
      "name": "btf_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
int btf_resolve(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
```

```json
{
  "name": "btf_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580952128,
      "name": "btf_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:3030",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580952128,
      "name": "btf_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
int btf_resolve(struct btf_verifier_env * env, const struct btf_type * t, u32 type_id)
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
