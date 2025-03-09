# Function: <code>__reg_bound_offset</code>

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
void __reg_bound_offset(struct bpf_reg_state * reg)
```

```json
{
  "name": "__reg_bound_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580557376,
      "name": "__reg_bound_offset",
      "external": false,
      "loc": "kernel/bpf/verifier.c:540",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580557376,
      "name": "__reg_bound_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void __reg_bound_offset(struct bpf_reg_state * reg)
```

```json
{
  "name": "__reg_bound_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580642176,
      "name": "__reg_bound_offset",
      "external": false,
      "loc": "kernel/bpf/verifier.c:667",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580642176,
      "name": "__reg_bound_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void __reg_bound_offset(struct bpf_reg_state * reg)
```

```json
{
  "name": "__reg_bound_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580703904,
      "name": "__reg_bound_offset",
      "external": false,
      "loc": "kernel/bpf/verifier.c:915",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580703904,
      "name": "__reg_bound_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void __reg_bound_offset(struct bpf_reg_state * reg)
```

```json
{
  "name": "__reg_bound_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580773232,
      "name": "__reg_bound_offset",
      "external": false,
      "loc": "kernel/bpf/verifier.c:974",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580773232,
      "name": "__reg_bound_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void __reg_bound_offset(struct bpf_reg_state * reg)
```

```json
{
  "name": "__reg_bound_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580824016,
      "name": "__reg_bound_offset",
      "external": false,
      "loc": "kernel/bpf/verifier.c:975",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580824016,
      "name": "__reg_bound_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void __reg_bound_offset(struct bpf_reg_state * reg)
```

```json
{
  "name": "__reg_bound_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580952656,
      "name": "__reg_bound_offset",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1209",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:__reg_combine_64_into_32",
        "kernel/bpf/verifier.c:__reg_combine_32_into_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580952656,
      "name": "__reg_bound_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void __reg_bound_offset(struct bpf_reg_state * reg)
```

```json
{
  "name": "__reg_bound_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580951904,
      "name": "__reg_bound_offset",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1241",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:__reg_combine_64_into_32",
        "kernel/bpf/verifier.c:__reg_combine_32_into_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580951904,
      "name": "__reg_bound_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void __reg_bound_offset(struct bpf_reg_state * reg)
```

```json
{
  "name": "__reg_bound_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580955520,
      "name": "__reg_bound_offset",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1335",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:__reg_combine_64_into_32",
        "kernel/bpf/verifier.c:__reg_combine_32_into_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580955520,
      "name": "__reg_bound_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void __reg_bound_offset(struct bpf_reg_state * reg)
```

```json
{
  "name": "__reg_bound_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581160400,
      "name": "__reg_bound_offset",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1349",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:check_alu_op",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:__reg_combine_64_into_32",
        "kernel/bpf/verifier.c:__reg_combine_32_into_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581160400,
      "name": "__reg_bound_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__reg_bound_offset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581449594,
      "name": "__reg_bound_offset",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1553",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:reg_bounds_sync"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__reg_bound_offset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581803354,
      "name": "__reg_bound_offset",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1767",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:reg_bounds_sync"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__reg_bound_offset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582021653,
      "name": "__reg_bound_offset",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2164",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:reg_bounds_sync"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__reg_bound_offset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582150713,
      "name": "__reg_bound_offset",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2164",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:reg_bounds_sync"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void __reg_bound_offset(struct bpf_reg_state * reg)
```

```json
{
  "name": "__reg_bound_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492147832,
      "name": "__reg_bound_offset",
      "external": false,
      "loc": "kernel/bpf/verifier.c:975",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:check_cond_jmp_op",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492147832,
      "name": "__reg_bound_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void __reg_bound_offset(struct bpf_reg_state * reg)
```

```json
{
  "name": "__reg_bound_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226045276,
      "name": "__reg_bound_offset",
      "external": false,
      "loc": "kernel/bpf/verifier.c:975",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226045276,
      "name": "__reg_bound_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void __reg_bound_offset(struct bpf_reg_state * reg)
```

```json
{
  "name": "__reg_bound_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285355056,
      "name": "__reg_bound_offset",
      "external": false,
      "loc": "kernel/bpf/verifier.c:975",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285355056,
      "name": "__reg_bound_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void __reg_bound_offset(struct bpf_reg_state * reg)
```

```json
{
  "name": "__reg_bound_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272308412,
      "name": "__reg_bound_offset",
      "external": false,
      "loc": "kernel/bpf/verifier.c:975",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272308412,
      "name": "__reg_bound_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void __reg_bound_offset(struct bpf_reg_state * reg)
```

```json
{
  "name": "__reg_bound_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580792816,
      "name": "__reg_bound_offset",
      "external": false,
      "loc": "kernel/bpf/verifier.c:975",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580792816,
      "name": "__reg_bound_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void __reg_bound_offset(struct bpf_reg_state * reg)
```

```json
{
  "name": "__reg_bound_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580738992,
      "name": "__reg_bound_offset",
      "external": false,
      "loc": "kernel/bpf/verifier.c:975",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580738992,
      "name": "__reg_bound_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void __reg_bound_offset(struct bpf_reg_state * reg)
```

```json
{
  "name": "__reg_bound_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580784064,
      "name": "__reg_bound_offset",
      "external": false,
      "loc": "kernel/bpf/verifier.c:975",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580784064,
      "name": "__reg_bound_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void __reg_bound_offset(struct bpf_reg_state * reg)
```

```json
{
  "name": "__reg_bound_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580842448,
      "name": "__reg_bound_offset",
      "external": false,
      "loc": "kernel/bpf/verifier.c:975",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:__reg_combine_min_max",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:reg_set_min_max_inv",
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580842448,
      "name": "__reg_bound_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void __reg_bound_offset(struct bpf_reg_state * reg)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void __reg_bound_offset(struct bpf_reg_state * reg)
```
</details>
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
