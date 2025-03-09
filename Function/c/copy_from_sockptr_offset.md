# Function: <code>copy_from_sockptr_offset</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_from_sockptr_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589235447,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_set_timeout",
        "net/core/sock.c:sock_set_timeout",
        "net/core/sock.c:sock_set_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589523602,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:copy_bpf_fprog_from_user",
        "net/core/filter.c:copy_bpf_fprog_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589865133,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590007180,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590027726,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:compat_ip_mcast_join_leave",
        "net/ipv4/ip_sockglue.c:ip_mcast_join_leave",
        "net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter",
        "net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr",
        "net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590067673,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_repair_options_est"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590185935,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590237095,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_seticmpfilter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590248245,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590457312,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590535826,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_user_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590772279,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_mcast_join_leave",
        "net/ipv6/ipv6_sockglue.c:ipv6_mcast_join_leave",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_set_mcast_msfilter",
        "net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr",
        "net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590816394,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_setsockopt",
        "net/ipv6/raw.c:rawv6_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590861020,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590903060,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590927954,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591016848,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:fanout_set_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591131800,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt"
      ],
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
  "name": "copy_from_sockptr_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589129252,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_set_timeout",
        "net/core/sock.c:sock_set_timeout",
        "net/core/sock.c:sock_set_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589418738,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:copy_bpf_fprog_from_user",
        "net/core/filter.c:copy_bpf_fprog_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589771149,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589921404,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589942158,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:compat_ip_mcast_join_leave",
        "net/ipv4/ip_sockglue.c:ip_mcast_join_leave",
        "net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter",
        "net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr",
        "net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589982025,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_repair_options_est"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590099919,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590146242,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590161397,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590383152,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590460978,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_user_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590699291,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_mcast_join_leave",
        "net/ipv6/ipv6_sockglue.c:ipv6_mcast_join_leave",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_set_mcast_msfilter",
        "net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr",
        "net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590742682,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_setsockopt",
        "net/ipv6/raw.c:rawv6_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590789900,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590832168,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590857477,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590944328,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591062552,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591150789,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int"
      ],
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
  "name": "copy_from_sockptr_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581153084,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_update_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581187215,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64",
        "kernel/bpf/verifier.c:check_btf_line"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581278496,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_iter.c:bpf_iter_link_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581369995,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "kernel/bpf/btf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589847750,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_set_timeout",
        "net/core/sock.c:sock_set_timeout",
        "net/core/sock.c:sock_set_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590146370,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:copy_bpf_fprog_from_user",
        "net/core/filter.c:copy_bpf_fprog_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590530493,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590687980,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590709006,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:compat_ip_mcast_join_leave",
        "net/ipv4/ip_sockglue.c:ip_mcast_join_leave",
        "net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter",
        "net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr",
        "net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590774925,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590874529,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590926562,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590941045,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591176944,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591264050,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_user_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591515220,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_mcast_join_leave",
        "net/ipv6/ipv6_sockglue.c:ipv6_mcast_join_leave",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_set_mcast_msfilter",
        "net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr",
        "net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591558472,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_setsockopt",
        "net/ipv6/raw.c:rawv6_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591607294,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591651464,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591687173,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591780184,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591905160,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592002634,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int"
      ],
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
  "name": "copy_from_sockptr_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591370288,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_copy_user_timeval",
        "net/core/sock.c:sock_copy_user_timeval",
        "net/core/sock.c:sock_copy_user_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591701300,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:copy_bpf_fprog_from_user",
        "net/core/filter.c:copy_bpf_fprog_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592137015,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592315375,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592340704,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:compat_ip_mcast_join_leave",
        "net/ipv4/ip_sockglue.c:ip_mcast_join_leave",
        "net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter",
        "net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr",
        "net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592380742,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_repair_options_est"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592513299,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592568426,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592589293,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592835166,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592930814,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_user_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593200720,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_mcast_join_leave",
        "net/ipv6/ipv6_sockglue.c:ipv6_mcast_join_leave",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_set_mcast_msfilter",
        "net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr",
        "net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593249630,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_setsockopt",
        "net/ipv6/raw.c:rawv6_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593300673,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593345933,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593384425,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593492459,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593625875,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593738883,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593753869,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/mctp/af_mctp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/af_mctp.c:mctp_setsockopt"
      ],
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
  "name": "copy_from_sockptr_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593131780,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sock_copy_user_timeval",
        "net/core/sock.c:sock_copy_user_timeval",
        "net/core/sock.c:sock_copy_user_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593500838,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:copy_bpf_fprog_from_user",
        "net/core/filter.c:copy_bpf_fprog_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593957463,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594152159,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594187632,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter",
        "net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:compat_ip_mcast_join_leave",
        "net/ipv4/ip_sockglue.c:ip_mcast_join_leave",
        "net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter",
        "net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr",
        "net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594263193,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:tcp_repair_options_est"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594369523,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594428933,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_seticmpfilter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594452562,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594713421,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mroute_getsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594813182,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_user_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595105339,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter",
        "net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_mcast_join_leave",
        "net/ipv6/ipv6_sockglue.c:ipv6_mcast_join_leave",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_set_mcast_msfilter",
        "net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr",
        "net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595152318,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_setsockopt",
        "net/ipv6/raw.c:rawv6_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595204705,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595252157,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595294845,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_getsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595411020,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:fanout_set_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595555699,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595676469,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595690845,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/mctp/af_mctp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/af_mctp.c:mctp_setsockopt"
      ],
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int copy_from_sockptr_offset(void * dst, sockptr_t src, size_t offset, size_t size)
```

```json
{
  "name": "copy_from_sockptr_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593584324,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sock_copy_user_timeval",
        "net/core/sock.c:sock_copy_user_timeval",
        "net/core/sock.c:sock_copy_user_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593972870,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:copy_bpf_fprog_from_user",
        "net/core/filter.c:copy_bpf_fprog_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594326128,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_setsockopt"
      ]
    },
    {
      "addr": 18446744071594539309,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594574579,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter",
        "net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:compat_ip_mcast_join_leave",
        "net/ipv4/ip_sockglue.c:ip_mcast_join_leave",
        "net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter",
        "net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr",
        "net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594650242,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:tcp_repair_options_est"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_getsockopt"
      ]
    },
    {
      "addr": 18446744071594756592,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys"
      ]
    },
    {
      "addr": 18446744071594818021,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_seticmpfilter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594833328,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_lib_setsockopt"
      ]
    },
    {
      "addr": 18446744071595105522,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mroute_getsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595204894,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_user_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595499341,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter",
        "net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_mcast_join_leave",
        "net/ipv6/ipv6_sockglue.c:ipv6_mcast_join_leave",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_set_mcast_msfilter",
        "net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr",
        "net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595548154,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_setsockopt",
        "net/ipv6/raw.c:rawv6_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595600384,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ]
    },
    {
      "addr": 18446744071595647517,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595689954,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_getsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595808207,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:fanout_set_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596064019,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596186906,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596200784,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/mctp/af_mctp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mctp/af_mctp.c:mctp_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594326128,
      "name": "copy_from_sockptr_offset.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071594614528,
      "name": "copy_from_sockptr_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071594756592,
      "name": "copy_from_sockptr_offset.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071594833328,
      "name": "copy_from_sockptr_offset.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071595600384,
      "name": "copy_from_sockptr_offset.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071596200784,
      "name": "copy_from_sockptr_offset.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int copy_from_sockptr_offset(void * dst, sockptr_t src, size_t offset, size_t size)
```

```json
{
  "name": "copy_from_sockptr_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582531642,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594301824,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:do_sock_getsockopt"
      ]
    },
    {
      "addr": 18446744071594357124,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sock_copy_user_timeval",
        "net/core/sock.c:sock_copy_user_timeval",
        "net/core/sock.c:sock_copy_user_timeval"
      ],
      "caller_func": [
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt"
      ]
    },
    {
      "addr": 18446744071594757766,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:copy_bpf_fprog_from_user",
        "net/core/filter.c:copy_bpf_fprog_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595125904,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_setsockopt"
      ]
    },
    {
      "addr": 18446744071595342010,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595378712,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter",
        "net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:compat_ip_mcast_join_leave",
        "net/ipv4/ip_sockglue.c:ip_mcast_join_leave",
        "net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter",
        "net/ipv4/ip_sockglue.c:ip_set_mcast_msfilter",
        "net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr",
        "net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr"
      ],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt"
      ]
    },
    {
      "addr": 18446744071595452061,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:tcp_repair_options_est"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_getsockopt"
      ]
    },
    {
      "addr": 18446744071595563264,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys"
      ]
    },
    {
      "addr": 18446744071595629317,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_seticmpfilter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595644128,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_lib_setsockopt"
      ]
    },
    {
      "addr": 18446744071595918194,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ip_mroute_getsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595967216,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv4/tcp_ao.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ao.c:tcp_ao_get_repair",
        "net/ipv4/tcp_ao.c:tcp_ao_get_sock_info",
        "net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user"
      ]
    },
    {
      "addr": 18446744071596045438,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_user_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596342903,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter",
        "net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_mcast_join_leave",
        "net/ipv6/ipv6_sockglue.c:ipv6_mcast_join_leave",
        "net/ipv6/ipv6_sockglue.c:compat_ipv6_set_mcast_msfilter",
        "net/ipv6/ipv6_sockglue.c:ipv6_set_mcast_msfilter",
        "net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr",
        "net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr"
      ],
      "caller_func": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt"
      ]
    },
    {
      "addr": 18446744071596390922,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_setsockopt",
        "net/ipv6/raw.c:rawv6_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596443264,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ]
    },
    {
      "addr": 18446744071596494973,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:fl_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596537714,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_getsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596658767,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:fanout_set_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596931299,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt",
        "net/xdp/xsk.c:xsk_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597062154,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597078544,
      "name": "copy_from_sockptr_offset",
      "external": false,
      "loc": "include/linux/sockptr.h:44",
      "file": "net/mctp/af_mctp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mctp/af_mctp.c:mctp_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594301824,
      "name": "copy_from_sockptr_offset.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071594328368,
      "name": "copy_from_sockptr_offset.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    },
    {
      "addr": 18446744071595125904,
      "name": "copy_from_sockptr_offset.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071595363584,
      "name": "copy_from_sockptr_offset.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071595417632,
      "name": "copy_from_sockptr_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071595563264,
      "name": "copy_from_sockptr_offset.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071595644128,
      "name": "copy_from_sockptr_offset.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071595967216,
      "name": "copy_from_sockptr_offset.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071596328976,
      "name": "copy_from_sockptr_offset.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071596443264,
      "name": "copy_from_sockptr_offset.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071597078544,
      "name": "copy_from_sockptr_offset.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int copy_from_sockptr_offset(void * dst, sockptr_t src, size_t offset, size_t size)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
