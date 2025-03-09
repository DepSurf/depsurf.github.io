# Function: <code>__nla_validate</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __nla_validate(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_validate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584302257,
      "name": "__nla_validate",
      "external": true,
      "loc": "lib/nlattr.c:419",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:validate_nla"
      ],
      "caller_func": [
        "kernel/taskstats.c:taskstats_pre_doit",
        "lib/nlattr.c:validate_nla",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
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
      "addr": 18446744071584303536,
      "name": "__nla_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __nla_validate(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_validate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584437049,
      "name": "__nla_validate",
      "external": true,
      "loc": "lib/nlattr.c:419",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:validate_nla"
      ],
      "caller_func": [
        "kernel/taskstats.c:taskstats_pre_doit",
        "lib/nlattr.c:validate_nla",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
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
      "addr": 18446744071584438240,
      "name": "__nla_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int __nla_validate(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585002368,
      "name": "__nla_validate",
      "external": true,
      "loc": "lib/nlattr.c:571",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_pre_doit",
        "net/ethtool/strset.c:strset_parse_request",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585002368,
      "name": "__nla_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
int __nla_validate(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585123216,
      "name": "__nla_validate",
      "external": true,
      "loc": "lib/nlattr.c:626",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/strset.c:strset_parse_request",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585123216,
      "name": "__nla_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
int __nla_validate(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585003776,
      "name": "__nla_validate",
      "external": true,
      "loc": "lib/nlattr.c:626",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/strset.c:strset_parse_request",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585003776,
      "name": "__nla_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
int __nla_validate(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585445184,
      "name": "__nla_validate",
      "external": true,
      "loc": "lib/nlattr.c:626",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/strset.c:strset_parse_request",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585445184,
      "name": "__nla_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
int __nla_validate(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586586480,
      "name": "__nla_validate",
      "external": true,
      "loc": "lib/nlattr.c:626",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/strset.c:strset_parse_request",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586586480,
      "name": "__nla_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int __nla_validate(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587826992,
      "name": "__nla_validate",
      "external": true,
      "loc": "lib/nlattr.c:641",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/strset.c:strset_parse_request",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587826992,
      "name": "__nla_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int __nla_validate(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588098352,
      "name": "__nla_validate",
      "external": true,
      "loc": "lib/nlattr.c:641",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/strset.c:strset_parse_request",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588098352,
      "name": "__nla_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int __nla_validate(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588434448,
      "name": "__nla_validate",
      "external": true,
      "loc": "lib/nlattr.c:673",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/strset.c:strset_parse_request",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588434448,
      "name": "__nla_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int __nla_validate(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_validate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496322324,
      "name": "__nla_validate",
      "external": true,
      "loc": "lib/nlattr.c:419",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:validate_nla"
      ],
      "caller_func": [
        "kernel/taskstats.c:taskstats_pre_doit",
        "lib/nlattr.c:validate_nla",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
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
      "addr": 18446603336496323584,
      "name": "__nla_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int __nla_validate(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_validate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229657184,
      "name": "__nla_validate",
      "external": true,
      "loc": "lib/nlattr.c:419",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:validate_nla"
      ],
      "caller_func": [
        "kernel/taskstats.c:taskstats_pre_doit",
        "lib/nlattr.c:validate_nla",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229658324,
      "name": "__nla_validate",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int __nla_validate(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_validate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290640536,
      "name": "__nla_validate",
      "external": true,
      "loc": "lib/nlattr.c:419",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:validate_nla"
      ],
      "caller_func": [
        "kernel/taskstats.c:taskstats_pre_doit",
        "lib/nlattr.c:validate_nla",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
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
      "addr": 13835058055290641888,
      "name": "__nla_validate",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int __nla_validate(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_validate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275374776,
      "name": "__nla_validate",
      "external": true,
      "loc": "lib/nlattr.c:419",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:validate_nla"
      ],
      "caller_func": [
        "kernel/taskstats.c:taskstats_pre_doit",
        "lib/nlattr.c:validate_nla",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
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
      "addr": 18446743936275375362,
      "name": "__nla_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int __nla_validate(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_validate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584405785,
      "name": "__nla_validate",
      "external": true,
      "loc": "lib/nlattr.c:419",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:validate_nla"
      ],
      "caller_func": [
        "kernel/taskstats.c:taskstats_pre_doit",
        "lib/nlattr.c:validate_nla",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
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
      "addr": 18446744071584406976,
      "name": "__nla_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int __nla_validate(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_validate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584340985,
      "name": "__nla_validate",
      "external": true,
      "loc": "lib/nlattr.c:419",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:validate_nla"
      ],
      "caller_func": [
        "kernel/taskstats.c:taskstats_pre_doit",
        "lib/nlattr.c:validate_nla",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
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
      "addr": 18446744071584342176,
      "name": "__nla_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int __nla_validate(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_validate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584388697,
      "name": "__nla_validate",
      "external": true,
      "loc": "lib/nlattr.c:419",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:validate_nla"
      ],
      "caller_func": [
        "kernel/taskstats.c:taskstats_pre_doit",
        "lib/nlattr.c:validate_nla",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_parse_tuple",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_parse_tuple_proto",
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
      "addr": 18446744071584389888,
      "name": "__nla_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int __nla_validate(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```

```json
{
  "name": "__nla_validate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584494761,
      "name": "__nla_validate",
      "external": true,
      "loc": "lib/nlattr.c:419",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:validate_nla"
      ],
      "caller_func": [
        "kernel/taskstats.c:taskstats_pre_doit",
        "lib/nlattr.c:validate_nla",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
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
      "addr": 18446744071584495952,
      "name": "__nla_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int __nla_validate(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack)
```
</details>
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
