# Function: <code>rtnl_newlink_create</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int rtnl_newlink_create(struct sk_buff * skb, struct ifinfomsg * ifm, const struct rtnl_link_ops * ops, struct nlattr * * tb, struct nlattr * * data, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtnl_newlink_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591615344,
      "name": "rtnl_newlink_create",
      "external": false,
      "loc": "net/core/rtnetlink.c:3311",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591615344,
      "name": "rtnl_newlink_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 928
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
int rtnl_newlink_create(struct sk_buff * skb, struct ifinfomsg * ifm, const struct rtnl_link_ops * ops, const struct nlmsghdr * nlh, struct nlattr * * tb, struct nlattr * * data, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtnl_newlink_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593397568,
      "name": "rtnl_newlink_create",
      "external": false,
      "loc": "net/core/rtnetlink.c:3353",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593397568,
      "name": "rtnl_newlink_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 961
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
int rtnl_newlink_create(struct sk_buff * skb, struct ifinfomsg * ifm, const struct rtnl_link_ops * ops, const struct nlmsghdr * nlh, struct nlattr * * tb, struct nlattr * * data, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtnl_newlink_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593862192,
      "name": "rtnl_newlink_create",
      "external": false,
      "loc": "net/core/rtnetlink.c:3432",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593862192,
      "name": "rtnl_newlink_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 961
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
int rtnl_newlink_create(struct sk_buff * skb, struct ifinfomsg * ifm, const struct rtnl_link_ops * ops, const struct nlmsghdr * nlh, struct nlattr * * tb, struct nlattr * * data, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtnl_newlink_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594644480,
      "name": "rtnl_newlink_create",
      "external": false,
      "loc": "net/core/rtnetlink.c:3464",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594644480,
      "name": "rtnl_newlink_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 961
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
int rtnl_newlink_create(struct sk_buff * skb, struct ifinfomsg * ifm, const struct rtnl_link_ops * ops, struct nlattr * * tb, struct nlattr * * data, struct netlink_ext_ack * extack)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct nlmsghdr * nlh</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, ifm, ops, tb, data, extack</code> ➡️ <code>skb, ifm, ops, nlh, tb, data, extack</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
