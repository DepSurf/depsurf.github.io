# Function: <code>__mark_reg_known</code>

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
  "name": "__mark_reg_known",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580579311,
      "name": "__mark_reg_known",
      "external": false,
      "loc": "kernel/bpf/verifier.c:434",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:mark_map_reg",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals"
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
  "name": "__mark_reg_known",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580670064,
      "name": "__mark_reg_known",
      "external": false,
      "loc": "kernel/bpf/verifier.c:554",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:mark_map_reg",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __mark_reg_known(struct bpf_reg_state * reg, u64 imm)
```

```json
{
  "name": "__mark_reg_known",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580703680,
      "name": "__mark_reg_known",
      "external": false,
      "loc": "kernel/bpf/verifier.c:801",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580703680,
      "name": "__mark_reg_known",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void __mark_reg_known(struct bpf_reg_state * reg, u64 imm)
```

```json
{
  "name": "__mark_reg_known",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580772992,
      "name": "__mark_reg_known",
      "external": false,
      "loc": "kernel/bpf/verifier.c:860",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580772992,
      "name": "__mark_reg_known",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void __mark_reg_known(struct bpf_reg_state * reg, u64 imm)
```

```json
{
  "name": "__mark_reg_known",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580823776,
      "name": "__mark_reg_known",
      "external": false,
      "loc": "kernel/bpf/verifier.c:861",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580823776,
      "name": "__mark_reg_known",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void __mark_reg_known(struct bpf_reg_state * reg, u64 imm)
```

```json
{
  "name": "__mark_reg_known",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581000345,
      "name": "__mark_reg_known",
      "external": false,
      "loc": "kernel/bpf/verifier.c:991",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_ld_imm",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_stack_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580951552,
      "name": "__mark_reg_known",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
void __mark_reg_known(struct bpf_reg_state * reg, u64 imm)
```

```json
{
  "name": "__mark_reg_known",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581002406,
      "name": "__mark_reg_known",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1032",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_ld_imm",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_stack_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580954976,
      "name": "__mark_reg_known",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
void __mark_reg_known(struct bpf_reg_state * reg, u64 imm)
```

```json
{
  "name": "__mark_reg_known",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580988598,
      "name": "__mark_reg_known",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1081",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_ld_imm",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:map_set_for_each_callback_args",
        "kernel/bpf/verifier.c:map_set_for_each_callback_args",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:mark_reg_stack_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580958496,
      "name": "__mark_reg_known",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
void __mark_reg_known(struct bpf_reg_state * reg, u64 imm)
```

```json
{
  "name": "__mark_reg_known",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581200858,
      "name": "__mark_reg_known",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1090",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:check_ld_imm",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:set_timer_callback_state",
        "kernel/bpf/verifier.c:set_timer_callback_state",
        "kernel/bpf/verifier.c:set_timer_callback_state",
        "kernel/bpf/verifier.c:map_set_for_each_callback_args",
        "kernel/bpf/verifier.c:map_set_for_each_callback_args",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:mark_reg_stack_read",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581163904,
      "name": "__mark_reg_known",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
void __mark_reg_known(struct bpf_reg_state * reg, u64 imm)
```

```json
{
  "name": "__mark_reg_known",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581443168,
      "name": "__mark_reg_known",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1317",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:check_ld_imm",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:set_find_vma_callback_state",
        "kernel/bpf/verifier.c:set_timer_callback_state",
        "kernel/bpf/verifier.c:set_timer_callback_state",
        "kernel/bpf/verifier.c:set_timer_callback_state",
        "kernel/bpf/verifier.c:map_set_for_each_callback_args",
        "kernel/bpf/verifier.c:map_set_for_each_callback_args",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:mark_reg_stack_read",
        "kernel/bpf/verifier.c:init_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581443168,
      "name": "__mark_reg_known",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void __mark_reg_known(struct bpf_reg_state * reg, u64 imm)
```

```json
{
  "name": "__mark_reg_known",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581797328,
      "name": "__mark_reg_known",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1518",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:check_ld_imm",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:set_user_ringbuf_callback_state",
        "kernel/bpf/verifier.c:set_find_vma_callback_state",
        "kernel/bpf/verifier.c:set_timer_callback_state",
        "kernel/bpf/verifier.c:set_timer_callback_state",
        "kernel/bpf/verifier.c:set_timer_callback_state",
        "kernel/bpf/verifier.c:map_set_for_each_callback_args",
        "kernel/bpf/verifier.c:map_set_for_each_callback_args",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:mark_reg_stack_read",
        "kernel/bpf/verifier.c:init_reg_state",
        "kernel/bpf/verifier.c:mark_stack_slots_dynptr",
        "kernel/bpf/verifier.c:mark_stack_slots_dynptr",
        "kernel/bpf/verifier.c:mark_stack_slots_dynptr",
        "kernel/bpf/verifier.c:mark_stack_slots_dynptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581797328,
      "name": "__mark_reg_known",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void __mark_reg_known(struct bpf_reg_state * reg, u64 imm)
```

```json
{
  "name": "__mark_reg_known",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581975936,
      "name": "__mark_reg_known",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1895",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:check_ld_imm",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:set_rbtree_add_callback_state",
        "kernel/bpf/verifier.c:set_rbtree_add_callback_state",
        "kernel/bpf/verifier.c:set_user_ringbuf_callback_state",
        "kernel/bpf/verifier.c:set_find_vma_callback_state",
        "kernel/bpf/verifier.c:set_timer_callback_state",
        "kernel/bpf/verifier.c:set_timer_callback_state",
        "kernel/bpf/verifier.c:set_timer_callback_state",
        "kernel/bpf/verifier.c:map_set_for_each_callback_args",
        "kernel/bpf/verifier.c:map_set_for_each_callback_args",
        "kernel/bpf/verifier.c:process_iter_arg",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:mark_reg_stack_read",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off",
        "kernel/bpf/verifier.c:init_reg_state",
        "kernel/bpf/verifier.c:mark_stack_slots_dynptr",
        "kernel/bpf/verifier.c:mark_stack_slots_dynptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581975936,
      "name": "__mark_reg_known",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void __mark_reg_known(struct bpf_reg_state * reg, u64 imm)
```

```json
{
  "name": "__mark_reg_known",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582099344,
      "name": "__mark_reg_known",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1745",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:check_ld_imm",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:set_rbtree_add_callback_state",
        "kernel/bpf/verifier.c:set_rbtree_add_callback_state",
        "kernel/bpf/verifier.c:set_user_ringbuf_callback_state",
        "kernel/bpf/verifier.c:set_find_vma_callback_state",
        "kernel/bpf/verifier.c:set_timer_callback_state",
        "kernel/bpf/verifier.c:set_timer_callback_state",
        "kernel/bpf/verifier.c:set_timer_callback_state",
        "kernel/bpf/verifier.c:map_set_for_each_callback_args",
        "kernel/bpf/verifier.c:map_set_for_each_callback_args",
        "kernel/bpf/verifier.c:process_iter_arg",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off",
        "kernel/bpf/verifier.c:mark_reg_stack_read",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off",
        "kernel/bpf/verifier.c:init_reg_state",
        "kernel/bpf/verifier.c:mark_stack_slots_dynptr",
        "kernel/bpf/verifier.c:mark_stack_slots_dynptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582099344,
      "name": "__mark_reg_known",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void __mark_reg_known(struct bpf_reg_state * reg, u64 imm)
```

```json
{
  "name": "__mark_reg_known",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492147616,
      "name": "__mark_reg_known",
      "external": false,
      "loc": "kernel/bpf/verifier.c:861",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492147616,
      "name": "__mark_reg_known",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void __mark_reg_known(struct bpf_reg_state * reg, u64 imm)
```

```json
{
  "name": "__mark_reg_known",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226044672,
      "name": "__mark_reg_known",
      "external": false,
      "loc": "kernel/bpf/verifier.c:861",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226044672,
      "name": "__mark_reg_known",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void __mark_reg_known(struct bpf_reg_state * reg, u64 imm)
```

```json
{
  "name": "__mark_reg_known",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285354720,
      "name": "__mark_reg_known",
      "external": false,
      "loc": "kernel/bpf/verifier.c:861",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285354720,
      "name": "__mark_reg_known",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __mark_reg_known(struct bpf_reg_state * reg, u64 imm)
```

```json
{
  "name": "__mark_reg_known",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272308204,
      "name": "__mark_reg_known",
      "external": false,
      "loc": "kernel/bpf/verifier.c:861",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272308204,
      "name": "__mark_reg_known",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void __mark_reg_known(struct bpf_reg_state * reg, u64 imm)
```

```json
{
  "name": "__mark_reg_known",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580792576,
      "name": "__mark_reg_known",
      "external": false,
      "loc": "kernel/bpf/verifier.c:861",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580792576,
      "name": "__mark_reg_known",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void __mark_reg_known(struct bpf_reg_state * reg, u64 imm)
```

```json
{
  "name": "__mark_reg_known",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580738752,
      "name": "__mark_reg_known",
      "external": false,
      "loc": "kernel/bpf/verifier.c:861",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580738752,
      "name": "__mark_reg_known",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void __mark_reg_known(struct bpf_reg_state * reg, u64 imm)
```

```json
{
  "name": "__mark_reg_known",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580783824,
      "name": "__mark_reg_known",
      "external": false,
      "loc": "kernel/bpf/verifier.c:861",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580783824,
      "name": "__mark_reg_known",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void __mark_reg_known(struct bpf_reg_state * reg, u64 imm)
```

```json
{
  "name": "__mark_reg_known",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580842208,
      "name": "__mark_reg_known",
      "external": false,
      "loc": "kernel/bpf/verifier.c:861",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580842208,
      "name": "__mark_reg_known",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void __mark_reg_known(struct bpf_reg_state * reg, u64 imm)
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
