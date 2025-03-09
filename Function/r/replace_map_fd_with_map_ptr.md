# Function: <code>replace_map_fd_with_map_ptr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "replace_map_fd_with_map_ptr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580378053,
      "name": "replace_map_fd_with_map_ptr",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1961",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "replace_map_fd_with_map_ptr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580437992,
      "name": "replace_map_fd_with_map_ptr",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2489",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "replace_map_fd_with_map_ptr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580492594,
      "name": "replace_map_fd_with_map_ptr",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2933",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "replace_map_fd_with_map_ptr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580520796,
      "name": "replace_map_fd_with_map_ptr",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3370",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "replace_map_fd_with_map_ptr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580582160,
      "name": "replace_map_fd_with_map_ptr",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4174",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "replace_map_fd_with_map_ptr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580674780,
      "name": "replace_map_fd_with_map_ptr",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5068",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
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
  "name": "replace_map_fd_with_map_ptr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580743564,
      "name": "replace_map_fd_with_map_ptr",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6239",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
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
int replace_map_fd_with_map_ptr(struct bpf_verifier_env * env)
```

```json
{
  "name": "replace_map_fd_with_map_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580783472,
      "name": "replace_map_fd_with_map_ptr",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7890",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580783472,
      "name": "replace_map_fd_with_map_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1427
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
int replace_map_fd_with_map_ptr(struct bpf_verifier_env * env)
```

```json
{
  "name": "replace_map_fd_with_map_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580834416,
      "name": "replace_map_fd_with_map_ptr",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7905",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580834416,
      "name": "replace_map_fd_with_map_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1427
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
int replace_map_fd_with_map_ptr(struct bpf_verifier_env * env)
```

```json
{
  "name": "replace_map_fd_with_map_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580964144,
      "name": "replace_map_fd_with_map_ptr",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9033",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580964144,
      "name": "replace_map_fd_with_map_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1169
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
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
int replace_map_fd_with_map_ptr(struct bpf_verifier_env * env)
```

```json
{
  "name": "replace_map_fd_with_map_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492158408,
      "name": "replace_map_fd_with_map_ptr",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7905",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492158408,
      "name": "replace_map_fd_with_map_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1424
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
int replace_map_fd_with_map_ptr(struct bpf_verifier_env * env)
```

```json
{
  "name": "replace_map_fd_with_map_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226054848,
      "name": "replace_map_fd_with_map_ptr",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7905",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226054848,
      "name": "replace_map_fd_with_map_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1508
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
int replace_map_fd_with_map_ptr(struct bpf_verifier_env * env)
```

```json
{
  "name": "replace_map_fd_with_map_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285369328,
      "name": "replace_map_fd_with_map_ptr",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7905",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285369328,
      "name": "replace_map_fd_with_map_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1680
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
int replace_map_fd_with_map_ptr(struct bpf_verifier_env * env)
```

```json
{
  "name": "replace_map_fd_with_map_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272317744,
      "name": "replace_map_fd_with_map_ptr",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7905",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272317744,
      "name": "replace_map_fd_with_map_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1140
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
int replace_map_fd_with_map_ptr(struct bpf_verifier_env * env)
```

```json
{
  "name": "replace_map_fd_with_map_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580803216,
      "name": "replace_map_fd_with_map_ptr",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7905",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580803216,
      "name": "replace_map_fd_with_map_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1427
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
int replace_map_fd_with_map_ptr(struct bpf_verifier_env * env)
```

```json
{
  "name": "replace_map_fd_with_map_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580749392,
      "name": "replace_map_fd_with_map_ptr",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7905",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580749392,
      "name": "replace_map_fd_with_map_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1427
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
int replace_map_fd_with_map_ptr(struct bpf_verifier_env * env)
```

```json
{
  "name": "replace_map_fd_with_map_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580794464,
      "name": "replace_map_fd_with_map_ptr",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7905",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580794464,
      "name": "replace_map_fd_with_map_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1427
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
int replace_map_fd_with_map_ptr(struct bpf_verifier_env * env)
```

```json
{
  "name": "replace_map_fd_with_map_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580852848,
      "name": "replace_map_fd_with_map_ptr",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7905",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580852848,
      "name": "replace_map_fd_with_map_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1427
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
int replace_map_fd_with_map_ptr(struct bpf_verifier_env * env)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int replace_map_fd_with_map_ptr(struct bpf_verifier_env * env)
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
