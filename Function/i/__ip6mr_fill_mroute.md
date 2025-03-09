# Function: <code>__ip6mr_fill_mroute</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ip6mr_fill_mroute",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587205152,
      "name": "__ip6mr_fill_mroute",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:2232",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_get_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587205152,
      "name": "__ip6mr_fill_mroute.isra.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
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
  "name": "__ip6mr_fill_mroute",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587661840,
      "name": "__ip6mr_fill_mroute",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:2236",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587661840,
      "name": "__ip6mr_fill_mroute.isra.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 586
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ip6mr_fill_mroute",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587870304,
      "name": "__ip6mr_fill_mroute",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:2236",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587870304,
      "name": "__ip6mr_fill_mroute.isra.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 586
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __ip6mr_fill_mroute(struct mr6_table * mrt, struct sk_buff * skb, struct mfc6_cache * c, struct rtmsg * rtm)
```

```json
{
  "name": "__ip6mr_fill_mroute",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588026944,
      "name": "__ip6mr_fill_mroute",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:2245",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588026944,
      "name": "__ip6mr_fill_mroute",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 554
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __ip6mr_fill_mroute(struct mr6_table * mrt, struct sk_buff * skb, struct mfc6_cache * c, struct rtmsg * rtm)
```

```json
{
  "name": "__ip6mr_fill_mroute",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588565888,
      "name": "__ip6mr_fill_mroute",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:2250",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588565888,
      "name": "__ip6mr_fill_mroute",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 554
    }
  ]
}
```
</details>
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int __ip6mr_fill_mroute(struct mr6_table * mrt, struct sk_buff * skb, struct mfc6_cache * c, struct rtmsg * rtm)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int __ip6mr_fill_mroute(struct mr6_table * mrt, struct sk_buff * skb, struct mfc6_cache * c, struct rtmsg * rtm)
```
</details>
</li>
</ul>
