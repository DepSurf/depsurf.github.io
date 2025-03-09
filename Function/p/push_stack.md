# Function: <code>push_stack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "push_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580374769,
      "name": "push_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:441",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "push_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580432842,
      "name": "push_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:447",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "push_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580486105,
      "name": "push_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:416",
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
  "name": "push_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580512573,
      "name": "push_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:435",
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
  "name": "push_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580569057,
      "name": "push_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:394",
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
  "name": "push_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580661798,
      "name": "push_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:512",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_verifier_state * push_stack(struct bpf_verifier_env * env, int insn_idx, int prev_insn_idx, bool speculative)
```

```json
{
  "name": "push_stack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580711024,
      "name": "push_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:757",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:sanitize_ptr_alu",
        "kernel/bpf/verifier.c:sanitize_ptr_alu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580711024,
      "name": "push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
struct bpf_verifier_state * push_stack(struct bpf_verifier_env * env, int insn_idx, int prev_insn_idx, bool speculative)
```

```json
{
  "name": "push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580790608,
      "name": "push_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:803",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:sanitize_ptr_alu",
        "kernel/bpf/verifier.c:sanitize_ptr_alu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580790608,
      "name": "push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
struct bpf_verifier_state * push_stack(struct bpf_verifier_env * env, int insn_idx, int prev_insn_idx, bool speculative)
```

```json
{
  "name": "push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580841632,
      "name": "push_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:803",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:sanitize_ptr_alu",
        "kernel/bpf/verifier.c:sanitize_ptr_alu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580841632,
      "name": "push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
struct bpf_verifier_state * push_stack(struct bpf_verifier_env * env, int insn_idx, int prev_insn_idx, bool speculative)
```

```json
{
  "name": "push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580971872,
      "name": "push_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:932",
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
      "addr": 18446744071580971872,
      "name": "push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
struct bpf_verifier_state * push_stack(struct bpf_verifier_env * env, int insn_idx, int prev_insn_idx, bool speculative)
```

```json
{
  "name": "push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580974112,
      "name": "push_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:958",
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
      "addr": 18446744071580974112,
      "name": "push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
struct bpf_verifier_state * push_stack(struct bpf_verifier_env * env, int insn_idx, int prev_insn_idx, bool speculative)
```

```json
{
  "name": "push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580980096,
      "name": "push_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1007",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:sanitize_speculative_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580980096,
      "name": "push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
struct bpf_verifier_state * push_stack(struct bpf_verifier_env * env, int insn_idx, int prev_insn_idx, bool speculative)
```

```json
{
  "name": "push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "push_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1016",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:sanitize_speculative_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581192240,
      "name": "push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071592182216,
      "name": "push_stack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct bpf_verifier_state * push_stack(struct bpf_verifier_env * env, int insn_idx, int prev_insn_idx, bool speculative)
```

```json
{
  "name": "push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "push_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1243",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:sanitize_speculative_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581475760,
      "name": "push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    },
    {
      "addr": 18446744071593956327,
      "name": "push_stack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct bpf_verifier_state * push_stack(struct bpf_verifier_env * env, int insn_idx, int prev_insn_idx, bool speculative)
```

```json
{
  "name": "push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "push_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1447",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:sanitize_speculative_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581834928,
      "name": "push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
    },
    {
      "addr": 18446744071596016103,
      "name": "push_stack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct bpf_verifier_state * push_stack(struct bpf_verifier_env * env, int insn_idx, int prev_insn_idx, bool speculative)
```

```json
{
  "name": "push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "push_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1824",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:sanitize_speculative_path",
        "kernel/bpf/verifier.c:check_kfunc_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582001600,
      "name": "push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
    },
    {
      "addr": 18446744071596536356,
      "name": "push_stack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct bpf_verifier_state * push_stack(struct bpf_verifier_env * env, int insn_idx, int prev_insn_idx, bool speculative)
```

```json
{
  "name": "push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "push_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1674",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:sanitize_speculative_path",
        "kernel/bpf/verifier.c:push_callback_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582124592,
      "name": "push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
    },
    {
      "addr": 18446744071597437381,
      "name": "push_stack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct bpf_verifier_state * push_stack(struct bpf_verifier_env * env, int insn_idx, int prev_insn_idx, bool speculative)
```

```json
{
  "name": "push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492167240,
      "name": "push_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:803",
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
      "addr": 18446603336492167240,
      "name": "push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
struct bpf_verifier_state * push_stack(struct bpf_verifier_env * env, int insn_idx, int prev_insn_idx, bool speculative)
```

```json
{
  "name": "push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226063196,
      "name": "push_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:803",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:sanitize_ptr_alu",
        "kernel/bpf/verifier.c:sanitize_ptr_alu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226063196,
      "name": "push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
struct bpf_verifier_state * push_stack(struct bpf_verifier_env * env, int insn_idx, int prev_insn_idx, bool speculative)
```

```json
{
  "name": "push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285378928,
      "name": "push_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:803",
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
      "addr": 13835058055285378928,
      "name": "push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
struct bpf_verifier_state * push_stack(struct bpf_verifier_env * env, int insn_idx, int prev_insn_idx, bool speculative)
```

```json
{
  "name": "push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272324378,
      "name": "push_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:803",
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
      "addr": 18446743936272324378,
      "name": "push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
struct bpf_verifier_state * push_stack(struct bpf_verifier_env * env, int insn_idx, int prev_insn_idx, bool speculative)
```

```json
{
  "name": "push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580810432,
      "name": "push_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:803",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:sanitize_ptr_alu",
        "kernel/bpf/verifier.c:sanitize_ptr_alu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580810432,
      "name": "push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
struct bpf_verifier_state * push_stack(struct bpf_verifier_env * env, int insn_idx, int prev_insn_idx, bool speculative)
```

```json
{
  "name": "push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580756608,
      "name": "push_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:803",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:sanitize_ptr_alu",
        "kernel/bpf/verifier.c:sanitize_ptr_alu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580756608,
      "name": "push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
struct bpf_verifier_state * push_stack(struct bpf_verifier_env * env, int insn_idx, int prev_insn_idx, bool speculative)
```

```json
{
  "name": "push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580801680,
      "name": "push_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:803",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:sanitize_ptr_alu",
        "kernel/bpf/verifier.c:sanitize_ptr_alu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580801680,
      "name": "push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
struct bpf_verifier_state * push_stack(struct bpf_verifier_env * env, int insn_idx, int prev_insn_idx, bool speculative)
```

```json
{
  "name": "push_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580860064,
      "name": "push_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:803",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:sanitize_ptr_alu",
        "kernel/bpf/verifier.c:sanitize_ptr_alu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580860064,
      "name": "push_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
struct bpf_verifier_state * push_stack(struct bpf_verifier_env * env, int insn_idx, int prev_insn_idx, bool speculative)
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
