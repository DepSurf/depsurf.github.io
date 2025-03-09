# Function: <code>__btf_kfunc_id_set_contains</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__btf_kfunc_id_set_contains",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581695966,
      "name": "__btf_kfunc_id_set_contains",
      "external": false,
      "loc": "kernel/bpf/btf.c:7095",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_kfunc_id_set_contains"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__btf_kfunc_id_set_contains",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582100603,
      "name": "__btf_kfunc_id_set_contains",
      "external": false,
      "loc": "kernel/bpf/btf.c:7557",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_kfunc_is_modify_return",
        "kernel/bpf/btf.c:btf_kfunc_id_set_contains",
        "kernel/bpf/btf.c:btf_kfunc_id_set_contains"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
u32 * __btf_kfunc_id_set_contains(const struct btf * btf, enum btf_kfunc_hook hook, u32 kfunc_btf_id, const struct bpf_prog * prog)
```

```json
{
  "name": "__btf_kfunc_id_set_contains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582224416,
      "name": "__btf_kfunc_id_set_contains",
      "external": false,
      "loc": "kernel/bpf/btf.c:7787",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_kfunc_is_modify_return",
        "kernel/bpf/btf.c:btf_kfunc_id_set_contains",
        "kernel/bpf/btf.c:btf_kfunc_id_set_contains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582224416,
      "name": "__btf_kfunc_id_set_contains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
u32 * __btf_kfunc_id_set_contains(const struct btf * btf, enum btf_kfunc_hook hook, u32 kfunc_btf_id, const struct bpf_prog * prog)
```

```json
{
  "name": "__btf_kfunc_id_set_contains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582380368,
      "name": "__btf_kfunc_id_set_contains",
      "external": false,
      "loc": "kernel/bpf/btf.c:7851",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_kfunc_is_modify_return",
        "kernel/bpf/btf.c:btf_kfunc_id_set_contains",
        "kernel/bpf/btf.c:btf_kfunc_id_set_contains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582380368,
      "name": "__btf_kfunc_id_set_contains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
u32 * __btf_kfunc_id_set_contains(const struct btf * btf, enum btf_kfunc_hook hook, u32 kfunc_btf_id, const struct bpf_prog * prog)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
