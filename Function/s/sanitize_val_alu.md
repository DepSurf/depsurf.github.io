# Function: <code>sanitize_val_alu</code>

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
int sanitize_val_alu(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "sanitize_val_alu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580703056,
      "name": "sanitize_val_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3132",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580703056,
      "name": "sanitize_val_alu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int sanitize_val_alu(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "sanitize_val_alu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580772352,
      "name": "sanitize_val_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4255",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580772352,
      "name": "sanitize_val_alu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int sanitize_val_alu(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "sanitize_val_alu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580823264,
      "name": "sanitize_val_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4258",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580823264,
      "name": "sanitize_val_alu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
  "name": "sanitize_val_alu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580955136,
      "name": "sanitize_val_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4935",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580955136,
      "name": "sanitize_val_alu.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sanitize_val_alu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580954784,
      "name": "sanitize_val_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5446",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580954784,
      "name": "sanitize_val_alu.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sanitize_val_alu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580981966,
      "name": "sanitize_val_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6447",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
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
  "name": "sanitize_val_alu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581194228,
      "name": "sanitize_val_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6736",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
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
  "name": "sanitize_val_alu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581479448,
      "name": "sanitize_val_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7735",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
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
  "name": "sanitize_val_alu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581838680,
      "name": "sanitize_val_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9671",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
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
  "name": "sanitize_val_alu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582057638,
      "name": "sanitize_val_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:11587",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
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
  "name": "sanitize_val_alu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582191670,
      "name": "sanitize_val_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:12521",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
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
int sanitize_val_alu(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "sanitize_val_alu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492147360,
      "name": "sanitize_val_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4258",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492147360,
      "name": "sanitize_val_alu",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int sanitize_val_alu(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "sanitize_val_alu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226042868,
      "name": "sanitize_val_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4258",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226042868,
      "name": "sanitize_val_alu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int sanitize_val_alu(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "sanitize_val_alu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285354416,
      "name": "sanitize_val_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4258",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285354416,
      "name": "sanitize_val_alu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int sanitize_val_alu(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "sanitize_val_alu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272307992,
      "name": "sanitize_val_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4258",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272307992,
      "name": "sanitize_val_alu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int sanitize_val_alu(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "sanitize_val_alu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580792064,
      "name": "sanitize_val_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4258",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580792064,
      "name": "sanitize_val_alu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int sanitize_val_alu(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "sanitize_val_alu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580738240,
      "name": "sanitize_val_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4258",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580738240,
      "name": "sanitize_val_alu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int sanitize_val_alu(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "sanitize_val_alu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580783312,
      "name": "sanitize_val_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4258",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580783312,
      "name": "sanitize_val_alu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int sanitize_val_alu(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "sanitize_val_alu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580841696,
      "name": "sanitize_val_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4258",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580841696,
      "name": "sanitize_val_alu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int sanitize_val_alu(struct bpf_verifier_env * env, struct bpf_insn * insn)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int sanitize_val_alu(struct bpf_verifier_env * env, struct bpf_insn * insn)
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
