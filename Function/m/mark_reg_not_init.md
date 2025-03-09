# Function: <code>mark_reg_not_init</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mark_reg_not_init(struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_not_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580501424,
      "name": "mark_reg_not_init",
      "external": false,
      "loc": "kernel/bpf/verifier.c:466",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580501424,
      "name": "mark_reg_not_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_not_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580562608,
      "name": "mark_reg_not_init",
      "external": false,
      "loc": "kernel/bpf/verifier.c:585",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580562608,
      "name": "mark_reg_not_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_not_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580646592,
      "name": "mark_reg_not_init",
      "external": false,
      "loc": "kernel/bpf/verifier.c:713",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580646592,
      "name": "mark_reg_not_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_not_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580707072,
      "name": "mark_reg_not_init",
      "external": false,
      "loc": "kernel/bpf/verifier.c:964",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580707072,
      "name": "mark_reg_not_init.part.46",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071580709248,
      "name": "mark_reg_not_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_not_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580832893,
      "name": "mark_reg_not_init",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1027",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580786544,
      "name": "mark_reg_not_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071580832848,
      "name": "mark_reg_not_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_not_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580837488,
      "name": "mark_reg_not_init",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1028",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580837488,
      "name": "mark_reg_not_init",
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
void mark_reg_not_init(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_not_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580969296,
      "name": "mark_reg_not_init",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1340",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_ld_abs",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_func_call",
        "kernel/bpf/verifier.c:check_func_call",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580969296,
      "name": "mark_reg_not_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void mark_reg_not_init(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_not_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580968736,
      "name": "mark_reg_not_init",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1370",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_ld_abs",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_func_call",
        "kernel/bpf/verifier.c:check_func_call",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580968736,
      "name": "mark_reg_not_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void mark_reg_not_init(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_not_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580976768,
      "name": "mark_reg_not_init",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1462",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_ld_abs",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580976768,
      "name": "mark_reg_not_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void mark_reg_not_init(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_not_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581188224,
      "name": "mark_reg_not_init",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1482",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_ld_abs",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581188224,
      "name": "mark_reg_not_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void mark_reg_not_init(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_not_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581473744,
      "name": "mark_reg_not_init",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1685",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_ld_abs",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581473744,
      "name": "mark_reg_not_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void mark_reg_not_init(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_not_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581833520,
      "name": "mark_reg_not_init",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1899",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_ld_abs",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581833520,
      "name": "mark_reg_not_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void mark_reg_not_init(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_not_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581969936,
      "name": "mark_reg_not_init",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2298",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_ld_abs",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581969936,
      "name": "mark_reg_not_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void mark_reg_not_init(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_not_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582098880,
      "name": "mark_reg_not_init",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2304",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_ld_abs",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582098880,
      "name": "mark_reg_not_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_not_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492155040,
      "name": "mark_reg_not_init",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1028",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492155040,
      "name": "mark_reg_not_init.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446603336492162616,
      "name": "mark_reg_not_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_not_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226058380,
      "name": "mark_reg_not_init",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1028",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226058380,
      "name": "mark_reg_not_init",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_not_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285373264,
      "name": "mark_reg_not_init",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1028",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285373264,
      "name": "mark_reg_not_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_not_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272315368,
      "name": "mark_reg_not_init",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1028",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272315368,
      "name": "mark_reg_not_init.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446743936272320260,
      "name": "mark_reg_not_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_not_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580806288,
      "name": "mark_reg_not_init",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1028",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580806288,
      "name": "mark_reg_not_init",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_not_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580752464,
      "name": "mark_reg_not_init",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1028",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580752464,
      "name": "mark_reg_not_init",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_not_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580797536,
      "name": "mark_reg_not_init",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1028",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580797536,
      "name": "mark_reg_not_init",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_not_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580855920,
      "name": "mark_reg_not_init",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1028",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580855920,
      "name": "mark_reg_not_init",
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void mark_reg_not_init(struct bpf_reg_state * regs, u32 regno)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_verifier_env * env</code>
</li>
<li>
<b>Param reordered. </b>
<code>regs, regno</code> ➡️ <code>env, regs, regno</code>
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
