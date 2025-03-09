# Function: <code>bpf_core_apply</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int bpf_core_apply(struct bpf_core_ctx * ctx, const struct bpf_core_relo * relo, int relo_idx, void * insn)
```

```json
{
  "name": "bpf_core_apply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581701104,
      "name": "bpf_core_apply",
      "external": true,
      "loc": "kernel/bpf/btf.c:7733",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_core_relo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581701104,
      "name": "bpf_core_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 859
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
int bpf_core_apply(struct bpf_core_ctx * ctx, const struct bpf_core_relo * relo, int relo_idx, void * insn)
```

```json
{
  "name": "bpf_core_apply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582102560,
      "name": "bpf_core_apply",
      "external": true,
      "loc": "kernel/bpf/btf.c:8154",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_core_relo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582102560,
      "name": "bpf_core_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 874
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
int bpf_core_apply(struct bpf_core_ctx * ctx, const struct bpf_core_relo * relo, int relo_idx, void * insn)
```

```json
{
  "name": "bpf_core_apply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582296608,
      "name": "bpf_core_apply",
      "external": true,
      "loc": "kernel/bpf/btf.c:8413",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_core_relo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582296608,
      "name": "bpf_core_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 875
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
int bpf_core_apply(struct bpf_core_ctx * ctx, const struct bpf_core_relo * relo, int relo_idx, void * insn)
```

```json
{
  "name": "bpf_core_apply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582454224,
      "name": "bpf_core_apply",
      "external": true,
      "loc": "kernel/bpf/btf.c:8478",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_core_relo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582454224,
      "name": "bpf_core_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 933
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int bpf_core_apply(struct bpf_core_ctx * ctx, const struct bpf_core_relo * relo, int relo_idx, void * insn)
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
