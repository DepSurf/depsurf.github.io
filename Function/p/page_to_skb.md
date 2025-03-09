# Function: <code>page_to_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * page_to_skb(struct virtnet_info * vi, struct receive_queue * rq, struct page * page, unsigned int offset, unsigned int len, unsigned int truesize)
```

```json
{
  "name": "page_to_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585074912,
      "name": "page_to_skb",
      "external": false,
      "loc": "drivers/net/virtio_net.c:246",
      "file": "drivers/net/virtio_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/virtio_net.c:virtnet_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585074912,
      "name": "page_to_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 788
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_to_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585467696,
      "name": "page_to_skb",
      "external": false,
      "loc": "drivers/net/virtio_net.c:252",
      "file": "drivers/net/virtio_net.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/virtio_net.c:virtnet_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585467696,
      "name": "page_to_skb.isra.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 757
    }
  ]
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
struct sk_buff * page_to_skb(struct virtnet_info * vi, struct receive_queue * rq, struct page * page, unsigned int offset, unsigned int len, unsigned int truesize, unsigned int headroom)
```

```json
{
  "name": "page_to_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_to_skb",
      "external": false,
      "loc": "drivers/net/virtio_net.c:465",
      "file": "drivers/net/virtio_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:receive_buf",
        "drivers/net/virtio_net.c:receive_mergeable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591768896,
      "name": "page_to_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1558
    },
    {
      "addr": 18446744071596796513,
      "name": "page_to_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
struct sk_buff * page_to_skb(struct virtnet_info * vi, struct receive_queue * rq, struct page * page, unsigned int offset, unsigned int len, unsigned int truesize, unsigned int headroom)
```

```json
{
  "name": "page_to_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_to_skb",
      "external": false,
      "loc": "drivers/net/virtio_net.c:526",
      "file": "drivers/net/virtio_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:receive_buf",
        "drivers/net/virtio_net.c:receive_mergeable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592516336,
      "name": "page_to_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1562
    },
    {
      "addr": 18446744071597720056,
      "name": "page_to_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
struct sk_buff * page_to_skb(struct virtnet_info * vi, struct receive_queue * rq, struct page * page, unsigned int offset, unsigned int len, unsigned int truesize)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
struct sk_buff * page_to_skb(struct virtnet_info * vi, struct receive_queue * rq, struct page * page, unsigned int offset, unsigned int len, unsigned int truesize, unsigned int headroom)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
