# Function: <code>adjust_reg_min_max_vals</code>

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
  "name": "adjust_reg_min_max_vals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580482688,
      "name": "adjust_reg_min_max_vals",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1516",
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
  "name": "adjust_reg_min_max_vals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580511981,
      "name": "adjust_reg_min_max_vals",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1803",
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
int adjust_reg_min_max_vals(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "adjust_reg_min_max_vals",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580564208,
      "name": "adjust_reg_min_max_vals",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2329",
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
      "addr": 18446744071580564208,
      "name": "adjust_reg_min_max_vals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2498
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
int adjust_reg_min_max_vals(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "adjust_reg_min_max_vals",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580650768,
      "name": "adjust_reg_min_max_vals",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3114",
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
      "addr": 18446744071580650768,
      "name": "adjust_reg_min_max_vals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2569
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
int adjust_reg_min_max_vals(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "adjust_reg_min_max_vals",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580714848,
      "name": "adjust_reg_min_max_vals",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3714",
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
      "addr": 18446744071580714848,
      "name": "adjust_reg_min_max_vals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2832
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int adjust_reg_min_max_vals(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "adjust_reg_min_max_vals",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_reg_min_max_vals",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4842",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_alu_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580796928,
      "name": "adjust_reg_min_max_vals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
    },
    {
      "addr": 18446744071580833067,
      "name": "adjust_reg_min_max_vals.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int adjust_reg_min_max_vals(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "adjust_reg_min_max_vals",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580848032,
      "name": "adjust_reg_min_max_vals",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4852",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_alu_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580848032,
      "name": "adjust_reg_min_max_vals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 582
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
int adjust_reg_min_max_vals(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "adjust_reg_min_max_vals",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581000016,
      "name": "adjust_reg_min_max_vals",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5923",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_alu_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581000016,
      "name": "adjust_reg_min_max_vals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 684
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
int adjust_reg_min_max_vals(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "adjust_reg_min_max_vals",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581002064,
      "name": "adjust_reg_min_max_vals",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6511",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_alu_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581002064,
      "name": "adjust_reg_min_max_vals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 703
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
int adjust_reg_min_max_vals(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "adjust_reg_min_max_vals",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580988256,
      "name": "adjust_reg_min_max_vals",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7674",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_alu_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580988256,
      "name": "adjust_reg_min_max_vals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 703
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
int adjust_reg_min_max_vals(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "adjust_reg_min_max_vals",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_reg_min_max_vals",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7963",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_alu_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581200464,
      "name": "adjust_reg_min_max_vals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 791
    },
    {
      "addr": 18446744071592182852,
      "name": "adjust_reg_min_max_vals.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
int adjust_reg_min_max_vals(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "adjust_reg_min_max_vals",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_reg_min_max_vals",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8954",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_alu_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581483616,
      "name": "adjust_reg_min_max_vals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 666
    },
    {
      "addr": 18446744071593956917,
      "name": "adjust_reg_min_max_vals.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
int adjust_reg_min_max_vals(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "adjust_reg_min_max_vals",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_reg_min_max_vals",
      "external": false,
      "loc": "kernel/bpf/verifier.c:10890",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_alu_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581863600,
      "name": "adjust_reg_min_max_vals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
    },
    {
      "addr": 18446744071596017859,
      "name": "adjust_reg_min_max_vals.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int adjust_reg_min_max_vals(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "adjust_reg_min_max_vals",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_reg_min_max_vals",
      "external": false,
      "loc": "kernel/bpf/verifier.c:12806",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_alu_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582060336,
      "name": "adjust_reg_min_max_vals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 704
    },
    {
      "addr": 18446744071596540144,
      "name": "adjust_reg_min_max_vals.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
int adjust_reg_min_max_vals(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "adjust_reg_min_max_vals",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_reg_min_max_vals",
      "external": false,
      "loc": "kernel/bpf/verifier.c:13744",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_alu_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582194368,
      "name": "adjust_reg_min_max_vals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 704
    },
    {
      "addr": 18446744071597442142,
      "name": "adjust_reg_min_max_vals.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
int adjust_reg_min_max_vals(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "adjust_reg_min_max_vals",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492172944,
      "name": "adjust_reg_min_max_vals",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4852",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_alu_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492172944,
      "name": "adjust_reg_min_max_vals",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "adjust_reg_min_max_vals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226075116,
      "name": "adjust_reg_min_max_vals",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4852",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_alu_op"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int adjust_reg_min_max_vals(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "adjust_reg_min_max_vals",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285386288,
      "name": "adjust_reg_min_max_vals",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4852",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_alu_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285386288,
      "name": "adjust_reg_min_max_vals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
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
int adjust_reg_min_max_vals(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "adjust_reg_min_max_vals",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272329310,
      "name": "adjust_reg_min_max_vals",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4852",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_alu_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272329310,
      "name": "adjust_reg_min_max_vals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 542
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
int adjust_reg_min_max_vals(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "adjust_reg_min_max_vals",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580816832,
      "name": "adjust_reg_min_max_vals",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4852",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_alu_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580816832,
      "name": "adjust_reg_min_max_vals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 582
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
int adjust_reg_min_max_vals(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "adjust_reg_min_max_vals",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580763008,
      "name": "adjust_reg_min_max_vals",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4852",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_alu_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580763008,
      "name": "adjust_reg_min_max_vals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 582
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
int adjust_reg_min_max_vals(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "adjust_reg_min_max_vals",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580808080,
      "name": "adjust_reg_min_max_vals",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4852",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_alu_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580808080,
      "name": "adjust_reg_min_max_vals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 582
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
int adjust_reg_min_max_vals(struct bpf_verifier_env * env, struct bpf_insn * insn)
```

```json
{
  "name": "adjust_reg_min_max_vals",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580866464,
      "name": "adjust_reg_min_max_vals",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4852",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_alu_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580866464,
      "name": "adjust_reg_min_max_vals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 582
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
int adjust_reg_min_max_vals(struct bpf_verifier_env * env, struct bpf_insn * insn)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int adjust_reg_min_max_vals(struct bpf_verifier_env * env, struct bpf_insn * insn)
```
</details>
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
