# Function: <code>mr_fill_mroute</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table * mrt, struct sk_buff * skb, struct mr_mfc * c, struct rtmsg * rtm)
```

```json
{
  "name": "mr_fill_mroute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588561888,
      "name": "mr_fill_mroute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:207",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588561888,
      "name": "mr_fill_mroute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table * mrt, struct sk_buff * skb, struct mr_mfc * c, struct rtmsg * rtm)
```

```json
{
  "name": "mr_fill_mroute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588759168,
      "name": "mr_fill_mroute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:208",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588759168,
      "name": "mr_fill_mroute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int mr_fill_mroute(struct mr_table * mrt, struct sk_buff * skb, struct mr_mfc * c, struct rtmsg * rtm)
```

```json
{
  "name": "mr_fill_mroute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mr_fill_mroute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:208",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589194895,
      "name": "mr_fill_mroute.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071589192128,
      "name": "mr_fill_mroute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table * mrt, struct sk_buff * skb, struct mr_mfc * c, struct rtmsg * rtm)
```

```json
{
  "name": "mr_fill_mroute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589417568,
      "name": "mr_fill_mroute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:208",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589417568,
      "name": "mr_fill_mroute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table * mrt, struct sk_buff * skb, struct mr_mfc * c, struct rtmsg * rtm)
```

```json
{
  "name": "mr_fill_mroute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590404688,
      "name": "mr_fill_mroute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:208",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_cache_resolve",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_cache_resolve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590404688,
      "name": "mr_fill_mroute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
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
int mr_fill_mroute(struct mr_table * mrt, struct sk_buff * skb, struct mr_mfc * c, struct rtmsg * rtm)
```

```json
{
  "name": "mr_fill_mroute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590462528,
      "name": "mr_fill_mroute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:208",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_cache_resolve",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_cache_resolve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590462528,
      "name": "mr_fill_mroute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
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
int mr_fill_mroute(struct mr_table * mrt, struct sk_buff * skb, struct mr_mfc * c, struct rtmsg * rtm)
```

```json
{
  "name": "mr_fill_mroute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590388288,
      "name": "mr_fill_mroute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:208",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590388288,
      "name": "mr_fill_mroute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
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
int mr_fill_mroute(struct mr_table * mrt, struct sk_buff * skb, struct mr_mfc * c, struct rtmsg * rtm)
```

```json
{
  "name": "mr_fill_mroute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591182560,
      "name": "mr_fill_mroute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:208",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591182560,
      "name": "mr_fill_mroute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 773
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
int mr_fill_mroute(struct mr_table * mrt, struct sk_buff * skb, struct mr_mfc * c, struct rtmsg * rtm)
```

```json
{
  "name": "mr_fill_mroute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592841056,
      "name": "mr_fill_mroute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:208",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_cache_resolve",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592841056,
      "name": "mr_fill_mroute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 820
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
int mr_fill_mroute(struct mr_table * mrt, struct sk_buff * skb, struct mr_mfc * c, struct rtmsg * rtm)
```

```json
{
  "name": "mr_fill_mroute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594718560,
      "name": "mr_fill_mroute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:208",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_cache_resolve",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594718560,
      "name": "mr_fill_mroute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 805
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
int mr_fill_mroute(struct mr_table * mrt, struct sk_buff * skb, struct mr_mfc * c, struct rtmsg * rtm)
```

```json
{
  "name": "mr_fill_mroute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595110576,
      "name": "mr_fill_mroute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:208",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_cache_resolve",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595110576,
      "name": "mr_fill_mroute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 802
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
int mr_fill_mroute(struct mr_table * mrt, struct sk_buff * skb, struct mr_mfc * c, struct rtmsg * rtm)
```

```json
{
  "name": "mr_fill_mroute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595923248,
      "name": "mr_fill_mroute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:208",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_cache_resolve",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595923248,
      "name": "mr_fill_mroute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 802
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table * mrt, struct sk_buff * skb, struct mr_mfc * c, struct rtmsg * rtm)
```

```json
{
  "name": "mr_fill_mroute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503069128,
      "name": "mr_fill_mroute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:208",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503069128,
      "name": "mr_fill_mroute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table * mrt, struct sk_buff * skb, struct mr_mfc * c, struct rtmsg * rtm)
```

```json
{
  "name": "mr_fill_mroute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235753252,
      "name": "mr_fill_mroute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:208",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235753252,
      "name": "mr_fill_mroute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table * mrt, struct sk_buff * skb, struct mr_mfc * c, struct rtmsg * rtm)
```

```json
{
  "name": "mr_fill_mroute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296772912,
      "name": "mr_fill_mroute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:208",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296772912,
      "name": "mr_fill_mroute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 948
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table * mrt, struct sk_buff * skb, struct mr_mfc * c, struct rtmsg * rtm)
```

```json
{
  "name": "mr_fill_mroute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279127318,
      "name": "mr_fill_mroute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:208",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279127318,
      "name": "mr_fill_mroute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table * mrt, struct sk_buff * skb, struct mr_mfc * c, struct rtmsg * rtm)
```

```json
{
  "name": "mr_fill_mroute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589021936,
      "name": "mr_fill_mroute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:208",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589021936,
      "name": "mr_fill_mroute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table * mrt, struct sk_buff * skb, struct mr_mfc * c, struct rtmsg * rtm)
```

```json
{
  "name": "mr_fill_mroute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588744992,
      "name": "mr_fill_mroute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:208",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588744992,
      "name": "mr_fill_mroute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table * mrt, struct sk_buff * skb, struct mr_mfc * c, struct rtmsg * rtm)
```

```json
{
  "name": "mr_fill_mroute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589458320,
      "name": "mr_fill_mroute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:208",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589458320,
      "name": "mr_fill_mroute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table * mrt, struct sk_buff * skb, struct mr_mfc * c, struct rtmsg * rtm)
```

```json
{
  "name": "mr_fill_mroute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589504608,
      "name": "mr_fill_mroute",
      "external": true,
      "loc": "net/ipv4/ipmr_base.c:208",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589504608,
      "name": "mr_fill_mroute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
    }
  ]
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int mr_fill_mroute(struct mr_table * mrt, struct sk_buff * skb, struct mr_mfc * c, struct rtmsg * rtm)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
