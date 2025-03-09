# Function: <code>propagate_liveness_reg</code>

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
int propagate_liveness_reg(struct bpf_verifier_env * env, struct bpf_reg_state * reg, struct bpf_reg_state * parent_reg)
```

```json
{
  "name": "propagate_liveness_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580787024,
      "name": "propagate_liveness_reg",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7087",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580787024,
      "name": "propagate_liveness_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
int propagate_liveness_reg(struct bpf_verifier_env * env, struct bpf_reg_state * reg, struct bpf_reg_state * parent_reg)
```

```json
{
  "name": "propagate_liveness_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580838128,
      "name": "propagate_liveness_reg",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7102",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580838128,
      "name": "propagate_liveness_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "propagate_liveness_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580970585,
      "name": "propagate_liveness_reg",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8235",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:propagate_liveness",
        "kernel/bpf/verifier.c:propagate_liveness"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "propagate_liveness_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580970036,
      "name": "propagate_liveness_reg",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9023",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:propagate_liveness",
        "kernel/bpf/verifier.c:propagate_liveness"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "propagate_liveness_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580970162,
      "name": "propagate_liveness_reg",
      "external": false,
      "loc": "kernel/bpf/verifier.c:10187",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:propagate_liveness",
        "kernel/bpf/verifier.c:propagate_liveness"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "propagate_liveness_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581179929,
      "name": "propagate_liveness_reg",
      "external": false,
      "loc": "kernel/bpf/verifier.c:10518",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:propagate_liveness",
        "kernel/bpf/verifier.c:propagate_liveness"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "propagate_liveness_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581458804,
      "name": "propagate_liveness_reg",
      "external": false,
      "loc": "kernel/bpf/verifier.c:11574",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:propagate_liveness",
        "kernel/bpf/verifier.c:propagate_liveness"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "propagate_liveness_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581821065,
      "name": "propagate_liveness_reg",
      "external": false,
      "loc": "kernel/bpf/verifier.c:13570",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:propagate_liveness",
        "kernel/bpf/verifier.c:propagate_liveness"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "propagate_liveness_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581978322,
      "name": "propagate_liveness_reg",
      "external": false,
      "loc": "kernel/bpf/verifier.c:15619",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:propagate_liveness",
        "kernel/bpf/verifier.c:propagate_liveness"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "propagate_liveness_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582106610,
      "name": "propagate_liveness_reg",
      "external": false,
      "loc": "kernel/bpf/verifier.c:16677",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:propagate_liveness",
        "kernel/bpf/verifier.c:propagate_liveness"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int propagate_liveness_reg(struct bpf_verifier_env * env, struct bpf_reg_state * reg, struct bpf_reg_state * parent_reg)
```

```json
{
  "name": "propagate_liveness_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492163336,
      "name": "propagate_liveness_reg",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7102",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492163336,
      "name": "propagate_liveness_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int propagate_liveness_reg(struct bpf_verifier_env * env, struct bpf_reg_state * reg, struct bpf_reg_state * parent_reg)
```

```json
{
  "name": "propagate_liveness_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226059048,
      "name": "propagate_liveness_reg",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7102",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226059048,
      "name": "propagate_liveness_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int propagate_liveness_reg(struct bpf_verifier_env * env, struct bpf_reg_state * reg, struct bpf_reg_state * parent_reg)
```

```json
{
  "name": "propagate_liveness_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285374176,
      "name": "propagate_liveness_reg",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7102",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285374176,
      "name": "propagate_liveness_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int propagate_liveness_reg(struct bpf_verifier_env * env, struct bpf_reg_state * reg, struct bpf_reg_state * parent_reg)
```

```json
{
  "name": "propagate_liveness_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272320912,
      "name": "propagate_liveness_reg",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7102",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272320912,
      "name": "propagate_liveness_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int propagate_liveness_reg(struct bpf_verifier_env * env, struct bpf_reg_state * reg, struct bpf_reg_state * parent_reg)
```

```json
{
  "name": "propagate_liveness_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580806928,
      "name": "propagate_liveness_reg",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7102",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580806928,
      "name": "propagate_liveness_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
int propagate_liveness_reg(struct bpf_verifier_env * env, struct bpf_reg_state * reg, struct bpf_reg_state * parent_reg)
```

```json
{
  "name": "propagate_liveness_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580753104,
      "name": "propagate_liveness_reg",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7102",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580753104,
      "name": "propagate_liveness_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
int propagate_liveness_reg(struct bpf_verifier_env * env, struct bpf_reg_state * reg, struct bpf_reg_state * parent_reg)
```

```json
{
  "name": "propagate_liveness_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580798176,
      "name": "propagate_liveness_reg",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7102",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580798176,
      "name": "propagate_liveness_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
int propagate_liveness_reg(struct bpf_verifier_env * env, struct bpf_reg_state * reg, struct bpf_reg_state * parent_reg)
```

```json
{
  "name": "propagate_liveness_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580856560,
      "name": "propagate_liveness_reg",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7102",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580856560,
      "name": "propagate_liveness_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
int propagate_liveness_reg(struct bpf_verifier_env * env, struct bpf_reg_state * reg, struct bpf_reg_state * parent_reg)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int propagate_liveness_reg(struct bpf_verifier_env * env, struct bpf_reg_state * reg, struct bpf_reg_state * parent_reg)
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
