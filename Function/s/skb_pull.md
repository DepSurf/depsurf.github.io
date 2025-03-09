# Function: <code>skb_pull</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned char * skb_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586212464,
      "name": "skb_pull",
      "external": true,
      "loc": "net/core/skbuff.c:1466",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "net/802/fddi.c:fddi_type_trans",
        "net/802/fddi.c:fddi_type_trans",
        "net/netlink/af_netlink.c:netlink_rcv_skb",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586212464,
      "name": "skb_pull",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
unsigned char * skb_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586631040,
      "name": "skb_pull",
      "external": true,
      "loc": "net/core/skbuff.c:1471",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "net/802/fddi.c:fddi_type_trans",
        "net/802/fddi.c:fddi_type_trans",
        "net/netlink/af_netlink.c:netlink_rcv_skb",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586631040,
      "name": "skb_pull",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
unsigned char * skb_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586816512,
      "name": "skb_pull",
      "external": true,
      "loc": "net/core/skbuff.c:1471",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "net/802/fddi.c:fddi_type_trans",
        "net/802/fddi.c:fddi_type_trans",
        "net/netlink/af_netlink.c:netlink_rcv_skb",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586816512,
      "name": "skb_pull",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void * skb_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586945184,
      "name": "skb_pull",
      "external": true,
      "loc": "net/core/skbuff.c:1484",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "net/802/fddi.c:fddi_type_trans",
        "net/802/fddi.c:fddi_type_trans",
        "net/netlink/af_netlink.c:netlink_rcv_skb",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586945184,
      "name": "skb_pull",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void * skb_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587440592,
      "name": "skb_pull",
      "external": true,
      "loc": "net/core/skbuff.c:1729",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "net/802/fddi.c:fddi_type_trans",
        "net/802/fddi.c:fddi_type_trans",
        "net/netlink/af_netlink.c:netlink_rcv_skb",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587440592,
      "name": "skb_pull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void * skb_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587744432,
      "name": "skb_pull",
      "external": true,
      "loc": "net/core/skbuff.c:1731",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "net/802/fddi.c:fddi_type_trans",
        "net/802/fddi.c:fddi_type_trans",
        "net/netlink/af_netlink.c:netlink_rcv_skb",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587744432,
      "name": "skb_pull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void * skb_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587879200,
      "name": "skb_pull",
      "external": true,
      "loc": "net/core/skbuff.c:1741",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "net/802/fddi.c:fddi_type_trans",
        "net/802/fddi.c:fddi_type_trans",
        "net/netlink/af_netlink.c:netlink_rcv_skb",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587879200,
      "name": "skb_pull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void * skb_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588186368,
      "name": "skb_pull",
      "external": true,
      "loc": "net/core/skbuff.c:1900",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/802/fddi.c:fddi_type_trans",
        "net/802/fddi.c:fddi_type_trans",
        "net/netlink/af_netlink.c:netlink_rcv_skb",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588186368,
      "name": "skb_pull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void * skb_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588388240,
      "name": "skb_pull",
      "external": true,
      "loc": "net/core/skbuff.c:1900",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/802/fddi.c:fddi_type_trans",
        "net/802/fddi.c:fddi_type_trans",
        "net/netlink/af_netlink.c:netlink_rcv_skb",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588388240,
      "name": "skb_pull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void * skb_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589275573,
      "name": "skb_pull",
      "external": true,
      "loc": "net/core/skbuff.c:1899",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_gro_receive_list"
      ],
      "caller_func": [
        "lib/kobject_uevent.c:uevent_net_broadcast",
        "drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "net/core/drop_monitor.c:net_dm_hw_packet_report",
        "net/core/drop_monitor.c:net_dm_packet_report",
        "net/802/fddi.c:fddi_type_trans",
        "net/802/fddi.c:fddi_type_trans",
        "net/netlink/af_netlink.c:netlink_rcv_skb",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/ipmr.c:ipmr_cache_resolve",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_resolve",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589243424,
      "name": "skb_pull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void * skb_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589275557,
      "name": "skb_pull",
      "external": true,
      "loc": "net/core/skbuff.c:1910",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_gro_receive_list"
      ],
      "caller_func": [
        "lib/kobject_uevent.c:uevent_net_broadcast",
        "drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "net/core/filter.c:__bpf_redirect_neigh",
        "net/core/drop_monitor.c:net_dm_hw_packet_report",
        "net/core/drop_monitor.c:net_dm_packet_report",
        "net/802/fddi.c:fddi_type_trans",
        "net/802/fddi.c:fddi_type_trans",
        "net/sched/sch_frag.c:sch_frag_prepare_frag",
        "net/netlink/af_netlink.c:netlink_rcv_skb",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/ipmr.c:ipmr_cache_resolve",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_cache_resolve",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589242720,
      "name": "skb_pull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void * skb_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589169625,
      "name": "skb_pull",
      "external": true,
      "loc": "net/core/skbuff.c:1952",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_gro_receive_list"
      ],
      "caller_func": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_read",
        "net/core/filter.c:__bpf_redirect_neigh",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/802/fddi.c:fddi_type_trans",
        "net/802/fddi.c:fddi_type_trans",
        "net/sched/sch_frag.c:sch_frag_prepare_frag",
        "net/netlink/af_netlink.c:netlink_rcv_skb",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589137696,
      "name": "skb_pull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void * skb_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589890409,
      "name": "skb_pull",
      "external": true,
      "loc": "net/core/skbuff.c:2024",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_gro_receive_list"
      ],
      "caller_func": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_read",
        "net/core/filter.c:__bpf_redirect_neigh",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/802/fddi.c:fddi_type_trans",
        "net/802/fddi.c:fddi_type_trans",
        "net/sched/sch_frag.c:sch_frag_prepare_frag",
        "net/netlink/af_netlink.c:netlink_rcv_skb",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_inline",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589854016,
      "name": "skb_pull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void * skb_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591382395,
      "name": "skb_pull",
      "external": true,
      "loc": "net/core/skbuff.c:2049",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_pull_data"
      ],
      "caller_func": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_read",
        "net/core/filter.c:__bpf_redirect_neigh",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/802/fddi.c:fddi_type_trans",
        "net/802/fddi.c:fddi_type_trans",
        "net/sched/sch_frag.c:sch_frag_prepare_frag",
        "net/netlink/af_netlink.c:netlink_rcv_skb",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/udp_offload.c:udp_gro_receive_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/ipmr.c:ipmr_cache_resolve",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_inline",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/mctp/route.c:mctp_do_fragment_route",
        "net/mctp/route.c:mctp_route_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591378992,
      "name": "skb_pull",
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
void * skb_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593143723,
      "name": "skb_pull",
      "external": true,
      "loc": "net/core/skbuff.c:2252",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_pull_data"
      ],
      "caller_func": [
        "drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_read",
        "net/core/filter.c:__bpf_redirect_neigh",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/802/fddi.c:fddi_type_trans",
        "net/802/fddi.c:fddi_type_trans",
        "net/sched/sch_frag.c:sch_frag_prepare_frag",
        "net/netlink/af_netlink.c:netlink_rcv_skb",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/udp_offload.c:udp_gro_receive_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/ipmr.c:ipmr_cache_resolve",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_inline",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/mctp/route.c:mctp_do_fragment_route",
        "net/mctp/route.c:mctp_route_input",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593139760,
      "name": "skb_pull",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * skb_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593597067,
      "name": "skb_pull",
      "external": true,
      "loc": "net/core/skbuff.c:2416",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_pull_data"
      ],
      "caller_func": [
        "drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_read",
        "net/core/filter.c:__bpf_redirect_neigh",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/802/fddi.c:fddi_type_trans",
        "net/802/fddi.c:fddi_type_trans",
        "net/sched/sch_frag.c:sch_frag_prepare_frag",
        "net/netlink/af_netlink.c:netlink_rcv_skb",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/udp_offload.c:udp_gro_receive_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/ipmr.c:ipmr_cache_resolve",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_inline",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/mctp/route.c:mctp_do_fragment_route",
        "net/mctp/route.c:mctp_route_input",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593592448,
      "name": "skb_pull",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * skb_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594371883,
      "name": "skb_pull",
      "external": true,
      "loc": "net/core/skbuff.c:2504",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_pull_data"
      ],
      "caller_func": [
        "drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_mp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:pad_compress_skb",
        "net/core/filter.c:__bpf_redirect_neigh",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/802/fddi.c:fddi_type_trans",
        "net/802/fddi.c:fddi_type_trans",
        "net/sched/sch_frag.c:sch_frag_prepare_frag",
        "net/netlink/af_netlink.c:netlink_rcv_skb",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/udp_offload.c:udp_gro_receive_segment",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/ipmr.c:ipmr_cache_resolve",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_inline",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "net/mctp/route.c:mctp_do_fragment_route",
        "net/mctp/route.c:mctp_route_input",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594365344,
      "name": "skb_pull",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void * skb_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501898720,
      "name": "skb_pull",
      "external": true,
      "loc": "net/core/skbuff.c:1900",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/802/fddi.c:fddi_type_trans",
        "net/802/fddi.c:fddi_type_trans",
        "net/netlink/af_netlink.c:netlink_rcv_skb",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501898720,
      "name": "skb_pull",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void * skb_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234664668,
      "name": "skb_pull",
      "external": true,
      "loc": "net/core/skbuff.c:1900",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/802/fddi.c:fddi_type_trans",
        "net/802/fddi.c:fddi_type_trans",
        "net/netlink/af_netlink.c:netlink_rcv_skb",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234664668,
      "name": "skb_pull",
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
void * skb_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295316128,
      "name": "skb_pull",
      "external": true,
      "loc": "net/core/skbuff.c:1900",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/802/fddi.c:fddi_type_trans",
        "net/802/fddi.c:fddi_type_trans",
        "net/netlink/af_netlink.c:netlink_rcv_skb",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295316128,
      "name": "skb_pull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void * skb_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278220382,
      "name": "skb_pull",
      "external": true,
      "loc": "net/core/skbuff.c:1900",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/802/fddi.c:fddi_type_trans",
        "net/802/fddi.c:fddi_type_trans",
        "net/netlink/af_netlink.c:netlink_rcv_skb",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278220382,
      "name": "skb_pull",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * skb_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587995024,
      "name": "skb_pull",
      "external": true,
      "loc": "net/core/skbuff.c:1900",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/802/fddi.c:fddi_type_trans",
        "net/802/fddi.c:fddi_type_trans",
        "net/netlink/af_netlink.c:netlink_rcv_skb",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587995024,
      "name": "skb_pull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void * skb_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587708128,
      "name": "skb_pull",
      "external": true,
      "loc": "net/core/skbuff.c:1900",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg",
        "drivers/net/vxlan.c:neigh_reduce",
        "drivers/net/vxlan.c:neigh_reduce",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/802/fddi.c:fddi_type_trans",
        "net/802/fddi.c:fddi_type_trans",
        "net/netlink/af_netlink.c:netlink_rcv_skb",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587708128,
      "name": "skb_pull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void * skb_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588326800,
      "name": "skb_pull",
      "external": true,
      "loc": "net/core/skbuff.c:1900",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/802/fddi.c:fddi_type_trans",
        "net/802/fddi.c:fddi_type_trans",
        "net/netlink/af_netlink.c:netlink_rcv_skb",
        "net/netfilter/nfnetlink.c:nfnetlink_rcv",
        "net/netfilter/nfnetlink.c:nfnetlink_rcv_batch",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588326800,
      "name": "skb_pull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void * skb_pull(struct sk_buff * skb, unsigned int len)
```

```json
{
  "name": "skb_pull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588462224,
      "name": "skb_pull",
      "external": true,
      "loc": "net/core/skbuff.c:1900",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/802/fddi.c:fddi_type_trans",
        "net/802/fddi.c:fddi_type_trans",
        "net/netlink/af_netlink.c:netlink_rcv_skb",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/udp_offload.c:__udp_gso_segment",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/calipso.c:calipso_skbuff_delattr",
        "net/ipv6/calipso.c:calipso_skbuff_setattr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/8021q/vlan_core.c:vlan_do_receive",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588462224,
      "name": "skb_pull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
