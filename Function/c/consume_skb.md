# Function: <code>consume_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void consume_skb(struct sk_buff * skb)
```

```json
{
  "name": "consume_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586210944,
      "name": "consume_skb",
      "external": true,
      "loc": "net/core/skbuff.c:747",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_skb",
        "kernel/audit.c:kauditd_thread",
        "ipc/mqueue.c:SyS_mq_notify",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/virtio_net.c:page_to_skb",
        "drivers/net/virtio_net.c:free_unused_bufs",
        "drivers/net/virtio_net.c:free_unused_bufs",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/datagram.c:__skb_recv_datagram",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/dev.c:__dev_kfree_skb_any",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586210944,
      "name": "consume_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void consume_skb(struct sk_buff * skb)
```

```json
{
  "name": "consume_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586637072,
      "name": "consume_skb",
      "external": true,
      "loc": "net/core/skbuff.c:748",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_send_skb",
        "ipc/mqueue.c:SyS_mq_notify",
        "drivers/net/virtio_net.c:remove_vq_common",
        "drivers/net/virtio_net.c:remove_vq_common",
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__dev_kfree_skb_any",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586637072,
      "name": "consume_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void consume_skb(struct sk_buff * skb)
```

```json
{
  "name": "consume_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586822608,
      "name": "consume_skb",
      "external": true,
      "loc": "net/core/skbuff.c:748",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_unicast_skb",
        "ipc/mqueue.c:SyS_mq_notify",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__dev_kfree_skb_any",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:skb_consume_udp",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586822608,
      "name": "consume_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void consume_skb(struct sk_buff * skb)
```

```json
{
  "name": "consume_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586961552,
      "name": "consume_skb",
      "external": true,
      "loc": "net/core/skbuff.c:742",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "ipc/mqueue.c:do_mq_notify",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__dev_kfree_skb_any",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586961552,
      "name": "consume_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void consume_skb(struct sk_buff * skb)
```

```json
{
  "name": "consume_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587445936,
      "name": "consume_skb",
      "external": true,
      "loc": "net/core/skbuff.c:695",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "ipc/mqueue.c:do_mq_notify",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__dev_kfree_skb_any",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587445936,
      "name": "consume_skb",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void consume_skb(struct sk_buff * skb)
```

```json
{
  "name": "consume_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587750208,
      "name": "consume_skb",
      "external": true,
      "loc": "net/core/skbuff.c:695",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/bpf/sockmap.c:bpf_tcp_recvmsg",
        "kernel/bpf/sockmap.c:free_sg",
        "ipc/mqueue.c:do_mq_notify",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__dev_kfree_skb_any",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_input.c:ip_local_deliver_finish",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_input_finish",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587750208,
      "name": "consume_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void consume_skb(struct sk_buff * skb)
```

```json
{
  "name": "consume_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587884288,
      "name": "consume_skb",
      "external": true,
      "loc": "net/core/skbuff.c:699",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "ipc/mqueue.c:do_mq_notify",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__dev_kfree_skb_any",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/skmsg.c:__sk_msg_free",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_forward.c:ip_forward_finish",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_finish_output",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587884288,
      "name": "consume_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void consume_skb(struct sk_buff * skb)
```

```json
{
  "name": "consume_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588189504,
      "name": "consume_skb",
      "external": true,
      "loc": "net/core/skbuff.c:832",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "ipc/mqueue.c:do_mq_notify",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__dev_kfree_skb_any",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/skmsg.c:__sk_msg_free",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward_finish",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588189504,
      "name": "consume_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void consume_skb(struct sk_buff * skb)
```

```json
{
  "name": "consume_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588394656,
      "name": "consume_skb",
      "external": true,
      "loc": "net/core/skbuff.c:832",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__dev_kfree_skb_any",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/skmsg.c:__sk_msg_free",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward_finish",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588394656,
      "name": "consume_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void consume_skb(struct sk_buff * skb)
```

```json
{
  "name": "consume_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589254464,
      "name": "consume_skb",
      "external": true,
      "loc": "net/core/skbuff.c:831",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "ipc/mqueue.c:do_mq_notify",
        "lib/kobject_uevent.c:uevent_net_broadcast_untagged",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:napi_reuse_skb",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__dev_kfree_skb_any",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:xdp_do_generic_redirect_map",
        "net/core/sock_reuseport.c:run_bpf_filter",
        "net/core/skmsg.c:__sk_msg_free",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_report",
        "net/core/drop_monitor.c:net_dm_packet_report",
        "net/core/drop_monitor.c:net_dm_packet_report",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward_finish",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_finish_output_gso",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589254464,
      "name": "consume_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void consume_skb(struct sk_buff * skb)
```

```json
{
  "name": "consume_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589253648,
      "name": "consume_skb",
      "external": true,
      "loc": "net/core/skbuff.c:842",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "ipc/mqueue.c:do_mq_notify",
        "lib/kobject_uevent.c:uevent_net_broadcast_untagged",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:napi_reuse_skb",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__dev_kfree_skb_any",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:xdp_do_generic_redirect_map",
        "net/core/sock_reuseport.c:run_bpf_filter",
        "net/core/skmsg.c:__sk_msg_free",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_report",
        "net/core/drop_monitor.c:net_dm_packet_report",
        "net/core/drop_monitor.c:net_dm_packet_report",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward_finish",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_finish_output_gso",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/xdp/xsk.c:xsk_generic_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589253648,
      "name": "consume_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void consume_skb(struct sk_buff * skb)
```

```json
{
  "name": "consume_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589156000,
      "name": "consume_skb",
      "external": true,
      "loc": "net/core/skbuff.c:890",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "ipc/mqueue.c:do_mq_notify",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_read",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:__msg_zerocopy_callback",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:napi_reuse_skb",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:validate_xmit_vlan",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/sock_reuseport.c:run_bpf_filter",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/core/selftests.c:net_test_loopback_validate",
        "net/core/skmsg.c:sk_msg_recvmsg",
        "net/core/skmsg.c:__sk_msg_free",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward_finish",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/xdp/xsk.c:xsk_generic_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589156000,
      "name": "consume_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void consume_skb(struct sk_buff * skb)
```

```json
{
  "name": "consume_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589876016,
      "name": "consume_skb",
      "external": true,
      "loc": "net/core/skbuff.c:906",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/bpf/devmap.c:dev_map_redirect_multi",
        "kernel/bpf/devmap.c:dev_map_redirect_multi",
        "kernel/bpf/devmap.c:dev_map_redirect_multi",
        "ipc/mqueue.c:do_mq_notify",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_read",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_expand_head",
        "net/core/skbuff.c:msg_zerocopy_callback",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:napi_reuse_skb",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:validate_xmit_vlan",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/sock_reuseport.c:run_bpf_filter",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/core/selftests.c:net_test_loopback_validate",
        "net/core/skmsg.c:sk_msg_recvmsg",
        "net/core/skmsg.c:__sk_msg_free",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward_finish",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/xdp/xsk.c:xsk_generic_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589876016,
      "name": "consume_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void consume_skb(struct sk_buff * skb)
```

```json
{
  "name": "consume_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591407952,
      "name": "consume_skb",
      "external": true,
      "loc": "net/core/skbuff.c:911",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/bpf/devmap.c:dev_map_redirect_multi",
        "kernel/bpf/devmap.c:dev_map_redirect_multi",
        "kernel/bpf/devmap.c:dev_map_redirect_multi",
        "ipc/mqueue.c:do_mq_notify",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_read",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_expand_head",
        "net/core/skbuff.c:__msg_zerocopy_callback",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__dev_kfree_skb_any",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/gro.c:napi_reuse_skb",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/core/selftests.c:net_test_loopback_validate",
        "net/core/skmsg.c:sk_msg_recvmsg",
        "net/core/skmsg.c:__sk_msg_free",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast",
        "net/netlink/af_netlink.c:netlink_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_fragment.c:ip_check_defrag",
        "net/ipv4/ip_forward.c:ip_forward_finish",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver",
        "net/ipv4/arp.c:arp_rcv",
        "net/ipv4/arp.c:arp_rcv",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_destructor",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/xdp/xsk.c:xsk_generic_xmit",
        "net/mctp/route.c:mctp_do_fragment_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591407952,
      "name": "consume_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
void consume_skb(struct sk_buff * skb)
```

```json
{
  "name": "consume_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593172560,
      "name": "consume_skb",
      "external": true,
      "loc": "net/core/skbuff.c:1092",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/bpf/devmap.c:dev_map_redirect_multi",
        "kernel/bpf/devmap.c:dev_map_redirect_multi",
        "kernel/bpf/devmap.c:dev_map_redirect_multi",
        "ipc/mqueue.c:do_mq_notify",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_read",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_expand_head",
        "net/core/skbuff.c:__msg_zerocopy_callback",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__dev_kfree_skb_any",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/gro.c:napi_reuse_skb",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/core/selftests.c:net_test_loopback_validate",
        "net/core/skmsg.c:sk_msg_recvmsg",
        "net/core/skmsg.c:__sk_msg_free",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast",
        "net/netlink/af_netlink.c:netlink_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_fragment.c:ip_check_defrag",
        "net/ipv4/ip_forward.c:ip_forward_finish",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp.c:tcp_read_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver",
        "net/ipv4/arp.c:arp_rcv",
        "net/ipv4/arp.c:arp_rcv",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:queue_oob",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_destructor",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/xdp/xsk.c:__xsk_generic_xmit",
        "net/mctp/route.c:mctp_do_fragment_route",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593172560,
      "name": "consume_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
void consume_skb(struct sk_buff * skb)
```

```json
{
  "name": "consume_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593626592,
      "name": "consume_skb",
      "external": true,
      "loc": "net/core/skbuff.c:1232",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/bpf/devmap.c:dev_map_redirect_multi",
        "kernel/bpf/devmap.c:dev_map_redirect_multi",
        "kernel/bpf/devmap.c:dev_map_redirect_multi",
        "ipc/mqueue.c:do_mq_notify",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/virtio_net.c:remove_vq_common",
        "drivers/net/virtio_net.c:receive_buf",
        "drivers/net/virtio_net.c:receive_mergeable",
        "drivers/net/virtio_net.c:page_to_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_read",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_expand_head",
        "net/core/skbuff.c:__msg_zerocopy_callback",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/gro.c:napi_reuse_skb",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/core/selftests.c:net_test_loopback_validate",
        "net/core/skmsg.c:sk_msg_recvmsg",
        "net/core/skmsg.c:__sk_msg_free",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast",
        "net/netlink/af_netlink.c:netlink_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_fragment.c:ip_check_defrag",
        "net/ipv4/ip_forward.c:ip_forward_finish",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver",
        "net/ipv4/arp.c:arp_rcv",
        "net/ipv4/arp.c:arp_rcv",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:queue_oob",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_destructor",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/xdp/xsk.c:__xsk_generic_xmit",
        "net/mctp/route.c:mctp_do_fragment_route",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593626592,
      "name": "consume_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void consume_skb(struct sk_buff * skb)
```

```json
{
  "name": "consume_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594401904,
      "name": "consume_skb",
      "external": true,
      "loc": "net/core/skbuff.c:1318",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/bpf/devmap.c:dev_map_redirect_multi",
        "kernel/bpf/devmap.c:dev_map_redirect_multi",
        "kernel/bpf/devmap.c:dev_map_redirect_multi",
        "ipc/mqueue.c:do_mq_notify",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/virtio_net.c:remove_vq_common",
        "drivers/net/virtio_net.c:receive_buf",
        "drivers/net/virtio_net.c:receive_mergeable",
        "drivers/net/virtio_net.c:page_to_skb",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:skb_segment_list",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_expand_head",
        "net/core/skbuff.c:__msg_zerocopy_callback",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/gro.c:napi_reuse_skb",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/core/drop_monitor.c:net_dm_hw_trap_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/core/selftests.c:net_test_loopback_validate",
        "net/core/skmsg.c:sk_msg_recvmsg",
        "net/core/skmsg.c:__sk_msg_free",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_fragment.c:ip_check_defrag",
        "net/ipv4/ip_forward.c:ip_forward_finish",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver",
        "net/ipv4/arp.c:arp_rcv",
        "net/ipv4/arp.c:arp_rcv",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_ndo_send",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:queue_oob",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_finish_output",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_destructor",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/ipv6/ip6_icmp.c:icmpv6_ndo_send",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/xdp/xsk.c:xsk_consume_skb",
        "net/mctp/route.c:mctp_do_fragment_route",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594401904,
      "name": "consume_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void consume_skb(struct sk_buff * skb)
```

```json
{
  "name": "consume_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501910424,
      "name": "consume_skb",
      "external": true,
      "loc": "net/core/skbuff.c:832",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_poll",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_cleanup",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_free_buffers",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_free_buffers",
        "drivers/net/ethernet/smsc/smc91x.c:smc_shutdown",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__dev_kfree_skb_any",
        "net/core/neighbour.c:neigh_probe",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/skmsg.c:__sk_msg_free",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward_finish",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501910424,
      "name": "consume_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void consume_skb(struct sk_buff * skb)
```

```json
{
  "name": "consume_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234671508,
      "name": "consume_skb",
      "external": true,
      "loc": "net/core/skbuff.c:832",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_free_buffers",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_free_buffers",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:napi_reuse_skb",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__dev_kfree_skb_any",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/skmsg.c:__sk_msg_free",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward_finish",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234671508,
      "name": "consume_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void consume_skb(struct sk_buff * skb)
```

```json
{
  "name": "consume_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295324096,
      "name": "consume_skb",
      "external": true,
      "loc": "net/core/skbuff.c:832",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__dev_kfree_skb_any",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/skmsg.c:__sk_msg_free",
        "net/core/drop_monitor.c:exit_net_drop_monitor",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward_finish",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295324096,
      "name": "consume_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void consume_skb(struct sk_buff * skb)
```

```json
{
  "name": "consume_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278223520,
      "name": "consume_skb",
      "external": true,
      "loc": "net/core/skbuff.c:832",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "ipc/mqueue.c:__se_sys_mq_notify",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__dev_kfree_skb_any",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/skmsg.c:__sk_msg_free",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward_finish",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278223520,
      "name": "consume_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void consume_skb(struct sk_buff * skb)
```

```json
{
  "name": "consume_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588001440,
      "name": "consume_skb",
      "external": true,
      "loc": "net/core/skbuff.c:832",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__dev_kfree_skb_any",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/skmsg.c:__sk_msg_free",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward_finish",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588001440,
      "name": "consume_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void consume_skb(struct sk_buff * skb)
```

```json
{
  "name": "consume_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587714528,
      "name": "consume_skb",
      "external": true,
      "loc": "net/core/skbuff.c:832",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/vxlan.c:vxlan_xmit",
        "drivers/net/vxlan.c:vxlan_xmit_one",
        "drivers/net/vxlan.c:neigh_reduce",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__dev_kfree_skb_any",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/skmsg.c:__sk_msg_free",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward_finish",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587714528,
      "name": "consume_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void consume_skb(struct sk_buff * skb)
```

```json
{
  "name": "consume_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588333216,
      "name": "consume_skb",
      "external": true,
      "loc": "net/core/skbuff.c:832",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__dev_kfree_skb_any",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/skmsg.c:__sk_msg_free",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward_finish",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588333216,
      "name": "consume_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void consume_skb(struct sk_buff * skb)
```

```json
{
  "name": "consume_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588468688,
      "name": "consume_skb",
      "external": true,
      "loc": "net/core/skbuff.c:832",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_notify",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/skbuff.c:skb_vlan_untag",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/datagram.c:__skb_try_recv_from_queue",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__dev_kfree_skb_any",
        "net/core/neighbour.c:neigh_probe",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/skmsg.c:__sk_msg_free",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_trim",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_forward.c:ip_forward_finish",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_sockglue.c:ip_recv_error",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/arp.c:arp_process",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/datagram.c:ipv6_recv_error",
        "net/ipv6/netfilter.c:br_ip6_fragment",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588468688,
      "name": "consume_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
