# Function: <code>pop_stack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int pop_stack(struct verifier_env * env, int * prev_insn_idx)
```

```json
{
  "name": "pop_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580367248,
      "name": "pop_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:422",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580367248,
      "name": "pop_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int pop_stack(struct verifier_env * env, int * prev_insn_idx)
```

```json
{
  "name": "pop_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580425168,
      "name": "pop_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:428",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580425168,
      "name": "pop_stack",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int pop_stack(struct bpf_verifier_env * env, int * prev_insn_idx)
```

```json
{
  "name": "pop_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580475424,
      "name": "pop_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:397",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_analyzer",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580475424,
      "name": "pop_stack",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int pop_stack(struct bpf_verifier_env * env, int * prev_insn_idx)
```

```json
{
  "name": "pop_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580500480,
      "name": "pop_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:416",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_analyzer",
        "kernel/bpf/verifier.c:bpf_analyzer",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580500480,
      "name": "pop_stack",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int pop_stack(struct bpf_verifier_env * env, int * prev_insn_idx, int * insn_idx)
```

```json
{
  "name": "pop_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580568736,
      "name": "pop_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:367",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580568736,
      "name": "pop_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int pop_stack(struct bpf_verifier_env * env, int * prev_insn_idx, int * insn_idx)
```

```json
{
  "name": "pop_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580645440,
      "name": "pop_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:485",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580645440,
      "name": "pop_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
int pop_stack(struct bpf_verifier_env * env, int * prev_insn_idx, int * insn_idx)
```

```json
{
  "name": "pop_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580708368,
      "name": "pop_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:730",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580708368,
      "name": "pop_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
int pop_stack(struct bpf_verifier_env * env, int * prev_insn_idx, int * insn_idx)
```

```json
{
  "name": "pop_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580782768,
      "name": "pop_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:776",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:push_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580782768,
      "name": "pop_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
int pop_stack(struct bpf_verifier_env * env, int * prev_insn_idx, int * insn_idx)
```

```json
{
  "name": "pop_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580833696,
      "name": "pop_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:776",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:push_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580833696,
      "name": "pop_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
int pop_stack(struct bpf_verifier_env * env, int * prev_insn_idx, int * insn_idx, bool pop_log)
```

```json
{
  "name": "pop_stack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580972077,
      "name": "pop_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:903",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:push_stack"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580962176,
      "name": "pop_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
int pop_stack(struct bpf_verifier_env * env, int * prev_insn_idx, int * insn_idx, bool pop_log)
```

```json
{
  "name": "pop_stack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580974317,
      "name": "pop_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:929",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:push_stack"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580962112,
      "name": "pop_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
int pop_stack(struct bpf_verifier_env * env, int * prev_insn_idx, int * insn_idx, bool pop_log)
```

```json
{
  "name": "pop_stack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580980301,
      "name": "pop_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:978",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:push_stack"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580961856,
      "name": "pop_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
int pop_stack(struct bpf_verifier_env * env, int * prev_insn_idx, int * insn_idx, bool pop_log)
```

```json
{
  "name": "pop_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581166816,
      "name": "pop_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:987",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:push_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581166816,
      "name": "pop_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
int pop_stack(struct bpf_verifier_env * env, int * prev_insn_idx, int * insn_idx, bool pop_log)
```

```json
{
  "name": "pop_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581446080,
      "name": "pop_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1214",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:push_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581446080,
      "name": "pop_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
int pop_stack(struct bpf_verifier_env * env, int * prev_insn_idx, int * insn_idx, bool pop_log)
```

```json
{
  "name": "pop_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581801152,
      "name": "pop_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1418",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:push_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581801152,
      "name": "pop_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
int pop_stack(struct bpf_verifier_env * env, int * prev_insn_idx, int * insn_idx, bool pop_log)
```

```json
{
  "name": "pop_stack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582001864,
      "name": "pop_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1795",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:push_stack"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:__check_func_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581986512,
      "name": "pop_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
int pop_stack(struct bpf_verifier_env * env, int * prev_insn_idx, int * insn_idx, bool pop_log)
```

```json
{
  "name": "pop_stack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582124903,
      "name": "pop_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1645",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:push_stack"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:push_callback_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582115360,
      "name": "pop_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
int pop_stack(struct bpf_verifier_env * env, int * prev_insn_idx, int * insn_idx)
```

```json
{
  "name": "pop_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492157224,
      "name": "pop_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:776",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:push_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492157224,
      "name": "pop_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int pop_stack(struct bpf_verifier_env * env, int * prev_insn_idx, int * insn_idx)
```

```json
{
  "name": "pop_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226054024,
      "name": "pop_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:776",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:push_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226054024,
      "name": "pop_stack",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int pop_stack(struct bpf_verifier_env * env, int * prev_insn_idx, int * insn_idx)
```

```json
{
  "name": "pop_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285368432,
      "name": "pop_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:776",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:push_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285368432,
      "name": "pop_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
int pop_stack(struct bpf_verifier_env * env, int * prev_insn_idx, int * insn_idx)
```

```json
{
  "name": "pop_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272317162,
      "name": "pop_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:776",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:push_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272317162,
      "name": "pop_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int pop_stack(struct bpf_verifier_env * env, int * prev_insn_idx, int * insn_idx)
```

```json
{
  "name": "pop_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580802496,
      "name": "pop_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:776",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:push_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580802496,
      "name": "pop_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
int pop_stack(struct bpf_verifier_env * env, int * prev_insn_idx, int * insn_idx)
```

```json
{
  "name": "pop_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580748672,
      "name": "pop_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:776",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:push_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580748672,
      "name": "pop_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
int pop_stack(struct bpf_verifier_env * env, int * prev_insn_idx, int * insn_idx)
```

```json
{
  "name": "pop_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580793744,
      "name": "pop_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:776",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:push_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580793744,
      "name": "pop_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
int pop_stack(struct bpf_verifier_env * env, int * prev_insn_idx, int * insn_idx)
```

```json
{
  "name": "pop_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580852128,
      "name": "pop_stack",
      "external": false,
      "loc": "kernel/bpf/verifier.c:776",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:push_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580852128,
      "name": "pop_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct verifier_env * env</code> ➡️ <code>struct bpf_verifier_env * env</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int * insn_idx</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool pop_log</code>
</li>
</ul>
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
