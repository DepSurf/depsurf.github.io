# Function: <code>skb_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned char * skb_put(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586208160,
      "name": "skb_put",
      "external": true,
      "loc": "net/core/skbuff.c:1425",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_vformat",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_n_string",
        "ipc/mqueue.c:SyS_mq_notify",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/nlattr.c:__nla_reserve",
        "lib/nlattr.c:__nla_reserve_nohdr",
        "lib/nlattr.c:nla_append",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/virtio_net.c:page_to_skb",
        "drivers/net/virtio_net.c:page_to_skb",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/ppp/ppp_generic.c:ppp_push",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skbuff.c:pskb_put",
        "net/core/skbuff.c:skb_copy",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netlink/af_netlink.c:__nlmsg_put",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/arp.c:arp_create",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ndisc.c:ndisc_fill_addr_option",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/packet/af_packet.c:packet_sendmsg",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586208160,
      "name": "skb_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
unsigned char * skb_put(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586629232,
      "name": "skb_put",
      "external": true,
      "loc": "net/core/skbuff.c:1430",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "ipc/mqueue.c:SyS_mq_notify",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/nlattr.c:nla_append",
        "lib/nlattr.c:__nla_reserve_nohdr",
        "lib/nlattr.c:__nla_reserve",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_push",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_put",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netlink/af_netlink.c:__nlmsg_put",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/arp.c:arp_create",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:__ndisc_fill_addr_option",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_sendmsg",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586629232,
      "name": "skb_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
unsigned char * skb_put(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586814016,
      "name": "skb_put",
      "external": true,
      "loc": "net/core/skbuff.c:1430",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "ipc/mqueue.c:SyS_mq_notify",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/nlattr.c:nla_append",
        "lib/nlattr.c:__nla_reserve_nohdr",
        "lib/nlattr.c:__nla_reserve",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_put",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netlink/af_netlink.c:__nlmsg_put",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/arp.c:arp_create",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:__ndisc_fill_addr_option",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_sendmsg",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586814016,
      "name": "skb_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * skb_put(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586940960,
      "name": "skb_put",
      "external": true,
      "loc": "net/core/skbuff.c:1443",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "ipc/mqueue.c:do_mq_notify",
        "lib/nlattr.c:nla_append",
        "lib/nlattr.c:__nla_put_nohdr",
        "lib/nlattr.c:nla_reserve_nohdr",
        "lib/nlattr.c:__nla_reserve",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_put",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netlink/af_netlink.c:__nlmsg_put",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/arp.c:arp_create",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:__ndisc_fill_addr_option",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_sendmsg",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586940960,
      "name": "skb_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * skb_put(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587434976,
      "name": "skb_put",
      "external": true,
      "loc": "net/core/skbuff.c:1688",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "ipc/mqueue.c:do_mq_notify",
        "lib/nlattr.c:nla_append",
        "lib/nlattr.c:__nla_put_nohdr",
        "lib/nlattr.c:nla_reserve_nohdr",
        "lib/nlattr.c:__nla_reserve",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_put",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netlink/af_netlink.c:__nlmsg_put",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/arp.c:arp_create",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:__ndisc_fill_addr_option",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_sendmsg",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587434976,
      "name": "skb_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * skb_put(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_put",
      "external": true,
      "loc": "net/core/skbuff.c:1690",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "ipc/mqueue.c:do_mq_notify",
        "lib/nlattr.c:nla_append",
        "lib/nlattr.c:__nla_put_nohdr",
        "lib/nlattr.c:nla_reserve_nohdr",
        "lib/nlattr.c:__nla_reserve",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_put",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netlink/af_netlink.c:__nlmsg_put",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/arp.c:arp_create",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:__ndisc_fill_addr_option",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_sendmsg",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default",
        "net/xdp/xsk.c:xsk_sendmsg",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587771540,
      "name": "skb_put.cold.86",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071587739280,
      "name": "skb_put",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * skb_put(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587874057,
      "name": "skb_put",
      "external": true,
      "loc": "net/core/skbuff.c:1700",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "ipc/mqueue.c:do_mq_notify",
        "lib/nlattr.c:nla_append",
        "lib/nlattr.c:__nla_put_nohdr",
        "lib/nlattr.c:nla_reserve_nohdr",
        "lib/nlattr.c:__nla_reserve",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_put",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netlink/af_netlink.c:__nlmsg_put",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/raw.c:raw_sendmsg",
        "net/ipv4/arp.c:arp_create",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:__ndisc_fill_addr_option",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_sendmsg",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default",
        "net/xdp/xsk.c:xsk_sendmsg",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587905253,
      "name": "skb_put.cold.87",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071587874000,
      "name": "skb_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * skb_put(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588179341,
      "name": "skb_put",
      "external": true,
      "loc": "net/core/skbuff.c:1859",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "ipc/mqueue.c:do_mq_notify",
        "lib/nlattr.c:nla_append",
        "lib/nlattr.c:__nla_put_nohdr",
        "lib/nlattr.c:nla_reserve_nohdr",
        "lib/nlattr.c:__nla_reserve",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_put",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/netlink/af_netlink.c:__nlmsg_put",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/arp.c:arp_create",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:__ndisc_fill_addr_option",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default",
        "net/xdp/xsk.c:xsk_sendmsg",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588211978,
      "name": "skb_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071588179280,
      "name": "skb_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * skb_put(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588385133,
      "name": "skb_put",
      "external": true,
      "loc": "net/core/skbuff.c:1859",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "ipc/mqueue.c:do_mq_notify",
        "lib/nlattr.c:nla_append",
        "lib/nlattr.c:__nla_put_nohdr",
        "lib/nlattr.c:nla_reserve_nohdr",
        "lib/nlattr.c:__nla_reserve",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_put",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/netlink/af_netlink.c:__nlmsg_put",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/arp.c:arp_create",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:__ndisc_fill_addr_option",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default",
        "net/xdp/xsk.c:__xsk_sendmsg",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588416742,
      "name": "skb_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071588385072,
      "name": "skb_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * skb_put(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589250952,
      "name": "skb_put",
      "external": true,
      "loc": "net/core/skbuff.c:1858",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_put",
        "net/core/skbuff.c:pskb_put"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "ipc/mqueue.c:do_mq_notify",
        "lib/nlattr.c:nla_append",
        "lib/nlattr.c:__nla_put_nohdr",
        "lib/nlattr.c:nla_reserve_nohdr",
        "lib/nlattr.c:__nla_reserve",
        "lib/kobject_uevent.c:uevent_net_broadcast",
        "lib/kobject_uevent.c:alloc_uevent_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:__tun_build_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_explode",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/route.c:inet_rtm_getroute_build_skb",
        "net/ipv4/route.c:inet_rtm_getroute_build_skb",
        "net/ipv4/route.c:inet_rtm_getroute_build_skb",
        "net/ipv4/route.c:inet_rtm_getroute_build_skb",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/arp.c:arp_create",
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grhead",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:__ndisc_fill_addr_option",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grhead",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default",
        "net/xdp/xsk.c:xsk_generic_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589284383,
      "name": "skb_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071589242048,
      "name": "skb_put",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * skb_put(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589250120,
      "name": "skb_put",
      "external": true,
      "loc": "net/core/skbuff.c:1869",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_put",
        "net/core/skbuff.c:pskb_put"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "ipc/mqueue.c:do_mq_notify",
        "lib/nlattr.c:nla_append",
        "lib/nlattr.c:__nla_put_nohdr",
        "lib/nlattr.c:nla_reserve_nohdr",
        "lib/nlattr.c:__nla_reserve",
        "lib/kobject_uevent.c:uevent_net_broadcast",
        "lib/kobject_uevent.c:alloc_uevent_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:__tun_build_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_explode",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/netlink/af_netlink.c:netlink_dump_done",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/route.c:inet_rtm_getroute_build_skb",
        "net/ipv4/route.c:inet_rtm_getroute_build_skb",
        "net/ipv4/route.c:inet_rtm_getroute_build_skb",
        "net/ipv4/route.c:inet_rtm_getroute_build_skb",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/arp.c:arp_create",
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grhead",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:__ndisc_fill_addr_option",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grhead",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default",
        "net/xdp/xsk.c:xsk_generic_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591627160,
      "name": "skb_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071589241328,
      "name": "skb_put",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * skb_put(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589144901,
      "name": "skb_put",
      "external": true,
      "loc": "net/core/skbuff.c:1911",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_put",
        "net/core/skbuff.c:pskb_put"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "ipc/mqueue.c:do_mq_notify",
        "lib/nlattr.c:nla_append",
        "lib/nlattr.c:__nla_put_nohdr",
        "lib/nlattr.c:nla_reserve_nohdr",
        "lib/nlattr.c:__nla_reserve",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:__tun_build_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_explode",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_write",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/netlink/af_netlink.c:netlink_dump_done",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/ipv4/route.c:inet_rtm_getroute_build_skb",
        "net/ipv4/route.c:inet_rtm_getroute_build_skb",
        "net/ipv4/route.c:inet_rtm_getroute_build_skb",
        "net/ipv4/route.c:inet_rtm_getroute_build_skb",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/arp.c:arp_create",
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grhead",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:__ndisc_fill_addr_option",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grhead",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp",
        "net/xdp/xsk.c:xsk_generic_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591570555,
      "name": "skb_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589136304,
      "name": "skb_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * skb_put(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589867366,
      "name": "skb_put",
      "external": true,
      "loc": "net/core/skbuff.c:1983",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_put",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "ipc/mqueue.c:do_mq_notify",
        "lib/nlattr.c:nla_append",
        "lib/nlattr.c:__nla_put_nohdr",
        "lib/nlattr.c:nla_reserve_nohdr",
        "lib/nlattr.c:__nla_reserve",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:__tun_build_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_explode",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_write",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/netlink/af_netlink.c:netlink_dump_done",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/ipv4/route.c:inet_rtm_getroute_build_skb",
        "net/ipv4/route.c:inet_rtm_getroute_build_skb",
        "net/ipv4/route.c:inet_rtm_getroute_build_skb",
        "net/ipv4/route.c:inet_rtm_getroute_build_skb",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/arp.c:arp_create",
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grhead",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:__ndisc_fill_addr_option",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grhead",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp",
        "net/xdp/xsk.c:xsk_generic_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592693971,
      "name": "skb_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589853952,
      "name": "skb_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * skb_put(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591393828,
      "name": "skb_put",
      "external": true,
      "loc": "net/core/skbuff.c:2008",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_put",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "ipc/mqueue.c:do_mq_notify",
        "lib/nlattr.c:nla_append",
        "lib/nlattr.c:__nla_put_nohdr",
        "lib/nlattr.c:nla_reserve_nohdr",
        "lib/nlattr.c:__nla_reserve",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:__tun_build_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_explode",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_write",
        "drivers/net/xen-netfront.c:bounce_skb",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/netlink/af_netlink.c:netlink_dump_done",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/arp.c:arp_create",
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grhead",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_ns_create",
        "net/ipv6/ndisc.c:ndisc_ns_create",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:__ndisc_fill_addr_option",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grhead",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default",
        "net/xdp/xsk.c:xsk_generic_xmit",
        "net/mctp/af_mctp.c:mctp_sendmsg",
        "net/mctp/af_mctp.c:mctp_sendmsg",
        "net/mctp/route.c:mctp_do_fragment_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594578332,
      "name": "skb_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071591378912,
      "name": "skb_put",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * skb_put(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593158532,
      "name": "skb_put",
      "external": true,
      "loc": "net/core/skbuff.c:2211",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_put",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "ipc/mqueue.c:do_mq_notify",
        "lib/nlattr.c:nla_append",
        "lib/nlattr.c:__nla_put_nohdr",
        "lib/nlattr.c:nla_reserve_nohdr",
        "lib/nlattr.c:__nla_reserve",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:__tun_build_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_explode",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_write",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_dump_done",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/arp.c:arp_create",
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grhead",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:queue_oob",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_ns_create",
        "net/ipv6/ndisc.c:ndisc_ns_create",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:__ndisc_fill_addr_option",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grhead",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default",
        "net/xdp/xsk.c:__xsk_generic_xmit",
        "net/mctp/af_mctp.c:mctp_sendmsg",
        "net/mctp/af_mctp.c:mctp_sendmsg",
        "net/mctp/route.c:mctp_do_fragment_route",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593139648,
      "name": "skb_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * skb_put(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593614201,
      "name": "skb_put",
      "external": true,
      "loc": "net/core/skbuff.c:2375",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_put",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "ipc/mqueue.c:do_mq_notify",
        "lib/nlattr.c:nla_append",
        "lib/nlattr.c:__nla_put_nohdr",
        "lib/nlattr.c:nla_reserve_nohdr",
        "lib/nlattr.c:__nla_reserve",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:__tun_build_skb",
        "drivers/net/virtio_net.c:receive_small",
        "drivers/net/virtio_net.c:receive_small_xdp",
        "drivers/net/virtio_net.c:page_to_skb",
        "drivers/net/virtio_net.c:page_to_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_explode",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_write",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_dump_done",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/arp.c:arp_create",
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grhead",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:queue_oob",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_ns_create",
        "net/ipv6/ndisc.c:ndisc_ns_create",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:__ndisc_fill_addr_option",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grhead",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default",
        "net/xdp/xsk.c:__xsk_generic_xmit",
        "net/mctp/af_mctp.c:mctp_sendmsg",
        "net/mctp/af_mctp.c:mctp_sendmsg",
        "net/mctp/route.c:mctp_do_fragment_route",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593592336,
      "name": "skb_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * skb_put(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594389302,
      "name": "skb_put",
      "external": true,
      "loc": "net/core/skbuff.c:2463",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_put",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "ipc/mqueue.c:do_mq_notify",
        "lib/nlattr.c:nla_append",
        "lib/nlattr.c:__nla_put_nohdr",
        "lib/nlattr.c:nla_reserve_nohdr",
        "lib/nlattr.c:__nla_reserve",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:__tun_build_skb",
        "drivers/net/virtio_net.c:receive_small",
        "drivers/net/virtio_net.c:receive_small_xdp",
        "drivers/net/virtio_net.c:page_to_skb",
        "drivers/net/virtio_net.c:page_to_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_explode",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/core/selftests.c:net_test_get_skb",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_dump_done",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/arp.c:arp_create",
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grhead",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:queue_oob",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_ns_create",
        "net/ipv6/ndisc.c:ndisc_ns_create",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:__ndisc_fill_addr_option",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grhead",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default",
        "net/xdp/xsk.c:xsk_build_skb",
        "net/mctp/af_mctp.c:mctp_sendmsg",
        "net/mctp/af_mctp.c:mctp_sendmsg",
        "net/mctp/route.c:mctp_do_fragment_route",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594365232,
      "name": "skb_put",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void * skb_put(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501895528,
      "name": "skb_put",
      "external": true,
      "loc": "net/core/skbuff.c:1859",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "ipc/mqueue.c:do_mq_notify",
        "lib/nlattr.c:nla_append",
        "lib/nlattr.c:__nla_put_nohdr",
        "lib/nlattr.c:nla_reserve_nohdr",
        "lib/nlattr.c:__nla_reserve",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_put",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/netlink/af_netlink.c:__nlmsg_put",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/arp.c:arp_create",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:__ndisc_fill_addr_option",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default",
        "net/xdp/xsk.c:__xsk_sendmsg",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501895528,
      "name": "skb_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void * skb_put(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234658652,
      "name": "skb_put",
      "external": true,
      "loc": "net/core/skbuff.c:1859",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "ipc/mqueue.c:do_mq_notify",
        "lib/nlattr.c:nla_append",
        "lib/nlattr.c:__nla_put_nohdr",
        "lib/nlattr.c:nla_reserve_nohdr",
        "lib/nlattr.c:__nla_reserve",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:__tun_build_skb",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_explode",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_put",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/netlink/af_netlink.c:__nlmsg_put",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/arp.c:arp_create",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grhead",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_output.c:__ip6_append_data",
        "net/ipv6/ip6_output.c:__ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:__ndisc_fill_addr_option",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grhead",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default",
        "net/xdp/xsk.c:__xsk_sendmsg",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234658652,
      "name": "skb_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void * skb_put(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295303168,
      "name": "skb_put",
      "external": true,
      "loc": "net/core/skbuff.c:1859",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "ipc/mqueue.c:do_mq_notify",
        "lib/nlattr.c:nla_append",
        "lib/nlattr.c:__nla_put_nohdr",
        "lib/nlattr.c:nla_reserve_nohdr",
        "lib/nlattr.c:__nla_reserve",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_put",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/netlink/af_netlink.c:__nlmsg_put",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/arp.c:arp_create",
        "net/ipv4/arp.c:arp_create",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grhead",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:__ndisc_fill_addr_option",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grhead",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default",
        "net/xdp/xsk.c:__xsk_sendmsg",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295303168,
      "name": "skb_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void * skb_put(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278214844,
      "name": "skb_put",
      "external": true,
      "loc": "net/core/skbuff.c:1859",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "ipc/mqueue.c:__se_sys_mq_notify",
        "lib/nlattr.c:nla_append",
        "lib/nlattr.c:__nla_reserve_nohdr",
        "lib/nlattr.c:__nla_reserve",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_put",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/netlink/af_netlink.c:__nlmsg_put",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/arp.c:arp_create",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grhead",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:__ndisc_fill_addr_option",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grhead",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default",
        "net/xdp/xsk.c:__xsk_sendmsg",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278214844,
      "name": "skb_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * skb_put(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587991917,
      "name": "skb_put",
      "external": true,
      "loc": "net/core/skbuff.c:1859",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "ipc/mqueue.c:do_mq_notify",
        "lib/nlattr.c:nla_append",
        "lib/nlattr.c:__nla_put_nohdr",
        "lib/nlattr.c:nla_reserve_nohdr",
        "lib/nlattr.c:__nla_reserve",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_put",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/netlink/af_netlink.c:__nlmsg_put",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/arp.c:arp_create",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:__ndisc_fill_addr_option",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default",
        "net/xdp/xsk.c:__xsk_sendmsg",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588023526,
      "name": "skb_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071587991856,
      "name": "skb_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * skb_put(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587705021,
      "name": "skb_put",
      "external": true,
      "loc": "net/core/skbuff.c:1859",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "ipc/mqueue.c:do_mq_notify",
        "lib/nlattr.c:nla_append",
        "lib/nlattr.c:__nla_put_nohdr",
        "lib/nlattr.c:nla_reserve_nohdr",
        "lib/nlattr.c:__nla_reserve",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/vxlan.c:neigh_reduce",
        "drivers/net/vxlan.c:neigh_reduce",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_put",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/netlink/af_netlink.c:__nlmsg_put",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/arp.c:arp_create",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:__ndisc_fill_addr_option",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default",
        "net/xdp/xsk.c:__xsk_sendmsg",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587736614,
      "name": "skb_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071587704960,
      "name": "skb_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * skb_put(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588323693,
      "name": "skb_put",
      "external": true,
      "loc": "net/core/skbuff.c:1859",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "ipc/mqueue.c:do_mq_notify",
        "lib/nlattr.c:nla_append",
        "lib/nlattr.c:__nla_put_nohdr",
        "lib/nlattr.c:nla_reserve_nohdr",
        "lib/nlattr.c:__nla_reserve",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_put",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/netlink/af_netlink.c:__nlmsg_put",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict",
        "net/netfilter/nfnetlink_log.c:__build_packet_message",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/arp.c:arp_create",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:__ndisc_fill_addr_option",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default",
        "net/xdp/xsk.c:__xsk_sendmsg",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588355302,
      "name": "skb_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071588323632,
      "name": "skb_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * skb_put(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588459117,
      "name": "skb_put",
      "external": true,
      "loc": "net/core/skbuff.c:1859",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_n_string",
        "kernel/audit.c:audit_log_n_hex",
        "kernel/audit.c:audit_log_vformat",
        "ipc/mqueue.c:do_mq_notify",
        "lib/nlattr.c:nla_append",
        "lib/nlattr.c:__nla_put_nohdr",
        "lib/nlattr.c:nla_reserve_nohdr",
        "lib/nlattr.c:__nla_reserve",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_put",
        "net/core/skbuff.c:skb_copy_expand",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/netlink/af_netlink.c:__nlmsg_put",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:ip_frag_next",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/arp.c:arp_create",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:igmp_send_report",
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/igmp.c:igmpv3_newpack",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_output.c:ip6_frag_next",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_rs",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/ndisc.c:__ndisc_fill_addr_option",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/mcast.c:mld_newpack",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp",
        "net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb",
        "lib/kobject_uevent.c:alloc_uevent_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588490822,
      "name": "skb_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071588459056,
      "name": "skb_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
<b>Return type changed. </b>
<code>unsigned char *</code> ➡️ <code>void *</code>
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
