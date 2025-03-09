# Function: <code>reg_set_min_max_inv</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reg_set_min_max_inv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580488004,
      "name": "reg_set_min_max_inv",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1925",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
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
  "name": "reg_set_min_max_inv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580516978,
      "name": "reg_set_min_max_inv",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2307",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
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
  "name": "reg_set_min_max_inv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580570669,
      "name": "reg_set_min_max_inv",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2719",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
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
  "name": "reg_set_min_max_inv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580663357,
      "name": "reg_set_min_max_inv",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3510",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
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
  "name": "reg_set_min_max_inv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580729402,
      "name": "reg_set_min_max_inv",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4200",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
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
void reg_set_min_max_inv(struct bpf_reg_state * true_reg, struct bpf_reg_state * false_reg, u64 val, u8 opcode, bool is_jmp32)
```

```json
{
  "name": "reg_set_min_max_inv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580773888,
      "name": "reg_set_min_max_inv",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5445",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580773888,
      "name": "reg_set_min_max_inv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 999
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
void reg_set_min_max_inv(struct bpf_reg_state * true_reg, struct bpf_reg_state * false_reg, u64 val, u8 opcode, bool is_jmp32)
```

```json
{
  "name": "reg_set_min_max_inv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580824672,
      "name": "reg_set_min_max_inv",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5455",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580824672,
      "name": "reg_set_min_max_inv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 999
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
  "name": "reg_set_min_max_inv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580997114,
      "name": "reg_set_min_max_inv",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6593",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
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
  "name": "reg_set_min_max_inv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580991201,
      "name": "reg_set_min_max_inv",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7261",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
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
  "name": "reg_set_min_max_inv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580998148,
      "name": "reg_set_min_max_inv",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8424",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
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
  "name": "reg_set_min_max_inv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581211998,
      "name": "reg_set_min_max_inv",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8717",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
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
  "name": "reg_set_min_max_inv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581496102,
      "name": "reg_set_min_max_inv",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9712",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
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
  "name": "reg_set_min_max_inv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581868767,
      "name": "reg_set_min_max_inv",
      "external": false,
      "loc": "kernel/bpf/verifier.c:11635",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
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
  "name": "reg_set_min_max_inv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582055409,
      "name": "reg_set_min_max_inv",
      "external": false,
      "loc": "kernel/bpf/verifier.c:13566",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
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
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "reg_set_min_max_inv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492181568,
      "name": "reg_set_min_max_inv",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5455",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void reg_set_min_max_inv(struct bpf_reg_state * true_reg, struct bpf_reg_state * false_reg, u64 val, u8 opcode, bool is_jmp32)
```

```json
{
  "name": "reg_set_min_max_inv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226045768,
      "name": "reg_set_min_max_inv",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5455",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226045768,
      "name": "reg_set_min_max_inv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1188
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
void reg_set_min_max_inv(struct bpf_reg_state * true_reg, struct bpf_reg_state * false_reg, u64 val, u8 opcode, bool is_jmp32)
```

```json
{
  "name": "reg_set_min_max_inv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285355856,
      "name": "reg_set_min_max_inv",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5455",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285355856,
      "name": "reg_set_min_max_inv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1248
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
void reg_set_min_max_inv(struct bpf_reg_state * true_reg, struct bpf_reg_state * false_reg, u64 val, u8 opcode, bool is_jmp32)
```

```json
{
  "name": "reg_set_min_max_inv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272308940,
      "name": "reg_set_min_max_inv",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5455",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272308940,
      "name": "reg_set_min_max_inv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 844
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
void reg_set_min_max_inv(struct bpf_reg_state * true_reg, struct bpf_reg_state * false_reg, u64 val, u8 opcode, bool is_jmp32)
```

```json
{
  "name": "reg_set_min_max_inv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580793472,
      "name": "reg_set_min_max_inv",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5455",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580793472,
      "name": "reg_set_min_max_inv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 999
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
void reg_set_min_max_inv(struct bpf_reg_state * true_reg, struct bpf_reg_state * false_reg, u64 val, u8 opcode, bool is_jmp32)
```

```json
{
  "name": "reg_set_min_max_inv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580739648,
      "name": "reg_set_min_max_inv",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5455",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580739648,
      "name": "reg_set_min_max_inv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 999
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
void reg_set_min_max_inv(struct bpf_reg_state * true_reg, struct bpf_reg_state * false_reg, u64 val, u8 opcode, bool is_jmp32)
```

```json
{
  "name": "reg_set_min_max_inv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580784720,
      "name": "reg_set_min_max_inv",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5455",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580784720,
      "name": "reg_set_min_max_inv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 999
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
void reg_set_min_max_inv(struct bpf_reg_state * true_reg, struct bpf_reg_state * false_reg, u64 val, u8 opcode, bool is_jmp32)
```

```json
{
  "name": "reg_set_min_max_inv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580843104,
      "name": "reg_set_min_max_inv",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5455",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580843104,
      "name": "reg_set_min_max_inv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 999
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
void reg_set_min_max_inv(struct bpf_reg_state * true_reg, struct bpf_reg_state * false_reg, u64 val, u8 opcode, bool is_jmp32)
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
void reg_set_min_max_inv(struct bpf_reg_state * true_reg, struct bpf_reg_state * false_reg, u64 val, u8 opcode, bool is_jmp32)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void reg_set_min_max_inv(struct bpf_reg_state * true_reg, struct bpf_reg_state * false_reg, u64 val, u8 opcode, bool is_jmp32)
```
</details>
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
