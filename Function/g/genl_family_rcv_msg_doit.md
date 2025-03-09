# Function: <code>genl_family_rcv_msg_doit</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genl_family_rcv_msg_doit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589839271,
      "name": "genl_family_rcv_msg_doit",
      "external": false,
      "loc": "net/netlink/genetlink.c:633",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_family_rcv_msg"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int genl_family_rcv_msg_doit(const struct genl_family * family, struct sk_buff * skb, struct nlmsghdr * nlh, struct netlink_ext_ack * extack, const struct genl_ops * ops, int hdrlen, struct net * net)
```

```json
{
  "name": "genl_family_rcv_msg_doit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589876048,
      "name": "genl_family_rcv_msg_doit",
      "external": false,
      "loc": "net/netlink/genetlink.c:703",
      "file": "net/netlink/genetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/genetlink.c:genl_family_rcv_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589876048,
      "name": "genl_family_rcv_msg_doit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
int genl_family_rcv_msg_doit(const struct genl_family * family, struct sk_buff * skb, struct nlmsghdr * nlh, struct netlink_ext_ack * extack, const struct genl_ops * ops, int hdrlen, struct net * net)
```

```json
{
  "name": "genl_family_rcv_msg_doit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589781824,
      "name": "genl_family_rcv_msg_doit",
      "external": false,
      "loc": "net/netlink/genetlink.c:703",
      "file": "net/netlink/genetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/genetlink.c:genl_rcv_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589781824,
      "name": "genl_family_rcv_msg_doit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
int genl_family_rcv_msg_doit(const struct genl_family * family, struct sk_buff * skb, struct nlmsghdr * nlh, struct netlink_ext_ack * extack, const struct genl_ops * ops, int hdrlen, struct net * net)
```

```json
{
  "name": "genl_family_rcv_msg_doit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590541248,
      "name": "genl_family_rcv_msg_doit",
      "external": false,
      "loc": "net/netlink/genetlink.c:695",
      "file": "net/netlink/genetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/genetlink.c:genl_rcv_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590541248,
      "name": "genl_family_rcv_msg_doit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
int genl_family_rcv_msg_doit(const struct genl_family * family, struct sk_buff * skb, struct nlmsghdr * nlh, struct netlink_ext_ack * extack, const struct genl_ops * ops, int hdrlen, struct net * net)
```

```json
{
  "name": "genl_family_rcv_msg_doit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592150912,
      "name": "genl_family_rcv_msg_doit",
      "external": false,
      "loc": "net/netlink/genetlink.c:695",
      "file": "net/netlink/genetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/genetlink.c:genl_rcv_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592150912,
      "name": "genl_family_rcv_msg_doit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genl_family_rcv_msg_doit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593977600,
      "name": "genl_family_rcv_msg_doit",
      "external": false,
      "loc": "net/netlink/genetlink.c:935",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/genetlink.c:genl_family_rcv_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593977600,
      "name": "genl_family_rcv_msg_doit.isra.0",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genl_family_rcv_msg_doit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594354320,
      "name": "genl_family_rcv_msg_doit",
      "external": false,
      "loc": "net/netlink/genetlink.c:937",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/genetlink.c:genl_family_rcv_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594354320,
      "name": "genl_family_rcv_msg_doit.isra.0",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int genl_family_rcv_msg_doit(const struct genl_family * family, struct sk_buff * skb, struct nlmsghdr * nlh, struct netlink_ext_ack * extack, const struct genl_split_ops * ops, int hdrlen, struct net * net)
```

```json
{
  "name": "genl_family_rcv_msg_doit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595151440,
      "name": "genl_family_rcv_msg_doit",
      "external": false,
      "loc": "net/netlink/genetlink.c:1080",
      "file": "net/netlink/genetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/genetlink.c:genl_family_rcv_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595151440,
      "name": "genl_family_rcv_msg_doit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int genl_family_rcv_msg_doit(const struct genl_family * family, struct sk_buff * skb, struct nlmsghdr * nlh, struct netlink_ext_ack * extack, const struct genl_ops * ops, int hdrlen, struct net * net)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int genl_family_rcv_msg_doit(const struct genl_family * family, struct sk_buff * skb, struct nlmsghdr * nlh, struct netlink_ext_ack * extack, const struct genl_ops * ops, int hdrlen, struct net * net)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
int genl_family_rcv_msg_doit(const struct genl_family * family, struct sk_buff * skb, struct nlmsghdr * nlh, struct netlink_ext_ack * extack, const struct genl_split_ops * ops, int hdrlen, struct net * net)
```
</details>
</li>
</ul>
