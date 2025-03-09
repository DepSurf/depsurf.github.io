# Function: <code>bpf_trampoline_get</code>

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
struct bpf_trampoline * bpf_trampoline_get(u64 key, struct bpf_attach_target_info * tgt_info)
```

```json
{
  "name": "bpf_trampoline_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581083936,
      "name": "bpf_trampoline_get",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:448",
      "file": "kernel/bpf/trampoline.c",
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
      "addr": 18446744071581083936,
      "name": "bpf_trampoline_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
struct bpf_trampoline * bpf_trampoline_get(u64 key, struct bpf_attach_target_info * tgt_info)
```

```json
{
  "name": "bpf_trampoline_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581101968,
      "name": "bpf_trampoline_get",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:478",
      "file": "kernel/bpf/trampoline.c",
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
      "addr": 18446744071581101968,
      "name": "bpf_trampoline_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
struct bpf_trampoline * bpf_trampoline_get(u64 key, struct bpf_attach_target_info * tgt_info)
```

```json
{
  "name": "bpf_trampoline_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581331600,
      "name": "bpf_trampoline_get",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:484",
      "file": "kernel/bpf/trampoline.c",
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
      "addr": 18446744071581331600,
      "name": "bpf_trampoline_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
struct bpf_trampoline * bpf_trampoline_get(u64 key, struct bpf_attach_target_info * tgt_info)
```

```json
{
  "name": "bpf_trampoline_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581636304,
      "name": "bpf_trampoline_get",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:496",
      "file": "kernel/bpf/trampoline.c",
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
      "addr": 18446744071581636304,
      "name": "bpf_trampoline_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 439
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
struct bpf_trampoline * bpf_trampoline_get(u64 key, struct bpf_attach_target_info * tgt_info)
```

```json
{
  "name": "bpf_trampoline_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582026352,
      "name": "bpf_trampoline_get",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:793",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/verifier.c:check_attach_btf_id",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582026352,
      "name": "bpf_trampoline_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct bpf_trampoline * bpf_trampoline_get(u64 key, struct bpf_attach_target_info * tgt_info)
```

```json
{
  "name": "bpf_trampoline_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582218640,
      "name": "bpf_trampoline_get",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:771",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/verifier.c:check_attach_btf_id",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582218640,
      "name": "bpf_trampoline_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct bpf_trampoline * bpf_trampoline_get(u64 key, struct bpf_attach_target_info * tgt_info)
```

```json
{
  "name": "bpf_trampoline_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582373840,
      "name": "bpf_trampoline_get",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:782",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/verifier.c:check_attach_btf_id",
        "kernel/bpf/verifier.c:check_attach_btf_id",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582373840,
      "name": "bpf_trampoline_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct bpf_trampoline * bpf_trampoline_get(u64 key, struct bpf_attach_target_info * tgt_info)
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
