# Function: <code>try_match_pkt_pointers</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "try_match_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580569249,
      "name": "try_match_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2887",
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
  "name": "try_match_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580661970,
      "name": "try_match_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3682",
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
  "name": "try_match_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580727795,
      "name": "try_match_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4387",
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
  "name": "try_match_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580776496,
      "name": "try_match_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5690",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580776496,
      "name": "try_match_pkt_pointers.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
  "name": "try_match_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580827424,
      "name": "try_match_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5700",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580827424,
      "name": "try_match_pkt_pointers.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
  "name": "try_match_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580962432,
      "name": "try_match_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6769",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580962432,
      "name": "try_match_pkt_pointers.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
bool try_match_pkt_pointers(const struct bpf_insn * insn, struct bpf_reg_state * dst_reg, struct bpf_reg_state * src_reg, struct bpf_verifier_state * this_branch, struct bpf_verifier_state * other_branch)
```

```json
{
  "name": "try_match_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580962384,
      "name": "try_match_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7426",
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
      "addr": 18446744071580962384,
      "name": "try_match_pkt_pointers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1131
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
bool try_match_pkt_pointers(const struct bpf_insn * insn, struct bpf_reg_state * dst_reg, struct bpf_reg_state * src_reg, struct bpf_verifier_state * this_branch, struct bpf_verifier_state * other_branch)
```

```json
{
  "name": "try_match_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580964832,
      "name": "try_match_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8565",
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
      "addr": 18446744071580964832,
      "name": "try_match_pkt_pointers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1131
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
bool try_match_pkt_pointers(const struct bpf_insn * insn, struct bpf_reg_state * dst_reg, struct bpf_reg_state * src_reg, struct bpf_verifier_state * this_branch, struct bpf_verifier_state * other_branch)
```

```json
{
  "name": "try_match_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581172496,
      "name": "try_match_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8858",
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
      "addr": 18446744071581172496,
      "name": "try_match_pkt_pointers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1846
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
bool try_match_pkt_pointers(const struct bpf_insn * insn, struct bpf_reg_state * dst_reg, struct bpf_reg_state * src_reg, struct bpf_verifier_state * this_branch, struct bpf_verifier_state * other_branch)
```

```json
{
  "name": "try_match_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581452112,
      "name": "try_match_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9840",
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
      "addr": 18446744071581452112,
      "name": "try_match_pkt_pointers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1863
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
bool try_match_pkt_pointers(const struct bpf_insn * insn, struct bpf_reg_state * dst_reg, struct bpf_reg_state * src_reg, struct bpf_verifier_state * this_branch, struct bpf_verifier_state * other_branch)
```

```json
{
  "name": "try_match_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581805952,
      "name": "try_match_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:11750",
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
      "addr": 18446744071581805952,
      "name": "try_match_pkt_pointers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1863
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
bool try_match_pkt_pointers(const struct bpf_insn * insn, struct bpf_reg_state * dst_reg, struct bpf_reg_state * src_reg, struct bpf_verifier_state * this_branch, struct bpf_verifier_state * other_branch)
```

```json
{
  "name": "try_match_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582035152,
      "name": "try_match_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:13683",
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
      "addr": 18446744071582035152,
      "name": "try_match_pkt_pointers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1844
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
bool try_match_pkt_pointers(const struct bpf_insn * insn, struct bpf_reg_state * dst_reg, struct bpf_reg_state * src_reg, struct bpf_verifier_state * this_branch, struct bpf_verifier_state * other_branch)
```

```json
{
  "name": "try_match_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582181376,
      "name": "try_match_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:14680",
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
      "addr": 18446744071582181376,
      "name": "try_match_pkt_pointers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1844
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
  "name": "try_match_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492150752,
      "name": "try_match_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5700",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492150752,
      "name": "try_match_pkt_pointers.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 840
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
bool try_match_pkt_pointers(const struct bpf_insn * insn, struct bpf_reg_state * dst_reg, struct bpf_reg_state * src_reg, struct bpf_verifier_state * this_branch, struct bpf_verifier_state * other_branch)
```

```json
{
  "name": "try_match_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226043380,
      "name": "try_match_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5700",
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
      "addr": 3226043380,
      "name": "try_match_pkt_pointers",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "try_match_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285360016,
      "name": "try_match_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5700",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285360016,
      "name": "try_match_pkt_pointers.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 984
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
  "name": "try_match_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272311440,
      "name": "try_match_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5700",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272311440,
      "name": "try_match_pkt_pointers.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
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
  "name": "try_match_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580796224,
      "name": "try_match_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5700",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580796224,
      "name": "try_match_pkt_pointers.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
  "name": "try_match_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580742400,
      "name": "try_match_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5700",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580742400,
      "name": "try_match_pkt_pointers.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
  "name": "try_match_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580787472,
      "name": "try_match_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5700",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580787472,
      "name": "try_match_pkt_pointers.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
  "name": "try_match_pkt_pointers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580845856,
      "name": "try_match_pkt_pointers",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5700",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580845856,
      "name": "try_match_pkt_pointers.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
bool try_match_pkt_pointers(const struct bpf_insn * insn, struct bpf_reg_state * dst_reg, struct bpf_reg_state * src_reg, struct bpf_verifier_state * this_branch, struct bpf_verifier_state * other_branch)
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
bool try_match_pkt_pointers(const struct bpf_insn * insn, struct bpf_reg_state * dst_reg, struct bpf_reg_state * src_reg, struct bpf_verifier_state * this_branch, struct bpf_verifier_state * other_branch)
```
</details>
</li>
</ul>
