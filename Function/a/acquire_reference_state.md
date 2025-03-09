# Function: <code>acquire_reference_state</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acquire_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580725151,
      "name": "acquire_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:597",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acquire_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580821035,
      "name": "acquire_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:620",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acquire_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580872295,
      "name": "acquire_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:620",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acquire_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581015404,
      "name": "acquire_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:747",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acquire_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581018446,
      "name": "acquire_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:773",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acquire_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581027766,
      "name": "acquire_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:822",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "acquire_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581249821,
      "name": "acquire_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:850",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int acquire_reference_state(struct bpf_verifier_env * env, int insn_idx)
```

```json
{
  "name": "acquire_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581437376,
      "name": "acquire_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1077",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581437376,
      "name": "acquire_reference_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
int acquire_reference_state(struct bpf_verifier_env * env, int insn_idx)
```

```json
{
  "name": "acquire_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acquire_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1275",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:mark_stack_slots_dynptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793008,
      "name": "acquire_reference_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    },
    {
      "addr": 18446744071596014214,
      "name": "acquire_reference_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int acquire_reference_state(struct bpf_verifier_env * env, int insn_idx)
```

```json
{
  "name": "acquire_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acquire_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1652",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:process_iter_arg",
        "kernel/bpf/verifier.c:mark_stack_slots_dynptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581964944,
      "name": "acquire_reference_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
    },
    {
      "addr": 18446744071596534835,
      "name": "acquire_reference_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int acquire_reference_state(struct bpf_verifier_env * env, int insn_idx)
```

```json
{
  "name": "acquire_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acquire_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1305",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:process_iter_arg",
        "kernel/bpf/verifier.c:mark_stack_slots_dynptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582091632,
      "name": "acquire_reference_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
    },
    {
      "addr": 18446744071597435745,
      "name": "acquire_reference_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
  "name": "acquire_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492197664,
      "name": "acquire_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:620",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "acquire_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226095424,
      "name": "acquire_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:620",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "acquire_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285416252,
      "name": "acquire_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:620",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "acquire_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272349014,
      "name": "acquire_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:620",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acquire_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580841095,
      "name": "acquire_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:620",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acquire_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580787271,
      "name": "acquire_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:620",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acquire_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580832343,
      "name": "acquire_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:620",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acquire_reference_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580890663,
      "name": "acquire_reference_state",
      "external": false,
      "loc": "kernel/bpf/verifier.c:620",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int acquire_reference_state(struct bpf_verifier_env * env, int insn_idx)
```
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
