# Function: <code>prandom_u32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 prandom_u32()
```

```json
{
  "name": "prandom_u32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583008896,
      "name": "prandom_u32",
      "external": true,
      "loc": "lib/random32.c:78",
      "file": "lib/random32.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/random32.c:__prandom_timer"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "mm/swapfile.c:SyS_swapon",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "block/blk-mq-tag.c:blk_mq_tag_init_last_tag",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/ipv4/route.c:ip_idents_reserve",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/mcast.c:igmp6_group_added",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/packet/af_packet.c:fanout_demux_rollover",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583008896,
      "name": "prandom_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
u32 prandom_u32()
```

```json
{
  "name": "prandom_u32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583300109,
      "name": "prandom_u32",
      "external": true,
      "loc": "lib/random32.c:78",
      "file": "lib/random32.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/random32.c:__prandom_timer"
      ],
      "caller_func": [
        "mm/swapfile.c:SyS_swapon",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "block/blk-mq-tag.c:blk_mq_tag_init_last_tag",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/ipv4/route.c:ip_idents_reserve",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_group_added",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583299328,
      "name": "prandom_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
u32 prandom_u32()
```

```json
{
  "name": "prandom_u32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583419149,
      "name": "prandom_u32",
      "external": true,
      "loc": "lib/random32.c:78",
      "file": "lib/random32.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/random32.c:__prandom_timer"
      ],
      "caller_func": [
        "mm/swapfile.c:SyS_swapon",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "lib/sbitmap.c:__sbitmap_queue_get",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/ipv4/route.c:ip_idents_reserve",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_group_added",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583418368,
      "name": "prandom_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
u32 prandom_u32()
```

```json
{
  "name": "prandom_u32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583440157,
      "name": "prandom_u32",
      "external": true,
      "loc": "lib/random32.c:78",
      "file": "lib/random32.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/random32.c:__prandom_timer"
      ],
      "caller_func": [
        "mm/swapfile.c:SyS_swapon",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "lib/sbitmap.c:__sbitmap_queue_get_shallow",
        "lib/sbitmap.c:__sbitmap_queue_get",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/ipv4/route.c:ip_idents_reserve",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583439408,
      "name": "prandom_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
u32 prandom_u32()
```

```json
{
  "name": "prandom_u32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583620093,
      "name": "prandom_u32",
      "external": true,
      "loc": "lib/random32.c:79",
      "file": "lib/random32.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/random32.c:__prandom_timer"
      ],
      "caller_func": [
        "mm/swapfile.c:SYSC_swapon",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "lib/sbitmap.c:__sbitmap_queue_get_shallow",
        "lib/sbitmap.c:__sbitmap_queue_get",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/ipv4/route.c:ip_idents_reserve",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:mld_dad_start_timer",
        "net/ipv6/mcast.c:mld_ifc_start_timer",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583619376,
      "name": "prandom_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
u32 prandom_u32()
```

```json
{
  "name": "prandom_u32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583836541,
      "name": "prandom_u32",
      "external": true,
      "loc": "lib/random32.c:79",
      "file": "lib/random32.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/random32.c:__prandom_timer"
      ],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "lib/sbitmap.c:__sbitmap_queue_get_shallow",
        "lib/sbitmap.c:__sbitmap_queue_get",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/ipv4/route.c:ip_idents_reserve",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:mld_dad_start_timer",
        "net/ipv6/mcast.c:mld_ifc_start_timer",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583835824,
      "name": "prandom_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
u32 prandom_u32()
```

```json
{
  "name": "prandom_u32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583920173,
      "name": "prandom_u32",
      "external": true,
      "loc": "lib/random32.c:79",
      "file": "lib/random32.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/random32.c:__prandom_timer"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "lib/sbitmap.c:__sbitmap_queue_get_shallow",
        "lib/sbitmap.c:__sbitmap_queue_get",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/ipv4/route.c:ip_idents_reserve",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/igmp.c:igmp_rcv",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:mld_dad_start_timer",
        "net/ipv6/mcast.c:mld_ifc_start_timer",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583919456,
      "name": "prandom_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 prandom_u32()
```

```json
{
  "name": "prandom_u32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584099981,
      "name": "prandom_u32",
      "external": true,
      "loc": "lib/random32.c:79",
      "file": "lib/random32.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/random32.c:__prandom_timer"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "lib/sbitmap.c:__sbitmap_queue_get_shallow",
        "lib/sbitmap.c:__sbitmap_queue_get",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/ipv4/route.c:ip_idents_reserve",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:mld_dad_start_timer",
        "net/ipv6/mcast.c:mld_ifc_start_timer",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584099216,
      "name": "prandom_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
u32 prandom_u32()
```

```json
{
  "name": "prandom_u32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584222765,
      "name": "prandom_u32",
      "external": true,
      "loc": "lib/random32.c:79",
      "file": "lib/random32.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/random32.c:__prandom_timer"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "lib/sbitmap.c:__sbitmap_queue_get_shallow",
        "lib/sbitmap.c:__sbitmap_queue_get",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/ipv4/route.c:ip_idents_reserve",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:mld_dad_start_timer",
        "net/ipv6/mcast.c:mld_ifc_start_timer",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584222000,
      "name": "prandom_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
u32 prandom_u32()
```

```json
{
  "name": "prandom_u32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584628381,
      "name": "prandom_u32",
      "external": true,
      "loc": "lib/random32.c:79",
      "file": "lib/random32.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/random32.c:__prandom_timer"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:scan_swap_map_slots",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/fat/inode.c:fat_fill_inode",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "lib/sbitmap.c:__sbitmap_queue_get_shallow",
        "lib/sbitmap.c:__sbitmap_queue_get",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/neighbour.c:neigh_proc_base_reachable_time",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_parms_alloc",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/ipv4/route.c:ip_idents_reserve",
        "net/ipv4/inet_connection_sock.c:inet_csk_find_open_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_ifc_event",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_start_timer",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/ipv6/addrconf.c:inet6_set_iftoken",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584628752,
      "name": "prandom_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
u32 prandom_u32()
```

```json
{
  "name": "prandom_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584747216,
      "name": "prandom_u32",
      "external": true,
      "loc": "lib/random32.c:384",
      "file": "lib/random32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:scan_swap_map_slots",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/fat/inode.c:fat_fill_inode",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "lib/random32.c:prandom_reseed",
        "lib/sbitmap.c:__sbitmap_queue_get_shallow",
        "lib/sbitmap.c:__sbitmap_queue_get",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/neighbour.c:neigh_proc_base_reachable_time",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_parms_alloc",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/ipv4/route.c:ip_idents_reserve",
        "net/ipv4/inet_connection_sock.c:inet_csk_find_open_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/icmp.c:icmp_global_allow",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_ifc_event",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/ipv6/addrconf.c:inet6_set_iftoken",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584747216,
      "name": "prandom_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
u32 prandom_u32()
```

```json
{
  "name": "prandom_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584775552,
      "name": "prandom_u32",
      "external": true,
      "loc": "lib/random32.c:384",
      "file": "lib/random32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:scan_swap_map_slots",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/fat/inode.c:fat_fill_inode",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "lib/random32.c:prandom_reseed",
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get",
        "lib/sbitmap.c:sbitmap_init_node",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/neighbour.c:neigh_proc_base_reachable_time",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_parms_alloc",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/ipv4/route.c:ip_idents_reserve",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_connection_sock.c:inet_csk_find_open_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/icmp.c:icmp_global_allow",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_ifc_event",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/ipv6/addrconf.c:inet6_set_iftoken",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/mcast.c:mld_ifc_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/output_core.c:ipv6_select_ident",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584775552,
      "name": "prandom_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
u32 prandom_u32()
```

```json
{
  "name": "prandom_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585205504,
      "name": "prandom_u32",
      "external": true,
      "loc": "lib/random32.c:384",
      "file": "lib/random32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus",
        "mm/shmem.c:shmem_get_inode",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:scan_swap_map_slots",
        "mm/kfence/core.c:kfence_guarded_alloc",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/fat/inode.c:fat_fill_inode",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "lib/random32.c:prandom_reseed",
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get",
        "lib/sbitmap.c:sbitmap_init_node",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/neighbour.c:neigh_proc_base_reachable_time",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_parms_alloc",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:ip_idents_reserve",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_connection_sock.c:inet_csk_find_open_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/icmp.c:icmp_global_allow",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_ifc_event",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/ipv6/addrconf.c:inet6_set_iftoken",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/route.c:rt6_insert_exception",
        "net/ipv6/mcast.c:mld_ifc_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/output_core.c:ipv6_select_ident",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585205504,
      "name": "prandom_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prandom_u32",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580555531,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582080969,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582526739,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:scan_swap_map_slots"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582706373,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_guarded_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583919768,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584014281,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584080518,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:ext4_multi_mount_protect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584262895,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_register_li_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584487841,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585489159,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586658825,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbitmap_queue_get_batch",
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get",
        "lib/sbitmap.c:sbitmap_init_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591371719,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591435594,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591575423,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_proc_base_reachable_time",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_parms_alloc",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_periodic_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592134737,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592274051,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592329898,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_build_and_send_pkt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592357922,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592365010,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592436206,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_send_challenge_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592472391,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_rtx_synack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592501049,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592526413,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592564550,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/ipv4/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592587676,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592622826,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_global_allow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592681086,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_ifc_event",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592848323,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592943923,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593000726,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_autobind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593113394,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_set_iftoken",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593133586,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_insert_exception"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593281185,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:__mld_query_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593304625,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593334974,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:__ip6_datagram_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593344892,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593408661,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593448921,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ipv6_select_ident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593469954,
      "name": "prandom_u32",
      "external": false,
      "loc": "include/linux/prandom.h:15",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:fanout_demux_rollover"
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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
u32 prandom_u32()
```

```json
{
  "name": "prandom_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496096032,
      "name": "prandom_u32",
      "external": true,
      "loc": "lib/random32.c:79",
      "file": "lib/random32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "lib/random32.c:__prandom_timer",
        "lib/sbitmap.c:__sbitmap_queue_get_shallow",
        "lib/sbitmap.c:__sbitmap_queue_get",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/ipv4/route.c:ip_idents_reserve",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_ifc_start_timer",
        "net/ipv4/igmp.c:igmp_start_timer",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:mld_dad_start_timer",
        "net/ipv6/mcast.c:mld_ifc_start_timer",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496096032,
      "name": "prandom_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
u32 prandom_u32()
```

```json
{
  "name": "prandom_u32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229423268,
      "name": "prandom_u32",
      "external": true,
      "loc": "lib/random32.c:79",
      "file": "lib/random32.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/random32.c:__prandom_timer"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "lib/sbitmap.c:__sbitmap_queue_get_shallow",
        "lib/sbitmap.c:__sbitmap_queue_get",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/netlink/af_netlink.c:netlink_autobind",
        "net/ipv4/route.c:ip_idents_reserve",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_ifc_start_timer",
        "net/ipv4/igmp.c:igmp_start_timer",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:mld_dad_start_timer",
        "net/ipv6/mcast.c:mld_ifc_start_timer",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229422456,
      "name": "prandom_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
u32 prandom_u32()
```

```json
{
  "name": "prandom_u32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290340344,
      "name": "prandom_u32",
      "external": true,
      "loc": "lib/random32.c:79",
      "file": "lib/random32.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/random32.c:__prandom_timer"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "lib/sbitmap.c:__sbitmap_queue_get_shallow",
        "lib/sbitmap.c:__sbitmap_queue_get",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/netlink/af_netlink.c:netlink_autobind",
        "net/ipv4/route.c:ip_idents_reserve",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290339008,
      "name": "prandom_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
u32 prandom_u32()
```

```json
{
  "name": "prandom_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275163958,
      "name": "prandom_u32",
      "external": true,
      "loc": "lib/random32.c:79",
      "file": "lib/random32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "lib/random32.c:__prandom_timer",
        "lib/sbitmap.c:__sbitmap_queue_get_shallow",
        "lib/sbitmap.c:__sbitmap_queue_get",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/netlink/af_netlink.c:netlink_autobind",
        "net/ipv4/route.c:ip_idents_reserve",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_ifc_start_timer",
        "net/ipv4/igmp.c:igmp_start_timer",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:mld_dad_start_timer",
        "net/ipv6/mcast.c:mld_ifc_start_timer",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275163958,
      "name": "prandom_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
u32 prandom_u32()
```

```json
{
  "name": "prandom_u32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584191501,
      "name": "prandom_u32",
      "external": true,
      "loc": "lib/random32.c:79",
      "file": "lib/random32.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/random32.c:__prandom_timer"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "lib/sbitmap.c:__sbitmap_queue_get_shallow",
        "lib/sbitmap.c:__sbitmap_queue_get",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/ipv4/route.c:ip_idents_reserve",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:mld_dad_start_timer",
        "net/ipv6/mcast.c:mld_ifc_start_timer",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584190736,
      "name": "prandom_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
u32 prandom_u32()
```

```json
{
  "name": "prandom_u32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584126717,
      "name": "prandom_u32",
      "external": true,
      "loc": "lib/random32.c:79",
      "file": "lib/random32.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/random32.c:__prandom_timer"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "lib/sbitmap.c:__sbitmap_queue_get_shallow",
        "lib/sbitmap.c:__sbitmap_queue_get",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/ipv4/route.c:ip_idents_reserve",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:mld_dad_start_timer",
        "net/ipv6/mcast.c:mld_ifc_start_timer",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584125968,
      "name": "prandom_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
u32 prandom_u32()
```

```json
{
  "name": "prandom_u32",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584175261,
      "name": "prandom_u32",
      "external": true,
      "loc": "lib/random32.c:79",
      "file": "lib/random32.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/random32.c:__prandom_timer"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "lib/sbitmap.c:__sbitmap_queue_get_shallow",
        "lib/sbitmap.c:__sbitmap_queue_get",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/ipv4/route.c:ip_idents_reserve",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:mld_dad_start_timer",
        "net/ipv6/mcast.c:mld_ifc_start_timer",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584174496,
      "name": "prandom_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
u32 prandom_u32()
```

```json
{
  "name": "prandom_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584279024,
      "name": "prandom_u32",
      "external": true,
      "loc": "lib/random32.c:79",
      "file": "lib/random32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "lib/random32.c:__prandom_timer",
        "lib/sbitmap.c:__sbitmap_queue_get_shallow",
        "lib/sbitmap.c:__sbitmap_queue_get",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/ipv4/route.c:ip_idents_reserve",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:mld_dad_start_timer",
        "net/ipv6/mcast.c:mld_ifc_start_timer",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584279024,
      "name": "prandom_u32",
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
u32 prandom_u32()
```
</details>
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
