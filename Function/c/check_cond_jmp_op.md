# Function: <code>check_cond_jmp_op</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_cond_jmp_op",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580374542,
      "name": "check_cond_jmp_op",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1164",
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
  "name": "check_cond_jmp_op",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580432044,
      "name": "check_cond_jmp_op",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1641",
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
  "name": "check_cond_jmp_op",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580484348,
      "name": "check_cond_jmp_op",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2008",
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
  "name": "check_cond_jmp_op",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580511378,
      "name": "check_cond_jmp_op",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2426",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int check_cond_jmp_op(struct bpf_verifier_env * env, struct bpf_insn * insn, int * insn_idx)
```

```json
{
  "name": "check_cond_jmp_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580568896,
      "name": "check_cond_jmp_op",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2980",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580568896,
      "name": "check_cond_jmp_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2742
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
int check_cond_jmp_op(struct bpf_verifier_env * env, struct bpf_insn * insn, int * insn_idx)
```

```json
{
  "name": "check_cond_jmp_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580661488,
      "name": "check_cond_jmp_op",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3775",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580661488,
      "name": "check_cond_jmp_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2808
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
int check_cond_jmp_op(struct bpf_verifier_env * env, struct bpf_insn * insn, int * insn_idx)
```

```json
{
  "name": "check_cond_jmp_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580727312,
      "name": "check_cond_jmp_op",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4480",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580727312,
      "name": "check_cond_jmp_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3234
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
int check_cond_jmp_op(struct bpf_verifier_env * env, struct bpf_insn * insn, int * insn_idx)
```

```json
{
  "name": "check_cond_jmp_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580803856,
      "name": "check_cond_jmp_op",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5787",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580803856,
      "name": "check_cond_jmp_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2143
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
int check_cond_jmp_op(struct bpf_verifier_env * env, struct bpf_insn * insn, int * insn_idx)
```

```json
{
  "name": "check_cond_jmp_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580854992,
      "name": "check_cond_jmp_op",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5797",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580854992,
      "name": "check_cond_jmp_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2143
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
int check_cond_jmp_op(struct bpf_verifier_env * env, struct bpf_insn * insn, int * insn_idx)
```

```json
{
  "name": "check_cond_jmp_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580995600,
      "name": "check_cond_jmp_op",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6866",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580995600,
      "name": "check_cond_jmp_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1974
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
int check_cond_jmp_op(struct bpf_verifier_env * env, struct bpf_insn * insn, int * insn_idx)
```

```json
{
  "name": "check_cond_jmp_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580989216,
      "name": "check_cond_jmp_op",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7555",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580989216,
      "name": "check_cond_jmp_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2264
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
int check_cond_jmp_op(struct bpf_verifier_env * env, struct bpf_insn * insn, int * insn_idx)
```

```json
{
  "name": "check_cond_jmp_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580996032,
      "name": "check_cond_jmp_op",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8694",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580996032,
      "name": "check_cond_jmp_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2455
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
int check_cond_jmp_op(struct bpf_verifier_env * env, struct bpf_insn * insn, int * insn_idx)
```

```json
{
  "name": "check_cond_jmp_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_cond_jmp_op",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8987",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581209600,
      "name": "check_cond_jmp_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2763
    },
    {
      "addr": 18446744071592183179,
      "name": "check_cond_jmp_op.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int check_cond_jmp_op(struct bpf_verifier_env * env, struct bpf_insn * insn, int * insn_idx)
```

```json
{
  "name": "check_cond_jmp_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_cond_jmp_op",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9969",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581493616,
      "name": "check_cond_jmp_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2907
    },
    {
      "addr": 18446744071593957361,
      "name": "check_cond_jmp_op.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int check_cond_jmp_op(struct bpf_verifier_env * env, struct bpf_insn * insn, int * insn_idx)
```

```json
{
  "name": "check_cond_jmp_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_cond_jmp_op",
      "external": false,
      "loc": "kernel/bpf/verifier.c:11867",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581866224,
      "name": "check_cond_jmp_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3156
    },
    {
      "addr": 18446744071596018000,
      "name": "check_cond_jmp_op.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
int check_cond_jmp_op(struct bpf_verifier_env * env, struct bpf_insn * insn, int * insn_idx)
```

```json
{
  "name": "check_cond_jmp_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_cond_jmp_op",
      "external": false,
      "loc": "kernel/bpf/verifier.c:13800",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582052304,
      "name": "check_cond_jmp_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3581
    },
    {
      "addr": 18446744071596539729,
      "name": "check_cond_jmp_op.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
int check_cond_jmp_op(struct bpf_verifier_env * env, struct bpf_insn * insn, int * insn_idx)
```

```json
{
  "name": "check_cond_jmp_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_cond_jmp_op",
      "external": false,
      "loc": "kernel/bpf/verifier.c:14797",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582188064,
      "name": "check_cond_jmp_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2613
    },
    {
      "addr": 18446744071597441712,
      "name": "check_cond_jmp_op.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int check_cond_jmp_op(struct bpf_verifier_env * env, struct bpf_insn * insn, int * insn_idx)
```

```json
{
  "name": "check_cond_jmp_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492180072,
      "name": "check_cond_jmp_op",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5797",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492180072,
      "name": "check_cond_jmp_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2552
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
int check_cond_jmp_op(struct bpf_verifier_env * env, struct bpf_insn * insn, int * insn_idx)
```

```json
{
  "name": "check_cond_jmp_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226077716,
      "name": "check_cond_jmp_op",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5797",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226077716,
      "name": "check_cond_jmp_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1568
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
int check_cond_jmp_op(struct bpf_verifier_env * env, struct bpf_insn * insn, int * insn_idx)
```

```json
{
  "name": "check_cond_jmp_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285395040,
      "name": "check_cond_jmp_op",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5797",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285395040,
      "name": "check_cond_jmp_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1720
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
int check_cond_jmp_op(struct bpf_verifier_env * env, struct bpf_insn * insn, int * insn_idx)
```

```json
{
  "name": "check_cond_jmp_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272335568,
      "name": "check_cond_jmp_op",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5797",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272335568,
      "name": "check_cond_jmp_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1256
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
int check_cond_jmp_op(struct bpf_verifier_env * env, struct bpf_insn * insn, int * insn_idx)
```

```json
{
  "name": "check_cond_jmp_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580823792,
      "name": "check_cond_jmp_op",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5797",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580823792,
      "name": "check_cond_jmp_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2143
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
int check_cond_jmp_op(struct bpf_verifier_env * env, struct bpf_insn * insn, int * insn_idx)
```

```json
{
  "name": "check_cond_jmp_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580769968,
      "name": "check_cond_jmp_op",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5797",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580769968,
      "name": "check_cond_jmp_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2143
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
int check_cond_jmp_op(struct bpf_verifier_env * env, struct bpf_insn * insn, int * insn_idx)
```

```json
{
  "name": "check_cond_jmp_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580815040,
      "name": "check_cond_jmp_op",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5797",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580815040,
      "name": "check_cond_jmp_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2143
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
int check_cond_jmp_op(struct bpf_verifier_env * env, struct bpf_insn * insn, int * insn_idx)
```

```json
{
  "name": "check_cond_jmp_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580873424,
      "name": "check_cond_jmp_op",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5797",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580873424,
      "name": "check_cond_jmp_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2143
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int check_cond_jmp_op(struct bpf_verifier_env * env, struct bpf_insn * insn, int * insn_idx)
```
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
