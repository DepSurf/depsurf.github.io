# Function: <code>xdp_do_flush</code>

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
void xdp_do_flush()
```

```json
{
  "name": "xdp_do_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589501312,
      "name": "xdp_do_flush",
      "external": true,
      "loc": "net/core/filter.c:3532",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589501312,
      "name": "xdp_do_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void xdp_do_flush()
```

```json
{
  "name": "xdp_do_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589503712,
      "name": "xdp_do_flush",
      "external": true,
      "loc": "net/core/filter.c:3939",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_build_skb",
        "drivers/net/xen-netfront.c:xennet_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589503712,
      "name": "xdp_do_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void xdp_do_flush()
```

```json
{
  "name": "xdp_do_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589401920,
      "name": "xdp_do_flush",
      "external": true,
      "loc": "net/core/filter.c:3918",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_build_skb",
        "drivers/net/xen-netfront.c:xennet_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589401920,
      "name": "xdp_do_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void xdp_do_flush()
```

```json
{
  "name": "xdp_do_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590128032,
      "name": "xdp_do_flush",
      "external": true,
      "loc": "net/core/filter.c:3914",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_build_skb",
        "drivers/net/xen-netfront.c:xennet_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590128032,
      "name": "xdp_do_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void xdp_do_flush()
```

```json
{
  "name": "xdp_do_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591679392,
      "name": "xdp_do_flush",
      "external": true,
      "loc": "net/core/filter.c:4134",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/xen-netfront.c:xennet_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591679392,
      "name": "xdp_do_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void xdp_do_flush()
```

```json
{
  "name": "xdp_do_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593465632,
      "name": "xdp_do_flush",
      "external": true,
      "loc": "net/core/filter.c:4148",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/xen-netfront.c:xennet_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593465632,
      "name": "xdp_do_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void xdp_do_flush()
```

```json
{
  "name": "xdp_do_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593932464,
      "name": "xdp_do_flush",
      "external": true,
      "loc": "net/core/filter.c:4202",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/virtio_net.c:virtnet_poll",
        "drivers/net/xen-netfront.c:xennet_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593932464,
      "name": "xdp_do_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void xdp_do_flush()
```

```json
{
  "name": "xdp_do_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594715296,
      "name": "xdp_do_flush",
      "external": true,
      "loc": "net/core/filter.c:4267",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/virtio_net.c:virtnet_poll",
        "drivers/net/xen-netfront.c:xennet_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594715296,
      "name": "xdp_do_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void xdp_do_flush()
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
