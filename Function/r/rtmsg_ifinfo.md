# Function: <code>rtmsg_ifinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rtmsg_ifinfo(int type, struct net_device * dev, unsigned int change, gfp_t flags)
```

```json
{
  "name": "rtmsg_ifinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586380608,
      "name": "rtmsg_ifinfo",
      "external": true,
      "loc": "net/core/rtnetlink.c:2548",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnetlink_event"
      ],
      "caller_func": [
        "net/core/dev.c:dev_close_many",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:register_netdevice",
        "net/core/rtnetlink.c:rtnetlink_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586380608,
      "name": "rtmsg_ifinfo.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071586380688,
      "name": "rtmsg_ifinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rtmsg_ifinfo(int type, struct net_device * dev, unsigned int change, gfp_t flags)
```

```json
{
  "name": "rtmsg_ifinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586816799,
      "name": "rtmsg_ifinfo",
      "external": true,
      "loc": "net/core/rtnetlink.c:2742",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnetlink_event"
      ],
      "caller_func": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many",
        "net/core/rtnetlink.c:rtnetlink_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586816656,
      "name": "rtmsg_ifinfo.part.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071586816736,
      "name": "rtmsg_ifinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rtmsg_ifinfo(int type, struct net_device * dev, unsigned int change, gfp_t flags)
```

```json
{
  "name": "rtmsg_ifinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587004607,
      "name": "rtmsg_ifinfo",
      "external": true,
      "loc": "net/core/rtnetlink.c:2815",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnetlink_event"
      ],
      "caller_func": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many",
        "net/core/rtnetlink.c:rtnetlink_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587004464,
      "name": "rtmsg_ifinfo.part.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071587004544,
      "name": "rtmsg_ifinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void rtmsg_ifinfo(int type, struct net_device * dev, unsigned int change, gfp_t flags)
```

```json
{
  "name": "rtmsg_ifinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587129696,
      "name": "rtmsg_ifinfo",
      "external": true,
      "loc": "net/core/rtnetlink.c:2918",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587129696,
      "name": "rtmsg_ifinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void rtmsg_ifinfo(int type, struct net_device * dev, unsigned int change, gfp_t flags)
```

```json
{
  "name": "rtmsg_ifinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587633424,
      "name": "rtmsg_ifinfo",
      "external": true,
      "loc": "net/core/rtnetlink.c:3149",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587633424,
      "name": "rtmsg_ifinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void rtmsg_ifinfo(int type, struct net_device * dev, unsigned int change, gfp_t flags)
```

```json
{
  "name": "rtmsg_ifinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587943632,
      "name": "rtmsg_ifinfo",
      "external": true,
      "loc": "net/core/rtnetlink.c:3306",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587943632,
      "name": "rtmsg_ifinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void rtmsg_ifinfo(int type, struct net_device * dev, unsigned int change, gfp_t flags)
```

```json
{
  "name": "rtmsg_ifinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588091696,
      "name": "rtmsg_ifinfo",
      "external": true,
      "loc": "net/core/rtnetlink.c:3449",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588091696,
      "name": "rtmsg_ifinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void rtmsg_ifinfo(int type, struct net_device * dev, unsigned int change, gfp_t flags)
```

```json
{
  "name": "rtmsg_ifinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588406784,
      "name": "rtmsg_ifinfo",
      "external": true,
      "loc": "net/core/rtnetlink.c:3510",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588406784,
      "name": "rtmsg_ifinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void rtmsg_ifinfo(int type, struct net_device * dev, unsigned int change, gfp_t flags)
```

```json
{
  "name": "rtmsg_ifinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588613168,
      "name": "rtmsg_ifinfo",
      "external": true,
      "loc": "net/core/rtnetlink.c:3541",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588613168,
      "name": "rtmsg_ifinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void rtmsg_ifinfo(int type, struct net_device * dev, unsigned int change, gfp_t flags)
```

```json
{
  "name": "rtmsg_ifinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589468768,
      "name": "rtmsg_ifinfo",
      "external": true,
      "loc": "net/core/rtnetlink.c:3744",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589468768,
      "name": "rtmsg_ifinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void rtmsg_ifinfo(int type, struct net_device * dev, unsigned int change, gfp_t flags)
```

```json
{
  "name": "rtmsg_ifinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589469856,
      "name": "rtmsg_ifinfo",
      "external": true,
      "loc": "net/core/rtnetlink.c:3836",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589469856,
      "name": "rtmsg_ifinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void rtmsg_ifinfo(int type, struct net_device * dev, unsigned int change, gfp_t flags)
```

```json
{
  "name": "rtmsg_ifinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589368272,
      "name": "rtmsg_ifinfo",
      "external": true,
      "loc": "net/core/rtnetlink.c:3834",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589368272,
      "name": "rtmsg_ifinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void rtmsg_ifinfo(int type, struct net_device * dev, unsigned int change, gfp_t flags)
```

```json
{
  "name": "rtmsg_ifinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590098592,
      "name": "rtmsg_ifinfo",
      "external": true,
      "loc": "net/core/rtnetlink.c:3855",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590098592,
      "name": "rtmsg_ifinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void rtmsg_ifinfo(int type, struct net_device * dev, unsigned int change, gfp_t flags)
```

```json
{
  "name": "rtmsg_ifinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591649056,
      "name": "rtmsg_ifinfo",
      "external": true,
      "loc": "net/core/rtnetlink.c:3946",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591649056,
      "name": "rtmsg_ifinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void rtmsg_ifinfo(int type, struct net_device * dev, unsigned int change, gfp_t flags, u32 portid, const struct nlmsghdr * nlh)
```

```json
{
  "name": "rtmsg_ifinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593432368,
      "name": "rtmsg_ifinfo",
      "external": true,
      "loc": "net/core/rtnetlink.c:3992",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593432368,
      "name": "rtmsg_ifinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void rtmsg_ifinfo(int type, struct net_device * dev, unsigned int change, gfp_t flags, u32 portid, const struct nlmsghdr * nlh)
```

```json
{
  "name": "rtmsg_ifinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593897344,
      "name": "rtmsg_ifinfo",
      "external": true,
      "loc": "net/core/rtnetlink.c:4081",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593897344,
      "name": "rtmsg_ifinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void rtmsg_ifinfo(int type, struct net_device * dev, unsigned int change, gfp_t flags, u32 portid, const struct nlmsghdr * nlh)
```

```json
{
  "name": "rtmsg_ifinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594680640,
      "name": "rtmsg_ifinfo",
      "external": true,
      "loc": "net/core/rtnetlink.c:4121",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594680640,
      "name": "rtmsg_ifinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void rtmsg_ifinfo(int type, struct net_device * dev, unsigned int change, gfp_t flags)
```

```json
{
  "name": "rtmsg_ifinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502159296,
      "name": "rtmsg_ifinfo",
      "external": true,
      "loc": "net/core/rtnetlink.c:3541",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502159296,
      "name": "rtmsg_ifinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void rtmsg_ifinfo(int type, struct net_device * dev, unsigned int change, gfp_t flags)
```

```json
{
  "name": "rtmsg_ifinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234902164,
      "name": "rtmsg_ifinfo",
      "external": true,
      "loc": "net/core/rtnetlink.c:3541",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234902164,
      "name": "rtmsg_ifinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void rtmsg_ifinfo(int type, struct net_device * dev, unsigned int change, gfp_t flags)
```

```json
{
  "name": "rtmsg_ifinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295629200,
      "name": "rtmsg_ifinfo",
      "external": true,
      "loc": "net/core/rtnetlink.c:3541",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295629200,
      "name": "rtmsg_ifinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void rtmsg_ifinfo(int type, struct net_device * dev, unsigned int change, gfp_t flags)
```

```json
{
  "name": "rtmsg_ifinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278413968,
      "name": "rtmsg_ifinfo",
      "external": true,
      "loc": "net/core/rtnetlink.c:3541",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278413968,
      "name": "rtmsg_ifinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void rtmsg_ifinfo(int type, struct net_device * dev, unsigned int change, gfp_t flags)
```

```json
{
  "name": "rtmsg_ifinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588219904,
      "name": "rtmsg_ifinfo",
      "external": true,
      "loc": "net/core/rtnetlink.c:3541",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588219904,
      "name": "rtmsg_ifinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void rtmsg_ifinfo(int type, struct net_device * dev, unsigned int change, gfp_t flags)
```

```json
{
  "name": "rtmsg_ifinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587932736,
      "name": "rtmsg_ifinfo",
      "external": true,
      "loc": "net/core/rtnetlink.c:3541",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587932736,
      "name": "rtmsg_ifinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void rtmsg_ifinfo(int type, struct net_device * dev, unsigned int change, gfp_t flags)
```

```json
{
  "name": "rtmsg_ifinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588551728,
      "name": "rtmsg_ifinfo",
      "external": true,
      "loc": "net/core/rtnetlink.c:3541",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588551728,
      "name": "rtmsg_ifinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void rtmsg_ifinfo(int type, struct net_device * dev, unsigned int change, gfp_t flags)
```

```json
{
  "name": "rtmsg_ifinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588689200,
      "name": "rtmsg_ifinfo",
      "external": true,
      "loc": "net/core/rtnetlink.c:3541",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__dev_notify_flags",
        "net/core/dev.c:dev_close_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588689200,
      "name": "rtmsg_ifinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 portid</code>
</li>
<li>
<b>Param added. </b>
<code>const struct nlmsghdr * nlh</code>
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
