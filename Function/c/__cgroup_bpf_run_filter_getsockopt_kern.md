# Function: <code>__cgroup_bpf_run_filter_getsockopt_kern</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_getsockopt_kern(struct sock * sk, int level, int optname, void * optval, int * optlen, int retval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_getsockopt_kern",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581186400,
      "name": "__cgroup_bpf_run_filter_getsockopt_kern",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1535",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581186400,
      "name": "__cgroup_bpf_run_filter_getsockopt_kern",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 574
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
int __cgroup_bpf_run_filter_getsockopt_kern(struct sock * sk, int level, int optname, void * optval, int * optlen, int retval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_getsockopt_kern",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581426560,
      "name": "__cgroup_bpf_run_filter_getsockopt_kern",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1565",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581426560,
      "name": "__cgroup_bpf_run_filter_getsockopt_kern",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
int __cgroup_bpf_run_filter_getsockopt_kern(struct sock * sk, int level, int optname, void * optval, int * optlen, int retval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_getsockopt_kern",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581752752,
      "name": "__cgroup_bpf_run_filter_getsockopt_kern",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1703",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581752752,
      "name": "__cgroup_bpf_run_filter_getsockopt_kern",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int __cgroup_bpf_run_filter_getsockopt_kern(struct sock * sk, int level, int optname, void * optval, int * optlen, int retval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_getsockopt_kern",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582167856,
      "name": "__cgroup_bpf_run_filter_getsockopt_kern",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1942",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582167856,
      "name": "__cgroup_bpf_run_filter_getsockopt_kern",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int __cgroup_bpf_run_filter_getsockopt_kern(struct sock * sk, int level, int optname, void * optval, int * optlen, int retval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_getsockopt_kern",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582365008,
      "name": "__cgroup_bpf_run_filter_getsockopt_kern",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1960",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582365008,
      "name": "__cgroup_bpf_run_filter_getsockopt_kern",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int __cgroup_bpf_run_filter_getsockopt_kern(struct sock * sk, int level, int optname, void * optval, int * optlen, int retval)
```

```json
{
  "name": "__cgroup_bpf_run_filter_getsockopt_kern",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582532064,
      "name": "__cgroup_bpf_run_filter_getsockopt_kern",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1978",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582532064,
      "name": "__cgroup_bpf_run_filter_getsockopt_kern",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int __cgroup_bpf_run_filter_getsockopt_kern(struct sock * sk, int level, int optname, void * optval, int * optlen, int retval)
```
</details>
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
