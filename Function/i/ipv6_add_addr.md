# Function: <code>ipv6_add_addr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct inet6_ifaddr * ipv6_add_addr(struct inet6_dev * idev, const struct in6_addr * addr, const struct in6_addr * peer_addr, int pfxlen, int scope, u32 flags, u32 valid_lft, u32 prefered_lft)
```

```json
{
  "name": "ipv6_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587013760,
      "name": "ipv6_add_addr",
      "external": false,
      "loc": "net/ipv6/addrconf.c:899",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587013760,
      "name": "ipv6_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1020
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
struct inet6_ifaddr * ipv6_add_addr(struct inet6_dev * idev, const struct in6_addr * addr, const struct in6_addr * peer_addr, int pfxlen, int scope, u32 flags, u32 valid_lft, u32 prefered_lft)
```

```json
{
  "name": "ipv6_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587460688,
      "name": "ipv6_add_addr",
      "external": false,
      "loc": "net/ipv6/addrconf.c:913",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587460688,
      "name": "ipv6_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1105
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
struct inet6_ifaddr * ipv6_add_addr(struct inet6_dev * idev, const struct in6_addr * addr, const struct in6_addr * peer_addr, int pfxlen, int scope, u32 flags, u32 valid_lft, u32 prefered_lft)
```

```json
{
  "name": "ipv6_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587664192,
      "name": "ipv6_add_addr",
      "external": false,
      "loc": "net/ipv6/addrconf.c:940",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587664192,
      "name": "ipv6_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1108
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
struct inet6_ifaddr * ipv6_add_addr(struct inet6_dev * idev, const struct in6_addr * addr, const struct in6_addr * peer_addr, int pfxlen, int scope, u32 flags, u32 valid_lft, u32 prefered_lft)
```

```json
{
  "name": "ipv6_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587823008,
      "name": "ipv6_add_addr",
      "external": false,
      "loc": "net/ipv6/addrconf.c:959",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587823008,
      "name": "ipv6_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1378
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
struct inet6_ifaddr * ipv6_add_addr(struct inet6_dev * idev, const struct in6_addr * addr, const struct in6_addr * peer_addr, int pfxlen, int scope, u32 flags, u32 valid_lft, u32 prefered_lft, bool can_block, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipv6_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588353184,
      "name": "ipv6_add_addr",
      "external": false,
      "loc": "net/ipv6/addrconf.c:1001",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588353184,
      "name": "ipv6_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1459
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
struct inet6_ifaddr * ipv6_add_addr(struct inet6_dev * idev, struct ifa6_config * cfg, bool can_block, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipv6_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588710544,
      "name": "ipv6_add_addr",
      "external": false,
      "loc": "net/ipv6/addrconf.c:989",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588710544,
      "name": "ipv6_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1530
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
struct inet6_ifaddr * ipv6_add_addr(struct inet6_dev * idev, struct ifa6_config * cfg, bool can_block, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipv6_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588930000,
      "name": "ipv6_add_addr",
      "external": false,
      "loc": "net/ipv6/addrconf.c:1003",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588930000,
      "name": "ipv6_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1438
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
struct inet6_ifaddr * ipv6_add_addr(struct inet6_dev * idev, struct ifa6_config * cfg, bool can_block, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipv6_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589372608,
      "name": "ipv6_add_addr",
      "external": false,
      "loc": "net/ipv6/addrconf.c:1037",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589372608,
      "name": "ipv6_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1495
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
struct inet6_ifaddr * ipv6_add_addr(struct inet6_dev * idev, struct ifa6_config * cfg, bool can_block, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipv6_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589597040,
      "name": "ipv6_add_addr",
      "external": false,
      "loc": "net/ipv6/addrconf.c:1037",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589597040,
      "name": "ipv6_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1498
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
struct inet6_ifaddr * ipv6_add_addr(struct inet6_dev * idev, struct ifa6_config * cfg, bool can_block, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipv6_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590603328,
      "name": "ipv6_add_addr",
      "external": false,
      "loc": "net/ipv6/addrconf.c:1037",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590603328,
      "name": "ipv6_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1443
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
struct inet6_ifaddr * ipv6_add_addr(struct inet6_dev * idev, struct ifa6_config * cfg, bool can_block, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipv6_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590664048,
      "name": "ipv6_add_addr",
      "external": false,
      "loc": "net/ipv6/addrconf.c:1037",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590664048,
      "name": "ipv6_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1443
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
struct inet6_ifaddr * ipv6_add_addr(struct inet6_dev * idev, struct ifa6_config * cfg, bool can_block, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipv6_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590589616,
      "name": "ipv6_add_addr",
      "external": false,
      "loc": "net/ipv6/addrconf.c:1039",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590589616,
      "name": "ipv6_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1746
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
struct inet6_ifaddr * ipv6_add_addr(struct inet6_dev * idev, struct ifa6_config * cfg, bool can_block, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipv6_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591402272,
      "name": "ipv6_add_addr",
      "external": false,
      "loc": "net/ipv6/addrconf.c:1046",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591402272,
      "name": "ipv6_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1746
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
struct inet6_ifaddr * ipv6_add_addr(struct inet6_dev * idev, struct ifa6_config * cfg, bool can_block, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipv6_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593078560,
      "name": "ipv6_add_addr",
      "external": false,
      "loc": "net/ipv6/addrconf.c:1055",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593078560,
      "name": "ipv6_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1684
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
struct inet6_ifaddr * ipv6_add_addr(struct inet6_dev * idev, struct ifa6_config * cfg, bool can_block, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipv6_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594972848,
      "name": "ipv6_add_addr",
      "external": false,
      "loc": "net/ipv6/addrconf.c:1055",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594972848,
      "name": "ipv6_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1676
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
struct inet6_ifaddr * ipv6_add_addr(struct inet6_dev * idev, struct ifa6_config * cfg, bool can_block, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipv6_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595365600,
      "name": "ipv6_add_addr",
      "external": false,
      "loc": "net/ipv6/addrconf.c:1054",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595365600,
      "name": "ipv6_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1611
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
struct inet6_ifaddr * ipv6_add_addr(struct inet6_dev * idev, struct ifa6_config * cfg, bool can_block, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipv6_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596206528,
      "name": "ipv6_add_addr",
      "external": false,
      "loc": "net/ipv6/addrconf.c:1073",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596206528,
      "name": "ipv6_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1746
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
struct inet6_ifaddr * ipv6_add_addr(struct inet6_dev * idev, struct ifa6_config * cfg, bool can_block, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipv6_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503274080,
      "name": "ipv6_add_addr",
      "external": false,
      "loc": "net/ipv6/addrconf.c:1037",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503274080,
      "name": "ipv6_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1292
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
struct inet6_ifaddr * ipv6_add_addr(struct inet6_dev * idev, struct ifa6_config * cfg, bool can_block, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipv6_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235944212,
      "name": "ipv6_add_addr",
      "external": false,
      "loc": "net/ipv6/addrconf.c:1037",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235944212,
      "name": "ipv6_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1380
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
struct inet6_ifaddr * ipv6_add_addr(struct inet6_dev * idev, struct ifa6_config * cfg, bool can_block, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipv6_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297016816,
      "name": "ipv6_add_addr",
      "external": false,
      "loc": "net/ipv6/addrconf.c:1037",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297016816,
      "name": "ipv6_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1792
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
struct inet6_ifaddr * ipv6_add_addr(struct inet6_dev * idev, struct ifa6_config * cfg, bool can_block, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipv6_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279297490,
      "name": "ipv6_add_addr",
      "external": false,
      "loc": "net/ipv6/addrconf.c:1037",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279297490,
      "name": "ipv6_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1284
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
struct inet6_ifaddr * ipv6_add_addr(struct inet6_dev * idev, struct ifa6_config * cfg, bool can_block, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipv6_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589201408,
      "name": "ipv6_add_addr",
      "external": false,
      "loc": "net/ipv6/addrconf.c:1037",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589201408,
      "name": "ipv6_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1498
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
struct inet6_ifaddr * ipv6_add_addr(struct inet6_dev * idev, struct ifa6_config * cfg, bool can_block, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipv6_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588926400,
      "name": "ipv6_add_addr",
      "external": false,
      "loc": "net/ipv6/addrconf.c:1037",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588926400,
      "name": "ipv6_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1498
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
struct inet6_ifaddr * ipv6_add_addr(struct inet6_dev * idev, struct ifa6_config * cfg, bool can_block, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipv6_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589638272,
      "name": "ipv6_add_addr",
      "external": false,
      "loc": "net/ipv6/addrconf.c:1037",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589638272,
      "name": "ipv6_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1498
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
struct inet6_ifaddr * ipv6_add_addr(struct inet6_dev * idev, struct ifa6_config * cfg, bool can_block, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ipv6_add_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589687264,
      "name": "ipv6_add_addr",
      "external": false,
      "loc": "net/ipv6/addrconf.c:1037",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589687264,
      "name": "ipv6_add_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1519
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool can_block</code>
</li>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack * extack</code>
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
<code>struct ifa6_config * cfg</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct in6_addr * addr</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct in6_addr * peer_addr</code>
</li>
<li>
<b>Param removed. </b>
<code>int pfxlen</code>
</li>
<li>
<b>Param removed. </b>
<code>int scope</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 flags</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 valid_lft</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 prefered_lft</code>
</li>
<li>
<b>Param reordered. </b>
<code>idev, addr, peer_addr, pfxlen, scope, flags, valid_lft, prefered_lft, can_block, extack</code> ➡️ <code>idev, cfg, can_block, extack</code>
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
