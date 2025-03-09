# Function: <code>check_map_access</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_map_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580369259,
      "name": "check_map_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:636",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_map_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580428023,
      "name": "check_map_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:642",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_map_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580478676,
      "name": "check_map_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:625",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_mem_access",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int check_map_access(struct bpf_verifier_env * env, u32 regno, int off, int size)
```

```json
{
  "name": "check_map_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580499776,
      "name": "check_map_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:647",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_map_access_adj",
        "kernel/bpf/verifier.c:check_map_access_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580499776,
      "name": "check_map_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
int check_map_access(struct bpf_verifier_env * env, u32 regno, int off, int size, bool zero_size_allowed)
```

```json
{
  "name": "check_map_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580556208,
      "name": "check_map_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:817",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580556208,
      "name": "check_map_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
int check_map_access(struct bpf_verifier_env * env, u32 regno, int off, int size, bool zero_size_allowed)
```

```json
{
  "name": "check_map_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580653440,
      "name": "check_map_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1253",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580653440,
      "name": "check_map_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
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
int check_map_access(struct bpf_verifier_env * env, u32 regno, int off, int size, bool zero_size_allowed)
```

```json
{
  "name": "check_map_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580712112,
      "name": "check_map_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1435",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580712112,
      "name": "check_map_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
int check_map_access(struct bpf_verifier_env * env, u32 regno, int off, int size, bool zero_size_allowed)
```

```json
{
  "name": "check_map_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580791776,
      "name": "check_map_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2167",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580791776,
      "name": "check_map_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int check_map_access(struct bpf_verifier_env * env, u32 regno, int off, int size, bool zero_size_allowed)
```

```json
{
  "name": "check_map_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580842800,
      "name": "check_map_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2168",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580842800,
      "name": "check_map_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int check_map_access(struct bpf_verifier_env * env, u32 regno, int off, int size, bool zero_size_allowed)
```

```json
{
  "name": "check_map_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580993664,
      "name": "check_map_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2572",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580993664,
      "name": "check_map_access",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int check_map_access(struct bpf_verifier_env * env, u32 regno, int off, int size, bool zero_size_allowed)
```

```json
{
  "name": "check_map_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580975984,
      "name": "check_map_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2645",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580975984,
      "name": "check_map_access",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int check_map_access(struct bpf_verifier_env * env, u32 regno, int off, int size, bool zero_size_allowed)
```

```json
{
  "name": "check_map_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580969104,
      "name": "check_map_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3190",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:sanitize_check_bounds",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580969104,
      "name": "check_map_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
int check_map_access(struct bpf_verifier_env * env, u32 regno, int off, int size, bool zero_size_allowed)
```

```json
{
  "name": "check_map_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581178336,
      "name": "check_map_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3256",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:sanitize_check_bounds",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581178336,
      "name": "check_map_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
int check_map_access(struct bpf_verifier_env * env, u32 regno, int off, int size, bool zero_size_allowed, enum bpf_access_src src)
```

```json
{
  "name": "check_map_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581456576,
      "name": "check_map_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3781",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:sanitize_check_bounds",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581456576,
      "name": "check_map_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 631
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
int check_map_access(struct bpf_verifier_env * env, u32 regno, int off, int size, bool zero_size_allowed, enum bpf_access_src src)
```

```json
{
  "name": "check_map_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581818704,
      "name": "check_map_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4223",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:sanitize_check_bounds",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581818704,
      "name": "check_map_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 697
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
int check_map_access(struct bpf_verifier_env * env, u32 regno, int off, int size, bool zero_size_allowed, enum bpf_access_src src)
```

```json
{
  "name": "check_map_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582029184,
      "name": "check_map_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5143",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:sanitize_check_bounds",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582029184,
      "name": "check_map_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 759
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
int check_map_access(struct bpf_verifier_env * env, u32 regno, int off, int size, bool zero_size_allowed, enum bpf_access_src src)
```

```json
{
  "name": "check_map_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582177488,
      "name": "check_map_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5344",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:sanitize_check_bounds",
        "kernel/bpf/verifier.c:check_reg_const_str",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582177488,
      "name": "check_map_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 794
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
int check_map_access(struct bpf_verifier_env * env, u32 regno, int off, int size, bool zero_size_allowed)
```

```json
{
  "name": "check_map_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492168600,
      "name": "check_map_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2168",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492168600,
      "name": "check_map_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
int check_map_access(struct bpf_verifier_env * env, u32 regno, int off, int size, bool zero_size_allowed)
```

```json
{
  "name": "check_map_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226064372,
      "name": "check_map_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2168",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226064372,
      "name": "check_map_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
int check_map_access(struct bpf_verifier_env * env, u32 regno, int off, int size, bool zero_size_allowed)
```

```json
{
  "name": "check_map_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285380512,
      "name": "check_map_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2168",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285380512,
      "name": "check_map_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
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
int check_map_access(struct bpf_verifier_env * env, u32 regno, int off, int size, bool zero_size_allowed)
```

```json
{
  "name": "check_map_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272325466,
      "name": "check_map_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2168",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272325466,
      "name": "check_map_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
int check_map_access(struct bpf_verifier_env * env, u32 regno, int off, int size, bool zero_size_allowed)
```

```json
{
  "name": "check_map_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580811600,
      "name": "check_map_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2168",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580811600,
      "name": "check_map_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int check_map_access(struct bpf_verifier_env * env, u32 regno, int off, int size, bool zero_size_allowed)
```

```json
{
  "name": "check_map_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580757776,
      "name": "check_map_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2168",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580757776,
      "name": "check_map_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int check_map_access(struct bpf_verifier_env * env, u32 regno, int off, int size, bool zero_size_allowed)
```

```json
{
  "name": "check_map_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580802848,
      "name": "check_map_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2168",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580802848,
      "name": "check_map_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int check_map_access(struct bpf_verifier_env * env, u32 regno, int off, int size, bool zero_size_allowed)
```

```json
{
  "name": "check_map_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580861232,
      "name": "check_map_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2168",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580861232,
      "name": "check_map_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int check_map_access(struct bpf_verifier_env * env, u32 regno, int off, int size)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool zero_size_allowed</code>
</li>
</ul>
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
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum bpf_access_src src</code>
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
