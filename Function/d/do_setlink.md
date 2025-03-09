# Function: <code>do_setlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_setlink(const struct sk_buff * skb, struct net_device * dev, struct ifinfomsg * ifm, struct nlattr * * tb, char * ifname, int status)
```

```json
{
  "name": "do_setlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586363984,
      "name": "do_setlink",
      "external": false,
      "loc": "net/core/rtnetlink.c:1679",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586363984,
      "name": "do_setlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2936
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
int do_setlink(const struct sk_buff * skb, struct net_device * dev, struct ifinfomsg * ifm, struct nlattr * * tb, char * ifname, int status)
```

```json
{
  "name": "do_setlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586796288,
      "name": "do_setlink",
      "external": false,
      "loc": "net/core/rtnetlink.c:1844",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586796288,
      "name": "do_setlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3239
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
int do_setlink(const struct sk_buff * skb, struct net_device * dev, struct ifinfomsg * ifm, struct nlattr * * tb, char * ifname, int status)
```

```json
{
  "name": "do_setlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586982800,
      "name": "do_setlink",
      "external": false,
      "loc": "net/core/rtnetlink.c:1906",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586982800,
      "name": "do_setlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3358
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
int do_setlink(const struct sk_buff * skb, struct net_device * dev, struct ifinfomsg * ifm, struct netlink_ext_ack * extack, struct nlattr * * tb, char * ifname, int status)
```

```json
{
  "name": "do_setlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587107648,
      "name": "do_setlink",
      "external": false,
      "loc": "net/core/rtnetlink.c:1975",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587107648,
      "name": "do_setlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3673
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
int do_setlink(const struct sk_buff * skb, struct net_device * dev, struct ifinfomsg * ifm, struct netlink_ext_ack * extack, struct nlattr * * tb, char * ifname, int status)
```

```json
{
  "name": "do_setlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587610256,
      "name": "do_setlink",
      "external": false,
      "loc": "net/core/rtnetlink.c:2147",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587610256,
      "name": "do_setlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3676
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
int do_setlink(const struct sk_buff * skb, struct net_device * dev, struct ifinfomsg * ifm, struct netlink_ext_ack * extack, struct nlattr * * tb, char * ifname, int status)
```

```json
{
  "name": "do_setlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_setlink",
      "external": false,
      "loc": "net/core/rtnetlink.c:2261",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587921408,
      "name": "do_setlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3587
    },
    {
      "addr": 18446744071587943818,
      "name": "do_setlink.cold.44",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
int do_setlink(const struct sk_buff * skb, struct net_device * dev, struct ifinfomsg * ifm, struct netlink_ext_ack * extack, struct nlattr * * tb, char * ifname, int status)
```

```json
{
  "name": "do_setlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_setlink",
      "external": false,
      "loc": "net/core/rtnetlink.c:2377",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588069232,
      "name": "do_setlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3627
    },
    {
      "addr": 18446744071588091882,
      "name": "do_setlink.cold.45",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
int do_setlink(const struct sk_buff * skb, struct net_device * dev, struct ifinfomsg * ifm, struct netlink_ext_ack * extack, struct nlattr * * tb, char * ifname, int status)
```

```json
{
  "name": "do_setlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_setlink",
      "external": false,
      "loc": "net/core/rtnetlink.c:2382",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588384944,
      "name": "do_setlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2419
    },
    {
      "addr": 18446744071588407169,
      "name": "do_setlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int do_setlink(const struct sk_buff * skb, struct net_device * dev, struct ifinfomsg * ifm, struct netlink_ext_ack * extack, struct nlattr * * tb, char * ifname, int status)
```

```json
{
  "name": "do_setlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_setlink",
      "external": false,
      "loc": "net/core/rtnetlink.c:2404",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588591312,
      "name": "do_setlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2419
    },
    {
      "addr": 18446744071588613352,
      "name": "do_setlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int do_setlink(const struct sk_buff * skb, struct net_device * dev, struct ifinfomsg * ifm, struct netlink_ext_ack * extack, struct nlattr * * tb, char * ifname, int status)
```

```json
{
  "name": "do_setlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_setlink",
      "external": false,
      "loc": "net/core/rtnetlink.c:2489",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589446416,
      "name": "do_setlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2766
    },
    {
      "addr": 18446744071589469056,
      "name": "do_setlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int do_setlink(const struct sk_buff * skb, struct net_device * dev, struct ifinfomsg * ifm, struct netlink_ext_ack * extack, struct nlattr * * tb, char * ifname, int status)
```

```json
{
  "name": "do_setlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_setlink",
      "external": false,
      "loc": "net/core/rtnetlink.c:2593",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589447344,
      "name": "do_setlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3113
    },
    {
      "addr": 18446744071591630501,
      "name": "do_setlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int do_setlink(const struct sk_buff * skb, struct net_device * dev, struct ifinfomsg * ifm, struct netlink_ext_ack * extack, struct nlattr * * tb, char * ifname, int status)
```

```json
{
  "name": "do_setlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_setlink",
      "external": false,
      "loc": "net/core/rtnetlink.c:2587",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589344352,
      "name": "do_setlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3132
    },
    {
      "addr": 18446744071591573934,
      "name": "do_setlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int do_setlink(const struct sk_buff * skb, struct net_device * dev, struct ifinfomsg * ifm, struct netlink_ext_ack * extack, struct nlattr * * tb, char * ifname, int status)
```

```json
{
  "name": "do_setlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_setlink",
      "external": false,
      "loc": "net/core/rtnetlink.c:2597",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590074944,
      "name": "do_setlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3141
    },
    {
      "addr": 18446744071592701458,
      "name": "do_setlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int do_setlink(const struct sk_buff * skb, struct net_device * dev, struct ifinfomsg * ifm, struct netlink_ext_ack * extack, struct nlattr * * tb, int status)
```

```json
{
  "name": "do_setlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_setlink",
      "external": false,
      "loc": "net/core/rtnetlink.c:2650",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591621984,
      "name": "do_setlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3616
    },
    {
      "addr": 18446744071594587944,
      "name": "do_setlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
int do_setlink(const struct sk_buff * skb, struct net_device * dev, struct ifinfomsg * ifm, struct netlink_ext_ack * extack, struct nlattr * * tb, int status)
```

```json
{
  "name": "do_setlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593404496,
      "name": "do_setlink",
      "external": false,
      "loc": "net/core/rtnetlink.c:2690",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593404496,
      "name": "do_setlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3640
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
int do_setlink(const struct sk_buff * skb, struct net_device * dev, struct ifinfomsg * ifm, struct netlink_ext_ack * extack, struct nlattr * * tb, int status)
```

```json
{
  "name": "do_setlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593868576,
      "name": "do_setlink",
      "external": false,
      "loc": "net/core/rtnetlink.c:2748",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593868576,
      "name": "do_setlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3669
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
int do_setlink(const struct sk_buff * skb, struct net_device * dev, struct ifinfomsg * ifm, struct netlink_ext_ack * extack, struct nlattr * * tb, int status)
```

```json
{
  "name": "do_setlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594651776,
      "name": "do_setlink",
      "external": false,
      "loc": "net/core/rtnetlink.c:2780",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594651776,
      "name": "do_setlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3694
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
int do_setlink(const struct sk_buff * skb, struct net_device * dev, struct ifinfomsg * ifm, struct netlink_ext_ack * extack, struct nlattr * * tb, char * ifname, int status)
```

```json
{
  "name": "do_setlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502135896,
      "name": "do_setlink",
      "external": false,
      "loc": "net/core/rtnetlink.c:2404",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502135896,
      "name": "do_setlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2248
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
int do_setlink(const struct sk_buff * skb, struct net_device * dev, struct ifinfomsg * ifm, struct netlink_ext_ack * extack, struct nlattr * * tb, char * ifname, int status)
```

```json
{
  "name": "do_setlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234877840,
      "name": "do_setlink",
      "external": false,
      "loc": "net/core/rtnetlink.c:2404",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234877840,
      "name": "do_setlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2308
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
int do_setlink(const struct sk_buff * skb, struct net_device * dev, struct ifinfomsg * ifm, struct netlink_ext_ack * extack, struct nlattr * * tb, char * ifname, int status)
```

```json
{
  "name": "do_setlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295601888,
      "name": "do_setlink",
      "external": false,
      "loc": "net/core/rtnetlink.c:2404",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295601888,
      "name": "do_setlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2620
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
int do_setlink(const struct sk_buff * skb, struct net_device * dev, struct ifinfomsg * ifm, struct netlink_ext_ack * extack, struct nlattr * * tb, char * ifname, int status)
```

```json
{
  "name": "do_setlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278393596,
      "name": "do_setlink",
      "external": false,
      "loc": "net/core/rtnetlink.c:2404",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278393596,
      "name": "do_setlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1762
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
int do_setlink(const struct sk_buff * skb, struct net_device * dev, struct ifinfomsg * ifm, struct netlink_ext_ack * extack, struct nlattr * * tb, char * ifname, int status)
```

```json
{
  "name": "do_setlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_setlink",
      "external": false,
      "loc": "net/core/rtnetlink.c:2404",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588198048,
      "name": "do_setlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2419
    },
    {
      "addr": 18446744071588220088,
      "name": "do_setlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int do_setlink(const struct sk_buff * skb, struct net_device * dev, struct ifinfomsg * ifm, struct netlink_ext_ack * extack, struct nlattr * * tb, char * ifname, int status)
```

```json
{
  "name": "do_setlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_setlink",
      "external": false,
      "loc": "net/core/rtnetlink.c:2404",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587910880,
      "name": "do_setlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2419
    },
    {
      "addr": 18446744071587932920,
      "name": "do_setlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int do_setlink(const struct sk_buff * skb, struct net_device * dev, struct ifinfomsg * ifm, struct netlink_ext_ack * extack, struct nlattr * * tb, char * ifname, int status)
```

```json
{
  "name": "do_setlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_setlink",
      "external": false,
      "loc": "net/core/rtnetlink.c:2404",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588529872,
      "name": "do_setlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2419
    },
    {
      "addr": 18446744071588551912,
      "name": "do_setlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int do_setlink(const struct sk_buff * skb, struct net_device * dev, struct ifinfomsg * ifm, struct netlink_ext_ack * extack, struct nlattr * * tb, char * ifname, int status)
```

```json
{
  "name": "do_setlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_setlink",
      "external": false,
      "loc": "net/core/rtnetlink.c:2404",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588667200,
      "name": "do_setlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2452
    },
    {
      "addr": 18446744071588689384,
      "name": "do_setlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
<code>struct netlink_ext_ack * extack</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, dev, ifm, tb, ifname, status</code> ➡️ <code>skb, dev, ifm, extack, tb, ifname, status</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>char * ifname</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, dev, ifm, extack, tb, ifname, status</code> ➡️ <code>skb, dev, ifm, extack, tb, status</code>
</li>
</ul>
</details>
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
