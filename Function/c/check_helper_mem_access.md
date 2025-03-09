# Function: <code>check_helper_mem_access</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int check_helper_mem_access(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_helper_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580505760,
      "name": "check_helper_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1070",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580505760,
      "name": "check_helper_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
int check_helper_mem_access(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_helper_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580557136,
      "name": "check_helper_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1366",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580557136,
      "name": "check_helper_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
int check_helper_mem_access(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_helper_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580657360,
      "name": "check_helper_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1916",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580657360,
      "name": "check_helper_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 742
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
int check_helper_mem_access(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_helper_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580721696,
      "name": "check_helper_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2178",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580721696,
      "name": "check_helper_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
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
int check_helper_mem_access(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_helper_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580799344,
      "name": "check_helper_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3087",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580799344,
      "name": "check_helper_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1209
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
int check_helper_mem_access(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_helper_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580850448,
      "name": "check_helper_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3088",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580850448,
      "name": "check_helper_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1246
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
int check_helper_mem_access(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_helper_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580993824,
      "name": "check_helper_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3584",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580993824,
      "name": "check_helper_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
int check_helper_mem_access(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_helper_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581004640,
      "name": "check_helper_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3803",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581004640,
      "name": "check_helper_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
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
int check_helper_mem_access(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_helper_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581011136,
      "name": "check_helper_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4476",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_reg",
        "kernel/bpf/verifier.c:check_mem_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581011136,
      "name": "check_helper_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
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
int check_helper_mem_access(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_helper_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_helper_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4590",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_reg",
        "kernel/bpf/verifier.c:check_mem_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581226976,
      "name": "check_helper_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 662
    },
    {
      "addr": 18446744071592184247,
      "name": "check_helper_mem_access.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int check_helper_mem_access(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_helper_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_helper_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5168",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_reg",
        "kernel/bpf/verifier.c:check_mem_reg",
        "kernel/bpf/verifier.c:check_mem_reg",
        "kernel/bpf/verifier.c:check_mem_reg",
        "kernel/bpf/verifier.c:check_mem_size_reg",
        "kernel/bpf/verifier.c:check_mem_size_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581460464,
      "name": "check_helper_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 913
    },
    {
      "addr": 18446744071593955284,
      "name": "check_helper_mem_access.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int check_helper_mem_access(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_helper_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_helper_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5699",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_reg",
        "kernel/bpf/verifier.c:check_mem_reg",
        "kernel/bpf/verifier.c:check_mem_reg",
        "kernel/bpf/verifier.c:check_mem_reg",
        "kernel/bpf/verifier.c:check_mem_size_reg",
        "kernel/bpf/verifier.c:check_mem_size_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581893392,
      "name": "check_helper_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1034
    },
    {
      "addr": 18446744071596019385,
      "name": "check_helper_mem_access.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int check_helper_mem_access(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_helper_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_helper_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6780",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_reg",
        "kernel/bpf/verifier.c:check_mem_reg",
        "kernel/bpf/verifier.c:check_mem_reg",
        "kernel/bpf/verifier.c:check_mem_reg",
        "kernel/bpf/verifier.c:check_mem_size_reg",
        "kernel/bpf/verifier.c:check_mem_size_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582070464,
      "name": "check_helper_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1100
    },
    {
      "addr": 18446744071596540634,
      "name": "check_helper_mem_access.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
int check_helper_mem_access(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_helper_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_helper_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7153",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_mem_reg",
        "kernel/bpf/verifier.c:check_mem_reg",
        "kernel/bpf/verifier.c:check_mem_reg",
        "kernel/bpf/verifier.c:check_mem_reg",
        "kernel/bpf/verifier.c:check_mem_size_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582202480,
      "name": "check_helper_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1104
    },
    {
      "addr": 18446744071597442585,
      "name": "check_helper_mem_access.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
int check_helper_mem_access(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_helper_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492175640,
      "name": "check_helper_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3088",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492175640,
      "name": "check_helper_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1144
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
int check_helper_mem_access(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_helper_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226072760,
      "name": "check_helper_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3088",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226072760,
      "name": "check_helper_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1276
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
int check_helper_mem_access(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_helper_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285389520,
      "name": "check_helper_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3088",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285389520,
      "name": "check_helper_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1496
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
int check_helper_mem_access(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_helper_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272331374,
      "name": "check_helper_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3088",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272331374,
      "name": "check_helper_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 958
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
int check_helper_mem_access(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_helper_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580819248,
      "name": "check_helper_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3088",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580819248,
      "name": "check_helper_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1246
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
int check_helper_mem_access(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_helper_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580765424,
      "name": "check_helper_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3088",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580765424,
      "name": "check_helper_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1246
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
int check_helper_mem_access(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_helper_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580810496,
      "name": "check_helper_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3088",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580810496,
      "name": "check_helper_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1246
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
int check_helper_mem_access(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_helper_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580868880,
      "name": "check_helper_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3088",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_func_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580868880,
      "name": "check_helper_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1246
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
int check_helper_mem_access(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
