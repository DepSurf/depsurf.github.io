# Function: <code>nla_put_64bit</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int nla_put_64bit(struct sk_buff * skb, int attrtype, int attrlen, const void * data, int padattr)
```

```json
{
  "name": "nla_put_64bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583422528,
      "name": "nla_put_64bit",
      "external": true,
      "loc": "lib/nlattr.c:562",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/netlink.c:quota_send_warning",
        "fs/quota/netlink.c:quota_send_warning",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/core/gen_stats.c:gnet_stats_copy_basic",
        "net/core/gen_stats.c:gnet_stats_start_copy_compat",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info",
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583422528,
      "name": "nla_put_64bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int nla_put_64bit(struct sk_buff * skb, int attrtype, int attrlen, const void * data, int padattr)
```

```json
{
  "name": "nla_put_64bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583548160,
      "name": "nla_put_64bit",
      "external": true,
      "loc": "lib/nlattr.c:562",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/netlink.c:quota_send_warning",
        "fs/quota/netlink.c:quota_send_warning",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_copy_basic",
        "net/core/gen_stats.c:gnet_stats_start_copy_compat",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info",
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583548160,
      "name": "nla_put_64bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int nla_put_64bit(struct sk_buff * skb, int attrtype, int attrlen, const void * data, int padattr)
```

```json
{
  "name": "nla_put_64bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583585824,
      "name": "nla_put_64bit",
      "external": true,
      "loc": "lib/nlattr.c:565",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/netlink.c:quota_send_warning",
        "fs/quota/netlink.c:quota_send_warning",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_copy_basic",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info",
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:__ipmr_fill_mroute",
        "net/ipv4/ipmr.c:__ipmr_fill_mroute",
        "net/ipv6/ip6mr.c:__ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:__ip6mr_fill_mroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583585824,
      "name": "nla_put_64bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int nla_put_64bit(struct sk_buff * skb, int attrtype, int attrlen, const void * data, int padattr)
```

```json
{
  "name": "nla_put_64bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583831984,
      "name": "nla_put_64bit",
      "external": true,
      "loc": "lib/nlattr.c:643",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/netlink.c:quota_send_warning",
        "fs/quota/netlink.c:quota_send_warning",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_copy_basic",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info",
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:__ipmr_fill_mroute",
        "net/ipv4/ipmr.c:__ipmr_fill_mroute",
        "net/ipv6/ip6mr.c:__ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:__ip6mr_fill_mroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583831984,
      "name": "nla_put_64bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int nla_put_64bit(struct sk_buff * skb, int attrtype, int attrlen, const void * data, int padattr)
```

```json
{
  "name": "nla_put_64bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584031968,
      "name": "nla_put_64bit",
      "external": true,
      "loc": "lib/nlattr.c:643",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/netlink.c:quota_send_warning",
        "fs/quota/netlink.c:quota_send_warning",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_copy_basic",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info",
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584031968,
      "name": "nla_put_64bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int nla_put_64bit(struct sk_buff * skb, int attrtype, int attrlen, const void * data, int padattr)
```

```json
{
  "name": "nla_put_64bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584113184,
      "name": "nla_put_64bit",
      "external": true,
      "loc": "lib/nlattr.c:818",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/netlink.c:quota_send_warning",
        "fs/quota/netlink.c:quota_send_warning",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/rtnetlink.c:rtnl_fill_link_ifmap",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info",
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584113184,
      "name": "nla_put_64bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int nla_put_64bit(struct sk_buff * skb, int attrtype, int attrlen, const void * data, int padattr)
```

```json
{
  "name": "nla_put_64bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584304096,
      "name": "nla_put_64bit",
      "external": true,
      "loc": "lib/nlattr.c:850",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/netlink.c:quota_send_warning",
        "fs/quota/netlink.c:quota_send_warning",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/rtnetlink.c:rtnl_fill_link_ifmap",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/devlink.c:devlink_fmsg_prepare_skb",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info",
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584304096,
      "name": "nla_put_64bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int nla_put_64bit(struct sk_buff * skb, int attrtype, int attrlen, const void * data, int padattr)
```

```json
{
  "name": "nla_put_64bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584438800,
      "name": "nla_put_64bit",
      "external": true,
      "loc": "lib/nlattr.c:850",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/netlink.c:quota_send_warning",
        "fs/quota/netlink.c:quota_send_warning",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/rtnetlink.c:rtnl_fill_link_ifmap",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_fmsg_prepare_skb",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info",
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584438800,
      "name": "nla_put_64bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int nla_put_64bit(struct sk_buff * skb, int attrtype, int attrlen, const void * data, int padattr)
```

```json
{
  "name": "nla_put_64bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584999328,
      "name": "nla_put_64bit",
      "external": true,
      "loc": "lib/nlattr.c:1002",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/netlink.c:quota_send_warning",
        "fs/quota/netlink.c:quota_send_warning",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_copy_app",
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/gen_stats.c:gnet_stats_start_copy_compat",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/rtnetlink.c:rtnl_fill_link_ifmap",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/core/drop_monitor.c:net_dm_hw_stats_put",
        "net/core/drop_monitor.c:net_dm_stats_put",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_trap_policer_stats_put",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_fmsg_prepare_skb",
        "net/core/devlink.c:devlink_nl_region_notify_build",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_resource_size_params_put",
        "net/core/devlink.c:devlink_resource_size_params_put",
        "net/core/devlink.c:devlink_resource_size_params_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/netlink/policy.c:netlink_policy_dump_write",
        "net/netlink/policy.c:netlink_policy_dump_write",
        "net/netlink/policy.c:netlink_policy_dump_write",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info",
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/mptcp/diag.c:subflow_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584999328,
      "name": "nla_put_64bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int nla_put_64bit(struct sk_buff * skb, int attrtype, int attrlen, const void * data, int padattr)
```

```json
{
  "name": "nla_put_64bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585119808,
      "name": "nla_put_64bit",
      "external": true,
      "loc": "lib/nlattr.c:1068",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/netlink.c:quota_send_warning",
        "fs/quota/netlink.c:quota_send_warning",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_copy_app",
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/gen_stats.c:gnet_stats_start_copy_compat",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/rtnetlink.c:rtnl_fill_link_ifmap",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/core/drop_monitor.c:net_dm_hw_stats_put",
        "net/core/drop_monitor.c:net_dm_stats_put",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_trap_policer_stats_put",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_fmsg_prepare_skb",
        "net/core/devlink.c:devlink_nl_region_notify_build",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_resource_size_params_put",
        "net/core/devlink.c:devlink_resource_size_params_put",
        "net/core/devlink.c:devlink_resource_size_params_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/ethtool/pause.c:pause_put_stats",
        "net/ethtool/pause.c:pause_put_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info",
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/mptcp/diag.c:subflow_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585119808,
      "name": "nla_put_64bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int nla_put_64bit(struct sk_buff * skb, int attrtype, int attrlen, const void * data, int padattr)
```

```json
{
  "name": "nla_put_64bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585000064,
      "name": "nla_put_64bit",
      "external": true,
      "loc": "lib/nlattr.c:1068",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/netlink.c:quota_send_warning",
        "fs/quota/netlink.c:quota_send_warning",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_copy_app",
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/gen_stats.c:gnet_stats_start_copy_compat",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/rtnetlink.c:rtnl_fill_link_ifmap",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_fmsg_prepare_skb",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify_build",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/ethtool/pause.c:pause_fill_reply",
        "net/ethtool/pause.c:pause_fill_reply",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info",
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info",
        "net/ipv4/nexthop.c:nla_put_nh_group_res",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv6/seg6_local.c:put_nla_counters",
        "net/ipv6/seg6_local.c:put_nla_counters",
        "net/ipv6/seg6_local.c:put_nla_counters",
        "net/mptcp/diag.c:subflow_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585000064,
      "name": "nla_put_64bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int nla_put_64bit(struct sk_buff * skb, int attrtype, int attrlen, const void * data, int padattr)
```

```json
{
  "name": "nla_put_64bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585441280,
      "name": "nla_put_64bit",
      "external": true,
      "loc": "lib/nlattr.c:1068",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/netlink.c:quota_send_warning",
        "fs/quota/netlink.c:quota_send_warning",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_copy_app",
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/gen_stats.c:gnet_stats_start_copy_compat",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/rtnetlink.c:rtnl_fill_link_ifmap",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_fmsg_prepare_skb",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify_build",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/ethtool/pause.c:pause_fill_reply",
        "net/ethtool/pause.c:pause_fill_reply",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info",
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info",
        "net/ipv4/nexthop.c:nla_put_nh_group_res",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv6/ioam6.c:ioam6_genl_dumpns",
        "net/ipv6/seg6_local.c:put_nla_counters",
        "net/ipv6/seg6_local.c:put_nla_counters",
        "net/ipv6/seg6_local.c:put_nla_counters",
        "net/mptcp/diag.c:subflow_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585441280,
      "name": "nla_put_64bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int nla_put_64bit(struct sk_buff * skb, int attrtype, int attrlen, const void * data, int padattr)
```

```json
{
  "name": "nla_put_64bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586582656,
      "name": "nla_put_64bit",
      "external": true,
      "loc": "lib/nlattr.c:1068",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/netlink.c:quota_send_warning",
        "fs/quota/netlink.c:quota_send_warning",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_copy_app",
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_start_copy_compat",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_fmsg_prepare_skb",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify_build",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/ethtool/pause.c:pause_fill_reply",
        "net/ethtool/pause.c:pause_fill_reply",
        "net/ethtool/stats.c:stats_put_rmon_hist",
        "net/ethtool/stats.c:stat_put",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info",
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info",
        "net/ipv4/nexthop.c:nla_put_nh_group_res",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv6/ioam6.c:ioam6_genl_dumpns",
        "net/ipv6/seg6_local.c:put_nla_counters",
        "net/ipv6/seg6_local.c:put_nla_counters",
        "net/ipv6/seg6_local.c:put_nla_counters",
        "net/mptcp/diag.c:subflow_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586582656,
      "name": "nla_put_64bit",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int nla_put_64bit(struct sk_buff * skb, int attrtype, int attrlen, const void * data, int padattr)
```

```json
{
  "name": "nla_put_64bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587821664,
      "name": "nla_put_64bit",
      "external": true,
      "loc": "lib/nlattr.c:1083",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/netlink.c:quota_send_warning",
        "fs/quota/netlink.c:quota_send_warning",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_copy_app",
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_start_copy_compat",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_fmsg_prepare_skb",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify_build",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/ethtool/pause.c:pause_fill_reply",
        "net/ethtool/pause.c:pause_fill_reply",
        "net/ethtool/stats.c:stats_put_rmon_hist",
        "net/ethtool/stats.c:stat_put",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info",
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info",
        "net/ipv4/nexthop.c:nla_put_nh_group_res",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv6/ioam6.c:ioam6_genl_dumpns",
        "net/ipv6/seg6_local.c:put_nla_counters",
        "net/ipv6/seg6_local.c:put_nla_counters",
        "net/ipv6/seg6_local.c:put_nla_counters",
        "net/mptcp/diag.c:subflow_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587821664,
      "name": "nla_put_64bit",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int nla_put_64bit(struct sk_buff * skb, int attrtype, int attrlen, const void * data, int padattr)
```

```json
{
  "name": "nla_put_64bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588093088,
      "name": "nla_put_64bit",
      "external": true,
      "loc": "lib/nlattr.c:1083",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/netlink.c:quota_send_warning",
        "fs/quota/netlink.c:quota_send_warning",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_copy_app",
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_start_copy_compat",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/ethtool/pause.c:pause_fill_reply",
        "net/ethtool/pause.c:pause_fill_reply",
        "net/ethtool/stats.c:stats_put_rmon_hist",
        "net/ethtool/stats.c:stat_put",
        "net/ethtool/mm.c:mm_fill_reply",
        "net/ethtool/mm.c:mm_fill_reply",
        "net/ethtool/mm.c:mm_fill_reply",
        "net/ethtool/mm.c:mm_fill_reply",
        "net/ethtool/mm.c:mm_fill_reply",
        "net/ethtool/mm.c:mm_fill_reply",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info",
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info",
        "net/ipv4/nexthop.c:nla_put_nh_group_res",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv6/ioam6.c:ioam6_genl_dumpns",
        "net/ipv6/seg6_local.c:put_nla_counters",
        "net/ipv6/seg6_local.c:put_nla_counters",
        "net/ipv6/seg6_local.c:put_nla_counters",
        "net/devlink/leftover.c:devlink_nl_trap_policer_fill",
        "net/devlink/leftover.c:devlink_nl_trap_policer_fill",
        "net/devlink/leftover.c:devlink_nl_trap_policer_fill",
        "net/devlink/leftover.c:devlink_nl_trap_group_fill",
        "net/devlink/leftover.c:devlink_nl_trap_group_fill",
        "net/devlink/leftover.c:devlink_nl_trap_fill",
        "net/devlink/leftover.c:devlink_nl_trap_fill",
        "net/devlink/leftover.c:devlink_nl_trap_fill",
        "net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit",
        "net/devlink/leftover.c:devlink_nl_region_notify_build",
        "net/devlink/leftover.c:devlink_dpipe_entry_put",
        "net/devlink/leftover.c:devlink_dpipe_entry_put",
        "net/devlink/leftover.c:devlink_dpipe_table_put",
        "net/devlink/leftover.c:devlink_dpipe_table_put",
        "net/devlink/leftover.c:devlink_dpipe_table_put",
        "net/devlink/dev.c:devlink_nl_flash_update_fill",
        "net/devlink/dev.c:devlink_nl_flash_update_fill",
        "net/devlink/dev.c:devlink_nl_flash_update_fill",
        "net/devlink/health.c:devlink_fmsg_prepare_skb",
        "net/devlink/health.c:devlink_nl_health_reporter_fill",
        "net/devlink/health.c:devlink_nl_health_reporter_fill",
        "net/devlink/health.c:devlink_nl_health_reporter_fill",
        "net/devlink/health.c:devlink_nl_health_reporter_fill",
        "net/devlink/health.c:devlink_nl_health_reporter_fill",
        "net/mptcp/diag.c:subflow_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588093088,
      "name": "nla_put_64bit",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int nla_put_64bit(struct sk_buff * skb, int attrtype, int attrlen, const void * data, int padattr)
```

```json
{
  "name": "nla_put_64bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588428960,
      "name": "nla_put_64bit",
      "external": true,
      "loc": "lib/nlattr.c:1115",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/netlink.c:quota_send_warning",
        "fs/quota/netlink.c:quota_send_warning",
        "drivers/dpll/dpll_netlink.c:dpll_cmd_pin_get_one",
        "drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_dplls",
        "drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_freq",
        "drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_freq",
        "drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_freq",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_copy_app",
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_start_copy_compat",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/netdev-genl.c:netdev_nl_dev_fill",
        "net/core/netdev-genl.c:netdev_nl_dev_fill",
        "net/core/netdev-genl.c:netdev_nl_dev_fill",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/ethtool/pause.c:pause_fill_reply",
        "net/ethtool/pause.c:pause_fill_reply",
        "net/ethtool/stats.c:stats_put_rmon_hist",
        "net/ethtool/stats.c:stat_put",
        "net/ethtool/mm.c:mm_fill_reply",
        "net/ethtool/mm.c:mm_fill_reply",
        "net/ethtool/mm.c:mm_fill_reply",
        "net/ethtool/mm.c:mm_fill_reply",
        "net/ethtool/mm.c:mm_fill_reply",
        "net/ethtool/mm.c:mm_fill_reply",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info",
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info",
        "net/ipv4/nexthop.c:nla_put_nh_group_res",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv6/ioam6.c:ioam6_genl_dumpns",
        "net/ipv6/seg6_local.c:put_nla_counters",
        "net/ipv6/seg6_local.c:put_nla_counters",
        "net/ipv6/seg6_local.c:put_nla_counters",
        "net/devlink/dev.c:devlink_nl_flash_update_fill",
        "net/devlink/dev.c:devlink_nl_flash_update_fill",
        "net/devlink/dev.c:devlink_nl_flash_update_fill",
        "net/devlink/dpipe.c:devlink_dpipe_entry_put",
        "net/devlink/dpipe.c:devlink_dpipe_entry_put",
        "net/devlink/dpipe.c:devlink_dpipe_table_put",
        "net/devlink/dpipe.c:devlink_dpipe_table_put",
        "net/devlink/dpipe.c:devlink_dpipe_table_put",
        "net/devlink/region.c:devlink_nl_region_read_dumpit",
        "net/devlink/region.c:devlink_nl_region_notify_build",
        "net/devlink/health.c:devlink_fmsg_prepare_skb",
        "net/devlink/health.c:devlink_nl_health_reporter_fill",
        "net/devlink/health.c:devlink_nl_health_reporter_fill",
        "net/devlink/health.c:devlink_nl_health_reporter_fill",
        "net/devlink/health.c:devlink_nl_health_reporter_fill",
        "net/devlink/health.c:devlink_nl_health_reporter_fill",
        "net/devlink/trap.c:devlink_nl_trap_policer_fill",
        "net/devlink/trap.c:devlink_nl_trap_policer_fill",
        "net/devlink/trap.c:devlink_nl_trap_policer_fill",
        "net/devlink/trap.c:devlink_nl_trap_group_fill",
        "net/devlink/trap.c:devlink_nl_trap_group_fill",
        "net/devlink/trap.c:devlink_nl_trap_fill",
        "net/devlink/trap.c:devlink_nl_trap_fill",
        "net/devlink/trap.c:devlink_nl_trap_fill",
        "net/mptcp/diag.c:subflow_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588428960,
      "name": "nla_put_64bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int nla_put_64bit(struct sk_buff * skb, int attrtype, int attrlen, const void * data, int padattr)
```

```json
{
  "name": "nla_put_64bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496324296,
      "name": "nla_put_64bit",
      "external": true,
      "loc": "lib/nlattr.c:850",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/netlink.c:quota_send_warning",
        "fs/quota/netlink.c:quota_send_warning",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/gen_stats.c:gnet_stats_start_copy_compat",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/rtnetlink.c:rtnl_fill_link_ifmap",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_fmsg_prepare_skb",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info",
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496324296,
      "name": "nla_put_64bit",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int nla_put_64bit(struct sk_buff * skb, int attrtype, int attrlen, const void * data, int padattr)
```

```json
{
  "name": "nla_put_64bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229658952,
      "name": "nla_put_64bit",
      "external": true,
      "loc": "lib/nlattr.c:850",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/netlink.c:quota_send_warning",
        "fs/quota/netlink.c:quota_send_warning",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/rtnetlink.c:rtnl_fill_link_ifmap",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_fmsg_prepare_skb",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info",
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229658952,
      "name": "nla_put_64bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int nla_put_64bit(struct sk_buff * skb, int attrtype, int attrlen, const void * data, int padattr)
```

```json
{
  "name": "nla_put_64bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290642752,
      "name": "nla_put_64bit",
      "external": true,
      "loc": "lib/nlattr.c:850",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/netlink.c:quota_send_warning",
        "fs/quota/netlink.c:quota_send_warning",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/rtnetlink.c:rtnl_fill_link_ifmap",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_fmsg_prepare_skb",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info",
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290642752,
      "name": "nla_put_64bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int nla_put_64bit(struct sk_buff * skb, int attrtype, int attrlen, const void * data, int padattr)
```

```json
{
  "name": "nla_put_64bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275376138,
      "name": "nla_put_64bit",
      "external": true,
      "loc": "lib/nlattr.c:850",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/netlink.c:quota_send_warning",
        "fs/quota/netlink.c:quota_send_warning",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/rtnetlink.c:rtnl_fill_link_ifmap",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_fmsg_prepare_skb",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info",
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275376138,
      "name": "nla_put_64bit",
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
int nla_put_64bit(struct sk_buff * skb, int attrtype, int attrlen, const void * data, int padattr)
```

```json
{
  "name": "nla_put_64bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584407536,
      "name": "nla_put_64bit",
      "external": true,
      "loc": "lib/nlattr.c:850",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/netlink.c:quota_send_warning",
        "fs/quota/netlink.c:quota_send_warning",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/rtnetlink.c:rtnl_fill_link_ifmap",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_fmsg_prepare_skb",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info",
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584407536,
      "name": "nla_put_64bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int nla_put_64bit(struct sk_buff * skb, int attrtype, int attrlen, const void * data, int padattr)
```

```json
{
  "name": "nla_put_64bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584342736,
      "name": "nla_put_64bit",
      "external": true,
      "loc": "lib/nlattr.c:850",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/netlink.c:quota_send_warning",
        "fs/quota/netlink.c:quota_send_warning",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/rtnetlink.c:rtnl_fill_link_ifmap",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_fmsg_prepare_skb",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info",
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584342736,
      "name": "nla_put_64bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int nla_put_64bit(struct sk_buff * skb, int attrtype, int attrlen, const void * data, int padattr)
```

```json
{
  "name": "nla_put_64bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584390448,
      "name": "nla_put_64bit",
      "external": true,
      "loc": "lib/nlattr.c:850",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/netlink.c:quota_send_warning",
        "fs/quota/netlink.c:quota_send_warning",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/rtnetlink.c:rtnl_fill_link_ifmap",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_fmsg_prepare_skb",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/netfilter/nf_conntrack_proto_dccp.c:dccp_to_nlattr",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_timestamp",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_timestamp",
        "net/netfilter/nf_conntrack_netlink.c:dump_counters",
        "net/netfilter/nf_conntrack_netlink.c:dump_counters",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info",
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584390448,
      "name": "nla_put_64bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int nla_put_64bit(struct sk_buff * skb, int attrtype, int attrlen, const void * data, int padattr)
```

```json
{
  "name": "nla_put_64bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584496512,
      "name": "nla_put_64bit",
      "external": true,
      "loc": "lib/nlattr.c:850",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/netlink.c:quota_send_warning",
        "fs/quota/netlink.c:quota_send_warning",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_finish_copy",
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:gnet_stats_copy_rate_est",
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/rtnetlink.c:rtnl_fill_link_ifmap",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_fmsg_prepare_skb",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp.c:tcp_get_timestamping_opt_stats",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info",
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584496512,
      "name": "nla_put_64bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int nla_put_64bit(struct sk_buff * skb, int attrtype, int attrlen, const void * data, int padattr)
```
</details>
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
