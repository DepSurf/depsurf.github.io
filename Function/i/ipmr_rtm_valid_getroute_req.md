# Function: <code>ipmr_rtm_valid_getroute_req</code>

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
  "name": "ipmr_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589180694,
      "name": "ipmr_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2482",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute"
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
  "name": "ipmr_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589405670,
      "name": "ipmr_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2483",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute"
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
int ipmr_rtm_valid_getroute_req(struct sk_buff * skb, const struct nlmsghdr * nlh, struct nlattr * * tb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipmr_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590384464,
      "name": "ipmr_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2451",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590384464,
      "name": "ipmr_rtm_valid_getroute_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int ipmr_rtm_valid_getroute_req(struct sk_buff * skb, const struct nlmsghdr * nlh, struct nlattr * * tb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipmr_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590442032,
      "name": "ipmr_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2460",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590442032,
      "name": "ipmr_rtm_valid_getroute_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int ipmr_rtm_valid_getroute_req(struct sk_buff * skb, const struct nlmsghdr * nlh, struct nlattr * * tb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipmr_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590367536,
      "name": "ipmr_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2460",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590367536,
      "name": "ipmr_rtm_valid_getroute_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 467
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
int ipmr_rtm_valid_getroute_req(struct sk_buff * skb, const struct nlmsghdr * nlh, struct nlattr * * tb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipmr_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591160096,
      "name": "ipmr_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2462",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591160096,
      "name": "ipmr_rtm_valid_getroute_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 467
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
int ipmr_rtm_valid_getroute_req(struct sk_buff * skb, const struct nlmsghdr * nlh, struct nlattr * * tb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipmr_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592815920,
      "name": "ipmr_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2456",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592815920,
      "name": "ipmr_rtm_valid_getroute_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
int ipmr_rtm_valid_getroute_req(struct sk_buff * skb, const struct nlmsghdr * nlh, struct nlattr * * tb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipmr_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594694336,
      "name": "ipmr_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2463",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594694336,
      "name": "ipmr_rtm_valid_getroute_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
int ipmr_rtm_valid_getroute_req(struct sk_buff * skb, const struct nlmsghdr * nlh, struct nlattr * * tb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipmr_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595086272,
      "name": "ipmr_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2478",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595086272,
      "name": "ipmr_rtm_valid_getroute_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
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
int ipmr_rtm_valid_getroute_req(struct sk_buff * skb, const struct nlmsghdr * nlh, struct nlattr * * tb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipmr_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595899072,
      "name": "ipmr_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2476",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595899072,
      "name": "ipmr_rtm_valid_getroute_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
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
  "name": "ipmr_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503046348,
      "name": "ipmr_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2483",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute"
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
  "name": "ipmr_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235736072,
      "name": "ipmr_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2483",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute"
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
  "name": "ipmr_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296762368,
      "name": "ipmr_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2483",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute"
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
  "name": "ipmr_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279122654,
      "name": "ipmr_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2483",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute"
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
  "name": "ipmr_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589010694,
      "name": "ipmr_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2483",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute"
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
  "name": "ipmr_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588733750,
      "name": "ipmr_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2483",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute"
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
  "name": "ipmr_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589447078,
      "name": "ipmr_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2483",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute"
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
  "name": "ipmr_rtm_valid_getroute_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589491958,
      "name": "ipmr_rtm_valid_getroute_req",
      "external": false,
      "loc": "net/ipv4/ipmr.c:2483",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_getroute"
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
int ipmr_rtm_valid_getroute_req(struct sk_buff * skb, const struct nlmsghdr * nlh, struct nlattr * * tb, struct netlink_ext_ack * extack)
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
