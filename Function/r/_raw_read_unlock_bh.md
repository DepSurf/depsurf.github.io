# Function: <code>_raw_read_unlock_bh</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t * lock)
```

```json
{
  "name": "_raw_read_unlock_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587381296,
      "name": "_raw_read_unlock_bh",
      "external": true,
      "loc": "kernel/locking/spinlock.c:277",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_unit_number",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_name",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_input_error",
        "net/core/sock.c:sock_i_uid",
        "net/core/sock.c:sock_i_uid",
        "net/core/sock.c:sock_i_ino",
        "net/core/sock.c:sock_i_ino",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/ping.c:ping_seq_stop",
        "net/ipv4/ping.c:ping_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_spd_getinfo",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup",
        "net/ipv6/anycast.c:ipv6_chk_acast_dev",
        "net/ipv6/anycast.c:ipv6_chk_acast_dev",
        "net/ipv6/anycast.c:ac6_seq_stop",
        "net/ipv6/anycast.c:ac6_seq_start",
        "net/ipv6/addrconf.c:ipv6_count_addresses",
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:ipv6_chk_custom_prefix",
        "net/ipv6/addrconf.c:ipv6_chk_prefix",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:ipv6_get_lladdr",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/ip6_fib.c:inet6_dump_fib",
        "net/ipv6/ip6_fib.c:inet6_dump_fib",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/mcast.c:igmp6_mcf_seq_stop",
        "net/ipv6/mcast.c:igmp6_mc_seq_stop",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu",
        "net/ipv6/mcast.c:igmp6_mcf_seq_next",
        "net/ipv6/mcast.c:igmp6_mc_seq_start",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:igmp6_mcf_seq_start",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:ipv6_mc_unmap",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587381296,
      "name": "_raw_read_unlock_bh",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t * lock)
```

```json
{
  "name": "_raw_read_unlock_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587884256,
      "name": "_raw_read_unlock_bh",
      "external": true,
      "loc": "kernel/locking/spinlock.c:277",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_name",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_number",
        "drivers/net/ppp/ppp_generic.c:ppp_input_error",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "net/core/sock.c:sock_i_ino",
        "net/core/sock.c:sock_i_ino",
        "net/core/sock.c:sock_i_uid",
        "net/core/sock.c:sock_i_uid",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/ping.c:ping_seq_stop",
        "net/ipv4/ping.c:ping_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup",
        "net/xfrm/xfrm_policy.c:xfrm_spd_getinfo",
        "net/ipv6/anycast.c:ac6_seq_stop",
        "net/ipv6/anycast.c:ac6_seq_start",
        "net/ipv6/anycast.c:ipv6_chk_acast_dev",
        "net/ipv6/anycast.c:ipv6_chk_acast_dev",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/addrconf.c:ipv6_chk_prefix",
        "net/ipv6/addrconf.c:ipv6_chk_custom_prefix",
        "net/ipv6/addrconf.c:ipv6_count_addresses",
        "net/ipv6/addrconf.c:ipv6_get_lladdr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/ip6_fib.c:inet6_dump_fib",
        "net/ipv6/ip6_fib.c:inet6_dump_fib",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/mcast.c:igmp6_mcf_seq_stop",
        "net/ipv6/mcast.c:igmp6_mcf_seq_next",
        "net/ipv6/mcast.c:igmp6_mcf_seq_start",
        "net/ipv6/mcast.c:igmp6_mc_seq_stop",
        "net/ipv6/mcast.c:igmp6_mc_seq_start",
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_unmap",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587884256,
      "name": "_raw_read_unlock_bh",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t * lock)
```

```json
{
  "name": "_raw_read_unlock_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588102560,
      "name": "_raw_read_unlock_bh",
      "external": true,
      "loc": "kernel/locking/spinlock.c:277",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_name",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_number",
        "drivers/net/ppp/ppp_generic.c:ppp_input_error",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "net/core/sock.c:sock_i_ino",
        "net/core/sock.c:sock_i_ino",
        "net/core/sock.c:sock_i_uid",
        "net/core/sock.c:sock_i_uid",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/ping.c:ping_seq_stop",
        "net/ipv4/ping.c:ping_lookup",
        "net/ipv6/anycast.c:ac6_seq_stop",
        "net/ipv6/anycast.c:ac6_seq_start",
        "net/ipv6/anycast.c:ipv6_chk_acast_dev",
        "net/ipv6/anycast.c:ipv6_chk_acast_dev",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/addrconf.c:ipv6_chk_prefix",
        "net/ipv6/addrconf.c:ipv6_chk_custom_prefix",
        "net/ipv6/addrconf.c:ipv6_count_addresses",
        "net/ipv6/addrconf.c:ipv6_get_lladdr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/ip6_fib.c:inet6_dump_fib",
        "net/ipv6/ip6_fib.c:inet6_dump_fib",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/mcast.c:igmp6_mcf_seq_stop",
        "net/ipv6/mcast.c:igmp6_mcf_seq_next",
        "net/ipv6/mcast.c:igmp6_mcf_seq_start",
        "net/ipv6/mcast.c:igmp6_mc_seq_stop",
        "net/ipv6/mcast.c:igmp6_mc_seq_start",
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_unmap",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588102560,
      "name": "_raw_read_unlock_bh",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t * lock)
```

```json
{
  "name": "_raw_read_unlock_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588328240,
      "name": "_raw_read_unlock_bh",
      "external": true,
      "loc": "kernel/locking/spinlock.c:277",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_name",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_number",
        "drivers/net/ppp/ppp_generic.c:ppp_input_error",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "net/core/sock.c:sock_i_ino",
        "net/core/sock.c:sock_i_uid",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/ping.c:ping_seq_stop",
        "net/ipv4/ping.c:ping_lookup",
        "net/ipv6/anycast.c:ac6_seq_stop",
        "net/ipv6/anycast.c:ac6_seq_start",
        "net/ipv6/anycast.c:ipv6_chk_acast_dev",
        "net/ipv6/anycast.c:ipv6_chk_acast_dev",
        "net/ipv6/addrconf.c:addrconf_disable_policy_idev",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/addrconf.c:ipv6_chk_prefix",
        "net/ipv6/addrconf.c:ipv6_chk_custom_prefix",
        "net/ipv6/addrconf.c:ipv6_count_addresses",
        "net/ipv6/addrconf.c:ipv6_count_addresses",
        "net/ipv6/addrconf.c:ipv6_get_lladdr",
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr",
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/ip6_fib.c:inet6_dump_fib",
        "net/ipv6/ip6_fib.c:inet6_dump_fib",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/mcast.c:igmp6_mcf_seq_stop",
        "net/ipv6/mcast.c:igmp6_mcf_seq_next",
        "net/ipv6/mcast.c:igmp6_mcf_seq_start",
        "net/ipv6/mcast.c:igmp6_mc_seq_stop",
        "net/ipv6/mcast.c:igmp6_mc_seq_start",
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_unmap",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588328240,
      "name": "_raw_read_unlock_bh",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t * lock)
```

```json
{
  "name": "_raw_read_unlock_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588894432,
      "name": "_raw_read_unlock_bh",
      "external": true,
      "loc": "kernel/locking/spinlock.c:270",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_name",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_number",
        "drivers/net/ppp/ppp_generic.c:ppp_input_error",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "net/core/sock.c:sock_i_ino",
        "net/core/sock.c:sock_i_uid",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/ping.c:ping_seq_stop",
        "net/ipv4/ping.c:ping_lookup",
        "net/ipv6/anycast.c:ac6_seq_stop",
        "net/ipv6/anycast.c:ac6_seq_start",
        "net/ipv6/anycast.c:ipv6_chk_acast_dev",
        "net/ipv6/anycast.c:ipv6_chk_acast_dev",
        "net/ipv6/addrconf.c:addrconf_disable_policy_idev",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:ipv6_get_lladdr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/mcast.c:igmp6_mcf_seq_stop",
        "net/ipv6/mcast.c:igmp6_mcf_seq_next",
        "net/ipv6/mcast.c:igmp6_mcf_seq_start",
        "net/ipv6/mcast.c:igmp6_mc_seq_stop",
        "net/ipv6/mcast.c:igmp6_mc_seq_start",
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_unmap",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588894432,
      "name": "_raw_read_unlock_bh",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t * lock)
```

```json
{
  "name": "_raw_read_unlock_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589272608,
      "name": "_raw_read_unlock_bh",
      "external": true,
      "loc": "kernel/locking/spinlock.c:270",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_name",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_number",
        "drivers/net/ppp/ppp_generic.c:ppp_input_error",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "net/core/sock.c:sock_i_ino",
        "net/core/sock.c:sock_i_uid",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/ping.c:ping_seq_stop",
        "net/ipv4/ping.c:ping_lookup",
        "net/ipv6/anycast.c:ac6_seq_stop",
        "net/ipv6/anycast.c:ac6_seq_start",
        "net/ipv6/anycast.c:ipv6_chk_acast_dev",
        "net/ipv6/addrconf.c:addrconf_disable_policy_idev",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:ipv6_get_lladdr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/mcast.c:igmp6_mcf_seq_stop",
        "net/ipv6/mcast.c:igmp6_mcf_seq_next",
        "net/ipv6/mcast.c:igmp6_mcf_seq_start",
        "net/ipv6/mcast.c:igmp6_mc_seq_stop",
        "net/ipv6/mcast.c:igmp6_mc_seq_start",
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_unmap",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589272608,
      "name": "_raw_read_unlock_bh",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t * lock)
```

```json
{
  "name": "_raw_read_unlock_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589515856,
      "name": "_raw_read_unlock_bh",
      "external": true,
      "loc": "kernel/locking/spinlock.c:270",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_name",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_number",
        "drivers/net/ppp/ppp_generic.c:ppp_input_error",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "net/core/sock.c:sock_i_ino",
        "net/core/sock.c:sock_i_uid",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/ping.c:ping_seq_stop",
        "net/ipv4/ping.c:ping_lookup",
        "net/ipv6/anycast.c:ac6_seq_stop",
        "net/ipv6/anycast.c:ac6_seq_start",
        "net/ipv6/addrconf.c:addrconf_disable_policy_idev",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_dad_run",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:ipv6_get_lladdr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/mcast.c:igmp6_mcf_seq_stop",
        "net/ipv6/mcast.c:igmp6_mcf_seq_next",
        "net/ipv6/mcast.c:igmp6_mcf_seq_start",
        "net/ipv6/mcast.c:igmp6_mc_seq_stop",
        "net/ipv6/mcast.c:igmp6_mc_seq_start",
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_unmap",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589515856,
      "name": "_raw_read_unlock_bh",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t * lock)
```

```json
{
  "name": "_raw_read_unlock_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589975008,
      "name": "_raw_read_unlock_bh",
      "external": true,
      "loc": "kernel/locking/spinlock.c:277",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_name",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_number",
        "drivers/net/ppp/ppp_generic.c:ppp_input_error",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "net/core/sock.c:sock_i_ino",
        "net/core/sock.c:sock_i_uid",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/ping.c:ping_seq_stop",
        "net/ipv4/ping.c:ping_lookup",
        "net/ipv6/anycast.c:ac6_seq_stop",
        "net/ipv6/anycast.c:ac6_seq_start",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr",
        "net/ipv6/addrconf.c:addrconf_disable_policy_idev",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_dad_run",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:ipv6_get_lladdr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/mcast.c:igmp6_mcf_seq_stop",
        "net/ipv6/mcast.c:igmp6_mcf_seq_next",
        "net/ipv6/mcast.c:igmp6_mcf_seq_start",
        "net/ipv6/mcast.c:igmp6_mc_seq_stop",
        "net/ipv6/mcast.c:igmp6_mc_seq_start",
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_unmap",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589975008,
      "name": "_raw_read_unlock_bh",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t * lock)
```

```json
{
  "name": "_raw_read_unlock_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590202304,
      "name": "_raw_read_unlock_bh",
      "external": true,
      "loc": "kernel/locking/spinlock.c:277",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_name",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_number",
        "drivers/net/ppp/ppp_generic.c:ppp_input_error",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "net/core/sock.c:sock_i_ino",
        "net/core/sock.c:sock_i_uid",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/ping.c:ping_seq_stop",
        "net/ipv4/ping.c:ping_lookup",
        "net/ipv6/anycast.c:ac6_seq_stop",
        "net/ipv6/anycast.c:ac6_seq_start",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr",
        "net/ipv6/addrconf.c:addrconf_disable_policy_idev",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_dad_run",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:ipv6_get_lladdr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/mcast.c:igmp6_mcf_seq_stop",
        "net/ipv6/mcast.c:igmp6_mcf_seq_next",
        "net/ipv6/mcast.c:igmp6_mcf_seq_start",
        "net/ipv6/mcast.c:igmp6_mc_seq_stop",
        "net/ipv6/mcast.c:igmp6_mc_seq_start",
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_unmap",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590202304,
      "name": "_raw_read_unlock_bh",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t * lock)
```

```json
{
  "name": "_raw_read_unlock_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591217840,
      "name": "_raw_read_unlock_bh",
      "external": true,
      "loc": "kernel/locking/spinlock.c:277",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_name",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_number",
        "drivers/net/ppp/ppp_generic.c:ppp_input_error",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "net/core/sock.c:sock_i_ino",
        "net/core/sock.c:sock_i_uid",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/neighbour.c:pneigh_dump_table",
        "net/core/neighbour.c:pneigh_dump_table",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/ping.c:ping_seq_stop",
        "net/ipv6/anycast.c:ac6_seq_stop",
        "net/ipv6/anycast.c:ac6_get_idx",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr",
        "net/ipv6/addrconf.c:addrconf_disable_policy_idev",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_dad_run",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_begin",
        "net/ipv6/addrconf.c:addrconf_dad_begin",
        "net/ipv6/addrconf.c:addrconf_dad_begin",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:ipv6_get_lladdr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/mcast.c:igmp6_mcf_seq_stop",
        "net/ipv6/mcast.c:igmp6_mcf_seq_next",
        "net/ipv6/mcast.c:igmp6_mcf_seq_start",
        "net/ipv6/mcast.c:igmp6_mc_seq_stop",
        "net/ipv6/mcast.c:igmp6_mc_get_idx",
        "net/ipv6/mcast.c:ipv6_mc_rejoin_groups",
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_unmap",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591217840,
      "name": "_raw_read_unlock_bh",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t * lock)
```

```json
{
  "name": "_raw_read_unlock_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591712272,
      "name": "_raw_read_unlock_bh",
      "external": true,
      "loc": "kernel/locking/spinlock.c:277",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_name",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_number",
        "drivers/net/ppp/ppp_generic.c:ppp_input_error",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "net/core/sock.c:sock_i_ino",
        "net/core/sock.c:sock_i_uid",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/neighbour.c:pneigh_dump_table",
        "net/core/neighbour.c:pneigh_dump_table",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/ping.c:ping_seq_stop",
        "net/ipv6/anycast.c:ac6_seq_stop",
        "net/ipv6/anycast.c:ac6_get_idx",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr",
        "net/ipv6/addrconf.c:addrconf_disable_policy_idev",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_dad_run",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_begin",
        "net/ipv6/addrconf.c:addrconf_dad_begin",
        "net/ipv6/addrconf.c:addrconf_dad_begin",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:ipv6_get_lladdr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/mcast.c:igmp6_mcf_seq_stop",
        "net/ipv6/mcast.c:igmp6_mcf_seq_next",
        "net/ipv6/mcast.c:igmp6_mcf_seq_start",
        "net/ipv6/mcast.c:igmp6_mc_seq_stop",
        "net/ipv6/mcast.c:igmp6_mc_get_idx",
        "net/ipv6/mcast.c:ipv6_mc_rejoin_groups",
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_unmap",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591712272,
      "name": "_raw_read_unlock_bh",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t * lock)
```

```json
{
  "name": "_raw_read_unlock_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591659680,
      "name": "_raw_read_unlock_bh",
      "external": true,
      "loc": "kernel/locking/spinlock.c:277",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_name",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_number",
        "drivers/net/ppp/ppp_generic.c:ppp_input_error",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "net/core/sock.c:sock_i_ino",
        "net/core/sock.c:sock_i_uid",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/ping.c:ping_seq_stop",
        "net/ipv6/anycast.c:ac6_seq_stop",
        "net/ipv6/anycast.c:ac6_seq_start",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr",
        "net/ipv6/addrconf.c:addrconf_disable_policy_idev",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_dad_run",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_begin",
        "net/ipv6/addrconf.c:addrconf_dad_begin",
        "net/ipv6/addrconf.c:addrconf_dad_begin",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:ipv6_get_lladdr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591659680,
      "name": "_raw_read_unlock_bh",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t * lock)
```

```json
{
  "name": "_raw_read_unlock_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592833408,
      "name": "_raw_read_unlock_bh",
      "external": true,
      "loc": "kernel/locking/spinlock.c:282",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_name",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_number",
        "drivers/net/ppp/ppp_generic.c:ppp_input_error",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "net/core/sock.c:sock_i_ino",
        "net/core/sock.c:sock_i_uid",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv4/ping.c:ping_seq_stop",
        "net/ipv6/anycast.c:ac6_seq_stop",
        "net/ipv6/anycast.c:ac6_seq_start",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr",
        "net/ipv6/addrconf.c:addrconf_disable_policy_idev",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_dad_run",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_begin",
        "net/ipv6/addrconf.c:addrconf_dad_begin",
        "net/ipv6/addrconf.c:addrconf_dad_begin",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:ipv6_get_lladdr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592833408,
      "name": "_raw_read_unlock_bh",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t * lock)
```

```json
{
  "name": "_raw_read_unlock_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594745232,
      "name": "_raw_read_unlock_bh",
      "external": true,
      "loc": "kernel/locking/spinlock.c:282",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_name",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_number",
        "drivers/net/ppp/ppp_generic.c:ppp_input_error",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "net/core/sock.c:sock_i_ino",
        "net/core/sock.c:sock_i_uid",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv6/anycast.c:ac6_seq_stop",
        "net/ipv6/anycast.c:ac6_seq_start",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr",
        "net/ipv6/addrconf.c:addrconf_disable_policy_idev",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_dad_run",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:ipv6_get_lladdr",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594745232,
      "name": "_raw_read_unlock_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void _raw_read_unlock_bh(rwlock_t * lock)
```

```json
{
  "name": "_raw_read_unlock_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596498144,
      "name": "_raw_read_unlock_bh",
      "external": true,
      "loc": "kernel/locking/spinlock.c:282",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_name",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_number",
        "drivers/net/ppp/ppp_generic.c:ppp_input_error",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "net/core/sock.c:sock_i_ino",
        "net/core/sock.c:sock_i_uid",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv6/anycast.c:ac6_seq_stop",
        "net/ipv6/anycast.c:ac6_seq_start",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr",
        "net/ipv6/addrconf.c:addrconf_disable_policy_idev",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_dad_run",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:ipv6_get_lladdr",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596498144,
      "name": "_raw_read_unlock_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void _raw_read_unlock_bh(rwlock_t * lock)
```

```json
{
  "name": "_raw_read_unlock_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597035712,
      "name": "_raw_read_unlock_bh",
      "external": true,
      "loc": "kernel/locking/spinlock.c:282",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_name",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_number",
        "drivers/net/ppp/ppp_generic.c:ppp_input_error",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "net/core/sock.c:sock_i_uid",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/neighbour.c:neigh_seq_stop",
        "net/core/neighbour.c:neigh_for_each",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv6/anycast.c:ac6_seq_stop",
        "net/ipv6/anycast.c:ac6_seq_start",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr",
        "net/ipv6/addrconf.c:addrconf_disable_policy_idev",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_dad_run",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:ipv6_inherit_eui64",
        "net/ipv6/addrconf.c:ipv6_get_lladdr",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597035712,
      "name": "_raw_read_unlock_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void _raw_read_unlock_bh(rwlock_t * lock)
```

```json
{
  "name": "_raw_read_unlock_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597967680,
      "name": "_raw_read_unlock_bh",
      "external": true,
      "loc": "kernel/locking/spinlock.c:282",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_name",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_number",
        "drivers/net/ppp/ppp_generic.c:ppp_input_error",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "net/core/sock.c:sock_i_uid",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_complete_tx_timestamp",
        "net/core/neighbour.c:neigh_seq_stop",
        "net/core/neighbour.c:neigh_for_each",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_req_get",
        "net/ipv6/anycast.c:ac6_seq_stop",
        "net/ipv6/anycast.c:ac6_seq_start",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr",
        "net/ipv6/addrconf.c:addrconf_disable_policy_idev",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_dad_run",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:ipv6_inherit_eui64",
        "net/ipv6/addrconf.c:ipv6_get_lladdr",
        "net/ipv6/addrconf.c:dev_forward_change",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597967680,
      "name": "_raw_read_unlock_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t * lock)
```

```json
{
  "name": "_raw_read_unlock_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236557688,
      "name": "_raw_read_unlock_bh",
      "external": true,
      "loc": "kernel/locking/spinlock.c:277",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_name",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_number",
        "drivers/net/ppp/ppp_generic.c:ppp_input_error",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "net/core/sock.c:sock_i_ino",
        "net/core/sock.c:sock_i_uid",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/ping.c:ping_seq_stop",
        "net/ipv4/ping.c:ping_lookup",
        "net/ipv6/anycast.c:ac6_seq_stop",
        "net/ipv6/anycast.c:ac6_seq_start",
        "net/ipv6/anycast.c:ac6_get_next",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr",
        "net/ipv6/addrconf.c:addrconf_disable_policy_idev",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_dad_run",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:ipv6_get_lladdr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/mcast.c:igmp6_mcf_seq_stop",
        "net/ipv6/mcast.c:igmp6_mcf_seq_next",
        "net/ipv6/mcast.c:igmp6_mcf_seq_start",
        "net/ipv6/mcast.c:igmp6_mcf_get_next",
        "net/ipv6/mcast.c:igmp6_mc_seq_stop",
        "net/ipv6/mcast.c:igmp6_mc_seq_start",
        "net/ipv6/mcast.c:igmp6_mc_get_next",
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_unmap",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236557688,
      "name": "_raw_read_unlock_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void _raw_read_unlock_bh(rwlock_t * lock)
```

```json
{
  "name": "_raw_read_unlock_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297802768,
      "name": "_raw_read_unlock_bh",
      "external": true,
      "loc": "kernel/locking/spinlock.c:277",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_name",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_number",
        "drivers/net/ppp/ppp_generic.c:ppp_input_error",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "net/core/sock.c:sock_i_ino",
        "net/core/sock.c:sock_i_uid",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/ping.c:ping_seq_stop",
        "net/ipv4/ping.c:ping_lookup",
        "net/ipv4/ping.c:ping_lookup",
        "net/ipv6/anycast.c:ac6_seq_stop",
        "net/ipv6/anycast.c:ac6_seq_start",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr",
        "net/ipv6/addrconf.c:addrconf_disable_policy_idev",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_dad_run",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:ipv6_get_lladdr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/mcast.c:igmp6_mcf_seq_stop",
        "net/ipv6/mcast.c:igmp6_mcf_seq_next",
        "net/ipv6/mcast.c:igmp6_mcf_seq_start",
        "net/ipv6/mcast.c:igmp6_mc_seq_stop",
        "net/ipv6/mcast.c:igmp6_mc_seq_start",
        "net/ipv6/mcast.c:igmp6_mc_get_next",
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_unmap",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297802768,
      "name": "_raw_read_unlock_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void _raw_read_unlock_bh(rwlock_t * lock)
```

```json
{
  "name": "_raw_read_unlock_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279811784,
      "name": "_raw_read_unlock_bh",
      "external": true,
      "loc": "kernel/locking/spinlock.c:277",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_name",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_number",
        "drivers/net/ppp/ppp_generic.c:ppp_input_error",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "net/core/sock.c:sock_i_ino",
        "net/core/sock.c:sock_i_uid",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/ping.c:ping_seq_stop",
        "net/ipv4/ping.c:ping_lookup",
        "net/ipv6/anycast.c:ac6_seq_stop",
        "net/ipv6/anycast.c:ac6_seq_start",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr",
        "net/ipv6/addrconf.c:addrconf_disable_policy_idev",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_dad_run",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:ipv6_get_lladdr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/mcast.c:igmp6_mcf_seq_stop",
        "net/ipv6/mcast.c:igmp6_mcf_seq_next",
        "net/ipv6/mcast.c:igmp6_mcf_seq_start",
        "net/ipv6/mcast.c:igmp6_mc_seq_stop",
        "net/ipv6/mcast.c:igmp6_mc_seq_start",
        "net/ipv6/mcast.c:igmp6_mc_get_next",
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_unmap",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279811784,
      "name": "_raw_read_unlock_bh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void _raw_read_unlock_bh(rwlock_t * lock)
```

```json
{
  "name": "_raw_read_unlock_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589804592,
      "name": "_raw_read_unlock_bh",
      "external": true,
      "loc": "kernel/locking/spinlock.c:277",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_name",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_number",
        "drivers/net/ppp/ppp_generic.c:ppp_input_error",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "net/core/sock.c:sock_i_ino",
        "net/core/sock.c:sock_i_uid",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/ping.c:ping_seq_stop",
        "net/ipv4/ping.c:ping_lookup",
        "net/ipv6/anycast.c:ac6_seq_stop",
        "net/ipv6/anycast.c:ac6_seq_start",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr",
        "net/ipv6/addrconf.c:addrconf_disable_policy_idev",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_dad_run",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:ipv6_get_lladdr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/mcast.c:igmp6_mcf_seq_stop",
        "net/ipv6/mcast.c:igmp6_mcf_seq_next",
        "net/ipv6/mcast.c:igmp6_mcf_seq_start",
        "net/ipv6/mcast.c:igmp6_mc_seq_stop",
        "net/ipv6/mcast.c:igmp6_mc_seq_start",
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_unmap",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589804592,
      "name": "_raw_read_unlock_bh",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t * lock)
```

```json
{
  "name": "_raw_read_unlock_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589526928,
      "name": "_raw_read_unlock_bh",
      "external": true,
      "loc": "kernel/locking/spinlock.c:277",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_name",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_number",
        "drivers/net/ppp/ppp_generic.c:ppp_input_error",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "net/core/sock.c:sock_i_ino",
        "net/core/sock.c:sock_i_uid",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/ping.c:ping_seq_stop",
        "net/ipv4/ping.c:ping_lookup",
        "net/ipv6/anycast.c:ac6_seq_stop",
        "net/ipv6/anycast.c:ac6_seq_start",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr",
        "net/ipv6/addrconf.c:addrconf_disable_policy_idev",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_dad_run",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:ipv6_get_lladdr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/mcast.c:igmp6_mcf_seq_stop",
        "net/ipv6/mcast.c:igmp6_mcf_seq_next",
        "net/ipv6/mcast.c:igmp6_mcf_seq_start",
        "net/ipv6/mcast.c:igmp6_mc_seq_stop",
        "net/ipv6/mcast.c:igmp6_mc_seq_start",
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_unmap",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589526928,
      "name": "_raw_read_unlock_bh",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t * lock)
```

```json
{
  "name": "_raw_read_unlock_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590248000,
      "name": "_raw_read_unlock_bh",
      "external": true,
      "loc": "kernel/locking/spinlock.c:277",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_name",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_number",
        "drivers/net/ppp/ppp_generic.c:ppp_input_error",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "net/core/sock.c:sock_i_ino",
        "net/core/sock.c:sock_i_uid",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/netfilter/nfnetlink_log.c:__build_packet_message",
        "net/netfilter/nfnetlink_log.c:__build_packet_message",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/ping.c:ping_seq_stop",
        "net/ipv4/ping.c:ping_lookup",
        "net/ipv6/anycast.c:ac6_seq_stop",
        "net/ipv6/anycast.c:ac6_seq_start",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr",
        "net/ipv6/addrconf.c:addrconf_disable_policy_idev",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_dad_run",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:ipv6_get_lladdr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/mcast.c:igmp6_mcf_seq_stop",
        "net/ipv6/mcast.c:igmp6_mcf_seq_next",
        "net/ipv6/mcast.c:igmp6_mcf_seq_start",
        "net/ipv6/mcast.c:igmp6_mc_seq_stop",
        "net/ipv6/mcast.c:igmp6_mc_seq_start",
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_unmap",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590248000,
      "name": "_raw_read_unlock_bh",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void _raw_read_unlock_bh(rwlock_t * lock)
```

```json
{
  "name": "_raw_read_unlock_bh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590299440,
      "name": "_raw_read_unlock_bh",
      "external": true,
      "loc": "kernel/locking/spinlock.c:277",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_name",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_number",
        "drivers/net/ppp/ppp_generic.c:ppp_input_error",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "net/core/sock.c:sock_i_ino",
        "net/core/sock.c:sock_i_uid",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/ping.c:ping_seq_stop",
        "net/ipv4/ping.c:ping_lookup",
        "net/ipv6/anycast.c:ac6_seq_stop",
        "net/ipv6/anycast.c:ac6_seq_start",
        "net/ipv6/anycast.c:ipv6_chk_acast_addr",
        "net/ipv6/addrconf.c:addrconf_disable_policy_idev",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:addrconf_dad_run",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:ipv6_get_lladdr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/mcast.c:igmp6_mcf_seq_stop",
        "net/ipv6/mcast.c:igmp6_mcf_seq_next",
        "net/ipv6/mcast.c:igmp6_mcf_seq_start",
        "net/ipv6/mcast.c:igmp6_mc_seq_stop",
        "net/ipv6/mcast.c:igmp6_mc_seq_start",
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_unmap",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_source",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590299440,
      "name": "_raw_read_unlock_bh",
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void _raw_read_unlock_bh(rwlock_t * lock)
```
</details>
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
