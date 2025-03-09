# Function: <code>register_btf_kfunc_id_set</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int register_btf_kfunc_id_set(enum bpf_prog_type prog_type, const struct btf_kfunc_id_set * kset)
```

```json
{
  "name": "register_btf_kfunc_id_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593961424,
      "name": "register_btf_kfunc_id_set",
      "external": true,
      "loc": "kernel/bpf/btf.c:7148",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_init",
        "net/ipv4/tcp_cubic.c:cubictcp_register",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_kfunc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593961404,
      "name": "register_btf_kfunc_id_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071581677472,
      "name": "register_btf_kfunc_id_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int register_btf_kfunc_id_set(enum bpf_prog_type prog_type, const struct btf_kfunc_id_set * kset)
```

```json
{
  "name": "register_btf_kfunc_id_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582072064,
      "name": "register_btf_kfunc_id_set",
      "external": true,
      "loc": "kernel/bpf/btf.c:7653",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:bpf_rstat_kfunc_init",
        "kernel/trace/bpf_trace.c:bpf_key_sig_kfuncs_init",
        "kernel/bpf/helpers.c:kfunc_init",
        "kernel/bpf/helpers.c:kfunc_init",
        "kernel/bpf/helpers.c:kfunc_init",
        "kernel/bpf/helpers.c:kfunc_init",
        "net/bpf/test_run.c:bpf_prog_test_run_init",
        "net/bpf/test_run.c:bpf_prog_test_run_init",
        "net/bpf/test_run.c:bpf_prog_test_run_init",
        "net/ipv4/tcp_cubic.c:cubictcp_register",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_kfunc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582072064,
      "name": "register_btf_kfunc_id_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int register_btf_kfunc_id_set(enum bpf_prog_type prog_type, const struct btf_kfunc_id_set * kset)
```

```json
{
  "name": "register_btf_kfunc_id_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582268176,
      "name": "register_btf_kfunc_id_set",
      "external": true,
      "loc": "kernel/bpf/btf.c:7914",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:bpf_rstat_kfunc_init",
        "kernel/trace/bpf_trace.c:bpf_key_sig_kfuncs_init",
        "kernel/bpf/helpers.c:kfunc_init",
        "kernel/bpf/helpers.c:kfunc_init",
        "kernel/bpf/helpers.c:kfunc_init",
        "kernel/bpf/helpers.c:kfunc_init",
        "kernel/bpf/cpumask.c:cpumask_kfunc_init",
        "kernel/bpf/cpumask.c:cpumask_kfunc_init",
        "drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_init",
        "drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_init",
        "net/core/filter.c:init_subsystem",
        "net/core/filter.c:bpf_kfunc_init",
        "net/core/filter.c:bpf_kfunc_init",
        "net/core/filter.c:bpf_kfunc_init",
        "net/core/filter.c:bpf_kfunc_init",
        "net/core/filter.c:bpf_kfunc_init",
        "net/core/filter.c:bpf_kfunc_init",
        "net/core/filter.c:bpf_kfunc_init",
        "net/core/filter.c:bpf_kfunc_init",
        "net/core/filter.c:bpf_kfunc_init",
        "net/core/filter.c:bpf_kfunc_init",
        "net/core/filter.c:bpf_kfunc_init",
        "net/core/xdp.c:xdp_metadata_init",
        "net/bpf/test_run.c:bpf_prog_test_run_init",
        "net/bpf/test_run.c:bpf_prog_test_run_init",
        "net/bpf/test_run.c:bpf_prog_test_run_init",
        "net/ipv4/tcp_cubic.c:cubictcp_register",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_kfunc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582268176,
      "name": "register_btf_kfunc_id_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int register_btf_kfunc_id_set(enum bpf_prog_type prog_type, const struct btf_kfunc_id_set * kset)
```

```json
{
  "name": "register_btf_kfunc_id_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582423712,
      "name": "register_btf_kfunc_id_set",
      "external": true,
      "loc": "kernel/bpf/btf.c:7979",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:bpf_rstat_kfunc_init",
        "kernel/trace/bpf_trace.c:bpf_fs_kfuncs_init",
        "kernel/trace/bpf_trace.c:bpf_key_sig_kfuncs_init",
        "kernel/bpf/helpers.c:kfunc_init",
        "kernel/bpf/helpers.c:kfunc_init",
        "kernel/bpf/helpers.c:kfunc_init",
        "kernel/bpf/helpers.c:kfunc_init",
        "kernel/bpf/helpers.c:kfunc_init",
        "kernel/bpf/map_iter.c:init_subsystem",
        "kernel/bpf/cpumask.c:cpumask_kfunc_init",
        "kernel/bpf/cpumask.c:cpumask_kfunc_init",
        "fs/verity/measure.c:fsverity_init_bpf",
        "drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_init",
        "drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_init",
        "net/core/filter.c:init_subsystem",
        "net/core/filter.c:bpf_kfunc_init",
        "net/core/filter.c:bpf_kfunc_init",
        "net/core/filter.c:bpf_kfunc_init",
        "net/core/filter.c:bpf_kfunc_init",
        "net/core/filter.c:bpf_kfunc_init",
        "net/core/filter.c:bpf_kfunc_init",
        "net/core/filter.c:bpf_kfunc_init",
        "net/core/filter.c:bpf_kfunc_init",
        "net/core/filter.c:bpf_kfunc_init",
        "net/core/filter.c:bpf_kfunc_init",
        "net/core/filter.c:bpf_kfunc_init",
        "net/core/filter.c:bpf_kfunc_init",
        "net/core/xdp.c:xdp_metadata_init",
        "net/bpf/test_run.c:bpf_prog_test_run_init",
        "net/bpf/test_run.c:bpf_prog_test_run_init",
        "net/bpf/test_run.c:bpf_prog_test_run_init",
        "net/ipv4/tcp_cubic.c:cubictcp_register",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_kfunc_init",
        "net/xfrm/xfrm_state_bpf.c:register_xfrm_state_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582423712,
      "name": "register_btf_kfunc_id_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int register_btf_kfunc_id_set(enum bpf_prog_type prog_type, const struct btf_kfunc_id_set * kset)
```
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
