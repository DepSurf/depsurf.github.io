# Function: <code>dev_map_enqueue_multi</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int dev_map_enqueue_multi(struct xdp_buff * xdp, struct net_device * dev_rx, struct bpf_map * map, bool exclude_ingress)
```

```json
{
  "name": "dev_map_enqueue_multi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581386832,
      "name": "dev_map_enqueue_multi",
      "external": true,
      "loc": "kernel/bpf/devmap.c:589",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581386832,
      "name": "dev_map_enqueue_multi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 904
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
int dev_map_enqueue_multi(struct xdp_frame * xdpf, struct net_device * dev_rx, struct bpf_map * map, bool exclude_ingress)
```

```json
{
  "name": "dev_map_enqueue_multi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581709744,
      "name": "dev_map_enqueue_multi",
      "external": true,
      "loc": "kernel/bpf/devmap.c:585",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_redirect_frame",
        "net/core/filter.c:xdp_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581709744,
      "name": "dev_map_enqueue_multi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 793
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
int dev_map_enqueue_multi(struct xdp_frame * xdpf, struct net_device * dev_rx, struct bpf_map * map, bool exclude_ingress)
```

```json
{
  "name": "dev_map_enqueue_multi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582116224,
      "name": "dev_map_enqueue_multi",
      "external": true,
      "loc": "kernel/bpf/devmap.c:585",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_redirect_frame",
        "net/core/filter.c:xdp_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582116224,
      "name": "dev_map_enqueue_multi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 719
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
int dev_map_enqueue_multi(struct xdp_frame * xdpf, struct net_device * dev_rx, struct bpf_map * map, bool exclude_ingress)
```

```json
{
  "name": "dev_map_enqueue_multi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582312352,
      "name": "dev_map_enqueue_multi",
      "external": true,
      "loc": "kernel/bpf/devmap.c:592",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_redirect_frame",
        "net/core/filter.c:xdp_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582312352,
      "name": "dev_map_enqueue_multi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
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
int dev_map_enqueue_multi(struct xdp_frame * xdpf, struct net_device * dev_rx, struct bpf_map * map, bool exclude_ingress)
```

```json
{
  "name": "dev_map_enqueue_multi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582473376,
      "name": "dev_map_enqueue_multi",
      "external": true,
      "loc": "kernel/bpf/devmap.c:601",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_redirect_frame",
        "net/core/filter.c:xdp_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582473376,
      "name": "dev_map_enqueue_multi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int dev_map_enqueue_multi(struct xdp_buff * xdp, struct net_device * dev_rx, struct bpf_map * map, bool exclude_ingress)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xdp_frame * xdpf</code>
</li>
<li>
<b>Param removed. </b>
<code>struct xdp_buff * xdp</code>
</li>
</ul>
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
