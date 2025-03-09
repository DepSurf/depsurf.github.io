# Function: <code>visit_func_call_insn</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int visit_func_call_insn(int t, int insn_cnt, struct bpf_insn * insns, struct bpf_verifier_env * env, bool visit_callee)
```

```json
{
  "name": "visit_func_call_insn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581013456,
      "name": "visit_func_call_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9310",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581013456,
      "name": "visit_func_call_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int visit_func_call_insn(int t, int insn_cnt, struct bpf_insn * insns, struct bpf_verifier_env * env, bool visit_callee)
```

```json
{
  "name": "visit_func_call_insn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581231008,
      "name": "visit_func_call_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9625",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581231008,
      "name": "visit_func_call_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int visit_func_call_insn(int t, int insn_cnt, struct bpf_insn * insns, struct bpf_verifier_env * env, bool visit_callee)
```

```json
{
  "name": "visit_func_call_insn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581517920,
      "name": "visit_func_call_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:10607",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581517920,
      "name": "visit_func_call_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
int visit_func_call_insn(int t, struct bpf_insn * insns, struct bpf_verifier_env * env, bool visit_callee)
```

```json
{
  "name": "visit_func_call_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581881888,
      "name": "visit_func_call_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:12585",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581881888,
      "name": "visit_func_call_insn",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int visit_func_call_insn(int t, struct bpf_insn * insns, struct bpf_verifier_env * env, bool visit_callee)
```

```json
{
  "name": "visit_func_call_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581975504,
      "name": "visit_func_call_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:14545",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581975504,
      "name": "visit_func_call_insn",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int visit_func_call_insn(int t, struct bpf_insn * insns, struct bpf_verifier_env * env, bool visit_callee)
```

```json
{
  "name": "visit_func_call_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582090832,
      "name": "visit_func_call_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:15487",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:visit_insn",
        "kernel/bpf/verifier.c:visit_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582090832,
      "name": "visit_func_call_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int visit_func_call_insn(int t, int insn_cnt, struct bpf_insn * insns, struct bpf_verifier_env * env, bool visit_callee)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int insn_cnt</code>
</li>
<li>
<b>Param reordered. </b>
<code>t, insn_cnt, insns, env, visit_callee</code> ➡️ <code>t, insns, env, visit_callee</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
