# Function: <code>tcp_inbound_md5_hash</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
enum skb_drop_reason tcp_inbound_md5_hash(const struct sock * sk, const struct sk_buff * skb, const void * saddr, const void * daddr, int family, int dif, int sdif)
```

```json
{
  "name": "tcp_inbound_md5_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_inbound_md5_hash",
      "external": true,
      "loc": "net/ipv4/tcp.c:4446",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594601129,
      "name": "tcp_inbound_md5_hash.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071592377392,
      "name": "tcp_inbound_md5_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
enum skb_drop_reason tcp_inbound_md5_hash(const struct sock * sk, const struct sk_buff * skb, const void * saddr, const void * daddr, int family, int dif, int sdif)
```

```json
{
  "name": "tcp_inbound_md5_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594226960,
      "name": "tcp_inbound_md5_hash",
      "external": true,
      "loc": "net/ipv4/tcp.c:4556",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594226960,
      "name": "tcp_inbound_md5_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
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
enum skb_drop_reason tcp_inbound_md5_hash(const struct sock * sk, const struct sk_buff * skb, const void * saddr, const void * daddr, int family, int dif, int sdif)
```

```json
{
  "name": "tcp_inbound_md5_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594613808,
      "name": "tcp_inbound_md5_hash",
      "external": true,
      "loc": "net/ipv4/tcp.c:4452",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594613808,
      "name": "tcp_inbound_md5_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 701
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
enum skb_drop_reason tcp_inbound_md5_hash(const struct sock * sk, const struct sk_buff * skb, const void * saddr, const void * daddr, int family, int l3index, const __u8 * hash_location)
```

```json
{
  "name": "tcp_inbound_md5_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595422464,
      "name": "tcp_inbound_md5_hash",
      "external": true,
      "loc": "net/ipv4/tcp.c:4431",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595422464,
      "name": "tcp_inbound_md5_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1363
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
enum skb_drop_reason tcp_inbound_md5_hash(const struct sock * sk, const struct sk_buff * skb, const void * saddr, const void * daddr, int family, int dif, int sdif)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int l3index</code>
</li>
<li>
<b>Param added. </b>
<code>const __u8 * hash_location</code>
</li>
<li>
<b>Param removed. </b>
<code>int dif</code>
</li>
<li>
<b>Param removed. </b>
<code>int sdif</code>
</li>
</ul>
</details>
</li>
</ul>
