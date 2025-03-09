# Function: <code>backtrack_insn</code>

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
int backtrack_insn(struct bpf_verifier_env * env, int idx, u32 * reg_mask, u64 * stack_mask)
```

```json
{
  "name": "backtrack_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580787120,
      "name": "backtrack_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1442",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580787120,
      "name": "backtrack_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 867
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
  "name": "backtrack_insn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580839844,
      "name": "backtrack_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1443",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:__mark_chain_precision"
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
int backtrack_insn(struct bpf_verifier_env * env, int idx, u32 * reg_mask, u64 * stack_mask)
```

```json
{
  "name": "backtrack_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580970880,
      "name": "backtrack_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1752",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580970880,
      "name": "backtrack_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 864
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
int backtrack_insn(struct bpf_verifier_env * env, int idx, u32 * reg_mask, u64 * stack_mask)
```

```json
{
  "name": "backtrack_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580970336,
      "name": "backtrack_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1804",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580970336,
      "name": "backtrack_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 864
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
int backtrack_insn(struct bpf_verifier_env * env, int idx, u32 * reg_mask, u64 * stack_mask)
```

```json
{
  "name": "backtrack_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580977488,
      "name": "backtrack_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2106",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580977488,
      "name": "backtrack_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 875
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int backtrack_insn(struct bpf_verifier_env * env, int idx, u32 * reg_mask, u64 * stack_mask)
```

```json
{
  "name": "backtrack_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "backtrack_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2174",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581189008,
      "name": "backtrack_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 947
    },
    {
      "addr": 18446744071592181562,
      "name": "backtrack_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int backtrack_insn(struct bpf_verifier_env * env, int idx, u32 * reg_mask, u64 * stack_mask)
```

```json
{
  "name": "backtrack_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "backtrack_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2524",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581461392,
      "name": "backtrack_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 896
    },
    {
      "addr": 18446744071593955457,
      "name": "backtrack_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int backtrack_insn(struct bpf_verifier_env * env, int idx, u32 * reg_mask, u64 * stack_mask)
```

```json
{
  "name": "backtrack_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "backtrack_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2780",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581811040,
      "name": "backtrack_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 964
    },
    {
      "addr": 18446744071596014678,
      "name": "backtrack_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int backtrack_insn(struct bpf_verifier_env * env, int idx, int subseq_idx, struct backtrack_state * bt)
```

```json
{
  "name": "backtrack_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "backtrack_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3390",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582037024,
      "name": "backtrack_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4067
    },
    {
      "addr": 18446744071596537916,
      "name": "backtrack_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int backtrack_insn(struct bpf_verifier_env * env, int idx, int subseq_idx, struct bpf_jmp_history_entry * hist, struct backtrack_state * bt)
```

```json
{
  "name": "backtrack_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "backtrack_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3544",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582152400,
      "name": "backtrack_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4269
    },
    {
      "addr": 18446744071597438967,
      "name": "backtrack_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int backtrack_insn(struct bpf_verifier_env * env, int idx, u32 * reg_mask, u64 * stack_mask)
```

```json
{
  "name": "backtrack_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492163456,
      "name": "backtrack_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1443",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492163456,
      "name": "backtrack_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 996
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
  "name": "backtrack_insn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226061104,
      "name": "backtrack_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1443",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:__mark_chain_precision"
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
  "name": "backtrack_insn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285376620,
      "name": "backtrack_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1443",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:__mark_chain_precision"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int backtrack_insn(struct bpf_verifier_env * env, int idx, u32 * reg_mask, u64 * stack_mask)
```

```json
{
  "name": "backtrack_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272321008,
      "name": "backtrack_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1443",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272321008,
      "name": "backtrack_insn",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "backtrack_insn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580808644,
      "name": "backtrack_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1443",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:__mark_chain_precision"
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
  "name": "backtrack_insn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580754820,
      "name": "backtrack_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1443",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:__mark_chain_precision"
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
  "name": "backtrack_insn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580799892,
      "name": "backtrack_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1443",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:__mark_chain_precision"
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
  "name": "backtrack_insn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580858276,
      "name": "backtrack_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1443",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:__mark_chain_precision"
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int backtrack_insn(struct bpf_verifier_env * env, int idx, u32 * reg_mask, u64 * stack_mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
int backtrack_insn(struct bpf_verifier_env * env, int idx, u32 * reg_mask, u64 * stack_mask)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int backtrack_insn(struct bpf_verifier_env * env, int idx, u32 * reg_mask, u64 * stack_mask)
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int subseq_idx</code>
</li>
<li>
<b>Param added. </b>
<code>struct backtrack_state * bt</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 * reg_mask</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 * stack_mask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_jmp_history_entry * hist</code>
</li>
<li>
<b>Param reordered. </b>
<code>env, idx, subseq_idx, bt</code> ➡️ <code>env, idx, subseq_idx, hist, bt</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int backtrack_insn(struct bpf_verifier_env * env, int idx, u32 * reg_mask, u64 * stack_mask)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int backtrack_insn(struct bpf_verifier_env * env, int idx, u32 * reg_mask, u64 * stack_mask)
```
</details>
</li>
</ul>
