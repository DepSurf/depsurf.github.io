# Function: <code>receive_small</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "receive_small",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585083875,
      "name": "receive_small",
      "external": false,
      "loc": "drivers/net/virtio_net.c:320",
      "file": "drivers/net/virtio_net.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:virtnet_receive"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "receive_small",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585476844,
      "name": "receive_small",
      "external": false,
      "loc": "drivers/net/virtio_net.c:326",
      "file": "drivers/net/virtio_net.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:virtnet_receive"
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * receive_small(struct net_device * dev, struct virtnet_info * vi, struct receive_queue * rq, void * buf, void * ctx, unsigned int len, unsigned int * xdp_xmit, struct virtnet_rq_stats * stats)
```

```json
{
  "name": "receive_small",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "receive_small",
      "external": false,
      "loc": "drivers/net/virtio_net.c:1061",
      "file": "drivers/net/virtio_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:receive_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591775584,
      "name": "receive_small",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 770
    },
    {
      "addr": 18446744071596796823,
      "name": "receive_small.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
struct sk_buff * receive_small(struct net_device * dev, struct virtnet_info * vi, struct receive_queue * rq, void * buf, void * ctx, unsigned int len, unsigned int * xdp_xmit, struct virtnet_rq_stats * stats)
```

```json
{
  "name": "receive_small",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "receive_small",
      "external": false,
      "loc": "drivers/net/virtio_net.c:1275",
      "file": "drivers/net/virtio_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:receive_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592522768,
      "name": "receive_small",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 767
    },
    {
      "addr": 18446744071597720390,
      "name": "receive_small.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
struct sk_buff * receive_small(struct net_device * dev, struct virtnet_info * vi, struct receive_queue * rq, void * buf, void * ctx, unsigned int len, unsigned int * xdp_xmit, struct virtnet_rq_stats * stats)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
