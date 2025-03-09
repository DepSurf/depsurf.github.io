# Function: <code>rtnl_register_module</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int rtnl_register_module(struct module * owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587918512,
      "name": "rtnl_register_module",
      "external": true,
      "loc": "net/core/rtnetlink.c:240",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587918512,
      "name": "rtnl_register_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int rtnl_register_module(struct module * owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588063728,
      "name": "rtnl_register_module",
      "external": true,
      "loc": "net/core/rtnetlink.c:246",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588063728,
      "name": "rtnl_register_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int rtnl_register_module(struct module * owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588379232,
      "name": "rtnl_register_module",
      "external": true,
      "loc": "net/core/rtnetlink.c:241",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588379232,
      "name": "rtnl_register_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int rtnl_register_module(struct module * owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588585600,
      "name": "rtnl_register_module",
      "external": true,
      "loc": "net/core/rtnetlink.c:241",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588585600,
      "name": "rtnl_register_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int rtnl_register_module(struct module * owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589435088,
      "name": "rtnl_register_module",
      "external": true,
      "loc": "net/core/rtnetlink.c:241",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589435088,
      "name": "rtnl_register_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int rtnl_register_module(struct module * owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589435584,
      "name": "rtnl_register_module",
      "external": true,
      "loc": "net/core/rtnetlink.c:241",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589435584,
      "name": "rtnl_register_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int rtnl_register_module(struct module * owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589332992,
      "name": "rtnl_register_module",
      "external": true,
      "loc": "net/core/rtnetlink.c:241",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589332992,
      "name": "rtnl_register_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int rtnl_register_module(struct module * owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590063040,
      "name": "rtnl_register_module",
      "external": true,
      "loc": "net/core/rtnetlink.c:241",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590063040,
      "name": "rtnl_register_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int rtnl_register_module(struct module * owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591607808,
      "name": "rtnl_register_module",
      "external": true,
      "loc": "net/core/rtnetlink.c:278",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/mctp/device.c:mctp_device_init",
        "net/mctp/device.c:mctp_device_init",
        "net/mctp/device.c:mctp_device_init",
        "net/mctp/route.c:mctp_routes_init",
        "net/mctp/route.c:mctp_routes_init",
        "net/mctp/route.c:mctp_routes_init",
        "net/mctp/neigh.c:mctp_neigh_init",
        "net/mctp/neigh.c:mctp_neigh_init",
        "net/mctp/neigh.c:mctp_neigh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591607808,
      "name": "rtnl_register_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int rtnl_register_module(struct module * owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593389712,
      "name": "rtnl_register_module",
      "external": true,
      "loc": "net/core/rtnetlink.c:279",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/mctp/device.c:mctp_device_init",
        "net/mctp/device.c:mctp_device_init",
        "net/mctp/device.c:mctp_device_init",
        "net/mctp/route.c:mctp_routes_init",
        "net/mctp/route.c:mctp_routes_init",
        "net/mctp/route.c:mctp_routes_init",
        "net/mctp/neigh.c:mctp_neigh_init",
        "net/mctp/neigh.c:mctp_neigh_init",
        "net/mctp/neigh.c:mctp_neigh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593389712,
      "name": "rtnl_register_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int rtnl_register_module(struct module * owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593853344,
      "name": "rtnl_register_module",
      "external": true,
      "loc": "net/core/rtnetlink.c:282",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/mctp/device.c:mctp_device_init",
        "net/mctp/device.c:mctp_device_init",
        "net/mctp/device.c:mctp_device_init",
        "net/mctp/route.c:mctp_routes_init",
        "net/mctp/route.c:mctp_routes_init",
        "net/mctp/route.c:mctp_routes_init",
        "net/mctp/neigh.c:mctp_neigh_init",
        "net/mctp/neigh.c:mctp_neigh_init",
        "net/mctp/neigh.c:mctp_neigh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593853344,
      "name": "rtnl_register_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int rtnl_register_module(struct module * owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594635856,
      "name": "rtnl_register_module",
      "external": true,
      "loc": "net/core/rtnetlink.c:283",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/mctp/device.c:mctp_device_init",
        "net/mctp/device.c:mctp_device_init",
        "net/mctp/device.c:mctp_device_init",
        "net/mctp/route.c:mctp_routes_init",
        "net/mctp/route.c:mctp_routes_init",
        "net/mctp/route.c:mctp_routes_init",
        "net/mctp/neigh.c:mctp_neigh_init",
        "net/mctp/neigh.c:mctp_neigh_init",
        "net/mctp/neigh.c:mctp_neigh_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594635856,
      "name": "rtnl_register_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int rtnl_register_module(struct module * owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502132056,
      "name": "rtnl_register_module",
      "external": true,
      "loc": "net/core/rtnetlink.c:241",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502132056,
      "name": "rtnl_register_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int rtnl_register_module(struct module * owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234875548,
      "name": "rtnl_register_module",
      "external": true,
      "loc": "net/core/rtnetlink.c:241",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234875548,
      "name": "rtnl_register_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int rtnl_register_module(struct module * owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295594992,
      "name": "rtnl_register_module",
      "external": true,
      "loc": "net/core/rtnetlink.c:241",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295594992,
      "name": "rtnl_register_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int rtnl_register_module(struct module * owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278395680,
      "name": "rtnl_register_module",
      "external": true,
      "loc": "net/core/rtnetlink.c:241",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278395680,
      "name": "rtnl_register_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int rtnl_register_module(struct module * owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588192336,
      "name": "rtnl_register_module",
      "external": true,
      "loc": "net/core/rtnetlink.c:241",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588192336,
      "name": "rtnl_register_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int rtnl_register_module(struct module * owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587905168,
      "name": "rtnl_register_module",
      "external": true,
      "loc": "net/core/rtnetlink.c:241",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587905168,
      "name": "rtnl_register_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int rtnl_register_module(struct module * owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588524160,
      "name": "rtnl_register_module",
      "external": true,
      "loc": "net/core/rtnetlink.c:241",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588524160,
      "name": "rtnl_register_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int rtnl_register_module(struct module * owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```

```json
{
  "name": "rtnl_register_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588661440,
      "name": "rtnl_register_module",
      "external": true,
      "loc": "net/core/rtnetlink.c:241",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/addrlabel.c:ipv6_addr_label_rtnl_register",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588661440,
      "name": "rtnl_register_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int rtnl_register_module(struct module * owner, int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags)
```
</details>
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
