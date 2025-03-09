# Function: <code>wait_woken</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int wait_woken(wait_queue_t * wait, unsigned int mode, long int timeout)
```

```json
{
  "name": "wait_woken",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579646016,
      "name": "wait_woken",
      "external": true,
      "loc": "kernel/sched/wait.c:326",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "drivers/virtio/virtio_balloon.c:balloon",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579646016,
      "name": "wait_woken",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
long int wait_woken(wait_queue_t * wait, unsigned int mode, long int timeout)
```

```json
{
  "name": "wait_woken",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579660752,
      "name": "wait_woken",
      "external": true,
      "loc": "kernel/sched/wait.c:326",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660752,
      "name": "wait_woken",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
long int wait_woken(wait_queue_t * wait, unsigned int mode, long int timeout)
```

```json
{
  "name": "wait_woken",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579684912,
      "name": "wait_woken",
      "external": true,
      "loc": "kernel/sched/wait.c:314",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684912,
      "name": "wait_woken",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry * wq_entry, unsigned int mode, long int timeout)
```

```json
{
  "name": "wait_woken",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579671200,
      "name": "wait_woken",
      "external": true,
      "loc": "kernel/sched/wait.c:355",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671200,
      "name": "wait_woken",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry * wq_entry, unsigned int mode, long int timeout)
```

```json
{
  "name": "wait_woken",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579701952,
      "name": "wait_woken",
      "external": true,
      "loc": "kernel/sched/wait.c:410",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579701952,
      "name": "wait_woken",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry * wq_entry, unsigned int mode, long int timeout)
```

```json
{
  "name": "wait_woken",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579736080,
      "name": "wait_woken",
      "external": true,
      "loc": "kernel/sched/wait.c:407",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/sockmap.c:bpf_tcp_recvmsg",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579736080,
      "name": "wait_woken",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry * wq_entry, unsigned int mode, long int timeout)
```

```json
{
  "name": "wait_woken",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579775760,
      "name": "wait_woken",
      "external": true,
      "loc": "kernel/sched/wait.c:409",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579775760,
      "name": "wait_woken",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
long int wait_woken(struct wait_queue_entry * wq_entry, unsigned int mode, long int timeout)
```

```json
{
  "name": "wait_woken",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579803424,
      "name": "wait_woken",
      "external": true,
      "loc": "kernel/sched/wait.c:406",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579803424,
      "name": "wait_woken",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
long int wait_woken(struct wait_queue_entry * wq_entry, unsigned int mode, long int timeout)
```

```json
{
  "name": "wait_woken",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579850992,
      "name": "wait_woken",
      "external": true,
      "loc": "kernel/sched/wait.c:406",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579850992,
      "name": "wait_woken",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
long int wait_woken(struct wait_queue_entry * wq_entry, unsigned int mode, long int timeout)
```

```json
{
  "name": "wait_woken",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579889120,
      "name": "wait_woken",
      "external": true,
      "loc": "kernel/sched/wait.c:423",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/ipv4/af_inet.c:inet_wait_for_connect",
        "net/mptcp/protocol.c:mptcp_wait_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579889120,
      "name": "wait_woken",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
long int wait_woken(struct wait_queue_entry * wq_entry, unsigned int mode, long int timeout)
```

```json
{
  "name": "wait_woken",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579883232,
      "name": "wait_woken",
      "external": true,
      "loc": "kernel/sched/wait.c:438",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/ipv4/af_inet.c:inet_wait_for_connect",
        "net/mptcp/protocol.c:mptcp_wait_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579883232,
      "name": "wait_woken",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
long int wait_woken(struct wait_queue_entry * wq_entry, unsigned int mode, long int timeout)
```

```json
{
  "name": "wait_woken",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579892416,
      "name": "wait_woken",
      "external": true,
      "loc": "kernel/sched/wait.c:443",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/core/skmsg.c:sk_msg_wait_data",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/mptcp/protocol.c:mptcp_wait_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892416,
      "name": "wait_woken",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
long int wait_woken(struct wait_queue_entry * wq_entry, unsigned int mode, long int timeout)
```

```json
{
  "name": "wait_woken",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580007376,
      "name": "wait_woken",
      "external": true,
      "loc": "kernel/sched/wait.c:451",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_msg_wait_data",
        "net/ipv4/udp_bpf.c:udp_msg_wait_data",
        "net/unix/unix_bpf.c:unix_msg_wait_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580007376,
      "name": "wait_woken",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
long int wait_woken(struct wait_queue_entry * wq_entry, unsigned int mode, long int timeout)
```

```json
{
  "name": "wait_woken",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580145616,
      "name": "wait_woken",
      "external": true,
      "loc": "kernel/sched/wait.c:450",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_msg_wait_data",
        "net/ipv4/udp_bpf.c:udp_bpf_recvmsg",
        "net/unix/unix_bpf.c:unix_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580145616,
      "name": "wait_woken",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry * wq_entry, unsigned int mode, long int timeout)
```

```json
{
  "name": "wait_woken",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580320576,
      "name": "wait_woken",
      "external": true,
      "loc": "kernel/sched/wait.c:454",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/ipv4/af_inet.c:inet_wait_for_connect",
        "net/ipv4/tcp_bpf.c:tcp_msg_wait_data",
        "net/ipv4/udp_bpf.c:udp_msg_wait_data",
        "net/unix/unix_bpf.c:unix_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580320576,
      "name": "wait_woken",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry * wq_entry, unsigned int mode, long int timeout)
```

```json
{
  "name": "wait_woken",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580387840,
      "name": "wait_woken",
      "external": true,
      "loc": "kernel/sched/wait.c:449",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/ipv4/af_inet.c:inet_wait_for_connect",
        "net/ipv4/tcp_bpf.c:tcp_msg_wait_data",
        "net/ipv4/udp_bpf.c:udp_msg_wait_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580387840,
      "name": "wait_woken",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
long int wait_woken(struct wait_queue_entry * wq_entry, unsigned int mode, long int timeout)
```

```json
{
  "name": "wait_woken",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580444448,
      "name": "wait_woken",
      "external": true,
      "loc": "kernel/sched/wait.c:414",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/ipv4/af_inet.c:inet_wait_for_connect",
        "net/ipv4/tcp_bpf.c:tcp_msg_wait_data",
        "net/ipv4/udp_bpf.c:udp_msg_wait_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580444448,
      "name": "wait_woken",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
long int wait_woken(struct wait_queue_entry * wq_entry, unsigned int mode, long int timeout)
```

```json
{
  "name": "wait_woken",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491041088,
      "name": "wait_woken",
      "external": true,
      "loc": "kernel/sched/wait.c:406",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491041088,
      "name": "wait_woken",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
long int wait_woken(struct wait_queue_entry * wq_entry, unsigned int mode, long int timeout)
```

```json
{
  "name": "wait_woken",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225051480,
      "name": "wait_woken",
      "external": true,
      "loc": "kernel/sched/wait.c:406",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225051480,
      "name": "wait_woken",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry * wq_entry, unsigned int mode, long int timeout)
```

```json
{
  "name": "wait_woken",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283921568,
      "name": "wait_woken",
      "external": true,
      "loc": "kernel/sched/wait.c:406",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283921568,
      "name": "wait_woken",
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
long int wait_woken(struct wait_queue_entry * wq_entry, unsigned int mode, long int timeout)
```

```json
{
  "name": "wait_woken",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271642260,
      "name": "wait_woken",
      "external": true,
      "loc": "kernel/sched/wait.c:406",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271642260,
      "name": "wait_woken",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry * wq_entry, unsigned int mode, long int timeout)
```

```json
{
  "name": "wait_woken",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579823344,
      "name": "wait_woken",
      "external": true,
      "loc": "kernel/sched/wait.c:406",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579823344,
      "name": "wait_woken",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
long int wait_woken(struct wait_queue_entry * wq_entry, unsigned int mode, long int timeout)
```

```json
{
  "name": "wait_woken",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579757936,
      "name": "wait_woken",
      "external": true,
      "loc": "kernel/sched/wait.c:406",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579757936,
      "name": "wait_woken",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
long int wait_woken(struct wait_queue_entry * wq_entry, unsigned int mode, long int timeout)
```

```json
{
  "name": "wait_woken",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579811360,
      "name": "wait_woken",
      "external": true,
      "loc": "kernel/sched/wait.c:406",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579811360,
      "name": "wait_woken",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
long int wait_woken(struct wait_queue_entry * wq_entry, unsigned int mode, long int timeout)
```

```json
{
  "name": "wait_woken",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579856496,
      "name": "wait_woken",
      "external": true,
      "loc": "kernel/sched/wait.c:406",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "drivers/vfio/vfio.c:vfio_del_group_dev",
        "net/core/sock.c:sk_wait_data",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579856496,
      "name": "wait_woken",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
<code>struct wait_queue_entry * wq_entry</code>
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
