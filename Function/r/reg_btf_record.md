# Function: <code>reg_btf_record</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct btf_record * reg_btf_record(const struct bpf_reg_state * reg)
```

```json
{
  "name": "reg_btf_record",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581791552,
      "name": "reg_btf_record",
      "external": false,
      "loc": "kernel/bpf/verifier.c:459",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:process_kf_arg_ptr_to_list_node",
        "kernel/bpf/verifier.c:process_kf_arg_ptr_to_list_head",
        "kernel/bpf/verifier.c:process_spin_lock",
        "kernel/bpf/verifier.c:process_spin_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581791552,
      "name": "reg_btf_record",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
struct btf_record * reg_btf_record(const struct bpf_reg_state * reg)
```

```json
{
  "name": "reg_btf_record",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581958736,
      "name": "reg_btf_record",
      "external": false,
      "loc": "kernel/bpf/verifier.c:474",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node",
        "kernel/bpf/verifier.c:set_rbtree_add_callback_state",
        "kernel/bpf/verifier.c:process_spin_lock",
        "kernel/bpf/verifier.c:process_spin_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581958736,
      "name": "reg_btf_record",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct btf_record * reg_btf_record(const struct bpf_reg_state * reg)
```

```json
{
  "name": "reg_btf_record",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582085504,
      "name": "reg_btf_record",
      "external": false,
      "loc": "kernel/bpf/verifier.c:409",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node",
        "kernel/bpf/verifier.c:set_rbtree_add_callback_state",
        "kernel/bpf/verifier.c:process_spin_lock",
        "kernel/bpf/verifier.c:process_spin_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582085504,
      "name": "reg_btf_record",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct btf_record * reg_btf_record(const struct bpf_reg_state * reg)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
