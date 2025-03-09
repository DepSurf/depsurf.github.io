# Function: <code>__xdp_build_skb_from_frame</code>

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
struct sk_buff * __xdp_build_skb_from_frame(struct xdp_frame * xdpf, struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "__xdp_build_skb_from_frame",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589460208,
      "name": "__xdp_build_skb_from_frame",
      "external": true,
      "loc": "net/core/xdp.c:529",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "net/core/xdp.c:xdp_build_skb_from_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589460208,
      "name": "__xdp_build_skb_from_frame",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
struct sk_buff * __xdp_build_skb_from_frame(struct xdp_frame * xdpf, struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "__xdp_build_skb_from_frame",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590197424,
      "name": "__xdp_build_skb_from_frame",
      "external": true,
      "loc": "net/core/xdp.c:530",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "net/core/xdp.c:xdp_build_skb_from_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590197424,
      "name": "__xdp_build_skb_from_frame",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
struct sk_buff * __xdp_build_skb_from_frame(struct xdp_frame * xdpf, struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "__xdp_build_skb_from_frame",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591760448,
      "name": "__xdp_build_skb_from_frame",
      "external": true,
      "loc": "net/core/xdp.c:616",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "net/core/xdp.c:xdp_build_skb_from_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591760448,
      "name": "__xdp_build_skb_from_frame",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
struct sk_buff * __xdp_build_skb_from_frame(struct xdp_frame * xdpf, struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "__xdp_build_skb_from_frame",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593552352,
      "name": "__xdp_build_skb_from_frame",
      "external": true,
      "loc": "net/core/xdp.c:614",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "net/core/xdp.c:xdp_build_skb_from_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593552352,
      "name": "__xdp_build_skb_from_frame",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 519
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
struct sk_buff * __xdp_build_skb_from_frame(struct xdp_frame * xdpf, struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "__xdp_build_skb_from_frame",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594017536,
      "name": "__xdp_build_skb_from_frame",
      "external": true,
      "loc": "net/core/xdp.c:600",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "net/core/xdp.c:xdp_build_skb_from_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594017536,
      "name": "__xdp_build_skb_from_frame",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
struct sk_buff * __xdp_build_skb_from_frame(struct xdp_frame * xdpf, struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "__xdp_build_skb_from_frame",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594803904,
      "name": "__xdp_build_skb_from_frame",
      "external": true,
      "loc": "net/core/xdp.c:600",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "net/core/xdp.c:xdp_build_skb_from_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594803904,
      "name": "__xdp_build_skb_from_frame",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
struct sk_buff * __xdp_build_skb_from_frame(struct xdp_frame * xdpf, struct sk_buff * skb, struct net_device * dev)
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
