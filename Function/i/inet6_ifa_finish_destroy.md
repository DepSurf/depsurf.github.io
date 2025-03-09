# Function: <code>inet6_ifa_finish_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void inet6_ifa_finish_destroy(struct inet6_ifaddr * ifp)
```

```json
{
  "name": "inet6_ifa_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587027888,
      "name": "inet6_ifa_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf.c:848",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587027888,
      "name": "inet6_ifa_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void inet6_ifa_finish_destroy(struct inet6_ifaddr * ifp)
```

```json
{
  "name": "inet6_ifa_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587475280,
      "name": "inet6_ifa_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf.c:862",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587475280,
      "name": "inet6_ifa_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void inet6_ifa_finish_destroy(struct inet6_ifaddr * ifp)
```

```json
{
  "name": "inet6_ifa_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587678544,
      "name": "inet6_ifa_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf.c:889",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587678544,
      "name": "inet6_ifa_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void inet6_ifa_finish_destroy(struct inet6_ifaddr * ifp)
```

```json
{
  "name": "inet6_ifa_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587828912,
      "name": "inet6_ifa_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf.c:908",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587828912,
      "name": "inet6_ifa_finish_destroy",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void inet6_ifa_finish_destroy(struct inet6_ifaddr * ifp)
```

```json
{
  "name": "inet6_ifa_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588359168,
      "name": "inet6_ifa_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf.c:912",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588359168,
      "name": "inet6_ifa_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void inet6_ifa_finish_destroy(struct inet6_ifaddr * ifp)
```

```json
{
  "name": "inet6_ifa_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet6_ifa_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf.c:901",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588737979,
      "name": "inet6_ifa_finish_destroy.cold.77",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071588716720,
      "name": "inet6_ifa_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void inet6_ifa_finish_destroy(struct inet6_ifaddr * ifp)
```

```json
{
  "name": "inet6_ifa_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet6_ifa_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf.c:915",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588958059,
      "name": "inet6_ifa_finish_destroy.cold.79",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071588936048,
      "name": "inet6_ifa_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void inet6_ifa_finish_destroy(struct inet6_ifaddr * ifp)
```

```json
{
  "name": "inet6_ifa_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet6_ifa_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf.c:949",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589401427,
      "name": "inet6_ifa_finish_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071589378896,
      "name": "inet6_ifa_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void inet6_ifa_finish_destroy(struct inet6_ifaddr * ifp)
```

```json
{
  "name": "inet6_ifa_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet6_ifa_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf.c:949",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589625846,
      "name": "inet6_ifa_finish_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071589603328,
      "name": "inet6_ifa_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void inet6_ifa_finish_destroy(struct inet6_ifaddr * ifp)
```

```json
{
  "name": "inet6_ifa_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet6_ifa_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf.c:949",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590636286,
      "name": "inet6_ifa_finish_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071590609936,
      "name": "inet6_ifa_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void inet6_ifa_finish_destroy(struct inet6_ifaddr * ifp)
```

```json
{
  "name": "inet6_ifa_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet6_ifa_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf.c:949",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591635880,
      "name": "inet6_ifa_finish_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071590670656,
      "name": "inet6_ifa_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void inet6_ifa_finish_destroy(struct inet6_ifaddr * ifp)
```

```json
{
  "name": "inet6_ifa_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet6_ifa_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf.c:951",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591579319,
      "name": "inet6_ifa_finish_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071590596336,
      "name": "inet6_ifa_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void inet6_ifa_finish_destroy(struct inet6_ifaddr * ifp)
```

```json
{
  "name": "inet6_ifa_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet6_ifa_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf.c:958",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592737017,
      "name": "inet6_ifa_finish_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071591409120,
      "name": "inet6_ifa_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void inet6_ifa_finish_destroy(struct inet6_ifaddr * ifp)
```

```json
{
  "name": "inet6_ifa_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet6_ifa_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf.c:968",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594623595,
      "name": "inet6_ifa_finish_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071593086432,
      "name": "inet6_ifa_finish_destroy",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void inet6_ifa_finish_destroy(struct inet6_ifaddr * ifp)
```

```json
{
  "name": "inet6_ifa_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594980800,
      "name": "inet6_ifa_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf.c:968",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594980800,
      "name": "inet6_ifa_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void inet6_ifa_finish_destroy(struct inet6_ifaddr * ifp)
```

```json
{
  "name": "inet6_ifa_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595373952,
      "name": "inet6_ifa_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf.c:967",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595373952,
      "name": "inet6_ifa_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void inet6_ifa_finish_destroy(struct inet6_ifaddr * ifp)
```

```json
{
  "name": "inet6_ifa_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596215104,
      "name": "inet6_ifa_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf.c:986",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596215104,
      "name": "inet6_ifa_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void inet6_ifa_finish_destroy(struct inet6_ifaddr * ifp)
```

```json
{
  "name": "inet6_ifa_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503280176,
      "name": "inet6_ifa_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf.c:949",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503280176,
      "name": "inet6_ifa_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void inet6_ifa_finish_destroy(struct inet6_ifaddr * ifp)
```

```json
{
  "name": "inet6_ifa_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235952364,
      "name": "inet6_ifa_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf.c:949",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/ipv6/ndisc.c:ndisc_rcv",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235952364,
      "name": "inet6_ifa_finish_destroy",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void inet6_ifa_finish_destroy(struct inet6_ifaddr * ifp)
```

```json
{
  "name": "inet6_ifa_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297032384,
      "name": "inet6_ifa_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf.c:949",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297032384,
      "name": "inet6_ifa_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void inet6_ifa_finish_destroy(struct inet6_ifaddr * ifp)
```

```json
{
  "name": "inet6_ifa_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279302978,
      "name": "inet6_ifa_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf.c:949",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279302978,
      "name": "inet6_ifa_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void inet6_ifa_finish_destroy(struct inet6_ifaddr * ifp)
```

```json
{
  "name": "inet6_ifa_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet6_ifa_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf.c:949",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589230214,
      "name": "inet6_ifa_finish_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071589207696,
      "name": "inet6_ifa_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void inet6_ifa_finish_destroy(struct inet6_ifaddr * ifp)
```

```json
{
  "name": "inet6_ifa_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet6_ifa_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf.c:949",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588955206,
      "name": "inet6_ifa_finish_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071588932688,
      "name": "inet6_ifa_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void inet6_ifa_finish_destroy(struct inet6_ifaddr * ifp)
```

```json
{
  "name": "inet6_ifa_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet6_ifa_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf.c:949",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589667078,
      "name": "inet6_ifa_finish_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071589644560,
      "name": "inet6_ifa_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void inet6_ifa_finish_destroy(struct inet6_ifaddr * ifp)
```

```json
{
  "name": "inet6_ifa_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet6_ifa_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf.c:949",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589716054,
      "name": "inet6_ifa_finish_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071589693568,
      "name": "inet6_ifa_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
