# Function: <code>kill_fasync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void kill_fasync(struct fasync_struct * * fp, int sig, int band)
```

```json
{
  "name": "kill_fasync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581070576,
      "name": "kill_fasync",
      "external": true,
      "loc": "fs/fcntl.c:723",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_wakeup",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_release",
        "fs/splice.c:wakeup_pipe_readers",
        "fs/splice.c:splice_to_pipe",
        "fs/splice.c:wakeup_pipe_writers",
        "fs/notify/notification.c:fsnotify_add_event",
        "fs/locks.c:lease_break_callback",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:queue_request",
        "fs/fuse/dev.c:queue_interrupt",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_queue_forget",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/hpet.c:hpet_interrupt",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/mousedev.c:mousedev_notify_readers",
        "drivers/input/mousedev.c:mousedev_write",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/rtc/interface.c:rtc_handle_legacy_irq",
        "net/socket.c:sock_wake_async",
        "net/socket.c:sock_wake_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581070576,
      "name": "kill_fasync",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void kill_fasync(struct fasync_struct * * fp, int sig, int band)
```

```json
{
  "name": "kill_fasync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581232496,
      "name": "kill_fasync",
      "external": true,
      "loc": "fs/fcntl.c:727",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_wakeup",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:wakeup_pipe_writers",
        "fs/splice.c:splice_to_pipe",
        "fs/splice.c:wakeup_pipe_readers",
        "fs/notify/notification.c:fsnotify_add_event",
        "fs/locks.c:lease_break_callback",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:queue_interrupt",
        "fs/fuse/dev.c:fuse_queue_forget",
        "fs/fuse/dev.c:queue_request",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_write_wakeup",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/hpet.c:hpet_interrupt",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/mousedev.c:mousedev_write",
        "drivers/input/mousedev.c:mousedev_notify_readers",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/rtc/interface.c:rtc_handle_legacy_irq",
        "net/socket.c:sock_wake_async",
        "net/socket.c:sock_wake_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581232496,
      "name": "kill_fasync",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void kill_fasync(struct fasync_struct * * fp, int sig, int band)
```

```json
{
  "name": "kill_fasync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581310304,
      "name": "kill_fasync",
      "external": true,
      "loc": "fs/fcntl.c:727",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_wakeup",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:wakeup_pipe_writers",
        "fs/splice.c:wakeup_pipe_readers",
        "fs/notify/notification.c:fsnotify_add_event",
        "fs/locks.c:lease_break_callback",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_queue_forget",
        "fs/fuse/dev.c:queue_request",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_write_wakeup",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/hpet.c:hpet_interrupt",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/mousedev.c:mousedev_write",
        "drivers/input/mousedev.c:mousedev_notify_readers",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/rtc/interface.c:rtc_handle_legacy_irq",
        "net/socket.c:sock_wake_async",
        "net/socket.c:sock_wake_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581310304,
      "name": "kill_fasync",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void kill_fasync(struct fasync_struct * * fp, int sig, int band)
```

```json
{
  "name": "kill_fasync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581361936,
      "name": "kill_fasync",
      "external": true,
      "loc": "fs/fcntl.c:997",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_wakeup",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:wakeup_pipe_writers",
        "fs/splice.c:wakeup_pipe_readers",
        "fs/notify/notification.c:fsnotify_add_event",
        "fs/locks.c:lease_break_callback",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_queue_forget",
        "fs/fuse/dev.c:queue_request",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_write_wakeup",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/hpet.c:hpet_interrupt",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/mousedev.c:mousedev_write",
        "drivers/input/mousedev.c:mousedev_notify_readers",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/rtc/interface.c:rtc_handle_legacy_irq",
        "net/socket.c:sock_wake_async",
        "net/socket.c:sock_wake_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581361936,
      "name": "kill_fasync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void kill_fasync(struct fasync_struct * * fp, int sig, int band)
```

```json
{
  "name": "kill_fasync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581503408,
      "name": "kill_fasync",
      "external": true,
      "loc": "fs/fcntl.c:1007",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_wakeup",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:wakeup_pipe_writers",
        "fs/splice.c:wakeup_pipe_readers",
        "fs/notify/notification.c:fsnotify_add_event",
        "fs/locks.c:lease_break_callback",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_queue_forget",
        "fs/fuse/dev.c:queue_request",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_write_wakeup",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/hpet.c:hpet_interrupt",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/mousedev.c:mousedev_write",
        "drivers/input/mousedev.c:mousedev_notify_readers",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/rtc/interface.c:rtc_handle_legacy_irq",
        "net/socket.c:sock_wake_async",
        "net/socket.c:sock_wake_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581503408,
      "name": "kill_fasync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void kill_fasync(struct fasync_struct * * fp, int sig, int band)
```

```json
{
  "name": "kill_fasync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kill_fasync",
      "external": true,
      "loc": "fs/fcntl.c:1013",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_wakeup",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:wakeup_pipe_writers",
        "fs/splice.c:wakeup_pipe_readers",
        "fs/notify/notification.c:fsnotify_add_event",
        "fs/locks.c:lease_break_callback",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:queue_interrupt",
        "fs/fuse/dev.c:fuse_queue_forget",
        "fs/fuse/dev.c:queue_request",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_write_wakeup",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/hpet.c:hpet_interrupt",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/net/tun.c:tun_xdp_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/mousedev.c:mousedev_write",
        "drivers/input/mousedev.c:mousedev_notify_readers",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/rtc/interface.c:rtc_handle_legacy_irq",
        "drivers/pps/kapi.c:pps_event",
        "net/socket.c:sock_wake_async",
        "net/socket.c:sock_wake_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581661026,
      "name": "kill_fasync.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581659936,
      "name": "kill_fasync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void kill_fasync(struct fasync_struct * * fp, int sig, int band)
```

```json
{
  "name": "kill_fasync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kill_fasync",
      "external": true,
      "loc": "fs/fcntl.c:1017",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_wakeup",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:wakeup_pipe_writers",
        "fs/splice.c:wakeup_pipe_readers",
        "fs/notify/notification.c:fsnotify_add_event",
        "fs/locks.c:lease_break_callback",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:queue_interrupt",
        "fs/fuse/dev.c:fuse_queue_forget",
        "fs/fuse/dev.c:queue_request",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_write_wakeup",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/hpet.c:hpet_interrupt",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/net/tun.c:tun_xdp_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/mousedev.c:mousedev_write",
        "drivers/input/mousedev.c:mousedev_notify_readers",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/rtc/interface.c:rtc_handle_legacy_irq",
        "drivers/pps/kapi.c:pps_event",
        "net/socket.c:sock_wake_async",
        "net/socket.c:sock_wake_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581747426,
      "name": "kill_fasync.cold.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581746256,
      "name": "kill_fasync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kill_fasync(struct fasync_struct * * fp, int sig, int band)
```

```json
{
  "name": "kill_fasync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581863611,
      "name": "kill_fasync",
      "external": true,
      "loc": "fs/fcntl.c:1017",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_wakeup",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:wakeup_pipe_writers",
        "fs/splice.c:wakeup_pipe_readers",
        "fs/notify/notification.c:fsnotify_add_event",
        "fs/io_uring.c:io_commit_cqring",
        "fs/locks.c:lease_break_callback",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:queue_interrupt",
        "fs/fuse/dev.c:fuse_queue_forget",
        "fs/fuse/dev.c:queue_request",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_write_wakeup",
        "drivers/tty/vt/vc_screen.c:vcs_notifier",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/hpet.c:hpet_interrupt",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/mousedev.c:mousedev_write",
        "drivers/input/mousedev.c:mousedev_notify_readers",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/rtc/interface.c:rtc_handle_legacy_irq",
        "drivers/pps/kapi.c:pps_event",
        "net/socket.c:sock_wake_async",
        "net/socket.c:sock_wake_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581864750,
      "name": "kill_fasync.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581863600,
      "name": "kill_fasync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kill_fasync(struct fasync_struct * * fp, int sig, int band)
```

```json
{
  "name": "kill_fasync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581935979,
      "name": "kill_fasync",
      "external": true,
      "loc": "fs/fcntl.c:1017",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_wakeup",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:wakeup_pipe_writers",
        "fs/splice.c:wakeup_pipe_readers",
        "fs/notify/notification.c:fsnotify_add_event",
        "fs/io_uring.c:io_commit_cqring",
        "fs/locks.c:lease_break_callback",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_wake_and_unlock",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_write_wakeup",
        "drivers/tty/vt/vc_screen.c:vcs_notifier",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/hpet.c:hpet_interrupt",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/mousedev.c:mousedev_write",
        "drivers/input/mousedev.c:mousedev_notify_readers",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/rtc/interface.c:rtc_handle_legacy_irq",
        "drivers/pps/kapi.c:pps_event",
        "net/socket.c:sock_wake_async",
        "net/socket.c:sock_wake_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581937094,
      "name": "kill_fasync.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581935968,
      "name": "kill_fasync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kill_fasync(struct fasync_struct * * fp, int sig, int band)
```

```json
{
  "name": "kill_fasync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582166011,
      "name": "kill_fasync",
      "external": true,
      "loc": "fs/fcntl.c:1019",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_wakeup",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:do_splice",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:__splice_from_pipe",
        "fs/notify/notification.c:fsnotify_add_event",
        "fs/io_uring.c:io_commit_cqring",
        "fs/locks.c:lease_break_callback",
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_wake_and_unlock",
        "drivers/tty/n_tty.c:__receive_buf",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_write_wakeup",
        "drivers/tty/vt/vc_screen.c:vcs_notifier",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/hpet.c:hpet_interrupt",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/mousedev.c:mousedev_write",
        "drivers/input/mousedev.c:mousedev_notify_readers",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/rtc/interface.c:rtc_uie_update_irq",
        "drivers/rtc/interface.c:rtc_aie_update_irq",
        "drivers/pps/kapi.c:pps_event",
        "net/socket.c:sock_wake_async",
        "net/socket.c:sock_wake_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582167126,
      "name": "kill_fasync.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071582166000,
      "name": "kill_fasync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kill_fasync(struct fasync_struct * * fp, int sig, int band)
```

```json
{
  "name": "kill_fasync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582212475,
      "name": "kill_fasync",
      "external": true,
      "loc": "fs/fcntl.c:1021",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_wakeup",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:do_splice",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:__splice_from_pipe",
        "fs/notify/notification.c:fsnotify_add_event",
        "fs/io_uring.c:io_cqring_ev_posted_iopoll",
        "fs/io_uring.c:io_cqring_ev_posted",
        "fs/locks.c:lease_break_callback",
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_wake_and_unlock",
        "drivers/tty/n_tty.c:__receive_buf",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_write_wakeup",
        "drivers/tty/vt/vc_screen.c:vcs_notifier",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/hpet.c:hpet_interrupt",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/mousedev.c:mousedev_write",
        "drivers/input/mousedev.c:mousedev_notify_readers",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/rtc/interface.c:rtc_uie_update_irq",
        "drivers/rtc/interface.c:rtc_aie_update_irq",
        "drivers/pps/kapi.c:pps_event",
        "net/socket.c:sock_wake_async",
        "net/socket.c:sock_wake_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591339610,
      "name": "kill_fasync.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071582212464,
      "name": "kill_fasync",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kill_fasync(struct fasync_struct * * fp, int sig, int band)
```

```json
{
  "name": "kill_fasync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582237483,
      "name": "kill_fasync",
      "external": true,
      "loc": "fs/fcntl.c:1026",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_wakeup",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:do_tee",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:splice_file_to_pipe",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:__splice_from_pipe",
        "fs/notify/notification.c:fsnotify_add_event",
        "fs/io_uring.c:io_iopoll_complete",
        "fs/io_uring.c:io_cqring_ev_posted",
        "fs/locks.c:lease_break_callback",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_wake_and_unlock",
        "drivers/tty/n_tty.c:__receive_buf",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_write_wakeup",
        "drivers/tty/vt/vc_screen.c:vcs_notifier",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/hpet.c:hpet_interrupt",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/mousedev.c:mousedev_write",
        "drivers/input/mousedev.c:mousedev_notify_readers",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/rtc/interface.c:rtc_uie_update_irq",
        "drivers/rtc/interface.c:rtc_aie_update_irq",
        "drivers/pps/kapi.c:pps_event",
        "net/socket.c:sock_wake_async",
        "net/socket.c:sock_wake_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591282326,
      "name": "kill_fasync.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071582237472,
      "name": "kill_fasync",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kill_fasync(struct fasync_struct * * fp, int sig, int band)
```

```json
{
  "name": "kill_fasync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582556153,
      "name": "kill_fasync",
      "external": true,
      "loc": "fs/fcntl.c:1031",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_wakeup",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:do_tee",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:splice_file_to_pipe",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:__splice_from_pipe",
        "fs/notify/notification.c:fsnotify_add_event",
        "fs/locks.c:lease_break_callback",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_wake_and_unlock",
        "drivers/tty/n_tty.c:__receive_buf",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_write_wakeup",
        "drivers/tty/vt/vc_screen.c:vcs_notifier",
        "drivers/char/random.c:random_ioctl",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/hpet.c:hpet_interrupt",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/mousedev.c:mousedev_write",
        "drivers/input/mousedev.c:mousedev_notify_readers",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/rtc/interface.c:rtc_uie_update_irq",
        "drivers/rtc/interface.c:rtc_aie_update_irq",
        "drivers/pps/kapi.c:pps_event",
        "net/socket.c:sock_wake_async",
        "net/socket.c:sock_wake_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592229527,
      "name": "kill_fasync.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071582556128,
      "name": "kill_fasync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kill_fasync(struct fasync_struct * * fp, int sig, int band)
```

```json
{
  "name": "kill_fasync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583084659,
      "name": "kill_fasync",
      "external": true,
      "loc": "fs/fcntl.c:1009",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_wakeup",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:do_tee",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:splice_file_to_pipe",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:__splice_from_pipe",
        "fs/splice.c:splice_from_pipe_next",
        "fs/notify/notification.c:fsnotify_insert_event",
        "fs/locks.c:lease_break_callback",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_wake_and_unlock",
        "drivers/tty/n_tty.c:__receive_buf",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_write_wakeup",
        "drivers/tty/vt/vc_screen.c:vcs_notifier",
        "drivers/char/random.c:_credit_init_bits",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/hpet.c:hpet_interrupt",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/mousedev.c:mousedev_write",
        "drivers/input/mousedev.c:mousedev_notify_readers",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/rtc/interface.c:rtc_uie_update_irq",
        "drivers/rtc/interface.c:rtc_aie_update_irq",
        "drivers/pps/kapi.c:pps_event",
        "net/socket.c:sock_wake_async",
        "net/socket.c:sock_wake_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594009272,
      "name": "kill_fasync.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071583084624,
      "name": "kill_fasync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void kill_fasync(struct fasync_struct * * fp, int sig, int band)
```

```json
{
  "name": "kill_fasync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583652128,
      "name": "kill_fasync",
      "external": true,
      "loc": "fs/fcntl.c:1010",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_wakeup",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:do_tee",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:splice_file_to_pipe",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:__splice_from_pipe",
        "fs/splice.c:splice_from_pipe_next",
        "fs/notify/notification.c:fsnotify_insert_event",
        "fs/locks.c:lease_break_callback",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_wake_and_unlock",
        "drivers/tty/n_tty.c:__receive_buf",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_write_wakeup",
        "drivers/tty/vt/vc_screen.c:vcs_notifier",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/hpet.c:hpet_interrupt",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/mousedev.c:mousedev_write",
        "drivers/input/mousedev.c:mousedev_notify_readers",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/rtc/interface.c:rtc_uie_update_irq",
        "drivers/rtc/interface.c:rtc_aie_update_irq",
        "drivers/pps/kapi.c:pps_event",
        "net/socket.c:sock_wake_async",
        "net/socket.c:sock_wake_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583652128,
      "name": "kill_fasync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void kill_fasync(struct fasync_struct * * fp, int sig, int band)
```

```json
{
  "name": "kill_fasync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583869280,
      "name": "kill_fasync",
      "external": true,
      "loc": "fs/fcntl.c:1011",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_wakeup",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:do_tee",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:splice_file_to_pipe",
        "fs/splice.c:splice_to_socket",
        "fs/splice.c:splice_to_socket",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:__splice_from_pipe",
        "fs/splice.c:splice_from_pipe_next",
        "fs/notify/notification.c:fsnotify_insert_event",
        "fs/locks.c:lease_break_callback",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_wake_and_unlock",
        "drivers/tty/n_tty.c:__receive_buf",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_write_wakeup",
        "drivers/tty/vt/vc_screen.c:vcs_notifier",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/hpet.c:hpet_interrupt",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/mousedev.c:mousedev_write",
        "drivers/input/mousedev.c:mousedev_notify_readers",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/rtc/interface.c:rtc_uie_update_irq",
        "drivers/rtc/interface.c:rtc_aie_update_irq",
        "drivers/pps/kapi.c:pps_event",
        "net/socket.c:sock_wake_async",
        "net/socket.c:sock_wake_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583869280,
      "name": "kill_fasync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void kill_fasync(struct fasync_struct * * fp, int sig, int band)
```

```json
{
  "name": "kill_fasync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584076320,
      "name": "kill_fasync",
      "external": true,
      "loc": "fs/fcntl.c:1012",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_wakeup",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:do_tee",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:splice_file_to_pipe",
        "fs/splice.c:splice_to_socket",
        "fs/splice.c:splice_to_socket",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:__splice_from_pipe",
        "fs/splice.c:splice_from_pipe_next",
        "fs/notify/notification.c:fsnotify_insert_event",
        "fs/locks.c:lease_break_callback",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_wake_and_unlock",
        "drivers/tty/n_tty.c:__receive_buf",
        "drivers/tty/n_tty.c:n_tty_receive_handle_newline",
        "drivers/tty/n_tty.c:n_tty_write_wakeup",
        "drivers/tty/vt/vc_screen.c:vcs_notifier",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/hpet.c:hpet_interrupt",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/mousedev.c:mousedev_write",
        "drivers/input/mousedev.c:mousedev_notify_readers",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/rtc/interface.c:rtc_uie_update_irq",
        "drivers/rtc/interface.c:rtc_aie_update_irq",
        "drivers/pps/kapi.c:pps_event",
        "net/socket.c:sock_wake_async",
        "net/socket.c:sock_wake_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584076320,
      "name": "kill_fasync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void kill_fasync(struct fasync_struct * * fp, int sig, int band)
```

```json
{
  "name": "kill_fasync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493419640,
      "name": "kill_fasync",
      "external": true,
      "loc": "fs/fcntl.c:1017",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_wakeup",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:wakeup_pipe_writers",
        "fs/splice.c:wakeup_pipe_readers",
        "fs/notify/notification.c:fsnotify_add_event",
        "fs/io_uring.c:io_commit_cqring",
        "fs/locks.c:lease_break_callback",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_wake_and_unlock",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_write_wakeup",
        "drivers/tty/n_tty.c:n_tty_write_wakeup",
        "drivers/tty/vt/vc_screen.c:vcs_notifier",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/mousedev.c:mousedev_write",
        "drivers/input/mousedev.c:mousedev_notify_readers",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/rtc/interface.c:rtc_handle_legacy_irq",
        "drivers/pps/kapi.c:pps_event",
        "net/socket.c:sock_wake_async",
        "net/socket.c:sock_wake_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493419640,
      "name": "kill_fasync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void kill_fasync(struct fasync_struct * * fp, int sig, int band)
```

```json
{
  "name": "kill_fasync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227002592,
      "name": "kill_fasync",
      "external": true,
      "loc": "fs/fcntl.c:1017",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_wakeup",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:wakeup_pipe_writers",
        "fs/splice.c:wakeup_pipe_readers",
        "fs/notify/notification.c:fsnotify_add_event",
        "fs/io_uring.c:io_commit_cqring",
        "fs/locks.c:lease_break_callback",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_wake_and_unlock",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_write_wakeup",
        "drivers/tty/vt/vc_screen.c:vcs_notifier",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/mousedev.c:mousedev_write",
        "drivers/input/mousedev.c:mousedev_notify_readers",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/rtc/interface.c:rtc_handle_legacy_irq",
        "drivers/pps/kapi.c:pps_event",
        "sound/core/control.c:snd_ctl_dev_disconnect",
        "sound/core/timer.c:snd_timer_user_tinterrupt",
        "sound/core/timer.c:snd_timer_user_ccallback",
        "sound/core/timer.c:snd_timer_user_interrupt",
        "sound/core/pcm_lib.c:snd_pcm_period_elapsed",
        "net/socket.c:sock_wake_async",
        "net/socket.c:sock_wake_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227002592,
      "name": "kill_fasync",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void kill_fasync(struct fasync_struct * * fp, int sig, int band)
```

```json
{
  "name": "kill_fasync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286978880,
      "name": "kill_fasync",
      "external": true,
      "loc": "fs/fcntl.c:1017",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_wakeup",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:wakeup_pipe_writers",
        "fs/splice.c:wakeup_pipe_readers",
        "fs/notify/notification.c:fsnotify_add_event",
        "fs/io_uring.c:io_commit_cqring",
        "fs/locks.c:lease_break_callback",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_dev_wake_and_unlock",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_write_wakeup",
        "drivers/tty/vt/vc_screen.c:vcs_notifier",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/mousedev.c:mousedev_write",
        "drivers/input/mousedev.c:mousedev_notify_readers",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/rtc/interface.c:rtc_handle_legacy_irq",
        "drivers/pps/kapi.c:pps_event",
        "net/socket.c:sock_wake_async",
        "net/socket.c:sock_wake_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286978880,
      "name": "kill_fasync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void kill_fasync(struct fasync_struct * * fp, int sig, int band)
```

```json
{
  "name": "kill_fasync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273125306,
      "name": "kill_fasync",
      "external": true,
      "loc": "fs/fcntl.c:1017",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_wakeup",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:wakeup_pipe_writers",
        "fs/splice.c:wakeup_pipe_readers",
        "fs/notify/notification.c:fsnotify_add_event",
        "fs/io_uring.c:io_commit_cqring",
        "fs/locks.c:lease_break_callback",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_wake_and_unlock",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_write_wakeup",
        "drivers/tty/vt/vc_screen.c:vcs_notifier",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/mousedev.c:mousedev_write",
        "drivers/input/mousedev.c:mousedev_notify_readers",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/rtc/interface.c:rtc_handle_legacy_irq",
        "drivers/pps/kapi.c:pps_event",
        "net/socket.c:sock_wake_async",
        "net/socket.c:sock_wake_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273125306,
      "name": "kill_fasync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kill_fasync(struct fasync_struct * * fp, int sig, int band)
```

```json
{
  "name": "kill_fasync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581904715,
      "name": "kill_fasync",
      "external": true,
      "loc": "fs/fcntl.c:1017",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_wakeup",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:wakeup_pipe_writers",
        "fs/splice.c:wakeup_pipe_readers",
        "fs/notify/notification.c:fsnotify_add_event",
        "fs/io_uring.c:io_commit_cqring",
        "fs/locks.c:lease_break_callback",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_wake_and_unlock",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_write_wakeup",
        "drivers/tty/vt/vc_screen.c:vcs_notifier",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/hpet.c:hpet_interrupt",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/mousedev.c:mousedev_write",
        "drivers/input/mousedev.c:mousedev_notify_readers",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/rtc/interface.c:rtc_handle_legacy_irq",
        "drivers/pps/kapi.c:pps_event",
        "net/socket.c:sock_wake_async",
        "net/socket.c:sock_wake_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581905830,
      "name": "kill_fasync.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581904704,
      "name": "kill_fasync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kill_fasync(struct fasync_struct * * fp, int sig, int band)
```

```json
{
  "name": "kill_fasync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581842315,
      "name": "kill_fasync",
      "external": true,
      "loc": "fs/fcntl.c:1017",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_wakeup",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:wakeup_pipe_writers",
        "fs/splice.c:wakeup_pipe_readers",
        "fs/notify/notification.c:fsnotify_add_event",
        "fs/io_uring.c:io_commit_cqring",
        "fs/locks.c:lease_break_callback",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_wake_and_unlock",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_write_wakeup",
        "drivers/tty/vt/vc_screen.c:vcs_notifier",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/hpet.c:hpet_interrupt",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/mousedev.c:mousedev_write",
        "drivers/input/mousedev.c:mousedev_notify_readers",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/rtc/interface.c:rtc_handle_legacy_irq",
        "drivers/pps/kapi.c:pps_event",
        "net/socket.c:sock_wake_async",
        "net/socket.c:sock_wake_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581843414,
      "name": "kill_fasync.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581842304,
      "name": "kill_fasync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kill_fasync(struct fasync_struct * * fp, int sig, int band)
```

```json
{
  "name": "kill_fasync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581896027,
      "name": "kill_fasync",
      "external": true,
      "loc": "fs/fcntl.c:1017",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_wakeup",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:wakeup_pipe_writers",
        "fs/splice.c:wakeup_pipe_readers",
        "fs/notify/notification.c:fsnotify_add_event",
        "fs/io_uring.c:io_commit_cqring",
        "fs/locks.c:lease_break_callback",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_wake_and_unlock",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_write_wakeup",
        "drivers/tty/vt/vc_screen.c:vcs_notifier",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/hpet.c:hpet_interrupt",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/mousedev.c:mousedev_write",
        "drivers/input/mousedev.c:mousedev_notify_readers",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/rtc/interface.c:rtc_handle_legacy_irq",
        "drivers/pps/kapi.c:pps_event",
        "net/socket.c:sock_wake_async",
        "net/socket.c:sock_wake_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581897142,
      "name": "kill_fasync.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581896016,
      "name": "kill_fasync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kill_fasync(struct fasync_struct * * fp, int sig, int band)
```

```json
{
  "name": "kill_fasync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581965620,
      "name": "kill_fasync",
      "external": true,
      "loc": "fs/fcntl.c:1017",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_wakeup",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_release",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read",
        "fs/pipe.c:pipe_read",
        "fs/splice.c:wakeup_pipe_writers",
        "fs/splice.c:wakeup_pipe_readers",
        "fs/notify/notification.c:fsnotify_add_event",
        "fs/io_uring.c:io_commit_cqring",
        "fs/locks.c:lease_break_callback",
        "fs/coredump.c:do_coredump",
        "fs/fuse/dev.c:fuse_abort_conn",
        "fs/fuse/dev.c:fuse_dev_wake_and_unlock",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_special",
        "drivers/tty/n_tty.c:n_tty_write_wakeup",
        "drivers/tty/vt/vc_screen.c:vcs_notifier",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/hpet.c:hpet_interrupt",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/mousedev.c:mousedev_write",
        "drivers/input/mousedev.c:mousedev_notify_readers",
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/rtc/interface.c:rtc_handle_legacy_irq",
        "drivers/pps/kapi.c:pps_event",
        "net/socket.c:sock_wake_async",
        "net/socket.c:sock_wake_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581966774,
      "name": "kill_fasync.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581965600,
      "name": "kill_fasync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
