# Function: <code>ethnl_fill_reply_header</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ethnl_fill_reply_header(struct sk_buff * skb, struct net_device * dev, u16 attrtype)
```

```json
{
  "name": "ethnl_fill_reply_header",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589881756,
      "name": "ethnl_fill_reply_header",
      "external": true,
      "loc": "net/ethtool/netlink.c:117",
      "file": "net/ethtool/netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethtool/netlink.c:ethnl_default_notify",
        "net/ethtool/netlink.c:ethnl_reply_init"
      ],
      "caller_func": [
        "net/ethtool/netlink.c:ethnl_default_notify",
        "net/ethtool/netlink.c:ethnl_reply_init",
        "net/ethtool/cabletest.c:ethnl_cable_test_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589878112,
      "name": "ethnl_fill_reply_header.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    },
    {
      "addr": 18446744071589880368,
      "name": "ethnl_fill_reply_header",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ethnl_fill_reply_header(struct sk_buff * skb, struct net_device * dev, u16 attrtype)
```

```json
{
  "name": "ethnl_fill_reply_header",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589920940,
      "name": "ethnl_fill_reply_header",
      "external": true,
      "loc": "net/ethtool/netlink.c:125",
      "file": "net/ethtool/netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethtool/netlink.c:ethnl_default_notify",
        "net/ethtool/netlink.c:ethnl_reply_init"
      ],
      "caller_func": [
        "net/ethtool/netlink.c:ethnl_default_notify",
        "net/ethtool/netlink.c:ethnl_reply_init",
        "net/ethtool/cabletest.c:ethnl_cable_test_alloc",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589917392,
      "name": "ethnl_fill_reply_header.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    },
    {
      "addr": 18446744071591633703,
      "name": "ethnl_fill_reply_header.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589919504,
      "name": "ethnl_fill_reply_header",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ethnl_fill_reply_header(struct sk_buff * skb, struct net_device * dev, u16 attrtype)
```

```json
{
  "name": "ethnl_fill_reply_header",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589828555,
      "name": "ethnl_fill_reply_header",
      "external": true,
      "loc": "net/ethtool/netlink.c:125",
      "file": "net/ethtool/netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethtool/netlink.c:ethnl_default_notify",
        "net/ethtool/netlink.c:ethnl_default_dumpit",
        "net/ethtool/netlink.c:ethnl_reply_init"
      ],
      "caller_func": [
        "net/ethtool/netlink.c:ethnl_default_notify",
        "net/ethtool/netlink.c:ethnl_default_dumpit",
        "net/ethtool/netlink.c:ethnl_reply_init",
        "net/ethtool/cabletest.c:ethnl_cable_test_alloc",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589824976,
      "name": "ethnl_fill_reply_header.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    },
    {
      "addr": 18446744071591577104,
      "name": "ethnl_fill_reply_header.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589827136,
      "name": "ethnl_fill_reply_header",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ethnl_fill_reply_header(struct sk_buff * skb, struct net_device * dev, u16 attrtype)
```

```json
{
  "name": "ethnl_fill_reply_header",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590591308,
      "name": "ethnl_fill_reply_header",
      "external": true,
      "loc": "net/ethtool/netlink.c:159",
      "file": "net/ethtool/netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ethtool/netlink.c:ethnl_default_notify",
        "net/ethtool/netlink.c:ethnl_default_dumpit",
        "net/ethtool/netlink.c:ethnl_reply_init"
      ],
      "caller_func": [
        "net/ethtool/netlink.c:ethnl_default_notify",
        "net/ethtool/netlink.c:ethnl_default_dumpit",
        "net/ethtool/netlink.c:ethnl_reply_init",
        "net/ethtool/cabletest.c:ethnl_cable_test_alloc",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590587296,
      "name": "ethnl_fill_reply_header.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    },
    {
      "addr": 18446744071592711831,
      "name": "ethnl_fill_reply_header.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071590589712,
      "name": "ethnl_fill_reply_header",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int ethnl_fill_reply_header(struct sk_buff * skb, struct net_device * dev, u16 attrtype)
```

```json
{
  "name": "ethnl_fill_reply_header",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethnl_fill_reply_header",
      "external": true,
      "loc": "net/ethtool/netlink.c:161",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/netlink.c:ethnl_default_notify",
        "net/ethtool/netlink.c:ethnl_default_dumpit",
        "net/ethtool/netlink.c:ethnl_reply_init",
        "net/ethtool/cabletest.c:ethnl_cable_test_alloc",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594597925,
      "name": "ethnl_fill_reply_header.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071592208192,
      "name": "ethnl_fill_reply_header",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int ethnl_fill_reply_header(struct sk_buff * skb, struct net_device * dev, u16 attrtype)
```

```json
{
  "name": "ethnl_fill_reply_header",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594037808,
      "name": "ethnl_fill_reply_header",
      "external": true,
      "loc": "net/ethtool/netlink.c:161",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/netlink.c:ethnl_default_notify",
        "net/ethtool/netlink.c:ethnl_default_dumpit",
        "net/ethtool/netlink.c:ethnl_reply_init",
        "net/ethtool/cabletest.c:ethnl_cable_test_alloc",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594037808,
      "name": "ethnl_fill_reply_header",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int ethnl_fill_reply_header(struct sk_buff * skb, struct net_device * dev, u16 attrtype)
```

```json
{
  "name": "ethnl_fill_reply_header",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594416112,
      "name": "ethnl_fill_reply_header",
      "external": true,
      "loc": "net/ethtool/netlink.c:163",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/netlink.c:ethnl_default_notify",
        "net/ethtool/netlink.c:ethnl_default_dumpit",
        "net/ethtool/netlink.c:ethnl_reply_init",
        "net/ethtool/cabletest.c:ethnl_cable_test_alloc",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594416112,
      "name": "ethnl_fill_reply_header",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int ethnl_fill_reply_header(struct sk_buff * skb, struct net_device * dev, u16 attrtype)
```

```json
{
  "name": "ethnl_fill_reply_header",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595218608,
      "name": "ethnl_fill_reply_header",
      "external": true,
      "loc": "net/ethtool/netlink.c:163",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/netlink.c:ethnl_default_notify",
        "net/ethtool/netlink.c:ethnl_default_dumpit",
        "net/ethtool/netlink.c:ethnl_reply_init",
        "net/ethtool/cabletest.c:ethnl_cable_test_alloc",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595218608,
      "name": "ethnl_fill_reply_header",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int ethnl_fill_reply_header(struct sk_buff * skb, struct net_device * dev, u16 attrtype)
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
