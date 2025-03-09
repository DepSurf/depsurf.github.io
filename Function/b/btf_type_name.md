# Function: <code>btf_type_name</code>

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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * btf_type_name(const struct btf * btf, u32 id)
```

```json
{
  "name": "btf_type_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582075908,
      "name": "btf_type_name",
      "external": false,
      "loc": "kernel/bpf/verifier.c:730",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:process_iter_arg",
        "kernel/bpf/verifier.c:process_iter_arg",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:print_verifier_state",
        "kernel/bpf/verifier.c:print_verifier_state"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:check_reg_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581951488,
      "name": "btf_type_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
const char * btf_type_name(const struct btf * btf, u32 id)
```

```json
{
  "name": "btf_type_name",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582240157,
      "name": "btf_type_name",
      "external": false,
      "loc": "kernel/bpf/verifier.c:344",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check_subprogs",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:map_kptr_match_type"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:check_reg_type"
      ]
    },
    {
      "addr": 18446744071582279295,
      "name": "btf_type_name",
      "external": false,
      "loc": "kernel/bpf/log.c:388",
      "file": "kernel/bpf/log.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/log.c:print_verifier_state",
        "kernel/bpf/log.c:print_reg_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582077696,
      "name": "btf_type_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
const char * btf_type_name(const struct btf * btf, u32 id)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
