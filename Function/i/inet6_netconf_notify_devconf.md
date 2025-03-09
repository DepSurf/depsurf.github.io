# Function: <code>inet6_netconf_notify_devconf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void inet6_netconf_notify_devconf(struct net * net, int type, int ifindex, struct ipv6_devconf * devconf)
```

```json
{
  "name": "inet6_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587025936,
      "name": "inet6_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv6/addrconf.c:537",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/ip6mr.c:mif6_delete",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587025936,
      "name": "inet6_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
void inet6_netconf_notify_devconf(struct net * net, int type, int ifindex, struct ipv6_devconf * devconf)
```

```json
{
  "name": "inet6_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587471024,
      "name": "inet6_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv6/addrconf.c:544",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587471024,
      "name": "inet6_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
void inet6_netconf_notify_devconf(struct net * net, int type, int ifindex, struct ipv6_devconf * devconf)
```

```json
{
  "name": "inet6_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587674320,
      "name": "inet6_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv6/addrconf.c:571",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587674320,
      "name": "inet6_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
void inet6_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv6_devconf * devconf)
```

```json
{
  "name": "inet6_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587824400,
      "name": "inet6_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv6/addrconf.c:582",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587824400,
      "name": "inet6_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
void inet6_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv6_devconf * devconf)
```

```json
{
  "name": "inet6_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588354656,
      "name": "inet6_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv6/addrconf.c:582",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588354656,
      "name": "inet6_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
void inet6_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv6_devconf * devconf)
```

```json
{
  "name": "inet6_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588712080,
      "name": "inet6_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv6/addrconf.c:571",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588712080,
      "name": "inet6_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void inet6_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv6_devconf * devconf)
```

```json
{
  "name": "inet6_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588931440,
      "name": "inet6_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv6/addrconf.c:569",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588931440,
      "name": "inet6_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void inet6_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv6_devconf * devconf)
```

```json
{
  "name": "inet6_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet6_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv6/addrconf.c:566",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589401361,
      "name": "inet6_netconf_notify_devconf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589374112,
      "name": "inet6_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
void inet6_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv6_devconf * devconf)
```

```json
{
  "name": "inet6_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589598544,
      "name": "inet6_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv6/addrconf.c:566",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589598544,
      "name": "inet6_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void inet6_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv6_devconf * devconf)
```

```json
{
  "name": "inet6_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590604784,
      "name": "inet6_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv6/addrconf.c:566",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_init_net",
        "net/ipv6/addrconf.c:addrconf_sysctl_unregister",
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_fixup_linkdown",
        "net/ipv6/addrconf.c:addrconf_fixup_linkdown",
        "net/ipv6/addrconf.c:addrconf_fixup_linkdown",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590604784,
      "name": "inet6_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void inet6_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv6_devconf * devconf)
```

```json
{
  "name": "inet6_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590665504,
      "name": "inet6_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv6/addrconf.c:566",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_init_net",
        "net/ipv6/addrconf.c:addrconf_sysctl_unregister",
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_fixup_linkdown",
        "net/ipv6/addrconf.c:addrconf_fixup_linkdown",
        "net/ipv6/addrconf.c:addrconf_fixup_linkdown",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590665504,
      "name": "inet6_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void inet6_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv6_devconf * devconf)
```

```json
{
  "name": "inet6_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590591376,
      "name": "inet6_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv6/addrconf.c:568",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_init_net",
        "net/ipv6/addrconf.c:addrconf_sysctl_unregister",
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590591376,
      "name": "inet6_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void inet6_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv6_devconf * devconf)
```

```json
{
  "name": "inet6_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591404032,
      "name": "inet6_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv6/addrconf.c:576",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_init_net",
        "net/ipv6/addrconf.c:addrconf_sysctl_unregister",
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591404032,
      "name": "inet6_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void inet6_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv6_devconf * devconf)
```

```json
{
  "name": "inet6_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593080256,
      "name": "inet6_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv6/addrconf.c:575",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_init_net",
        "net/ipv6/addrconf.c:addrconf_sysctl_unregister",
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593080256,
      "name": "inet6_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
void inet6_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv6_devconf * devconf)
```

```json
{
  "name": "inet6_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594974544,
      "name": "inet6_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv6/addrconf.c:575",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_init_net",
        "net/ipv6/addrconf.c:addrconf_sysctl_unregister",
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594974544,
      "name": "inet6_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
void inet6_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv6_devconf * devconf)
```

```json
{
  "name": "inet6_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595367232,
      "name": "inet6_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv6/addrconf.c:574",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_init_net",
        "net/ipv6/addrconf.c:addrconf_sysctl_unregister",
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595367232,
      "name": "inet6_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
void inet6_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv6_devconf * devconf)
```

```json
{
  "name": "inet6_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596208304,
      "name": "inet6_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv6/addrconf.c:578",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/addrconf.c:addrconf_init_net",
        "net/ipv6/addrconf.c:addrconf_sysctl_unregister",
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596208304,
      "name": "inet6_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
void inet6_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv6_devconf * devconf)
```

```json
{
  "name": "inet6_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503275376,
      "name": "inet6_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv6/addrconf.c:566",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503275376,
      "name": "inet6_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void inet6_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv6_devconf * devconf)
```

```json
{
  "name": "inet6_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235947560,
      "name": "inet6_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv6/addrconf.c:566",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__addrconf_sysctl_unregister",
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235947560,
      "name": "inet6_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void inet6_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv6_devconf * devconf)
```

```json
{
  "name": "inet6_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297025360,
      "name": "inet6_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv6/addrconf.c:566",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297025360,
      "name": "inet6_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
void inet6_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv6_devconf * devconf)
```

```json
{
  "name": "inet6_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279298774,
      "name": "inet6_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv6/addrconf.c:566",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279298774,
      "name": "inet6_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void inet6_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv6_devconf * devconf)
```

```json
{
  "name": "inet6_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589202912,
      "name": "inet6_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv6/addrconf.c:566",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589202912,
      "name": "inet6_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void inet6_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv6_devconf * devconf)
```

```json
{
  "name": "inet6_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588927904,
      "name": "inet6_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv6/addrconf.c:566",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588927904,
      "name": "inet6_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void inet6_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv6_devconf * devconf)
```

```json
{
  "name": "inet6_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589639776,
      "name": "inet6_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv6/addrconf.c:566",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589639776,
      "name": "inet6_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void inet6_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv6_devconf * devconf)
```

```json
{
  "name": "inet6_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589688784,
      "name": "inet6_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv6/addrconf.c:566",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__addrconf_sysctl_register",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589688784,
      "name": "inet6_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
<code>int event</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, type, ifindex, devconf</code> ➡️ <code>net, event, type, ifindex, devconf</code>
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
