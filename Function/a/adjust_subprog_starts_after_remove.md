# Function: <code>adjust_subprog_starts_after_remove</code>

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
  "name": "adjust_subprog_starts_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_subprog_starts_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8145",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:verifier_remove_insns"
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
  "name": "adjust_subprog_starts_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_subprog_starts_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8160",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:verifier_remove_insns"
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
int adjust_subprog_starts_after_remove(struct bpf_verifier_env * env, u32 off, u32 cnt)
```

```json
{
  "name": "adjust_subprog_starts_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580953088,
      "name": "adjust_subprog_starts_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9274",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verifier_remove_insns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580953088,
      "name": "adjust_subprog_starts_after_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
int adjust_subprog_starts_after_remove(struct bpf_verifier_env * env, u32 off, u32 cnt)
```

```json
{
  "name": "adjust_subprog_starts_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580952336,
      "name": "adjust_subprog_starts_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:10204",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verifier_remove_insns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580952336,
      "name": "adjust_subprog_starts_after_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
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
int adjust_subprog_starts_after_remove(struct bpf_verifier_env * env, u32 off, u32 cnt)
```

```json
{
  "name": "adjust_subprog_starts_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580955680,
      "name": "adjust_subprog_starts_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:11469",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verifier_remove_insns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580955680,
      "name": "adjust_subprog_starts_after_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
int adjust_subprog_starts_after_remove(struct bpf_verifier_env * env, u32 off, u32 cnt)
```

```json
{
  "name": "adjust_subprog_starts_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581160560,
      "name": "adjust_subprog_starts_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:11852",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verifier_remove_insns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581160560,
      "name": "adjust_subprog_starts_after_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 855
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
int adjust_subprog_starts_after_remove(struct bpf_verifier_env * env, u32 off, u32 cnt)
```

```json
{
  "name": "adjust_subprog_starts_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581438336,
      "name": "adjust_subprog_starts_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:12911",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verifier_remove_insns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581438336,
      "name": "adjust_subprog_starts_after_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 815
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
int adjust_subprog_starts_after_remove(struct bpf_verifier_env * env, u32 off, u32 cnt)
```

```json
{
  "name": "adjust_subprog_starts_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581793808,
      "name": "adjust_subprog_starts_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:14888",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verifier_remove_insns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793808,
      "name": "adjust_subprog_starts_after_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 815
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
int adjust_subprog_starts_after_remove(struct bpf_verifier_env * env, u32 off, u32 cnt)
```

```json
{
  "name": "adjust_subprog_starts_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_subprog_starts_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:17105",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verifier_remove_insns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581965760,
      "name": "adjust_subprog_starts_after_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1016
    },
    {
      "addr": 18446744071596534905,
      "name": "adjust_subprog_starts_after_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
int adjust_subprog_starts_after_remove(struct bpf_verifier_env * env, u32 off, u32 cnt)
```

```json
{
  "name": "adjust_subprog_starts_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_subprog_starts_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:18259",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verifier_remove_insns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582095040,
      "name": "adjust_subprog_starts_after_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1073
    },
    {
      "addr": 18446744071597436180,
      "name": "adjust_subprog_starts_after_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
  "name": "adjust_subprog_starts_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_subprog_starts_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8160",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:verifier_remove_insns"
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
  "name": "adjust_subprog_starts_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_subprog_starts_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8160",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:verifier_remove_insns"
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
  "name": "adjust_subprog_starts_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_subprog_starts_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8160",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:verifier_remove_insns"
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
  "name": "adjust_subprog_starts_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272309898,
      "name": "adjust_subprog_starts_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8160",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:verifier_remove_insns"
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
  "name": "adjust_subprog_starts_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_subprog_starts_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8160",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:verifier_remove_insns"
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
  "name": "adjust_subprog_starts_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_subprog_starts_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8160",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:verifier_remove_insns"
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
  "name": "adjust_subprog_starts_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_subprog_starts_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8160",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:verifier_remove_insns"
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
  "name": "adjust_subprog_starts_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_subprog_starts_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8160",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:verifier_remove_insns"
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
int adjust_subprog_starts_after_remove(struct bpf_verifier_env * env, u32 off, u32 cnt)
```
</details>
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
