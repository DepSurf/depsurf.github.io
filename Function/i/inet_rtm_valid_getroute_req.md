# Function: <code>inet_rtm_valid_getroute_req</code>

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
  "name": "inet_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588765264,
      "name": "inet_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/route.c:2997",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
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
  "name": "inet_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588989024,
      "name": "inet_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/route.c:3008",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
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
int inet_rtm_valid_getroute_req(struct sk_buff * skb, const struct nlmsghdr * nlh, struct nlattr * * tb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "inet_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589927840,
      "name": "inet_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/route.c:3095",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589927840,
      "name": "inet_rtm_valid_getroute_req",
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
int inet_rtm_valid_getroute_req(struct sk_buff * skb, const struct nlmsghdr * nlh, struct nlattr * * tb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "inet_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589968432,
      "name": "inet_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/route.c:3077",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589968432,
      "name": "inet_rtm_valid_getroute_req",
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
int inet_rtm_valid_getroute_req(struct sk_buff * skb, const struct nlmsghdr * nlh, struct nlattr * * tb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "inet_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589883760,
      "name": "inet_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/route.c:3078",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589883760,
      "name": "inet_rtm_valid_getroute_req",
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
int inet_rtm_valid_getroute_req(struct sk_buff * skb, const struct nlmsghdr * nlh, struct nlattr * * tb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "inet_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590647600,
      "name": "inet_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/route.c:3196",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590647600,
      "name": "inet_rtm_valid_getroute_req",
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
int inet_rtm_valid_getroute_req(struct sk_buff * skb, const struct nlmsghdr * nlh, struct nlattr * * tb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "inet_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592272288,
      "name": "inet_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/route.c:3220",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592272288,
      "name": "inet_rtm_valid_getroute_req",
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
int inet_rtm_valid_getroute_req(struct sk_buff * skb, const struct nlmsghdr * nlh, struct nlattr * * tb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "inet_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594107248,
      "name": "inet_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/route.c:3211",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594107248,
      "name": "inet_rtm_valid_getroute_req",
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
int inet_rtm_valid_getroute_req(struct sk_buff * skb, const struct nlmsghdr * nlh, struct nlattr * * tb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "inet_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594494128,
      "name": "inet_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/route.c:3207",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594494128,
      "name": "inet_rtm_valid_getroute_req",
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
int inet_rtm_valid_getroute_req(struct sk_buff * skb, const struct nlmsghdr * nlh, struct nlattr * * tb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "inet_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595297040,
      "name": "inet_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/route.c:3162",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595297040,
      "name": "inet_rtm_valid_getroute_req",
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
  "name": "inet_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502594032,
      "name": "inet_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/route.c:3008",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
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
  "name": "inet_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235299512,
      "name": "inet_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/route.c:3008",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
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
  "name": "inet_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296184080,
      "name": "inet_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/route.c:3008",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
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
  "name": "inet_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278747188,
      "name": "inet_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/route.c:3008",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
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
  "name": "inet_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588595408,
      "name": "inet_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/route.c:3008",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
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
  "name": "inet_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588307392,
      "name": "inet_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/route.c:3008",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
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
  "name": "inet_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589031584,
      "name": "inet_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/route.c:3008",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
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
  "name": "inet_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589070624,
      "name": "inet_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/route.c:3008",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
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
int inet_rtm_valid_getroute_req(struct sk_buff * skb, const struct nlmsghdr * nlh, struct nlattr * * tb, struct netlink_ext_ack * extack)
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
