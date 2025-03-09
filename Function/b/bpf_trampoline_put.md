# Function: <code>bpf_trampoline_put</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void bpf_trampoline_put(struct bpf_trampoline * tr)
```

```json
{
  "name": "bpf_trampoline_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581069456,
      "name": "bpf_trampoline_put",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:334",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_free_deferred",
        "kernel/bpf/verifier.c:check_attach_btf_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069456,
      "name": "bpf_trampoline_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void bpf_trampoline_put(struct bpf_trampoline * tr)
```

```json
{
  "name": "bpf_trampoline_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581084048,
      "name": "bpf_trampoline_put",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:468",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_free_deferred",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_link_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581084048,
      "name": "bpf_trampoline_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void bpf_trampoline_put(struct bpf_trampoline * tr)
```

```json
{
  "name": "bpf_trampoline_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581102384,
      "name": "bpf_trampoline_put",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:498",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_free_deferred",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_link_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581102384,
      "name": "bpf_trampoline_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void bpf_trampoline_put(struct bpf_trampoline * tr)
```

```json
{
  "name": "bpf_trampoline_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581332016,
      "name": "bpf_trampoline_put",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:504",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_free_deferred",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_link_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581332016,
      "name": "bpf_trampoline_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void bpf_trampoline_put(struct bpf_trampoline * tr)
```

```json
{
  "name": "bpf_trampoline_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581636752,
      "name": "bpf_trampoline_put",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:516",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_free_deferred",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_link_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581636752,
      "name": "bpf_trampoline_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void bpf_trampoline_put(struct bpf_trampoline * tr)
```

```json
{
  "name": "bpf_trampoline_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582026260,
      "name": "bpf_trampoline_put",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:813",
      "file": "kernel/bpf/trampoline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_free_deferred",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_link_release",
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582024720,
      "name": "bpf_trampoline_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 18446744071582026496,
      "name": "bpf_trampoline_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void bpf_trampoline_put(struct bpf_trampoline * tr)
```

```json
{
  "name": "bpf_trampoline_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582218548,
      "name": "bpf_trampoline_put",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:791",
      "file": "kernel/bpf/trampoline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_free_deferred",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_link_release",
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582216688,
      "name": "bpf_trampoline_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 18446744071582218784,
      "name": "bpf_trampoline_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void bpf_trampoline_put(struct bpf_trampoline * tr)
```

```json
{
  "name": "bpf_trampoline_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582373748,
      "name": "bpf_trampoline_put",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:802",
      "file": "kernel/bpf/trampoline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_free_deferred",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_link_release",
        "kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582371952,
      "name": "bpf_trampoline_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 18446744071582373984,
      "name": "bpf_trampoline_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void bpf_trampoline_put(struct bpf_trampoline * tr)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
