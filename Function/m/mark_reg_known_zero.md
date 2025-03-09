# Function: <code>mark_reg_known_zero</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_known_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580566720,
      "name": "mark_reg_known_zero",
      "external": false,
      "loc": "kernel/bpf/verifier.c:452",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580566720,
      "name": "mark_reg_known_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
void mark_reg_known_zero(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_known_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580646848,
      "name": "mark_reg_known_zero",
      "external": false,
      "loc": "kernel/bpf/verifier.c:579",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:init_reg_state",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580646848,
      "name": "mark_reg_known_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_known_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580709328,
      "name": "mark_reg_known_zero",
      "external": false,
      "loc": "kernel/bpf/verifier.c:827",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:init_reg_state",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580709328,
      "name": "mark_reg_known_zero",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_known_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580832967,
      "name": "mark_reg_known_zero",
      "external": false,
      "loc": "kernel/bpf/verifier.c:886",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:init_reg_state",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580786624,
      "name": "mark_reg_known_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071580832922,
      "name": "mark_reg_known_zero.cold",
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
void mark_reg_known_zero(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_known_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580837632,
      "name": "mark_reg_known_zero",
      "external": false,
      "loc": "kernel/bpf/verifier.c:887",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:init_reg_state",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580837632,
      "name": "mark_reg_known_zero",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_known_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580969936,
      "name": "mark_reg_known_zero",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1031",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:check_ld_imm",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580969936,
      "name": "mark_reg_known_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void mark_reg_known_zero(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_known_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580969376,
      "name": "mark_reg_known_zero",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1063",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:check_ld_imm",
        "kernel/bpf/verifier.c:check_ld_imm",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580969376,
      "name": "mark_reg_known_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void mark_reg_known_zero(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_known_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580977232,
      "name": "mark_reg_known_zero",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1112",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:check_ld_imm",
        "kernel/bpf/verifier.c:check_ld_imm",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580977232,
      "name": "mark_reg_known_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void mark_reg_known_zero(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_known_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581255558,
      "name": "mark_reg_known_zero",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1121",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:init_reg_state"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:check_ld_imm",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581188896,
      "name": "mark_reg_known_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void mark_reg_known_zero(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_known_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581546747,
      "name": "mark_reg_known_zero",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1348",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:init_reg_state"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:check_ld_imm",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581474832,
      "name": "mark_reg_known_zero",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_known_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581918092,
      "name": "mark_reg_known_zero",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1549",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:init_reg_state"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:check_ld_imm",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581824144,
      "name": "mark_reg_known_zero",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_known_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582100572,
      "name": "mark_reg_known_zero",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1928",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:init_reg_state"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:check_ld_imm",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581976192,
      "name": "mark_reg_known_zero",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_known_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582238725,
      "name": "mark_reg_known_zero",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1782",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:init_reg_state"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:check_ld_imm",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582100064,
      "name": "mark_reg_known_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_known_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492162760,
      "name": "mark_reg_known_zero",
      "external": false,
      "loc": "kernel/bpf/verifier.c:887",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:init_reg_state",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492162760,
      "name": "mark_reg_known_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void mark_reg_known_zero(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_known_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226058528,
      "name": "mark_reg_known_zero",
      "external": false,
      "loc": "kernel/bpf/verifier.c:887",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:init_reg_state",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226058528,
      "name": "mark_reg_known_zero",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_known_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285373472,
      "name": "mark_reg_known_zero",
      "external": false,
      "loc": "kernel/bpf/verifier.c:887",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:init_reg_state",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285373472,
      "name": "mark_reg_known_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_known_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272320400,
      "name": "mark_reg_known_zero",
      "external": false,
      "loc": "kernel/bpf/verifier.c:887",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:init_reg_state",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272320400,
      "name": "mark_reg_known_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void mark_reg_known_zero(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_known_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580806432,
      "name": "mark_reg_known_zero",
      "external": false,
      "loc": "kernel/bpf/verifier.c:887",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:init_reg_state",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580806432,
      "name": "mark_reg_known_zero",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_known_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580752608,
      "name": "mark_reg_known_zero",
      "external": false,
      "loc": "kernel/bpf/verifier.c:887",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:init_reg_state",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580752608,
      "name": "mark_reg_known_zero",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_known_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580797680,
      "name": "mark_reg_known_zero",
      "external": false,
      "loc": "kernel/bpf/verifier.c:887",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:init_reg_state",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580797680,
      "name": "mark_reg_known_zero",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void mark_reg_known_zero(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
```

```json
{
  "name": "mark_reg_known_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580856064,
      "name": "mark_reg_known_zero",
      "external": false,
      "loc": "kernel/bpf/verifier.c:887",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:init_reg_state",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580856064,
      "name": "mark_reg_known_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void mark_reg_known_zero(struct bpf_verifier_env * env, struct bpf_reg_state * regs, u32 regno)
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
