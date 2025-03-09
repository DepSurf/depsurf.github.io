# Function: <code>__mark_reg_unknown</code>

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
  "name": "__mark_reg_unknown",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580581012,
      "name": "__mark_reg_unknown",
      "external": false,
      "loc": "kernel/bpf/verifier.c:557",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals"
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
  "name": "__mark_reg_unknown",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580651681,
      "name": "__mark_reg_unknown",
      "external": false,
      "loc": "kernel/bpf/verifier.c:684",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call"
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
void __mark_reg_unknown(struct bpf_reg_state * reg)
```

```json
{
  "name": "__mark_reg_unknown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580703568,
      "name": "__mark_reg_unknown",
      "external": false,
      "loc": "kernel/bpf/verifier.c:932",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580703568,
      "name": "__mark_reg_unknown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void __mark_reg_unknown(struct bpf_reg_state * reg)
```

```json
{
  "name": "__mark_reg_unknown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580772864,
      "name": "__mark_reg_unknown",
      "external": false,
      "loc": "kernel/bpf/verifier.c:991",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580772864,
      "name": "__mark_reg_unknown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mark_reg_unknown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580826848,
      "name": "__mark_reg_unknown",
      "external": false,
      "loc": "kernel/bpf/verifier.c:992",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580826848,
      "name": "__mark_reg_unknown.isra.0",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __mark_reg_unknown(const struct bpf_verifier_env * env, struct bpf_reg_state * reg)
```

```json
{
  "name": "__mark_reg_unknown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580951136,
      "name": "__mark_reg_unknown",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1305",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:clean_func_state",
        "kernel/bpf/verifier.c:clean_func_state",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:release_reg_references",
        "kernel/bpf/verifier.c:__clear_all_pkt_pointers",
        "kernel/bpf/verifier.c:check_stack_boundary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580951136,
      "name": "__mark_reg_unknown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
void __mark_reg_unknown(const struct bpf_verifier_env * env, struct bpf_reg_state * reg)
```

```json
{
  "name": "__mark_reg_unknown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580950336,
      "name": "__mark_reg_unknown",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1335",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:clean_func_state",
        "kernel/bpf/verifier.c:clean_func_state",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:release_reg_references",
        "kernel/bpf/verifier.c:__clear_all_pkt_pointers",
        "kernel/bpf/verifier.c:check_stack_boundary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580950336,
      "name": "__mark_reg_unknown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
void __mark_reg_unknown(const struct bpf_verifier_env * env, struct bpf_reg_state * reg)
```

```json
{
  "name": "__mark_reg_unknown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580954640,
      "name": "__mark_reg_unknown",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1427",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:clean_live_states",
        "kernel/bpf/verifier.c:clean_live_states",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:map_set_for_each_callback_args",
        "kernel/bpf/verifier.c:check_stack_range_initialized"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580954640,
      "name": "__mark_reg_unknown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
void __mark_reg_unknown(const struct bpf_verifier_env * env, struct bpf_reg_state * reg)
```

```json
{
  "name": "__mark_reg_unknown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mark_reg_unknown",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1447",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:clean_live_states",
        "kernel/bpf/verifier.c:clean_live_states",
        "kernel/bpf/verifier.c:check_ld_abs",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:set_timer_callback_state",
        "kernel/bpf/verifier.c:set_timer_callback_state",
        "kernel/bpf/verifier.c:map_set_for_each_callback_args",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:check_stack_range_initialized"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581162528,
      "name": "__mark_reg_unknown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071592180712,
      "name": "__mark_reg_unknown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
void __mark_reg_unknown(const struct bpf_verifier_env * env, struct bpf_reg_state * reg)
```

```json
{
  "name": "__mark_reg_unknown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mark_reg_unknown",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1650",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:clean_live_states",
        "kernel/bpf/verifier.c:clean_live_states",
        "kernel/bpf/verifier.c:check_ld_abs",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:set_find_vma_callback_state",
        "kernel/bpf/verifier.c:set_find_vma_callback_state",
        "kernel/bpf/verifier.c:set_timer_callback_state",
        "kernel/bpf/verifier.c:set_timer_callback_state",
        "kernel/bpf/verifier.c:set_loop_callback_state",
        "kernel/bpf/verifier.c:set_loop_callback_state",
        "kernel/bpf/verifier.c:set_loop_callback_state",
        "kernel/bpf/verifier.c:map_set_for_each_callback_args",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:release_reference",
        "kernel/bpf/verifier.c:check_stack_range_initialized"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581440624,
      "name": "__mark_reg_unknown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    },
    {
      "addr": 18446744071593954746,
      "name": "__mark_reg_unknown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
void __mark_reg_unknown(const struct bpf_verifier_env * env, struct bpf_reg_state * reg)
```

```json
{
  "name": "__mark_reg_unknown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mark_reg_unknown",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1864",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:check_ld_abs",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:set_user_ringbuf_callback_state",
        "kernel/bpf/verifier.c:set_user_ringbuf_callback_state",
        "kernel/bpf/verifier.c:set_user_ringbuf_callback_state",
        "kernel/bpf/verifier.c:set_user_ringbuf_callback_state",
        "kernel/bpf/verifier.c:set_find_vma_callback_state",
        "kernel/bpf/verifier.c:set_find_vma_callback_state",
        "kernel/bpf/verifier.c:set_timer_callback_state",
        "kernel/bpf/verifier.c:set_timer_callback_state",
        "kernel/bpf/verifier.c:set_loop_callback_state",
        "kernel/bpf/verifier.c:set_loop_callback_state",
        "kernel/bpf/verifier.c:set_loop_callback_state",
        "kernel/bpf/verifier.c:map_set_for_each_callback_args",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:check_stack_range_initialized",
        "kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot",
        "kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581792160,
      "name": "__mark_reg_unknown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071596014165,
      "name": "__mark_reg_unknown.cold",
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
void __mark_reg_unknown(const struct bpf_verifier_env * env, struct bpf_reg_state * reg)
```

```json
{
  "name": "__mark_reg_unknown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mark_reg_unknown",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2261",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:clean_live_states",
        "kernel/bpf/verifier.c:clean_live_states",
        "kernel/bpf/verifier.c:check_ld_abs",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:set_rbtree_add_callback_state",
        "kernel/bpf/verifier.c:set_rbtree_add_callback_state",
        "kernel/bpf/verifier.c:set_rbtree_add_callback_state",
        "kernel/bpf/verifier.c:set_user_ringbuf_callback_state",
        "kernel/bpf/verifier.c:set_user_ringbuf_callback_state",
        "kernel/bpf/verifier.c:set_user_ringbuf_callback_state",
        "kernel/bpf/verifier.c:set_user_ringbuf_callback_state",
        "kernel/bpf/verifier.c:set_find_vma_callback_state",
        "kernel/bpf/verifier.c:set_find_vma_callback_state",
        "kernel/bpf/verifier.c:set_timer_callback_state",
        "kernel/bpf/verifier.c:set_timer_callback_state",
        "kernel/bpf/verifier.c:set_loop_callback_state",
        "kernel/bpf/verifier.c:set_loop_callback_state",
        "kernel/bpf/verifier.c:set_loop_callback_state",
        "kernel/bpf/verifier.c:map_set_for_each_callback_args",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:clear_all_pkt_pointers",
        "kernel/bpf/verifier.c:clear_all_pkt_pointers",
        "kernel/bpf/verifier.c:clear_all_pkt_pointers",
        "kernel/bpf/verifier.c:clear_all_pkt_pointers",
        "kernel/bpf/verifier.c:process_iter_arg",
        "kernel/bpf/verifier.c:process_spin_lock",
        "kernel/bpf/verifier.c:process_spin_lock",
        "kernel/bpf/verifier.c:process_spin_lock",
        "kernel/bpf/verifier.c:process_spin_lock",
        "kernel/bpf/verifier.c:check_stack_range_initialized",
        "kernel/bpf/verifier.c:mark_reg_stack_read",
        "kernel/bpf/verifier.c:mark_reg_stack_read",
        "kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot",
        "kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot",
        "kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot",
        "kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot",
        "kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot",
        "kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot",
        "kernel/bpf/verifier.c:invalidate_dynptr",
        "kernel/bpf/verifier.c:invalidate_dynptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581961296,
      "name": "__mark_reg_unknown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071596534419,
      "name": "__mark_reg_unknown.cold",
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
void __mark_reg_unknown(const struct bpf_verifier_env * env, struct bpf_reg_state * reg)
```

```json
{
  "name": "__mark_reg_unknown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mark_reg_unknown",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2267",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:check_ld_abs",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:set_rbtree_add_callback_state",
        "kernel/bpf/verifier.c:set_rbtree_add_callback_state",
        "kernel/bpf/verifier.c:set_rbtree_add_callback_state",
        "kernel/bpf/verifier.c:set_user_ringbuf_callback_state",
        "kernel/bpf/verifier.c:set_user_ringbuf_callback_state",
        "kernel/bpf/verifier.c:set_user_ringbuf_callback_state",
        "kernel/bpf/verifier.c:set_user_ringbuf_callback_state",
        "kernel/bpf/verifier.c:set_find_vma_callback_state",
        "kernel/bpf/verifier.c:set_find_vma_callback_state",
        "kernel/bpf/verifier.c:set_timer_callback_state",
        "kernel/bpf/verifier.c:set_timer_callback_state",
        "kernel/bpf/verifier.c:set_loop_callback_state",
        "kernel/bpf/verifier.c:set_loop_callback_state",
        "kernel/bpf/verifier.c:set_loop_callback_state",
        "kernel/bpf/verifier.c:map_set_for_each_callback_args",
        "kernel/bpf/verifier.c:invalidate_non_owning_refs",
        "kernel/bpf/verifier.c:invalidate_non_owning_refs",
        "kernel/bpf/verifier.c:invalidate_non_owning_refs",
        "kernel/bpf/verifier.c:invalidate_non_owning_refs",
        "kernel/bpf/verifier.c:clear_all_pkt_pointers",
        "kernel/bpf/verifier.c:clear_all_pkt_pointers",
        "kernel/bpf/verifier.c:clear_all_pkt_pointers",
        "kernel/bpf/verifier.c:clear_all_pkt_pointers",
        "kernel/bpf/verifier.c:process_iter_arg",
        "kernel/bpf/verifier.c:check_stack_range_initialized",
        "kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot",
        "kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot",
        "kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot",
        "kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot",
        "kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot",
        "kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot",
        "kernel/bpf/verifier.c:invalidate_dynptr",
        "kernel/bpf/verifier.c:invalidate_dynptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582089184,
      "name": "__mark_reg_unknown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071597435639,
      "name": "__mark_reg_unknown.cold",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__mark_reg_unknown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492149624,
      "name": "__mark_reg_unknown",
      "external": false,
      "loc": "kernel/bpf/verifier.c:992",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492149624,
      "name": "__mark_reg_unknown.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void __mark_reg_unknown(const struct bpf_verifier_env * env, struct bpf_reg_state * reg)
```

```json
{
  "name": "__mark_reg_unknown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226044512,
      "name": "__mark_reg_unknown",
      "external": false,
      "loc": "kernel/bpf/verifier.c:992",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226044512,
      "name": "__mark_reg_unknown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__mark_reg_unknown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285358736,
      "name": "__mark_reg_unknown",
      "external": false,
      "loc": "kernel/bpf/verifier.c:992",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285358736,
      "name": "__mark_reg_unknown.isra.0",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__mark_reg_unknown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272312486,
      "name": "__mark_reg_unknown",
      "external": false,
      "loc": "kernel/bpf/verifier.c:992",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272312486,
      "name": "__mark_reg_unknown.isra.0",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mark_reg_unknown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580795648,
      "name": "__mark_reg_unknown",
      "external": false,
      "loc": "kernel/bpf/verifier.c:992",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580795648,
      "name": "__mark_reg_unknown.isra.0",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mark_reg_unknown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580741824,
      "name": "__mark_reg_unknown",
      "external": false,
      "loc": "kernel/bpf/verifier.c:992",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580741824,
      "name": "__mark_reg_unknown.isra.0",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mark_reg_unknown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580786896,
      "name": "__mark_reg_unknown",
      "external": false,
      "loc": "kernel/bpf/verifier.c:992",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580786896,
      "name": "__mark_reg_unknown.isra.0",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mark_reg_unknown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580845280,
      "name": "__mark_reg_unknown",
      "external": false,
      "loc": "kernel/bpf/verifier.c:992",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580845280,
      "name": "__mark_reg_unknown.isra.0",
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void __mark_reg_unknown(struct bpf_reg_state * reg)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
void __mark_reg_unknown(struct bpf_reg_state * reg)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void __mark_reg_unknown(const struct bpf_verifier_env * env, struct bpf_reg_state * reg)
```
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void __mark_reg_unknown(const struct bpf_verifier_env * env, struct bpf_reg_state * reg)
```
</details>
</li>
</ul>
