# Function: <code>inet6_rtm_valid_getroute_req</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet6_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589417375,
      "name": "inet6_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv6/route.c:5688",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:inet6_rtm_getroute"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet6_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589641583,
      "name": "inet6_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv6/route.c:5702",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:inet6_rtm_getroute"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int inet6_rtm_valid_getroute_req(struct sk_buff * skb, const struct nlmsghdr * nlh, struct nlattr * * tb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "inet6_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590646464,
      "name": "inet6_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv6/route.c:5790",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590646464,
      "name": "inet6_rtm_valid_getroute_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
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
int inet6_rtm_valid_getroute_req(struct sk_buff * skb, const struct nlmsghdr * nlh, struct nlattr * * tb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "inet6_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590706560,
      "name": "inet6_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv6/route.c:5779",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590706560,
      "name": "inet6_rtm_valid_getroute_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
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
int inet6_rtm_valid_getroute_req(struct sk_buff * skb, const struct nlmsghdr * nlh, struct nlattr * * tb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "inet6_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590634400,
      "name": "inet6_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv6/route.c:5798",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590634400,
      "name": "inet6_rtm_valid_getroute_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
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
int inet6_rtm_valid_getroute_req(struct sk_buff * skb, const struct nlmsghdr * nlh, struct nlattr * * tb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "inet6_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591447680,
      "name": "inet6_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv6/route.c:5957",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591447680,
      "name": "inet6_rtm_valid_getroute_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
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
int inet6_rtm_valid_getroute_req(struct sk_buff * skb, const struct nlmsghdr * nlh, struct nlattr * * tb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "inet6_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593126320,
      "name": "inet6_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv6/route.c:5950",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593126320,
      "name": "inet6_rtm_valid_getroute_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
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
int inet6_rtm_valid_getroute_req(struct sk_buff * skb, const struct nlmsghdr * nlh, struct nlattr * * tb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "inet6_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595022704,
      "name": "inet6_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv6/route.c:5951",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595022704,
      "name": "inet6_rtm_valid_getroute_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
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
int inet6_rtm_valid_getroute_req(struct sk_buff * skb, const struct nlmsghdr * nlh, struct nlattr * * tb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "inet6_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595416128,
      "name": "inet6_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv6/route.c:5949",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595416128,
      "name": "inet6_rtm_valid_getroute_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 518
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
int inet6_rtm_valid_getroute_req(struct sk_buff * skb, const struct nlmsghdr * nlh, struct nlattr * * tb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "inet6_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596257936,
      "name": "inet6_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv6/route.c:5942",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596257936,
      "name": "inet6_rtm_valid_getroute_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 518
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "inet6_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503333632,
      "name": "inet6_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv6/route.c:5702",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:inet6_rtm_getroute"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "inet6_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235993180,
      "name": "inet6_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv6/route.c:5702",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:inet6_rtm_getroute"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "inet6_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297083044,
      "name": "inet6_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv6/route.c:5702",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:inet6_rtm_getroute"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "inet6_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279338924,
      "name": "inet6_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv6/route.c:5702",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:inet6_rtm_getroute"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet6_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589245951,
      "name": "inet6_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv6/route.c:5702",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:inet6_rtm_getroute"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet6_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588970943,
      "name": "inet6_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv6/route.c:5702",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:inet6_rtm_getroute"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet6_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589682815,
      "name": "inet6_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv6/route.c:5702",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:inet6_rtm_getroute"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet6_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589732015,
      "name": "inet6_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv6/route.c:5702",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:inet6_rtm_getroute"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int inet6_rtm_valid_getroute_req(struct sk_buff * skb, const struct nlmsghdr * nlh, struct nlattr * * tb, struct netlink_ext_ack * extack)
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
