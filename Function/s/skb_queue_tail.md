# Function: <code>skb_queue_tail</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void skb_queue_tail(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586205664,
      "name": "skb_queue_tail",
      "external": true,
      "loc": "net/core/skbuff.c:2481",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_hold_skb",
        "kernel/audit.c:audit_log_end",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/ppp/ppp_generic.c:ppp_push",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/netlink/af_netlink.c:__netlink_sendskb",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586205664,
      "name": "skb_queue_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void skb_queue_tail(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586626480,
      "name": "skb_queue_tail",
      "external": true,
      "loc": "net/core/skbuff.c:2479",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:audit_hold_skb",
        "kernel/auditfilter.c:audit_list_rules",
        "kernel/auditfilter.c:audit_list_rules",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_push",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/netlink/af_netlink.c:__netlink_sendskb",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586626480,
      "name": "skb_queue_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void skb_queue_tail(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586811008,
      "name": "skb_queue_tail",
      "external": true,
      "loc": "net/core/skbuff.c:2474",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:kauditd_thread",
        "kernel/auditfilter.c:audit_list_rules",
        "kernel/auditfilter.c:audit_list_rules",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/netlink/af_netlink.c:__netlink_sendskb",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586811008,
      "name": "skb_queue_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void skb_queue_tail(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586935344,
      "name": "skb_queue_tail",
      "external": true,
      "loc": "net/core/skbuff.c:2514",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:kauditd_retry_skb",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_start_xmit",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skbuff.c:sock_queue_err_skb",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/netlink/af_netlink.c:__netlink_sendskb",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586935344,
      "name": "skb_queue_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void skb_queue_tail(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587428400,
      "name": "skb_queue_tail",
      "external": true,
      "loc": "net/core/skbuff.c:2893",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:kauditd_retry_skb",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/bpf/sockmap.c:smap_read_sock_strparser",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skbuff.c:sock_queue_err_skb",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/netlink/af_netlink.c:__netlink_sendskb",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587428400,
      "name": "skb_queue_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void skb_queue_tail(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587732816,
      "name": "skb_queue_tail",
      "external": true,
      "loc": "net/core/skbuff.c:2909",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:kauditd_retry_skb",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/bpf/sockmap.c:smap_read_sock_strparser",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/netlink/af_netlink.c:__netlink_sendskb",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587732816,
      "name": "skb_queue_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void skb_queue_tail(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587867072,
      "name": "skb_queue_tail",
      "external": true,
      "loc": "net/core/skbuff.c:2968",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:kauditd_retry_skb",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/netlink/af_netlink.c:__netlink_sendskb",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587867072,
      "name": "skb_queue_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void skb_queue_tail(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588171744,
      "name": "skb_queue_tail",
      "external": true,
      "loc": "net/core/skbuff.c:3134",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:kauditd_retry_skb",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/netlink/af_netlink.c:__netlink_sendskb",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588171744,
      "name": "skb_queue_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void skb_queue_tail(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588376944,
      "name": "skb_queue_tail",
      "external": true,
      "loc": "net/core/skbuff.c:3140",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:kauditd_retry_skb",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/netlink/af_netlink.c:__netlink_sendskb",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588376944,
      "name": "skb_queue_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void skb_queue_tail(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_tail",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589246783,
      "name": "skb_queue_tail",
      "external": true,
      "loc": "net/core/skbuff.c:3139",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_queue_err_skb"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:kauditd_retry_skb",
        "kernel/auditfilter.c:audit_list_rules",
        "kernel/auditfilter.c:audit_list_rules",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_explode",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_skb_redirect",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume",
        "net/xfrm/espintcp.c:handle_nonesp",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589239536,
      "name": "skb_queue_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void skb_queue_tail(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_tail",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589246047,
      "name": "skb_queue_tail",
      "external": true,
      "loc": "net/core/skbuff.c:3157",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_queue_err_skb"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:kauditd_retry_skb",
        "kernel/auditfilter.c:audit_list_rules",
        "kernel/auditfilter.c:audit_list_rules",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_explode",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_skb_redirect",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:do_one_broadcast",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume",
        "net/xfrm/espintcp.c:handle_nonesp",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589238928,
      "name": "skb_queue_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void skb_queue_tail(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_tail",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589140847,
      "name": "skb_queue_tail",
      "external": true,
      "loc": "net/core/skbuff.c:3243",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_queue_err_skb"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:kauditd_retry_skb",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_explode",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "drivers/net/wwan/wwan_core.c:wwan_port_rx",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_skb_redirect",
        "net/netlink/af_netlink.c:__netlink_sendskb",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume",
        "net/xfrm/espintcp.c:handle_nonesp",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589132720,
      "name": "skb_queue_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void skb_queue_tail(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_tail",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589860707,
      "name": "skb_queue_tail",
      "external": true,
      "loc": "net/core/skbuff.c:3315",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_queue_err_skb"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:kauditd_hold_skb",
        "kernel/audit.c:kauditd_hold_skb",
        "kernel/audit.c:kauditd_rehold_skb",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_explode",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "drivers/net/wwan/wwan_core.c:wwan_port_rx",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_skb_redirect",
        "net/netlink/af_netlink.c:__netlink_sendskb",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume",
        "net/xfrm/espintcp.c:espintcp_rcv",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589852416,
      "name": "skb_queue_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void skb_queue_tail(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_tail",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591383539,
      "name": "skb_queue_tail",
      "external": true,
      "loc": "net/core/skbuff.c:3364",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_queue_err_skb"
      ],
      "caller_func": [
        "kernel/audit.c:audit_buffer_aux_new",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:kauditd_hold_skb",
        "kernel/audit.c:kauditd_hold_skb",
        "kernel/audit.c:kauditd_rehold_skb",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_explode",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "drivers/net/wwan/wwan_core.c:wwan_port_rx",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_skb_redirect",
        "net/netlink/af_netlink.c:__netlink_sendskb",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume",
        "net/xfrm/espintcp.c:handle_nonesp",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591376976,
      "name": "skb_queue_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void skb_queue_tail(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_tail",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593146131,
      "name": "skb_queue_tail",
      "external": true,
      "loc": "net/core/skbuff.c:3568",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_queue_err_skb"
      ],
      "caller_func": [
        "kernel/audit.c:audit_buffer_aux_new",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:kauditd_hold_skb",
        "kernel/audit.c:kauditd_hold_skb",
        "kernel/audit.c:kauditd_rehold_skb",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_explode",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "drivers/net/wwan/wwan_core.c:wwan_port_rx",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_skb_redirect",
        "net/netlink/af_netlink.c:__netlink_sendskb",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume",
        "net/xfrm/espintcp.c:handle_nonesp",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:queue_oob",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/garbage.c:unix_gc",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593137648,
      "name": "skb_queue_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void skb_queue_tail(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_tail",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593599752,
      "name": "skb_queue_tail",
      "external": true,
      "loc": "net/core/skbuff.c:3738",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_queue_err_skb"
      ],
      "caller_func": [
        "kernel/audit.c:audit_buffer_aux_new",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:kauditd_hold_skb",
        "kernel/audit.c:kauditd_hold_skb",
        "kernel/audit.c:kauditd_rehold_skb",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_explode",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "drivers/net/wwan/wwan_core.c:wwan_port_rx",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_skb_redirect",
        "net/netlink/af_netlink.c:__netlink_sendskb",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume",
        "net/xfrm/espintcp.c:handle_nonesp",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:queue_oob",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/garbage.c:unix_gc",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593590496,
      "name": "skb_queue_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void skb_queue_tail(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_tail",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594374344,
      "name": "skb_queue_tail",
      "external": true,
      "loc": "net/core/skbuff.c:3859",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_queue_err_skb"
      ],
      "caller_func": [
        "kernel/audit.c:audit_buffer_aux_new",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:kauditd_hold_skb",
        "kernel/audit.c:kauditd_hold_skb",
        "kernel/audit.c:kauditd_rehold_skb",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_explode",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_skb_redirect",
        "net/netlink/af_netlink.c:__netlink_sendskb",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume",
        "net/xfrm/espintcp.c:handle_nonesp",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:queue_oob",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/garbage.c:unix_gc",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594363280,
      "name": "skb_queue_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void skb_queue_tail(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501901416,
      "name": "skb_queue_tail",
      "external": true,
      "loc": "net/core/skbuff.c:3140",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:kauditd_retry_skb",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/netlink/af_netlink.c:__netlink_sendskb",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501901416,
      "name": "skb_queue_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void skb_queue_tail(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234650984,
      "name": "skb_queue_tail",
      "external": true,
      "loc": "net/core/skbuff.c:3140",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:kauditd_retry_skb",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_mp_explode",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/netlink/af_netlink.c:__netlink_sendskb",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234650984,
      "name": "skb_queue_tail",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void skb_queue_tail(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295296256,
      "name": "skb_queue_tail",
      "external": true,
      "loc": "net/core/skbuff.c:3140",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:kauditd_retry_skb",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skbuff.c:sock_queue_err_skb",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/netlink/af_netlink.c:__netlink_sendskb",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295296256,
      "name": "skb_queue_tail",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void skb_queue_tail(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278205904,
      "name": "skb_queue_tail",
      "external": true,
      "loc": "net/core/skbuff.c:3140",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:kauditd_retry_skb",
        "kernel/auditfilter.c:audit_list_rules",
        "kernel/auditfilter.c:audit_list_rules",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/netlink/af_netlink.c:__netlink_sendskb",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278205904,
      "name": "skb_queue_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void skb_queue_tail(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587983728,
      "name": "skb_queue_tail",
      "external": true,
      "loc": "net/core/skbuff.c:3140",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:kauditd_retry_skb",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/netlink/af_netlink.c:__netlink_sendskb",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587983728,
      "name": "skb_queue_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void skb_queue_tail(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587696832,
      "name": "skb_queue_tail",
      "external": true,
      "loc": "net/core/skbuff.c:3140",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:kauditd_retry_skb",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/netlink/af_netlink.c:__netlink_sendskb",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587696832,
      "name": "skb_queue_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void skb_queue_tail(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588315504,
      "name": "skb_queue_tail",
      "external": true,
      "loc": "net/core/skbuff.c:3140",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:kauditd_retry_skb",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/netlink/af_netlink.c:__netlink_sendskb",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588315504,
      "name": "skb_queue_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void skb_queue_tail(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_tail",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588450736,
      "name": "skb_queue_tail",
      "external": true,
      "loc": "net/core/skbuff.c:3140",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:kauditd_retry_skb",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/auditfilter.c:audit_list_rules_send",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_write",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/netlink/af_netlink.c:__netlink_sendskb",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588450736,
      "name": "skb_queue_tail",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
