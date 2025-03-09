# Function: <code>opt_hard_wire_dead_code_branches</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "opt_hard_wire_dead_code_branches",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580831355,
      "name": "opt_hard_wire_dead_code_branches",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8332",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
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
  "name": "opt_hard_wire_dead_code_branches",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580882651,
      "name": "opt_hard_wire_dead_code_branches",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8347",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
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
void opt_hard_wire_dead_code_branches(struct bpf_verifier_env * env)
```

```json
{
  "name": "opt_hard_wire_dead_code_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580952816,
      "name": "opt_hard_wire_dead_code_branches",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9461",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580952816,
      "name": "opt_hard_wire_dead_code_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
void opt_hard_wire_dead_code_branches(struct bpf_verifier_env * env)
```

```json
{
  "name": "opt_hard_wire_dead_code_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580952064,
      "name": "opt_hard_wire_dead_code_branches",
      "external": false,
      "loc": "kernel/bpf/verifier.c:10391",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580952064,
      "name": "opt_hard_wire_dead_code_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "opt_hard_wire_dead_code_branches",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581039243,
      "name": "opt_hard_wire_dead_code_branches",
      "external": false,
      "loc": "kernel/bpf/verifier.c:11657",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
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
  "name": "opt_hard_wire_dead_code_branches",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581262105,
      "name": "opt_hard_wire_dead_code_branches",
      "external": false,
      "loc": "kernel/bpf/verifier.c:12040",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void opt_hard_wire_dead_code_branches(struct bpf_verifier_env * env)
```

```json
{
  "name": "opt_hard_wire_dead_code_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "opt_hard_wire_dead_code_branches",
      "external": false,
      "loc": "kernel/bpf/verifier.c:13099",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581439888,
      "name": "opt_hard_wire_dead_code_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    },
    {
      "addr": 18446744071593954639,
      "name": "opt_hard_wire_dead_code_branches.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void opt_hard_wire_dead_code_branches(struct bpf_verifier_env * env)
```

```json
{
  "name": "opt_hard_wire_dead_code_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "opt_hard_wire_dead_code_branches",
      "external": false,
      "loc": "kernel/bpf/verifier.c:15076",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793504,
      "name": "opt_hard_wire_dead_code_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
    },
    {
      "addr": 18446744071596014241,
      "name": "opt_hard_wire_dead_code_branches.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void opt_hard_wire_dead_code_branches(struct bpf_verifier_env * env)
```

```json
{
  "name": "opt_hard_wire_dead_code_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "opt_hard_wire_dead_code_branches",
      "external": false,
      "loc": "kernel/bpf/verifier.c:17293",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581965456,
      "name": "opt_hard_wire_dead_code_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
    },
    {
      "addr": 18446744071596534862,
      "name": "opt_hard_wire_dead_code_branches.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void opt_hard_wire_dead_code_branches(struct bpf_verifier_env * env)
```

```json
{
  "name": "opt_hard_wire_dead_code_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "opt_hard_wire_dead_code_branches",
      "external": false,
      "loc": "kernel/bpf/verifier.c:18447",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582094688,
      "name": "opt_hard_wire_dead_code_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
    },
    {
      "addr": 18446744071597436135,
      "name": "opt_hard_wire_dead_code_branches.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
  "name": "opt_hard_wire_dead_code_branches",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492207600,
      "name": "opt_hard_wire_dead_code_branches",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8347",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
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
  "name": "opt_hard_wire_dead_code_branches",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226104884,
      "name": "opt_hard_wire_dead_code_branches",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8347",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
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
  "name": "opt_hard_wire_dead_code_branches",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285427284,
      "name": "opt_hard_wire_dead_code_branches",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8347",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
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
  "name": "opt_hard_wire_dead_code_branches",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272356888,
      "name": "opt_hard_wire_dead_code_branches",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8347",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
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
  "name": "opt_hard_wire_dead_code_branches",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580851451,
      "name": "opt_hard_wire_dead_code_branches",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8347",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
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
  "name": "opt_hard_wire_dead_code_branches",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580797627,
      "name": "opt_hard_wire_dead_code_branches",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8347",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
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
  "name": "opt_hard_wire_dead_code_branches",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580842699,
      "name": "opt_hard_wire_dead_code_branches",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8347",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
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
  "name": "opt_hard_wire_dead_code_branches",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580900987,
      "name": "opt_hard_wire_dead_code_branches",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8347",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void opt_hard_wire_dead_code_branches(struct bpf_verifier_env * env)
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
void opt_hard_wire_dead_code_branches(struct bpf_verifier_env * env)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void opt_hard_wire_dead_code_branches(struct bpf_verifier_env * env)
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
