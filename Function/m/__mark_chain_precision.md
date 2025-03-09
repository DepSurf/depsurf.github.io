# Function: <code>__mark_chain_precision</code>

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
int __mark_chain_precision(struct bpf_verifier_env * env, int regno, int spi)
```

```json
{
  "name": "__mark_chain_precision",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580789328,
      "name": "__mark_chain_precision",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1660",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580789328,
      "name": "__mark_chain_precision",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1183
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
int __mark_chain_precision(struct bpf_verifier_env * env, int regno, int spi)
```

```json
{
  "name": "__mark_chain_precision",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580839552,
      "name": "__mark_chain_precision",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1661",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580839552,
      "name": "__mark_chain_precision",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1938
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
int __mark_chain_precision(struct bpf_verifier_env * env, int regno, int spi)
```

```json
{
  "name": "__mark_chain_precision",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580991824,
      "name": "__mark_chain_precision",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1970",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:propagate_precision",
        "kernel/bpf/verifier.c:propagate_precision",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_stack_write",
        "kernel/bpf/verifier.c:check_stack_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580991824,
      "name": "__mark_chain_precision",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1141
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
int __mark_chain_precision(struct bpf_verifier_env * env, int regno, int spi)
```

```json
{
  "name": "__mark_chain_precision",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580972704,
      "name": "__mark_chain_precision",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2022",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:propagate_precision",
        "kernel/bpf/verifier.c:propagate_precision",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_stack_write",
        "kernel/bpf/verifier.c:check_stack_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580972704,
      "name": "__mark_chain_precision",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1141
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
int __mark_chain_precision(struct bpf_verifier_env * env, int regno, int spi)
```

```json
{
  "name": "__mark_chain_precision",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580978368,
      "name": "__mark_chain_precision",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2325",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_stack_write_var_off",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580978368,
      "name": "__mark_chain_precision",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1214
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
int __mark_chain_precision(struct bpf_verifier_env * env, int regno, int spi)
```

```json
{
  "name": "__mark_chain_precision",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mark_chain_precision",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2393",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_stack_write_var_off",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581189968,
      "name": "__mark_chain_precision",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1549
    },
    {
      "addr": 18446744071592181673,
      "name": "__mark_chain_precision.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
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
int __mark_chain_precision(struct bpf_verifier_env * env, int regno, int spi)
```

```json
{
  "name": "__mark_chain_precision",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mark_chain_precision",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2739",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_mem_size_reg",
        "kernel/bpf/verifier.c:check_stack_write_var_off",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581465376,
      "name": "__mark_chain_precision",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1623
    },
    {
      "addr": 18446744071593955694,
      "name": "__mark_chain_precision.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
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
int __mark_chain_precision(struct bpf_verifier_env * env, int frame, int regno, int spi)
```

```json
{
  "name": "__mark_chain_precision",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mark_chain_precision",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3122",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:propagate_precision",
        "kernel/bpf/verifier.c:propagate_precision",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_size_reg",
        "kernel/bpf/verifier.c:check_stack_write_var_off",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581815056,
      "name": "__mark_chain_precision",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1863
    },
    {
      "addr": 18446744071596014938,
      "name": "__mark_chain_precision.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
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
int __mark_chain_precision(struct bpf_verifier_env * env, int regno)
```

```json
{
  "name": "__mark_chain_precision",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mark_chain_precision",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3959",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:propagate_precision",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_size_reg",
        "kernel/bpf/verifier.c:check_stack_write_var_off",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582041120,
      "name": "__mark_chain_precision",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3084
    },
    {
      "addr": 18446744071596538178,
      "name": "__mark_chain_precision.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
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
int __mark_chain_precision(struct bpf_verifier_env * env, int regno)
```

```json
{
  "name": "__mark_chain_precision",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mark_chain_precision",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4121",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:propagate_precision",
        "kernel/bpf/verifier.c:check_return_code",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:prepare_func_exit",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_size_reg",
        "kernel/bpf/verifier.c:check_stack_write_var_off",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582156688,
      "name": "__mark_chain_precision",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3312
    },
    {
      "addr": 18446744071597439222,
      "name": "__mark_chain_precision.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
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
int __mark_chain_precision(struct bpf_verifier_env * env, int regno, int spi)
```

```json
{
  "name": "__mark_chain_precision",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492165872,
      "name": "__mark_chain_precision",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1661",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_stack_write",
        "kernel/bpf/verifier.c:check_stack_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492165872,
      "name": "__mark_chain_precision",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1228
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
int __mark_chain_precision(struct bpf_verifier_env * env, int regno, int spi)
```

```json
{
  "name": "__mark_chain_precision",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226060672,
      "name": "__mark_chain_precision",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1661",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_stack_write",
        "kernel/bpf/verifier.c:check_stack_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226060672,
      "name": "__mark_chain_precision",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2388
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
int __mark_chain_precision(struct bpf_verifier_env * env, int regno, int spi)
```

```json
{
  "name": "__mark_chain_precision",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285376128,
      "name": "__mark_chain_precision",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1661",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_stack_write",
        "kernel/bpf/verifier.c:check_stack_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285376128,
      "name": "__mark_chain_precision",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2572
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
int __mark_chain_precision(struct bpf_verifier_env * env, int regno, int spi)
```

```json
{
  "name": "__mark_chain_precision",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272323188,
      "name": "__mark_chain_precision",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1661",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_stack_write",
        "kernel/bpf/verifier.c:check_stack_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272323188,
      "name": "__mark_chain_precision",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1056
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
int __mark_chain_precision(struct bpf_verifier_env * env, int regno, int spi)
```

```json
{
  "name": "__mark_chain_precision",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580808352,
      "name": "__mark_chain_precision",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1661",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580808352,
      "name": "__mark_chain_precision",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1938
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
int __mark_chain_precision(struct bpf_verifier_env * env, int regno, int spi)
```

```json
{
  "name": "__mark_chain_precision",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580754528,
      "name": "__mark_chain_precision",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1661",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580754528,
      "name": "__mark_chain_precision",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1938
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
int __mark_chain_precision(struct bpf_verifier_env * env, int regno, int spi)
```

```json
{
  "name": "__mark_chain_precision",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580799600,
      "name": "__mark_chain_precision",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1661",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580799600,
      "name": "__mark_chain_precision",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1938
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
int __mark_chain_precision(struct bpf_verifier_env * env, int regno, int spi)
```

```json
{
  "name": "__mark_chain_precision",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580857984,
      "name": "__mark_chain_precision",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1661",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580857984,
      "name": "__mark_chain_precision",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1938
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int __mark_chain_precision(struct bpf_verifier_env * env, int regno, int spi)
```
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int frame</code>
</li>
<li>
<b>Param reordered. </b>
<code>env, regno, spi</code> ➡️ <code>env, frame, regno, spi</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int frame</code>
</li>
<li>
<b>Param removed. </b>
<code>int spi</code>
</li>
<li>
<b>Param reordered. </b>
<code>env, frame, regno, spi</code> ➡️ <code>env, regno</code>
</li>
</ul>
</details>
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
