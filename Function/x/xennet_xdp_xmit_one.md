# Function: <code>xennet_xdp_xmit_one</code>

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
int xennet_xdp_xmit_one(struct net_device * dev, struct netfront_queue * queue, struct xdp_frame * xdpf)
```

```json
{
  "name": "xennet_xdp_xmit_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587923632,
      "name": "xennet_xdp_xmit_one",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:577",
      "file": "drivers/net/xen-netfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_xdp_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587923632,
      "name": "xennet_xdp_xmit_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xennet_xdp_xmit_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587799338,
      "name": "xennet_xdp_xmit_one",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:577",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_xdp_xmit"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xennet_xdp_xmit_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588403045,
      "name": "xennet_xdp_xmit_one",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:605",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_xdp_xmit"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xennet_xdp_xmit_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589798645,
      "name": "xennet_xdp_xmit_one",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:611",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_xdp_xmit"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xennet_xdp_xmit_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591454501,
      "name": "xennet_xdp_xmit_one",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:611",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_xdp_xmit"
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
  "name": "xennet_xdp_xmit_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591870005,
      "name": "xennet_xdp_xmit_one",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:611",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_xdp_xmit"
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
  "name": "xennet_xdp_xmit_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592609762,
      "name": "xennet_xdp_xmit_one",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:612",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_xdp_xmit"
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
int xennet_xdp_xmit_one(struct net_device * dev, struct netfront_queue * queue, struct xdp_frame * xdpf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int xennet_xdp_xmit_one(struct net_device * dev, struct netfront_queue * queue, struct xdp_frame * xdpf)
```
</details>
</li>
</ul>
