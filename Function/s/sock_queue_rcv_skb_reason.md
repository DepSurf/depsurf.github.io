# Function: <code>sock_queue_rcv_skb_reason</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int sock_queue_rcv_skb_reason(struct sock * sk, struct sk_buff * skb, enum skb_drop_reason * reason)
```

```json
{
  "name": "sock_queue_rcv_skb_reason",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591356384,
      "name": "sock_queue_rcv_skb_reason",
      "external": true,
      "loc": "net/core/sock.c:511",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ping.c:__ping_queue_rcv_skb",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/mctp/route.c:mctp_route_input",
        "net/mctp/route.c:mctp_route_input",
        "net/mctp/route.c:mctp_route_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591356384,
      "name": "sock_queue_rcv_skb_reason",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int sock_queue_rcv_skb_reason(struct sock * sk, struct sk_buff * skb, enum skb_drop_reason * reason)
```

```json
{
  "name": "sock_queue_rcv_skb_reason",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593124528,
      "name": "sock_queue_rcv_skb_reason",
      "external": true,
      "loc": "net/core/sock.c:511",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ping.c:__ping_queue_rcv_skb",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/mctp/route.c:mctp_route_input",
        "net/mctp/route.c:mctp_route_input",
        "net/mctp/route.c:mctp_route_input",
        "net/mctp/route.c:mctp_route_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593124528,
      "name": "sock_queue_rcv_skb_reason",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int sock_queue_rcv_skb_reason(struct sock * sk, struct sk_buff * skb, enum skb_drop_reason * reason)
```

```json
{
  "name": "sock_queue_rcv_skb_reason",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593577264,
      "name": "sock_queue_rcv_skb_reason",
      "external": true,
      "loc": "net/core/sock.c:517",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ping.c:__ping_queue_rcv_skb",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/mctp/route.c:mctp_route_input",
        "net/mctp/route.c:mctp_route_input",
        "net/mctp/route.c:mctp_route_input",
        "net/mctp/route.c:mctp_route_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593577264,
      "name": "sock_queue_rcv_skb_reason",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int sock_queue_rcv_skb_reason(struct sock * sk, struct sk_buff * skb, enum skb_drop_reason * reason)
```

```json
{
  "name": "sock_queue_rcv_skb_reason",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594349744,
      "name": "sock_queue_rcv_skb_reason",
      "external": true,
      "loc": "net/core/sock.c:514",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ping.c:__ping_queue_rcv_skb",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/mctp/route.c:mctp_route_input",
        "net/mctp/route.c:mctp_route_input",
        "net/mctp/route.c:mctp_route_input",
        "net/mctp/route.c:mctp_route_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594349744,
      "name": "sock_queue_rcv_skb_reason",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int sock_queue_rcv_skb_reason(struct sock * sk, struct sk_buff * skb, enum skb_drop_reason * reason)
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
