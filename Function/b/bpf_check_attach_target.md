# Function: <code>bpf_check_attach_target</code>

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
int bpf_check_attach_target(struct bpf_verifier_log * log, const struct bpf_prog * prog, const struct bpf_prog * tgt_prog, u32 btf_id, struct bpf_attach_target_info * tgt_info)
```

```json
{
  "name": "bpf_check_attach_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581023568,
      "name": "bpf_check_attach_target",
      "external": true,
      "loc": "kernel/bpf/verifier.c:11643",
      "file": "kernel/bpf/verifier.c",
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
      "addr": 18446744071581023568,
      "name": "bpf_check_attach_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1911
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
int bpf_check_attach_target(struct bpf_verifier_log * log, const struct bpf_prog * prog, const struct bpf_prog * tgt_prog, u32 btf_id, struct bpf_attach_target_info * tgt_info)
```

```json
{
  "name": "bpf_check_attach_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581033856,
      "name": "bpf_check_attach_target",
      "external": true,
      "loc": "kernel/bpf/verifier.c:12954",
      "file": "kernel/bpf/verifier.c",
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
      "addr": 18446744071581033856,
      "name": "bpf_check_attach_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1919
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_check_attach_target(struct bpf_verifier_log * log, const struct bpf_prog * prog, const struct bpf_prog * tgt_prog, u32 btf_id, struct bpf_attach_target_info * tgt_info)
```

```json
{
  "name": "bpf_check_attach_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_check_attach_target",
      "external": true,
      "loc": "kernel/bpf/verifier.c:13390",
      "file": "kernel/bpf/verifier.c",
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
      "addr": 18446744071592185598,
      "name": "bpf_check_attach_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071581256880,
      "name": "bpf_check_attach_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1914
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_check_attach_target(struct bpf_verifier_log * log, const struct bpf_prog * prog, const struct bpf_prog * tgt_prog, u32 btf_id, struct bpf_attach_target_info * tgt_info)
```

```json
{
  "name": "bpf_check_attach_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_check_attach_target",
      "external": true,
      "loc": "kernel/bpf/verifier.c:14554",
      "file": "kernel/bpf/verifier.c",
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
      "addr": 18446744071593959871,
      "name": "bpf_check_attach_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071581547744,
      "name": "bpf_check_attach_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1753
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_check_attach_target(struct bpf_verifier_log * log, const struct bpf_prog * prog, const struct bpf_prog * tgt_prog, u32 btf_id, struct bpf_attach_target_info * tgt_info)
```

```json
{
  "name": "bpf_check_attach_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_check_attach_target",
      "external": true,
      "loc": "kernel/bpf/verifier.c:16711",
      "file": "kernel/bpf/verifier.c",
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
      "addr": 18446744071596020403,
      "name": "bpf_check_attach_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071581919152,
      "name": "bpf_check_attach_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1888
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_check_attach_target(struct bpf_verifier_log * log, const struct bpf_prog * prog, const struct bpf_prog * tgt_prog, u32 btf_id, struct bpf_attach_target_info * tgt_info)
```

```json
{
  "name": "bpf_check_attach_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_check_attach_target",
      "external": true,
      "loc": "kernel/bpf/verifier.c:18995",
      "file": "kernel/bpf/verifier.c",
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
      "addr": 18446744071596541748,
      "name": "bpf_check_attach_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071582101632,
      "name": "bpf_check_attach_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2053
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_check_attach_target(struct bpf_verifier_log * log, const struct bpf_prog * prog, const struct bpf_prog * tgt_prog, u32 btf_id, struct bpf_attach_target_info * tgt_info)
```

```json
{
  "name": "bpf_check_attach_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_check_attach_target",
      "external": true,
      "loc": "kernel/bpf/verifier.c:20322",
      "file": "kernel/bpf/verifier.c",
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
      "addr": 18446744071597444587,
      "name": "bpf_check_attach_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071582241504,
      "name": "bpf_check_attach_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2334
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
int bpf_check_attach_target(struct bpf_verifier_log * log, const struct bpf_prog * prog, const struct bpf_prog * tgt_prog, u32 btf_id, struct bpf_attach_target_info * tgt_info)
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
