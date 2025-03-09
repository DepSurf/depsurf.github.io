# Function: <code>tnum_const</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct tnum tnum_const(u64 value)
```

```json
{
  "name": "tnum_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580587792,
      "name": "tnum_const",
      "external": true,
      "loc": "kernel/bpf/tnum.c:15",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:mark_map_reg",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580587792,
      "name": "tnum_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct tnum tnum_const(u64 value)
```

```json
{
  "name": "tnum_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580683280,
      "name": "tnum_const",
      "external": true,
      "loc": "kernel/bpf/tnum.c:15",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:mark_map_reg",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580683280,
      "name": "tnum_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct tnum tnum_const(u64 value)
```

```json
{
  "name": "tnum_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580754192,
      "name": "tnum_const",
      "external": true,
      "loc": "kernel/bpf/tnum.c:15",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:__mark_reg_known"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580754192,
      "name": "tnum_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct tnum tnum_const(u64 value)
```

```json
{
  "name": "tnum_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580838000,
      "name": "tnum_const",
      "external": true,
      "loc": "kernel/bpf/tnum.c:16",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:__mark_reg_known"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580838000,
      "name": "tnum_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct tnum tnum_const(u64 value)
```

```json
{
  "name": "tnum_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580889024,
      "name": "tnum_const",
      "external": true,
      "loc": "kernel/bpf/tnum.c:16",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:__mark_reg_known"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580889024,
      "name": "tnum_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct tnum tnum_const(u64 value)
```

```json
{
  "name": "tnum_const",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581028912,
      "name": "tnum_const",
      "external": true,
      "loc": "kernel/bpf/tnum.c:16",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_return_code",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581028912,
      "name": "tnum_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct tnum tnum_const(u64 value)
```

```json
{
  "name": "tnum_const",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581036240,
      "name": "tnum_const",
      "external": true,
      "loc": "kernel/bpf/tnum.c:16",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_return_code",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581036240,
      "name": "tnum_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct tnum tnum_const(u64 value)
```

```json
{
  "name": "tnum_const",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581049632,
      "name": "tnum_const",
      "external": true,
      "loc": "kernel/bpf/tnum.c:16",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_return_code",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581049632,
      "name": "tnum_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct tnum tnum_const(u64 value)
```

```json
{
  "name": "tnum_const",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581274240,
      "name": "tnum_const",
      "external": true,
      "loc": "kernel/bpf/tnum.c:16",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_return_code",
        "kernel/bpf/verifier.c:check_return_code",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581274240,
      "name": "tnum_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct tnum tnum_const(u64 value)
```

```json
{
  "name": "tnum_const",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581567616,
      "name": "tnum_const",
      "external": true,
      "loc": "kernel/bpf/tnum.c:16",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_return_code",
        "kernel/bpf/verifier.c:check_return_code",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581567616,
      "name": "tnum_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct tnum tnum_const(u64 value)
```

```json
{
  "name": "tnum_const",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581943440,
      "name": "tnum_const",
      "external": true,
      "loc": "kernel/bpf/tnum.c:16",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_return_code",
        "kernel/bpf/verifier.c:check_return_code",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:__mark_reg_known"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581943440,
      "name": "tnum_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct tnum tnum_const(u64 value)
```

```json
{
  "name": "tnum_const",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582128960,
      "name": "tnum_const",
      "external": true,
      "loc": "kernel/bpf/tnum.c:16",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_return_code",
        "kernel/bpf/verifier.c:check_return_code",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:__mark_reg_known"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582128960,
      "name": "tnum_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct tnum tnum_const(u64 value)
```

```json
{
  "name": "tnum_const",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582272133,
      "name": "tnum_const",
      "external": true,
      "loc": "kernel/bpf/tnum.c:16",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_const_subreg"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:regs_refine_cond_op",
        "kernel/bpf/verifier.c:regs_refine_cond_op",
        "kernel/bpf/verifier.c:regs_refine_cond_op",
        "kernel/bpf/verifier.c:regs_refine_cond_op",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:coerce_reg_to_size_sx",
        "kernel/bpf/verifier.c:coerce_reg_to_size_sx",
        "kernel/bpf/verifier.c:coerce_reg_to_size_sx",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:__mark_reg_known"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582270544,
      "name": "tnum_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct tnum tnum_const(u64 value)
```

```json
{
  "name": "tnum_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492215136,
      "name": "tnum_const",
      "external": true,
      "loc": "kernel/bpf/tnum.c:16",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:__mark_reg_known"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492215136,
      "name": "tnum_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct tnum tnum_const(u64 value)
```

```json
{
  "name": "tnum_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226112196,
      "name": "tnum_const",
      "external": true,
      "loc": "kernel/bpf/tnum.c:16",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:__mark_reg_known"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226112196,
      "name": "tnum_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct tnum tnum_const(u64 value)
```

```json
{
  "name": "tnum_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285436640,
      "name": "tnum_const",
      "external": true,
      "loc": "kernel/bpf/tnum.c:16",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:__mark_reg_known"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285436640,
      "name": "tnum_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct tnum tnum_const(u64 value)
```

```json
{
  "name": "tnum_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272363090,
      "name": "tnum_const",
      "external": true,
      "loc": "kernel/bpf/tnum.c:16",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:__mark_reg_known"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272363090,
      "name": "tnum_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct tnum tnum_const(u64 value)
```

```json
{
  "name": "tnum_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580857824,
      "name": "tnum_const",
      "external": true,
      "loc": "kernel/bpf/tnum.c:16",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:__mark_reg_known"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580857824,
      "name": "tnum_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct tnum tnum_const(u64 value)
```

```json
{
  "name": "tnum_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580803952,
      "name": "tnum_const",
      "external": true,
      "loc": "kernel/bpf/tnum.c:16",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:__mark_reg_known"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580803952,
      "name": "tnum_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct tnum tnum_const(u64 value)
```

```json
{
  "name": "tnum_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580849072,
      "name": "tnum_const",
      "external": true,
      "loc": "kernel/bpf/tnum.c:16",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:__mark_reg_known"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580849072,
      "name": "tnum_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct tnum tnum_const(u64 value)
```

```json
{
  "name": "tnum_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580907392,
      "name": "tnum_const",
      "external": true,
      "loc": "kernel/bpf/tnum.c:16",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:__mark_reg_known"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580907392,
      "name": "tnum_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct tnum tnum_const(u64 value)
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
