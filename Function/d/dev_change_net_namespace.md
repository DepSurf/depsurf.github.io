# Function: <code>dev_change_net_namespace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dev_change_net_namespace(struct net_device * dev, struct net * net, const char * pat)
```

```json
{
  "name": "dev_change_net_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586285072,
      "name": "dev_change_net_namespace",
      "external": true,
      "loc": "net/core/dev.c:7309",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_newlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586285072,
      "name": "dev_change_net_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 980
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dev_change_net_namespace(struct net_device * dev, struct net * net, const char * pat)
```

```json
{
  "name": "dev_change_net_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586713184,
      "name": "dev_change_net_namespace",
      "external": true,
      "loc": "net/core/dev.c:7827",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586713184,
      "name": "dev_change_net_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1015
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dev_change_net_namespace(struct net_device * dev, struct net * net, const char * pat)
```

```json
{
  "name": "dev_change_net_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586898864,
      "name": "dev_change_net_namespace",
      "external": true,
      "loc": "net/core/dev.c:7998",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586898864,
      "name": "dev_change_net_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1015
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dev_change_net_namespace(struct net_device * dev, struct net * net, const char * pat)
```

```json
{
  "name": "dev_change_net_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587024176,
      "name": "dev_change_net_namespace",
      "external": true,
      "loc": "net/core/dev.c:8192",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587024176,
      "name": "dev_change_net_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 956
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dev_change_net_namespace(struct net_device * dev, struct net * net, const char * pat)
```

```json
{
  "name": "dev_change_net_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587522048,
      "name": "dev_change_net_namespace",
      "external": true,
      "loc": "net/core/dev.c:8371",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587522048,
      "name": "dev_change_net_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1063
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
int dev_change_net_namespace(struct net_device * dev, struct net * net, const char * pat)
```

```json
{
  "name": "dev_change_net_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587822784,
      "name": "dev_change_net_namespace",
      "external": true,
      "loc": "net/core/dev.c:8621",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587822784,
      "name": "dev_change_net_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1025
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
int dev_change_net_namespace(struct net_device * dev, struct net * net, const char * pat)
```

```json
{
  "name": "dev_change_net_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587956256,
      "name": "dev_change_net_namespace",
      "external": true,
      "loc": "net/core/dev.c:9251",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587956256,
      "name": "dev_change_net_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1039
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
int dev_change_net_namespace(struct net_device * dev, struct net * net, const char * pat)
```

```json
{
  "name": "dev_change_net_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_net_namespace",
      "external": true,
      "loc": "net/core/dev.c:9356",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588311767,
      "name": "dev_change_net_namespace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071588270976,
      "name": "dev_change_net_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1040
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
int dev_change_net_namespace(struct net_device * dev, struct net * net, const char * pat)
```

```json
{
  "name": "dev_change_net_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588477328,
      "name": "dev_change_net_namespace",
      "external": true,
      "loc": "net/core/dev.c:9700",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588477328,
      "name": "dev_change_net_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1099
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
int dev_change_net_namespace(struct net_device * dev, struct net * net, const char * pat)
```

```json
{
  "name": "dev_change_net_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589350144,
      "name": "dev_change_net_namespace",
      "external": true,
      "loc": "net/core/dev.c:10155",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589350144,
      "name": "dev_change_net_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1053
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
int dev_change_net_namespace(struct net_device * dev, struct net * net, const char * pat)
```

```json
{
  "name": "dev_change_net_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589351712,
      "name": "dev_change_net_namespace",
      "external": true,
      "loc": "net/core/dev.c:10864",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589351712,
      "name": "dev_change_net_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1053
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_change_net_namespace",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589255993,
      "name": "dev_change_net_namespace",
      "external": false,
      "loc": "include/linux/netdevice.h:4036",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589349805,
      "name": "dev_change_net_namespace",
      "external": false,
      "loc": "include/linux/netdevice.h:4036",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:__rtnl_newlink"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_change_net_namespace",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589981550,
      "name": "dev_change_net_namespace",
      "external": false,
      "loc": "include/linux/netdevice.h:4054",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590080432,
      "name": "dev_change_net_namespace",
      "external": false,
      "loc": "include/linux/netdevice.h:4054",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:__rtnl_newlink"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_change_net_namespace",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591525164,
      "name": "dev_change_net_namespace",
      "external": false,
      "loc": "include/linux/netdevice.h:3844",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591615736,
      "name": "dev_change_net_namespace",
      "external": false,
      "loc": "include/linux/netdevice.h:3844",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_newlink_create"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_change_net_namespace",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593298764,
      "name": "dev_change_net_namespace",
      "external": false,
      "loc": "include/linux/netdevice.h:3888",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593397993,
      "name": "dev_change_net_namespace",
      "external": false,
      "loc": "include/linux/netdevice.h:3888",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_newlink_create"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_change_net_namespace",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593758535,
      "name": "dev_change_net_namespace",
      "external": false,
      "loc": "include/linux/netdevice.h:3947",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593862617,
      "name": "dev_change_net_namespace",
      "external": false,
      "loc": "include/linux/netdevice.h:3947",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_newlink_create"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_change_net_namespace",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594537545,
      "name": "dev_change_net_namespace",
      "external": false,
      "loc": "include/linux/netdevice.h:4026",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594644905,
      "name": "dev_change_net_namespace",
      "external": false,
      "loc": "include/linux/netdevice.h:4026",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_newlink_create"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int dev_change_net_namespace(struct net_device * dev, struct net * net, const char * pat)
```

```json
{
  "name": "dev_change_net_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502005384,
      "name": "dev_change_net_namespace",
      "external": true,
      "loc": "net/core/dev.c:9700",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502005384,
      "name": "dev_change_net_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 964
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
int dev_change_net_namespace(struct net_device * dev, struct net * net, const char * pat)
```

```json
{
  "name": "dev_change_net_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234760868,
      "name": "dev_change_net_namespace",
      "external": true,
      "loc": "net/core/dev.c:9700",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234760868,
      "name": "dev_change_net_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1084
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
int dev_change_net_namespace(struct net_device * dev, struct net * net, const char * pat)
```

```json
{
  "name": "dev_change_net_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295446048,
      "name": "dev_change_net_namespace",
      "external": true,
      "loc": "net/core/dev.c:9700",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295446048,
      "name": "dev_change_net_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1196
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
int dev_change_net_namespace(struct net_device * dev, struct net * net, const char * pat)
```

```json
{
  "name": "dev_change_net_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278295978,
      "name": "dev_change_net_namespace",
      "external": true,
      "loc": "net/core/dev.c:9700",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278295978,
      "name": "dev_change_net_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 844
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
int dev_change_net_namespace(struct net_device * dev, struct net * net, const char * pat)
```

```json
{
  "name": "dev_change_net_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588084112,
      "name": "dev_change_net_namespace",
      "external": true,
      "loc": "net/core/dev.c:9700",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588084112,
      "name": "dev_change_net_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1099
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
int dev_change_net_namespace(struct net_device * dev, struct net * net, const char * pat)
```

```json
{
  "name": "dev_change_net_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587797680,
      "name": "dev_change_net_namespace",
      "external": true,
      "loc": "net/core/dev.c:9700",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587797680,
      "name": "dev_change_net_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1099
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
int dev_change_net_namespace(struct net_device * dev, struct net * net, const char * pat)
```

```json
{
  "name": "dev_change_net_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588415888,
      "name": "dev_change_net_namespace",
      "external": true,
      "loc": "net/core/dev.c:9700",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588415888,
      "name": "dev_change_net_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1099
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
int dev_change_net_namespace(struct net_device * dev, struct net * net, const char * pat)
```

```json
{
  "name": "dev_change_net_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588554528,
      "name": "dev_change_net_namespace",
      "external": true,
      "loc": "net/core/dev.c:9700",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588554528,
      "name": "dev_change_net_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1099
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int dev_change_net_namespace(struct net_device * dev, struct net * net, const char * pat)
```
</details>
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
