# Function: <code>reg_set_min_max</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void reg_set_min_max(struct bpf_reg_state * true_reg, struct bpf_reg_state * false_reg, u64 val, u8 opcode)
```

```json
{
  "name": "reg_set_min_max",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580474992,
      "name": "reg_set_min_max",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1877",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580474992,
      "name": "reg_set_min_max",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void reg_set_min_max(struct bpf_reg_state * true_reg, struct bpf_reg_state * false_reg, u64 val, u8 opcode)
```

```json
{
  "name": "reg_set_min_max",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580500672,
      "name": "reg_set_min_max",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2228",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580500672,
      "name": "reg_set_min_max",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 553
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reg_set_min_max",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580569928,
      "name": "reg_set_min_max",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2641",
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
      "addr": 18446744071580567408,
      "name": "reg_set_min_max.part.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 738
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reg_set_min_max",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580662579,
      "name": "reg_set_min_max",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3432",
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
      "addr": 18446744071580643936,
      "name": "reg_set_min_max.part.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 745
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reg_set_min_max",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580728701,
      "name": "reg_set_min_max",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4115",
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
      "addr": 18446744071580706272,
      "name": "reg_set_min_max.part.44",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 793
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reg_set_min_max",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580805646,
      "name": "reg_set_min_max",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5323",
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
      "addr": 18446744071580778880,
      "name": "reg_set_min_max.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 976
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
  "name": "reg_set_min_max",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580856782,
      "name": "reg_set_min_max",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5333",
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
      "addr": 18446744071580829808,
      "name": "reg_set_min_max.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 976
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
void reg_set_min_max(struct bpf_reg_state * true_reg, struct bpf_reg_state * false_reg, u64 val, u32 val32, u8 opcode, bool is_jmp32)
```

```json
{
  "name": "reg_set_min_max",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580959488,
      "name": "reg_set_min_max",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6444",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071580959488,
      "name": "reg_set_min_max",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1437
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
void reg_set_min_max(struct bpf_reg_state * true_reg, struct bpf_reg_state * false_reg, u64 val, u32 val32, u8 opcode, bool is_jmp32)
```

```json
{
  "name": "reg_set_min_max",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580959376,
      "name": "reg_set_min_max",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7108",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071580959376,
      "name": "reg_set_min_max",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1477
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
void reg_set_min_max(struct bpf_reg_state * true_reg, struct bpf_reg_state * false_reg, u64 val, u32 val32, u8 opcode, bool is_jmp32)
```

```json
{
  "name": "reg_set_min_max",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580963424,
      "name": "reg_set_min_max",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8271",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071580963424,
      "name": "reg_set_min_max",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1398
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
void reg_set_min_max(struct bpf_reg_state * true_reg, struct bpf_reg_state * false_reg, u64 val, u32 val32, u8 opcode, bool is_jmp32)
```

```json
{
  "name": "reg_set_min_max",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581171088,
      "name": "reg_set_min_max",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8564",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071581171088,
      "name": "reg_set_min_max",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1398
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
void reg_set_min_max(struct bpf_reg_state * true_reg, struct bpf_reg_state * false_reg, u64 val, u32 val32, u8 opcode, bool is_jmp32)
```

```json
{
  "name": "reg_set_min_max",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581450416,
      "name": "reg_set_min_max",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9552",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071581450416,
      "name": "reg_set_min_max",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1690
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
void reg_set_min_max(struct bpf_reg_state * true_reg, struct bpf_reg_state * false_reg, u64 val, u32 val32, u8 opcode, bool is_jmp32)
```

```json
{
  "name": "reg_set_min_max",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581804240,
      "name": "reg_set_min_max",
      "external": false,
      "loc": "kernel/bpf/verifier.c:11475",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071581804240,
      "name": "reg_set_min_max",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1690
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
void reg_set_min_max(struct bpf_reg_state * true_reg, struct bpf_reg_state * false_reg, u64 val, u32 val32, u8 opcode, bool is_jmp32)
```

```json
{
  "name": "reg_set_min_max",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582022544,
      "name": "reg_set_min_max",
      "external": false,
      "loc": "kernel/bpf/verifier.c:13406",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071582022544,
      "name": "reg_set_min_max",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1640
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int reg_set_min_max(struct bpf_verifier_env * env, struct bpf_reg_state * true_reg1, struct bpf_reg_state * true_reg2, struct bpf_reg_state * false_reg1, struct bpf_reg_state * false_reg2, u8 opcode, bool is_jmp32)
```

```json
{
  "name": "reg_set_min_max",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582187600,
      "name": "reg_set_min_max",
      "external": false,
      "loc": "kernel/bpf/verifier.c:14577",
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
      "addr": 18446744071582187600,
      "name": "reg_set_min_max",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
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
  "name": "reg_set_min_max",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492181508,
      "name": "reg_set_min_max",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5333",
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
      "addr": 18446603336492154128,
      "name": "reg_set_min_max.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 912
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
  "name": "reg_set_min_max",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226079020,
      "name": "reg_set_min_max",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5333",
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
      "addr": 3226049888,
      "name": "reg_set_min_max.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1180
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
  "name": "reg_set_min_max",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285396484,
      "name": "reg_set_min_max",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5333",
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
      "addr": 13835058055285364560,
      "name": "reg_set_min_max.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1196
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
  "name": "reg_set_min_max",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272336660,
      "name": "reg_set_min_max",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5333",
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
      "addr": 18446743936272314566,
      "name": "reg_set_min_max.part.0",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reg_set_min_max",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580825582,
      "name": "reg_set_min_max",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5333",
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
      "addr": 18446744071580798608,
      "name": "reg_set_min_max.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 976
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
  "name": "reg_set_min_max",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580771758,
      "name": "reg_set_min_max",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5333",
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
      "addr": 18446744071580744784,
      "name": "reg_set_min_max.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 976
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
  "name": "reg_set_min_max",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580816830,
      "name": "reg_set_min_max",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5333",
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
      "addr": 18446744071580789856,
      "name": "reg_set_min_max.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 976
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
  "name": "reg_set_min_max",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580875214,
      "name": "reg_set_min_max",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5333",
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
      "addr": 18446744071580848240,
      "name": "reg_set_min_max.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 976
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void reg_set_min_max(struct bpf_reg_state * true_reg, struct bpf_reg_state * false_reg, u64 val, u8 opcode)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void reg_set_min_max(struct bpf_reg_state * true_reg, struct bpf_reg_state * false_reg, u64 val, u8 opcode)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void reg_set_min_max(struct bpf_reg_state * true_reg, struct bpf_reg_state * false_reg, u64 val, u32 val32, u8 opcode, bool is_jmp32)
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
<code>struct bpf_verifier_env * env</code>
</li>
<li>
<b>Param added. </b>
<code>struct bpf_reg_state * true_reg1</code>
</li>
<li>
<b>Param added. </b>
<code>struct bpf_reg_state * true_reg2</code>
</li>
<li>
<b>Param added. </b>
<code>struct bpf_reg_state * false_reg1</code>
</li>
<li>
<b>Param added. </b>
<code>struct bpf_reg_state * false_reg2</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_reg_state * true_reg</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_reg_state * false_reg</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 val</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 val32</code>
</li>
<li>
<b>Param reordered. </b>
<code>true_reg, false_reg, val, val32, opcode, is_jmp32</code> ➡️ <code>env, true_reg1, true_reg2, false_reg1, false_reg2, opcode, is_jmp32</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
</ul>
