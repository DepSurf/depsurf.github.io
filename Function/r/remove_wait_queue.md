# Function: <code>remove_wait_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void remove_wait_queue(wait_queue_head_t * q, wait_queue_t * wait)
```

```json
{
  "name": "remove_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579644576,
      "name": "remove_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:45",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:audit_log_start",
        "mm/huge_memory.c:khugepaged",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/select.c:poll_freewait",
        "fs/select.c:poll_freewait",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/signalfd.c:signalfd_read",
        "drivers/virtio/virtio_balloon.c:balloon",
        "drivers/virtio/virtio_balloon.c:balloon",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/rtc-dev.c:rtc_dev_read",
        "drivers/md/dm.c:dm_wait_for_completion",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644576,
      "name": "remove_wait_queue",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void remove_wait_queue(wait_queue_head_t * q, wait_queue_t * wait)
```

```json
{
  "name": "remove_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579659312,
      "name": "remove_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:45",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "kernel/audit.c:audit_log_start",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/select.c:poll_freewait",
        "fs/select.c:poll_freewait",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/signalfd.c:signalfd_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/rtc-dev.c:rtc_dev_read",
        "drivers/md/dm.c:dm_wait_for_completion",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579659312,
      "name": "remove_wait_queue",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void remove_wait_queue(wait_queue_head_t * q, wait_queue_t * wait)
```

```json
{
  "name": "remove_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579683856,
      "name": "remove_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:45",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/select.c:poll_freewait",
        "fs/select.c:poll_freewait",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/signalfd.c:signalfd_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/rtc-dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683856,
      "name": "remove_wait_queue",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "remove_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579669712,
      "name": "remove_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:46",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/select.c:poll_freewait",
        "fs/select.c:poll_freewait",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/signalfd.c:signalfd_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/rtc-dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579669712,
      "name": "remove_wait_queue",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "remove_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579700160,
      "name": "remove_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:46",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/select.c:poll_freewait",
        "fs/select.c:poll_freewait",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/signalfd.c:signalfd_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/rtc-dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579700160,
      "name": "remove_wait_queue",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "remove_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579734272,
      "name": "remove_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:39",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "kernel/bpf/sockmap.c:bpf_tcp_recvmsg",
        "kernel/bpf/sockmap.c:bpf_tcp_recvmsg",
        "kernel/bpf/sockmap.c:bpf_tcp_recvmsg",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/select.c:poll_freewait",
        "fs/select.c:poll_freewait",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/signalfd.c:signalfd_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/rtc-dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579734272,
      "name": "remove_wait_queue",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "remove_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579773952,
      "name": "remove_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:39",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/select.c:poll_freewait",
        "fs/select.c:poll_freewait",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/signalfd.c:signalfd_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579773952,
      "name": "remove_wait_queue",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "remove_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579801616,
      "name": "remove_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:40",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/select.c:poll_freewait",
        "fs/select.c:poll_freewait",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/signalfd.c:signalfd_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579801616,
      "name": "remove_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void remove_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "remove_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579849184,
      "name": "remove_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:40",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/select.c:poll_freewait",
        "fs/select.c:poll_freewait",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/signalfd.c:signalfd_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579849184,
      "name": "remove_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void remove_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "remove_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579887872,
      "name": "remove_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:40",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged_do_scan",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/select.c:poll_freewait",
        "fs/select.c:poll_freewait",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/signalfd.c:signalfd_dequeue",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
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
      "addr": 18446744071579887872,
      "name": "remove_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void remove_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "remove_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579882112,
      "name": "remove_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:51",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged_do_scan",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/select.c:poll_freewait",
        "fs/select.c:poll_freewait",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/signalfd.c:signalfd_dequeue",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_ring_recv",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
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
      "addr": 18446744071579882112,
      "name": "remove_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void remove_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "remove_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579891264,
      "name": "remove_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:51",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region_locked",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/select.c:poll_freewait",
        "fs/select.c:poll_freewait",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/signalfd.c:signalfd_dequeue",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_ring_recv",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/core/skmsg.c:sk_msg_wait_data",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/mptcp/protocol.c:mptcp_wait_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579891264,
      "name": "remove_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void remove_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "remove_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580006192,
      "name": "remove_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:51",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region_locked",
        "kernel/audit.c:audit_receive",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/select.c:poll_freewait",
        "fs/select.c:poll_freewait",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/signalfd.c:signalfd_dequeue",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_msg_wait_data",
        "net/ipv4/udp_bpf.c:udp_msg_wait_data",
        "net/unix/unix_bpf.c:unix_msg_wait_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580006192,
      "name": "remove_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void remove_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "remove_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580137888,
      "name": "remove_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:50",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region_locked",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:audit_receive",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/select.c:poll_freewait",
        "fs/select.c:poll_freewait",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_free",
        "fs/eventpoll.c:ep_remove",
        "fs/signalfd.c:signalfd_dequeue",
        "drivers/pci/vgaarb.c:vga_get",
        "drivers/pci/vgaarb.c:vga_get",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/net/tun.c:tun_ring_recv",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_msg_wait_data",
        "net/ipv4/udp_bpf.c:udp_bpf_recvmsg",
        "net/ipv4/udp_bpf.c:udp_bpf_recvmsg",
        "net/unix/unix_bpf.c:unix_bpf_recvmsg",
        "net/unix/unix_bpf.c:unix_bpf_recvmsg",
        "net/unix/unix_bpf.c:unix_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580137888,
      "name": "remove_wait_queue",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "remove_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580312592,
      "name": "remove_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:50",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region_locked",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:audit_receive",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/select.c:poll_freewait",
        "fs/select.c:poll_freewait",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_free",
        "fs/eventpoll.c:ep_remove",
        "fs/signalfd.c:signalfd_dequeue",
        "drivers/pci/vgaarb.c:vga_get",
        "drivers/pci/vgaarb.c:vga_get",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/net/tun.c:tun_ring_recv",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:inet_wait_for_connect",
        "net/ipv4/tcp_bpf.c:tcp_msg_wait_data",
        "net/ipv4/udp_bpf.c:udp_msg_wait_data",
        "net/unix/unix_bpf.c:unix_bpf_recvmsg",
        "net/unix/unix_bpf.c:unix_bpf_recvmsg",
        "net/unix/unix_bpf.c:unix_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580312592,
      "name": "remove_wait_queue",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "remove_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580379264,
      "name": "remove_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:50",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region_locked",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:audit_receive",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/select.c:poll_freewait",
        "fs/select.c:poll_freewait",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_clear_and_put",
        "fs/eventpoll.c:__ep_remove",
        "fs/signalfd.c:signalfd_dequeue",
        "drivers/pci/vgaarb.c:vga_get",
        "drivers/pci/vgaarb.c:vga_get",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/net/tun.c:tun_ring_recv",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
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
      "addr": 18446744071580379264,
      "name": "remove_wait_queue",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "remove_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580437248,
      "name": "remove_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:50",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region_locked",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:audit_receive",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/select.c:poll_freewait",
        "fs/select.c:poll_freewait",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:ep_clear_and_put",
        "fs/eventpoll.c:__ep_remove",
        "fs/signalfd.c:signalfd_dequeue",
        "io_uring/waitid.c:io_waitid",
        "io_uring/waitid.c:io_waitid",
        "io_uring/waitid.c:io_waitid_cb",
        "io_uring/waitid.c:io_waitid_cb",
        "drivers/pci/vgaarb.c:vga_get",
        "drivers/pci/vgaarb.c:vga_get",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/net/tun.c:tun_ring_recv",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/stream.c:sk_stream_wait_connect",
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
      "addr": 18446744071580437248,
      "name": "remove_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void remove_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "remove_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491042784,
      "name": "remove_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:40",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/select.c:poll_freewait",
        "fs/select.c:poll_freewait",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/signalfd.c:signalfd_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491042784,
      "name": "remove_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void remove_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "remove_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225049112,
      "name": "remove_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:40",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/select.c:poll_freewait",
        "fs/select.c:poll_freewait",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/signalfd.c:signalfd_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "sound/core/control.c:snd_ctl_read",
        "sound/core/timer.c:snd_timer_user_read",
        "sound/core/pcm_native.c:snd_pcm_drain",
        "sound/core/pcm_lib.c:__snd_pcm_lib_xfer",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225049112,
      "name": "remove_wait_queue",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "remove_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283918624,
      "name": "remove_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:40",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/select.c:poll_freewait",
        "fs/select.c:poll_freewait",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/signalfd.c:signalfd_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283918624,
      "name": "remove_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void remove_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "remove_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271640518,
      "name": "remove_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:40",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/select.c:poll_freewait",
        "fs/select.c:poll_freewait",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/signalfd.c:signalfd_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271640518,
      "name": "remove_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void remove_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "remove_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579821536,
      "name": "remove_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:40",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/select.c:poll_freewait",
        "fs/select.c:poll_freewait",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/signalfd.c:signalfd_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579821536,
      "name": "remove_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void remove_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "remove_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579756144,
      "name": "remove_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:40",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/select.c:poll_freewait",
        "fs/select.c:poll_freewait",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/signalfd.c:signalfd_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579756144,
      "name": "remove_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void remove_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "remove_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579809552,
      "name": "remove_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:40",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/select.c:poll_freewait",
        "fs/select.c:poll_freewait",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/signalfd.c:signalfd_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579809552,
      "name": "remove_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void remove_wait_queue(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry)
```

```json
{
  "name": "remove_wait_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579854704,
      "name": "remove_wait_queue",
      "external": true,
      "loc": "kernel/sched/wait.c:40",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_wait",
        "kernel/resource.c:__request_region",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memcg_event_remove",
        "fs/select.c:poll_freewait",
        "fs/select.c:poll_freewait",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/signalfd.c:signalfd_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/vt/selection.c:paste_selection",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/char/hpet.c:hpet_read",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/gpu/vga/vgaarb.c:vga_get",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/ppp/ppp_generic.c:ppp_read",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/usb/core/devio.c:reap_as",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579854704,
      "name": "remove_wait_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
