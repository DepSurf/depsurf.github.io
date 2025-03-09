# Function: <code>ip6_dst_lookup_tunnel</code>

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
struct dst_entry * ip6_dst_lookup_tunnel(struct sk_buff * skb, struct net_device * dev, struct net * net, struct socket * sock, struct in6_addr * saddr, const struct ip_tunnel_info * info, u8 protocol, bool use_cache)
```

```json
{
  "name": "ip6_dst_lookup_tunnel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590562688,
      "name": "ip6_dst_lookup_tunnel",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1216",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590562688,
      "name": "ip6_dst_lookup_tunnel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
struct dst_entry * ip6_dst_lookup_tunnel(struct sk_buff * skb, struct net_device * dev, struct net * net, struct socket * sock, struct in6_addr * saddr, const struct ip_tunnel_info * info, u8 protocol, bool use_cache)
```

```json
{
  "name": "ip6_dst_lookup_tunnel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590622608,
      "name": "ip6_dst_lookup_tunnel",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1255",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590622608,
      "name": "ip6_dst_lookup_tunnel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
struct dst_entry * ip6_dst_lookup_tunnel(struct sk_buff * skb, struct net_device * dev, struct net * net, struct socket * sock, struct in6_addr * saddr, const struct ip_tunnel_info * info, u8 protocol, bool use_cache)
```

```json
{
  "name": "ip6_dst_lookup_tunnel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590546704,
      "name": "ip6_dst_lookup_tunnel",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1286",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590546704,
      "name": "ip6_dst_lookup_tunnel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
struct dst_entry * ip6_dst_lookup_tunnel(struct sk_buff * skb, struct net_device * dev, struct net * net, struct socket * sock, struct in6_addr * saddr, const struct ip_tunnel_info * info, u8 protocol, bool use_cache)
```

```json
{
  "name": "ip6_dst_lookup_tunnel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591357376,
      "name": "ip6_dst_lookup_tunnel",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1265",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591357376,
      "name": "ip6_dst_lookup_tunnel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
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
struct dst_entry * ip6_dst_lookup_tunnel(struct sk_buff * skb, struct net_device * dev, struct net * net, struct socket * sock, struct in6_addr * saddr, const struct ip_tunnel_info * info, u8 protocol, bool use_cache)
```

```json
{
  "name": "ip6_dst_lookup_tunnel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593030240,
      "name": "ip6_dst_lookup_tunnel",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1287",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593030240,
      "name": "ip6_dst_lookup_tunnel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
struct dst_entry * ip6_dst_lookup_tunnel(struct sk_buff * skb, struct net_device * dev, struct net * net, struct socket * sock, struct in6_addr * saddr, const struct ip_tunnel_info * info, u8 protocol, bool use_cache)
```

```json
{
  "name": "ip6_dst_lookup_tunnel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594921360,
      "name": "ip6_dst_lookup_tunnel",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1305",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594921360,
      "name": "ip6_dst_lookup_tunnel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
struct dst_entry * ip6_dst_lookup_tunnel(struct sk_buff * skb, struct net_device * dev, struct net * net, struct socket * sock, struct in6_addr * saddr, const struct ip_tunnel_info * info, u8 protocol, bool use_cache)
```

```json
{
  "name": "ip6_dst_lookup_tunnel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595313056,
      "name": "ip6_dst_lookup_tunnel",
      "external": true,
      "loc": "net/ipv6/ip6_output.c:1306",
      "file": "net/ipv6/ip6_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595313056,
      "name": "ip6_dst_lookup_tunnel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
    }
  ]
}
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct dst_entry * ip6_dst_lookup_tunnel(struct sk_buff * skb, struct net_device * dev, struct net * net, struct socket * sock, struct in6_addr * saddr, const struct ip_tunnel_info * info, u8 protocol, bool use_cache)
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
struct dst_entry * ip6_dst_lookup_tunnel(struct sk_buff * skb, struct net_device * dev, struct net * net, struct socket * sock, struct in6_addr * saddr, const struct ip_tunnel_info * info, u8 protocol, bool use_cache)
```
</details>
</li>
</ul>
