# Function: <code>rtnl_fill_ifinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff * skb, struct net_device * dev, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask)
```

```json
{
  "name": "rtnl_fill_ifinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586373712,
      "name": "rtnl_fill_ifinfo",
      "external": false,
      "loc": "net/core/rtnetlink.c:1191",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586373712,
      "name": "rtnl_fill_ifinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3868
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff * skb, struct net_device * dev, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask)
```

```json
{
  "name": "rtnl_fill_ifinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586806048,
      "name": "rtnl_fill_ifinfo",
      "external": false,
      "loc": "net/core/rtnetlink.c:1252",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586806048,
      "name": "rtnl_fill_ifinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4254
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff * skb, struct net_device * dev, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask)
```

```json
{
  "name": "rtnl_fill_ifinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586993824,
      "name": "rtnl_fill_ifinfo",
      "external": false,
      "loc": "net/core/rtnetlink.c:1282",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586993824,
      "name": "rtnl_fill_ifinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4258
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
int rtnl_fill_ifinfo(struct sk_buff * skb, struct net_device * dev, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event)
```

```json
{
  "name": "rtnl_fill_ifinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587119184,
      "name": "rtnl_fill_ifinfo",
      "external": false,
      "loc": "net/core/rtnetlink.c:1333",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587119184,
      "name": "rtnl_fill_ifinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4178
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
int rtnl_fill_ifinfo(struct sk_buff * skb, struct net_device * dev, struct net * src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int * new_nsid, int tgt_netnsid)
```

```json
{
  "name": "rtnl_fill_ifinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587623152,
      "name": "rtnl_fill_ifinfo",
      "external": false,
      "loc": "net/core/rtnetlink.c:1432",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587623152,
      "name": "rtnl_fill_ifinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3831
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff * skb, struct net_device * dev, struct net * src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int * new_nsid, int new_ifindex, int tgt_netnsid)
```

```json
{
  "name": "rtnl_fill_ifinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_fill_ifinfo",
      "external": false,
      "loc": "net/core/rtnetlink.c:1532",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587934800,
      "name": "rtnl_fill_ifinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3762
    },
    {
      "addr": 18446744071587943850,
      "name": "rtnl_fill_ifinfo.cold.45",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff * skb, struct net_device * dev, struct net * src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int * new_nsid, int new_ifindex, int tgt_netnsid)
```

```json
{
  "name": "rtnl_fill_ifinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_fill_ifinfo",
      "external": false,
      "loc": "net/core/rtnetlink.c:1584",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588080864,
      "name": "rtnl_fill_ifinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3716
    },
    {
      "addr": 18446744071588091914,
      "name": "rtnl_fill_ifinfo.cold.46",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int rtnl_fill_ifinfo(struct sk_buff * skb, struct net_device * dev, struct net * src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int * new_nsid, int new_ifindex, int tgt_netnsid)
```

```json
{
  "name": "rtnl_fill_ifinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_fill_ifinfo",
      "external": false,
      "loc": "net/core/rtnetlink.c:1587",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588395664,
      "name": "rtnl_fill_ifinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3708
    },
    {
      "addr": 18446744071588407470,
      "name": "rtnl_fill_ifinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff * skb, struct net_device * dev, struct net * src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int * new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp)
```

```json
{
  "name": "rtnl_fill_ifinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_fill_ifinfo",
      "external": false,
      "loc": "net/core/rtnetlink.c:1587",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588602032,
      "name": "rtnl_fill_ifinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3744
    },
    {
      "addr": 18446744071588613398,
      "name": "rtnl_fill_ifinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff * skb, struct net_device * dev, struct net * src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int * new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp)
```

```json
{
  "name": "rtnl_fill_ifinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_fill_ifinfo",
      "external": false,
      "loc": "net/core/rtnetlink.c:1661",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589461056,
      "name": "rtnl_fill_ifinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2607
    },
    {
      "addr": 18446744071589469102,
      "name": "rtnl_fill_ifinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff * skb, struct net_device * dev, struct net * src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int * new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp)
```

```json
{
  "name": "rtnl_fill_ifinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_fill_ifinfo",
      "external": false,
      "loc": "net/core/rtnetlink.c:1701",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589463456,
      "name": "rtnl_fill_ifinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2855
    },
    {
      "addr": 18446744071591630571,
      "name": "rtnl_fill_ifinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff * skb, struct net_device * dev, struct net * src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int * new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp)
```

```json
{
  "name": "rtnl_fill_ifinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_fill_ifinfo",
      "external": false,
      "loc": "net/core/rtnetlink.c:1703",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589361264,
      "name": "rtnl_fill_ifinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3433
    },
    {
      "addr": 18446744071591574004,
      "name": "rtnl_fill_ifinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff * skb, struct net_device * dev, struct net * src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int * new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp)
```

```json
{
  "name": "rtnl_fill_ifinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_fill_ifinfo",
      "external": false,
      "loc": "net/core/rtnetlink.c:1692",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590091472,
      "name": "rtnl_fill_ifinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3583
    },
    {
      "addr": 18446744071592701602,
      "name": "rtnl_fill_ifinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
int rtnl_fill_ifinfo(struct sk_buff * skb, struct net_device * dev, struct net * src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int * new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp)
```

```json
{
  "name": "rtnl_fill_ifinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_fill_ifinfo",
      "external": false,
      "loc": "net/core/rtnetlink.c:1732",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591641056,
      "name": "rtnl_fill_ifinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4277
    },
    {
      "addr": 18446744071594588155,
      "name": "rtnl_fill_ifinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff * skb, struct net_device * dev, struct net * src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int * new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp)
```

```json
{
  "name": "rtnl_fill_ifinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_fill_ifinfo",
      "external": false,
      "loc": "net/core/rtnetlink.c:1767",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593423968,
      "name": "rtnl_fill_ifinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4460
    },
    {
      "addr": 18446744071596326729,
      "name": "rtnl_fill_ifinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff * skb, struct net_device * dev, struct net * src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int * new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp)
```

```json
{
  "name": "rtnl_fill_ifinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_fill_ifinfo",
      "external": false,
      "loc": "net/core/rtnetlink.c:1778",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593889440,
      "name": "rtnl_fill_ifinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3944
    },
    {
      "addr": 18446744071596857006,
      "name": "rtnl_fill_ifinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff * skb, struct net_device * dev, struct net * src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int * new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp)
```

```json
{
  "name": "rtnl_fill_ifinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_fill_ifinfo",
      "external": false,
      "loc": "net/core/rtnetlink.c:1807",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594672576,
      "name": "rtnl_fill_ifinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4060
    },
    {
      "addr": 18446744071597782011,
      "name": "rtnl_fill_ifinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
int rtnl_fill_ifinfo(struct sk_buff * skb, struct net_device * dev, struct net * src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int * new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp)
```

```json
{
  "name": "rtnl_fill_ifinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502149128,
      "name": "rtnl_fill_ifinfo",
      "external": false,
      "loc": "net/core/rtnetlink.c:1587",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502149128,
      "name": "rtnl_fill_ifinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3412
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
int rtnl_fill_ifinfo(struct sk_buff * skb, struct net_device * dev, struct net * src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int * new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp)
```

```json
{
  "name": "rtnl_fill_ifinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234891356,
      "name": "rtnl_fill_ifinfo",
      "external": false,
      "loc": "net/core/rtnetlink.c:1587",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234891356,
      "name": "rtnl_fill_ifinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3712
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
int rtnl_fill_ifinfo(struct sk_buff * skb, struct net_device * dev, struct net * src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int * new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp)
```

```json
{
  "name": "rtnl_fill_ifinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295616112,
      "name": "rtnl_fill_ifinfo",
      "external": false,
      "loc": "net/core/rtnetlink.c:1587",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295616112,
      "name": "rtnl_fill_ifinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4388
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
int rtnl_fill_ifinfo(struct sk_buff * skb, struct net_device * dev, struct net * src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int * new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp)
```

```json
{
  "name": "rtnl_fill_ifinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278405598,
      "name": "rtnl_fill_ifinfo",
      "external": false,
      "loc": "net/core/rtnetlink.c:1587",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278405598,
      "name": "rtnl_fill_ifinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2704
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff * skb, struct net_device * dev, struct net * src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int * new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp)
```

```json
{
  "name": "rtnl_fill_ifinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_fill_ifinfo",
      "external": false,
      "loc": "net/core/rtnetlink.c:1587",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588208768,
      "name": "rtnl_fill_ifinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3744
    },
    {
      "addr": 18446744071588220134,
      "name": "rtnl_fill_ifinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff * skb, struct net_device * dev, struct net * src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int * new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp)
```

```json
{
  "name": "rtnl_fill_ifinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_fill_ifinfo",
      "external": false,
      "loc": "net/core/rtnetlink.c:1587",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587921600,
      "name": "rtnl_fill_ifinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3744
    },
    {
      "addr": 18446744071587932966,
      "name": "rtnl_fill_ifinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff * skb, struct net_device * dev, struct net * src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int * new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp)
```

```json
{
  "name": "rtnl_fill_ifinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_fill_ifinfo",
      "external": false,
      "loc": "net/core/rtnetlink.c:1587",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588540592,
      "name": "rtnl_fill_ifinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3744
    },
    {
      "addr": 18446744071588551958,
      "name": "rtnl_fill_ifinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff * skb, struct net_device * dev, struct net * src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int * new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp)
```

```json
{
  "name": "rtnl_fill_ifinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtnl_fill_ifinfo",
      "external": false,
      "loc": "net/core/rtnetlink.c:1587",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588678016,
      "name": "rtnl_fill_ifinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3793
    },
    {
      "addr": 18446744071588689430,
      "name": "rtnl_fill_ifinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 event</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net * src_net</code>
</li>
<li>
<b>Param added. </b>
<code>int * new_nsid</code>
</li>
<li>
<b>Param added. </b>
<code>int tgt_netnsid</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, dev, type, pid, seq, change, flags, ext_filter_mask, event</code> ➡️ <code>skb, dev, src_net, type, pid, seq, change, flags, ext_filter_mask, event, new_nsid, tgt_netnsid</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int new_ifindex</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, dev, src_net, type, pid, seq, change, flags, ext_filter_mask, event, new_nsid, tgt_netnsid</code> ➡️ <code>skb, dev, src_net, type, pid, seq, change, flags, ext_filter_mask, event, new_nsid, new_ifindex, tgt_netnsid</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
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
