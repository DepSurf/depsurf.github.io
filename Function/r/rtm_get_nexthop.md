# Function: <code>rtm_get_nexthop</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int rtm_get_nexthop(struct sk_buff * in_skb, struct nlmsghdr * nlh, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_get_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtm_get_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1557",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589153488,
      "name": "rtm_get_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    },
    {
      "addr": 18446744071589158802,
      "name": "rtm_get_nexthop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
int rtm_get_nexthop(struct sk_buff * in_skb, struct nlmsghdr * nlh, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_get_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589377600,
      "name": "rtm_get_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1559",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589377600,
      "name": "rtm_get_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
int rtm_get_nexthop(struct sk_buff * in_skb, struct nlmsghdr * nlh, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_get_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590363248,
      "name": "rtm_get_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1695",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590363248,
      "name": "rtm_get_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int rtm_get_nexthop(struct sk_buff * in_skb, struct nlmsghdr * nlh, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_get_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590418704,
      "name": "rtm_get_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1918",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590418704,
      "name": "rtm_get_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int rtm_get_nexthop(struct sk_buff * in_skb, struct nlmsghdr * nlh, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_get_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590342816,
      "name": "rtm_get_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2985",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590342816,
      "name": "rtm_get_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
int rtm_get_nexthop(struct sk_buff * in_skb, struct nlmsghdr * nlh, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_get_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591127616,
      "name": "rtm_get_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:3014",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591127616,
      "name": "rtm_get_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
int rtm_get_nexthop(struct sk_buff * in_skb, struct nlmsghdr * nlh, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_get_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592781392,
      "name": "rtm_get_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:3014",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592781392,
      "name": "rtm_get_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
int rtm_get_nexthop(struct sk_buff * in_skb, struct nlmsghdr * nlh, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_get_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594654976,
      "name": "rtm_get_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:3014",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594654976,
      "name": "rtm_get_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
int rtm_get_nexthop(struct sk_buff * in_skb, struct nlmsghdr * nlh, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_get_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595047376,
      "name": "rtm_get_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:3014",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595047376,
      "name": "rtm_get_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
int rtm_get_nexthop(struct sk_buff * in_skb, struct nlmsghdr * nlh, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_get_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595860416,
      "name": "rtm_get_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:3037",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595860416,
      "name": "rtm_get_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
int rtm_get_nexthop(struct sk_buff * in_skb, struct nlmsghdr * nlh, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_get_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503020552,
      "name": "rtm_get_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1559",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503020552,
      "name": "rtm_get_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
int rtm_get_nexthop(struct sk_buff * in_skb, struct nlmsghdr * nlh, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_get_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235710608,
      "name": "rtm_get_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1559",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235710608,
      "name": "rtm_get_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
int rtm_get_nexthop(struct sk_buff * in_skb, struct nlmsghdr * nlh, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_get_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296716400,
      "name": "rtm_get_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1559",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296716400,
      "name": "rtm_get_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
int rtm_get_nexthop(struct sk_buff * in_skb, struct nlmsghdr * nlh, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_get_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279093052,
      "name": "rtm_get_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1559",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279093052,
      "name": "rtm_get_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
int rtm_get_nexthop(struct sk_buff * in_skb, struct nlmsghdr * nlh, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_get_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588983776,
      "name": "rtm_get_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1559",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588983776,
      "name": "rtm_get_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
int rtm_get_nexthop(struct sk_buff * in_skb, struct nlmsghdr * nlh, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_get_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588695712,
      "name": "rtm_get_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1559",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588695712,
      "name": "rtm_get_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
int rtm_get_nexthop(struct sk_buff * in_skb, struct nlmsghdr * nlh, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_get_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589420160,
      "name": "rtm_get_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1559",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589420160,
      "name": "rtm_get_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
int rtm_get_nexthop(struct sk_buff * in_skb, struct nlmsghdr * nlh, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_get_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589463744,
      "name": "rtm_get_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1559",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589463744,
      "name": "rtm_get_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int rtm_get_nexthop(struct sk_buff * in_skb, struct nlmsghdr * nlh, struct netlink_ext_ack * extack)
```
</details>
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
