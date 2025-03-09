# Function: <code>synchronize_net</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void synchronize_net()
```

```json
{
  "name": "synchronize_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586276432,
      "name": "synchronize_net",
      "external": true,
      "loc": "net/core/dev.c:7219",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:dev_remove_pack",
        "net/core/dev.c:dev_remove_offload",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/lwtunnel.c:lwtunnel_encap_del_ops",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/netfilter/core.c:nf_unregister_net_hook",
        "net/netfilter/core.c:nf_unregister_net_hook",
        "net/ipv4/protocol.c:inet_del_protocol",
        "net/ipv4/protocol.c:inet_del_offload",
        "net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister",
        "net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender",
        "net/ipv6/protocol.c:inet6_del_protocol",
        "net/ipv6/protocol.c:inet6_del_offload",
        "net/packet/af_packet.c:__fanout_set_data_bpf",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586276432,
      "name": "synchronize_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void synchronize_net()
```

```json
{
  "name": "synchronize_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586702128,
      "name": "synchronize_net",
      "external": true,
      "loc": "net/core/dev.c:7737",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_net_exit",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_napi_del",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:dev_remove_offload",
        "net/core/dev.c:dev_remove_pack",
        "net/core/lwtunnel.c:lwtunnel_encap_del_ops",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/netfilter/core.c:nf_unregister_net_hook",
        "net/netfilter/core.c:nf_unregister_net_hook",
        "net/ipv4/protocol.c:inet_del_offload",
        "net/ipv4/protocol.c:inet_del_protocol",
        "net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister",
        "net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender",
        "net/ipv6/protocol.c:inet6_del_offload",
        "net/ipv6/protocol.c:inet6_del_protocol",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:__fanout_set_data_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586702128,
      "name": "synchronize_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void synchronize_net()
```

```json
{
  "name": "synchronize_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586888496,
      "name": "synchronize_net",
      "external": true,
      "loc": "net/core/dev.c:7908",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_napi_del",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:dev_remove_offload",
        "net/core/dev.c:dev_remove_pack",
        "net/core/lwtunnel.c:lwtunnel_encap_del_ops",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/netfilter/core.c:nf_unregister_net_hook",
        "net/netfilter/core.c:nf_unregister_net_hook",
        "net/ipv4/protocol.c:inet_del_offload",
        "net/ipv4/protocol.c:inet_del_protocol",
        "net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister",
        "net/ipv6/seg6.c:seg6_genl_set_tunsrc",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister",
        "net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender",
        "net/ipv6/protocol.c:inet6_del_offload",
        "net/ipv6/protocol.c:inet6_del_protocol",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:__fanout_set_data_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586888496,
      "name": "synchronize_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void synchronize_net()
```

```json
{
  "name": "synchronize_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587012800,
      "name": "synchronize_net",
      "external": true,
      "loc": "net/core/dev.c:8102",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_napi_del",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:dev_remove_offload",
        "net/core/dev.c:dev_remove_pack",
        "net/core/lwtunnel.c:lwtunnel_encap_del_ops",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/netfilter/core.c:nf_unregister_net_hooks",
        "net/netfilter/core.c:nf_unregister_net_hooks",
        "net/netfilter/core.c:nf_unregister_net_hooks",
        "net/netfilter/core.c:nf_unregister_net_hook",
        "net/netfilter/core.c:nf_unregister_net_hook",
        "net/ipv4/protocol.c:inet_del_offload",
        "net/ipv4/protocol.c:inet_del_protocol",
        "net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister",
        "net/ipv6/seg6.c:seg6_genl_set_tunsrc",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister",
        "net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender",
        "net/ipv6/protocol.c:inet6_del_offload",
        "net/ipv6/protocol.c:inet6_del_protocol",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:__fanout_set_data_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587012800,
      "name": "synchronize_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void synchronize_net()
```

```json
{
  "name": "synchronize_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587510752,
      "name": "synchronize_net",
      "external": true,
      "loc": "net/core/dev.c:8281",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_napi_del",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_remove_offload",
        "net/core/dev.c:dev_remove_pack",
        "net/core/lwtunnel.c:lwtunnel_encap_del_ops",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/netfilter/core.c:nf_unregister_net_hooks",
        "net/netfilter/core.c:nf_unregister_net_hooks",
        "net/netfilter/core.c:nf_unregister_net_hook",
        "net/netfilter/core.c:nf_unregister_net_hook",
        "net/netfilter/core.c:nf_register_net_hook",
        "net/ipv4/protocol.c:inet_del_offload",
        "net/ipv4/protocol.c:inet_del_protocol",
        "net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister",
        "net/ipv6/seg6.c:seg6_genl_set_tunsrc",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister",
        "net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender",
        "net/ipv6/protocol.c:inet6_del_offload",
        "net/ipv6/protocol.c:inet6_del_protocol",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:__fanout_set_data_bpf",
        "net/packet/af_packet.c:__unregister_prot_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587510752,
      "name": "synchronize_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void synchronize_net()
```

```json
{
  "name": "synchronize_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587814800,
      "name": "synchronize_net",
      "external": true,
      "loc": "net/core/dev.c:8531",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_delete_elem",
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/xskmap.c:xsk_map_free",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_napi_del",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_remove_offload",
        "net/core/dev.c:dev_remove_pack",
        "net/core/lwtunnel.c:lwtunnel_encap_del_ops",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/ipv4/protocol.c:inet_del_offload",
        "net/ipv4/protocol.c:inet_del_protocol",
        "net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister",
        "net/ipv6/seg6.c:seg6_genl_set_tunsrc",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister",
        "net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender",
        "net/ipv6/protocol.c:inet6_del_offload",
        "net/ipv6/protocol.c:inet6_del_protocol",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:__fanout_set_data_bpf",
        "net/packet/af_packet.c:__unregister_prot_hook",
        "net/xdp/xsk.c:xsk_release",
        "net/xdp/xdp_umem.c:xdp_del_sk_umem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587814800,
      "name": "synchronize_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void synchronize_net()
```

```json
{
  "name": "synchronize_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587949696,
      "name": "synchronize_net",
      "external": true,
      "loc": "net/core/dev.c:9161",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_free",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_napi_del",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_remove_offload",
        "net/core/dev.c:dev_remove_pack",
        "net/core/lwtunnel.c:lwtunnel_encap_del_ops",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/ipv4/protocol.c:inet_del_offload",
        "net/ipv4/protocol.c:inet_del_protocol",
        "net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister",
        "net/ipv6/seg6.c:seg6_genl_set_tunsrc",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister",
        "net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender",
        "net/ipv6/protocol.c:inet6_del_offload",
        "net/ipv6/protocol.c:inet6_del_protocol",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:__fanout_set_data_bpf",
        "net/packet/af_packet.c:__unregister_prot_hook",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587949696,
      "name": "synchronize_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void synchronize_net()
```

```json
{
  "name": "synchronize_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588259888,
      "name": "synchronize_net",
      "external": true,
      "loc": "net/core/dev.c:9266",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_free",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_napi_del",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_remove_offload",
        "net/core/dev.c:dev_remove_pack",
        "net/core/lwtunnel.c:lwtunnel_encap_del_ops",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/ipv4/protocol.c:inet_del_offload",
        "net/ipv4/protocol.c:inet_del_protocol",
        "net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister",
        "net/ipv6/seg6.c:seg6_genl_set_tunsrc",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister",
        "net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender",
        "net/ipv6/protocol.c:inet6_del_offload",
        "net/ipv6/protocol.c:inet6_del_protocol",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:__fanout_set_data_bpf",
        "net/packet/af_packet.c:__unregister_prot_hook",
        "net/xdp/xsk.c:xsk_unbind_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588259888,
      "name": "synchronize_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void synchronize_net()
```

```json
{
  "name": "synchronize_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588465008,
      "name": "synchronize_net",
      "external": true,
      "loc": "net/core/dev.c:9610",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_free",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_napi_del",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_remove_offload",
        "net/core/dev.c:dev_remove_pack",
        "net/core/lwtunnel.c:lwtunnel_encap_del_ops",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/ipv4/protocol.c:inet_del_offload",
        "net/ipv4/protocol.c:inet_del_protocol",
        "net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister",
        "net/ipv6/seg6.c:seg6_genl_set_tunsrc",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister",
        "net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender",
        "net/ipv6/protocol.c:inet6_del_offload",
        "net/ipv6/protocol.c:inet6_del_protocol",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:__fanout_set_data_bpf",
        "net/packet/af_packet.c:__unregister_prot_hook",
        "net/xdp/xsk.c:xsk_unbind_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588465008,
      "name": "synchronize_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void synchronize_net()
```

```json
{
  "name": "synchronize_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589350350,
      "name": "synchronize_net",
      "external": true,
      "loc": "net/core/dev.c:10065",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_napi_del",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_remove_offload",
        "net/core/dev.c:dev_remove_pack"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/rtnetlink.c:rtnl_unregister_all",
        "net/core/lwtunnel.c:lwtunnel_encap_del_ops",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/ipv4/protocol.c:inet_del_offload",
        "net/ipv4/protocol.c:inet_del_protocol",
        "net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister",
        "net/ipv6/seg6.c:seg6_genl_set_tunsrc",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister",
        "net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender",
        "net/ipv6/protocol.c:inet6_del_offload",
        "net/ipv6/protocol.c:inet6_del_protocol",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_notifier",
        "net/xdp/xsk.c:xsk_release",
        "net/xdp/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589331264,
      "name": "synchronize_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void synchronize_net()
```

```json
{
  "name": "synchronize_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589351918,
      "name": "synchronize_net",
      "external": true,
      "loc": "net/core/dev.c:10774",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_remove_offload",
        "net/core/dev.c:dev_remove_pack"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/xen-netfront.c:xennet_destroy_queues",
        "net/core/rtnetlink.c:rtnl_unregister_all",
        "net/core/lwtunnel.c:lwtunnel_encap_del_ops",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/ipv4/protocol.c:inet_del_offload",
        "net/ipv4/protocol.c:inet_del_protocol",
        "net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister",
        "net/ipv6/seg6.c:seg6_genl_set_tunsrc",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister",
        "net/ipv6/protocol.c:inet6_del_offload",
        "net/ipv6/protocol.c:inet6_del_protocol",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:fanout_set_data",
        "net/xdp/xsk.c:xsk_notifier",
        "net/xdp/xsk.c:xsk_release",
        "net/xdp/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589331504,
      "name": "synchronize_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void synchronize_net()
```

```json
{
  "name": "synchronize_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589254302,
      "name": "synchronize_net",
      "external": true,
      "loc": "net/core/dev.c:10955",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:unregister_netdevice_many",
        "net/core/dev.c:unregister_netdevice_many",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_remove_offload",
        "net/core/dev.c:dev_remove_pack"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/xen-netfront.c:xennet_destroy_queues",
        "net/core/rtnetlink.c:rtnl_unregister_all",
        "net/core/lwtunnel.c:lwtunnel_encap_del_ops",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/ipv4/protocol.c:inet_del_offload",
        "net/ipv4/protocol.c:inet_del_protocol",
        "net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/seg6.c:seg6_genl_set_tunsrc",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister",
        "net/ipv6/protocol.c:inet6_del_offload",
        "net/ipv6/protocol.c:inet6_del_protocol",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_notifier",
        "net/xdp/xsk.c:xsk_release",
        "net/xdp/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589226160,
      "name": "synchronize_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void synchronize_net()
```

```json
{
  "name": "synchronize_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589979838,
      "name": "synchronize_net",
      "external": true,
      "loc": "net/core/dev.c:10962",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:unregister_netdevice_many",
        "net/core/dev.c:unregister_netdevice_many",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_remove_offload",
        "net/core/dev.c:dev_remove_pack"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/xen-netfront.c:xennet_destroy_queues",
        "net/core/rtnetlink.c:rtnl_unregister_all",
        "net/core/lwtunnel.c:lwtunnel_encap_del_ops",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/ipv4/protocol.c:inet_del_offload",
        "net/ipv4/protocol.c:inet_del_protocol",
        "net/ipv4/nexthop.c:replace_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop_grp",
        "net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/seg6.c:seg6_genl_set_tunsrc",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister",
        "net/ipv6/protocol.c:inet6_del_offload",
        "net/ipv6/protocol.c:inet6_del_protocol",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_notifier",
        "net/xdp/xsk.c:xsk_release",
        "net/xdp/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589948464,
      "name": "synchronize_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void synchronize_net()
```

```json
{
  "name": "synchronize_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591523228,
      "name": "synchronize_net",
      "external": true,
      "loc": "net/core/dev.c:10742",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:unregister_netdevice_many",
        "net/core/dev.c:unregister_netdevice_many",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_remove_pack"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/xen-netfront.c:xennet_destroy_queues",
        "net/core/rtnetlink.c:rtnl_unregister_all",
        "net/core/gro.c:dev_remove_offload",
        "net/core/lwtunnel.c:lwtunnel_encap_del_ops",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/ipv4/protocol.c:inet_del_offload",
        "net/ipv4/protocol.c:inet_del_protocol",
        "net/ipv4/nexthop.c:replace_nexthop_grp",
        "net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/seg6.c:seg6_genl_set_tunsrc",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister",
        "net/ipv6/protocol.c:inet6_del_offload",
        "net/ipv6/protocol.c:inet6_del_protocol",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_notifier",
        "net/xdp/xsk.c:xsk_release",
        "net/xdp/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591483936,
      "name": "synchronize_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void synchronize_net()
```

```json
{
  "name": "synchronize_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593296796,
      "name": "synchronize_net",
      "external": true,
      "loc": "net/core/dev.c:10737",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_remove_pack"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/xen-netfront.c:xennet_destroy_queues",
        "net/core/rtnetlink.c:rtnl_unregister_all",
        "net/core/gro.c:dev_remove_offload",
        "net/core/lwtunnel.c:lwtunnel_encap_del_ops",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/ipv4/protocol.c:inet_del_offload",
        "net/ipv4/protocol.c:inet_del_protocol",
        "net/ipv4/nexthop.c:replace_nexthop_grp",
        "net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/seg6.c:seg6_genl_set_tunsrc",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister",
        "net/ipv6/protocol.c:inet6_del_offload",
        "net/ipv6/protocol.c:inet6_del_protocol",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:fanout_set_data",
        "net/packet/af_packet.c:fanout_set_data",
        "net/xdp/xsk.c:xsk_notifier",
        "net/xdp/xsk.c:xsk_release",
        "net/xdp/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593252352,
      "name": "synchronize_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void synchronize_net()
```

```json
{
  "name": "synchronize_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593756497,
      "name": "synchronize_net",
      "external": true,
      "loc": "net/core/dev.c:10753",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_remove_pack"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/virtio_net.c:virtnet_free_queues",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/xen-netfront.c:xennet_destroy_queues",
        "net/core/rtnetlink.c:rtnl_unregister_all",
        "net/core/gro.c:dev_remove_offload",
        "net/core/lwtunnel.c:lwtunnel_encap_del_ops",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/ipv4/protocol.c:inet_del_offload",
        "net/ipv4/protocol.c:inet_del_protocol",
        "net/ipv4/nexthop.c:replace_nexthop_grp",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/seg6.c:seg6_genl_set_tunsrc",
        "net/ipv6/protocol.c:inet6_del_offload",
        "net/ipv6/protocol.c:inet6_del_protocol",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:fanout_set_data",
        "net/packet/af_packet.c:fanout_set_data",
        "net/xdp/xsk.c:xsk_notifier",
        "net/xdp/xsk.c:xsk_release",
        "net/xdp/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593713200,
      "name": "synchronize_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void synchronize_net()
```

```json
{
  "name": "synchronize_net",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594535013,
      "name": "synchronize_net",
      "external": true,
      "loc": "net/core/dev.c:10964",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_remove_pack"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/virtio_net.c:virtnet_free_queues",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/xen-netfront.c:xennet_destroy_queues",
        "net/core/rtnetlink.c:rtnl_unregister_all",
        "net/core/gro.c:dev_remove_offload",
        "net/core/lwtunnel.c:lwtunnel_encap_del_ops",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/ipv4/protocol.c:inet_del_offload",
        "net/ipv4/protocol.c:inet_del_protocol",
        "net/ipv4/nexthop.c:replace_nexthop_grp",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/seg6.c:seg6_genl_set_tunsrc",
        "net/ipv6/protocol.c:inet6_del_offload",
        "net/ipv6/protocol.c:inet6_del_protocol",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:fanout_set_data",
        "net/packet/af_packet.c:fanout_set_data",
        "net/xdp/xsk.c:xsk_notifier",
        "net/xdp/xsk.c:xsk_release",
        "net/xdp/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594492320,
      "name": "synchronize_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void synchronize_net()
```

```json
{
  "name": "synchronize_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501989192,
      "name": "synchronize_net",
      "external": true,
      "loc": "net/core/dev.c:9610",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_free",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_napi_del",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_remove_offload",
        "net/core/dev.c:dev_remove_pack",
        "net/core/lwtunnel.c:lwtunnel_encap_del_ops",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/ipv4/protocol.c:inet_del_offload",
        "net/ipv4/protocol.c:inet_del_offload",
        "net/ipv4/protocol.c:inet_del_protocol",
        "net/ipv4/protocol.c:inet_del_protocol",
        "net/ipv6/seg6.c:seg6_genl_set_tunsrc",
        "net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender",
        "net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender",
        "net/ipv6/protocol.c:inet6_del_offload",
        "net/ipv6/protocol.c:inet6_del_offload",
        "net/ipv6/protocol.c:inet6_del_protocol",
        "net/ipv6/protocol.c:inet6_del_protocol",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:__fanout_set_data_bpf",
        "net/xdp/xsk.c:xsk_unbind_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501989192,
      "name": "synchronize_net",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void synchronize_net()
```

```json
{
  "name": "synchronize_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234746784,
      "name": "synchronize_net",
      "external": true,
      "loc": "net/core/dev.c:9610",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_free",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_napi_del",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_remove_offload",
        "net/core/dev.c:dev_remove_pack",
        "net/core/lwtunnel.c:lwtunnel_encap_del_ops",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/ipv4/protocol.c:inet_del_offload",
        "net/ipv4/protocol.c:inet_del_protocol",
        "net/ipv6/seg6.c:seg6_genl_set_tunsrc",
        "net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender",
        "net/ipv6/protocol.c:inet6_del_offload",
        "net/ipv6/protocol.c:inet6_del_protocol",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:__fanout_set_data_bpf",
        "net/xdp/xsk.c:xsk_unbind_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234746784,
      "name": "synchronize_net",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void synchronize_net()
```

```json
{
  "name": "synchronize_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295425264,
      "name": "synchronize_net",
      "external": true,
      "loc": "net/core/dev.c:9610",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_free",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_napi_del",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_remove_offload",
        "net/core/dev.c:dev_remove_offload",
        "net/core/dev.c:dev_remove_pack",
        "net/core/rtnetlink.c:rtnl_unregister_all",
        "net/core/lwtunnel.c:lwtunnel_encap_del_ops",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/ipv4/protocol.c:inet_del_offload",
        "net/ipv4/protocol.c:inet_del_protocol",
        "net/ipv6/seg6.c:seg6_genl_set_tunsrc",
        "net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender",
        "net/ipv6/protocol.c:inet6_del_offload",
        "net/ipv6/protocol.c:inet6_del_protocol",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:__fanout_set_data_bpf",
        "net/xdp/xsk.c:xsk_unbind_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295425264,
      "name": "synchronize_net",
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
void synchronize_net()
```

```json
{
  "name": "synchronize_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278288070,
      "name": "synchronize_net",
      "external": true,
      "loc": "net/core/dev.c:9610",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_free",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_napi_del",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_remove_offload",
        "net/core/dev.c:dev_remove_pack",
        "net/core/lwtunnel.c:lwtunnel_encap_del_ops",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/ipv4/protocol.c:inet_del_offload",
        "net/ipv4/protocol.c:inet_del_protocol",
        "net/ipv6/seg6.c:seg6_genl_set_tunsrc",
        "net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender",
        "net/ipv6/protocol.c:inet6_del_offload",
        "net/ipv6/protocol.c:inet6_del_protocol",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:__fanout_set_data_bpf",
        "net/xdp/xsk.c:xsk_unbind_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278288070,
      "name": "synchronize_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void synchronize_net()
```

```json
{
  "name": "synchronize_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588071792,
      "name": "synchronize_net",
      "external": true,
      "loc": "net/core/dev.c:9610",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_free",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_napi_del",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_remove_offload",
        "net/core/dev.c:dev_remove_pack",
        "net/core/lwtunnel.c:lwtunnel_encap_del_ops",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/ipv4/protocol.c:inet_del_offload",
        "net/ipv4/protocol.c:inet_del_protocol",
        "net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister",
        "net/ipv6/seg6.c:seg6_genl_set_tunsrc",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister",
        "net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender",
        "net/ipv6/protocol.c:inet6_del_offload",
        "net/ipv6/protocol.c:inet6_del_protocol",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:__fanout_set_data_bpf",
        "net/packet/af_packet.c:__unregister_prot_hook",
        "net/xdp/xsk.c:xsk_unbind_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588071792,
      "name": "synchronize_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void synchronize_net()
```

```json
{
  "name": "synchronize_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587785216,
      "name": "synchronize_net",
      "external": true,
      "loc": "net/core/dev.c:9610",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_free",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/vxlan.c:vxlan_sock_release",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_napi_del",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_remove_offload",
        "net/core/dev.c:dev_remove_pack",
        "net/core/lwtunnel.c:lwtunnel_encap_del_ops",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/ipv4/protocol.c:inet_del_offload",
        "net/ipv4/protocol.c:inet_del_protocol",
        "net/ipv4/ip_tunnel.c:ip_tunnel_encap_del_ops",
        "net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister",
        "net/ipv6/seg6.c:seg6_genl_set_tunsrc",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister",
        "net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender",
        "net/ipv6/protocol.c:inet6_del_offload",
        "net/ipv6/protocol.c:inet6_del_protocol",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:__fanout_set_data_bpf",
        "net/packet/af_packet.c:__unregister_prot_hook",
        "net/xdp/xsk.c:xsk_unbind_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587785216,
      "name": "synchronize_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void synchronize_net()
```

```json
{
  "name": "synchronize_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588403568,
      "name": "synchronize_net",
      "external": true,
      "loc": "net/core/dev.c:9610",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_free",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_napi_del",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_remove_offload",
        "net/core/dev.c:dev_remove_pack",
        "net/core/lwtunnel.c:lwtunnel_encap_del_ops",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/netfilter/nfnetlink.c:nfnetlink_net_exit_batch",
        "net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_resize",
        "net/netfilter/nf_conntrack_core.c:nf_conntrack_cleanup_net_list",
        "net/netfilter/nf_conntrack_core.c:nf_ct_iterate_destroy",
        "net/ipv4/protocol.c:inet_del_offload",
        "net/ipv4/protocol.c:inet_del_protocol",
        "net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister",
        "net/ipv6/seg6.c:seg6_genl_set_tunsrc",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister",
        "net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender",
        "net/ipv6/protocol.c:inet6_del_offload",
        "net/ipv6/protocol.c:inet6_del_protocol",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:__fanout_set_data_bpf",
        "net/packet/af_packet.c:__unregister_prot_hook",
        "net/xdp/xsk.c:xsk_unbind_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588403568,
      "name": "synchronize_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void synchronize_net()
```

```json
{
  "name": "synchronize_net",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588540032,
      "name": "synchronize_net",
      "external": true,
      "loc": "net/core/dev.c:9610",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:xsk_map_free",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_napi_del",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_remove_offload",
        "net/core/dev.c:dev_remove_pack",
        "net/core/lwtunnel.c:lwtunnel_encap_del_ops",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_remove_tap",
        "net/ipv4/protocol.c:inet_del_offload",
        "net/ipv4/protocol.c:inet_del_protocol",
        "net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister",
        "net/ipv6/seg6.c:seg6_genl_set_tunsrc",
        "net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister",
        "net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender",
        "net/ipv6/protocol.c:inet6_del_offload",
        "net/ipv6/protocol.c:inet6_del_protocol",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:__fanout_set_data_bpf",
        "net/packet/af_packet.c:__unregister_prot_hook",
        "net/xdp/xsk.c:xsk_unbind_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588540032,
      "name": "synchronize_net",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
