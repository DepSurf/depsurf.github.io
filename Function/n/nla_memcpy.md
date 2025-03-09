# Function: <code>nla_memcpy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int nla_memcpy(void * dest, const struct nlattr * src, int count)
```

```json
{
  "name": "nla_memcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583127888,
      "name": "nla_memcpy",
      "external": true,
      "loc": "lib/nlattr.c:277",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/fib6_rules.c:fib6_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583127888,
      "name": "nla_memcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int nla_memcpy(void * dest, const struct nlattr * src, int count)
```

```json
{
  "name": "nla_memcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583422112,
      "name": "nla_memcpy",
      "external": true,
      "loc": "lib/nlattr.c:277",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/fib6_rules.c:fib6_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583422112,
      "name": "nla_memcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int nla_memcpy(void * dest, const struct nlattr * src, int count)
```

```json
{
  "name": "nla_memcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583547744,
      "name": "nla_memcpy",
      "external": true,
      "loc": "lib/nlattr.c:277",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/fib6_rules.c:fib6_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583547744,
      "name": "nla_memcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int nla_memcpy(void * dest, const struct nlattr * src, int count)
```

```json
{
  "name": "nla_memcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583585408,
      "name": "nla_memcpy",
      "external": true,
      "loc": "lib/nlattr.c:285",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/fib6_rules.c:fib6_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583585408,
      "name": "nla_memcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int nla_memcpy(void * dest, const struct nlattr * src, int count)
```

```json
{
  "name": "nla_memcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583831440,
      "name": "nla_memcpy",
      "external": true,
      "loc": "lib/nlattr.c:363",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/sched/act_api.c:tc_dump_action",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/fib6_rules.c:fib6_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583831440,
      "name": "nla_memcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int nla_memcpy(void * dest, const struct nlattr * src, int count)
```

```json
{
  "name": "nla_memcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584031408,
      "name": "nla_memcpy",
      "external": true,
      "loc": "lib/nlattr.c:363",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/rtnetlink.c:do_setlink",
        "net/sched/act_api.c:tc_dump_action",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/fib6_rules.c:fib6_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584031408,
      "name": "nla_memcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int nla_memcpy(void * dest, const struct nlattr * src, int count)
```

```json
{
  "name": "nla_memcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584112592,
      "name": "nla_memcpy",
      "external": true,
      "loc": "lib/nlattr.c:538",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/rtnetlink.c:do_setlink",
        "net/sched/act_api.c:tc_dump_action",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/fib6_rules.c:fib6_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584112592,
      "name": "nla_memcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int nla_memcpy(void * dest, const struct nlattr * src, int count)
```

```json
{
  "name": "nla_memcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584301536,
      "name": "nla_memcpy",
      "external": true,
      "loc": "lib/nlattr.c:570",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/sched/act_api.c:tc_dump_action",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/fib6_rules.c:fib6_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584301536,
      "name": "nla_memcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int nla_memcpy(void * dest, const struct nlattr * src, int count)
```

```json
{
  "name": "nla_memcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584436256,
      "name": "nla_memcpy",
      "external": true,
      "loc": "lib/nlattr.c:570",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/sched/act_api.c:tc_dump_action",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/fib6_rules.c:fib6_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584436256,
      "name": "nla_memcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int nla_memcpy(void * dest, const struct nlattr * src, int count)
```

```json
{
  "name": "nla_memcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584998784,
      "name": "nla_memcpy",
      "external": true,
      "loc": "lib/nlattr.c:722",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:nla_validate_int_range",
        "lib/nlattr.c:nla_validate_int_range",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/devlink.c:devlink_trap_policer_set",
        "net/core/devlink.c:devlink_trap_policer_set",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/mptcp/pm_netlink.c:mptcp_pm_parse_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584998784,
      "name": "nla_memcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int nla_memcpy(void * dest, const struct nlattr * src, int count)
```

```json
{
  "name": "nla_memcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585119104,
      "name": "nla_memcpy",
      "external": true,
      "loc": "lib/nlattr.c:789",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:nla_validate_int_range",
        "lib/nlattr.c:nla_validate_int_range",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/devlink.c:devlink_trap_policer_set",
        "net/core/devlink.c:devlink_trap_policer_set",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_flash_update",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/mptcp/pm_netlink.c:mptcp_pm_parse_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585119104,
      "name": "nla_memcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int nla_memcpy(void * dest, const struct nlattr * src, int count)
```

```json
{
  "name": "nla_memcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584999376,
      "name": "nla_memcpy",
      "external": true,
      "loc": "lib/nlattr.c:789",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:nla_validate_int_range",
        "lib/nlattr.c:nla_validate_int_range",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_flash_update",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/mptcp/pm_netlink.c:mptcp_pm_parse_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584999376,
      "name": "nla_memcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int nla_memcpy(void * dest, const struct nlattr * src, int count)
```

```json
{
  "name": "nla_memcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585440592,
      "name": "nla_memcpy",
      "external": true,
      "loc": "lib/nlattr.c:789",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:nla_validate_int_range",
        "lib/nlattr.c:nla_validate_int_range",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_flash_update",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_nl_rate_set",
        "net/core/devlink.c:devlink_nl_rate_set",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/ioam6.c:ioam6_genl_addsc",
        "net/ipv6/ioam6.c:ioam6_genl_addns",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/mptcp/pm_netlink.c:mptcp_pm_parse_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585440592,
      "name": "nla_memcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int nla_memcpy(void * dest, const struct nlattr * src, int count)
```

```json
{
  "name": "nla_memcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586581168,
      "name": "nla_memcpy",
      "external": true,
      "loc": "lib/nlattr.c:789",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:nla_validate_int_range",
        "lib/nlattr.c:nla_validate_int_range",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_flash_update",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_nl_rate_set",
        "net/core/devlink.c:devlink_nl_rate_set",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/ioam6.c:ioam6_genl_addsc",
        "net/ipv6/ioam6.c:ioam6_genl_addns",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/ioam6_iptunnel.c:ioam6_build_state",
        "net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586581168,
      "name": "nla_memcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int nla_memcpy(void * dest, const struct nlattr * src, int count)
```

```json
{
  "name": "nla_memcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587822288,
      "name": "nla_memcpy",
      "external": true,
      "loc": "lib/nlattr.c:804",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:nla_validate_range_unsigned",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_flash_update",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_nl_rate_set",
        "net/core/devlink.c:devlink_nl_rate_set",
        "net/core/devlink.c:devlink_port_function_set",
        "net/core/devlink.c:devlink_port_function_set",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/ioam6.c:ioam6_genl_addsc",
        "net/ipv6/ioam6.c:ioam6_genl_addns",
        "net/ipv6/ip6mr.c:ip6mr_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_getroute",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/ioam6_iptunnel.c:ioam6_build_state",
        "net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587822288,
      "name": "nla_memcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int nla_memcpy(void * dest, const struct nlattr * src, int count)
```

```json
{
  "name": "nla_memcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588093760,
      "name": "nla_memcpy",
      "external": true,
      "loc": "lib/nlattr.c:804",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:nla_validate_range_unsigned",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/rtnetlink.c:do_setlink",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/ioam6.c:ioam6_genl_addsc",
        "net/ipv6/ioam6.c:ioam6_genl_addns",
        "net/ipv6/ip6mr.c:ip6mr_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_getroute",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/ioam6_iptunnel.c:ioam6_build_state",
        "net/devlink/leftover.c:devlink_nl_cmd_trap_policer_set_doit",
        "net/devlink/leftover.c:devlink_nl_cmd_trap_policer_set_doit",
        "net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit",
        "net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit",
        "net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit",
        "net/devlink/leftover.c:devlink_nl_cmd_resource_set",
        "net/devlink/leftover.c:devlink_nl_cmd_resource_set",
        "net/devlink/leftover.c:devlink_nl_rate_set",
        "net/devlink/leftover.c:devlink_nl_rate_set",
        "net/devlink/leftover.c:devlink_port_function_set",
        "net/devlink/leftover.c:devlink_port_function_set",
        "net/devlink/dev.c:devlink_nl_cmd_flash_update",
        "net/devlink/dev.c:devlink_nl_cmd_reload",
        "net/devlink/health.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588093760,
      "name": "nla_memcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int nla_memcpy(void * dest, const struct nlattr * src, int count)
```

```json
{
  "name": "nla_memcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588429584,
      "name": "nla_memcpy",
      "external": true,
      "loc": "lib/nlattr.c:836",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:nla_validate_range_unsigned",
        "drivers/dpll/dpll_netlink.c:dpll_device_find_from_nlattr",
        "drivers/dpll/dpll_netlink.c:dpll_pin_find_from_nlattr",
        "drivers/dpll/dpll_netlink.c:dpll_pin_freq_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/page_pool_user.c:netdev_nl_page_pool_get_doit",
        "net/core/page_pool_user.c:netdev_nl_page_pool_stats_get_doit",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/ioam6.c:ioam6_genl_addsc",
        "net/ipv6/ioam6.c:ioam6_genl_addns",
        "net/ipv6/ip6mr.c:ip6mr_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_getroute",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/ioam6_iptunnel.c:ioam6_build_state",
        "net/devlink/dev.c:devlink_nl_flash_update_doit",
        "net/devlink/dev.c:devlink_nl_reload_doit",
        "net/devlink/port.c:devlink_port_function_set",
        "net/devlink/port.c:devlink_port_function_validate",
        "net/devlink/resource.c:devlink_nl_resource_set_doit",
        "net/devlink/resource.c:devlink_nl_resource_set_doit",
        "net/devlink/region.c:devlink_nl_region_read_dumpit",
        "net/devlink/region.c:devlink_nl_region_read_dumpit",
        "net/devlink/region.c:devlink_nl_region_read_dumpit",
        "net/devlink/health.c:devlink_nl_health_reporter_set_doit",
        "net/devlink/trap.c:devlink_nl_trap_policer_set_doit",
        "net/devlink/trap.c:devlink_nl_trap_policer_set_doit",
        "net/devlink/rate.c:devlink_nl_rate_set",
        "net/devlink/rate.c:devlink_nl_rate_set",
        "net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588429584,
      "name": "nla_memcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int nla_memcpy(void * dest, const struct nlattr * src, int count)
```

```json
{
  "name": "nla_memcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496321488,
      "name": "nla_memcpy",
      "external": true,
      "loc": "lib/nlattr.c:570",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/sched/act_api.c:tc_dump_action",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/fib6_rules.c:fib6_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496321488,
      "name": "nla_memcpy",
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
int nla_memcpy(void * dest, const struct nlattr * src, int count)
```

```json
{
  "name": "nla_memcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229656052,
      "name": "nla_memcpy",
      "external": true,
      "loc": "lib/nlattr.c:570",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/fib_rules.c:fib_nl2rule",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/sched/act_api.c:tc_dump_action",
        "net/ipv4/tcp_metrics.c:__parse_nl_addr",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/fib6_rules.c:fib6_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229656052,
      "name": "nla_memcpy",
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
int nla_memcpy(void * dest, const struct nlattr * src, int count)
```

```json
{
  "name": "nla_memcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290638720,
      "name": "nla_memcpy",
      "external": true,
      "loc": "lib/nlattr.c:570",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/sched/act_api.c:tc_dump_action",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/fib6_rules.c:fib6_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290638720,
      "name": "nla_memcpy",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int nla_memcpy(void * dest, const struct nlattr * src, int count)
```

```json
{
  "name": "nla_memcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275373748,
      "name": "nla_memcpy",
      "external": true,
      "loc": "lib/nlattr.c:570",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/sched/act_api.c:tc_dump_action",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/fib6_rules.c:fib6_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275373748,
      "name": "nla_memcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int nla_memcpy(void * dest, const struct nlattr * src, int count)
```

```json
{
  "name": "nla_memcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584404992,
      "name": "nla_memcpy",
      "external": true,
      "loc": "lib/nlattr.c:570",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/sched/act_api.c:tc_dump_action",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/fib6_rules.c:fib6_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584404992,
      "name": "nla_memcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int nla_memcpy(void * dest, const struct nlattr * src, int count)
```

```json
{
  "name": "nla_memcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584340192,
      "name": "nla_memcpy",
      "external": true,
      "loc": "lib/nlattr.c:570",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla",
        "drivers/net/vxlan.c:vxlan_nl2conf",
        "drivers/net/vxlan.c:vxlan_nl2conf",
        "drivers/net/vxlan.c:vxlan_fdb_parse",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/sched/act_api.c:tc_dump_action",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/fib6_rules.c:fib6_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584340192,
      "name": "nla_memcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int nla_memcpy(void * dest, const struct nlattr * src, int count)
```

```json
{
  "name": "nla_memcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584387904,
      "name": "nla_memcpy",
      "external": true,
      "loc": "lib/nlattr.c:570",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/sched/act_api.c:tc_dump_action",
        "net/netfilter/nf_conntrack_proto_dccp.c:nlattr_to_dccp",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/fib6_rules.c:fib6_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584387904,
      "name": "nla_memcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int nla_memcpy(void * dest, const struct nlattr * src, int count)
```

```json
{
  "name": "nla_memcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584493968,
      "name": "nla_memcpy",
      "external": true,
      "loc": "lib/nlattr.c:570",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neightbl_set",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/sched/act_api.c:tc_dump_action",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_build_state",
        "net/ipv4/ip_tunnel_core.c:ip_tun_build_state",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/fib6_rules.c:fib6_rule_configure",
        "net/ipv6/fib6_rules.c:fib6_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584493968,
      "name": "nla_memcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
