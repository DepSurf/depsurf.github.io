# Function: <code>add_wait_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void add_wait_queue(wait_queue_head_t * q, wait_queue_t * wait)
```

```json
{
  "name": "add_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579644416,
      "name": "add_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:23",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/huge_memory.c:khugepaged",
        "mm/memcontrol.c:memcg_event_ptable_queue_proc",
        "fs/select.c:__pollwait",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/signalfd.c:signalfd_read",
        "drivers/virtio/virtio_balloon.c:balloon",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/rtc-dev.c:rtc_dev_read",
        "drivers/md/dm.c:dm_wait_for_completion",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644416,
      "name": "add_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void add_wait_queue(wait_queue_head_t * q, wait_queue_t * wait)
```

```json
{
  "name": "add_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579659152,
      "name": "add_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:23",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_ptable_queue_proc",
        "fs/select.c:__pollwait",
        "fs/dcache.c:d_alloc_parallel",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/signalfd.c:signalfd_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/rtc-dev.c:rtc_dev_read",
        "drivers/md/dm.c:dm_wait_for_completion",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579659152,
      "name": "add_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void add_wait_queue(wait_queue_head_t * q, wait_queue_t * wait)
```

```json
{
  "name": "add_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579683696,
      "name": "add_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:23",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_ptable_queue_proc",
        "fs/select.c:__pollwait",
        "fs/dcache.c:d_alloc_parallel",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/signalfd.c:signalfd_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/rtc-dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683696,
      "name": "add_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void add_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579669552,
      "name": "add_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:24",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_ptable_queue_proc",
        "fs/select.c:__pollwait",
        "fs/dcache.c:d_alloc_parallel",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/signalfd.c:signalfd_read",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/rtc-dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579669552,
      "name": "add_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void add_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579700000,
      "name": "add_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:24",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_ptable_queue_proc",
        "fs/select.c:__pollwait",
        "fs/dcache.c:d_alloc_parallel",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/signalfd.c:signalfd_read",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/rtc-dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579700000,
      "name": "add_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void add_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579734112,
      "name": "add_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:17",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "kernel/bpf/sockmap.c:bpf_tcp_recvmsg",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_ptable_queue_proc",
        "fs/select.c:__pollwait",
        "fs/dcache.c:d_alloc_parallel",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/signalfd.c:signalfd_read",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/rtc-dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579734112,
      "name": "add_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void add_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579773792,
      "name": "add_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:17",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_ptable_queue_proc",
        "fs/select.c:__pollwait",
        "fs/dcache.c:d_alloc_parallel",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/signalfd.c:signalfd_read",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/aio.c:aio_poll_queue_proc",
        "fs/aio.c:aio_poll_complete_work",
        "lib/sbitmap.c:sbitmap_add_wait_queue",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579773792,
      "name": "add_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void add_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579801456,
      "name": "add_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:18",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_ptable_queue_proc",
        "fs/select.c:__pollwait",
        "fs/dcache.c:d_alloc_parallel",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/signalfd.c:signalfd_read",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/aio.c:aio_poll_queue_proc",
        "fs/aio.c:aio_poll_complete_work",
        "fs/io_uring.c:io_poll_queue_proc",
        "fs/io_uring.c:io_poll_complete_work",
        "lib/sbitmap.c:sbitmap_add_wait_queue",
        "lib/sbitmap.c:sbitmap_add_wait_queue",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579801456,
      "name": "add_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void add_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579849024,
      "name": "add_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:18",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_ptable_queue_proc",
        "fs/select.c:__pollwait",
        "fs/dcache.c:d_alloc_parallel",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/signalfd.c:signalfd_read",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/aio.c:aio_poll_queue_proc",
        "fs/aio.c:aio_poll_complete_work",
        "fs/io_uring.c:io_poll_queue_proc",
        "fs/io_uring.c:io_poll_complete_work",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/vfio/virqfd.c:virqfd_ptable_queue_proc",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579849024,
      "name": "add_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void add_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579887712,
      "name": "add_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:18",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged_do_scan",
        "mm/memcontrol.c:memcg_event_ptable_queue_proc",
        "fs/select.c:__pollwait",
        "fs/dcache.c:d_alloc_parallel",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/signalfd.c:signalfd_dequeue",
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/aio.c:aio_poll_queue_proc",
        "fs/aio.c:aio_poll_complete_work",
        "fs/io_uring.c:io_poll_queue_proc",
        "fs/io_uring.c:io_async_queue_proc",
        "fs/io_uring.c:io_poll_rewait",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/vfio/virqfd.c:virqfd_ptable_queue_proc",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:inet_wait_for_connect",
        "net/mptcp/protocol.c:mptcp_wait_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579887712,
      "name": "add_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void add_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579884096,
      "name": "add_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:18",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged_do_scan",
        "mm/memcontrol.c:memcg_event_ptable_queue_proc",
        "fs/select.c:__pollwait",
        "fs/dcache.c:d_alloc_parallel",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/signalfd.c:signalfd_dequeue",
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/aio.c:aio_poll_queue_proc",
        "fs/aio.c:aio_poll_complete_work",
        "fs/io_uring.c:__io_queue_proc",
        "fs/io_uring.c:io_poll_rewait",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_ring_recv",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/vfio/virqfd.c:virqfd_ptable_queue_proc",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:inet_wait_for_connect",
        "net/mptcp/protocol.c:mptcp_wait_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579884096,
      "name": "add_wait_queue",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void add_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579893120,
      "name": "add_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:18",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region_locked",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_ptable_queue_proc",
        "fs/select.c:__pollwait",
        "fs/dcache.c:d_alloc_parallel",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/signalfd.c:signalfd_dequeue",
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/aio.c:aio_poll_queue_proc",
        "fs/aio.c:aio_poll_complete_work",
        "fs/io_uring.c:__io_queue_proc",
        "fs/io_uring.c:io_poll_task_func",
        "fs/io_uring.c:io_poll_rewait",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_ring_recv",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/vfio/virqfd.c:virqfd_ptable_queue_proc",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/core/skmsg.c:sk_msg_wait_data",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/mptcp/protocol.c:mptcp_wait_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893120,
      "name": "add_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void add_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008032,
      "name": "add_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:18",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region_locked",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_ptable_queue_proc",
        "fs/select.c:__pollwait",
        "fs/dcache.c:d_alloc_parallel",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/signalfd.c:signalfd_dequeue",
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/aio.c:aio_poll_queue_proc",
        "fs/io_uring.c:__io_queue_proc",
        "fs/io_uring.c:io_poll_task_func",
        "fs/io_uring.c:io_poll_rewait",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/vfio/virqfd.c:virqfd_ptable_queue_proc",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_msg_wait_data",
        "net/ipv4/udp_bpf.c:udp_msg_wait_data",
        "net/unix/unix_bpf.c:unix_msg_wait_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008032,
      "name": "add_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void add_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580161568,
      "name": "add_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:17",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region_locked",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_ptable_queue_proc",
        "fs/select.c:__pollwait",
        "fs/dcache.c:d_alloc_parallel",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/signalfd.c:signalfd_dequeue",
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/aio.c:aio_poll_queue_proc",
        "io_uring/io_uring.c:__io_queue_proc",
        "drivers/pci/vgaarb.c:vga_get",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/net/tun.c:tun_ring_recv",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/vfio/virqfd.c:virqfd_ptable_queue_proc",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_msg_wait_data",
        "net/ipv4/udp_bpf.c:udp_bpf_recvmsg",
        "net/unix/unix_bpf.c:unix_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580161568,
      "name": "add_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void add_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580337872,
      "name": "add_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:17",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region_locked",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_ptable_queue_proc",
        "fs/select.c:__pollwait",
        "fs/dcache.c:d_alloc_parallel",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/signalfd.c:signalfd_dequeue",
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/aio.c:aio_poll_queue_proc",
        "io_uring/poll.c:__io_queue_proc",
        "drivers/pci/vgaarb.c:vga_get",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/net/tun.c:tun_ring_recv",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:inet_wait_for_connect",
        "net/ipv4/tcp_bpf.c:tcp_msg_wait_data",
        "net/ipv4/udp_bpf.c:udp_msg_wait_data",
        "net/unix/unix_bpf.c:unix_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580337872,
      "name": "add_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void add_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580404864,
      "name": "add_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:17",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region_locked",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_ptable_queue_proc",
        "fs/select.c:__pollwait",
        "fs/dcache.c:d_alloc_parallel",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/signalfd.c:signalfd_dequeue",
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/aio.c:aio_poll_queue_proc",
        "io_uring/poll.c:__io_queue_proc",
        "drivers/pci/vgaarb.c:vga_get",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/net/tun.c:tun_ring_recv",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:inet_wait_for_connect",
        "net/ipv4/tcp_bpf.c:tcp_msg_wait_data",
        "net/ipv4/udp_bpf.c:udp_msg_wait_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580404864,
      "name": "add_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void add_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580461488,
      "name": "add_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:17",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region_locked",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_ptable_queue_proc",
        "fs/select.c:__pollwait",
        "fs/dcache.c:d_alloc_parallel",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/signalfd.c:signalfd_dequeue",
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/aio.c:aio_poll_queue_proc",
        "io_uring/poll.c:__io_queue_proc",
        "io_uring/waitid.c:io_waitid",
        "io_uring/waitid.c:io_waitid_cb",
        "drivers/pci/vgaarb.c:vga_get",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/net/tun.c:tun_ring_recv",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:inet_wait_for_connect",
        "net/ipv4/tcp_bpf.c:tcp_msg_wait_data",
        "net/ipv4/udp_bpf.c:udp_msg_wait_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580461488,
      "name": "add_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void add_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491043168,
      "name": "add_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:18",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/eventfd.c:irqfd_ptable_queue_proc",
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_ptable_queue_proc",
        "fs/select.c:__pollwait",
        "fs/dcache.c:d_alloc_parallel",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/signalfd.c:signalfd_read",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/aio.c:aio_poll_queue_proc",
        "fs/aio.c:aio_poll_complete_work",
        "fs/io_uring.c:io_poll_queue_proc",
        "fs/io_uring.c:io_poll_complete_work",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491043168,
      "name": "add_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void add_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225048944,
      "name": "add_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:18",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/memcontrol.c:memcg_event_ptable_queue_proc",
        "fs/select.c:__pollwait",
        "fs/dcache.c:d_alloc_parallel",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/signalfd.c:signalfd_read",
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/aio.c:aio_poll_queue_proc",
        "fs/aio.c:aio_poll_complete_work",
        "fs/io_uring.c:io_poll_queue_proc",
        "fs/io_uring.c:io_poll_complete_work",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "sound/core/control.c:snd_ctl_read",
        "sound/core/timer.c:snd_timer_user_read",
        "sound/core/pcm_native.c:snd_pcm_drain",
        "sound/core/pcm_lib.c:__snd_pcm_lib_xfer",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225048944,
      "name": "add_wait_queue",
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
void add_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283918336,
      "name": "add_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:18",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_ptable_queue_proc",
        "fs/select.c:__pollwait",
        "fs/dcache.c:d_alloc_parallel",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/signalfd.c:signalfd_read",
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/aio.c:aio_poll_queue_proc",
        "fs/aio.c:aio_poll_complete_work",
        "fs/io_uring.c:io_poll_queue_proc",
        "fs/io_uring.c:io_poll_complete_work",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/vfio/virqfd.c:virqfd_ptable_queue_proc",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283918336,
      "name": "add_wait_queue",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void add_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271640332,
      "name": "add_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:18",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/memcontrol.c:memcg_event_ptable_queue_proc",
        "fs/select.c:__pollwait",
        "fs/dcache.c:d_alloc_parallel",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/signalfd.c:signalfd_read",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/aio.c:aio_poll_queue_proc",
        "fs/aio.c:aio_poll_complete_work",
        "fs/io_uring.c:io_poll_queue_proc",
        "fs/io_uring.c:io_poll_complete_work",
        "lib/sbitmap.c:sbitmap_add_wait_queue",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271640332,
      "name": "add_wait_queue",
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
void add_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579821376,
      "name": "add_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:18",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_ptable_queue_proc",
        "fs/select.c:__pollwait",
        "fs/dcache.c:d_alloc_parallel",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/signalfd.c:signalfd_read",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/aio.c:aio_poll_queue_proc",
        "fs/aio.c:aio_poll_complete_work",
        "fs/io_uring.c:io_poll_queue_proc",
        "fs/io_uring.c:io_poll_complete_work",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579821376,
      "name": "add_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void add_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579755984,
      "name": "add_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:18",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_ptable_queue_proc",
        "fs/select.c:__pollwait",
        "fs/dcache.c:d_alloc_parallel",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/signalfd.c:signalfd_read",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/aio.c:aio_poll_queue_proc",
        "fs/aio.c:aio_poll_complete_work",
        "fs/io_uring.c:io_poll_queue_proc",
        "fs/io_uring.c:io_poll_complete_work",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/vfio/virqfd.c:virqfd_ptable_queue_proc",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579755984,
      "name": "add_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void add_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579809392,
      "name": "add_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:18",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_ptable_queue_proc",
        "fs/select.c:__pollwait",
        "fs/dcache.c:d_alloc_parallel",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/signalfd.c:signalfd_read",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/aio.c:aio_poll_queue_proc",
        "fs/aio.c:aio_poll_complete_work",
        "fs/io_uring.c:io_poll_queue_proc",
        "fs/io_uring.c:io_poll_complete_work",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/vfio/virqfd.c:virqfd_ptable_queue_proc",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579809392,
      "name": "add_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void add_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "add_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579854544,
      "name": "add_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:18",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_ptable_queue_proc",
        "fs/select.c:__pollwait",
        "fs/dcache.c:d_alloc_parallel",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_ptable_queue_proc",
        "fs/signalfd.c:signalfd_read",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/aio.c:aio_poll_queue_proc",
        "fs/aio.c:aio_poll_complete_work",
        "fs/io_uring.c:io_poll_queue_proc",
        "fs/io_uring.c:io_poll_complete_work",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/vfio/virqfd.c:virqfd_ptable_queue_proc",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579854544,
      "name": "add_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
<b>Param added. </b>
<code>struct wait_queue_head * wq_head</code>
</li>
<li>
<b>Param added. </b>
<code>struct wait_queue_entry * wq_entry</code>
</li>
<li>
<b>Param removed. </b>
<code>wait_queue_head_t * q</code>
</li>
<li>
<b>Param removed. </b>
<code>wait_queue_t * wait</code>
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
