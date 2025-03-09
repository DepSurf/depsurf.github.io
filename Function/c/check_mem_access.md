# Function: <code>check_mem_access</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int check_mem_access(struct verifier_env * env, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno)
```

```json
{
  "name": "check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580368848,
      "name": "check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:681",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580368848,
      "name": "check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1280
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
int check_mem_access(struct verifier_env * env, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno)
```

```json
{
  "name": "check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580427088,
      "name": "check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:758",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580427088,
      "name": "check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1923
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
int check_mem_access(struct bpf_verifier_env * env, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno)
```

```json
{
  "name": "check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580478448,
      "name": "check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:751",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580478448,
      "name": "check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2314
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
int check_mem_access(struct bpf_verifier_env * env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno)
```

```json
{
  "name": "check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580503632,
      "name": "check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:878",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580503632,
      "name": "check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2128
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
int check_mem_access(struct bpf_verifier_env * env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once)
```

```json
{
  "name": "check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580571648,
      "name": "check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1118",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580571648,
      "name": "check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2469
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
int check_mem_access(struct bpf_verifier_env * env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once)
```

```json
{
  "name": "check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580654144,
      "name": "check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1673",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580654144,
      "name": "check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3202
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
int check_mem_access(struct bpf_verifier_env * env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once)
```

```json
{
  "name": "check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580718064,
      "name": "check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1932",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580718064,
      "name": "check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3618
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
int check_mem_access(struct bpf_verifier_env * env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once)
```

```json
{
  "name": "check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580814240,
      "name": "check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2748",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580814240,
      "name": "check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4026
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
int check_mem_access(struct bpf_verifier_env * env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once)
```

```json
{
  "name": "check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580865440,
      "name": "check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2749",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580865440,
      "name": "check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4026
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
int check_mem_access(struct bpf_verifier_env * env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once)
```

```json
{
  "name": "check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581008480,
      "name": "check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3203",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_xadd",
        "kernel/bpf/verifier.c:check_xadd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581008480,
      "name": "check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2821
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
int check_mem_access(struct bpf_verifier_env * env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once)
```

```json
{
  "name": "check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581011728,
      "name": "check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3410",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_xadd",
        "kernel/bpf/verifier.c:check_xadd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581011728,
      "name": "check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2936
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
int check_mem_access(struct bpf_verifier_env * env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once)
```

```json
{
  "name": "check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581018976,
      "name": "check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4038",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_atomic",
        "kernel/bpf/verifier.c:check_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581018976,
      "name": "check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3566
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
int check_mem_access(struct bpf_verifier_env * env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once)
```

```json
{
  "name": "check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4139",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_atomic",
        "kernel/bpf/verifier.c:check_atomic",
        "kernel/bpf/verifier.c:check_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581238368,
      "name": "check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4813
    },
    {
      "addr": 18446744071592184868,
      "name": "check_mem_access.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
int check_mem_access(struct bpf_verifier_env * env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once)
```

```json
{
  "name": "check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4688",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_atomic",
        "kernel/bpf/verifier.c:check_atomic",
        "kernel/bpf/verifier.c:check_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581525520,
      "name": "check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 5338
    },
    {
      "addr": 18446744071593959221,
      "name": "check_mem_access.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
int check_mem_access(struct bpf_verifier_env * env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once)
```

```json
{
  "name": "check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5194",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_atomic",
        "kernel/bpf/verifier.c:check_atomic",
        "kernel/bpf/verifier.c:check_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581888032,
      "name": "check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 5333
    },
    {
      "addr": 18446744071596019071,
      "name": "check_mem_access.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
int check_mem_access(struct bpf_verifier_env * env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once)
```

```json
{
  "name": "check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6274",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:process_iter_arg",
        "kernel/bpf/verifier.c:process_dynptr_func",
        "kernel/bpf/verifier.c:process_dynptr_func",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_atomic",
        "kernel/bpf/verifier.c:check_atomic",
        "kernel/bpf/verifier.c:check_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582065024,
      "name": "check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 5417
    },
    {
      "addr": 18446744071596540306,
      "name": "check_mem_access.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
int check_mem_access(struct bpf_verifier_env * env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once, bool is_ldsx)
```

```json
{
  "name": "check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6648",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:process_iter_arg",
        "kernel/bpf/verifier.c:process_dynptr_func",
        "kernel/bpf/verifier.c:process_dynptr_func",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_atomic",
        "kernel/bpf/verifier.c:check_atomic",
        "kernel/bpf/verifier.c:check_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582195856,
      "name": "check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 5294
    },
    {
      "addr": 18446744071597442208,
      "name": "check_mem_access.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
int check_mem_access(struct bpf_verifier_env * env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once)
```

```json
{
  "name": "check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492192328,
      "name": "check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2749",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492192328,
      "name": "check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2792
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
int check_mem_access(struct bpf_verifier_env * env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once)
```

```json
{
  "name": "check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226088724,
      "name": "check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2749",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226088724,
      "name": "check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2940
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
int check_mem_access(struct bpf_verifier_env * env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once)
```

```json
{
  "name": "check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285409264,
      "name": "check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2749",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285409264,
      "name": "check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3132
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
int check_mem_access(struct bpf_verifier_env * env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once)
```

```json
{
  "name": "check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272344714,
      "name": "check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2749",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272344714,
      "name": "check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2242
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
int check_mem_access(struct bpf_verifier_env * env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once)
```

```json
{
  "name": "check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580834240,
      "name": "check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2749",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580834240,
      "name": "check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4026
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
int check_mem_access(struct bpf_verifier_env * env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once)
```

```json
{
  "name": "check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580780416,
      "name": "check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2749",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580780416,
      "name": "check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4026
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
int check_mem_access(struct bpf_verifier_env * env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once)
```

```json
{
  "name": "check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580825488,
      "name": "check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2749",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580825488,
      "name": "check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4026
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
int check_mem_access(struct bpf_verifier_env * env, int insn_idx, u32 regno, int off, int bpf_size, enum bpf_access_type t, int value_regno, bool strict_alignment_once)
```

```json
{
  "name": "check_mem_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580883808,
      "name": "check_mem_access",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2749",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580883808,
      "name": "check_mem_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4026
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct verifier_env * env</code> ➡️ <code>struct bpf_verifier_env * env</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int insn_idx</code>
</li>
<li>
<b>Param reordered. </b>
<code>env, regno, off, bpf_size, t, value_regno</code> ➡️ <code>env, insn_idx, regno, off, bpf_size, t, value_regno</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool strict_alignment_once</code>
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool is_ldsx</code>
</li>
</ul>
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
