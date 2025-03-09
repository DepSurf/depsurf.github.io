# Function: <code>print_verifier_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void print_verifier_state(struct verifier_env * env)
```

```json
{
  "name": "print_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580367584,
      "name": "print_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:251",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580367584,
      "name": "print_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
void print_verifier_state(struct verifier_state * state)
```

```json
{
  "name": "print_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580425504,
      "name": "print_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:250",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580425504,
      "name": "print_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
void print_verifier_state(struct bpf_verifier_state * state)
```

```json
{
  "name": "print_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580475760,
      "name": "print_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:210",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580475760,
      "name": "print_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
void print_verifier_state(struct bpf_verifier_state * state)
```

```json
{
  "name": "print_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580499248,
      "name": "print_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:212",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_map_access_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580499248,
      "name": "print_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
void print_verifier_state(struct bpf_verifier_env * env, struct bpf_verifier_state * state)
```

```json
{
  "name": "print_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580555520,
      "name": "print_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:219",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_map_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580555520,
      "name": "print_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 674
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
void print_verifier_state(struct bpf_verifier_env * env, const struct bpf_func_state * state)
```

```json
{
  "name": "print_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580647648,
      "name": "print_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:285",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_map_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580647648,
      "name": "print_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 930
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
void print_verifier_state(struct bpf_verifier_env * env, const struct bpf_func_state * state)
```

```json
{
  "name": "print_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580709824,
      "name": "print_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:418",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_map_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580709824,
      "name": "print_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1109
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
void print_verifier_state(struct bpf_verifier_env * env, const struct bpf_func_state * state)
```

```json
{
  "name": "print_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580788128,
      "name": "print_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:433",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_map_access",
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580788128,
      "name": "print_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1189
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
void print_verifier_state(struct bpf_verifier_env * env, const struct bpf_func_state * state)
```

```json
{
  "name": "print_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580838352,
      "name": "print_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:433",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_map_access",
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580838352,
      "name": "print_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1189
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
void print_verifier_state(struct bpf_verifier_env * env, const struct bpf_func_state * state)
```

```json
{
  "name": "print_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580990400,
      "name": "print_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:542",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:prepare_func_exit",
        "kernel/bpf/verifier.c:prepare_func_exit",
        "kernel/bpf/verifier.c:check_func_call",
        "kernel/bpf/verifier.c:check_func_call",
        "kernel/bpf/verifier.c:check_mem_region_access",
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580990400,
      "name": "print_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1413
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
void print_verifier_state(struct bpf_verifier_env * env, const struct bpf_func_state * state)
```

```json
{
  "name": "print_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580971328,
      "name": "print_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:566",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:prepare_func_exit",
        "kernel/bpf/verifier.c:prepare_func_exit",
        "kernel/bpf/verifier.c:check_func_call",
        "kernel/bpf/verifier.c:check_func_call",
        "kernel/bpf/verifier.c:check_mem_region_access",
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580971328,
      "name": "print_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1363
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
void print_verifier_state(struct bpf_verifier_env * env, const struct bpf_func_state * state)
```

```json
{
  "name": "print_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580967312,
      "name": "print_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:614",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:prepare_func_exit",
        "kernel/bpf/verifier.c:prepare_func_exit",
        "kernel/bpf/verifier.c:check_mem_region_access",
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580967312,
      "name": "print_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1350
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
void print_verifier_state(struct bpf_verifier_env * env, const struct bpf_func_state * state)
```

```json
{
  "name": "print_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:615",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:prepare_func_exit",
        "kernel/bpf/verifier.c:prepare_func_exit",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:check_mem_region_access",
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581175968,
      "name": "print_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1817
    },
    {
      "addr": 18446744071592181101,
      "name": "print_verifier_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void print_verifier_state(struct bpf_verifier_env * env, const struct bpf_func_state * state, bool print_all)
```

```json
{
  "name": "print_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:814",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:prepare_func_exit",
        "kernel/bpf/verifier.c:prepare_func_exit",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:__mark_chain_precision",
        "kernel/bpf/verifier.c:print_insn_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581463056,
      "name": "print_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2306
    },
    {
      "addr": 18446744071593955568,
      "name": "print_verifier_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void print_verifier_state(struct bpf_verifier_env * env, const struct bpf_func_state * state, bool print_all)
```

```json
{
  "name": "print_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1003",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:prepare_func_exit",
        "kernel/bpf/verifier.c:prepare_func_exit",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:__mark_chain_precision",
        "kernel/bpf/verifier.c:print_insn_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581812832,
      "name": "print_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2206
    },
    {
      "addr": 18446744071596014789,
      "name": "print_verifier_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void print_verifier_state(struct bpf_verifier_env * env, const struct bpf_func_state * state, bool print_all)
```

```json
{
  "name": "print_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1342",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:prepare_func_exit",
        "kernel/bpf/verifier.c:prepare_func_exit",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:__mark_chain_precision",
        "kernel/bpf/verifier.c:print_insn_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582014064,
      "name": "print_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3091
    },
    {
      "addr": 18446744071596536921,
      "name": "print_verifier_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
void print_verifier_state(struct bpf_verifier_env * env, const struct bpf_func_state * state, bool print_all)
```

```json
{
  "name": "print_verifier_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_verifier_state",
      "external": true,
      "loc": "kernel/bpf/log.c:710",
      "file": "kernel/bpf/log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:prepare_func_exit",
        "kernel/bpf/verifier.c:prepare_func_exit",
        "kernel/bpf/verifier.c:__mark_chain_precision",
        "kernel/bpf/log.c:print_insn_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597445702,
      "name": "print_verifier_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071582278128,
      "name": "print_verifier_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1778
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
void print_verifier_state(struct bpf_verifier_env * env, const struct bpf_func_state * state)
```

```json
{
  "name": "print_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492164616,
      "name": "print_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:433",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_map_access",
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492164616,
      "name": "print_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1256
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
void print_verifier_state(struct bpf_verifier_env * env, const struct bpf_func_state * state)
```

```json
{
  "name": "print_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226059288,
      "name": "print_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:433",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:check_map_access",
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226059288,
      "name": "print_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1384
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
void print_verifier_state(struct bpf_verifier_env * env, const struct bpf_func_state * state)
```

```json
{
  "name": "print_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285374560,
      "name": "print_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:433",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_map_access",
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285374560,
      "name": "print_verifier_state",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void print_verifier_state(struct bpf_verifier_env * env, const struct bpf_func_state * state)
```

```json
{
  "name": "print_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272322012,
      "name": "print_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:433",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_map_access",
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272322012,
      "name": "print_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1176
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
void print_verifier_state(struct bpf_verifier_env * env, const struct bpf_func_state * state)
```

```json
{
  "name": "print_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580807152,
      "name": "print_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:433",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_map_access",
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580807152,
      "name": "print_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1189
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
void print_verifier_state(struct bpf_verifier_env * env, const struct bpf_func_state * state)
```

```json
{
  "name": "print_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580753328,
      "name": "print_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:433",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_map_access",
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580753328,
      "name": "print_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1189
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
void print_verifier_state(struct bpf_verifier_env * env, const struct bpf_func_state * state)
```

```json
{
  "name": "print_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580798400,
      "name": "print_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:433",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_map_access",
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580798400,
      "name": "print_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1189
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
void print_verifier_state(struct bpf_verifier_env * env, const struct bpf_func_state * state)
```

```json
{
  "name": "print_verifier_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580856784,
      "name": "print_verifier_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:433",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_map_access",
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580856784,
      "name": "print_verifier_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1189
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct verifier_state * state</code>
</li>
<li>
<b>Param removed. </b>
<code>struct verifier_env * env</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct verifier_state * state</code> ➡️ <code>struct bpf_verifier_state * state</code>
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
<code>struct bpf_verifier_env * env</code>
</li>
<li>
<b>Param reordered. </b>
<code>state</code> ➡️ <code>env, state</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bpf_verifier_state * state</code> ➡️ <code>const struct bpf_func_state * state</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool print_all</code>
</li>
</ul>
</details>
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
