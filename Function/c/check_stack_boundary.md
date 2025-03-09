# Function: <code>check_stack_boundary</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int check_stack_boundary(struct verifier_env * env, int regno, int access_size)
```

```json
{
  "name": "check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580367856,
      "name": "check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:781",
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
      "addr": 18446744071580367856,
      "name": "check_stack_boundary",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int check_stack_boundary(struct verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580425872,
      "name": "check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:885",
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
      "addr": 18446744071580425872,
      "name": "check_stack_boundary",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
int check_stack_boundary(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580476304,
      "name": "check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:917",
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
      "addr": 18446744071580476304,
      "name": "check_stack_boundary",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
int check_stack_boundary(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580500192,
      "name": "check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1023",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580500192,
      "name": "check_stack_boundary",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
int check_stack_boundary(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580556544,
      "name": "check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1306",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/verifier.c:check_helper_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580556544,
      "name": "check_stack_boundary",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580657522,
      "name": "check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1844",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_helper_mem_access"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580721862,
      "name": "check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2106",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_helper_mem_access"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580799570,
      "name": "check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2962",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_helper_mem_access"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580850674,
      "name": "check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2963",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_helper_mem_access"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int check_stack_boundary(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580979536,
      "name": "check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3454",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580979536,
      "name": "check_stack_boundary",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1084
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
int check_stack_boundary(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580984864,
      "name": "check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3684",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580984864,
      "name": "check_stack_boundary",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1009
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492175920,
      "name": "check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2963",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_helper_mem_access"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226073028,
      "name": "check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2963",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_helper_mem_access"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285389856,
      "name": "check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2963",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_helper_mem_access"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272331586,
      "name": "check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2963",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_helper_mem_access"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580819474,
      "name": "check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2963",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_helper_mem_access"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580765650,
      "name": "check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2963",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_helper_mem_access"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580810722,
      "name": "check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2963",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_helper_mem_access"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_stack_boundary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580869106,
      "name": "check_stack_boundary",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2963",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_helper_mem_access"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool zero_size_allowed</code>
</li>
<li>
<b>Param added. </b>
<code>struct bpf_call_arg_meta * meta</code>
</li>
</ul>
</details>
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int check_stack_boundary(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int check_stack_boundary(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int check_stack_boundary(struct bpf_verifier_env * env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta * meta)
```
</details>
</li>
</ul>
