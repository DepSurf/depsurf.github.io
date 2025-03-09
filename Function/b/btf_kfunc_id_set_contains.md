# Function: <code>btf_kfunc_id_set_contains</code>

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
bool btf_kfunc_id_set_contains(const struct btf * btf, enum bpf_prog_type prog_type, enum btf_kfunc_type type, u32 kfunc_btf_id)
```

```json
{
  "name": "btf_kfunc_id_set_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581695920,
      "name": "btf_kfunc_id_set_contains",
      "external": true,
      "loc": "kernel/bpf/btf.c:7137",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581695920,
      "name": "btf_kfunc_id_set_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
u32 * btf_kfunc_id_set_contains(const struct btf * btf, enum bpf_prog_type prog_type, u32 kfunc_btf_id)
```

```json
{
  "name": "btf_kfunc_id_set_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582100576,
      "name": "btf_kfunc_id_set_contains",
      "external": true,
      "loc": "kernel/bpf/btf.c:7606",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_kfunc_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582100576,
      "name": "btf_kfunc_id_set_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
u32 * btf_kfunc_id_set_contains(const struct btf * btf, u32 kfunc_btf_id, const struct bpf_prog * prog)
```

```json
{
  "name": "btf_kfunc_id_set_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582294784,
      "name": "btf_kfunc_id_set_contains",
      "external": true,
      "loc": "kernel/bpf/btf.c:7858",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:fetch_kfunc_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582294784,
      "name": "btf_kfunc_id_set_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
u32 * btf_kfunc_id_set_contains(const struct btf * btf, u32 kfunc_btf_id, const struct bpf_prog * prog)
```

```json
{
  "name": "btf_kfunc_id_set_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582452400,
      "name": "btf_kfunc_id_set_contains",
      "external": true,
      "loc": "kernel/bpf/btf.c:7923",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:fetch_kfunc_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582452400,
      "name": "btf_kfunc_id_set_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
bool btf_kfunc_id_set_contains(const struct btf * btf, enum bpf_prog_type prog_type, enum btf_kfunc_type type, u32 kfunc_btf_id)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>enum btf_kfunc_type type</code>
</li>
<li>
<b>Param reordered. </b>
<code>btf, prog_type, type, kfunc_btf_id</code> ➡️ <code>btf, prog_type, kfunc_btf_id</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>u32 *</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct bpf_prog * prog</code>
</li>
<li>
<b>Param removed. </b>
<code>enum bpf_prog_type prog_type</code>
</li>
<li>
<b>Param reordered. </b>
<code>btf, prog_type, kfunc_btf_id</code> ➡️ <code>btf, kfunc_btf_id, prog</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
