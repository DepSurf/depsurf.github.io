# Function: <code>btf_obj_id</code>

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
u32 btf_obj_id(const struct btf * btf)
```

```json
{
  "name": "btf_obj_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581125872,
      "name": "btf_obj_id",
      "external": true,
      "loc": "kernel/bpf/btf.c:5736",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/verifier.c:check_attach_btf_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581125872,
      "name": "btf_obj_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
u32 btf_obj_id(const struct btf * btf)
```

```json
{
  "name": "btf_obj_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581145760,
      "name": "btf_obj_id",
      "external": true,
      "loc": "kernel/bpf/btf.c:5929",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/verifier.c:check_attach_btf_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581145760,
      "name": "btf_obj_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
u32 btf_obj_id(const struct btf * btf)
```

```json
{
  "name": "btf_obj_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581379136,
      "name": "btf_obj_id",
      "external": true,
      "loc": "kernel/bpf/btf.c:5982",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/verifier.c:check_attach_btf_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581379136,
      "name": "btf_obj_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
u32 btf_obj_id(const struct btf * btf)
```

```json
{
  "name": "btf_obj_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581694112,
      "name": "btf_obj_id",
      "external": true,
      "loc": "kernel/bpf/btf.c:6715",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/verifier.c:check_attach_btf_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581694112,
      "name": "btf_obj_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
u32 btf_obj_id(const struct btf * btf)
```

```json
{
  "name": "btf_obj_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582093072,
      "name": "btf_obj_id",
      "external": true,
      "loc": "kernel/bpf/btf.c:7206",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_prog_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/verifier.c:check_attach_btf_id",
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582093072,
      "name": "btf_obj_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
u32 btf_obj_id(const struct btf * btf)
```

```json
{
  "name": "btf_obj_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582289200,
      "name": "btf_obj_id",
      "external": true,
      "loc": "kernel/bpf/btf.c:7305",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_prog_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/verifier.c:check_attach_btf_id",
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582289200,
      "name": "btf_obj_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
u32 btf_obj_id(const struct btf * btf)
```

```json
{
  "name": "btf_obj_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582446688,
      "name": "btf_obj_id",
      "external": true,
      "loc": "kernel/bpf/btf.c:7369",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_prog_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/verifier.c:check_attach_btf_id",
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582446688,
      "name": "btf_obj_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
u32 btf_obj_id(const struct btf * btf)
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
