# Function: <code>btf_get</code>

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
void btf_get(struct btf * btf)
```

```json
{
  "name": "btf_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581110880,
      "name": "btf_get",
      "external": true,
      "loc": "kernel/bpf/btf.c:1527",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581110880,
      "name": "btf_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void btf_get(struct btf * btf)
```

```json
{
  "name": "btf_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581129472,
      "name": "btf_get",
      "external": true,
      "loc": "kernel/bpf/btf.c:1528",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/verifier.c:check_pseudo_btf_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581129472,
      "name": "btf_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void btf_get(struct btf * btf)
```

```json
{
  "name": "btf_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581361890,
      "name": "btf_get",
      "external": true,
      "loc": "kernel/bpf/btf.c:1528",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:bpf_btf_find_by_name_kind"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581361456,
      "name": "btf_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void btf_get(struct btf * btf)
```

```json
{
  "name": "btf_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581676885,
      "name": "btf_get",
      "external": true,
      "loc": "kernel/bpf/btf.c:1656",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:bpf_find_btf_id",
        "kernel/bpf/btf.c:bpf_find_btf_id"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_map_copy_kptr_off_tab",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581675696,
      "name": "btf_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void btf_get(struct btf * btf)
```

```json
{
  "name": "btf_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582071285,
      "name": "btf_get",
      "external": true,
      "loc": "kernel/bpf/btf.c:1679",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:bpf_find_btf_id",
        "kernel/bpf/btf.c:bpf_find_btf_id"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:btf_record_dup",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582069968,
      "name": "btf_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void btf_get(struct btf * btf)
```

```json
{
  "name": "btf_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582289914,
      "name": "btf_get",
      "external": true,
      "loc": "kernel/bpf/btf.c:1709",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_parse_kptr",
        "kernel/bpf/btf.c:bpf_find_btf_id",
        "kernel/bpf/btf.c:bpf_find_btf_id"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:btf_record_dup",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582265760,
      "name": "btf_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void btf_get(struct btf * btf)
```

```json
{
  "name": "btf_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582447402,
      "name": "btf_get",
      "external": true,
      "loc": "kernel/bpf/btf.c:1710",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_parse_kptr",
        "kernel/bpf/btf.c:bpf_find_btf_id",
        "kernel/bpf/btf.c:bpf_find_btf_id"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:btf_record_dup",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/map_in_map.c:bpf_map_meta_alloc",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582421200,
      "name": "btf_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void btf_get(struct btf * btf)
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
