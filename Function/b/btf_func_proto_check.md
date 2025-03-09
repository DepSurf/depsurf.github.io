# Function: <code>btf_func_proto_check</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_func_proto_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580795472,
      "name": "btf_func_proto_check",
      "external": false,
      "loc": "kernel/bpf/btf.c:2306",
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
  "name": "btf_func_proto_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580883346,
      "name": "btf_func_proto_check",
      "external": false,
      "loc": "kernel/bpf/btf.c:2790",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_check_all_types"
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
  "name": "btf_func_proto_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580934306,
      "name": "btf_func_proto_check",
      "external": false,
      "loc": "kernel/bpf/btf.c:2789",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_check_all_types"
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
int btf_func_proto_check(struct btf_verifier_env * env, const struct btf_type * t)
```

```json
{
  "name": "btf_func_proto_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581090400,
      "name": "btf_func_proto_check",
      "external": false,
      "loc": "kernel/bpf/btf.c:2899",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090400,
      "name": "btf_func_proto_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 554
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
int btf_func_proto_check(struct btf_verifier_env * env, const struct btf_type * t)
```

```json
{
  "name": "btf_func_proto_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581116816,
      "name": "btf_func_proto_check",
      "external": false,
      "loc": "kernel/bpf/btf.c:3683",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581116816,
      "name": "btf_func_proto_check",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int btf_func_proto_check(struct btf_verifier_env * env, const struct btf_type * t)
```

```json
{
  "name": "btf_func_proto_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581135568,
      "name": "btf_func_proto_check",
      "external": false,
      "loc": "kernel/bpf/btf.c:3755",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581135568,
      "name": "btf_func_proto_check",
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
int btf_func_proto_check(struct btf_verifier_env * env, const struct btf_type * t)
```

```json
{
  "name": "btf_func_proto_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581368368,
      "name": "btf_func_proto_check",
      "external": false,
      "loc": "kernel/bpf/btf.c:3804",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581368368,
      "name": "btf_func_proto_check",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int btf_func_proto_check(struct btf_verifier_env * env, const struct btf_type * t)
```

```json
{
  "name": "btf_func_proto_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581684512,
      "name": "btf_func_proto_check",
      "external": false,
      "loc": "kernel/bpf/btf.c:4305",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581684512,
      "name": "btf_func_proto_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 734
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
int btf_func_proto_check(struct btf_verifier_env * env, const struct btf_type * t)
```

```json
{
  "name": "btf_func_proto_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582079200,
      "name": "btf_func_proto_check",
      "external": false,
      "loc": "kernel/bpf/btf.c:4729",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582079200,
      "name": "btf_func_proto_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 831
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
int btf_func_proto_check(struct btf_verifier_env * env, const struct btf_type * t)
```

```json
{
  "name": "btf_func_proto_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582275760,
      "name": "btf_func_proto_check",
      "external": false,
      "loc": "kernel/bpf/btf.c:4799",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582275760,
      "name": "btf_func_proto_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 826
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
int btf_func_proto_check(struct btf_verifier_env * env, const struct btf_type * t)
```

```json
{
  "name": "btf_func_proto_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582431296,
      "name": "btf_func_proto_check",
      "external": false,
      "loc": "kernel/bpf/btf.c:4807",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582431296,
      "name": "btf_func_proto_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 826
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
  "name": "btf_func_proto_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492273700,
      "name": "btf_func_proto_check",
      "external": false,
      "loc": "kernel/bpf/btf.c:2789",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_check_all_types"
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
  "name": "btf_func_proto_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226162760,
      "name": "btf_func_proto_check",
      "external": false,
      "loc": "kernel/bpf/btf.c:2789",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_check_all_types"
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
  "name": "btf_func_proto_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285504824,
      "name": "btf_func_proto_check",
      "external": false,
      "loc": "kernel/bpf/btf.c:2789",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_check_all_types"
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
  "name": "btf_func_proto_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272409916,
      "name": "btf_func_proto_check",
      "external": false,
      "loc": "kernel/bpf/btf.c:2789",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_check_all_types"
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
  "name": "btf_func_proto_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580903106,
      "name": "btf_func_proto_check",
      "external": false,
      "loc": "kernel/bpf/btf.c:2789",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_check_all_types"
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
  "name": "btf_func_proto_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580849170,
      "name": "btf_func_proto_check",
      "external": false,
      "loc": "kernel/bpf/btf.c:2789",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_check_all_types"
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
  "name": "btf_func_proto_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580894354,
      "name": "btf_func_proto_check",
      "external": false,
      "loc": "kernel/bpf/btf.c:2789",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_check_all_types"
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
  "name": "btf_func_proto_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580952994,
      "name": "btf_func_proto_check",
      "external": false,
      "loc": "kernel/bpf/btf.c:2789",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_check_all_types"
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
int btf_func_proto_check(struct btf_verifier_env * env, const struct btf_type * t)
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
