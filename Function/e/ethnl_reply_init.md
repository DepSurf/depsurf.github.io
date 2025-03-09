# Function: <code>ethnl_reply_init</code>

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
struct sk_buff * ethnl_reply_init(size_t payload, struct net_device * dev, u8 cmd, u16 hdr_attrtype, struct genl_info * info, void * * ehdrp)
```

```json
{
  "name": "ethnl_reply_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589880400,
      "name": "ethnl_reply_init",
      "external": true,
      "loc": "net/ethtool/netlink.c:154",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/netlink.c:ethnl_default_doit",
        "net/ethtool/features.c:features_send_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589880400,
      "name": "ethnl_reply_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct sk_buff * ethnl_reply_init(size_t payload, struct net_device * dev, u8 cmd, u16 hdr_attrtype, struct genl_info * info, void * * ehdrp)
```

```json
{
  "name": "ethnl_reply_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589919536,
      "name": "ethnl_reply_init",
      "external": true,
      "loc": "net/ethtool/netlink.c:162",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/netlink.c:ethnl_default_doit",
        "net/ethtool/features.c:features_send_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589919536,
      "name": "ethnl_reply_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct sk_buff * ethnl_reply_init(size_t payload, struct net_device * dev, u8 cmd, u16 hdr_attrtype, struct genl_info * info, void * * ehdrp)
```

```json
{
  "name": "ethnl_reply_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589827168,
      "name": "ethnl_reply_init",
      "external": true,
      "loc": "net/ethtool/netlink.c:162",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/netlink.c:ethnl_default_doit",
        "net/ethtool/features.c:features_send_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589827168,
      "name": "ethnl_reply_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
struct sk_buff * ethnl_reply_init(size_t payload, struct net_device * dev, u8 cmd, u16 hdr_attrtype, struct genl_info * info, void * * ehdrp)
```

```json
{
  "name": "ethnl_reply_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590589744,
      "name": "ethnl_reply_init",
      "external": true,
      "loc": "net/ethtool/netlink.c:196",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/netlink.c:ethnl_default_doit",
        "net/ethtool/features.c:features_send_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590589744,
      "name": "ethnl_reply_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
struct sk_buff * ethnl_reply_init(size_t payload, struct net_device * dev, u8 cmd, u16 hdr_attrtype, struct genl_info * info, void * * ehdrp)
```

```json
{
  "name": "ethnl_reply_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592209376,
      "name": "ethnl_reply_init",
      "external": true,
      "loc": "net/ethtool/netlink.c:198",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/netlink.c:ethnl_default_doit",
        "net/ethtool/features.c:features_send_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592209376,
      "name": "ethnl_reply_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
struct sk_buff * ethnl_reply_init(size_t payload, struct net_device * dev, u8 cmd, u16 hdr_attrtype, struct genl_info * info, void * * ehdrp)
```

```json
{
  "name": "ethnl_reply_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594039056,
      "name": "ethnl_reply_init",
      "external": true,
      "loc": "net/ethtool/netlink.c:198",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/netlink.c:ethnl_default_doit",
        "net/ethtool/features.c:features_send_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594039056,
      "name": "ethnl_reply_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
struct sk_buff * ethnl_reply_init(size_t payload, struct net_device * dev, u8 cmd, u16 hdr_attrtype, struct genl_info * info, void * * ehdrp)
```

```json
{
  "name": "ethnl_reply_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594417360,
      "name": "ethnl_reply_init",
      "external": true,
      "loc": "net/ethtool/netlink.c:200",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/netlink.c:ethnl_default_doit",
        "net/ethtool/features.c:features_send_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594417360,
      "name": "ethnl_reply_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
struct sk_buff * ethnl_reply_init(size_t payload, struct net_device * dev, u8 cmd, u16 hdr_attrtype, struct genl_info * info, void * * ehdrp)
```

```json
{
  "name": "ethnl_reply_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595219552,
      "name": "ethnl_reply_init",
      "external": true,
      "loc": "net/ethtool/netlink.c:200",
      "file": "net/ethtool/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/netlink.c:ethnl_default_doit",
        "net/ethtool/features.c:features_send_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595219552,
      "name": "ethnl_reply_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
struct sk_buff * ethnl_reply_init(size_t payload, struct net_device * dev, u8 cmd, u16 hdr_attrtype, struct genl_info * info, void * * ehdrp)
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
