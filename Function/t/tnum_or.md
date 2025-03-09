# Function: <code>tnum_or</code>

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
struct tnum tnum_or(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580588112,
      "name": "tnum_or",
      "external": true,
      "loc": "kernel/bpf/tnum.c:80",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580588112,
      "name": "tnum_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct tnum tnum_or(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580683600,
      "name": "tnum_or",
      "external": true,
      "loc": "kernel/bpf/tnum.c:90",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580683600,
      "name": "tnum_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct tnum tnum_or(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580754512,
      "name": "tnum_or",
      "external": true,
      "loc": "kernel/bpf/tnum.c:90",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580754512,
      "name": "tnum_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct tnum tnum_or(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580838320,
      "name": "tnum_or",
      "external": true,
      "loc": "kernel/bpf/tnum.c:91",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580838320,
      "name": "tnum_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct tnum tnum_or(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580889360,
      "name": "tnum_or",
      "external": true,
      "loc": "kernel/bpf/tnum.c:96",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580889360,
      "name": "tnum_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct tnum tnum_or(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_or",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581029749,
      "name": "tnum_or",
      "external": true,
      "loc": "kernel/bpf/tnum.c:96",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_const_subreg"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:__reg_bound_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581029248,
      "name": "tnum_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct tnum tnum_or(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_or",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581037077,
      "name": "tnum_or",
      "external": true,
      "loc": "kernel/bpf/tnum.c:96",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_const_subreg"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:__reg_bound_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581036576,
      "name": "tnum_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct tnum tnum_or(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_or",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581050469,
      "name": "tnum_or",
      "external": true,
      "loc": "kernel/bpf/tnum.c:96",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_const_subreg"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:__reg_bound_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581049968,
      "name": "tnum_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct tnum tnum_or(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_or",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581275237,
      "name": "tnum_or",
      "external": true,
      "loc": "kernel/bpf/tnum.c:96",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_const_subreg"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:__reg_bound_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581274720,
      "name": "tnum_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct tnum tnum_or(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_or",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581568869,
      "name": "tnum_or",
      "external": true,
      "loc": "kernel/bpf/tnum.c:96",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_const_subreg"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:reg_bounds_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581568208,
      "name": "tnum_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct tnum tnum_or(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_or",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581944981,
      "name": "tnum_or",
      "external": true,
      "loc": "kernel/bpf/tnum.c:96",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_const_subreg"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:reg_bounds_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581944160,
      "name": "tnum_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct tnum tnum_or(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_or",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582130469,
      "name": "tnum_or",
      "external": true,
      "loc": "kernel/bpf/tnum.c:96",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_const_subreg"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:reg_bounds_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582129648,
      "name": "tnum_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct tnum tnum_or(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_or",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582272053,
      "name": "tnum_or",
      "external": true,
      "loc": "kernel/bpf/tnum.c:96",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_with_subreg"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:regs_refine_cond_op",
        "kernel/bpf/verifier.c:regs_refine_cond_op",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:reg_bounds_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582271232,
      "name": "tnum_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct tnum tnum_or(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492215792,
      "name": "tnum_or",
      "external": true,
      "loc": "kernel/bpf/tnum.c:96",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492215792,
      "name": "tnum_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct tnum tnum_or(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226113216,
      "name": "tnum_or",
      "external": true,
      "loc": "kernel/bpf/tnum.c:96",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226113216,
      "name": "tnum_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct tnum tnum_or(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285437008,
      "name": "tnum_or",
      "external": true,
      "loc": "kernel/bpf/tnum.c:96",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285437008,
      "name": "tnum_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct tnum tnum_or(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272363818,
      "name": "tnum_or",
      "external": true,
      "loc": "kernel/bpf/tnum.c:96",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272363818,
      "name": "tnum_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct tnum tnum_or(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580858160,
      "name": "tnum_or",
      "external": true,
      "loc": "kernel/bpf/tnum.c:96",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580858160,
      "name": "tnum_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct tnum tnum_or(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580804288,
      "name": "tnum_or",
      "external": true,
      "loc": "kernel/bpf/tnum.c:96",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580804288,
      "name": "tnum_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct tnum tnum_or(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580849408,
      "name": "tnum_or",
      "external": true,
      "loc": "kernel/bpf/tnum.c:96",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580849408,
      "name": "tnum_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct tnum tnum_or(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580907728,
      "name": "tnum_or",
      "external": true,
      "loc": "kernel/bpf/tnum.c:96",
      "file": "kernel/bpf/tnum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580907728,
      "name": "tnum_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct tnum tnum_or(struct tnum a, struct tnum b)
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
