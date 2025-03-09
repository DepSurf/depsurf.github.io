# Function: <code>__ip_route_output_key_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct rtable * __ip_route_output_key_hash(struct net * net, struct flowi4 * fl4, int mp_hash)
```

```json
{
  "name": "__ip_route_output_key_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586538128,
      "name": "__ip_route_output_key_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2128",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_update_pmtu",
        "net/ipv4/route.c:ipv4_redirect",
        "net/ipv4/route.c:ipv4_sk_redirect",
        "net/ipv4/route.c:ip_route_output_flow",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/icmp.c:icmp_route_lookup",
        "net/ipv4/icmp.c:icmp_route_lookup",
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_lookup",
        "net/ipv4/xfrm4_policy.c:xfrm4_get_saddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586538128,
      "name": "__ip_route_output_key_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2193
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct rtable * __ip_route_output_key_hash(struct net * net, struct flowi4 * fl4, int mp_hash)
```

```json
{
  "name": "__ip_route_output_key_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586981040,
      "name": "__ip_route_output_key_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2147",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_flow",
        "net/ipv4/route.c:ipv4_sk_redirect",
        "net/ipv4/route.c:ipv4_redirect",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_update_pmtu",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/icmp.c:icmp_route_lookup",
        "net/ipv4/icmp.c:icmp_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586981040,
      "name": "__ip_route_output_key_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2336
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rtable * __ip_route_output_key_hash(struct net * net, struct flowi4 * fl4, int mp_hash)
```

```json
{
  "name": "__ip_route_output_key_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587171152,
      "name": "__ip_route_output_key_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2187",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_flow",
        "net/ipv4/route.c:ipv4_sk_redirect",
        "net/ipv4/route.c:ipv4_redirect",
        "net/ipv4/route.c:ipv4_update_pmtu",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/icmp.c:icmp_route_lookup",
        "net/ipv4/icmp.c:icmp_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587171152,
      "name": "__ip_route_output_key_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2359
    }
  ]
}
```
</details>
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
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
struct rtable * __ip_route_output_key_hash(struct net * net, struct flowi4 * fl4, int mp_hash)
```
</details>
</li>
</ul>
