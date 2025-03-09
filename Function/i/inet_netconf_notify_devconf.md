# Function: <code>inet_netconf_notify_devconf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void inet_netconf_notify_devconf(struct net * net, int type, int ifindex, struct ipv4_devconf * devconf)
```

```json
{
  "name": "inet_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586785584,
      "name": "inet_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv4/devinet.c:1799",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586785584,
      "name": "inet_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
void inet_netconf_notify_devconf(struct net * net, int type, int ifindex, struct ipv4_devconf * devconf)
```

```json
{
  "name": "inet_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587231536,
      "name": "inet_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv4/devinet.c:1831",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587231536,
      "name": "inet_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
void inet_netconf_notify_devconf(struct net * net, int type, int ifindex, struct ipv4_devconf * devconf)
```

```json
{
  "name": "inet_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587432080,
      "name": "inet_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv4/devinet.c:1831",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587432080,
      "name": "inet_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
void inet_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv4_devconf * devconf)
```

```json
{
  "name": "inet_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587568480,
      "name": "inet_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv4/devinet.c:1875",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587568480,
      "name": "inet_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void inet_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv4_devconf * devconf)
```

```json
{
  "name": "inet_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588092240,
      "name": "inet_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv4/devinet.c:1884",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588092240,
      "name": "inet_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void inet_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv4_devconf * devconf)
```

```json
{
  "name": "inet_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588445776,
      "name": "inet_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv4/devinet.c:1894",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588445776,
      "name": "inet_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
void inet_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv4_devconf * devconf)
```

```json
{
  "name": "inet_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588638864,
      "name": "inet_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv4/devinet.c:2033",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588638864,
      "name": "inet_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
void inet_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv4_devconf * devconf)
```

```json
{
  "name": "inet_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv4/devinet.c:2086",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589055673,
      "name": "inet_netconf_notify_devconf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589051088,
      "name": "inet_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void inet_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv4_devconf * devconf)
```

```json
{
  "name": "inet_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589275600,
      "name": "inet_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv4/devinet.c:2081",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589275600,
      "name": "inet_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void inet_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv4_devconf * devconf)
```

```json
{
  "name": "inet_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590250944,
      "name": "inet_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv4/devinet.c:2087",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:inet_forward_change",
        "net/ipv4/devinet.c:inet_forward_change",
        "net/ipv4/devinet.c:inet_forward_change",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_destroy",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590250944,
      "name": "inet_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void inet_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv4_devconf * devconf)
```

```json
{
  "name": "inet_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590303808,
      "name": "inet_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv4/devinet.c:2086",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:inet_forward_change",
        "net/ipv4/devinet.c:inet_forward_change",
        "net/ipv4/devinet.c:inet_forward_change",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_destroy",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590303808,
      "name": "inet_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void inet_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv4_devconf * devconf)
```

```json
{
  "name": "inet_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590219808,
      "name": "inet_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv4/devinet.c:2087",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590219808,
      "name": "inet_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void inet_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv4_devconf * devconf)
```

```json
{
  "name": "inet_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591002240,
      "name": "inet_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv4/devinet.c:2088",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591002240,
      "name": "inet_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void inet_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv4_devconf * devconf)
```

```json
{
  "name": "inet_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592648272,
      "name": "inet_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv4/devinet.c:2095",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592648272,
      "name": "inet_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void inet_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv4_devconf * devconf)
```

```json
{
  "name": "inet_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594514704,
      "name": "inet_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv4/devinet.c:2096",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_destroy",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594514704,
      "name": "inet_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void inet_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv4_devconf * devconf)
```

```json
{
  "name": "inet_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594906416,
      "name": "inet_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv4/devinet.c:2099",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_destroy",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594906416,
      "name": "inet_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
void inet_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv4_devconf * devconf)
```

```json
{
  "name": "inet_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595718064,
      "name": "inet_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv4/devinet.c:2130",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_exit_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:devinet_init_net",
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_destroy",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595718064,
      "name": "inet_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
void inet_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv4_devconf * devconf)
```

```json
{
  "name": "inet_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502905480,
      "name": "inet_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv4/devinet.c:2081",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502905480,
      "name": "inet_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void inet_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv4_devconf * devconf)
```

```json
{
  "name": "inet_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235598864,
      "name": "inet_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv4/devinet.c:2081",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:__devinet_sysctl_unregister",
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235598864,
      "name": "inet_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
void inet_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv4_devconf * devconf)
```

```json
{
  "name": "inet_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296572112,
      "name": "inet_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv4/devinet.c:2081",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296572112,
      "name": "inet_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
void inet_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv4_devconf * devconf)
```

```json
{
  "name": "inet_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279001090,
      "name": "inet_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv4/devinet.c:2081",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279001090,
      "name": "inet_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void inet_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv4_devconf * devconf)
```

```json
{
  "name": "inet_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588881776,
      "name": "inet_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv4/devinet.c:2081",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588881776,
      "name": "inet_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void inet_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv4_devconf * devconf)
```

```json
{
  "name": "inet_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588593712,
      "name": "inet_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv4/devinet.c:2081",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588593712,
      "name": "inet_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void inet_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv4_devconf * devconf)
```

```json
{
  "name": "inet_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589318160,
      "name": "inet_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv4/devinet.c:2081",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589318160,
      "name": "inet_netconf_notify_devconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void inet_netconf_notify_devconf(struct net * net, int event, int type, int ifindex, struct ipv4_devconf * devconf)
```

```json
{
  "name": "inet_netconf_notify_devconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589360032,
      "name": "inet_netconf_notify_devconf",
      "external": true,
      "loc": "net/ipv4/devinet.c:2081",
      "file": "net/ipv4/devinet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/devinet.c:__devinet_sysctl_register",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_sysctl_forward",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/devinet.c:devinet_conf_proc",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589360032,
      "name": "inet_netconf_notify_devconf",
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
