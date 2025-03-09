# Function: <code>sanitize_ptr_alu</code>

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
int sanitize_ptr_alu(struct bpf_verifier_env * env, struct bpf_insn * insn, const struct bpf_reg_state * ptr_reg, struct bpf_reg_state * dst_reg, bool off_is_neg)
```

```json
{
  "name": "sanitize_ptr_alu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580711232,
      "name": "sanitize_ptr_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3143",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580711232,
      "name": "sanitize_ptr_alu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 571
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
int sanitize_ptr_alu(struct bpf_verifier_env * env, struct bpf_insn * insn, const struct bpf_reg_state * ptr_reg, struct bpf_reg_state * dst_reg, bool off_is_neg)
```

```json
{
  "name": "sanitize_ptr_alu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580790832,
      "name": "sanitize_ptr_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4266",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580790832,
      "name": "sanitize_ptr_alu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
int sanitize_ptr_alu(struct bpf_verifier_env * env, struct bpf_insn * insn, const struct bpf_reg_state * ptr_reg, struct bpf_reg_state * dst_reg, bool off_is_neg)
```

```json
{
  "name": "sanitize_ptr_alu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580841856,
      "name": "sanitize_ptr_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4269",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580841856,
      "name": "sanitize_ptr_alu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
  "name": "sanitize_ptr_alu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580972176,
      "name": "sanitize_ptr_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4946",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580972176,
      "name": "sanitize_ptr_alu.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 667
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
  "name": "sanitize_ptr_alu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580974416,
      "name": "sanitize_ptr_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5457",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580974416,
      "name": "sanitize_ptr_alu.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 716
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
  "name": "sanitize_ptr_alu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580980528,
      "name": "sanitize_ptr_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6489",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580980528,
      "name": "sanitize_ptr_alu.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 901
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
int sanitize_ptr_alu(struct bpf_verifier_env * env, struct bpf_insn * insn, const struct bpf_reg_state * ptr_reg, const struct bpf_reg_state * off_reg, struct bpf_reg_state * dst_reg, struct bpf_sanitize_info * info, const bool commit_window)
```

```json
{
  "name": "sanitize_ptr_alu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sanitize_ptr_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6778",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581192688,
      "name": "sanitize_ptr_alu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1009
    },
    {
      "addr": 18446744071592182237,
      "name": "sanitize_ptr_alu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int sanitize_ptr_alu(struct bpf_verifier_env * env, struct bpf_insn * insn, const struct bpf_reg_state * ptr_reg, const struct bpf_reg_state * off_reg, struct bpf_reg_state * dst_reg, struct bpf_sanitize_info * info, const bool commit_window)
```

```json
{
  "name": "sanitize_ptr_alu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sanitize_ptr_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7777",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581476256,
      "name": "sanitize_ptr_alu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1059
    },
    {
      "addr": 18446744071593956348,
      "name": "sanitize_ptr_alu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
int sanitize_ptr_alu(struct bpf_verifier_env * env, struct bpf_insn * insn, const struct bpf_reg_state * ptr_reg, const struct bpf_reg_state * off_reg, struct bpf_reg_state * dst_reg, struct bpf_sanitize_info * info, const bool commit_window)
```

```json
{
  "name": "sanitize_ptr_alu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sanitize_ptr_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9713",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581835456,
      "name": "sanitize_ptr_alu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1062
    },
    {
      "addr": 18446744071596016124,
      "name": "sanitize_ptr_alu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
int sanitize_ptr_alu(struct bpf_verifier_env * env, struct bpf_insn * insn, const struct bpf_reg_state * ptr_reg, const struct bpf_reg_state * off_reg, struct bpf_reg_state * dst_reg, struct bpf_sanitize_info * info, const bool commit_window)
```

```json
{
  "name": "sanitize_ptr_alu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sanitize_ptr_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:11629",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582002192,
      "name": "sanitize_ptr_alu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1058
    },
    {
      "addr": 18446744071596536377,
      "name": "sanitize_ptr_alu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
int sanitize_ptr_alu(struct bpf_verifier_env * env, struct bpf_insn * insn, const struct bpf_reg_state * ptr_reg, const struct bpf_reg_state * off_reg, struct bpf_reg_state * dst_reg, struct bpf_sanitize_info * info, const bool commit_window)
```

```json
{
  "name": "sanitize_ptr_alu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sanitize_ptr_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:12563",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582125232,
      "name": "sanitize_ptr_alu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1058
    },
    {
      "addr": 18446744071597437402,
      "name": "sanitize_ptr_alu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
  "name": "sanitize_ptr_alu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492167512,
      "name": "sanitize_ptr_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4269",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492167512,
      "name": "sanitize_ptr_alu.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
int sanitize_ptr_alu(struct bpf_verifier_env * env, struct bpf_insn * insn, const struct bpf_reg_state * ptr_reg, struct bpf_reg_state * dst_reg, bool off_is_neg)
```

```json
{
  "name": "sanitize_ptr_alu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226063444,
      "name": "sanitize_ptr_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4269",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226063444,
      "name": "sanitize_ptr_alu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
  "name": "sanitize_ptr_alu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285379312,
      "name": "sanitize_ptr_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4269",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285379312,
      "name": "sanitize_ptr_alu.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
  "name": "sanitize_ptr_alu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272324592,
      "name": "sanitize_ptr_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4269",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272324592,
      "name": "sanitize_ptr_alu.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
int sanitize_ptr_alu(struct bpf_verifier_env * env, struct bpf_insn * insn, const struct bpf_reg_state * ptr_reg, struct bpf_reg_state * dst_reg, bool off_is_neg)
```

```json
{
  "name": "sanitize_ptr_alu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580810656,
      "name": "sanitize_ptr_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4269",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580810656,
      "name": "sanitize_ptr_alu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
int sanitize_ptr_alu(struct bpf_verifier_env * env, struct bpf_insn * insn, const struct bpf_reg_state * ptr_reg, struct bpf_reg_state * dst_reg, bool off_is_neg)
```

```json
{
  "name": "sanitize_ptr_alu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580756832,
      "name": "sanitize_ptr_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4269",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580756832,
      "name": "sanitize_ptr_alu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
int sanitize_ptr_alu(struct bpf_verifier_env * env, struct bpf_insn * insn, const struct bpf_reg_state * ptr_reg, struct bpf_reg_state * dst_reg, bool off_is_neg)
```

```json
{
  "name": "sanitize_ptr_alu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580801904,
      "name": "sanitize_ptr_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4269",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580801904,
      "name": "sanitize_ptr_alu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
int sanitize_ptr_alu(struct bpf_verifier_env * env, struct bpf_insn * insn, const struct bpf_reg_state * ptr_reg, struct bpf_reg_state * dst_reg, bool off_is_neg)
```

```json
{
  "name": "sanitize_ptr_alu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580860288,
      "name": "sanitize_ptr_alu",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4269",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580860288,
      "name": "sanitize_ptr_alu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
int sanitize_ptr_alu(struct bpf_verifier_env * env, struct bpf_insn * insn, const struct bpf_reg_state * ptr_reg, struct bpf_reg_state * dst_reg, bool off_is_neg)
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
int sanitize_ptr_alu(struct bpf_verifier_env * env, struct bpf_insn * insn, const struct bpf_reg_state * ptr_reg, struct bpf_reg_state * dst_reg, bool off_is_neg)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int sanitize_ptr_alu(struct bpf_verifier_env * env, struct bpf_insn * insn, const struct bpf_reg_state * ptr_reg, const struct bpf_reg_state * off_reg, struct bpf_reg_state * dst_reg, struct bpf_sanitize_info * info, const bool commit_window)
```
</details>
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int sanitize_ptr_alu(struct bpf_verifier_env * env, struct bpf_insn * insn, const struct bpf_reg_state * ptr_reg, struct bpf_reg_state * dst_reg, bool off_is_neg)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int sanitize_ptr_alu(struct bpf_verifier_env * env, struct bpf_insn * insn, const struct bpf_reg_state * ptr_reg, struct bpf_reg_state * dst_reg, bool off_is_neg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int sanitize_ptr_alu(struct bpf_verifier_env * env, struct bpf_insn * insn, const struct bpf_reg_state * ptr_reg, struct bpf_reg_state * dst_reg, bool off_is_neg)
```
</details>
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
