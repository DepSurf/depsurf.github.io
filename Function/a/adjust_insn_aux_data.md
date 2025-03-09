# Function: <code>adjust_insn_aux_data</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "adjust_insn_aux_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580501679,
      "name": "adjust_insn_aux_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3495",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "adjust_insn_aux_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580560175,
      "name": "adjust_insn_aux_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4300",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "adjust_insn_aux_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580643090,
      "name": "adjust_insn_aux_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5201",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
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
  "name": "adjust_insn_aux_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580704931,
      "name": "adjust_insn_aux_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6387",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
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
  "name": "adjust_insn_aux_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580806057,
      "name": "adjust_insn_aux_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8079",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
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
  "name": "adjust_insn_aux_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580857193,
      "name": "adjust_insn_aux_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8094",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
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
int adjust_insn_aux_data(struct bpf_verifier_env * env, struct bpf_prog * new_prog, u32 off, u32 cnt)
```

```json
{
  "name": "adjust_insn_aux_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580955328,
      "name": "adjust_insn_aux_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9208",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580955328,
      "name": "adjust_insn_aux_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
int adjust_insn_aux_data(struct bpf_verifier_env * env, struct bpf_prog * new_prog, u32 off, u32 cnt)
```

```json
{
  "name": "adjust_insn_aux_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580956192,
      "name": "adjust_insn_aux_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:10125",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580956192,
      "name": "adjust_insn_aux_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
int adjust_insn_aux_data(struct bpf_verifier_env * env, struct bpf_prog * new_prog, u32 off, u32 cnt)
```

```json
{
  "name": "adjust_insn_aux_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580959264,
      "name": "adjust_insn_aux_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:11386",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580959264,
      "name": "adjust_insn_aux_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
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
void adjust_insn_aux_data(struct bpf_verifier_env * env, struct bpf_insn_aux_data * new_data, struct bpf_prog * new_prog, u32 off, u32 cnt)
```

```json
{
  "name": "adjust_insn_aux_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581164928,
      "name": "adjust_insn_aux_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:11764",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581164928,
      "name": "adjust_insn_aux_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
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
void adjust_insn_aux_data(struct bpf_verifier_env * env, struct bpf_insn_aux_data * new_data, struct bpf_prog * new_prog, u32 off, u32 cnt)
```

```json
{
  "name": "adjust_insn_aux_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581444944,
      "name": "adjust_insn_aux_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:12823",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581444944,
      "name": "adjust_insn_aux_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
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
void adjust_insn_aux_data(struct bpf_verifier_env * env, struct bpf_insn_aux_data * new_data, struct bpf_prog * new_prog, u32 off, u32 cnt)
```

```json
{
  "name": "adjust_insn_aux_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581798976,
      "name": "adjust_insn_aux_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:14800",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581798976,
      "name": "adjust_insn_aux_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
void adjust_insn_aux_data(struct bpf_verifier_env * env, struct bpf_insn_aux_data * new_data, struct bpf_prog * new_prog, u32 off, u32 cnt)
```

```json
{
  "name": "adjust_insn_aux_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581978720,
      "name": "adjust_insn_aux_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:17017",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581978720,
      "name": "adjust_insn_aux_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
void adjust_insn_aux_data(struct bpf_verifier_env * env, struct bpf_insn_aux_data * new_data, struct bpf_prog * new_prog, u32 off, u32 cnt)
```

```json
{
  "name": "adjust_insn_aux_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582107008,
      "name": "adjust_insn_aux_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:18171",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582107008,
      "name": "adjust_insn_aux_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
  "name": "adjust_insn_aux_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492182704,
      "name": "adjust_insn_aux_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8094",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
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
  "name": "adjust_insn_aux_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226079340,
      "name": "adjust_insn_aux_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8094",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
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
  "name": "adjust_insn_aux_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285396852,
      "name": "adjust_insn_aux_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8094",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
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
  "name": "adjust_insn_aux_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272336898,
      "name": "adjust_insn_aux_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8094",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
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
  "name": "adjust_insn_aux_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580825993,
      "name": "adjust_insn_aux_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8094",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
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
  "name": "adjust_insn_aux_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580772169,
      "name": "adjust_insn_aux_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8094",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
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
  "name": "adjust_insn_aux_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580817241,
      "name": "adjust_insn_aux_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8094",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
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
  "name": "adjust_insn_aux_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580875625,
      "name": "adjust_insn_aux_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8094",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_patch_insn_data"
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
int adjust_insn_aux_data(struct bpf_verifier_env * env, struct bpf_prog * new_prog, u32 off, u32 cnt)
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_insn_aux_data * new_data</code>
</li>
<li>
<b>Param reordered. </b>
<code>env, new_prog, off, cnt</code> ➡️ <code>env, new_data, new_prog, off, cnt</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
