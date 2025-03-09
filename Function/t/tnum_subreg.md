# Function: <code>tnum_subreg</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct tnum tnum_subreg(struct tnum a)
```

```json
{
  "name": "tnum_subreg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581029696,
      "name": "tnum_subreg",
      "external": true,
      "loc": "kernel/bpf/tnum.c:198",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:is_branch32_taken",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:scalar32_min_max_or",
        "kernel/bpf/verifier.c:scalar32_min_max_or",
        "kernel/bpf/verifier.c:scalar32_min_max_or",
        "kernel/bpf/verifier.c:scalar32_min_max_and",
        "kernel/bpf/verifier.c:scalar32_min_max_and",
        "kernel/bpf/verifier.c:scalar32_min_max_and",
        "kernel/bpf/verifier.c:__reg_bound_offset",
        "kernel/bpf/verifier.c:__update_reg32_bounds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581029696,
      "name": "tnum_subreg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
struct tnum tnum_subreg(struct tnum a)
```

```json
{
  "name": "tnum_subreg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581037024,
      "name": "tnum_subreg",
      "external": true,
      "loc": "kernel/bpf/tnum.c:198",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:is_branch32_taken",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:scalar32_min_max_xor",
        "kernel/bpf/verifier.c:scalar32_min_max_xor",
        "kernel/bpf/verifier.c:scalar32_min_max_xor",
        "kernel/bpf/verifier.c:scalar32_min_max_or",
        "kernel/bpf/verifier.c:scalar32_min_max_or",
        "kernel/bpf/verifier.c:scalar32_min_max_or",
        "kernel/bpf/verifier.c:scalar32_min_max_and",
        "kernel/bpf/verifier.c:scalar32_min_max_and",
        "kernel/bpf/verifier.c:scalar32_min_max_and",
        "kernel/bpf/verifier.c:__reg_bound_offset",
        "kernel/bpf/verifier.c:__update_reg32_bounds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581037024,
      "name": "tnum_subreg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
struct tnum tnum_subreg(struct tnum a)
```

```json
{
  "name": "tnum_subreg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581050416,
      "name": "tnum_subreg",
      "external": true,
      "loc": "kernel/bpf/tnum.c:198",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:is_branch32_taken",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:__reg_bound_offset",
        "kernel/bpf/verifier.c:__update_reg32_bounds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581050416,
      "name": "tnum_subreg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
struct tnum tnum_subreg(struct tnum a)
```

```json
{
  "name": "tnum_subreg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581275184,
      "name": "tnum_subreg",
      "external": true,
      "loc": "kernel/bpf/tnum.c:201",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:is_branch32_taken",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:__reg_bound_offset",
        "kernel/bpf/verifier.c:__update_reg32_bounds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581275184,
      "name": "tnum_subreg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
struct tnum tnum_subreg(struct tnum a)
```

```json
{
  "name": "tnum_subreg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581568784,
      "name": "tnum_subreg",
      "external": true,
      "loc": "kernel/bpf/tnum.c:201",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:is_branch32_taken",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:reg_bounds_sync",
        "kernel/bpf/verifier.c:__update_reg32_bounds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581568784,
      "name": "tnum_subreg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct tnum tnum_subreg(struct tnum a)
```

```json
{
  "name": "tnum_subreg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581944864,
      "name": "tnum_subreg",
      "external": true,
      "loc": "kernel/bpf/tnum.c:201",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:is_branch32_taken",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:reg_bounds_sync",
        "kernel/bpf/verifier.c:__update_reg32_bounds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581944864,
      "name": "tnum_subreg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct tnum tnum_subreg(struct tnum a)
```

```json
{
  "name": "tnum_subreg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582130352,
      "name": "tnum_subreg",
      "external": true,
      "loc": "kernel/bpf/tnum.c:201",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:is_branch32_taken",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:reg_bounds_sync",
        "kernel/bpf/verifier.c:__update_reg32_bounds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582130352,
      "name": "tnum_subreg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct tnum tnum_subreg(struct tnum a)
```

```json
{
  "name": "tnum_subreg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582272053,
      "name": "tnum_subreg",
      "external": true,
      "loc": "kernel/bpf/tnum.c:195",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_with_subreg"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:regs_refine_cond_op",
        "kernel/bpf/verifier.c:regs_refine_cond_op",
        "kernel/bpf/verifier.c:regs_refine_cond_op",
        "kernel/bpf/verifier.c:regs_refine_cond_op",
        "kernel/bpf/verifier.c:regs_refine_cond_op",
        "kernel/bpf/verifier.c:regs_refine_cond_op",
        "kernel/bpf/verifier.c:regs_refine_cond_op",
        "kernel/bpf/verifier.c:regs_refine_cond_op",
        "kernel/bpf/verifier.c:regs_refine_cond_op",
        "kernel/bpf/verifier.c:regs_refine_cond_op",
        "kernel/bpf/verifier.c:regs_refine_cond_op",
        "kernel/bpf/verifier.c:regs_refine_cond_op",
        "kernel/bpf/verifier.c:regs_refine_cond_op",
        "kernel/bpf/verifier.c:is_branch_taken",
        "kernel/bpf/verifier.c:is_branch_taken",
        "kernel/bpf/verifier.c:is_branch_taken",
        "kernel/bpf/verifier.c:is_scalar_branch_taken",
        "kernel/bpf/verifier.c:is_scalar_branch_taken",
        "kernel/bpf/verifier.c:is_scalar_branch_taken",
        "kernel/bpf/verifier.c:is_scalar_branch_taken",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:reg_bounds_sanity_check",
        "kernel/bpf/verifier.c:reg_bounds_sanity_check",
        "kernel/bpf/verifier.c:reg_bounds_sync",
        "kernel/bpf/verifier.c:__update_reg32_bounds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582271936,
      "name": "tnum_subreg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct tnum tnum_subreg(struct tnum a)
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
