# Function: <code>btf_id_set_contains</code>

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
bool btf_id_set_contains(const struct btf_id_set * set, u32 id)
```

```json
{
  "name": "btf_id_set_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581125920,
      "name": "btf_id_set_contains",
      "external": true,
      "loc": "kernel/bpf/btf.c:5753",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash_allowed",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581125920,
      "name": "btf_id_set_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
bool btf_id_set_contains(const struct btf_id_set * set, u32 id)
```

```json
{
  "name": "btf_id_set_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581145856,
      "name": "btf_id_set_contains",
      "external": true,
      "loc": "kernel/bpf/btf.c:5951",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_attach_btf_id",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash_allowed",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog",
        "net/bpf/test_run.c:bpf_prog_test_check_kfunc_call",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_check_kfunc_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581145856,
      "name": "btf_id_set_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
bool btf_id_set_contains(const struct btf_id_set * set, u32 id)
```

```json
{
  "name": "btf_id_set_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581379264,
      "name": "btf_id_set_contains",
      "external": true,
      "loc": "kernel/bpf/btf.c:6004",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_attach_btf_id",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash_allowed",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog",
        "net/bpf/test_run.c:bpf_prog_test_check_kfunc_call",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_check_kfunc_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581379264,
      "name": "btf_id_set_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
bool btf_id_set_contains(const struct btf_id_set * set, u32 id)
```

```json
{
  "name": "btf_id_set_contains",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581696012,
      "name": "btf_id_set_contains",
      "external": true,
      "loc": "kernel/bpf/btf.c:6737",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_kfunc_id_set_contains"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_attach_btf_id",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash_allowed",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581694272,
      "name": "btf_id_set_contains",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_id_set_contains",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581625030,
      "name": "btf_id_set_contains",
      "external": false,
      "loc": "include/linux/btf.h:460",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581921742,
      "name": "btf_id_set_contains",
      "external": false,
      "loc": "include/linux/btf.h:460",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_attach_btf_id",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:check_kfunc_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582098800,
      "name": "btf_id_set_contains",
      "external": false,
      "loc": "include/linux/btf.h:460",
      "file": "kernel/bpf/btf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582188097,
      "name": "btf_id_set_contains",
      "external": false,
      "loc": "include/linux/btf.h:460",
      "file": "kernel/bpf/bpf_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lsm.c:bpf_lsm_is_trusted",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto",
        "kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash_allowed",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_find_cgroup_shim"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_id_set_contains",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581764486,
      "name": "btf_id_set_contains",
      "external": false,
      "loc": "include/linux/btf.h:476",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582104461,
      "name": "btf_id_set_contains",
      "external": false,
      "loc": "include/linux/btf.h:476",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_attach_btf_id",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582292994,
      "name": "btf_id_set_contains",
      "external": false,
      "loc": "include/linux/btf.h:476",
      "file": "kernel/bpf/btf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582387937,
      "name": "btf_id_set_contains",
      "external": false,
      "loc": "include/linux/btf.h:476",
      "file": "kernel/bpf/bpf_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lsm.c:bpf_lsm_is_trusted",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto",
        "kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash_allowed",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_find_cgroup_shim"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_id_set_contains",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581883382,
      "name": "btf_id_set_contains",
      "external": false,
      "loc": "include/linux/btf.h:487",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582244662,
      "name": "btf_id_set_contains",
      "external": false,
      "loc": "include/linux/btf.h:487",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_attach_btf_id",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582450514,
      "name": "btf_id_set_contains",
      "external": false,
      "loc": "include/linux/btf.h:487",
      "file": "kernel/bpf/btf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582555537,
      "name": "btf_id_set_contains",
      "external": false,
      "loc": "include/linux/btf.h:487",
      "file": "kernel/bpf/bpf_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lsm.c:bpf_lsm_is_trusted",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto",
        "kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash_allowed",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_find_cgroup_shim"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
bool btf_id_set_contains(const struct btf_id_set * set, u32 id)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
bool btf_id_set_contains(const struct btf_id_set * set, u32 id)
```
</details>
</li>
</ul>
