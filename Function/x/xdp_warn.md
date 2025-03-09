# Function: <code>xdp_warn</code>

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
void xdp_warn(const char * msg, const char * func, const int line)
```

```json
{
  "name": "xdp_warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589549600,
      "name": "xdp_warn",
      "external": true,
      "loc": "net/core/xdp.c:474",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:dev_xdp_enqueue",
        "kernel/bpf/cpumap.c:cpu_map_enqueue",
        "drivers/net/tun.c:tun_xdp_act"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589549600,
      "name": "xdp_warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void xdp_warn(const char * msg, const char * func, const int line)
```

```json
{
  "name": "xdp_warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589558656,
      "name": "xdp_warn",
      "external": true,
      "loc": "net/core/xdp.c:511",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:dev_xdp_enqueue",
        "kernel/bpf/cpumap.c:cpu_map_enqueue",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "drivers/net/tun.c:tun_xdp_act"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589558656,
      "name": "xdp_warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void xdp_warn(const char * msg, const char * func, const int line)
```

```json
{
  "name": "xdp_warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589456608,
      "name": "xdp_warn",
      "external": true,
      "loc": "net/core/xdp.c:512",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:dev_xdp_enqueue",
        "kernel/bpf/cpumap.c:cpu_map_enqueue",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "drivers/net/tun.c:tun_xdp_act"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589456608,
      "name": "xdp_warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void xdp_warn(const char * msg, const char * func, const int line)
```

```json
{
  "name": "xdp_warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590194048,
      "name": "xdp_warn",
      "external": true,
      "loc": "net/core/xdp.c:513",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_enqueue_multi",
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:dev_xdp_enqueue",
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run",
        "kernel/bpf/cpumap.c:cpu_map_enqueue",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "drivers/net/tun.c:tun_xdp_act"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590194048,
      "name": "xdp_warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void xdp_warn(const char * msg, const char * func, const int line)
```

```json
{
  "name": "xdp_warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591757408,
      "name": "xdp_warn",
      "external": true,
      "loc": "net/core/xdp.c:599",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "drivers/net/tun.c:tun_xdp_act",
        "net/core/filter.c:xdp_do_redirect",
        "net/bpf/test_run.c:xdp_test_run_init_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591757408,
      "name": "xdp_warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void xdp_warn(const char * msg, const char * func, const int line)
```

```json
{
  "name": "xdp_warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593548432,
      "name": "xdp_warn",
      "external": true,
      "loc": "net/core/xdp.c:597",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "drivers/net/tun.c:tun_xdp_act",
        "net/core/filter.c:xdp_do_redirect",
        "net/bpf/test_run.c:xdp_test_run_init_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593548432,
      "name": "xdp_warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void xdp_warn(const char * msg, const char * func, const int line)
```

```json
{
  "name": "xdp_warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594017136,
      "name": "xdp_warn",
      "external": true,
      "loc": "net/core/xdp.c:584",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "drivers/net/tun.c:tun_xdp_act",
        "drivers/net/virtio_net.c:virtnet_xdp_handler",
        "net/core/filter.c:xdp_do_redirect",
        "net/bpf/test_run.c:xdp_test_run_init_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594017136,
      "name": "xdp_warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void xdp_warn(const char * msg, const char * func, const int line)
```

```json
{
  "name": "xdp_warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594803504,
      "name": "xdp_warn",
      "external": true,
      "loc": "net/core/xdp.c:584",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "drivers/net/tun.c:tun_xdp_act",
        "drivers/net/virtio_net.c:virtnet_xdp_handler",
        "net/core/filter.c:xdp_do_redirect",
        "net/bpf/test_run.c:xdp_test_run_init_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594803504,
      "name": "xdp_warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void xdp_warn(const char * msg, const char * func, const int line)
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
