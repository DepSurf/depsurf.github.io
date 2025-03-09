# Function: <code>skb_queue_purge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void skb_queue_purge(struct sk_buff_head * list)
```

```json
{
  "name": "skb_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586210000,
      "name": "skb_queue_purge",
      "external": true,
      "loc": "net/core/skbuff.c:2441",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/netlink/af_netlink.c:netlink_sock_destruct",
        "net/netlink/af_netlink.c:netlink_release",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/packet/af_packet.c:packet_sock_destruct",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/wireless/wext-core.c:wext_pernet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586210000,
      "name": "skb_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void skb_queue_purge(struct sk_buff_head * list)
```

```json
{
  "name": "skb_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586636096,
      "name": "skb_queue_purge",
      "external": true,
      "loc": "net/core/skbuff.c:2439",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_sock_destruct",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_sock_destruct",
        "net/wireless/wext-core.c:wext_pernet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586636096,
      "name": "skb_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void skb_queue_purge(struct sk_buff_head * list)
```

```json
{
  "name": "skb_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586821504,
      "name": "skb_queue_purge",
      "external": true,
      "loc": "net/core/skbuff.c:2415",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_sock_destruct",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_sock_destruct",
        "net/wireless/wext-core.c:wext_pernet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586821504,
      "name": "skb_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void skb_queue_purge(struct sk_buff_head * list)
```

```json
{
  "name": "skb_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586957728,
      "name": "skb_queue_purge",
      "external": true,
      "loc": "net/core/skbuff.c:2455",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_sock_destruct",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_sock_destruct",
        "net/wireless/wext-core.c:wext_pernet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586957728,
      "name": "skb_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void skb_queue_purge(struct sk_buff_head * list)
```

```json
{
  "name": "skb_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587444752,
      "name": "skb_queue_purge",
      "external": true,
      "loc": "net/core/skbuff.c:2831",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_sock_destruct",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_sock_destruct",
        "net/wireless/wext-core.c:wext_pernet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587444752,
      "name": "skb_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void skb_queue_purge(struct sk_buff_head * list)
```

```json
{
  "name": "skb_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587748976,
      "name": "skb_queue_purge",
      "external": true,
      "loc": "net/core/skbuff.c:2847",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_sock_destruct",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_sock_destruct",
        "net/wireless/wext-core.c:wext_pernet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587748976,
      "name": "skb_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void skb_queue_purge(struct sk_buff_head * list)
```

```json
{
  "name": "skb_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587883072,
      "name": "skb_queue_purge",
      "external": true,
      "loc": "net/core/skbuff.c:2902",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_sock_destruct",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_sock_destruct",
        "net/wireless/wext-core.c:wext_pernet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587883072,
      "name": "skb_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void skb_queue_purge(struct sk_buff_head * list)
```

```json
{
  "name": "skb_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588188368,
      "name": "skb_queue_purge",
      "external": true,
      "loc": "net/core/skbuff.c:3068",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_sock_destruct",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_sock_destruct",
        "net/wireless/wext-core.c:wext_pernet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588188368,
      "name": "skb_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void skb_queue_purge(struct sk_buff_head * list)
```

```json
{
  "name": "skb_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588393520,
      "name": "skb_queue_purge",
      "external": true,
      "loc": "net/core/skbuff.c:3074",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_sock_destruct",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_sock_destruct",
        "net/wireless/wext-core.c:wext_pernet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588393520,
      "name": "skb_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void skb_queue_purge(struct sk_buff_head * list)
```

```json
{
  "name": "skb_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589257216,
      "name": "skb_queue_purge",
      "external": true,
      "loc": "net/core/skbuff.c:3073",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_sock_destruct",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_sock_destruct",
        "net/wireless/wext-core.c:wext_pernet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589257216,
      "name": "skb_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void skb_queue_purge(struct sk_buff_head * list)
```

```json
{
  "name": "skb_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589256352,
      "name": "skb_queue_purge",
      "external": true,
      "loc": "net/core/skbuff.c:3091",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_sock_destruct",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_sock_destruct",
        "net/wireless/wext-core.c:wext_pernet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589256352,
      "name": "skb_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void skb_queue_purge(struct sk_buff_head * list)
```

```json
{
  "name": "skb_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589162816,
      "name": "skb_queue_purge",
      "external": true,
      "loc": "net/core/skbuff.c:3177",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "drivers/net/wwan/wwan_core.c:wwan_remove_port",
        "drivers/net/wwan/wwan_core.c:wwan_port_destroy",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_sock_destruct",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_sock_destruct",
        "net/wireless/wext-core.c:wext_pernet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589162816,
      "name": "skb_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void skb_queue_purge(struct sk_buff_head * list)
```

```json
{
  "name": "skb_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589878384,
      "name": "skb_queue_purge",
      "external": true,
      "loc": "net/core/skbuff.c:3249",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_release",
        "drivers/net/wwan/wwan_core.c:wwan_remove_port",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_sock_destruct",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/unix/af_unix.c:unix_dgram_disconnected",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_sock_destruct",
        "net/wireless/wext-core.c:wext_pernet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589878384,
      "name": "skb_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void skb_queue_purge(struct sk_buff_head * list)
```

```json
{
  "name": "skb_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591396544,
      "name": "skb_queue_purge",
      "external": true,
      "loc": "net/core/skbuff.c:3298",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_release",
        "drivers/net/wwan/wwan_core.c:wwan_remove_port",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_sock_destruct",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/unix/af_unix.c:unix_dgram_disconnected",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/wireless/wext-core.c:wext_pernet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591396544,
      "name": "skb_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void skb_queue_purge(struct sk_buff_head * list)
```

```json
{
  "name": "skb_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593161488,
      "name": "skb_queue_purge",
      "external": true,
      "loc": "net/core/skbuff.c:3502",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_release",
        "drivers/net/wwan/wwan_core.c:wwan_remove_port",
        "net/core/stream.c:sk_stream_kill_queues",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_sock_destruct",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/unix/af_unix.c:unix_dgram_disconnected",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/wireless/wext-core.c:wext_pernet_exit",
        "net/mctp/af_mctp.c:mctp_sk_destruct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593161488,
      "name": "skb_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void skb_queue_purge(struct sk_buff_head * list)
```

```json
{
  "name": "skb_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593628608,
      "name": "skb_queue_purge",
      "external": true,
      "loc": "net/core/skbuff.c:3672",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_release",
        "drivers/net/wwan/wwan_core.c:wwan_remove_port",
        "net/core/stream.c:sk_stream_kill_queues",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_sock_destruct",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/unix/af_unix.c:unix_dgram_disconnected",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/wireless/wext-core.c:wext_pernet_exit",
        "net/mctp/af_mctp.c:mctp_sk_destruct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593628608,
      "name": "skb_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "skb_queue_purge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581315884,
      "name": "skb_queue_purge",
      "external": false,
      "loc": "include/linux/skbuff.h:3187",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_list_rules_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592456812,
      "name": "skb_queue_purge",
      "external": false,
      "loc": "include/linux/skbuff.h:3187",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/tun.c:tun_queue_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592584497,
      "name": "skb_queue_purge",
      "external": false,
      "loc": "include/linux/skbuff.h:3187",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594438158,
      "name": "skb_queue_purge",
      "external": false,
      "loc": "include/linux/skbuff.h:3187",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_kill_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594867239,
      "name": "skb_queue_purge",
      "external": false,
      "loc": "include/linux/skbuff.h:3187",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:rcu_cleanup_netpoll_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595141875,
      "name": "skb_queue_purge",
      "external": false,
      "loc": "include/linux/skbuff.h:3187",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_sock_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596030988,
      "name": "skb_queue_purge",
      "external": false,
      "loc": "include/linux/skbuff.h:3187",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596100448,
      "name": "skb_queue_purge",
      "external": false,
      "loc": "include/linux/skbuff.h:3187",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:espintcp_close",
        "net/xfrm/espintcp.c:espintcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596110901,
      "name": "skb_queue_purge",
      "external": false,
      "loc": "include/linux/skbuff.h:3187",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/unix/af_unix.c:unix_dgram_disconnected"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596638715,
      "name": "skb_queue_purge",
      "external": false,
      "loc": "include/linux/skbuff.h:3187",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596788805,
      "name": "skb_queue_purge",
      "external": false,
      "loc": "include/linux/skbuff.h:3187",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-core.c:wext_pernet_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597075973,
      "name": "skb_queue_purge",
      "external": false,
      "loc": "include/linux/skbuff.h:3187",
      "file": "net/mctp/af_mctp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/af_mctp.c:mctp_sk_destruct"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void skb_queue_purge(struct sk_buff_head * list)
```

```json
{
  "name": "skb_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501909256,
      "name": "skb_queue_purge",
      "external": true,
      "loc": "net/core/skbuff.c:3074",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_sock_destruct",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_sock_destruct",
        "net/wireless/wext-core.c:wext_pernet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501909256,
      "name": "skb_queue_purge",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void skb_queue_purge(struct sk_buff_head * list)
```

```json
{
  "name": "skb_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234670516,
      "name": "skb_queue_purge",
      "external": true,
      "loc": "net/core/skbuff.c:3074",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/ethernet/ti/cpts.c:cpts_unregister",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_sock_destruct",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_sock_destruct",
        "net/wireless/wext-core.c:wext_pernet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234670516,
      "name": "skb_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void skb_queue_purge(struct sk_buff_head * list)
```

```json
{
  "name": "skb_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295322352,
      "name": "skb_queue_purge",
      "external": true,
      "loc": "net/core/skbuff.c:3074",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_sock_destruct",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_sock_destruct",
        "net/wireless/wext-core.c:wext_pernet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295322352,
      "name": "skb_queue_purge",
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
void skb_queue_purge(struct sk_buff_head * list)
```

```json
{
  "name": "skb_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278222500,
      "name": "skb_queue_purge",
      "external": true,
      "loc": "net/core/skbuff.c:3074",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_sock_destruct",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_sock_destruct",
        "net/wireless/wext-core.c:wext_pernet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278222500,
      "name": "skb_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void skb_queue_purge(struct sk_buff_head * list)
```

```json
{
  "name": "skb_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588000304,
      "name": "skb_queue_purge",
      "external": true,
      "loc": "net/core/skbuff.c:3074",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_sock_destruct",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_sock_destruct",
        "net/wireless/wext-core.c:wext_pernet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588000304,
      "name": "skb_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void skb_queue_purge(struct sk_buff_head * list)
```

```json
{
  "name": "skb_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587713392,
      "name": "skb_queue_purge",
      "external": true,
      "loc": "net/core/skbuff.c:3074",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_sock_destruct",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_sock_destruct",
        "net/wireless/wext-core.c:wext_pernet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587713392,
      "name": "skb_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void skb_queue_purge(struct sk_buff_head * list)
```

```json
{
  "name": "skb_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588332080,
      "name": "skb_queue_purge",
      "external": true,
      "loc": "net/core/skbuff.c:3074",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_sock_destruct",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_sock_destruct",
        "net/wireless/wext-core.c:wext_pernet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588332080,
      "name": "skb_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void skb_queue_purge(struct sk_buff_head * list)
```

```json
{
  "name": "skb_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588467552,
      "name": "skb_queue_purge",
      "external": true,
      "loc": "net/core/skbuff.c:3074",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_sock_destruct",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/unix/af_unix.c:unix_sock_destructor",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_sock_destruct",
        "net/wireless/wext-core.c:wext_pernet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588467552,
      "name": "skb_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void skb_queue_purge(struct sk_buff_head * list)
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
