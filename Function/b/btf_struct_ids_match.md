# Function: <code>btf_struct_ids_match</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool btf_struct_ids_match(struct bpf_verifier_log * log, const struct btf * btf, u32 id, int off, const struct btf * need_btf, u32 need_type_id)
```

```json
{
  "name": "btf_struct_ids_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581121248,
      "name": "btf_struct_ids_match",
      "external": true,
      "loc": "kernel/bpf/btf.c:5041",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_reg_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581121248,
      "name": "btf_struct_ids_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
bool btf_struct_ids_match(struct bpf_verifier_log * log, const struct btf * btf, u32 id, int off, const struct btf * need_btf, u32 need_type_id)
```

```json
{
  "name": "btf_struct_ids_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581140192,
      "name": "btf_struct_ids_match",
      "external": true,
      "loc": "kernel/bpf/btf.c:5114",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/btf.c:btf_check_func_arg_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581140192,
      "name": "btf_struct_ids_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
bool btf_struct_ids_match(struct bpf_verifier_log * log, const struct btf * btf, u32 id, int off, const struct btf * need_btf, u32 need_type_id)
```

```json
{
  "name": "btf_struct_ids_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581373024,
      "name": "btf_struct_ids_match",
      "external": true,
      "loc": "kernel/bpf/btf.c:5167",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/btf.c:btf_check_func_arg_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581373024,
      "name": "btf_struct_ids_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
bool btf_struct_ids_match(struct bpf_verifier_log * log, const struct btf * btf, u32 id, int off, const struct btf * need_btf, u32 need_type_id, bool strict)
```

```json
{
  "name": "btf_struct_ids_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581689632,
      "name": "btf_struct_ids_match",
      "external": true,
      "loc": "kernel/bpf/btf.c:5714",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581689632,
      "name": "btf_struct_ids_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
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
bool btf_struct_ids_match(struct bpf_verifier_log * log, const struct btf * btf, u32 id, int off, const struct btf * need_btf, u32 need_type_id, bool strict)
```

```json
{
  "name": "btf_struct_ids_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582087488,
      "name": "btf_struct_ids_match",
      "external": true,
      "loc": "kernel/bpf/btf.c:6383",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:process_kf_arg_ptr_to_list_node",
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:map_kptr_match_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582087488,
      "name": "btf_struct_ids_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
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
bool btf_struct_ids_match(struct bpf_verifier_log * log, const struct btf * btf, u32 id, int off, const struct btf * need_btf, u32 need_type_id, bool strict)
```

```json
{
  "name": "btf_struct_ids_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582283840,
      "name": "btf_struct_ids_match",
      "external": true,
      "loc": "kernel/bpf/btf.c:6471",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node",
        "kernel/bpf/verifier.c:process_kf_arg_ptr_to_btf_id",
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:map_kptr_match_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582283840,
      "name": "btf_struct_ids_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
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
bool btf_struct_ids_match(struct bpf_verifier_log * log, const struct btf * btf, u32 id, int off, const struct btf * need_btf, u32 need_type_id, bool strict)
```

```json
{
  "name": "btf_struct_ids_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582440624,
      "name": "btf_struct_ids_match",
      "external": true,
      "loc": "kernel/bpf/btf.c:6643",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node",
        "kernel/bpf/verifier.c:process_kf_arg_ptr_to_btf_id",
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:map_kptr_match_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582440624,
      "name": "btf_struct_ids_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
bool btf_struct_ids_match(struct bpf_verifier_log * log, const struct btf * btf, u32 id, int off, const struct btf * need_btf, u32 need_type_id)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool strict</code>
</li>
</ul>
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
