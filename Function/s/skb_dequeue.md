# Function: <code>skb_dequeue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * skb_dequeue(struct sk_buff_head * list)
```

```json
{
  "name": "skb_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586205360,
      "name": "skb_dequeue",
      "external": true,
      "loc": "net/core/skbuff.c:2401",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "net/core/skbuff.c:skb_queue_purge",
        "net/core/dev.c:dev_cpu_callback",
        "net/core/neighbour.c:pneigh_queue_purge",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/wireless/wext-core.c:wireless_nlevent_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586205360,
      "name": "skb_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct sk_buff * skb_dequeue(struct sk_buff_head * list)
```

```json
{
  "name": "skb_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586626176,
      "name": "skb_dequeue",
      "external": true,
      "loc": "net/core/skbuff.c:2399",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/skbuff.c:skb_queue_purge",
        "net/core/dev.c:dev_cpu_callback",
        "net/core/neighbour.c:pneigh_queue_purge",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:queue_process",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/wireless/wext-core.c:wireless_nlevent_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586626176,
      "name": "skb_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct sk_buff * skb_dequeue(struct sk_buff_head * list)
```

```json
{
  "name": "skb_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586810704,
      "name": "skb_dequeue",
      "external": true,
      "loc": "net/core/skbuff.c:2375",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:auditd_reset",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/skbuff.c:skb_queue_purge",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/neighbour.c:pneigh_queue_purge",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:queue_process",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/wireless/wext-core.c:wireless_nlevent_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586810704,
      "name": "skb_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct sk_buff * skb_dequeue(struct sk_buff_head * list)
```

```json
{
  "name": "skb_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586935040,
      "name": "skb_dequeue",
      "external": true,
      "loc": "net/core/skbuff.c:2415",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_send_queue",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/skbuff.c:skb_queue_purge",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/neighbour.c:pneigh_queue_purge",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:queue_process",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/wireless/wext-core.c:wireless_nlevent_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586935040,
      "name": "skb_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct sk_buff * skb_dequeue(struct sk_buff_head * list)
```

```json
{
  "name": "skb_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587428096,
      "name": "skb_dequeue",
      "external": true,
      "loc": "net/core/skbuff.c:2791",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_send_queue",
        "kernel/bpf/sockmap.c:smap_tx_work",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/skbuff.c:skb_queue_purge",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/neighbour.c:pneigh_queue_purge",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:queue_process",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/wireless/wext-core.c:wireless_nlevent_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587428096,
      "name": "skb_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct sk_buff * skb_dequeue(struct sk_buff_head * list)
```

```json
{
  "name": "skb_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587732512,
      "name": "skb_dequeue",
      "external": true,
      "loc": "net/core/skbuff.c:2807",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_send_queue",
        "kernel/bpf/sockmap.c:smap_tx_work",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/skbuff.c:skb_queue_purge",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/neighbour.c:pneigh_queue_purge",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:queue_process",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/wireless/wext-core.c:wireless_nlevent_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587732512,
      "name": "skb_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct sk_buff * skb_dequeue(struct sk_buff_head * list)
```

```json
{
  "name": "skb_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587866768,
      "name": "skb_dequeue",
      "external": true,
      "loc": "net/core/skbuff.c:2862",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_send_queue",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/skbuff.c:skb_queue_purge",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/neighbour.c:pneigh_queue_purge",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:queue_process",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/wireless/wext-core.c:wireless_nlevent_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587866768,
      "name": "skb_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct sk_buff * skb_dequeue(struct sk_buff_head * list)
```

```json
{
  "name": "skb_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588171440,
      "name": "skb_dequeue",
      "external": true,
      "loc": "net/core/skbuff.c:3028",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_send_queue",
        "fs/io_uring.c:io_sqe_files_unregister",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/skbuff.c:skb_queue_purge",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/neighbour.c:pneigh_queue_purge",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:queue_process",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/wireless/wext-core.c:wireless_nlevent_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588171440,
      "name": "skb_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
struct sk_buff * skb_dequeue(struct sk_buff_head * list)
```

```json
{
  "name": "skb_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588376640,
      "name": "skb_dequeue",
      "external": true,
      "loc": "net/core/skbuff.c:3034",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_send_queue",
        "fs/io_uring.c:io_sqe_files_unregister",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/skbuff.c:skb_queue_purge",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/neighbour.c:pneigh_queue_purge",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:queue_process",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/wireless/wext-core.c:wireless_nlevent_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588376640,
      "name": "skb_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
struct sk_buff * skb_dequeue(struct sk_buff_head * list)
```

```json
{
  "name": "skb_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589242464,
      "name": "skb_dequeue",
      "external": true,
      "loc": "net/core/skbuff.c:3033",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_send_queue",
        "fs/io_uring.c:io_sqe_files_unregister",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/skbuff.c:skb_queue_purge",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:queue_process",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/wireless/wext-core.c:wireless_nlevent_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589242464,
      "name": "skb_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct sk_buff * skb_dequeue(struct sk_buff_head * list)
```

```json
{
  "name": "skb_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589241760,
      "name": "skb_dequeue",
      "external": true,
      "loc": "net/core/skbuff.c:3051",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_send_queue",
        "fs/io_uring.c:io_sqe_files_unregister",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/skbuff.c:skb_queue_purge",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:queue_process",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/wireless/wext-core.c:wireless_nlevent_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589241760,
      "name": "skb_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct sk_buff * skb_dequeue(struct sk_buff_head * list)
```

```json
{
  "name": "skb_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589136736,
      "name": "skb_dequeue",
      "external": true,
      "loc": "net/core/skbuff.c:3137",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_send_queue",
        "fs/io_uring.c:io_rsrc_file_put",
        "fs/io_uring.c:io_rsrc_file_put",
        "fs/io_uring.c:__io_sqe_files_unregister",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_read",
        "net/core/skbuff.c:skb_queue_purge",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:queue_process",
        "net/core/skmsg.c:sk_psock_stop",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/wireless/wext-core.c:wireless_nlevent_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589136736,
      "name": "skb_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct sk_buff * skb_dequeue(struct sk_buff_head * list)
```

```json
{
  "name": "skb_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589856608,
      "name": "skb_dequeue",
      "external": true,
      "loc": "net/core/skbuff.c:3209",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "fs/io_uring.c:io_rsrc_file_put",
        "fs/io_uring.c:io_rsrc_file_put",
        "fs/io_uring.c:__io_sqe_files_unregister",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_read",
        "net/core/skbuff.c:skb_queue_purge",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:queue_process",
        "net/core/skmsg.c:sk_psock_stop",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/wireless/wext-core.c:wireless_nlevent_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589856608,
      "name": "skb_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct sk_buff * skb_dequeue(struct sk_buff_head * list)
```

```json
{
  "name": "skb_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591382064,
      "name": "skb_dequeue",
      "external": true,
      "loc": "net/core/skbuff.c:3258",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:kauditd_send_queue",
        "io_uring/io_uring.c:io_rsrc_file_put",
        "io_uring/io_uring.c:__io_sqe_files_unregister",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_read",
        "net/core/skbuff.c:skb_queue_purge",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:queue_process",
        "net/core/skmsg.c:sk_psock_stop",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/wireless/wext-core.c:wireless_nlevent_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591382064,
      "name": "skb_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct sk_buff * skb_dequeue(struct sk_buff_head * list)
```

```json
{
  "name": "skb_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593143360,
      "name": "skb_dequeue",
      "external": true,
      "loc": "net/core/skbuff.c:3462",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:kauditd_send_queue",
        "io_uring/rsrc.c:io_rsrc_file_put",
        "io_uring/rsrc.c:__io_sqe_files_unregister",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_read",
        "net/core/skbuff.c:skb_queue_purge",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:queue_process",
        "net/core/skmsg.c:sk_psock_stop",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/wireless/wext-core.c:wireless_nlevent_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593143360,
      "name": "skb_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct sk_buff * skb_dequeue(struct sk_buff_head * list)
```

```json
{
  "name": "skb_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593596896,
      "name": "skb_dequeue",
      "external": true,
      "loc": "net/core/skbuff.c:3632",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:kauditd_send_queue",
        "io_uring/rsrc.c:io_rsrc_file_scm_put",
        "io_uring/rsrc.c:io_rsrc_file_scm_put",
        "io_uring/rsrc.c:__io_sqe_files_unregister",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_read",
        "net/core/skbuff.c:skb_queue_purge",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:queue_process",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/wireless/wext-core.c:wireless_nlevent_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593596896,
      "name": "skb_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct sk_buff * skb_dequeue(struct sk_buff_head * list)
```

```json
{
  "name": "skb_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594371712,
      "name": "skb_dequeue",
      "external": true,
      "loc": "net/core/skbuff.c:3720",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:kauditd_send_queue",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:queue_process",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/wireless/wext-core.c:wireless_nlevent_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594371712,
      "name": "skb_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct sk_buff * skb_dequeue(struct sk_buff_head * list)
```

```json
{
  "name": "skb_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501902224,
      "name": "skb_dequeue",
      "external": true,
      "loc": "net/core/skbuff.c:3034",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_send_queue",
        "fs/io_uring.c:io_sqe_files_unregister",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/skbuff.c:skb_queue_purge",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/neighbour.c:pneigh_queue_purge",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:queue_process",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/wireless/wext-core.c:wireless_nlevent_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501902224,
      "name": "skb_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct sk_buff * skb_dequeue(struct sk_buff_head * list)
```

```json
{
  "name": "skb_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234650656,
      "name": "skb_dequeue",
      "external": true,
      "loc": "net/core/skbuff.c:3034",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_send_queue",
        "fs/io_uring.c:io_sqe_files_unregister",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/skbuff.c:skb_queue_purge",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/neighbour.c:pneigh_queue_purge",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:queue_process",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/wireless/wext-core.c:wireless_nlevent_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234650656,
      "name": "skb_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct sk_buff * skb_dequeue(struct sk_buff_head * list)
```

```json
{
  "name": "skb_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295295664,
      "name": "skb_dequeue",
      "external": true,
      "loc": "net/core/skbuff.c:3034",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_send_queue",
        "fs/io_uring.c:io_sqe_files_unregister",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/skbuff.c:skb_queue_purge",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/neighbour.c:pneigh_queue_purge",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:queue_process",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/wireless/wext-core.c:wireless_nlevent_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295295664,
      "name": "skb_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct sk_buff * skb_dequeue(struct sk_buff_head * list)
```

```json
{
  "name": "skb_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278205592,
      "name": "skb_dequeue",
      "external": true,
      "loc": "net/core/skbuff.c:3034",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_send_queue",
        "fs/io_uring.c:io_sqe_files_unregister",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/skbuff.c:skb_queue_purge",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/neighbour.c:pneigh_queue_purge",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:queue_process",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/wireless/wext-core.c:wireless_nlevent_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278205592,
      "name": "skb_dequeue",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct sk_buff * skb_dequeue(struct sk_buff_head * list)
```

```json
{
  "name": "skb_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587983424,
      "name": "skb_dequeue",
      "external": true,
      "loc": "net/core/skbuff.c:3034",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_send_queue",
        "fs/io_uring.c:io_sqe_files_unregister",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/skbuff.c:skb_queue_purge",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/neighbour.c:pneigh_queue_purge",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:queue_process",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/wireless/wext-core.c:wireless_nlevent_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587983424,
      "name": "skb_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
struct sk_buff * skb_dequeue(struct sk_buff_head * list)
```

```json
{
  "name": "skb_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587696528,
      "name": "skb_dequeue",
      "external": true,
      "loc": "net/core/skbuff.c:3034",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_send_queue",
        "fs/io_uring.c:io_sqe_files_unregister",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/skbuff.c:skb_queue_purge",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/neighbour.c:pneigh_queue_purge",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:queue_process",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/wireless/wext-core.c:wireless_nlevent_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587696528,
      "name": "skb_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
struct sk_buff * skb_dequeue(struct sk_buff_head * list)
```

```json
{
  "name": "skb_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588315200,
      "name": "skb_dequeue",
      "external": true,
      "loc": "net/core/skbuff.c:3034",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_send_queue",
        "fs/io_uring.c:io_sqe_files_unregister",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/skbuff.c:skb_queue_purge",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/neighbour.c:pneigh_queue_purge",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:queue_process",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/wireless/wext-core.c:wireless_nlevent_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588315200,
      "name": "skb_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
struct sk_buff * skb_dequeue(struct sk_buff_head * list)
```

```json
{
  "name": "skb_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588450432,
      "name": "skb_dequeue",
      "external": true,
      "loc": "net/core/skbuff.c:3034",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_send_queue",
        "fs/io_uring.c:io_sqe_files_unregister",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "net/core/skbuff.c:skb_queue_purge",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/neighbour.c:pneigh_queue_purge",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:queue_process",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/wireless/wext-core.c:wireless_nlevent_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588450432,
      "name": "skb_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
