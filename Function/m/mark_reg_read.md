# Function: <code>mark_reg_read</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mark_reg_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580563136,
      "name": "mark_reg_read",
      "external": false,
      "loc": "kernel/bpf/verifier.c:623",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_reg_arg"
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
int mark_reg_read(struct bpf_verifier_env * env, const struct bpf_verifier_state * state, struct bpf_verifier_state * parent, u32 regno)
```

```json
{
  "name": "mark_reg_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580647232,
      "name": "mark_reg_read",
      "external": false,
      "loc": "kernel/bpf/verifier.c:927",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_reg_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580647232,
      "name": "mark_reg_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
int mark_reg_read(struct bpf_verifier_env * env, const struct bpf_reg_state * state, struct bpf_reg_state * parent)
```

```json
{
  "name": "mark_reg_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580709584,
      "name": "mark_reg_read",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1130",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_reg_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580709584,
      "name": "mark_reg_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
int mark_reg_read(struct bpf_verifier_env * env, const struct bpf_reg_state * state, struct bpf_reg_state * parent, u8 flag)
```

```json
{
  "name": "mark_reg_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580786848,
      "name": "mark_reg_read",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1195",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:propagate_liveness_reg",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_reg_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580786848,
      "name": "mark_reg_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
int mark_reg_read(struct bpf_verifier_env * env, const struct bpf_reg_state * state, struct bpf_reg_state * parent, u8 flag)
```

```json
{
  "name": "mark_reg_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580837952,
      "name": "mark_reg_read",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1196",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:propagate_liveness_reg",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_reg_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580837952,
      "name": "mark_reg_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
int mark_reg_read(struct bpf_verifier_env * env, const struct bpf_reg_state * state, struct bpf_reg_state * parent, u8 flag)
```

```json
{
  "name": "mark_reg_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580970192,
      "name": "mark_reg_read",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1505",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:propagate_liveness",
        "kernel/bpf/verifier.c:propagate_liveness",
        "kernel/bpf/verifier.c:check_stack_boundary",
        "kernel/bpf/verifier.c:check_stack_read",
        "kernel/bpf/verifier.c:check_stack_read",
        "kernel/bpf/verifier.c:check_reg_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580970192,
      "name": "mark_reg_read",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int mark_reg_read(struct bpf_verifier_env * env, const struct bpf_reg_state * state, struct bpf_reg_state * parent, u8 flag)
```

```json
{
  "name": "mark_reg_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580969632,
      "name": "mark_reg_read",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1557",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:propagate_liveness",
        "kernel/bpf/verifier.c:propagate_liveness",
        "kernel/bpf/verifier.c:check_stack_boundary",
        "kernel/bpf/verifier.c:check_stack_read",
        "kernel/bpf/verifier.c:check_stack_read",
        "kernel/bpf/verifier.c:check_reg_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580969632,
      "name": "mark_reg_read",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int mark_reg_read(struct bpf_verifier_env * env, const struct bpf_reg_state * state, struct bpf_reg_state * parent, u8 flag)
```

```json
{
  "name": "mark_reg_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580969648,
      "name": "mark_reg_read",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1828",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:propagate_liveness",
        "kernel/bpf/verifier.c:propagate_liveness",
        "kernel/bpf/verifier.c:check_stack_range_initialized",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off",
        "kernel/bpf/verifier.c:check_reg_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580969648,
      "name": "mark_reg_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
int mark_reg_read(struct bpf_verifier_env * env, const struct bpf_reg_state * state, struct bpf_reg_state * parent, u8 flag)
```

```json
{
  "name": "mark_reg_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581179232,
      "name": "mark_reg_read",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1896",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:propagate_liveness",
        "kernel/bpf/verifier.c:propagate_liveness",
        "kernel/bpf/verifier.c:check_stack_range_initialized",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off",
        "kernel/bpf/verifier.c:check_reg_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581179232,
      "name": "mark_reg_read",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int mark_reg_read(struct bpf_verifier_env * env, const struct bpf_reg_state * state, struct bpf_reg_state * parent, u8 flag)
```

```json
{
  "name": "mark_reg_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581458016,
      "name": "mark_reg_read",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2239",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:propagate_liveness",
        "kernel/bpf/verifier.c:propagate_liveness",
        "kernel/bpf/verifier.c:check_stack_range_initialized",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off",
        "kernel/bpf/verifier.c:check_reg_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581458016,
      "name": "mark_reg_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int mark_reg_read(struct bpf_verifier_env * env, const struct bpf_reg_state * state, struct bpf_reg_state * parent, u8 flag)
```

```json
{
  "name": "mark_reg_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581820256,
      "name": "mark_reg_read",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2454",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:propagate_liveness",
        "kernel/bpf/verifier.c:propagate_liveness",
        "kernel/bpf/verifier.c:process_dynptr_func",
        "kernel/bpf/verifier.c:process_dynptr_func",
        "kernel/bpf/verifier.c:check_stack_range_initialized",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off",
        "kernel/bpf/verifier.c:check_reg_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581820256,
      "name": "mark_reg_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int mark_reg_read(struct bpf_verifier_env * env, const struct bpf_reg_state * state, struct bpf_reg_state * parent, u8 flag)
```

```json
{
  "name": "mark_reg_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581954512,
      "name": "mark_reg_read",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2885",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:propagate_liveness",
        "kernel/bpf/verifier.c:propagate_liveness",
        "kernel/bpf/verifier.c:process_iter_arg",
        "kernel/bpf/verifier.c:process_dynptr_func",
        "kernel/bpf/verifier.c:process_dynptr_func",
        "kernel/bpf/verifier.c:check_stack_range_initialized",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off",
        "kernel/bpf/verifier.c:check_reg_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581954512,
      "name": "mark_reg_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int mark_reg_read(struct bpf_verifier_env * env, const struct bpf_reg_state * state, struct bpf_reg_state * parent, u8 flag)
```

```json
{
  "name": "mark_reg_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582082800,
      "name": "mark_reg_read",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2983",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:propagate_liveness",
        "kernel/bpf/verifier.c:propagate_liveness",
        "kernel/bpf/verifier.c:prepare_func_exit",
        "kernel/bpf/verifier.c:process_iter_arg",
        "kernel/bpf/verifier.c:process_dynptr_func",
        "kernel/bpf/verifier.c:process_dynptr_func",
        "kernel/bpf/verifier.c:check_stack_range_initialized",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off",
        "kernel/bpf/verifier.c:__check_reg_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582082800,
      "name": "mark_reg_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int mark_reg_read(struct bpf_verifier_env * env, const struct bpf_reg_state * state, struct bpf_reg_state * parent, u8 flag)
```

```json
{
  "name": "mark_reg_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492163080,
      "name": "mark_reg_read",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1196",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:propagate_liveness_reg",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_reg_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492163080,
      "name": "mark_reg_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int mark_reg_read(struct bpf_verifier_env * env, const struct bpf_reg_state * state, struct bpf_reg_state * parent, u8 flag)
```

```json
{
  "name": "mark_reg_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226058816,
      "name": "mark_reg_read",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1196",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:propagate_liveness_reg",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_reg_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226058816,
      "name": "mark_reg_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int mark_reg_read(struct bpf_verifier_env * env, const struct bpf_reg_state * state, struct bpf_reg_state * parent, u8 flag)
```

```json
{
  "name": "mark_reg_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285373904,
      "name": "mark_reg_read",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1196",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:propagate_liveness_reg",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_reg_arg",
        "kernel/bpf/verifier.c:check_reg_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285373904,
      "name": "mark_reg_read",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int mark_reg_read(struct bpf_verifier_env * env, const struct bpf_reg_state * state, struct bpf_reg_state * parent, u8 flag)
```

```json
{
  "name": "mark_reg_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272320702,
      "name": "mark_reg_read",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1196",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:propagate_liveness_reg",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_reg_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272320702,
      "name": "mark_reg_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int mark_reg_read(struct bpf_verifier_env * env, const struct bpf_reg_state * state, struct bpf_reg_state * parent, u8 flag)
```

```json
{
  "name": "mark_reg_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580806752,
      "name": "mark_reg_read",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1196",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:propagate_liveness_reg",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_reg_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580806752,
      "name": "mark_reg_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
int mark_reg_read(struct bpf_verifier_env * env, const struct bpf_reg_state * state, struct bpf_reg_state * parent, u8 flag)
```

```json
{
  "name": "mark_reg_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580752928,
      "name": "mark_reg_read",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1196",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:propagate_liveness_reg",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_reg_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580752928,
      "name": "mark_reg_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
int mark_reg_read(struct bpf_verifier_env * env, const struct bpf_reg_state * state, struct bpf_reg_state * parent, u8 flag)
```

```json
{
  "name": "mark_reg_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580798000,
      "name": "mark_reg_read",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1196",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:propagate_liveness_reg",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_reg_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580798000,
      "name": "mark_reg_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
int mark_reg_read(struct bpf_verifier_env * env, const struct bpf_reg_state * state, struct bpf_reg_state * parent, u8 flag)
```

```json
{
  "name": "mark_reg_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580856384,
      "name": "mark_reg_read",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1196",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:propagate_liveness_reg",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_reg_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580856384,
      "name": "mark_reg_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
int mark_reg_read(struct bpf_verifier_env * env, const struct bpf_verifier_state * state, struct bpf_verifier_state * parent, u32 regno)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 regno</code>
</li>
<li>
<b>Param type changed. </b>
<code>const struct bpf_verifier_state * state</code> ➡️ <code>const struct bpf_reg_state * state</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct bpf_verifier_state * parent</code> ➡️ <code>struct bpf_reg_state * parent</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 flag</code>
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
