# Function: <code>bpf_adj_linfo_after_remove</code>

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
  "name": "bpf_adj_linfo_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580775335,
      "name": "bpf_adj_linfo_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8201",
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
  "name": "bpf_adj_linfo_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580826119,
      "name": "bpf_adj_linfo_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8216",
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
int bpf_adj_linfo_after_remove(struct bpf_verifier_env * env, u32 off, u32 cnt)
```

```json
{
  "name": "bpf_adj_linfo_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580953520,
      "name": "bpf_adj_linfo_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9330",
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
      "addr": 18446744071580953520,
      "name": "bpf_adj_linfo_after_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
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
int bpf_adj_linfo_after_remove(struct bpf_verifier_env * env, u32 off, u32 cnt)
```

```json
{
  "name": "bpf_adj_linfo_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580952768,
      "name": "bpf_adj_linfo_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:10260",
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
      "addr": 18446744071580952768,
      "name": "bpf_adj_linfo_after_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
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
int bpf_adj_linfo_after_remove(struct bpf_verifier_env * env, u32 off, u32 cnt)
```

```json
{
  "name": "bpf_adj_linfo_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580956112,
      "name": "bpf_adj_linfo_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:11525",
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
      "addr": 18446744071580956112,
      "name": "bpf_adj_linfo_after_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
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
int bpf_adj_linfo_after_remove(struct bpf_verifier_env * env, u32 off, u32 cnt)
```

```json
{
  "name": "bpf_adj_linfo_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581161424,
      "name": "bpf_adj_linfo_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:11908",
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
      "addr": 18446744071581161424,
      "name": "bpf_adj_linfo_after_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 700
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
int bpf_adj_linfo_after_remove(struct bpf_verifier_env * env, u32 off, u32 cnt)
```

```json
{
  "name": "bpf_adj_linfo_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581439152,
      "name": "bpf_adj_linfo_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:12967",
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
      "addr": 18446744071581439152,
      "name": "bpf_adj_linfo_after_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 723
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
int bpf_adj_linfo_after_remove(struct bpf_verifier_env * env, u32 off, u32 cnt)
```

```json
{
  "name": "bpf_adj_linfo_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581794640,
      "name": "bpf_adj_linfo_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:14944",
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
      "addr": 18446744071581794640,
      "name": "bpf_adj_linfo_after_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 723
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
int bpf_adj_linfo_after_remove(struct bpf_verifier_env * env, u32 off, u32 cnt)
```

```json
{
  "name": "bpf_adj_linfo_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581966800,
      "name": "bpf_adj_linfo_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:17161",
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
      "addr": 18446744071581966800,
      "name": "bpf_adj_linfo_after_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 765
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
int bpf_adj_linfo_after_remove(struct bpf_verifier_env * env, u32 off, u32 cnt)
```

```json
{
  "name": "bpf_adj_linfo_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582096144,
      "name": "bpf_adj_linfo_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:18315",
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
      "addr": 18446744071582096144,
      "name": "bpf_adj_linfo_after_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 764
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
  "name": "bpf_adj_linfo_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492148868,
      "name": "bpf_adj_linfo_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8216",
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
  "name": "bpf_adj_linfo_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226047404,
      "name": "bpf_adj_linfo_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8216",
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
  "name": "bpf_adj_linfo_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285357716,
      "name": "bpf_adj_linfo_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8216",
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
  "name": "bpf_adj_linfo_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272310048,
      "name": "bpf_adj_linfo_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8216",
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
  "name": "bpf_adj_linfo_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580794919,
      "name": "bpf_adj_linfo_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8216",
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
  "name": "bpf_adj_linfo_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580741095,
      "name": "bpf_adj_linfo_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8216",
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
  "name": "bpf_adj_linfo_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580786167,
      "name": "bpf_adj_linfo_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8216",
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
  "name": "bpf_adj_linfo_after_remove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580844551,
      "name": "bpf_adj_linfo_after_remove",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8216",
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
int bpf_adj_linfo_after_remove(struct bpf_verifier_env * env, u32 off, u32 cnt)
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
