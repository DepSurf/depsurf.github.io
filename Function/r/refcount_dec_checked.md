# Function: <code>refcount_dec_checked</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void refcount_dec_checked(refcount_t * r)
```

```json
{
  "name": "refcount_dec_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583965792,
      "name": "refcount_dec_checked",
      "external": true,
      "loc": "lib/refcount.c:226",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583965792,
      "name": "refcount_dec_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void refcount_dec_checked(refcount_t * r)
```

```json
{
  "name": "refcount_dec_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584145648,
      "name": "refcount_dec_checked",
      "external": true,
      "loc": "lib/refcount.c:234",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584145648,
      "name": "refcount_dec_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void refcount_dec_checked(refcount_t * r)
```

```json
{
  "name": "refcount_dec_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584268096,
      "name": "refcount_dec_checked",
      "external": true,
      "loc": "lib/refcount.c:234",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584268096,
      "name": "refcount_dec_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void refcount_dec_checked(refcount_t * r)
```

```json
{
  "name": "refcount_dec_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496150856,
      "name": "refcount_dec_checked",
      "external": true,
      "loc": "lib/refcount.c:234",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes",
        "fs/fuse/dev.c:request_wait_answer",
        "net/core/sock.c:sk_stop_timer",
        "net/core/datagram.c:__sk_queue_drop_skb",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit",
        "net/netlink/af_netlink.c:netlink_remove",
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_release_cb",
        "net/ipv4/tcp_output.c:tcp_release_cb",
        "net/ipv4/tcp_output.c:tcp_release_cb",
        "net/ipv4/tcp_output.c:tcp_release_cb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/arp.c:arp_constructor",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_stop_timer",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/unix/af_unix.c:unix_bind",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:addrconf_del_dad_work",
        "net/ipv6/ndisc.c:ndisc_constructor",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:mld_ifc_stop_timer",
        "net/ipv6/mcast.c:mld_gq_stop_timer",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496150856,
      "name": "refcount_dec_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void refcount_dec_checked(refcount_t * r)
```

```json
{
  "name": "refcount_dec_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229472572,
      "name": "refcount_dec_checked",
      "external": true,
      "loc": "lib/refcount.c:234",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes",
        "fs/fuse/dev.c:fuse_simple_request",
        "sound/core/pcm_native.c:snd_pcm_unlink",
        "sound/core/pcm_native.c:snd_pcm_unlink",
        "net/core/sock.c:sk_stop_timer",
        "net/core/datagram.c:__sk_queue_drop_skb",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit",
        "net/netlink/af_netlink.c:netlink_remove",
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_release_cb",
        "net/ipv4/tcp_output.c:tcp_release_cb",
        "net/ipv4/tcp_output.c:tcp_release_cb",
        "net/ipv4/tcp_output.c:tcp_release_cb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/arp.c:arp_constructor",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:ip_mc_down",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_stop_timer",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/unix/af_unix.c:unix_bind",
        "net/unix/af_unix.c:unix_autobind",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:addrconf_del_dad_work",
        "net/ipv6/ndisc.c:ndisc_constructor",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:mld_ifc_stop_timer",
        "net/ipv6/mcast.c:mld_gq_stop_timer",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/packet/af_packet.c:packet_release",
        "net/xdp/xsk.c:xsk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229472572,
      "name": "refcount_dec_checked",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void refcount_dec_checked(refcount_t * r)
```

```json
{
  "name": "refcount_dec_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290411952,
      "name": "refcount_dec_checked",
      "external": true,
      "loc": "lib/refcount.c:234",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290411952,
      "name": "refcount_dec_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void refcount_dec_checked(refcount_t * r)
```

```json
{
  "name": "refcount_dec_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275205156,
      "name": "refcount_dec_checked",
      "external": true,
      "loc": "lib/refcount.c:234",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275205156,
      "name": "refcount_dec_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void refcount_dec_checked(refcount_t * r)
```

```json
{
  "name": "refcount_dec_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584236832,
      "name": "refcount_dec_checked",
      "external": true,
      "loc": "lib/refcount.c:234",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584236832,
      "name": "refcount_dec_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void refcount_dec_checked(refcount_t * r)
```

```json
{
  "name": "refcount_dec_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584172032,
      "name": "refcount_dec_checked",
      "external": true,
      "loc": "lib/refcount.c:234",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584172032,
      "name": "refcount_dec_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void refcount_dec_checked(refcount_t * r)
```

```json
{
  "name": "refcount_dec_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584220592,
      "name": "refcount_dec_checked",
      "external": true,
      "loc": "lib/refcount.c:234",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584220592,
      "name": "refcount_dec_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void refcount_dec_checked(refcount_t * r)
```

```json
{
  "name": "refcount_dec_checked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584325424,
      "name": "refcount_dec_checked",
      "external": true,
      "loc": "lib/refcount.c:234",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584325424,
      "name": "refcount_dec_checked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void refcount_dec_checked(refcount_t * r)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void refcount_dec_checked(refcount_t * r)
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
