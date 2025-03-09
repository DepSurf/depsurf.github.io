# Function: <code>unregister_netdevice_many</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void unregister_netdevice_many(struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_many",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586277696,
      "name": "unregister_netdevice_many",
      "external": true,
      "loc": "net/core/dev.c:7263",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:__rtnl_link_unregister",
        "net/core/rtnetlink.c:rtnl_delete_link",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_device_event",
        "net/ipv6/ip6mr.c:mroute_clean_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586277696,
      "name": "unregister_netdevice_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void unregister_netdevice_many(struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_many",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586703648,
      "name": "unregister_netdevice_many",
      "external": true,
      "loc": "net/core/dev.c:7781",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_delete_link",
        "net/core/rtnetlink.c:__rtnl_link_unregister",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_device_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586703648,
      "name": "unregister_netdevice_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void unregister_netdevice_many(struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_many",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586890256,
      "name": "unregister_netdevice_many",
      "external": true,
      "loc": "net/core/dev.c:7952",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_delete_link",
        "net/core/rtnetlink.c:__rtnl_link_unregister",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_device_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586890256,
      "name": "unregister_netdevice_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unregister_netdevice_many(struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587018109,
      "name": "unregister_netdevice_many",
      "external": true,
      "loc": "net/core/dev.c:8146",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit_batch"
      ],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_delete_link",
        "net/core/rtnetlink.c:__rtnl_link_unregister",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587017616,
      "name": "unregister_netdevice_many.part.102",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446744071587017760,
      "name": "unregister_netdevice_many",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unregister_netdevice_many(struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587515920,
      "name": "unregister_netdevice_many",
      "external": true,
      "loc": "net/core/dev.c:8325",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit_batch"
      ],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_delete_link",
        "net/core/rtnetlink.c:__rtnl_link_unregister",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587515424,
      "name": "unregister_netdevice_many.part.107",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446744071587515568,
      "name": "unregister_netdevice_many",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unregister_netdevice_many(struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587857152,
      "name": "unregister_netdevice_many",
      "external": true,
      "loc": "net/core/dev.c:8575",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_delete_link",
        "net/core/rtnetlink.c:__rtnl_link_unregister",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587857152,
      "name": "unregister_netdevice_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unregister_netdevice_many(struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587997536,
      "name": "unregister_netdevice_many",
      "external": true,
      "loc": "net/core/dev.c:9205",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_delete_link",
        "net/core/rtnetlink.c:__rtnl_link_unregister",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587997536,
      "name": "unregister_netdevice_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unregister_netdevice_many(struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588269580,
      "name": "unregister_netdevice_many",
      "external": true,
      "loc": "net/core/dev.c:9310",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit_batch"
      ],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_delete_link",
        "net/core/rtnetlink.c:__rtnl_link_unregister",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588269088,
      "name": "unregister_netdevice_many.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071588269232,
      "name": "unregister_netdevice_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unregister_netdevice_many(struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588475929,
      "name": "unregister_netdevice_many",
      "external": true,
      "loc": "net/core/dev.c:9654",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit_batch"
      ],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_delete_link",
        "net/core/rtnetlink.c:__rtnl_link_unregister",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588475440,
      "name": "unregister_netdevice_many.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071588475584,
      "name": "unregister_netdevice_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unregister_netdevice_many(struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589389449,
      "name": "unregister_netdevice_many",
      "external": true,
      "loc": "net/core/dev.c:10109",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit_batch"
      ],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:__rtnl_link_unregister",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589388624,
      "name": "unregister_netdevice_many.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071589388768,
      "name": "unregister_netdevice_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void unregister_netdevice_many(struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589355513,
      "name": "unregister_netdevice_many",
      "external": true,
      "loc": "net/core/dev.c:10818",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit_batch"
      ],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:__rtnl_link_unregister",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589354688,
      "name": "unregister_netdevice_many.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071589354832,
      "name": "unregister_netdevice_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void unregister_netdevice_many(struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_many",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589249424,
      "name": "unregister_netdevice_many",
      "external": true,
      "loc": "net/core/dev.c:11000",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdevice_queue",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:__rtnl_link_unregister",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589249424,
      "name": "unregister_netdevice_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1368
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
void unregister_netdevice_many(struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_many",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unregister_netdevice_many",
      "external": true,
      "loc": "net/core/dev.c:11007",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/wwan/wwan_core.c:wwan_unregister_ops",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdevice_queue",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:__rtnl_link_unregister",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592698237,
      "name": "unregister_netdevice_many.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071589974144,
      "name": "unregister_netdevice_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1418
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
void unregister_netdevice_many(struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_many",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unregister_netdevice_many",
      "external": true,
      "loc": "net/core/dev.c:10787",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/wwan/wwan_core.c:wwan_unregister_ops",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdevice_queue",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:__rtnl_link_unregister",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594584557,
      "name": "unregister_netdevice_many.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071591520224,
      "name": "unregister_netdevice_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1647
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unregister_netdevice_many(struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593335651,
      "name": "unregister_netdevice_many",
      "external": true,
      "loc": "net/core/dev.c:10887",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdevice_queue"
      ],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/wwan/wwan_core.c:wwan_unregister_ops",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:__rtnl_link_unregister",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593333184,
      "name": "unregister_netdevice_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unregister_netdevice_many(struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593797443,
      "name": "unregister_netdevice_many",
      "external": true,
      "loc": "net/core/dev.c:10904",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdevice_queue"
      ],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/wwan/wwan_core.c:wwan_unregister_ops",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:__rtnl_link_unregister",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593794992,
      "name": "unregister_netdevice_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unregister_netdevice_many(struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594578801,
      "name": "unregister_netdevice_many",
      "external": true,
      "loc": "net/core/dev.c:11115",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdevice_queue"
      ],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:__rtnl_link_unregister",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594575856,
      "name": "unregister_netdevice_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void unregister_netdevice_many(struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502002344,
      "name": "unregister_netdevice_many",
      "external": true,
      "loc": "net/core/dev.c:9654",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit_batch"
      ],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_delete_link",
        "net/core/rtnetlink.c:__rtnl_link_unregister",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502001784,
      "name": "unregister_netdevice_many.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446603336502001952,
      "name": "unregister_netdevice_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void unregister_netdevice_many(struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234767624,
      "name": "unregister_netdevice_many",
      "external": true,
      "loc": "net/core/dev.c:9654",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit_batch"
      ],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_delete_link",
        "net/core/rtnetlink.c:__rtnl_link_unregister",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234767100,
      "name": "unregister_netdevice_many.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 3234767244,
      "name": "unregister_netdevice_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void unregister_netdevice_many(struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295438256,
      "name": "unregister_netdevice_many",
      "external": true,
      "loc": "net/core/dev.c:9654",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit_batch"
      ],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_delete_link",
        "net/core/rtnetlink.c:__rtnl_link_unregister",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295437568,
      "name": "unregister_netdevice_many.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 13835058055295437792,
      "name": "unregister_netdevice_many",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void unregister_netdevice_many(struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278305512,
      "name": "unregister_netdevice_many",
      "external": true,
      "loc": "net/core/dev.c:9654",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit_batch"
      ],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_delete_link",
        "net/core/rtnetlink.c:__rtnl_link_unregister",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278305050,
      "name": "unregister_netdevice_many.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446743936278305176,
      "name": "unregister_netdevice_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unregister_netdevice_many(struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588082713,
      "name": "unregister_netdevice_many",
      "external": true,
      "loc": "net/core/dev.c:9654",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit_batch"
      ],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_delete_link",
        "net/core/rtnetlink.c:__rtnl_link_unregister",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588082224,
      "name": "unregister_netdevice_many.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071588082368,
      "name": "unregister_netdevice_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unregister_netdevice_many(struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587796281,
      "name": "unregister_netdevice_many",
      "external": true,
      "loc": "net/core/dev.c:9654",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit_batch"
      ],
      "caller_func": [
        "drivers/net/vxlan.c:vxlan_exit_batch_net",
        "drivers/net/vxlan.c:vxlan_netdevice_event",
        "drivers/net/vxlan.c:vxlan_dev_create",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_delete_link",
        "net/core/rtnetlink.c:__rtnl_link_unregister",
        "net/ipv4/ip_tunnel.c:ip_tunnel_delete_nets",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587795792,
      "name": "unregister_netdevice_many.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071587795936,
      "name": "unregister_netdevice_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unregister_netdevice_many(struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588414489,
      "name": "unregister_netdevice_many",
      "external": true,
      "loc": "net/core/dev.c:9654",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit_batch"
      ],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_delete_link",
        "net/core/rtnetlink.c:__rtnl_link_unregister",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588414000,
      "name": "unregister_netdevice_many.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071588414144,
      "name": "unregister_netdevice_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unregister_netdevice_many(struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588553081,
      "name": "unregister_netdevice_many",
      "external": true,
      "loc": "net/core/dev.c:9654",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit_batch"
      ],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_delete_link",
        "net/core/rtnetlink.c:__rtnl_link_unregister",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588552592,
      "name": "unregister_netdevice_many.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071588552736,
      "name": "unregister_netdevice_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
