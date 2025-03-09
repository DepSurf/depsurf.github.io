# Function: <code>is_branch_taken</code>

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
  "name": "is_branch_taken",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580727589,
      "name": "is_branch_taken",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4037",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_branch_taken",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580804170,
      "name": "is_branch_taken",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5183",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580778192,
      "name": "is_branch_taken.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 683
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_branch_taken",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580855306,
      "name": "is_branch_taken",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5193",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580829120,
      "name": "is_branch_taken.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 683
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int is_branch_taken(struct bpf_reg_state * reg, u64 val, u8 opcode, bool is_jmp32)
```

```json
{
  "name": "is_branch_taken",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580954704,
      "name": "is_branch_taken",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6411",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580954704,
      "name": "is_branch_taken",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int is_branch_taken(struct bpf_reg_state * reg, u64 val, u8 opcode, bool is_jmp32)
```

```json
{
  "name": "is_branch_taken",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580954352,
      "name": "is_branch_taken",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7014",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580954352,
      "name": "is_branch_taken",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int is_branch_taken(struct bpf_reg_state * reg, u64 val, u8 opcode, bool is_jmp32)
```

```json
{
  "name": "is_branch_taken",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580957328,
      "name": "is_branch_taken",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8177",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580957328,
      "name": "is_branch_taken",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int is_branch_taken(struct bpf_reg_state * reg, u64 val, u8 opcode, bool is_jmp32)
```

```json
{
  "name": "is_branch_taken",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581163168,
      "name": "is_branch_taken",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8470",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581163168,
      "name": "is_branch_taken",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
int is_branch_taken(struct bpf_reg_state * reg, u64 val, u8 opcode, bool is_jmp32)
```

```json
{
  "name": "is_branch_taken",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581441568,
      "name": "is_branch_taken",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9458",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581441568,
      "name": "is_branch_taken",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
int is_branch_taken(struct bpf_reg_state * reg, u64 val, u8 opcode, bool is_jmp32)
```

```json
{
  "name": "is_branch_taken",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581795824,
      "name": "is_branch_taken",
      "external": false,
      "loc": "kernel/bpf/verifier.c:11381",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581795824,
      "name": "is_branch_taken",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
int is_branch_taken(struct bpf_reg_state * reg, u64 val, u8 opcode, bool is_jmp32)
```

```json
{
  "name": "is_branch_taken",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581986720,
      "name": "is_branch_taken",
      "external": false,
      "loc": "kernel/bpf/verifier.c:13312",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581986720,
      "name": "is_branch_taken",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
int is_branch_taken(struct bpf_reg_state * reg1, struct bpf_reg_state * reg2, u8 opcode, bool is_jmp32)
```

```json
{
  "name": "is_branch_taken",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582185120,
      "name": "is_branch_taken",
      "external": false,
      "loc": "kernel/bpf/verifier.c:14341",
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
      "addr": 18446744071582185120,
      "name": "is_branch_taken",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 671
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
  "name": "is_branch_taken",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492180272,
      "name": "is_branch_taken",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5193",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492153456,
      "name": "is_branch_taken.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "is_branch_taken",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226078012,
      "name": "is_branch_taken",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5193",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226049116,
      "name": "is_branch_taken.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 772
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "is_branch_taken",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285395280,
      "name": "is_branch_taken",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5193",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285363696,
      "name": "is_branch_taken.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 860
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "is_branch_taken",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272335744,
      "name": "is_branch_taken",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5193",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272314016,
      "name": "is_branch_taken.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_branch_taken",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580824106,
      "name": "is_branch_taken",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5193",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580797920,
      "name": "is_branch_taken.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 683
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_branch_taken",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580770282,
      "name": "is_branch_taken",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5193",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580744096,
      "name": "is_branch_taken.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 683
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_branch_taken",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580815354,
      "name": "is_branch_taken",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5193",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580789168,
      "name": "is_branch_taken.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 683
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_branch_taken",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580873738,
      "name": "is_branch_taken",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5193",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580847552,
      "name": "is_branch_taken.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 683
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int is_branch_taken(struct bpf_reg_state * reg, u64 val, u8 opcode, bool is_jmp32)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_reg_state * reg1</code>
</li>
<li>
<b>Param added. </b>
<code>struct bpf_reg_state * reg2</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_reg_state * reg</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 val</code>
</li>
</ul>
</details>
</li>
</ul>
