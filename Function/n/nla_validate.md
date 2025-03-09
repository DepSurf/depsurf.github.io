# Function: <code>nla_validate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int nla_validate(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy)
```

```json
{
  "name": "nla_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583127424,
      "name": "nla_validate",
      "external": true,
      "loc": "lib/nlattr.c:122",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583127424,
      "name": "nla_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int nla_validate(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy)
```

```json
{
  "name": "nla_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583421600,
      "name": "nla_validate",
      "external": true,
      "loc": "lib/nlattr.c:122",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/switchdev/switchdev.c:switchdev_port_bridge_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583421600,
      "name": "nla_validate",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int nla_validate(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy)
```

```json
{
  "name": "nla_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583547264,
      "name": "nla_validate",
      "external": true,
      "loc": "lib/nlattr.c:122",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/switchdev/switchdev.c:switchdev_port_bridge_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583547264,
      "name": "nla_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int nla_validate(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nla_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583584896,
      "name": "nla_validate",
      "external": true,
      "loc": "lib/nlattr.c:123",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/switchdev/switchdev.c:switchdev_port_bridge_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583584896,
      "name": "nla_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int nla_validate(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nla_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583830928,
      "name": "nla_validate",
      "external": true,
      "loc": "lib/nlattr.c:175",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583830928,
      "name": "nla_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int nla_validate(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nla_validate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584032496,
      "name": "nla_validate",
      "external": true,
      "loc": "lib/nlattr.c:175",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584032496,
      "name": "nla_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int nla_validate(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nla_validate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584114330,
      "name": "nla_validate",
      "external": true,
      "loc": "lib/nlattr.c:332",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla"
      ],
      "caller_func": [
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584115088,
      "name": "nla_validate.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071584115232,
      "name": "nla_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nla_validate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589441144,
      "name": "nla_validate",
      "external": false,
      "loc": "include/net/netlink.h:836",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590350877,
      "name": "nla_validate",
      "external": false,
      "loc": "include/net/netlink.h:836",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nla_validate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589441688,
      "name": "nla_validate",
      "external": false,
      "loc": "include/net/netlink.h:849",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590403197,
      "name": "nla_validate",
      "external": false,
      "loc": "include/net/netlink.h:849",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nla_validate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589341492,
      "name": "nla_validate",
      "external": false,
      "loc": "include/net/netlink.h:849",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590319341,
      "name": "nla_validate",
      "external": false,
      "loc": "include/net/netlink.h:849",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "nla_validate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590072094,
      "name": "nla_validate",
      "external": false,
      "loc": "include/net/netlink.h:849",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591107069,
      "name": "nla_validate",
      "external": false,
      "loc": "include/net/netlink.h:849",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "nla_validate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591620943,
      "name": "nla_validate",
      "external": false,
      "loc": "include/net/netlink.h:849",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592759469,
      "name": "nla_validate",
      "external": false,
      "loc": "include/net/netlink.h:849",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "nla_validate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593402351,
      "name": "nla_validate",
      "external": false,
      "loc": "include/net/netlink.h:866",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594632525,
      "name": "nla_validate",
      "external": false,
      "loc": "include/net/netlink.h:866",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "nla_validate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593866751,
      "name": "nla_validate",
      "external": false,
      "loc": "include/net/netlink.h:867",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595024893,
      "name": "nla_validate",
      "external": false,
      "loc": "include/net/netlink.h:867",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "nla_validate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594650899,
      "name": "nla_validate",
      "external": false,
      "loc": "include/net/netlink.h:874",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595837703,
      "name": "nla_validate",
      "external": false,
      "loc": "include/net/netlink.h:874",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int nla_validate(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, struct netlink_ext_ack * extack)
```
</details>
</li>
</ul>
