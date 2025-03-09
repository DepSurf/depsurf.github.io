# Function: <code>__sock_recv_cmsgs</code>

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
void __sock_recv_cmsgs(struct msghdr * msg, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "__sock_recv_cmsgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591328112,
      "name": "__sock_recv_cmsgs",
      "external": true,
      "loc": "net/socket.c:979",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg",
        "net/mctp/af_mctp.c:mctp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591328112,
      "name": "__sock_recv_cmsgs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
void __sock_recv_cmsgs(struct msghdr * msg, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "__sock_recv_cmsgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593082416,
      "name": "__sock_recv_cmsgs",
      "external": true,
      "loc": "net/socket.c:984",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg",
        "net/mctp/af_mctp.c:mctp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593082416,
      "name": "__sock_recv_cmsgs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
void __sock_recv_cmsgs(struct msghdr * msg, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "__sock_recv_cmsgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593531856,
      "name": "__sock_recv_cmsgs",
      "external": true,
      "loc": "net/socket.c:1002",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg",
        "net/mctp/af_mctp.c:mctp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593531856,
      "name": "__sock_recv_cmsgs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
void __sock_recv_cmsgs(struct msghdr * msg, struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "__sock_recv_cmsgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594304400,
      "name": "__sock_recv_cmsgs",
      "external": true,
      "loc": "net/socket.c:1024",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/raw.c:rawv6_recvmsg",
        "net/packet/af_packet.c:packet_recvmsg",
        "net/mctp/af_mctp.c:mctp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594304400,
      "name": "__sock_recv_cmsgs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
void __sock_recv_cmsgs(struct msghdr * msg, struct sock * sk, struct sk_buff * skb)
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
