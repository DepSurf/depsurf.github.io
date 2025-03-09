# Function: <code>bpf_adj_branches</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_adj_branches",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580412599,
      "name": "bpf_adj_branches",
      "external": false,
      "loc": "kernel/bpf/core.c:149",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_patch_insn_single"
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
  "name": "bpf_adj_branches",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580461351,
      "name": "bpf_adj_branches",
      "external": false,
      "loc": "kernel/bpf/core.c:231",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_patch_insn_single"
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
  "name": "bpf_adj_branches",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580479575,
      "name": "bpf_adj_branches",
      "external": false,
      "loc": "kernel/bpf/core.c:234",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_patch_insn_single"
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
  "name": "bpf_adj_branches",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580538055,
      "name": "bpf_adj_branches",
      "external": false,
      "loc": "kernel/bpf/core.c:230",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_patch_insn_single"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int bpf_adj_branches(struct bpf_prog * prog, u32 pos, u32 delta, const bool probe_pass)
```

```json
{
  "name": "bpf_adj_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580615552,
      "name": "bpf_adj_branches",
      "external": false,
      "loc": "kernel/bpf/core.c:256",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580615552,
      "name": "bpf_adj_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int bpf_adj_branches(struct bpf_prog * prog, u32 pos, u32 delta, const bool probe_pass)
```

```json
{
  "name": "bpf_adj_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580674464,
      "name": "bpf_adj_branches",
      "external": false,
      "loc": "kernel/bpf/core.c:344",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580674464,
      "name": "bpf_adj_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
int bpf_adj_branches(struct bpf_prog * prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass)
```

```json
{
  "name": "bpf_adj_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580738880,
      "name": "bpf_adj_branches",
      "external": false,
      "loc": "kernel/bpf/core.c:372",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580738880,
      "name": "bpf_adj_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
int bpf_adj_branches(struct bpf_prog * prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass)
```

```json
{
  "name": "bpf_adj_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580789600,
      "name": "bpf_adj_branches",
      "external": false,
      "loc": "kernel/bpf/core.c:372",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580789600,
      "name": "bpf_adj_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
int bpf_adj_branches(struct bpf_prog * prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass)
```

```json
{
  "name": "bpf_adj_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580907008,
      "name": "bpf_adj_branches",
      "external": false,
      "loc": "kernel/bpf/core.c:372",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580907008,
      "name": "bpf_adj_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
int bpf_adj_branches(struct bpf_prog * prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass)
```

```json
{
  "name": "bpf_adj_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580901728,
      "name": "bpf_adj_branches",
      "external": false,
      "loc": "kernel/bpf/core.c:368",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580901728,
      "name": "bpf_adj_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
int bpf_adj_branches(struct bpf_prog * prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass)
```

```json
{
  "name": "bpf_adj_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580905552,
      "name": "bpf_adj_branches",
      "external": false,
      "loc": "kernel/bpf/core.c:374",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580905552,
      "name": "bpf_adj_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 398
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
int bpf_adj_branches(struct bpf_prog * prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass)
```

```json
{
  "name": "bpf_adj_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581107744,
      "name": "bpf_adj_branches",
      "external": false,
      "loc": "kernel/bpf/core.c:374",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581107744,
      "name": "bpf_adj_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 398
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
int bpf_adj_branches(struct bpf_prog * prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass)
```

```json
{
  "name": "bpf_adj_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581384352,
      "name": "bpf_adj_branches",
      "external": false,
      "loc": "kernel/bpf/core.c:379",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581384352,
      "name": "bpf_adj_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
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
int bpf_adj_branches(struct bpf_prog * prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass)
```

```json
{
  "name": "bpf_adj_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581733008,
      "name": "bpf_adj_branches",
      "external": false,
      "loc": "kernel/bpf/core.c:387",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581733008,
      "name": "bpf_adj_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
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
int bpf_adj_branches(struct bpf_prog * prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass)
```

```json
{
  "name": "bpf_adj_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581892160,
      "name": "bpf_adj_branches",
      "external": false,
      "loc": "kernel/bpf/core.c:388",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581892160,
      "name": "bpf_adj_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
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
int bpf_adj_branches(struct bpf_prog * prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass)
```

```json
{
  "name": "bpf_adj_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582015872,
      "name": "bpf_adj_branches",
      "external": false,
      "loc": "kernel/bpf/core.c:405",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582015872,
      "name": "bpf_adj_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
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
int bpf_adj_branches(struct bpf_prog * prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass)
```

```json
{
  "name": "bpf_adj_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492103280,
      "name": "bpf_adj_branches",
      "external": false,
      "loc": "kernel/bpf/core.c:372",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492103280,
      "name": "bpf_adj_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
int bpf_adj_branches(struct bpf_prog * prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass)
```

```json
{
  "name": "bpf_adj_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226003404,
      "name": "bpf_adj_branches",
      "external": false,
      "loc": "kernel/bpf/core.c:372",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226003404,
      "name": "bpf_adj_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
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
int bpf_adj_branches(struct bpf_prog * prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass)
```

```json
{
  "name": "bpf_adj_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285305360,
      "name": "bpf_adj_branches",
      "external": false,
      "loc": "kernel/bpf/core.c:372",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285305360,
      "name": "bpf_adj_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
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
int bpf_adj_branches(struct bpf_prog * prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass)
```

```json
{
  "name": "bpf_adj_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272278476,
      "name": "bpf_adj_branches",
      "external": false,
      "loc": "kernel/bpf/core.c:372",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272278476,
      "name": "bpf_adj_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int bpf_adj_branches(struct bpf_prog * prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass)
```

```json
{
  "name": "bpf_adj_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580758400,
      "name": "bpf_adj_branches",
      "external": false,
      "loc": "kernel/bpf/core.c:372",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580758400,
      "name": "bpf_adj_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
int bpf_adj_branches(struct bpf_prog * prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass)
```

```json
{
  "name": "bpf_adj_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580704576,
      "name": "bpf_adj_branches",
      "external": false,
      "loc": "kernel/bpf/core.c:372",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580704576,
      "name": "bpf_adj_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
int bpf_adj_branches(struct bpf_prog * prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass)
```

```json
{
  "name": "bpf_adj_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580749648,
      "name": "bpf_adj_branches",
      "external": false,
      "loc": "kernel/bpf/core.c:372",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580749648,
      "name": "bpf_adj_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
int bpf_adj_branches(struct bpf_prog * prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass)
```

```json
{
  "name": "bpf_adj_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580807744,
      "name": "bpf_adj_branches",
      "external": false,
      "loc": "kernel/bpf/core.c:372",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_remove_insns",
        "kernel/bpf/core.c:bpf_patch_insn_single",
        "kernel/bpf/core.c:bpf_patch_insn_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580807744,
      "name": "bpf_adj_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int bpf_adj_branches(struct bpf_prog * prog, u32 pos, u32 delta, const bool probe_pass)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>s32 end_old</code>
</li>
<li>
<b>Param added. </b>
<code>s32 end_new</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 delta</code>
</li>
<li>
<b>Param reordered. </b>
<code>prog, pos, delta, probe_pass</code> ➡️ <code>prog, pos, end_old, end_new, probe_pass</code>
</li>
</ul>
</details>
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
