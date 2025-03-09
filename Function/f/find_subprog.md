# Function: <code>find_subprog</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int find_subprog(struct bpf_verifier_env * env, int off)
```

```json
{
  "name": "find_subprog",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580641536,
      "name": "find_subprog",
      "external": false,
      "loc": "kernel/bpf/verifier.c:770",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580641536,
      "name": "find_subprog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
int find_subprog(struct bpf_verifier_env * env, int off)
```

```json
{
  "name": "find_subprog",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580703472,
      "name": "find_subprog",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1022",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580703472,
      "name": "find_subprog",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int find_subprog(struct bpf_verifier_env * env, int off)
```

```json
{
  "name": "find_subprog",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580772768,
      "name": "find_subprog",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1087",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580772768,
      "name": "find_subprog",
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
int find_subprog(struct bpf_verifier_env * env, int off)
```

```json
{
  "name": "find_subprog",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580823680,
      "name": "find_subprog",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1088",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580823680,
      "name": "find_subprog",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_subprog",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580988945,
      "name": "find_subprog",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1396",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:check_func_call",
        "kernel/bpf/verifier.c:check_max_stack_depth"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_subprog",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580997659,
      "name": "find_subprog",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1441",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:check_func_call",
        "kernel/bpf/verifier.c:check_max_stack_depth"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_subprog",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581004891,
      "name": "find_subprog",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1533",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_max_stack_depth"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_subprog",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581220245,
      "name": "find_subprog",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1601",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_max_stack_depth"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_subprog",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581505475,
      "name": "find_subprog",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1806",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_ld_imm",
        "kernel/bpf/verifier.c:check_max_stack_depth"
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
  "name": "find_subprog",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581860323,
      "name": "find_subprog",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2021",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_ld_imm",
        "kernel/bpf/verifier.c:check_max_stack_depth"
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
  "name": "find_subprog",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582032755,
      "name": "find_subprog",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2420",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_ld_imm",
        "kernel/bpf/verifier.c:check_max_stack_depth_subprog",
        "kernel/bpf/verifier.c:backtrack_insn"
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
  "name": "find_subprog",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582174789,
      "name": "find_subprog",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2431",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:check_ld_imm",
        "kernel/bpf/verifier.c:check_max_stack_depth_subprog",
        "kernel/bpf/verifier.c:backtrack_insn"
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
int find_subprog(struct bpf_verifier_env * env, int off)
```

```json
{
  "name": "find_subprog",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492147512,
      "name": "find_subprog",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1088",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492147512,
      "name": "find_subprog",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int find_subprog(struct bpf_verifier_env * env, int off)
```

```json
{
  "name": "find_subprog",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226044404,
      "name": "find_subprog",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1088",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226044404,
      "name": "find_subprog",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int find_subprog(struct bpf_verifier_env * env, int off)
```

```json
{
  "name": "find_subprog",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285354560,
      "name": "find_subprog",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1088",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285354560,
      "name": "find_subprog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int find_subprog(struct bpf_verifier_env * env, int off)
```

```json
{
  "name": "find_subprog",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272308110,
      "name": "find_subprog",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1088",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272308110,
      "name": "find_subprog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
int find_subprog(struct bpf_verifier_env * env, int off)
```

```json
{
  "name": "find_subprog",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580792480,
      "name": "find_subprog",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1088",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580792480,
      "name": "find_subprog",
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
int find_subprog(struct bpf_verifier_env * env, int off)
```

```json
{
  "name": "find_subprog",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580738656,
      "name": "find_subprog",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1088",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580738656,
      "name": "find_subprog",
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
int find_subprog(struct bpf_verifier_env * env, int off)
```

```json
{
  "name": "find_subprog",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580783728,
      "name": "find_subprog",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1088",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580783728,
      "name": "find_subprog",
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
int find_subprog(struct bpf_verifier_env * env, int off)
```

```json
{
  "name": "find_subprog",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580842112,
      "name": "find_subprog",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1088",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580842112,
      "name": "find_subprog",
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int find_subprog(struct bpf_verifier_env * env, int off)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int find_subprog(struct bpf_verifier_env * env, int off)
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
